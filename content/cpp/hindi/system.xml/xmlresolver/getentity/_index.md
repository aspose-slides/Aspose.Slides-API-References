---
title: GetEntity()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: जब व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो यह एक URI को उस वस्तु से जोड़ता है जिसमें वास्तविक संसाधन होता है।
type: docs
weight: 14
url: /hi/system.xml/xmlresolver/getentity/
---
## XmlResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) विधि

जब किसी व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो यह एक URI को उस वस्तु से जोड़ता है जिसमें वास्तविक संसाधन होता है।

```cpp
virtual SharedPtr<Object> System::Xml::XmlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn)=0
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/) कॉल से प्राप्त URI। |
| role | [String](../../../system/string/) | वर्तमान में उपयोग नहीं किया जाता। |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | वापसी के लिये वस्तु का प्रकार। वर्तमान संस्करण केवल Stream वस्तुओं को लौटाता है। |

### रिटर्न मान

यदि स्ट्रीम के अलावा कोई प्रकार निर्दिष्ट किया गया हो तो एक स्ट्रीम वस्तु या **nullptr**।

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [Object](../../../system/object/)
* क्लास [Uri](../../../system/uri/)
* क्लास [String](../../../system/string/)
* क्लास [TypeInfo](../../../system/typeinfo/)
* क्लास [XmlResolver](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)