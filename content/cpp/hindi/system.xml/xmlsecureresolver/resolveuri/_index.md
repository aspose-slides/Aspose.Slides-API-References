---
title: ResolveUri()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: बेस और रिलेटिव URI से एब्सॉल्यूट URI को हल करता है, आधारभूत XmlResolver पर ResolveUri को कॉल करके।
type: docs
weight: 40
url: /hi/system.xml/xmlsecureresolver/resolveuri/
---
## XmlSecureResolver::ResolveUri(SharedPtr\<Uri\>, String) विधि


बेस और रिलेटिव URI से एब्सॉल्यूट URI को हल करता है, आधारभूत [XmlResolver](../../xmlresolver/) पर **ResolveUri** को कॉल करके।

```cpp
SharedPtr<Uri> System::Xml::XmlSecureResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | रिलेटिव URI को हल करने के लिए उपयोग किया गया बेस URI। |
| relativeUri | [String](../../../system/string/) | हल करने के लिए URI। यह URI एब्सॉल्यूट या रिलेटिव हो सकता है। यदि एब्सॉल्यूट है, तो यह मान प्रभावी रूप से **baseUri** मान को प्रतिस्थापित करता है। यदि रिलेटिव है, तो यह **baseUri** के साथ मिलकर एक एब्सॉल्यूट URI बनाता है। |

### रिटर्न वैल्यू

एब्सॉल्यूट URI या **nullptr** यदि रिलेटिव URI को हल नहीं किया जा सकता (आधारभूत [XmlResolver](../../xmlresolver/) पर **ResolveUri** को कॉल करके प्राप्त किया जाता है)।

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [Uri](../../../system/uri/)
* क्लास [String](../../../system/string/)
* क्लास [XmlSecureResolver](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)