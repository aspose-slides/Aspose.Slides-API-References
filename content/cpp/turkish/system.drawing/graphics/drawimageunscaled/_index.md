---
title: DrawImageUnscaled()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen konumda, orijinal fiziksel boyutunu koruyarak belirtilen görüntüyü çizer.
type: docs
weight: 443
url: /tr/system.drawing/graphics/drawimageunscaled/
---
## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, int, int) metot

Belirtilen konumda, orijinal fiziksel boyutunu koruyarak belirtilen görüntüyü çizer.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, int x, int y)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Çizilecek görüntü |
| x | int | Çizilen görüntünün sol üst köşesinin X koordinatı |
| y | int | Çizilen görüntünün sol üst köşesinin Y koordinatı |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, int, int, int, int) metot

Belirtilen bir konumda, orijinal fiziksel boyutunu koruyarak belirtilen görüntüyü çizer.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, int x, int y, int width, int height)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Çizilecek görüntü |
| x | int | Çizilen görüntünün sol üst köşesinin X koordinatı |
| y | int | Çizilen görüntünün sol üst köşesinin Y koordinatı |
| width | int | Kullanılmaz |
| height | int | Kullanılmaz |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, const Rectangle\&) metot

Belirtilen bir konumda, orijinal fiziksel boyutunu koruyarak belirtilen görüntüyü çizer.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, const Rectangle &rect)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Çizilecek görüntü |
| rect | const [Rectangle](../../rectangle/)\& | Çizilen görüntünün sol üst köşesini belirten dikdörtgen. Dikdörtgenin X ve Y özellikleri sol üst köşeyi belirler. Genişlik ve yükseklik değerleri göz ardı edilir. |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, const Point\&) metot

Belirtilen bir konumda, orijinal fiziksel boyutunu koruyarak belirtilen görüntüyü çizer.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, const Point &point)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Çizilecek görüntü |
| point | const [Point](../../point/)\& | [Point](../../point/) yapısı, çizilen görüntünün sol üst köşesini belirler. |

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Image](../../image/)
* Sınıf [Graphics](../)
* Sınıf [Rectangle](../../rectangle/)
* Sınıf [Point](../../point/)
* Ad alanı [System::Drawing](../../)
* Kütüphane [Aspose.Slides](../../../)