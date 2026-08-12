---
title: GetEntity()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: एक URI को उस वस्तु से मैप करता है जिसमें वास्तविक संसाधन होते हैं।
type: docs
weight: 27
url: /hi/system.xml/xmlsecureresolver/getentity/
---
## XmlSecureResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) मेथड

एक URI को उस वस्तु से मैप करता है जिसमें वास्तविक संसाधन होते हैं।

```cpp
SharedPtr<Object> System::Xml::XmlSecureResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI जो [XmlSecureResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/) कॉल से लौटाया जाता है। |
| role | [String](../../../system/string/) | वर्तमान में उपयोग नहीं किया जाता है। |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | वापस करने वाली वस्तु का प्रकार। वर्तमान संस्करण केवल Stream वस्तुएँ लौटाता है। |

### Return Value

आधारभूत [XmlResolver](../../xmlresolver/) पर **GetEntity** को कॉल करने से प्राप्त स्ट्रीम। यदि Stream के अलावा कोई अन्य प्रकार निर्दिष्ट किया जाता है, तो मेथड **nullptr** लौटाता है।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [Object](../../../system/object/)
* क्लास [Uri](../../../system/uri/)
* क्लास [String](../../../system/string/)
* क्लास [TypeInfo](../../../system/typeinfo/)
* क्लास [XmlSecureResolver](../)
* नामस्थान [System::Xml](../../)
* Library [Aspose.Slides](../../../)