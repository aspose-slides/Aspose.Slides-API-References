---
title: RectangleF()
second_title: C++ için Aspose.Slides API Referansı
description: RectangleF nesnesinin yeni bir örneğini oluşturur; bu nesne, X ve Y koordinatları ile genişlik ve yükseklik değerleri 0 olarak ayarlanmış bir dikdörtgeni temsil eder.
type: docs
weight: 1
url: /tr/system.drawing/rectanglef/rectanglef/
---
## RectangleF::RectangleF() yapıcı

Constructs a new instance of [RectangleF](../) object that represents a rectangle with X and Y coordinates and width and hegiht values set to 0.

```cpp
System::Drawing::RectangleF::RectangleF()
```

## RectangleF::RectangleF(float, float, float, float) yapıcı

Constructs a new instance of [RectangleF](../) object that represents a rectangle with the specified coordinates of its upper left corner and width and height.

```cpp
System::Drawing::RectangleF::RectangleF(float x, float y, float width, float height)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | **float** | Dikdörtgenin sol üst köşe X koordinatının bir değeri |
| y | **float** | Dikdörtgenin sol üst köşe Y koordinatının bir değeri |
| width | **float** | Dikdörtgenin genişliği |
| height | **float** | Dikdörtgenin yüksekliği |

## RectangleF::RectangleF(const PointF&, const SizeF&) yapıcı

Constructs a new instance of [RectangleF](../) object that represents a rectangle with the coordinates of its upper left corner specified as an instance of [PointF](../../pointf/) class and its width and height as an instance of [SizeF](../../sizef/) class.

```cpp
System::Drawing::RectangleF::RectangleF(const PointF &location, const SizeF &size)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| location | const [PointF](../../pointf/)\& | Dikdörtgenin sol üst köşe konumunu belirtir |
| size | const [SizeF](../../sizef/)\& | Dikdörtgenin genişliğini ve hegihtini belirtir |

## RectangleF::RectangleF(const Rectangle&) yapıcı

Constructs a new instance of [RectangleF](../) object that represents the rectangle equivalent to the specified one.

```cpp
System::Drawing::RectangleF::RectangleF(const Rectangle &rect)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | [Rectangle](../../rectangle/) sınıfının, oluşturulan nesne tarafından temsil edilecek dikdörtgenin konumunu ve boyutunu belirten bir örneği |

## Ayrıca Bakınız

* Sınıf [RectangleF](../)
* Sınıf [PointF](../../pointf/)
* Sınıf [SizeF](../../sizef/)
* Sınıf [Rectangle](../../rectangle/)
* AdAlanı [System::Drawing](../../)
* Kütüphane [Aspose.Slides](../../../)