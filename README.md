# Linux_Learning
Linux command

# Linux Komutları Notları

## Genel Notlar
- `~` (Tilda): **home/seyma** dizinini ifade eder.
- `pwd`: **Print Working Directory** - Bulunduğunuz klasörü yazdırır.
- `ls`: **List** - Klasör içeriğini listeler.
- `cd`: **Change Directory** - Klasör değiştirir.
  - `cd Desktop`: Desktop klasörüne geçiş yapar (büyük-küçük harfe dikkat!).
  - `cd ..`: Bir üst klasöre geçer.
- `clear`: Yazdığınız komutları temizler.
- `cd Dow` ardından `TAB`: Dizin ismini otomatik tamamlar. Ancak, aynı harflerle başlayan birden fazla dizin varsa tamamlamaz, bir harf daha ekleyin.
- **Yukarı ok tuşu**: Daha önce yazdığınız komutları görüntüler. Her basışta bir önceki komut gelir.

---

## Dosya ve Klasör İşlemleri
- `touch linux.txt`: **linux.txt** adında bir dosya oluşturur.
- `echo "iyiki linux öğreniyorum" > linux.txt`: Dosyaya metin yazar (var olan içeriği siler).
- `cat linux.txt`: Dosyanın içeriğini görüntüler.
- `echo "iyi ki linux öğreniyorum ne güzel" >> linux.txt`: Dosyanın mevcut içeriğinin sonuna metin ekler.
- `ls > sonyazidosyasi.txt`: **ls** komutunun çıktısını bir dosyaya aktarır.
  - `cat sonyazidosyasi.txt`: Dosyanın içeriğini görüntüler.
- `rm linux.txt`: Dosyayı siler. (Ancak, klasör silmek için hata alır.)
- `cp linux.txt seyma`: Dosyayı başka bir klasöre kopyalar.
- `mv linux.txt seyma`: Dosyayı başka bir klasöre taşır.
- `mv linux2.txt linux3.txt`: Dosyanın ismini değiştirir.
- `mkdir yeniklasor`: Yeni bir klasör oluşturur.
- `rm -r yeniklasor/`: Klasörü ve içeriğini siler.

---

### Ek Notlar
- **Mavi renkte gözükenler klasördür.**
- Bir klasörü başka bir klasöre kopyalamak için: `cp -r`.




### Tilda (~) home/seyma dizinini ifade eder.
### Bulunduğunuz klasörü yazdırma
pwd

### Klasör içeriğini listeleme
ls

### Klasör değiştirme
cd Desktop      # Desktop klasörüne geçer.
cd ..           # Bir üst klasöre çıkar.

### Komut ekranını temizleme
clear

### Dizin otomatik tamamlama
cd Dow[TAB]

### Yukarı ok tuşu ile geçmiş komutları görüntüleme

### Dosya işlemleri
touch linux.txt                               # Yeni bir dosya oluşturma
echo "iyiki linux öğreniyorum" > linux.txt    # Dosyaya metin yazma
cat linux.txt                                 # Dosya içeriğini görme
echo "iyi ki linux öğreniyorum ne güzel" >> linux.txt  # Dosyanın sonuna metin ekleme

### Listeleme çıktısını dosyaya kaydetme
ls > sonyazidosyasi.txt
cat sonyazidosyasi.txt                        # Dosya içeriğini görüntüleme

### Dosya silme
rm linux.txt

### Kopyalama ve taşıma işlemleri
cp linux.txt seyma                            # Kopyalama
mv linux.txt seyma                            # Taşıma
mv linux2.txt linux3.txt                      # Yeniden adlandırma

### Klasör oluşturma ve silme
mkdir yeniklasor                              # Yeni klasör oluşturma
rm -r yeniklasor/                             # Klasörü silme

### Klasörleri kopyalama
cp -r klasor1 klasor2                         # Klasörleri kopyalama
