# BusinessOS POS

BusinessOS yönetim paneliyle aynı Supabase projesini kullanan ayrı POS ve stok panelidir.

## Kurulum

1. `supabase-config.example.js` dosyasını `supabase-config.js` olarak kopyalayın.
2. Yönetim panelindeki Supabase URL ve public anon key değerlerini girin.
3. `supabase-pos-schema.sql` dosyasını Supabase SQL Editor’da çalıştırın.
4. `index.html` dosyasını statik site olarak Render’a deploy edin.

İlk sürümde kart ödemesi `pending` olarak kaydedilir; işletme sahibi fiziksel POS cihazında ödemeyi alır. Gerçek cihaz entegrasyonu seçilecek POS sağlayıcısının API/SDK’sına göre ayrıca yapılır.
