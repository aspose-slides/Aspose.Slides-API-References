---
title: set_UpperLimit()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die obere oder untere Grenze an
type: docs
weight: 40
url: /de/aspose.slides.mathtext/imathlimit/set_upperlimit/
---
## IMathLimit::set_UpperLimit(bool) Methode


Gibt die obere oder untere Grenze an

```cpp
virtual void Aspose::Slides::MathText::IMathLimit::set_UpperLimit(bool value)=0
```

## Bemerkungen


Beispiel: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
limitElement->set_UpperLimit(false);
```

## Siehe auch

* Klasse [IMathLimit](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)