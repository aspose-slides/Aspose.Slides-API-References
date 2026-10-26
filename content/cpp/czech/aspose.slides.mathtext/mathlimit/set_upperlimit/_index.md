---
title: set_UpperLimit()
second_title: Aspose.Slides pro C++ API Reference
description: Určuje horní nebo dolní limit
type: docs
weight: 40
url: /cs/aspose.slides.mathtext/mathlimit/set_upperlimit/
---
## MathLimit::set_UpperLimit(bool) metoda

Určuje horní nebo dolní limit

```cpp
void Aspose::Slides::MathText::MathLimit::set_UpperLimit(bool value) override
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