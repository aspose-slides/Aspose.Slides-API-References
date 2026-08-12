---
title: GetEntity()
second_title: Aspose.Slides for C++ API रेफ़रेंस
description: एक URI को उस वस्तु से जोड़ता है जो वास्तविक संसाधन रखती है।
type: docs
weight: 53
url: /hi/system.xml/xmlurlresolver/getentity/
---
## XmlUrlResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) विधि

एक URI को उस वस्तु से मैप करता है जो वास्तविक संसाधन रखती है।

```cpp
SharedPtr<Object> System::Xml::XmlUrlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../../xmlresolver/resolveuri/) कॉल से लौटाया गया URI। |
| role | [String](../../../system/string/) | वर्तमान में उपयोग नहीं किया गया है। |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | वापस करने वाली वस्तु का प्रकार। वर्तमान कार्यान्वयन केवल Stream वस्तुएँ लौटाता है। |

### रिटर्न वैल्यू

एक Stream वस्तु या **nullptr** यदि stream के अलावा कोई अन्य प्रकार निर्दिष्ट किया गया हो।

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlUrlResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)