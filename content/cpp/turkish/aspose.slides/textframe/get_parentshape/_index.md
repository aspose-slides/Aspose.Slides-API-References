---
title: get_ParentShape()
second_title: Aspose.Slides for C++ API Referansı
description: Üst şekli döndürür; üst nesne IShape arayüzünü uygulamıyorsa null döndürür. Yalnızca okuma IShape.
type: docs
weight: 92
url: /tr/aspose.slides/textframe/get_parentshape/
---
## TextFrame::get_ParentShape() metodu


Üst şekli döndürür; üst nesne [IShape](../../ishape/) arayüzünü uygulamıyorsa null döndürür. Yalnızca okuma [IShape](../../ishape/).

```cpp
System::SharedPtr<IShape> Aspose::Slides::TextFrame::get_ParentShape() override
```

## Açıklamalar


Aşağıdaki kod örneği gösterir 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<AutoShape> autoShape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(autoShape->get_TextFrame()->get_ParentShape() == autoShape);
```

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IShape](../../ishape/)
* Sınıf [TextFrame](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)