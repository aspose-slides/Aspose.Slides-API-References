---
title: get_LinkPathRelative()
second_title: Aspose.Slides for C++ API संदर्भ
description: "यदि उपलब्ध हो तो लिंक किए गए फ़ाइल का सापेक्ष पथ लौटाता है, अन्यथा एक खाली स्ट्रिंग लौटाता है। केवल पढ़ने योग्य System::String."
type: docs
weight: 131
url: /hi/aspose.slides/oleobjectframe/get_linkpathrelative/
---
## OleObjectFrame::get_LinkPathRelative() मेथड


यदि उपलब्ध हो तो लिंक किए गए फ़ाइल का सापेक्ष पथ लौटाता है, अन्यथा एक खाली स्ट्रिंग लौटाता है। केवल पढ़ने योग्य [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::OleObjectFrame::get_LinkPathRelative() override
```

## टिप्पणी


Ppt प्रस्तुतियों में, कुछ Ole ऑब्जेक्ट लिंक में सापेक्ष प्रतिनिधित्व हो सकता है। 


```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.ppt");

auto oleFrame = System::AsCast<Aspose::Slides::IOleObjectFrame>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));

if (oleFrame != nullptr)
{
    System::Console::WriteLine(System::String(u"The relative path: ") + oleFrame->get_LinkPathRelative());
}
```

## देखें

* क्लास [String](../../../system/string/)
* क्लास [OleObjectFrame](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)