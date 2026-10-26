---
title: get_UpperLimit()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Určuje horní nebo dolní limit
type: docs
weight: 27
url: /cs/aspose.slides.mathtext/mathlimit/get_upperlimit/
---
## MathLimit::get_UpperLimit() metoda


Určuje horní nebo dolní limit

```cpp
bool Aspose::Slides::MathText::MathLimit::get_UpperLimit() override
```

## Poznámky


Příklad: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
limitElement->set_UpperLimit(false);
```

## Viz také

* Třída [MathLimit](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)