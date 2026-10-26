---
title: get_ParentShape()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce la forma genitore o null se l'oggetto genitore non implementa l'interfaccia IShape Read-only IShape.
type: docs
weight: 92
url: /it/aspose.slides/textframe/get_parentshape/
---
## TextFrame::get_ParentShape() metodo


Restituisce la forma genitore o null se l'oggetto genitore non implementa l'interfaccia [IShape](../../ishape/) Solo lettura [IShape](../../ishape/).

```cpp
System::SharedPtr<IShape> Aspose::Slides::TextFrame::get_ParentShape() override
```

## Osservazioni


Il seguente esempio di codice mostra 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<AutoShape> autoShape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(autoShape->get_TextFrame()->get_ParentShape() == autoShape);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IShape](../../ishape/)
* Classe [TextFrame](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)