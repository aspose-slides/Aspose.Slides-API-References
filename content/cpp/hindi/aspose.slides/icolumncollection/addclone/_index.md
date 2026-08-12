---
title: AddClone()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट टेम्पलेट पंक्ति की एक प्रति बनाता है और उसे तालिका के नीचे जोड़ता है।
type: docs
weight: 14
url: /hi/aspose.slides/icolumncollection/addclone/
---
## IColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) विधि

निर्दिष्ट टेम्पलेट पंक्ति की एक प्रति बनाता है और उसे तालिका के नीचे जोड़ता है।

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) जो एक टेम्पलेट के रूप में उपयोग किया जाता है। |
| withAttachedColumns | **bool** | टेम्पलेट पंक्ति से जुड़े सभी कॉलम को भी कॉपी करने के लिए True। |

### रिटर्न मान

जोड़े गए कॉलम।

## संबंधित देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IColumn](../../icolumn/)
* क्लास [IColumnCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)