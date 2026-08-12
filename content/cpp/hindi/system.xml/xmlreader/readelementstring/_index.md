---
title: ReadElementString()
second_title: Aspose.Slides for C++ API संदर्भ
description: "केवल-पाठ तत्व को पढ़ता है। हालांकि, इसके बजाय XmlReader::ReadElementContentAsString विधि का उपयोग करने की अनुशंसा की जाती है, क्योंकि यह इस ऑपरेशन को संभालने का अधिक सीधा तरीका प्रदान करती है।"
type: docs
weight: 859
url: /hi/system.xml/xmlreader/readelementstring/
---
## XmlReader::ReadElementString() विधि

केवल टेक्स्ट वाले तत्व को पढ़ता है। हालांकि, [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) विधि का उपयोग करना अनुशंसित है, क्योंकि यह इस ऑपरेशन को संभालने का अधिक सीधा तरीका प्रदान करता है।

```cpp
virtual String System::Xml::XmlReader::ReadElementString()
```

### रिटर्न मान

पढ़े गए तत्व में निहित टेक्स्ट। यदि तत्व खाली हो तो एक खाली स्ट्रिंग।

## XmlReader::ReadElementString(String) विधि

[XmlReader::get_Name](../get_name/) मान को जांचता है कि वह दी गई स्ट्रिंग से मेल खाता है, इससे पहले कि वह केवल-टेक्स्ट वाले तत्व को पढ़े। हालांकि, [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) विधि का उपयोग करना अनुशंसित है, क्योंकि यह इस ऑपरेशन को संभालने का अधिक सीधा तरीका प्रदान करता है।

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String name)
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| name | [String](../../../system/string/) | जांचने के लिए नाम। |

### रिटर्न मान

पढ़े गए तत्व में निहित टेक्स्ट। यदि तत्व खाली हो तो एक खाली स्ट्रिंग।

## XmlReader::ReadElementString(String, String) विधि

[XmlReader::get_LocalName](../get_localname/) और [XmlReader::get_NamespaceURI](../get_namespaceuri/) मानों को जांचता है कि वे दी गई स्ट्रिंग्स से मेल खाते हैं, इससे पहले कि वह केवल-टेक्स्ट वाले तत्व को पढ़े। हालांकि, [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) विधि का उपयोग करना अनुशंसित है, क्योंकि यह इस ऑपरेशन को संभालने का अधिक सीधा तरीका प्रदान करता है।

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String localname, String ns)
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| localname | [String](../../../system/string/) | जांचने के लिए स्थानीय नाम। |
| ns | [String](../../../system/string/) | जांचने के लिए नेमस्पेस URI। |

### रिटर्न मान

पढ़े गए तत्व में निहित टेक्स्ट। यदि तत्व खाली हो तो एक खाली स्ट्रिंग।

## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [XmlReader](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)