---
title: get_IsDecorative()
second_title: Riferimento API di Aspose.Slides per C++
description: Ottiene l'opzione 'Segna come decorativo' Lettura/scrittura bool.
type: docs
weight: 521
url: /it/aspose.slides/shape/get_isdecorative/
---
## Shape::get_IsDecorative() metodo


Ottiene l'opzione 'Segna come decorativo' Lettura/scrittura **bool**.

```cpp
bool Aspose::Slides::Shape::get_IsDecorative() override
```

## Osservazioni



```cpp
auto pres = System::MakeObject<Presentation>(u"sample.pptx")
pres->get_Slide(0)->get_Shape(0)->set_IsDecorative(true);
```

## Vedi anche

* Classe [Shape](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)