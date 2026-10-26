---
title: Rectangle()
second_title: Aspose.Slides for C++ API Referansı
description: X ve Y koordinatları ile genişlik ve yükseklik değerleri 0 olarak ayarlanmış bir dikdörtgeni temsil eden Rectangle nesnesinin yeni bir örneğini oluşturur.
type: docs
weight: 1
url: /tr/system.drawing/rectangle/rectangle/
---
## Rectangle::Rectangle() yapıcı

X ve Y koordinatları ile genişlik ve yükseklik değerleri 0 olarak ayarlanmış bir dikdörtgeni temsil eden [Rectangle](../) nesnesinin yeni bir örneğini oluşturur.

```cpp
System::Drawing::Rectangle::Rectangle()
```

## Rectangle::Rectangle(int, int, int, int) yapıcı

[Rectangle](../) nesnesinin yeni bir örneğini oluşturur; bu nesne belirtilen sol üst köşe koordinatları ile genişlik ve yüksekliği olan bir dikdörtgeni temsil eder.

```cpp
System::Drawing::Rectangle::Rectangle(int x, int y, int width, int height)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | int | Dikdörtgenin sol üst köşesinin X koordinatının bir değeri |
| y | int | Dikdörtgenin sol üst köşesinin Y koordinatının bir değeri |
| width | int | Dikdörtgenin genişliği |
| height | int | Dikdörtgenin yüksekliği |

## Rectangle::Rectangle(const Point\&, const Size\&) yapıcı

[Rectangle](../) nesnesinin yeni bir örneğini oluşturur; bu nesne, sol üst köşe koordinatları [Point](../../point/) sınıfının bir örneğiyle ve genişlik ve yükseklik [Size](../../size/) sınıfının bir örneğiyle belirtilen bir dikdörtgeni temsil eder.

```cpp
System::Drawing::Rectangle::Rectangle(const Point &location, const Size &size)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| location | const [Point](../../point/)\& | Dikdörtgenin sol üst köşesinin konumunu belirtir |
| size | const [Size](../../size/)\& | Dikdörtgenin genişliğini ve yüksekliğini belirtir |

## Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle\_&) yapıcı

[Rectangle](../) nesnesinin yeni bir örneğini oluşturur; bu nesne belirtilen dikdörtgen ile eşdeğer bir dikdörtgeni temsil eder.

```cpp
System::Drawing::Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle_ &rect)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | const **System::Windows::Forms::Screen::Rectangle_**\& | **System::Windows::Forms::Screen::Rectangle_** sınıfının bir örneği; oluşturulan nesnenin temsil edeceği dikdörtgenin konumunu ve boyutunu belirtir |

## İlgili

* Sınıf [Rectangle](../)
* Sınıf [Point](../../point/)
* Sınıf [Size](../../size/)
* Ad Alanı [System::Drawing](../../)
* Kütüphane [Aspose.Slides](../../../)