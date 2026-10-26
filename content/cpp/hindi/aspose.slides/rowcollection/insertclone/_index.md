---
title: InsertClone()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट टेम्पलेट पंक्ति की एक प्रति बनाता है और उसे तालिका में निर्दिष्ट स्थिति पर डालता है।
type: docs
weight: 66
url: /hi/aspose.slides/rowcollection/insertclone/
---
## RowCollection::InsertClone(int32_t, System::SharedPtr\<IRow\>, bool) मेथड


निर्दिष्ट टेम्पलेट पंक्ति की एक कॉपी बनाता है और इसे तालिका में निर्दिष्ट स्थिति पर डालता है।

```cpp
System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::RowCollection::InsertClone(int32_t index, System::SharedPtr<IRow> templ, bool withAttachedRows) override
```


### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | **int32_t** | नई पंक्ति का इंडेक्स। |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) जो टेम्पलेट के रूप में उपयोग होता है। |
| withAttachedRows | **bool** | True यदि टेम्पलेट पंक्ति से जुड़ी सभी पंक्तियों को भी कॉपी करना है। |

### रिटर्न वैल्यू

डाली गई पंक्तियाँ।

## संबंधित देखें

* टाइपडिफ़ [ArrayPtr](../../../system/arrayptr/)
* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IRow](../../irow/)
* क्लास [RowCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)