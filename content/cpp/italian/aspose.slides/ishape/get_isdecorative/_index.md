---
title: get_IsDecorative()
second_title: Riferimento API di Aspose.Slides per C++
description: Recupera l'opzione 'Mark as decorative' Lettura/scrittura **bool**.
type: docs
weight: 404
url: /it/aspose.slides/ishape/get_isdecorative/
---
## IShape::get_IsDecorative() metodo

Recupera l'opzione 'Mark as decorative' Lettura/scrittura **bool**.

```cpp
virtual bool Aspose::Slides::IShape::get_IsDecorative()=0
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