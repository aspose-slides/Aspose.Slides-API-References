---
title: set_UpperLimit()
second_title: Aspose.Slides C++ API referenciája
description: Megadja a felső vagy alsó határt
type: docs
weight: 40
url: /hu/aspose.slides.mathtext/mathlimit/set_upperlimit/
---
## MathLimit::set_UpperLimit(bool) módszer


Megadja a felső vagy alsó határt

```cpp
void Aspose::Slides::MathText::MathLimit::set_UpperLimit(bool value) override
```

## Megjegyzés


Példa: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
limitElement->set_UpperLimit(false);
```

## Lásd még

* Osztály [MathLimit](../)
* Névterület [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)