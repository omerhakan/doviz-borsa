# Doviz Borsa Widget

Türkiye piyasalarında ki döviz ve borsayı izlemek için Rainmeter eklentisi

![Widget Preview](http://www.omerhakan.net/doviz-borsa-widget.png)

### Özellikler:

 * Avro, dolar, gram altın ve BIST 100'ü gösterir
 * Takip etmek istediğiniz kur veya hisseyi ekleyebilirsiniz (Kur - Hisse Yönetmek bölümüne bakabilirsiniz)
 * 5 dakikada bir güncellenir
 * İlgili sayfaya ulaşmak için kur veya hissenin ismine tıklayın

# Gereklilikler
 * [Rainmeter 4.1+](https://www.rainmeter.net)
 * [Win10Widgets](http://win10widgets.com) - stiller bu temadan alınıyor

# Yükleme

 1. [Rainmeter 4.1+](https://www.rainmeter.net) ve [Win10Widgets](http://win10widgets.com) yükleyin
 2. Bilgisayarınızda `C:\Users\[MY_USER]\Documents\Rainmeter\Skins\Win10 Widgets` klasörüne gidin ve `Doviz Borsa` isminde yeni bir klasör oluşturun
 3. https://github.com/omerhakan/doviz-borsa adresinden zip dosyasını çekin ve içeriğini yukarıda oluşturduğunuz klasörün içine koyun
 4. Rainmeter'dan ekleyin
 
# Kur - Hisse Yönetmek

Her bölüm aşağıdaki şekilde isim ve ayıraçla başlar

```
# Euro (EUR)__________________________________________________________________
```
 
### Kur - Hisse Kaldırmak

 1. Silmek istediğiniz kur veya hissenin alanını bulun
 2. Alanı silin
 3. Diğer kur veya hisselerin satır numarasını güncelleyin. `Y=(#TopPadding#+(#RowHeight#*4))` alanındaki `4` satır numarasını gösterir.

### Yeni Kur - Hisse Eklemek

 1. Kur veya hisse alanını kopyalayın
 2. Kur veya hissenin adını ve gerekli linklerini düzeltin (gerekli bilgi ve linkler [Doviz.com API](https://github.com/prosman/dovizcom-api) adresinde bulunuyor)
 3. Satır numarasını güncelleyin. `Y=(#TopPadding#+(#RowHeight#*4))` alanındaki `4` satır numarasını gösterir.
 
  > Eğer daha fazla sayıda Kur - Hisse ekleyecekseniz dosyanın `[Variables]` alanındaki `BackgroundHeight=160` değişkeni artırın.

Not: Fikir Ben Kuhl'ın (https://github.com/bkuhl) Cryptometer(https://github.com/bkuhl/cryptometer) isimli aracına aittir. Tüm övgüler onun.

Note: I got this idea from Cryptometer(https://github.com/bkuhl/cryptometer) - Ben Kuhl (https://github.com/bkuhl), so all credit goes to him.