# data_maning_midterm

# 📊 Data Mining Midterm Assignment

Bu repository, **Data Mining** dersi kapsamında hazırlanmış vize ödevini içermektedir.  
Çalışmada hasta verileri kullanılarak keşifsel veri analizi (EDA), görselleştirme ve temel istatistiksel analizler gerçekleştirilmiştir.

---

## 🧪 Ödev Kapsamı (Assignment Tasks)

### 1️⃣ Sayısal Değişkenler için Temel İstatistikler
Tüm **sayısal sütunlar** için aşağıdaki temel istatistikler hesaplanmıştır:
- Mean  
- Standard Deviation (Std)  
- Minimum (Min)  
- %25 Quantile  
- Median  
- %75 Quantile  
- Maximum (Max)

---

### 2️⃣ Kategorik Değişkenlerin Görselleştirilmesi
Kategorik sütunlar için:
- Her sütun **ayrı ayrı** olacak şekilde  
- **Pasta grafikleri (pie chart)** ile dağılımlar görselleştirilmiştir.

---

### 3️⃣ Hastalık Türüne Göre Tedavi Süresi Analizi
- **Condition** sütunu (hastalık sebebi) ile  
- **Treatment_Duration_days** değişkeni arasındaki ilişki  
- Tüm hastalıklar için **tek bir boxplot** üzerinde gösterilmiştir.

---

### 4️⃣ İlaçlar ve Yan Etkiler için 2 Boyutlu Frekans Analizi
- **Drug_Name** ve **Side_Effects** sütunları kullanılarak  
- **2 boyutlu histogram / frekans görselleştirmesi** oluşturulmuştur.  
- Elde edilen sonuçlar yorumlanmıştır.

---

### 5️⃣ Hiyerarşik Kümeleme (Clustering)
- 4. maddede kullanılan veriler üzerinden  
- **Seaborn `clustermap`** fonksiyonu ile  
- **Hiyerarşik kümeleme analizi** yapılmıştır.  
- Grafik ve sonuçlar **Markdown hücrelerinde yorumlanmıştır**.

---

### 6️⃣ Yaş ve İyileşme Skoru Korelasyonu
- **Age** ve **Improvement_Score** değişkenleri arasındaki  
- **Korelasyon katsayısı** hesaplanmış  
- Sonuç istatistiksel olarak yorumlanmıştır.

---

### 7️⃣ Cinsiyete Göre Hastalık Oranları
- Erkek ve kadınlar için  
- **Condition** değişkeninin dağılımı  
- **Normalize edilmiş** şekilde hesaplanmıştır  
  (Her cinsiyet için toplam olasılık = 1).

---

### 8️⃣ Baş Dönmesi (Dizziness) Yan Etkisi Analizi
- **Dizziness** yan etkisinin raporlandığı ilaçlar belirlenmiştir.  
- Bu ilaçlar **azalan sıklığa göre sıralanmıştır**.

---

### 9️⃣ Metoprolol için Baş Dönmesi Olasılığı
- **Metoprolol** ilacı için raporlanan tüm yan etkiler içinde  
- **Dizziness** yan etkisinin olasılığı hesaplanmıştır.

---

## 🛠️ Kullanılan Kütüphaneler

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

---

## 📁 Proje Dosyaları

- `data_mining_midterm.ipynb` — Analiz ve görselleştirmelerin yapıldığı Notebook  
- `README.md` — Proje açıklaması  
- `data/` — Veri seti (varsa)

---


