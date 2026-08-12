---
title: SetNamedItem()
second_title: Aspose.Slides for C++ API संदर्भ
description: "XmlNode को उसके XmlNode::get_Name परिणाम का उपयोग करके जोड़ता है।"
type: docs
weight: 14
url: /hi/system.xml/xmlattributecollection/setnameditem/
---
## XmlAttributeCollection::SetNamedItem(SharedPtr\<XmlNode\>) विधि

एक [XmlNode](../../xmlnode/) को उसके [XmlNode::get_Name](../../xmlnode/get_name/) परिणाम का उपयोग करके जोड़ता है।

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttributeCollection::SetNamedItem(SharedPtr<XmlNode> node) override
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | इस संग्रह में संग्रहीत करने के लिये एक गुण नोड। नोड बाद में नोड के नाम का प्रयोग करके पहुँचा जा सकेगा। यदि उसी नाम का नोड पहले से संग्रह में मौजूद है, तो उसे नए नोड से बदल दिया जाता है; अन्यथा, नोड को संग्रह के अंत में जोड़ा जाता है। |

### रिटर्न मान

यदि **node** समान नाम वाले मौजूदा नोड को बदलता है, तो पुराना नोड वापस किया जाता है; अन्यथा, जोड़ा गया नोड वापस किया जाता है।

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlNode](../../xmlnode/)
* क्लास [XmlAttributeCollection](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)