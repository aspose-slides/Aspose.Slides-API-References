---
title: InsertClone()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट टेम्पलेट कॉलम की एक प्रति बनाता है और उसे तालिका में निर्दिष्ट स्थिति पर सम्मिलित करता है।
type: docs
weight: 27
url: /hi/aspose.slides/icolumncollection/insertclone/
---
## IColumnCollection::InsertClone(int32_t, System::SharedPtr\<IColumn\>, bool) विधि

एक निर्दिष्ट टेम्पलेट कॉलम की प्रति बनाता है और उसे तालिका में निर्दिष्ट स्थान पर सम्मिलित करता है।

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::InsertClone(int32_t index, System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | नए कॉलम का इंडेक्स। |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) जिसे टेम्पलेट के रूप में उपयोग किया जाता है। |
| withAttachedColumns | **bool** | टेम्पलेट कॉलम से जुड़ी सभी कॉलमों को भी कॉपी करने के लिए true। |

### वापसी मान

डाली गई कॉलम।

## संबंधित देखें

* टाइपडिफ़ [ArrayPtr](../../../system/arrayptr/)
* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IColumn](../../icolumn/)
* क्लास [IColumnCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)