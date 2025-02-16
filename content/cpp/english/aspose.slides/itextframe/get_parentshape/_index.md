---
title: get_ParentShape()
second_title: Aspose.Slides for C++ API Reference
description: Returns the parent shape or null if the parent object does not implement the IShape interface Read-only IShape.
type: docs
weight: 66
url: /aspose.slides/itextframe/get_parentshape/
---
## ITextFrame::get_ParentShape() method


Returns the parent shape or null if the parent object does not implement the [IShape](../../ishape/) interface Read-only [IShape](../../ishape/).

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::ITextFrame::get_ParentShape()=0
```

## Remarks


The following code sample shows 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<AutoShape> autoShape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(autoShape->get_TextFrame()->get_ParentShape() == autoShape);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShape](../../ishape/)
* Class [ITextFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)