---
title: AddClone()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट टेम्पलेट पंक्ति की एक प्रति बनाता है और उसे तालिका के नीचे सम्मिलित करता है।
type: docs
weight: 53
url: /hi/aspose.slides/columncollection/addclone/
---
## ColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) विधि


निर्दिष्ट टेम्पलेट पंक्ति की एक प्रति बनाता है और उसे तालिका के नीचे सम्मिलित करता है।

```cpp
System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::ColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns) override
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) जो टेम्पलेट के रूप में उपयोग किया जाता है। |
| withAttachedColumns | **bool** | True ताकि टेम्पलेट पंक्ति से जुड़ी सभी कॉलम भी कॉपी हो जाएँ। |

### वापसी मान

जोड़े गए कॉलम।

## देखें

* टाइपडेफ़ [ArrayPtr](../../../system/arrayptr/)
* टाइपडेफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IColumn](../../icolumn/)
* क्लास [ColumnCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)