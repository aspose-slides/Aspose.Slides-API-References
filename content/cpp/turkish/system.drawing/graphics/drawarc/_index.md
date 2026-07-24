---
title: DrawArc()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen kalemi kullanarak, geçerli nesne tarafından temsil edilen yüzeyde belirtilen yayı çizer.
type: docs
weight: 248
url: /tr/system.drawing/graphics/drawarc/
---
## Graphics::DrawArc(const SharedPtr\<Pen\>\&, int32_t, int32_t, int32_t, int32_t, int32_t, int32_t) metod

Belirtilen kalemi kullanarak, geçerli nesne tarafından temsil edilen yüzeyde belirtilen yayı çizer.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, int32_t x, int32_t y, int32_t width, int32_t height, int32_t startAngle, int32_t sweepAngle)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Arcı çizerken kullanılacak bir pen |
| x | **int32_t** | Elipsi tanımlayan dikdörtgenin sol üst köşesinin X koordinatı |
| y | **int32_t** | Elipsi tanımlayan dikdörtgenin sol üst köşesinin Y koordinatı |
| width | **int32_t** | Elipsi tanımlayan dikdörtgenin genişliği |
| height | **int32_t** | Elipsi tanımlayan dikdörtgenin yüksekliği |
| startAngle | **int32_t** | X ekseninden yayının başlangıç noktasına saat yönünde ölçülen açı (derece) |
| sweepAngle | **int32_t** | **startAngle**'den yayının bitiş noktasına saat yönünde ölçülen açı (derece) |

## Graphics::DrawArc(const SharedPtr\<Pen\>\&, float, float, float, float, float, float) metod

Belirtilen kalemi kullanarak, geçerli nesne tarafından temsil edilen yüzeyde belirtilen yayı çizer.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Arcı çizerken kullanılacak bir pen |
| x | **float** | Elipsi tanımlayan dikdörtgenin sol üst köşesinin X koordinatı |
| y | **float** | Elipsi tanımlayan dikdörtgenin sol üst köşesinin Y koordinatı |
| width | **float** | Elipsi tanımlayan dikdörtgenin genişliği |
| height | **float** | Elipsi tanımlayan dikdörtgenin yüksekliği |
| startAngle | **float** | X ekseninden yayının başlangıç noktasına saat yönünde ölçülen açı (derece) |
| sweepAngle | **float** | **startAngle**'den yayının bitiş noktasına saat yönünde ölçülen açı (derece) |

## Graphics::DrawArc(const SharedPtr\<Pen\>\&, Rectangle, float, float) metod

Belirtilen kalemi kullanarak, geçerli nesne tarafından temsil edilen yüzeyde belirtilen yayı çizer.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, Rectangle rect, float startAngle, float sweepAngle)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Arcı çizerken kullanılacak bir pen |
| rect | [Rectangle](../../rectangle/) | Elipsi tanımlayan dikdörtgen |
| startAngle | **float** | X ekseninden yayının başlangıç noktasına saat yönünde ölçülen açı (derece) |
| sweepAngle | **float** | **startAngle**'den yayının bitiş noktasına saat yönünde ölçülen açı (derece) |

## Graphics::DrawArc(const SharedPtr\<Pen\>\&, RectangleF, float, float) metod

Belirtilen kalemi kullanarak, geçerli nesne tarafından temsil edilen yüzeyde belirtilen yayı çizer.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, RectangleF rect, float startAngle, float sweepAngle)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Arcı çizerken kullanılacak bir pen |
| rect | [RectangleF](../../rectanglef/) | Elipsi tanımlayan dikdörtgen |
| startAngle | **float** | X ekseninden yayının başlangıç noktasına saat yönünde ölçülen açı (derece) |
| sweepAngle | **float** | **startAngle**'den yayının bitiş noktasına saat yönünde ölçülen açı (derece) |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Pen](../../pen/)
* Sınıf [Graphics](../)
* Sınıf [Rectangle](../../rectangle/)
* Sınıf [RectangleF](../../rectanglef/)
* Ad alanı [System::Drawing](../../)
* Kütüphane [Aspose.Slides](../../../)