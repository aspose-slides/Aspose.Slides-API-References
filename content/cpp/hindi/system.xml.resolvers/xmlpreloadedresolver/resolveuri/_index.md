---
title: ResolveUri()
second_title: Aspose.Slides for C++ API संदर्भ
description: बेस और रिलेटिव URI से पूर्ण URI को हल करता है।
type: docs
weight: 40
url: /hi/system.xml.resolvers/xmlpreloadedresolver/resolveuri/
---
## XmlPreloadedResolver::ResolveUri(SharedPtr\<Uri\>, String) विधि

बेस और रिलेटिव URI से पूर्ण URI को हल करता है।

```cpp
SharedPtr<Uri> System::Xml::Resolvers::XmlPreloadedResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | रिलेटिव URI को हल करने के लिए उपयोग किया जाने वाला बेस URI। |
| relativeUri | [String](../../../system/string/) | हल करने के लिए URI। यह URI पूर्ण या रिलेटिव हो सकता है। यदि पूर्ण है, तो यह मान प्रभावी रूप से **baseUri** मान को प्रतिस्थापित कर देता है। यदि रिलेटिव है, तो यह **baseUri** के साथ मिलकर एक पूर्ण URI बनाता है। |

### रिटर्न वैल्यू

[Uri](../../../system/uri/) जो पूर्ण URI का प्रतिनिधित्व करता है या यदि रिलेटिव URI हल नहीं हो सकता है तो **nullptr**।

## संबंधित देखें

* टाइपडेट [SharedPtr](../../../system/sharedptr/)
* क्लास [Uri](../../../system/uri/)
* क्लास [String](../../../system/string/)
* क्लास [XmlPreloadedResolver](../)
* नेमस्पेस [System::Xml::Resolvers](../../)
* लाइब्रेरी [Aspose.Slides](../../../)