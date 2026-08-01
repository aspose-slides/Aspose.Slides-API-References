---
title: get_ParentShape()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de bovenliggende vorm of null als het bovenliggende object de IShape-interface niet implementeert Alleen-lezen IShape.
type: docs
weight: 92
url: /nl/aspose.slides/textframe/get_parentshape/
---
## TextFrame::get_ParentShape() methode

Retourneert de bovenliggende vorm of null als het bovenliggende object de [IShape](../../ishape/) interface Alleen-lezen [IShape](../../ishape/).

```cpp
System::SharedPtr<IShape> Aspose::Slides::TextFrame::get_ParentShape() override
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
* Klasse [TextFrame](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)