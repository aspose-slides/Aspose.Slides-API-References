---
title: get_ParentShape()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar den överordnade formen eller null om det överordnade objektet inte implementerar IShape-gränssnittet Skrivskyddad IShape.
type: docs
weight: 92
url: /sv/aspose.slides/textframe/get_parentshape/
---
## TextFrame::get_ParentShape() metod


Returnerar den överordnade formen eller null om det överordnade objektet inte implementerar [IShape](../../ishape/)-gränssnittet Skrivskyddad [IShape](../../ishape/).

```cpp
System::SharedPtr<IShape> Aspose::Slides::TextFrame::get_ParentShape() override
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
* Klass [TextFrame](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)