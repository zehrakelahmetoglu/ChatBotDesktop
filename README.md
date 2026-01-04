🤖 **GroqSharp: Ultra-Fast C# Desktop Chatbot**
GroqSharp, C# Windows Forms mimarisi üzerine inşa edilmiş, dünyanın en hızlı çıkarım motoru olan Groq LPU™ teknolojisini kullanan modern bir masaüstü yapay zeka asistanıdır. Bu uygulama, bulut tabanlı bir LLM (Large Language Model) ile yerel bir masaüstü arayüzünü kusursuz bir şekilde birleştirir.

✨ **Öne Çıkan Özellikler**
  ⚡ Işık Hızında Yanıtlar: Groq'un özel donanımı sayesinde saniyede yüzlerce kelime (token) üretim hızı.

  🧠 Zeki Modeller: Meta'nın en gelişmiş açık kaynaklı modeli olan llama-3.3-70b-versatile entegrasyonu.

  🌐 Kesintisiz İletişim: HttpClient ve JSON tabanlı asenkron veri transferi.

  🛡️ Güvenli Mimari: async/await yapısı ile ana iş parçacığını (UI thread) dondurmadan arka planda işlem yapma.

  📉 Düşük Kaynak Tüketimi: Model bulutta çalıştığı için düşük donanımlı bilgisayarlarda bile yüksek performans.

🛠️**Teknik Altyapı**
Dil: C# (.NET Framework / .NET 8.0)

Arayüz: Windows Forms (WinForms)

Veri İşleme: Newtonsoft.Json

API Sağlayıcı: Groq Cloud

🚀 **Hızlı Başlangıç**
1. Hazırlık
Visual Studio üzerinde Newtonsoft.Json NuGet paketini projenize dahil edin.

2. API Yapılandırması
Groq Console üzerinden ücretsiz bir API anahtarı alın ve koddaki ilgili alana yapıştırın:

C#

private const string ApiKey = "gsk_your_api_key_here";
3. Derleme
Projeyi F5 ile başlatın ve yapay zeka ile sohbet etmeye başlayın!

📋 **Proje Yapısı**
Form1.cs: Ana uygulama mantığı ve API haberleşmesi.

Form1.Designer.cs: Görsel bileşenlerin (TextBox, Button, ListBox) tanımları.

App.config: Uygulama yapılandırma ayarları.
