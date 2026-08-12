---
title: IsStartElement()
second_title: Aspose.Slides for C++ API संदर्भ
description: "XmlReader::MoveToContent को कॉल करता है और जांचता है कि वर्तमान सामग्री नोड एक प्रारंभ टैग या खाली तत्व टैग है या नहीं।"
type: docs
weight: 885
url: /hi/system.xml/xmlreader/isstartelement/
---
## XmlReader::IsStartElement() विधि

[XmlReader::MoveToContent](../movetocontent/) को कॉल करता है और जांचता है कि वर्तमान सामग्री नोड एक प्रारंभ टैग या खाली तत्व टैग है या नहीं।

```cpp
virtual bool System::Xml::XmlReader::IsStartElement()
```

### वापसी मान

**true** यदि [XmlReader::MoveToContent](../movetocontent/) द्वारा एक प्रारंभ टैग या खाली तत्व टैग पाया जाता है; **false** यदि [XmlNodeType::Element](../../xmlnodetype/) के अलावा कोई अन्य नोड प्रकार मिला।

## XmlReader::IsStartElement(String) विधि

[XmlReader::MoveToContent](../movetocontent/) को कॉल करता है और जांचता है कि वर्तमान सामग्री नोड एक प्रारंभ टैग या खाली तत्व टैग है और क्या पाया गया तत्व का [XmlReader::get_Name](../get_name/) मान दिए गए आर्ग्युमेंट से मेल खाता है।

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String name)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | [String](../../../system/string/) | पाया गया तत्व के **Name** मान के खिलाफ मिलान करने वाली स्ट्रिंग। |

### वापसी मान

**true** यदि परिणामी नोड एक तत्व है और **Name** मान निर्दिष्ट स्ट्रिंग से मेल खाता है। **false** यदि [XmlNodeType::Element](../../xmlnodetype/) के अलावा कोई अन्य नोड प्रकार मिला या तत्व का **Name** मान निर्दिष्ट स्ट्रिंग से मेल नहीं खाता।

## XmlReader::IsStartElement(String, String) विधि

[XmlReader::MoveToContent](../movetocontent/) को कॉल करता है और जांचता है कि वर्तमान सामग्री नोड एक प्रारंभ टैग या खाली तत्व टैग है और क्या पाया गया तत्व का [XmlReader::get_LocalName](../get_localname/) और [XmlReader::get_NamespaceURI](../get_namespaceuri/) मान दिए गए स्ट्रिंग्स से मेल खाते हैं।

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String localname, String ns)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| localname | [String](../../../system/string/) | पाया गया तत्व के **LocalName** मान के खिलाफ मिलान करने वाली स्ट्रिंग। |
| ns | [String](../../../system/string/) | पाया गया तत्व के **NamespaceURI** मान के खिलाफ मिलान करने वाली स्ट्रिंग। |

### वापसी मान

**true** यदि परिणामी नोड एक तत्व है। **false** यदि [XmlNodeType::Element](../../xmlnodetype/) के अलावा कोई अन्य नोड प्रकार मिला या **LocalName** और **NamespaceURI** मान निर्दिष्ट स्ट्रिंग्स से मेल नहीं खाते।

## संबंधित देखें

* क्लास [XmlReader](../)
* क्लास [String](../../../system/string/)
* नामस्थान [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)