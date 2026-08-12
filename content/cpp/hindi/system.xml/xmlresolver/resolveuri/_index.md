---
title: ResolveUri()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: जब एक व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो यह बेस और रिलेटिव URI से पूर्ण URI निर्धारित करता है।
type: docs
weight: 27
url: /hi/system.xml/xmlresolver/resolveuri/
---
## XmlResolver::ResolveUri(SharedPtr\<Uri\>, String) मेथड

जब एक व्युत्पन्न वर्ग में प्रतिस्थापित किया जाता है, तो यह बेस और रिलेटिव URI से पूर्ण URI निर्धारित करता है।

```cpp
virtual SharedPtr<Uri> System::Xml::XmlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | रिलेटिव URI को हल करने के लिए उपयोग किया गया बेस URI। |
| relativeUri | [String](../../../system/string/) | हल करने के लिए URI। URI पूर्ण या रिलेटिव हो सकता है। यदि पूर्ण हो, तो यह मान प्रभावी रूप से **baseUri** मान को प्रतिस्थापित करता है। यदि रिलेटिव हो, तो यह **baseUri** के साथ मिलकर एक पूर्ण URI बनाता है। |

### वापसी मान

पूर्ण URI, या **nullptr** यदि रिलेटिव URI को हल नहीं किया जा सकता।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [Uri](../../../system/uri/)
* क्लास [String](../../../system/string/)
* क्लास [XmlResolver](../)
* नामस्थान [System::Xml](../../)
* Library [Aspose.Slides](../../../)