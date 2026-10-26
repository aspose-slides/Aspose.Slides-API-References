---
title: ReadStartElement()
second_title: C++ के लिये Aspose.Slides API संदर्भ
description: जाँचता है कि वर्तमान नोड एक तत्व है और रीडर को अगले नोड तक ले जाता है।
type: docs
weight: 846
url: /hi/system.xml/xmlreader/readstartelement/
---
## XmlReader::ReadStartElement() विधि

जांचता है कि वर्तमान नोड एक तत्व है और रीडर को अगले नोड तक ले जाता है।

```cpp
virtual void System::Xml::XmlReader::ReadStartElement()
```

## XmlReader::ReadStartElement(String) विधि

जांचता है कि वर्तमान कंटेंट नोड दिया गया [XmlReader::get_Name](../get_name/) मान के साथ एक तत्व है और रीडर को अगले नोड तक ले जाता है।

```cpp
virtual void System::Xml::XmlReader::ReadStartElement(String name)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | [String](../../../system/string/) | तत्व का क्वालिफ़ाइड नाम। |

## XmlReader::ReadStartElement(String, String) विधि

जांचता है कि वर्तमान कंटेंट नोड दिए गए [XmlReader::get_LocalName](../get_localname/) और [XmlReader::get_NamespaceURI](../get_namespaceuri/) मानों के साथ एक तत्व है और रीडर को अगले नोड तक ले जाता है।

```cpp
virtual void System::Xml::XmlReader::ReadStartElement(String localname, String ns)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| localname | [String](../../../system/string/) | तत्व का स्थानीय नाम। |
| ns | [String](../../../system/string/) | तत्व का नेमस्पेस URI। |

## संबंधित देखें

* क्लास [XmlReader](../)
* क्लास [String](../../../system/string/)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)