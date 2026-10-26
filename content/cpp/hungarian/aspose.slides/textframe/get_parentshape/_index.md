---
title: get_ParentShape()
second_title: Aspose.Slides C++ API referencia
description: Visszaadja a szülő alakzatot vagy null értéket, ha a szülő objektum nem valósítja meg az IShape interfészt csak olvasható IShape.
type: docs
weight: 92
url: /hu/aspose.slides/textframe/get_parentshape/
---
## TextFrame::get_ParentShape() metódus


Visszaadja a szülő alakzatot vagy null értéket, ha a szülő objektum nem valósítja meg a [IShape](../../ishape/) interfészt Csak olvasható [IShape](../../ishape/).

```cpp
System::SharedPtr<IShape> Aspose::Slides::TextFrame::get_ParentShape() override
```

## Megjegyzések


Az alábbi kódrészlet mutatja 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<AutoShape> autoShape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(autoShape->get_TextFrame()->get_ParentShape() == autoShape);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IShape](../../ishape/)
* Osztály [TextFrame](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)