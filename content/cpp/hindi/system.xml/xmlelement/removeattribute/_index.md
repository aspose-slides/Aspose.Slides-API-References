---
title: RemoveAttribute()
second_title: C++ के लिए Aspose.Slides API रेफ़रेंस
description: नाम द्वारा एक विशेषता हटाता है।
type: docs
weight: 235
url: /hi/system.xml/xmlelement/removeattribute/
---
## XmlElement::RemoveAttribute(String) विधि

नाम द्वारा एक विशेषता हटाता है।

```cpp
virtual void System::Xml::XmlElement::RemoveAttribute(String name)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| name | [String](../../../system/string/) | हटाने के लिये विशेषता का नाम। यह एक योग्य नाम है। यह मिलते हुए नोड के **get_Name** मान से तुलना किया जाता है। |

## XmlElement::RemoveAttribute(String, String) विधि

निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वाली विशेषता को हटाता है। (यदि हटाई गई विशेषता का डिफ़ॉल्ट मान है, तो उसे तुरंत बदल दिया जाता है)।

```cpp
virtual void System::Xml::XmlElement::RemoveAttribute(String localName, String namespaceURI)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| localName | [String](../../../system/string/) | हटाने के लिये विशेषता का स्थानीय नाम। |
| namespaceURI | [String](../../../system/string/) | हटाने के लिये विशेषता का नेमस्पेस URI। |

## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [XmlElement](../)
* नामस्थान [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)