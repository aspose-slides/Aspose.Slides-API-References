---
title: GetImage()
second_title: Aspose.Slides für C++ API Referenz
description: "Gibt das Miniaturbild der Form zurück. ShapeThumbnailBounds::Shape Form-Miniaturbild-Bereichstyp wird standardmäßig verwendet."
type: docs
weight: 547
url: /de/aspose.slides/ishape/getimage/
---
## IShape::GetImage() Methode

Gibt das Miniaturbild der Form zurück. [ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) Form-Miniaturbild-Bereichstyp wird standardmäßig verwendet.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IShape::GetImage()=0
```

### Rückgabewert

[Shape](../../shape/) Miniaturbild.

## IShape::GetImage(ShapeThumbnailBounds, float, float) Methode

Gibt das Miniaturbild der Form zurück.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IShape::GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../../shape/) Miniaturbild-Bereichstyp. |
| scaleX | **float** | X-Skalierung |
| scaleY | **float** | Y-Skalierung |

### Rückgabewert

[Shape](../../shape/) Miniaturbild oder Null, falls [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/) verwendet wird und die Form keine sichtbaren Elemente hat.

## Siehe auch

* Enum [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IImage](../../iimage/)
* Klasse [IShape](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)