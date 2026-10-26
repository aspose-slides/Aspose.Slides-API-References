---
title: get_UpperLimit()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die obere oder untere Grenze an
type: docs
weight: 27
url: /de/aspose.slides.mathtext/mathlimit/get_upperlimit/
---
## MathLimit::get_UpperLimit() Methode


Gibt die obere oder untere Grenze an

```cpp
bool Aspose::Slides::MathText::MathLimit::get_UpperLimit() override
```

## Hinweise


Beispiel:
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
limitElement->set_UpperLimit(false);
```

## Siehe auch

* Klasse [MathLimit](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)