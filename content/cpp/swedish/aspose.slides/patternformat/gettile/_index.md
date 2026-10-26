---
title: GetTile()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en kakelbild för mönsterfyllning med specificerade färger.
type: docs
weight: 53
url: /sv/aspose.slides/patternformat/gettile/
---
## PatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) metod

Skapar en kakelbild för mönsterfyllningen med specificerade färger.

```cpp
System::SharedPtr<IImage> Aspose::Slides::PatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | Bakgrunden [System::Drawing::Color](../../../system.drawing/color/) för mönstret. |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | Förgrunden [System::Drawing::Color](../../../system.drawing/color/) för mönstret. |

### Returvärde

Kakel [IImage](../../iimage/).

## PatternFormat::GetTile(System::Drawing::Color) metod

Skapar en kakelbild för mönsterfyllningen.

```cpp
System::SharedPtr<IImage> Aspose::Slides::PatternFormat::GetTile(System::Drawing::Color styleColor) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | Standardvärdet [System::Drawing::Color](../../../system.drawing/color/) |

### Returvärde

Kakel [IImage](../../iimage/).

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IImage](../../iimage/)
* Klass [Color](../../../system.drawing/color/)
* Klass [PatternFormat](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)