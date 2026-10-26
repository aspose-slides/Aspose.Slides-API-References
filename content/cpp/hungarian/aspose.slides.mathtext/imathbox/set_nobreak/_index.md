---
title: set_NoBreak()
second_title: Aspose.Slides for C++ API-referencia
description: "Nincs törés. Ez a tulajdonság határozza meg a \"törhetetlen\" tulajdonságot az objektumdobozon. Ha igaz, a dobozon belül nem fordulhat elő sortörés. Ez fontos lehet olyan operátor emulatoroknál, amelyek több, mint egy bináris operátort tartalmaznak. Ha ez az elem nincs megadva, a dobozon belül előfordulhatnak törések. Alapértelmezett: true"
type: docs
weight: 53
url: /hu/aspose.slides.mathtext/imathbox/set_nobreak/
---
## IMathBox::set_NoBreak(bool) metódus


Nincs törés. Ez a tulajdonság határozza meg a \"unbreakable\" (törhetetlen) tulajdonságot az objektumdobozon. Ha igaz, a dobozon belül nem fordulhat elő sortörés. Ez fontos lehet azoknál az operátoros emulátoroknál, amelyek több, mint egy bináris operátort tartalmaznak. Ha ez az elem nincs megadva, a dobozon belül előfordulhatnak törések. Alapértelmezett: true

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_NoBreak(bool value)=0
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