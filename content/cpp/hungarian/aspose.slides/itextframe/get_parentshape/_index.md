---
title: get_ParentShape()
second_title: Aspose.Slides C++ API referencia
description: Visszaadja a szülő alakzatot, vagy null értéket, ha a szülő objektum nem valósítja meg az IShape interfészt. Csak olvasható IShape.
type: docs
weight: 66
url: /hu/aspose.slides/itextframe/get_parentshape/
---
## ITextFrame::get_ParentShape() metódus

Visszaadja a szülő alakzatot, vagy null értéket, ha a szülő objektum nem valósítja meg a [IShape](../../ishape/) interfészt. Csak olvasható [IShape](../../ishape/).

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::ITextFrame::get_ParentShape()=0
```

## Megjegyzések

A következő kódminta mutatja 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<AutoShape> autoShape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(autoShape->get_TextFrame()->get_ParentShape() == autoShape);
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IShape](../../ishape/)
* Osztály [ITextFrame](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)