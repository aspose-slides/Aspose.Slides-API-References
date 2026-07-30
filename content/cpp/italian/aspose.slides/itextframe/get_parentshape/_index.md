---
title: get_ParentShape()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce la forma padre o null se l'oggetto padre non implementa l'interfaccia IShape Solo lettura IShape.
type: docs
weight: 66
url: /it/aspose.slides/itextframe/get_parentshape/
---
## ITextFrame::get_ParentShape() metodo

Restituisce la forma padre o null se l'oggetto padre non implementa l'interfaccia [IShape](../../ishape/) Solo lettura [IShape](../../ishape/).

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::ITextFrame::get_ParentShape()=0
```

## Note

Il seguente esempio di codice mostra
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<AutoShape> autoShape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(autoShape->get_TextFrame()->get_ParentShape() == autoShape);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IShape](../../ishape/)
* Classe [ITextFrame](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)