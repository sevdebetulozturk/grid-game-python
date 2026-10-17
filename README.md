# Grid Game (Python)

Python ile yazılmış, konsol üzerinde oynanan basit bir 2D tahta oyunu.
Oyuncu (`P`), rastgele yerleştirilmiş engellere (`X`) çarpmadan hedefe (`H`) ulaşmaya çalışır.

## Özellikler

- Boyutu ayarlanabilir kare tahta
- Rastgele yerleştirilen engeller
- Sınır ve engel çarpışma kontrolü
- Hedefe ulaşınca kazanma, engele çarpınca kaybetme
- Geçersiz girişlere karşı kontrol

## Nasıl Çalıştırılır?

Python 3.8 veya üzeri gerekir.

```bash
git clone https://github.com/KULLANICI_ADINIZ/grid-game-python.git
cd grid-game-python
python grid_game.py
```

## Nasıl Oynanır?

| Komut | Anlamı        |
|-------|---------------|
| `h u`   | Yukarı        |
| `h d`   | Aşağı         |
| `h l`   | Sola          |
| `h r`   | Sağa          |
| `çık`   | Oyundan çıkış |

## Örnek Çıktı

2D Simülasyon Oyununa Hoşgeldiniz!
Oyunun başında bir karakter seçeceksiniz.
Hedefe (H) ulaşmaya çalışın, engele (X) çarpmamaya dikkat edin.
Komutlar: hareket için: h + [u/ d/ r/ l], çık
Lütfen bir karakter seçin (Ör: P): P

Oyun Başladı!
P        
         
    X    
        X
X       H

Geçersiz komut! Komutlar: h + [u/ d/ r/ l], çık

(Engellerin yeri her çalıştırmada değişir.)

## Kullanılan Kavramlar

- Fonksiyonlar ve modüler kod yapısı
- İki boyutlu listeler (list of lists)
- İç içe döngüler ve koşullar
- `random` modülü ile rastgele engel yerleştirme
- Kullanıcıdan girdi alma ve girdi doğrulama
- Sınır ve çarpışma kontrolü

## Bilinen Eksikler

Bu proje ilk yazılım dersinde öğrenme amacıyla yazıldı ve bazı eksikleri var:

- Engeller bazen hedefe giden yolu tamamen kapatabilir, bu durumda oyun kazanılamaz.
- Engele çarpıldığında oyuncu tahtada çarpışma noktasına taşınmıyor.
- Giriş filtreleme basit tutuldu (ör. birden fazla harf girilirse ilk geçerli harf alınıyor).

## Geliştirme Fikirleri

- [ ] Engellerin hedefi kapatmamasını sağlamak (yol bulma algoritması)
- [ ] Zorluk seviyeleri
- [ ] Renkli çıktı veya grafik arayüz (pygame / tkinter)

## Hakkında

Bu proje Gebze Teknik Üniversitesi Elektronik Mühendisliği INF212 dersi kapsamında geliştirilmiştir.
