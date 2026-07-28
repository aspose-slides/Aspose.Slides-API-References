---
title: GetImage()
second_title: Aspose.Slides C++ API referencia
description: "Visszaadja az alakzat miniatűrjét. Alapértelmezés szerint a ShapeThumbnailBounds::Shape alakzat miniatűr határoló típusa kerül felhasználásra."
type: docs
weight: 547
url: /hu/aspose.slides/ishape/getimage/
---
## IShape::GetImage() metódus


Visszaadja az alakzat miniatűrjét. [ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) az alakzat miniatűr határoló típusa alapértelmezés szerint használatos.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IShape::GetImage()=0
```


### Visszatérési érték

[Shape](../../shape/) miniatűr.

## IShape::GetImage(ShapeThumbnailBounds, float, float) metódus


Visszaadja az alakzat miniatűrjét.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IShape::GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../../shape/) miniatűr határoló típusa. |
| scaleX | **float** | X skála |
| scaleY | **float** | Y skála |

### Visszatérési érték

[Shape](../../shape/) miniatűr vagy null, ha [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/) használatos és az alakzatnak nincsenek látható elemei.

## Lásd még

* Enum [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [IShape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)