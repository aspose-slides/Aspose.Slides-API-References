---
title: GetEntity()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक URI को ऐसी वस्तु से जोड़ता है जिसमें वास्तविक संसाधन होता है।
type: docs
weight: 53
url: /hi/system.xml.resolvers/xmlpreloadedresolver/getentity/
---
## XmlPreloadedResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) विधि

एक URI को ऐसे वस्तु से मैप करता है जिसमें वास्तविक संसाधन शामिल है।

```cpp
SharedPtr<Object> System::Xml::Resolvers::XmlPreloadedResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | [XmlResolver::ResolveUri(SharedPtr<Uri>,String)](../../../system.xml/xmlresolver/resolveuri/) कॉल से प्राप्त किया गया URI। |
| role | [String](../../../system/string/) | वर्तमान में उपयोग नहीं किया जाता है। |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | वापस करने के लिए वस्तु का प्रकार। [XmlPreloadedResolver](../) URI को जो [String](../../../system/string/) के रूप में जोड़ा गया है, के लिए Stream वस्तुओं और TextReader वस्तुओं का समर्थन करता है। यदि अनुरोधित प्रकार को रिज़ॉल्वर द्वारा समर्थित नहीं किया जाता है, तो एक अपवाद फेंका जाएगा। इस रिज़ॉल्वर द्वारा किसी विशेष **Type** का समर्थन किया जाता है या नहीं, निर्धारित करने के लिए XmlPreloadedResolver::SupportsType(SharedPtr<Uri>,TypeInfo) विधि का प्रयोग करें। |

### रिटर्न मान

वास्तविक स्रोत से मेल खाता हुआ Stream या TextReader वस्तु।

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [Object](../../../system/object/)
* क्लास [Uri](../../../system/uri/)
* क्लास [String](../../../system/string/)
* क्लास [TypeInfo](../../../system/typeinfo/)
* क्लास [XmlPreloadedResolver](../)
* नेमस्पेस [System::Xml::Resolvers](../../)
* लाइब्रेरी [Aspose.Slides](../../../)