---
title: ResolveUri()
second_title: Aspose.Slides for C++ API संदर्भ
description: आधार और सापेक्ष URI से पूर्ण URI को हल करता है।
type: docs
weight: 66
url: /hi/system.xml/xmlurlresolver/resolveuri/
---
## XmlUrlResolver::ResolveUri(SharedPtr\<Uri\>, String) मेथड


आधार और सापेक्ष URI से पूर्ण URI को हल करता है।

```cpp
SharedPtr<Uri> System::Xml::XmlUrlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | सापेक्ष URI को हल करने के लिए उपयोग किया गया आधार URI। |
| relativeUri | [String](../../../system/string/) | हल करने वाला URI। URI पूर्ण या सापेक्ष हो सकता है। यदि पूर्ण है, तो यह मान प्रभावी रूप से **baseUri** मान को प्रतिस्थापित करता है। यदि सापेक्ष है, तो यह **baseUri** के साथ मिलकर एक पूर्ण URI बनाता है। |

### वापसी मान

पूर्ण URI, या **nullptr** यदि सापेक्ष URI को हल नहीं किया जा सकता।

## देखें भी

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [Uri](../../../system/uri/)
* क्लास [String](../../../system/string/)
* क्लास [XmlUrlResolver](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)