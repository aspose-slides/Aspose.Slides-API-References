---
title: GetUnspecifiedDefaultAttributes()
second_title: Aspose.Slides for C++ API संदर्भ
description: "डिफ़ॉल्ट विशेषताओं पर पहचान बाधाओं को सत्यापित करता है और किसी भी ऐसी विशेषता जिसके डिफ़ॉल्ट मान हैं और जिन्हें तत्व संदर्भ में पहले XmlSchemaValidator::ValidateAttribute विधि का उपयोग करके सत्यापित नहीं किया गया था, के लिए निर्दिष्ट List को XmlSchemaAttribute ऑब्जेक्ट्स से भरता है।"
type: docs
weight: 157
url: /hi/system.xml.schema/xmlschemavalidator/getunspecifieddefaultattributes/
---
## XmlSchemaValidator::GetUnspecifiedDefaultAttributes(const SharedPtr\<Collections::Generic::List\<SharedPtr\<Object\>\>\>\&) विधि

डिफ़ॉल्ट विशेषताओं पर पहचान बाधाओं को मान्य करता है और किसी भी विशेषता जिसके डिफ़ॉल्ट मान हैं और जिन्हें तत्व संदर्भ में पहले [XmlSchemaValidator::ValidateAttribute](../validateattribute/) विधि का उपयोग करके मान्य नहीं किया गया है, के लिए निर्दिष्ट List को [XmlSchemaAttribute](../../xmlschemaattribute/) ऑब्जेक्ट्स से भरता है।

```cpp
void System::Xml::Schema::XmlSchemaValidator::GetUnspecifiedDefaultAttributes(const SharedPtr<Collections::Generic::List<SharedPtr<Object>>> &defaultAttributes)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| defaultAttributes | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::List](../../../system.collections.generic/list/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\>\& | एक List जिसे [XmlSchemaAttribute](../../xmlschemaattribute/) ऑब्जेक्ट्स से भरना है, उन सभी विशेषताओं के लिए जो तत्व संदर्भ में मान्य करने के दौरान अभी तक नहीं मिले हैं। |

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../../../system.collections.generic/list/)
* Class [Object](../../../system/object/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)