---
title: ReadContentAs()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट प्रकार के एक ऑब्जेक्ट के रूप में सामग्री को पढ़ता है।
type: docs
weight: 456
url: /hi/system.xml/xmlreader/readcontentas/
---
## XmlReader::ReadContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) मेथड

पहले से निर्दिष्ट प्रकार के एक ऑब्जेक्ट के रूप में सामग्री को पढ़ता है।

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | वापसी किए जाने वाले मान का प्रकार। |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | एक [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) ऑब्जेक्ट जिसका उपयोग प्रकार रूपांतरण से संबंधित किसी भी नेमस्पेस उपसर्ग को हल करने के लिए किया जाता है। उदाहरण के लिए, इसे [XmlQualifiedName](../../xmlqualifiedname/) ऑब्जेक्ट को **xs:string** में बदलते समय उपयोग किया जा सकता है। यह मान **nullptr** हो सकता है। |

### रिटर्न मान

अनुरोधित प्रकार में परिवर्तित किया गया संयोजित टेक्स्ट सामग्री या एट्रिब्यूट मान।

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [Object](../../../system/object/)
* क्लास [TypeInfo](../../../system/typeinfo/)
* क्लास [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* क्लास [XmlReader](../)
* नामस्थान [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)