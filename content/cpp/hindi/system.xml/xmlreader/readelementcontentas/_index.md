---
title: ReadElementContentAs()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: वांछित प्रकार के रूप में तत्व की सामग्री पढ़ता है।
type: docs
weight: 586
url: /hi/system.xml/xmlreader/readelementcontentas/
---
## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) विधि

वांछित प्रकार के रूप में तत्व की सामग्री पढ़ता है।

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | लौटाए जाने वाले मान के प्रकार। |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | एक [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) वस्तु जो प्रकार रूपांतरण से सम्बंधित किसी भी नेमस्पेस उपसर्ग को हल करने के लिए उपयोग की जाती है। |

### रिटर्न वैल्यू

वांछित टाइप्ड ऑब्जेक्ट में परिवर्तित तत्व की सामग्री।

## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>, String, String) विधि

जाँचता है कि निर्दिष्ट लोकेल नाम और नेमस्पेस URI वर्तमान तत्व से मेल खाता है या नहीं, फिर वांछित प्रकार के रूप में तत्व की सामग्री पढ़ता है।

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver, String localName, String namespaceURI)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | लौटाए जाने वाले मान के प्रकार। |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | एक [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) वस्तु जो प्रकार रूपांतरण से सम्बंधित किसी भी नेमस्पेस उपसर्ग को हल करने के लिए उपयोग की जाती है। |
| localName | [String](../../../system/string/) | तत्व का स्थानीय नाम। |
| namespaceURI | [String](../../../system/string/) | तत्व का नेमस्पेस URI। |

### रिटर्न वैल्यू

वांछित टाइप्ड ऑब्जेक्ट में परिवर्तित तत्व की सामग्री।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Class [XmlReader](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)