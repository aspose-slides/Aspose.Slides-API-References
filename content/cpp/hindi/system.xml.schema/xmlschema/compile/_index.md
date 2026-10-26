---
title: Compile()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: XML SchemaObject Model (SOM) को सत्यापन के लिए स्कीमा जानकारी में संकलित करता है। प्रोग्राम द्वारा निर्मित SOM की वाक्यात्मक और अर्थपूर्ण संरचना की जाँच करने के लिए उपयोग किया जाता है। संकलन के दौरान अर्थपूर्ण सत्यापन जांच की जाती है।
type: docs
weight: 352
url: /hi/system.xml.schema/xmlschema/compile/
---
## XmlSchema::Compile(ValidationEventHandler) विधि

XML [Schema](../../)[Object](../../../system/object/) मॉडल (SOM) को सत्यापन के लिए स्कीमा जानकारी में संकलित करता है। प्रोग्रामेटिक रूप से निर्मित SOM की वाक्यात्मक और अर्थपूर्ण संरचना की जाँच करने के लिए उपयोग किया जाता है। संकलन के दौरान अर्थपूर्ण सत्यापन जांच की जाती है।

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | वैलिडेशन इवेंट हैंडलर जो XML [Schema](../../) वैलिडेशन त्रुटियों के बारे में जानकारी प्राप्त करता है। |

## XmlSchema::Compile(ValidationEventHandler, const SharedPtr\<XmlResolver\>\&) विधि

XML [Schema](../../)[Object](../../../system/object/) मॉडल (SOM) को सत्यापन के लिए स्कीमा जानकारी में संकलित करता है। प्रोग्रामेटिक रूप से निर्मित SOM की वाक्यात्मक और अर्थपूर्ण संरचना की जाँच करने के लिए उपयोग किया जाता है। संकलन के दौरान अर्थपूर्ण सत्यापन जांच की जाती है।

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler, const SharedPtr<XmlResolver> &resolver)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | वैलिडेशन इवेंट हैंडलर जो XML [Schema](../../) वैलिडेशन त्रुटियों के बारे में जानकारी प्राप्त करता है। |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) जो **include** और **import** तत्वों में संदर्भित नेमस्पेस को हल करने के लिए उपयोग किया जाता है। |

## संबंधित देखें

* टाइपडिफ़ [ValidationEventHandler](../../validationeventhandler/)
* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlSchema](../)
* क्लास [XmlResolver](../../../system.xml/xmlresolver/)
* नामस्थान [System::Xml::Schema](../../)
* लाइब्रेरी [Aspose.Slides](../../../)