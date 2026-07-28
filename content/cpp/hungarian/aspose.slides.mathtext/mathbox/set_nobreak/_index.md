---
title: set_NoBreak()
second_title: Aspose.Slides C++ API hivatkozás
description: "Nincs törés Ez a tulajdonság meghatározza a \"unbreakable\" tulajdonságot az objektumdobozon. Ha igaz, a dobozon belül nem fordulhat elő sortörés. Ez fontos lehet olyan operátor emulátoroknál, amelyek több, mint egy bináris operátort tartalmaznak. Ha ez az elem nincs megadva, a dobozon belül fordulhatnak sortörések. Alapértelmezett: true"
type: docs
weight: 53
url: /hu/aspose.slides.mathtext/mathbox/set_nobreak/
---
## MathBox::set_NoBreak(bool) metódus

Nincs törés Ez a tulajdonság meghatározza a "unbreakable" tulajdonságot az objektumdobozon. Ha igaz, a dobozon belül nem fordulhat elő sortörés. Ez fontos lehet olyan operátor emulátoroknál, amelyek több, mint egy bináris operátort tartalmaznak. Ha ez az elem nincs megadva, a dobozon belül fordulhatnak sortörések. Alapértelmezett: true

```cpp
void Aspose::Slides::MathText::MathBox::set_NoBreak(bool value) override
```

## Megjegyzések

Példa: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"*****"));
box->set_NoBreak(false);
```

## Lásd még

* Osztály [MathBox](../)
* Névtere [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)