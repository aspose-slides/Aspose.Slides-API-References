---
title: DrawPie()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen kalemi kullanarak, mevcut nesne tarafından temsil edilen yüzey üzerinde belirtilen daire dilimini çizer.
type: docs
weight: 261
url: /tr/system.drawing/graphics/drawpie/
---
## Graphics::DrawPie(const SharedPtr\<Pen\>\&, int32_t, int32_t, int32_t, int32_t, int32_t, int32_t) yöntemi


Belirtilen daire dilimini, belirtilen kalemi kullanarak mevcut nesnenin temsil ettiği yüzey üzerinde çizer.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, int32_t x, int32_t y, int32_t width, int32_t height, int32_t startAngle, int32_t sweepAngle)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Daire dilimini çizerken kullanılacak bir kalem |
| x | **int32_t** | Elipsi tanımlayan dikdörtgenin sol üst köşesinin X koordinatı |
| y | **int32_t** | Elipsi tanımlayan dikdörtgenin sol üst köşesinin Y koordinatı |
| width | **int32_t** | Elipsi tanımlayan dikdörtgenin genişliği |
| height | **int32_t** | Elipsi tanımlayan dikdörtgenin yüksekliği |
| startAngle | **int32_t** | X ekseninden saat yönünde ölçülen, daire diliminin başlangıç noktasına kadar olan açı (derece) |
| sweepAngle | **int32_t** | **startAngle**'den saat yönünde ölçülen, daire diliminin bitiş noktasına kadar olan açı (derece) |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, float, float, float, float, float, float) yöntemi


Belirtilen daire dilimini, belirtilen kalemi kullanarak mevcut nesnenin temsil ettiği yüzey üzerinde çizer.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Daire dilimini çizerken kullanılacak bir kalem |
| x | **float** | Elipsi tanımlayan dikdörtgenin sol üst köşesinin X koordinatı |
| y | **float** | Elipsi tanımlayan dikdörtgenin sol üst köşesinin Y koordinatı |
| width | **float** | Elipsi tanımlayan dikdörtgenin genişliği |
| height | **float** | Elipsi tanımlayan dikdörtgenin yüksekliği |
| startAngle | **float** | X ekseninden saat yönünde ölçülen, daire diliminin başlangıç noktasına kadar olan açı (derece) |
| sweepAngle | **float** | **startAngle**'den saat yönünde ölçülen, daire diliminin bitiş noktasına kadar olan açı (derece) |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, Rectangle, float, float) yöntemi


Belirtilen daire dilimini, belirtilen kalemi kullanarak mevcut nesnenin temsil ettiği yüzey üzerinde çizer.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, Rectangle rect, float startAngle, float sweepAngle)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Daire dilimini çizerken kullanılacak bir kalem |
| rect | [Rectangle](../../rectangle/) | Elipsi tanımlayan dikdörtgen |
| startAngle | **float** | X ekseninden saat yönünde ölçülen, daire diliminin başlangıç noktasına kadar olan açı (derece) |
| sweepAngle | **float** | **startAngle**'den saat yönünde ölçülen, daire diliminin bitiş noktasına kadar olan açı (derece) |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, RectangleF, float, float) yöntemi


Belirtilen daire dilimini, belirtilen kalemi kullanarak mevcut nesnenin temsil ettiği yüzey üzerinde çizer.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, RectangleF rect, float startAngle, float sweepAngle)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Daire dilimini çizerken kullanılacak bir kalem |
| rect | [RectangleF](../../rectanglef/) | Elipsi tanımlayan dikdörtgen |
| startAngle | **float** | X ekseninden saat yönünde ölçülen, daire diliminin başlangıç noktasına kadar olan açı (derece) |
| sweepAngle | **float** | **startAngle**'den saat yönünde ölçülen, daire diliminin bitiş noktasına kadar olan açı (derece) |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Pen](../../pen/)
* Sınıf [Graphics](../)
* Sınıf [Rectangle](../../rectangle/)
* Sınıf [RectangleF](../../rectanglef/)
* Ad Alanı [System::Drawing](../../)
* Kütüphane [Aspose.Slides](../../../)