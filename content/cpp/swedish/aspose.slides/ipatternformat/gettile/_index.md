---
title: GetTile()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en kakelbild för mönsterfyllning med angivna färger.
type: docs
weight: 53
url: /sv/aspose.slides/ipatternformat/gettile/
---
## IPatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) method


Skapar en kakelbild för mönsterfyllning med angivna färger.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground)=0
```


### Arguments

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | Bakgrunden [System::Drawing::Color](../../../system.drawing/color/) för mönstret. |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | Förgrunden [System::Drawing::Color](../../../system.drawing/color/) för mönstret. |

### Return Value

Kakel [System::Drawing::Bitmap](../../../system.drawing/bitmap/).

## IPatternFormat::GetTile(System::Drawing::Color) method


Skapar en kakelbild för mönsterfyllning.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color styleColor)=0
```


### Arguments

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | Standard [System::Drawing::Color](../../../system.drawing/color/), definierad i ShapeEx:s StyleEx-objekt. Fyllningens färger kan bero på detta. |

### Return Value

Kakel [System::Drawing::Bitmap](../../../system.drawing/bitmap/).

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IImage](../../iimage/)
* Klass [Color](../../../system.drawing/color/)
* Klass [IPatternFormat](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)