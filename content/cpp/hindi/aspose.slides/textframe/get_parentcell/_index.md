---
title: get_ParentCell()
second_title: Aspose.Slides for C++ API संदर्भ
description: यदि पैरेंट ऑब्जेक्ट ICell इंटरफ़ेस को लागू नहीं करता है तो पैरेंट सेल लौटाता है या null लौटाता है। केवल-पढ़ने योग्य ICell.
type: docs
weight: 105
url: /hi/aspose.slides/textframe/get_parentcell/
---
## TextFrame::get_ParentCell() मेथड


पैरेंट सेल लौटाता है या यदि पैरेंट ऑब्जेक्ट [ICell](../../icell/) इंटरफ़ेस को लागू नहीं करता है तो null लौटाता है। केवल-पढ़ने योग्य [ICell](../../icell/).

```cpp
System::SharedPtr<ICell> Aspose::Slides::TextFrame::get_ParentCell() override
```

## टिप्पणियाँ


निम्नलिखित कोड उदाहरण दिखाता है 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<Table> table = System::ExplicitCast<Table>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(table->idx_get(0, 0)->get_TextFrame()->get_ParentCell() == table->idx_get(0, 0));
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [ICell](../../icell/)
* क्लास [TextFrame](../)
* नेमस्पेस [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)