---
title: Add()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: संग्रह के अंत में एक Paragraph जोड़ता है।
type: docs
weight: 27
url: /hi/aspose.slides/iparagraphcollection/add/
---
## IParagraphCollection::Add(System::SharedPtr\<IParagraph\>) विधि

संग्रह के अंत में एक [Paragraph](../../paragraph/) जोड़ता है।

```cpp
virtual void Aspose::Slides::IParagraphCollection::Add(System::SharedPtr<IParagraph> value)=0
```

### Arguments

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | संग्रह के अंत में जोड़ने के लिये [Paragraph](../../paragraph/)। |

## IParagraphCollection::Add(System::SharedPtr\<IParagraphCollection\>) विधि

संग्रह के अंत में [ParagraphCollection](../../paragraphcollection/) की सामग्री जोड़ता है।

```cpp
virtual int32_t Aspose::Slides::IParagraphCollection::Add(System::SharedPtr<IParagraphCollection> value)=0
```

### Arguments

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraphCollection](../)\> | संग्रह के अंत में जोड़ने के लिये [ParagraphCollection](../../paragraphcollection/)। |

### Return Value

इंडेक्स जहाँ [Paragraph](../../paragraph/) जोड़ा गया है या -1 यदि जोड़ने के लिये कुछ नहीं है।

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IParagraph](../../iparagraph/)
* क्लास [IParagraphCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)