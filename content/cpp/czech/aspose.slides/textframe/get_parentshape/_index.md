---
title: get_ParentShape()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vrací rodičovský tvar nebo null, pokud rodičovský objekt neimplementuje rozhraní IShape. Pouze pro čtení IShape.
type: docs
weight: 92
url: /cs/aspose.slides/textframe/get_parentshape/
---
## TextFrame::get_ParentShape() metoda


Vrací rodičovský tvar nebo null, pokud rodičovský objekt neimplementuje rozhraní [IShape](../../ishape/) Pouze pro čtení [IShape](../../ishape/).

```cpp
System::SharedPtr<IShape> Aspose::Slides::TextFrame::get_ParentShape() override
```

## Poznámky


The following code sample shows 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<AutoShape> autoShape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(autoShape->get_TextFrame()->get_ParentShape() == autoShape);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IShape](../../ishape/)
* Třída [TextFrame](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)