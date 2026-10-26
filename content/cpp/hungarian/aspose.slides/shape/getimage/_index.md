---
title: GetImage()
second_title: Aspose.Slides for C++ API referencia
description: "Visszaadja az alakzat bélyegképét. A ShapeThumbnailBounds::Shape alakzat bélyegkép határ típusa alapértelmezés szerint van használva."
type: docs
weight: 651
url: /hu/aspose.slides/shape/getimage/
---
## Shape::GetImage() metódus

Visszaadja az alakzat bélyegképét. [ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) az alakzat bélyegkép határ típusa van alapértelmezésként használva.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage() override
```


### Visszatérési érték

[Shape](../) bélyegkép.

## Shape::GetImage(ShapeThumbnailBounds, float, float) metódus

Visszaadja az alakzat bélyegképét.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../) bélyegkép határ típusa. |
| scaleX | **float** | X skála |
| scaleY | **float** | Y skála |

### Visszatérési érték

[Shape](../) bélyegkép vagy null abban az esetben, amikor [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/) használatban van, és egy alakztnak nincsenek látható elemei.

## Lásd még

* Enum [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IImage](../../iimage/)
* Osztály [Shape](../)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)