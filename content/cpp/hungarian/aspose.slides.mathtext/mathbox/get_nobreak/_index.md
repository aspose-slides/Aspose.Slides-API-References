---
title: get_NoBreak()
second_title: Aspose.Slides C++ API referencia
description: "Nincs törés Ez a tulajdonság meghatározza a \"törhetetlen\" tulajdonságot az objektumdobozon. Ha igaz, nem fordulhat elő sortörés a dobozban. Ez fontos lehet operátor emulátoroknál, amelyek egynél több bináris operátorból állnak. Ha ez az elem nincs megadva, sortörés fordulhat elő a dobozon belül. Alapérték: true"
type: docs
weight: 40
url: /hu/aspose.slides.mathtext/mathbox/get_nobreak/
---
## MathBox::get_NoBreak() metódus

Nincs törés Ez a tulajdonság meghatározza a "törhetetlen" tulajdonságot az objektumdobozon. Ha igaz, akkor nem fordulhat elő sortörés a dobozban. Ez fontos lehet operátor emulátoroknál, amelyek egynél több bináris operátorból állnak. Ha ez az elem nincs megadva, sortörés fordulhat elő a dobozon belül. Alapérték: true

```cpp
bool Aspose::Slides::MathText::MathBox::get_NoBreak() override
```

## Megjegyzések

Példa: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"*****"));
box->set_NoBreak(false);
```

## Lásd még

* Class [MathBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)