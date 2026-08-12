---
title: get_ParentCell()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: यदि पैरेंट ऑब्जेक्ट ICell इंटरफ़ेस को लागू नहीं करता है तो पैरेंट सेल या null लौटाता है। केवल-पढ़ने योग्य ICell.
type: docs
weight: 79
url: /hi/aspose.slides/itextframe/get_parentcell/
---
## ITextFrame::get_ParentCell() विधि


यदि पैरेंट ऑब्जेक्ट [ICell](../../icell/) इंटरफ़ेस को लागू नहीं करता है तो पैरेंट सेल या null लौटाता है। केवल-पढ़ने योग्य [ICell](../../icell/)।

```cpp
virtual System::SharedPtr<ICell> Aspose::Slides::ITextFrame::get_ParentCell()=0
```

## टिप्पणी


निम्नलिखित कोड नमूना दिखाता है 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<Table> table = System::ExplicitCast<Table>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(table->idx_get(0, 0)->get_TextFrame()->get_ParentCell() == table->idx_get(0, 0));
```

## देखिए

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [ICell](../../icell/)
* क्लास [ITextFrame](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)