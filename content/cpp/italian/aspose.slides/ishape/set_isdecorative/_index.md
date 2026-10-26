---
title: set_IsDecorative()
second_title: Riferimento API di Aspose.Slides per C++
description: Imposta l'opzione 'Mark as decorative' Lettura/scrittura bool.
type: docs
weight: 417
url: /it/aspose.slides/ishape/set_isdecorative/
---
## IShape::set_IsDecorative(bool) metodo


Imposta l'opzione 'Mark as decorative' Lettura/scrittura **bool**.

```cpp
virtual void Aspose::Slides::IShape::set_IsDecorative(bool value)=0
```

## Osservazioni



```cpp
auto pres = System::MakeObject<Presentation>(u"sample.pptx")
pres->get_Slide(0)->get_Shape(0)->set_IsDecorative(true);
```

## Vedi anche

* Classe [IShape](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)