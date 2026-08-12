---
title: get_ParentShape()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: पैरेंट आकार को लौटाता है या null यदि पैरेंट वस्तु IShape इंटरफ़ेस को लागू नहीं करती है केवल-पढ़ने-योग्य IShape.
type: docs
weight: 66
url: /hi/aspose.slides/itextframe/get_parentshape/
---
## ITextFrame::get_ParentShape() विधि


पैरेंट आकार को लौटाता है या null यदि पैरेंट वस्तु [IShape](../../ishape/) इंटरफ़ेस को लागू नहीं करती है केवल-पढ़ने योग्य [IShape](../../ishape/).

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::ITextFrame::get_ParentShape()=0
```

## टिप्पणी


निम्न कोड नमूना दिखाता है 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<AutoShape> autoShape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(autoShape->get_TextFrame()->get_ParentShape() == autoShape);
```

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IShape](../../ishape/)
* क्लास [ITextFrame](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)