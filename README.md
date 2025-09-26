# 📌 İşaret Dili Tanıma Projesi

## 📖 Giriş
Bu projede **işaret dili veri seti** ile çalıştım.  
Amaç, görüntüler üzerinden işaret dilindeki harfleri/simgeleri tanıyabilen bir **makine öğrenmesi / derin öğrenme modeli** geliştirmekti.  

Kullandığım yöntemler:  
- CNN (Convolutional Neural Networks)  
- Veri artırma (data augmentation)  
- Model performansını artırmak için farklı katman ve parametre denemeleri  

Notebook dosyalarında, hem kod hem de markdown hücreleri ile proje sürecini adım adım açıkladım.  

---

## ⚙️ Teknik Anlatım
Notebook içerisinde şu adımlar işlendi:  
1. **Veri Ön İşleme** – Görsellerin yeniden boyutlandırılması, normalizasyon, eğitim/test ayrımı  
2. **Keşifsel Veri Analizi (EDA)** – Örnek görsellerin incelenmesi, sınıf dağılımı  
3. **Modelleme** – CNN tabanlı derin öğrenme mimarisi kullanıldı  
4. **Değerlendirme** – Eğitim / doğrulama doğrulukları ve kayıpları incelendi  

Her notebook içerisinde teknik detayları markdown hücrelerinde açıkladım.  

---

## 📊 Metrikler ve Sonuçlar
Projede kullanılan metrikler:  
- Accuracy  
- Loss grafikleri  
- Confusion Matrix ile sınıf bazlı performans  

Elde edilen sonuçlar:  
- CNN modeli ile test setinde %... başarı elde edildi  

Sonuçların yorumu:  
- CNN, görsel verilerde en iyi sonucu verdi  
- Daha derin ağlar ile doğruluk artırılabilir  

---

## 🔮 Sonuç ve Gelecek Çalışmalar
Bu projede işaret dili tanıma için temel bir CNN modeli geliştirildi.  
Gelecekte şu geliştirmeler yapılabilir:  
- Daha büyük / farklı dillerden veri setleri ile çalışma  
- Transfer Learning (ör. ResNet, EfficientNet) ile doğruluk artırma  
- Gerçek zamanlı kamera entegrasyonu ile işaret dili tanıma  
- Mobil uygulama veya web arayüzü ekleme  
- Modelin bulut ortamına (AWS, GCP, Azure) deploy edilmesi  

---

Linkler

https://www.kaggle.com/code/vedatkoylahisar/sign-language
