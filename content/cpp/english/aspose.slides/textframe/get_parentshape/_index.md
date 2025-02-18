---
title: get_ParentShape()
second_title: Aspose.Slides for C++ API Reference
description: Returns the parent shape or null if the parent object does not implement the IShape interface Read-only IShape.
type: docs
weight: 92
url: /aspose.slides/textframe/get_parentshape/
---
## TextFrame::get_ParentShape() method


Returns the parent shape or null if the parent object does not implement the [IShape](../../ishape/) interface Read-only [IShape](../../ishape/).

```cpp
System::SharedPtr<IShape> Aspose::Slides::TextFrame::get_ParentShape() override
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
* Class [TextFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)