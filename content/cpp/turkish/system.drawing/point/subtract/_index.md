---  
title: Subtract()  
second_title: Aspose.Slides for C++ API Referansı  
description: Belirtilen Size nesnesinin genişlik ve yükseklik değerlerini, belirtilen Point nesnesinin X ve Y koordinat değerlerinden sırasıyla çıkarır.  
type: docs  
weight: 196  
url: /tr/system.drawing/point/subtract/  
---
## Point::Subtract(const Point\&, const Size\&) metod

Belirtilen [Size](../../size/) nesnesinin genişlik ve yükseklik değerlerini, belirtilen [Point](../) nesnesinin X ve Y koordinat değerlerinden sırasıyla çıkarır.

```cpp
static Point System::Drawing::Point::Subtract(const Point &point, const Size &size)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | const [Point](../)\& | Çevrilecek nokta |
| size | const [Size](../../size/)\& | Koordinat değerlerinden **point** için çıkartılacak değerleri belirten [Size](../../size/) nesnesi |

### Dönüş Değeri

Yeni bir [Point](../) nesnesi; X koordinat değeri, **size**'ın genişlik değerinin **point**'ın X koordinat değerinden çıkarılması sonucu elde edilen değerle, Y koordinat değeri ise **size**'ın yükseklik değerinin **point**'ın Y koordinat değerinden çıkarılması sonucu elde edilen değerle eşittir.

## İlgili

* Sınıf [Point](../)
* Sınıf [Size](../../size/)
* Ad Alanı [System::Drawing](../../)
* Kütüphane [Aspose.Slides](../../../)