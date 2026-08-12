---
title: Add()
second_title: Aspose.Slides for C++ API संदर्भ
description: संग्रह के अंत में एक Paragraph जोड़ता है।
type: docs
weight: 40
url: /hi/aspose.slides/paragraphcollection/add/
---
## ParagraphCollection::Add(System::SharedPtr\<IParagraph\>) विधि

संग्रह के अंत में एक [Paragraph](../../paragraph/) जोड़ता है।

```cpp
void Aspose::Slides::ParagraphCollection::Add(System::SharedPtr<IParagraph> value) override
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | संग्रह के अंत में जोड़ने के लिए [Paragraph](../../paragraph/)। |

## ParagraphCollection::Add(System::SharedPtr\<IParagraphCollection\>) विधि

संग्रह के अंत में [ParagraphCollection](../) की सामग्री जोड़ता है।

```cpp
int32_t Aspose::Slides::ParagraphCollection::Add(System::SharedPtr<IParagraphCollection> value) override
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraphCollection](../../iparagraphcollection/)\> | संग्रह के अंत में जोड़ने के लिए [ParagraphCollection](../)। |

### वापसी मान

[Paragraph](../../paragraph/) जोड़े जाने का सूचकांक या यदि जोड़ने के लिये कुछ नहीं है तो -1।

## देखें

* टाइपडेफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IParagraph](../../iparagraph/)
* क्लास [ParagraphCollection](../)
* क्लास [IParagraphCollection](../../iparagraphcollection/)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)