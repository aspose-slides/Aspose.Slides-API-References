---
title: get_IsDecorative()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt de optie 'Mark as decorative' op, lezen/schrijven bool.
type: docs
weight: 404
url: /nl/aspose.slides/ishape/get_isdecorative/
---
## IShape::get_IsDecorative() methode


Haal de optie 'Mark as decorative' op, lezen/schrijven **bool**.

```cpp
virtual bool Aspose::Slides::IShape::get_IsDecorative()=0
```

## Opmerkingen



```cpp
auto pres = System::MakeObject<Presentation>(u"sample.pptx")
pres->get_Slide(0)->get_Shape(0)->set_IsDecorative(true);
```

## Zie ook

* Klasse [IShape](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)