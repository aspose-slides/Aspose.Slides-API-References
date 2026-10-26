---
title: Add()
second_title: Aspose.Slides for C++ API संदर्भ
description: दिए गए URL द्वारा स्थित स्कीमा को स्कीमा संग्रह में जोड़ता है।
type: docs
weight: 40
url: /hi/system.xml.schema/xmlschemacollection/add/
---
## XmlSchemaCollection::Add(const String\&, const String\&) विधि

दिए गए URL द्वारा स्थित स्कीमा को स्कीमा संग्रह में जोड़ता है।

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const String &uri)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | स्कीमा से जुड़ा नेमस्पेस URI। XML स्कीमा के लिए, यह सामान्यतः **targetNamespace** होगा। |
| uri | const [String](../../../system/string/)\& | स्कीमा को लोड करने वाले URL को निर्दिष्ट करता है। |

### रिटर्न मान

स्कीमा संग्रह में जोड़ा गया [XmlSchema](../../xmlschema/); यदि जोड़ा जा रहा स्कीमा XDR स्कीमा है या स्कीमा में संकलन त्रुटियां हैं तो **nullptr**।

## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&) विधि

[XmlReader](../../../system.xml/xmlreader/) में निहित स्कीमा को स्कीमा संग्रह में जोड़ता है।

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | स्कीमा से जुड़ा नेमस्पेस URI। XML स्कीमा के लिए, यह सामान्यतः **targetNamespace** होगा। |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) जिसमें जोड़ने के लिए स्कीमा है। |

### रिटर्न मान

स्कीमा संग्रह में जोड़ा गया [XmlSchema](../../xmlschema/); यदि जोड़ा जा रहा स्कीमा XDR स्कीमा है या स्कीमा में संकलन त्रुटियां हैं तो **nullptr**।

## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) विधि

[XmlReader](../../../system.xml/xmlreader/) में निहित स्कीमा को स्कीमा संग्रह में जोड़ता है। निर्दिष्ट [XmlResolver](../../../system.xml/xmlresolver/) का उपयोग किसी भी बाहरी संसाधनों को हल करने के लिए किया जाता है।

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | स्कीमा से जुड़ा नेमस्पेस URI। XML स्कीमा के लिए, यह सामान्यतः **targetNamespace** होगा। |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) जिसमें जोड़ने के लिए स्कीमा है। |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) का उपयोग **include** और **import** तत्वों या **x-schema** एट्रिब्यूट (XDR स्कीमा) में उल्लेखित नेमस्पेस को हल करने के लिए किया जाता है। यदि यह **nullptr** है, तो बाहरी संदर्भ हल नहीं किए जाएंगे। |

### रिटर्न मान

स्कीमा संग्रह में जोड़ा गया [XmlSchema](../../xmlschema/); यदि जोड़ा जा रहा स्कीमा XDR स्कीमा है या स्कीमा में संकलन त्रुटियां हैं तो **nullptr**।

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&) विधि

संग्रह में [XmlSchema](../../xmlschema/) को जोड़ता है।

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | संग्रह में जोड़ने के लिए [XmlSchema](../../xmlschema/)। |

### रिटर्न मान

[XmlSchema](../../xmlschema/) ऑब्जेक्ट।

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) विधि

[XmlSchema](../../xmlschema/) को संग्रह में जोड़ता है। निर्दिष्ट [XmlResolver](../../../system.xml/xmlresolver/) का उपयोग किसी भी बाहरी संदर्भ को हल करने के लिए किया जाता है।

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | संग्रह में जोड़ने के लिए [XmlSchema](../../xmlschema/)। |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) का उपयोग **include** और **import** तत्वों में उल्लेखित नेमस्पेस को हल करने के लिए किया जाता है। यदि यह **nullptr** है, तो बाहरी संदर्भ हल नहीं किए जाएंगे। |

### रिटर्न मान

स्कीमा संग्रह में जोड़ा गया [XmlSchema](../../xmlschema/)।

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchemaCollection\>\&) विधि

दिए गए संग्रह में परिभाषित सभी नेमस्पेस (उनके संबंधित स्कीमा सहित) को इस संग्रह में जोड़ता है।

```cpp
void System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchemaCollection> &schema)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaCollection](../)\>\& | आप इस संग्रह में जोड़ना चाहते हैं [XmlSchemaCollection](../)। |

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlSchema](../../xmlschema/)
* क्लास [String](../../../system/string/)
* क्लास [XmlSchemaCollection](../)
* क्लास [XmlReader](../../../system.xml/xmlreader/)
* क्लास [XmlResolver](../../../system.xml/xmlresolver/)
* नेमस्पेस [System::Xml::Schema](../../)
* लाइब्रेरी [Aspose.Slides](../../../)