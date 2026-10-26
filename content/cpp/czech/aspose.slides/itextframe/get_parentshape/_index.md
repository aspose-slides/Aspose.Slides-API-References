---
title: get_ParentShape()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vrátí nadřazený tvar nebo null, pokud nadřazený objekt neimplementuje rozhraní IShape. Pouze pro čtení IShape.
type: docs
weight: 66
url: /cs/aspose.slides/itextframe/get_parentshape/
---
## ITextFrame::get_ParentShape() metoda

Vrátí nadřazený tvar nebo null, pokud nadřazený objekt neimplementuje rozhraní [IShape](../../ishape/) Pouze pro čtení [IShape](../../ishape/).

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::ITextFrame::get_ParentShape()=0
```

## Poznámky

Následující ukázka kódu ukazuje
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<AutoShape> autoShape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(autoShape->get_TextFrame()->get_ParentShape() == autoShape);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IShape](../../ishape/)
* Třída [ITextFrame](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)