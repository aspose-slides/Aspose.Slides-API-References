---
title: AddClone()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: निर्धारित टेम्पलेट पंक्ति की एक प्रति बनाता है और उसे तालिका के नीचे सम्मिलित करता है।
type: docs
weight: 53
url: /hi/aspose.slides/rowcollection/addclone/
---
## RowCollection::AddClone(System::SharedPtr\<IRow\>, bool) विधि

निर्दिष्ट टेम्पलेट पंक्ति की एक प्रति बनाता है और उसे तालिका के निचले भाग में सम्मिलित करता है।

```cpp
System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::RowCollection::AddClone(System::SharedPtr<IRow> templ, bool withAttachedRows) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) जो टेम्पलेट के रूप में प्रयोग किया जाता है। |
| withAttachedRows | **bool** | टेम्पलेट पंक्ति से जुड़ी सभी पंक्तियों को भी कॉपी करने के लिए True। |

### रिटर्न वैल्यू

जोड़ी गई पंक्तियाँ।

## संबंधित देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IRow](../../irow/)
* क्लास [RowCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)