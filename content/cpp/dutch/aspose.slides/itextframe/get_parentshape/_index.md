---
title: get_ParentShape()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de bovenliggende vorm of null indien het bovenliggende object de IShape interface Alleen-lezen IShape niet implementeert.
type: docs
weight: 66
url: /nl/aspose.slides/itextframe/get_parentshape/
---
## ITextFrame::get_ParentShape() methode

Retourneert de bovenliggende vorm of null als het bovenliggende object de [IShape](../../ishape/) interface Alleen-lezen [IShape](../../ishape/) niet implementeert.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::ITextFrame::get_ParentShape()=0
```

## Opmerkingen

Het volgende codevoorbeeld toont
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<AutoShape> autoShape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(autoShape->get_TextFrame()->get_ParentShape() == autoShape);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IShape](../../ishape/)
* Klasse [ITextFrame](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)