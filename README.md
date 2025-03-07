# Card_Fraud_Detection
# 🚀 Credit Card Fraud Detection - Kredi Kartı Dolandırıcılığı Tespiti

Bu proje, kredi kartı işlemlerinde **fraud (dolandırıcılık) tespit etmek** amacıyla geliştirilmiştir.  
Gerçek dünya kredi kartı verileri kullanılarak, **makine öğrenmesi ile dolandırıcılık işlemlerinin otomatik olarak tespit edilmesi** hedeflenmiştir.

## 📊 Kullanılan Yöntemler:
✅ **EDA (Keşifsel Veri Analizi)** → Veri seti incelenerek fraud işlemlerinin özellikleri analiz edildi.  
✅ **Dengesiz Veri Problemi (Imbalanced Data)** → Fraud işlemler oldukça az olduğu için **SMOTE yöntemi** ile veri dengelendi.  
✅ **Makine Öğrenmesi Modelleri** → **Random Forest ve XGBoost** modelleri eğitildi ve karşılaştırıldı.  
✅ **Performans Değerlendirme** → Precision, Recall, F1-Score gibi metriklerle modellerin başarısı ölçüldü.  
✅ **Threshold Optimizasyonu** → Fraud işlemleri daha iyi yakalamak için uygun eşik değeri belirlendi.  
 

## 🔍 Veri Seti:
Veri seti, **kredi kartı işlemleri** içerir ve her işlem için anonimleştirilmiş 28 farklı özellik (V1-V28) ile işlem tutarı (**Amount**) gibi değişkenleri barındırır.  

## 🎯 Sonuç ve Gelecekteki Geliştirmeler:
✅ Model, fraud işlemleri büyük oranda doğru tespit edebilmektedir.  
✅ Daha büyük veri setleriyle modelin başarısı artırılabilir.  
✅ Gerçek zamanlı fraud tespiti için **API veya Dashboard** geliştirilebilir.  

📌 **Veri Seti:**  
Bu projede kullanılan veri setine aşağıdaki linkten ulaşabilirsiniz:  
🔗 [Kaggle Veri Seti](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)  



