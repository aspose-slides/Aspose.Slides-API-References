---
title: get_SchemaInfo()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: वर्तमान नोड को स्कीमा वैधता के परिणामस्वरूप असाइन किया गया स्कीमा जानकारी लौटाता है।
type: docs
weight: 196
url: /hi/system.xml/xmlreader/get_schemainfo/
---
## XmlReader::get_SchemaInfo() विधि


वर्तमान नोड को स्कीमा वैधता के परिणामस्वरूप असाइन किया गया स्कीमा जानकारी लौटाता है।

```cpp
virtual SharedPtr<Schema::IXmlSchemaInfo> System::Xml::XmlReader::get_SchemaInfo()
```


### रिटर्न मान

वर्तमान नोड के लिए स्कीमा जानकारी युक्त एक IXmlSchemaInfo ऑब्जेक्ट। [Schema](../../../system.xml.schema/) जानकारी को तत्वों, एट्रिब्यूट्स, या गैर-शून्य [XmlReader::get_ValueType](../get_valuetype/) मान वाले टेक्स्ट नोड्स पर सेट किया जा सकता है। यदि वर्तमान नोड उपरोक्त नोड प्रकारों में से कोई नहीं है, या यदि [XmlReader](../) इंस्टेंस स्कीमा जानकारी रिपोर्ट नहीं करता है, तो यह विधि **nullptr** लौटाती है। यदि इस विधि को [XmlTextReader](../../xmltextreader/) या [XmlValidatingReader](../../xmlvalidatingreader/) ऑब्जेक्ट से कॉल किया जाता है, तो यह विधि हमेशा **nullptr** लौटाती है। ये [XmlReader](../) कार्यान्वयन get_SchemaInfo विधि के माध्यम से स्कीमा जानकारी उजागर नहीं करते हैं।

## संबंधित देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IXmlSchemaInfo](../../../system.xml.schema/ixmlschemainfo/)
* क्लास [XmlReader](../)
* नामस्थान [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)