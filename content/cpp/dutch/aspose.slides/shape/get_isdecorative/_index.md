---
title: get_IsDecorative()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt de 'Mark as decorative' optie lezen/schrijven bool.
type: docs
weight: 521
url: /nl/aspose.slides/shape/get_isdecorative/
---
## Shape::get_IsDecorative() methode


Haalt de 'Markeren als decoratief' optie lezen/schrijven **bool**.

```cpp
bool Aspose::Slides::Shape::get_IsDecorative() override
```

## Opmerkingen



```cpp
auto pres = System::MakeObject<Presentation>(u"sample.pptx")
pres->get_Slide(0)->get_Shape(0)->set_IsDecorative(true);
```

## Zie ook

* Klasse [Shape](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)