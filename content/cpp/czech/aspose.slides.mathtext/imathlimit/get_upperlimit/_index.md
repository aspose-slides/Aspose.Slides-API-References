---
title: get_UpperLimit()
second_title: Aspose.Slides pro C++ – reference API
description: Určuje horní nebo dolní limit
type: docs
weight: 27
url: /cs/aspose.slides.mathtext/imathlimit/get_upperlimit/
---
## IMathLimit::get_UpperLimit() metoda

Určuje horní nebo dolní limit

```cpp
virtual bool Aspose::Slides::MathText::IMathLimit::get_UpperLimit()=0
```

## Poznámky

Příklad:
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
limitElement->set_UpperLimit(false);
```

## Viz také

* Třída [IMathLimit](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)