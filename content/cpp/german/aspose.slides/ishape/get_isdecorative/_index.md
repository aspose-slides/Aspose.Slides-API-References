---
title: get_IsDecorative()
second_title: Aspose.Slides für C++ API Referenz
description: Liest/Schreibt die Option 'Mark as decorative' als bool.
type: docs
weight: 404
url: /de/aspose.slides/ishape/get_isdecorative/
---
## IShape::get_IsDecorative() Methode

Liest/Schreibt die Option 'Mark as decorative' als **bool**.

```cpp
virtual bool Aspose::Slides::IShape::get_IsDecorative()=0
```

## Anmerkungen



```cpp
auto pres = System::MakeObject<Presentation>(u"sample.pptx")
pres->get_Slide(0)->get_Shape(0)->set_IsDecorative(true);
```

## Siehe auch

* Klasse [IShape](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)