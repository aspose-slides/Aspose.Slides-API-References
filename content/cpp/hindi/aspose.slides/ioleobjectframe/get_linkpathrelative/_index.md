---
title: get_LinkPathRelative()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "यदि मौजूद हो तो लिंक की गई फ़ाइल का सापेक्ष पथ लौटाता है, अन्यथा एक खाली स्ट्रिंग लौटाता है। केवल-पढ़ने योग्य System::String."
type: docs
weight: 118
url: /hi/aspose.slides/ioleobjectframe/get_linkpathrelative/
---
## IOleObjectFrame::get_LinkPathRelative() मेथड

यदि मौजूद हो तो लिंक किए गए फ़ाइल का सापेक्ष पथ लौटाता है, अन्यथा एक खाली स्ट्रिंग लौटाता है। केवल-पढ़ने योग्य [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::IOleObjectFrame::get_LinkPathRelative()=0
```

## टिप्पणी

Ppt प्रस्तुतीकरणों में, कुछ Ole ऑब्जेक्ट लिंक में सापेक्ष प्रतिनिधित्व हो सकता है।

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.ppt");

auto oleFrame = System::AsCast<Aspose::Slides::IOleObjectFrame>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));

if (oleFrame != nullptr)
{
    System::Console::WriteLine(System::String(u"The relative path: ") + oleFrame->get_LinkPathRelative());
}
```

## देखें

* वर्ग [String](../../../system/string/)
* वर्ग [IOleObjectFrame](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)