# StudyBuddy AI: Yapay Zeka Destekli Mobil Öğrenme Asistanı 🎓🤖

> **Bu proje, TÜBİTAK 2209-A Üniversite Öğrencileri Araştırma Projeleri Destekleme Programı formatına ve akademik standartlara uygun olarak geliştirilmiştir.**

StudyBuddy AI, geleneksel öğrenme metodolojilerini modern yapay zeka (AI) ve görüntü işleme (OCR) teknolojileriyle birleştiren, Android platformu tabanlı bir eğitim teknolojisi (EdTech) projesidir. Projenin temel amacı, statik ders materyallerini dinamik ve etkileşimli birer öğrenme aracına dönüştürerek öğrenci verimliliğini artırmaktır.

## 🎯 Projenin Özgün Değeri
Mevcut not tutma uygulamalarının aksine StudyBuddy AI, içeriği sadece saklamaz; **Semantik Analiz** yöntemlerini kullanarak anlamlandırır. 
- **Bilişsel Yükün Azaltılması:** Karmaşık notlardan otomatik özet çıkarımı.
- **Aktif Geri Bildirim:** Not içeriklerinden yapay zeka ile otomatik soru (Quiz) üretimi.
- **Erişilebilirlik:** Fiziksel el yazısı notların **Google ML Kit** ile yüksek doğrulukla dijitalleştirilmesi.

## 🛠 Teknik Mimari ve Metodoloji
Proje, sürdürülebilirlik ve test edilebilirlik için **MVVM (Model-View-ViewModel)** mimarisi üzerine inşa edilmiştir.

- **Frontend:** Kotlin / Jetpack Compose (Modern Android UI)
- **Görüntü İşleme:** Google ML Kit (On-device Text Recognition) & CameraX
- **Zeka Katmanı:** Google Gemini API (NLP & İçerik Analizi)
- **Backend & Veri Yönetimi:** Firebase Firestore (NoSQL), Firebase Auth & Cloud Storage
- **Ağ Yönetimi:** Retrofit & OkHttp (REST API entegrasyonu)

## 📋 Proje İş Paketleri (TÜBİTAK Zaman Çizelgesi)
1. **İP1: Analiz ve Tasarım:** Literatür taraması ve UI/UX prototiplerinin oluşturulması.
2. **İP2: Altyapı Kurulumu:** Firebase servislerinin ve API anahtarlarının konfigüre edilmesi.
3. **İP3: Görüntü İşleme Modülü:** OCR motorunun entegrasyonu ve metin parse işlemleri.
4. **İP4: AI Entegrasyonu:** LLM modelleri ile özetleme ve soru üretme algoritmalarının kodlanması.
5. **İP5: Test ve Raporlama:** Kullanıcı kabul testleri ve nihai akademik raporun hazırlanması.

## 🚀 Kurulum ve Çalıştırma
1. Bu depoyu klonlayın: `git clone https://github.com/kullaniciadi/StudyBuddyAI.git`
2. Android Studio (Ladybug veya güncel sürüm) ile projeyi açın.
3. `google-services.json` dosyasını `app/` dizinine ekleyin.
4. `local.properties` dosyasına API Key tanımlamalarınızı yapın.
5. Projeyi bir emülatör veya fiziksel cihazda çalıştırın.

---
## 📝 Akademik Beyan
Bu çalışma, Mobil Programlama dersi kapsamında bir araştırma projesi önerisi olarak sunulmuştur. Projenin tüm dökümantasyonu TÜBİTAK 2209-A rehberindeki bilimsel etik ve metodoloji kuralları gözetilerek hazırlanmıştır.

**Geliştirici:** [Umut Can Durmuş]  
**Danışman:** [Mehmet Tekerek]
