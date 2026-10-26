---
title: get_ParentShape()
second_title: Aspose.Slides için C++ API Referansı
description: Üst şekli döndürür veya üst nesne IShape arayüzünü uygulamıyorsa null döndürür. Yalnızca okuma IShape.
type: docs
weight: 66
url: /tr/aspose.slides/itextframe/get_parentshape/
---
## ITextFrame::get_ParentShape() metodu

Üst şekli döndürür veya üst nesne [IShape](../../ishape/) arayüzünü uygulamıyorsa null döndürür. Yalnızca okuma [IShape](../../ishape/).

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::ITextFrame::get_ParentShape()=0
```

## Açıklamalar

Aşağıdaki kod örneği gösterir 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<AutoShape> autoShape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(autoShape->get_TextFrame()->get_ParentShape() == autoShape);
```

## Ayrıca

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShape](../../ishape/)
* Class [ITextFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)