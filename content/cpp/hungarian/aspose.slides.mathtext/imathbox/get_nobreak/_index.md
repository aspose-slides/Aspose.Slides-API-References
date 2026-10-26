---
title: get_NoBreak()
second_title: Aspose.Slides C++ API referencia
description: "Nincs törés. Ez a tulajdonság határozza meg a \"szüntelhetetlen\" tulajdonságot az objektumdobozon. Ha igaz, a dobozon belül nem fordulhat elő sortörés. Ez fontos lehet olyan operátoremulátoroknál, amelyek több, mint egy bináris operátort tartalmaznak. Ha ez az elem nincs megadva, sortörés előfordulhat a dobozban. Alapérték: true"
type: docs
weight: 40
url: /hu/aspose.slides.mathtext/imathbox/get_nobreak/
---
## IMathBox::get_NoBreak() metódus

No break. This property specifies the "unbreakable" property on the object box. When true, no line breaks can occur within the box. This can be important for operator emulators that consist of more than one binary operator. When this element is not specified, breaks can occur inside box. Default: true

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_NoBreak()=0
```

## Megjegyzések

Példa:
```cpp
auto box = System::MakeObject<MathematicalText>(u"**********")->ToBox();
box->set_NoBreak(false);
```

## Lásd még

* Osztály [IMathBox](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)