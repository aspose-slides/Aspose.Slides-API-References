---
title: set_AlignmentPoint()
second_title: Aspose.Slides for C++ API-referencia
description: "Ha igaz, ez az operátor emulátor vonalazási pontként működik; vagyis más egyenletek kijelölt vonalazási pontjai ezzel összhangba hozhatók. Alapértelmezett: false"
type: docs
weight: 105
url: /hu/aspose.slides.mathtext/mathbox/set_alignmentpoint/
---
## MathBox::set_AlignmentPoint(bool) metódus

When true, this operator emulator serves as an alignment point; that is, designated alignment points in other equations can be aligned with it. Default: false

```cpp
void Aspose::Slides::MathText::MathBox::set_AlignmentPoint(bool value) override
```

## Megjegyzések

Példa:
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_AlignmentPoint(true);
```

## Lásd még

* Osztály [MathBox](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)