---
title: Point()
second_title: Aspose.Slides for C++ API Referansı
description: Yeni bir Point nesnesi oluşturur ve X ve Y koordinat değerlerini 0 ile başlatır.
type: docs
weight: 1
url: /tr/system.drawing/point/point/
---
## Point::Point() yapıcı

[Point](../) nesnesini oluşturur ve X ve Y koordinat değerlerini 0 ile başlatır.

```cpp
System::Drawing::Point::Point()
```

## Point::Point(int, int) yapıcı

[Point](../) nesnesini oluşturur ve belirtilen değerlerle başlatır.

```cpp
System::Drawing::Point::Point(int x, int y)
```

### Argumentler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | int | X koordinatının değeri |
| y | int | Y koordinatının değeri |

## Point::Point(const Size\&) yapıcı

[Point](../) nesnesini oluşturur ve X ve Y koordinat değerlerini ilgili [SizeF](../../sizef/) nesnesinin genişlik ve yükseklik değerleriyle sırasıyla başlatır.

```cpp
System::Drawing::Point::Point(const Size &size)
```

### Argumentler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| size | const [Size](../../size/)\& | Oluşturulan [Point](../) nesnesinin X ve Y koordinat değerlerini başlatmak için kullanılan genişlik ve yükseklik değerlerine sahip bir [SizeF](../../sizef/) nesnesi |

## Point::Point(int) yapıcı

[Point](../) nesnesini oluşturur ve X koordinat değerini belirtilen 32-bit tam sayının yüksek 16 bitinden, Y koordinat değerini ise belirtilen 32-bit tam sayının düşük 16 bitinden oluşan değerle başlatır.

```cpp
System::Drawing::Point::Point(int dw)
```

### Argumentler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dw | int | Oluşturulan nesnenin X koordinat değerini belirleyen yüksek 16 biti ve Y koordinat değerini belirleyen düşük 16 biti içeren 32-bit tam sayı değeri |

## İlgili

* Sınıf [Point](../)
* Sınıf [Size](../../size/)
* Ad Alanı [System::Drawing](../../)
* Kütüphane [Aspose.Slides](../../../)