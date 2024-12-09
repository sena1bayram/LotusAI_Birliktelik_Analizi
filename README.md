# 🛒 Alışverişte Gizli İlişkileri Keşfet! 🛍️

## 🎯 Giriş
Bu proje, **Groceries Dataset** kullanarak alışveriş sepetindeki ürünler arasındaki gizli ilişkileri keşfetmek için tasarlandı. 🎉 Veri seti, alışveriş yapan kişilerin **müşteri numarası (Member_number)**, **tarih (Date)** ve **ürün açıklamaları (itemDescription)** gibi bilgilerini içeriyor. Amacımız, **müşteri davranışlarını** anlamak ve **cross-selling** fırsatlarını ortaya çıkarmak! 🛍️💡

---

## 🤔 Birliktelik Analizi Nedir?
**Birliktelik analizi**, müşterilerin bir ürün aldığında başka hangi ürünleri alma olasılığının yüksek olduğunu keşfetmek için kullanılır. Bu analizde kullandığımız metrikler şunlardır:

- **🔢 Destek (Support):** Ürün ya da ürün gruplarının toplam alışverişler içerisindeki görünme sıklığı.
- **✅ Güven (Confidence):** Bir ürünün başka bir ürünü tahmin etme doğruluğu.
- **📈 Lift:** Ürünlerin birlikte alım oranının, bağımsız alımlara göre ne kadar yüksek olduğunu gösterir. Lift > 1 olduğunda, güçlü bir ilişki vardır.

---

## 🚀 Hiperparametre Optimizasyonu
Projede, **Grid Search** yöntemiyle **min_support** (minimum destek) ve **min_threshold** (minimum güven) değerleri optimize edilmiştir. 🔍 Farklı parametre kombinasyonları denenmiş ve en yüksek **lift** değerine sahip kurallar seçilmiştir. 💪 Optimizasyon süreci, anlamlı ürün kombinasyonlarının bulunmasını kolaylaştırdı ve sonuçları daha güçlü hale getirdi. 🏆

---

## 📊 Görselleştirme
Sonuçlarımızı daha anlamlı ve görsel hale getirmek için aşağıdaki yöntemleri kullandık:

1. **🎨 Destek, Güven ve Lift Dağılımı (Scatter Plot):**
   - **Seaborn** kütüphanesi ile oluşturulan bu grafik, kuralların **destek** ve **güven** değerlerini görselleştirir. Lift değerleri, **nokta boyutlarıyla** vurgulanır. Güçlü ilişkiler göz kamaştırıyor! 🌟

2. **🕸️ Kural Ağı (Association Rule Network):**
   - **NetworkX** ile oluşturulan bu ağ, ürünler arasındaki ilişkileri bir harita gibi görselleştirir. 🗺️ Kenarların kalınlığı, **lift** değerine bağlıdır ve güçlü ilişkileri hemen fark etmenizi sağlar! 🔗✨

---

## 🏁 Sonuç
Bu proje ile ürünler arasındaki **gizli ilişkiler** ortaya çıkarıldı ve **cross-selling stratejileri** için önemli bilgiler sağlandı. 🛒💬 Yüksek **lift** ve **confidence** değerine sahip kurallar, pazarlama kararlarında yol gösterici olacaktır. 📊

![image](https://github.com/user-attachments/assets/f617dfbe-687c-4d57-a3fd-1328d877c7a5)

![image](https://github.com/user-attachments/assets/c61c577a-88c3-42be-a6fe-9a596132d212)


---

## 📂 Dosyalar
Detaylı analiz ve kodlar için şu dosyaya göz atabilirsiniz:
- [Birliktelik Kural Analizi.pdf](Birliktelik%20Kural%20Analizi.pdf)

---

> 💡 **Not:** Bu analiz sayesinde müşterilerinizi daha iyi anlayabilir, satışlarınızı artıracak stratejik adımlar atabilirsiniz! 🚀
