---
title: set_UpperLimit()
second_title: Aspose.Slides pro C++ – reference API
description: Určuje horní nebo dolní limit
type: docs
weight: 40
url: /cs/aspose.slides.mathtext/imathlimit/set_upperlimit/
---
## IMathLimit::set_UpperLimit(bool) metoda

Určuje horní nebo dolní limit

```cpp
virtual void Aspose::Slides::MathText::IMathLimit::set_UpperLimit(bool value)=0
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