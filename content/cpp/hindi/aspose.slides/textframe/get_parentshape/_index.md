---
title: get_ParentShape()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: पैरेंट आकार या null लौटाता है यदि पैरेंट ऑब्जेक्ट IShape इंटरफ़ेस को लागू नहीं करता है। केवल-पठन IShape।
type: docs
weight: 92
url: /hi/aspose.slides/textframe/get_parentshape/
---
## TextFrame::get_ParentShape() मेथड

पैरेंट आकार या null लौटाता है यदि पैरेंट ऑब्जेक्ट [IShape](../../ishape/) इंटरफ़ेस को लागू नहीं करता है। केवल-पठन [IShape](../../ishape/)।

```cpp
System::SharedPtr<IShape> Aspose::Slides::TextFrame::get_ParentShape() override
```

## टिप्पणी

निम्नलिखित कोड नमूना दिखाता है 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<AutoShape> autoShape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(autoShape->get_TextFrame()->get_ParentShape() == autoShape);
```

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IShape](../../ishape/)
* क्लास [TextFrame](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)