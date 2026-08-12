---
title: InsertClone()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्दिष्ट टेम्पलेट पंक्ति की एक प्रति बनाता है और उसे तालिका में निर्दिष्ट स्थिति में सम्मिलित करता है।
type: docs
weight: 27
url: /hi/aspose.slides/irowcollection/insertclone/
---
## IRowCollection::InsertClone(int32_t, System::SharedPtr\<IRow\>, bool) विधि

निर्दिष्ट टेम्पलेट पंक्ति की एक प्रति बनाता है और उसे तालिका में निर्दिष्ट स्थिति में सम्मिलित करता है।

```cpp
virtual System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::IRowCollection::InsertClone(int32_t index, System::SharedPtr<IRow> templ, bool withAttachedRows)=0
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | नई पंक्ति का अनुक्रमांक। |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) जिसे टेम्पलेट के रूप में उपयोग किया जाता है। |
| withAttachedRows | **bool** | True टेम्पलेट पंक्ति से जुड़ी सभी पंक्तियों को भी कॉपी करने के लिए। |

### वापसी मान

डाली गई पंक्तियाँ।

## और देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IRow](../../irow/)
* Class [IRowCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)