---
title: AddClone()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्दिष्ट टेम्प्लेट पंक्ति की एक कॉपी बनाता है और उसे तालिका के नीचे जोड़ता है।
type: docs
weight: 14
url: /hi/aspose.slides/irowcollection/addclone/
---
## IRowCollection::AddClone(System::SharedPtr\<IRow\>, bool) method

निर्दिष्ट टेम्प्लेट पंक्ति की एक कॉपी बनाता है और उसे तालिका के नीचे जोड़ता है।

```cpp
virtual System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::IRowCollection::AddClone(System::SharedPtr<IRow> templ, bool withAttachedRows)=0
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) जो टेम्प्लेट के रूप में उपयोग किया जाता है। |
| withAttachedRows | **bool** | टेम्प्लेट पंक्ति से जुड़ी सभी पंक्तियों की कॉपी भी करने के लिए true। |

### वापसी मान

जोड़ी गई पंक्तियाँ।

## देखें

* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IRow](../../irow/)
* क्लास [IRowCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)