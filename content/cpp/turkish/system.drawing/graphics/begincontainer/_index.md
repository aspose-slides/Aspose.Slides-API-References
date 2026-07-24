---
title: BeginContainer()
second_title: Aspose.Slides for C++ API Referansı
description: Bu nesnenin mevcut durumunu içeren bir kapsayıcıyı kaydeder, yeni bir kapsayıcı açar ve kullanır ve kaydedilen kapsayıcıyı döndürür.
type: docs
weight: 976
url: /tr/system.drawing/graphics/begincontainer/
---
## Graphics::BeginContainer() metot

Bu nesnenin mevcut durumuyla bir kapsayıcıyı kaydeder, yeni bir kapsayıcı açar ve kullanır ve kaydedilen kapsayıcıyı döndürür.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer()
```

## Graphics::BeginContainer(Rectangle, Rectangle, GraphicsUnit) metot

Bu nesnenin mevcut durumuyla bir kapsayıcıyı kaydeder, yeni bir kapsayıcı açar ve kullanır ve kaydedilen kapsayıcıyı döndürür.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(Rectangle dstrect, Rectangle srcrect, GraphicsUnit unit)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dstrect | [Rectangle](../../rectangle/) | The rectangle that specifies a scale transformation of the new container. Used together with **srcrect** |
| srcrect | [Rectangle](../../rectangle/) | The rectangle that specifies a scale transformation of the new container. Used together with **dstrect** |
| unit | [GraphicsUnit](../../graphicsunit/) | The value that specifies the unit of measure of the new container |

## Graphics::BeginContainer(RectangleF, RectangleF, GraphicsUnit) metot

Bu nesnenin mevcut durumuyla bir kapsayıcıyı kaydeder, yeni bir kapsayıcı açar ve kullanır ve kaydedilen kapsayıcıyı döndürür.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(RectangleF dstrect, RectangleF srcrect, GraphicsUnit unit)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dstrect | [RectangleF](../../rectanglef/) | The rectangle that specifies a scale transformation of the new container. Used together with **srcrect** |
| srcrect | [RectangleF](../../rectanglef/) | The rectangle that specifies a scale transformation of the new container. Used together with **dstrect** |
| unit | [GraphicsUnit](../../graphicsunit/) | The value that specifies the unit of measure of the new container |

## İlgili

* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [GraphicsContainer](../../../system.drawing.drawing2d/graphicscontainer/)
* Sınıf [Graphics](../)
* Sınıf [Rectangle](../../rectangle/)
* Sınıf [RectangleF](../../rectanglef/)
* Ad Alanı [System::Drawing](../../)
* Library [Aspose.Slides](../../../)