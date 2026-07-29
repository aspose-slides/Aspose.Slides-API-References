---
title: get_ParentShape()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar den överordnade formen eller null om det överordnade objektet inte implementerar IShape-gränssnittet Skrivskyddad IShape.
type: docs
weight: 66
url: /sv/aspose.slides/itextframe/get_parentshape/
---
## ITextFrame::get_ParentShape() metod

Returnerar den överordnade formen eller null om det överordnade objektet inte implementerar [IShape](../../ishape/) gränssnittet Skrivskyddad [IShape](../../ishape/).

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::ITextFrame::get_ParentShape()=0
```

## Anmärkningar

Följande kodexempel visar 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<AutoShape> autoShape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(autoShape->get_TextFrame()->get_ParentShape() == autoShape);
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IShape](../../ishape/)
* Klass [ITextFrame](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)