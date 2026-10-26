---
title: DrawRectangle()
second_title: Aspose.Slides for C++ API Referansı
description: Geçerli nesne tarafından temsil edilen yüzeyde belirtilen kalemi kullanarak belirtilen dikdörtgeni çizer.
type: docs
weight: 287
url: /tr/system.drawing/graphics/drawrectangle/
---
## Graphics::DrawRectangle(const SharedPtr\<Pen\>\&, int, int, int, int) metot


Belirtilen dikdörtgeni, belirtilen kalemi kullanarak geçerli nesne tarafından temsil edilen yüzeyde çizer.

```cpp
void System::Drawing::Graphics::DrawRectangle(const SharedPtr<Pen> &pen, int x, int y, int width, int height)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Dikdörtgeni çizerken kullanılacak bir kalem |
| x | int | Çizilecek dikdörtgenin sol üst köşesinin X koordinatı |
| y | int | Çizilecek dikdörtgenin sol üst köşesinin Y koordinatı |
| width | int | Çizilecek dikdörtgenin genişliği |
| height | int | Çizilecek dikdörtgenin yüksekliği |

## Graphics::DrawRectangle(const SharedPtr\<Pen\>\&, float, float, float, float) metot


Belirtilen dikdörtgeni, belirtilen kalemi kullanarak geçerli nesne tarafından temsil edilen yüzeyde çizer.

```cpp
void System::Drawing::Graphics::DrawRectangle(const SharedPtr<Pen> &pen, float x, float y, float width, float height)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Dikdörtgeni çizerken kullanılacak bir kalem |
| x | **float** | Çizilecek dikdörtgenin sol üst köşesinin X koordinatı |
| y | **float** | Çizilecek dikdörtgenin sol üst köşesinin Y koordinatı |
| width | **float** | Çizilecek dikdörtgenin genişliği |
| height | **float** | Çizilecek dikdörtgenin yüksekliği |

## Graphics::DrawRectangle(const SharedPtr\<Pen\>\&, Rectangle) metot


Belirtilen dikdörtgeni, belirtilen kalemi kullanarak geçerli nesne tarafından temsil edilen yüzeyde çizer.

```cpp
void System::Drawing::Graphics::DrawRectangle(const SharedPtr<Pen> &pen, Rectangle rect)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Dikdörtgeni çizerken kullanılacak bir kalem |
| rect | [Rectangle](../../rectangle/) | [Rectangle](../../rectangle/) nesnesi, çizilecek dikdörtgenin konumunu ve boyutunu belirtir |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Pen](../../pen/)
* Sınıf [Graphics](../)
* Sınıf [Rectangle](../../rectangle/)
* İsim Alanı [System::Drawing](../../)
* Library [Aspose.Slides](../../../)