---
title: FoundResult()
second_title: Aspose.Slides for C++ API संदर्भ
description: कोलबैक मेथड जो पाए गए टेक्स्ट के बारे में डेटा प्राप्त करता है।
type: docs
weight: 1
url: /hi/aspose.slides/ifindresultcallback/foundresult/
---
## IFindResultCallback::FoundResult(System::SharedPtr\<ITextFrame\>, System::String, System::String, int32_t) मेथड

कोलबैक मेथड जो पाए गए टेक्स्ट के बारे में डेटा प्राप्त करता है।

```cpp
virtual void Aspose::Slides::IFindResultCallback::FoundResult(System::SharedPtr<ITextFrame> textFrame, System::String sourceText, System::String foundText, int32_t textPosition)=0
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| textFrame | [System::SharedPtr](../../../system/sharedptr/)\<[ITextFrame](../../itextframe/)\> | [ITextFrame](../../itextframe/) जिसमें टेक्स्ट पाया गया। |
| sourceText | [System::String](../../../system/string/) | स्रोत टेक्स्ट जिसमें टेक्स्ट पाया गया। |
| foundText | [System::String](../../../system/string/) | पाया गया टेक्स्ट। |
| textPosition | **int32_t** | पाए गए टेक्स्ट की स्थिति। |

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITextFrame](../../itextframe/)
* Class [String](../../../system/string/)
* Class [IFindResultCallback](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)