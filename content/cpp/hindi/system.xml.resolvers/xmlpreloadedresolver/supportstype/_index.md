---
title: SupportsType()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्धारित करता है कि रिज़ॉल्वर केवल Stream के अलावा अन्य Types का समर्थन करता है या नहीं।
type: docs
weight: 66
url: /hi/system.xml.resolvers/xmlpreloadedresolver/supportstype/
---
## XmlPreloadedResolver::SupportsType(SharedPtr\<Uri\>, const TypeInfo\&) विधि


निर्धारित करता है कि रिज़ॉल्वर केवल Stream के अलावा अन्य Types का समर्थन करता है या नहीं।

```cpp
bool System::Xml::Resolvers::XmlPreloadedResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type) override
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | जाँचने के लिए पूर्ण URI। |
| type | const [TypeInfo](../../../system/typeinfo/)\& | वापस करने के लिए Type। |

### रिटर्न वैल्यू

**true** अगर Type समर्थित है; अन्यथा **false**.

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [Uri](../../../system/uri/)
* क्लास [TypeInfo](../../../system/typeinfo/)
* क्लास [XmlPreloadedResolver](../)
* नेमस्पेस [System::Xml::Resolvers](../../)
* लाइब्रेरी [Aspose.Slides](../../../)