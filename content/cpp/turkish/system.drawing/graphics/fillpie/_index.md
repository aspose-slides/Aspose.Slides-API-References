---
title: FillPie()
second_title: Aspose.Slides için C++ API Referansı
description: Geçerli nesne tarafından temsil edilen yüzeyde, belirtilen fırça kullanılarak belirtilen dilimi doldurur.
type: docs
weight: 274
url: /tr/system.drawing/graphics/fillpie/
---
## Graphics::FillPie(const SharedPtr\<Brush\>\&, int, int, int, int, int, int) metod

Geçerli nesne tarafından temsil edilen yüzeyde, belirtilen fırça kullanılarak belirtilen dilim doldurulur.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Dilim doldurulurken kullanılacak fırça |
| x | int | Ellipse'i tanımlayan dikdörtgenin sol üst köşesinin X koordinatı |
| y | int | Ellipse'i tanımlayan dikdörtgenin sol üst köşesinin Y koordinatı |
| width | int | Ellipse'i tanımlayan dikdörtgenin genişliği |
| height | int | Ellipse'i tanımlayan dikdörtgenin yüksekliği |
| startAngle | int | X ekseninden saat yönünde ölçülen derece cinsinden, dilimin başlangıç noktasına kadar olan açı |
| sweepAngle | int | X ekseninden saat yönünde ölçülen derece cinsinden, **startAngle**'den dilimin bitiş noktasına kadar olan açı |

## Graphics::FillPie(const SharedPtr\<Brush\>\&, float, float, float, float, float, float) metod

Geçerli nesne tarafından temsil edilen yüzeyde, belirtilen fırça kullanılarak belirtilen dilim doldurulur.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Dilim doldurulurken kullanılacak fırça |
| x | **float** | Ellipse'i tanımlayan dikdörtgenin sol üst köşesinin X koordinatı |
| y | **float** | Ellipse'i tanımlayan dikdörtgenin sol üst köşesinin Y koordinatı |
| width | **float** | Ellipse'i tanımlayan dikdörtgenin genişliği |
| height | **float** | Ellipse'i tanımlayan dikdörtgenin yüksekliği |
| startAngle | **float** | X ekseninden saat yönünde ölçülen derece cinsinden, dilimin başlangıç noktasına kadar olan açı |
| sweepAngle | **float** | X ekseninden saat yönünde ölçülen derece cinsinden, **startAngle**'den dilimin bitiş noktasına kadar olan açı |

## Graphics::FillPie(const SharedPtr\<Brush\>\&, Rectangle, float, float) metod

Geçerli nesne tarafından temsil edilen yüzeyde, belirtilen fırça kullanılarak belirtilen dilim doldurulur.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, Rectangle rect, float startAngle, float sweepAngle)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Dilim doldurulurken kullanılacak fırça |
| rect | [Rectangle](../../rectangle/) | Ellipse'i tanımlayan dikdörtgen |
| startAngle | **float** | X ekseninden saat yönünde ölçülen derece cinsinden, dilimin başlangıç noktasına kadar olan açı |
| sweepAngle | **float** | X ekseninden saat yönünde ölçülen derece cinsinden, **startAngle**'den dilimin bitiş noktasına kadar olan açı |

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Brush](../../brush/)
* Class [Graphics](../)
* Class [Rectangle](../../rectangle/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)