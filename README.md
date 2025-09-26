# Derin Öğrenme ile Spor Görselleri Sınıflandırma



---

## 📌 Giriş
Bu projede, **Kaggle Sports Classification** veri seti kullanılarak farklı spor dallarına ait görseller sınıflandırılmıştır.  

- **Model:** EfficientNetB0 (ImageNet önceden eğitilmiş ağırlıklarıyla transfer learning)  
- **Veri artırma:** ImageDataGenerator ile dönüşler, kaydırmalar, parlaklık değişiklikleri, zoom ve flip işlemleri  
- **Değerlendirme:** Eğitim/Doğrulama/Test ayrımı  
- **Ek Analizler:** Confusion Matrix, Classification Report, Grad-CAM görselleştirmeleri  

Projenin teknik anlatımı notebook içerisinde markdown hücrelerinde yapılmıştır.

---

## 📊 Metrikler
Model eğitimi sonunda aşağıdaki sonuçlar elde edilmiştir:

- **Eğitim / Doğrulama Eğrileri:** Accuracy ve Loss grafiklerle karşılaştırıldı.  
- **Test Sonucu:** Test accuracy ve test loss raporlandı.  
- **Classification Report:** Precision, recall, f1-score değerleri sınıf bazlı çıkarıldı.  
- **Confusion Matrix:** İlk 20 sınıf için detaylı hata analizi yapıldı.  
- **Grad-CAM:** Modelin hangi bölgelerden öğrenme yaptığı görselleştirildi.  

Bu sonuçlar, modelin spor görsellerini başarılı şekilde ayırt edebildiğini göstermektedir.

---

## 🛠️ Ekler
Proje kapsamında ayrıca:  

- **TensorBoard** entegrasyonu ile eğitim süreci canlı takip edilmiştir.  
- **Class Weighting** ile dengesiz sınıflar için ağırlıklandırma yapılmıştır.  
- **Hyperparameter Tuning (Keras Tuner)** ile dense layer boyutu, dropout oranı ve learning rate için en iyi değerler aranmıştır.  
- **Grad-CAM** ile görselleştirme eklenmiştir.  


---

## 🚀 Sonuç ve Gelecek Çalışmalar
Bu proje, EfficientNetB0 tabanlı transfer learning ile spor görsellerinin sınıflandırılabileceğini göstermiştir.  

Gelecek çalışmalar için:  
- Daha derin EfficientNet varyantları (B3, B4 vb.) denenebilir.  
- Veri seti artırılabilir veya gerçek zamanlı veri toplanabilir.  
- Model, **mobil cihazlara deploy** edilebilir.  
- **Streamlit / Flask** tabanlı bir kullanıcı arayüzü eklenerek son kullanıcıya sunulabilir.  

---

## Linkler

https://www.kaggle.com/code/semihkantar/derin-ogrenme
https://www.kaggle.com/datasets/gpiosenka/sports-classification
