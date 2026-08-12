---
title: ResolveUri()
second_title: Aspose.Slides for C++ API संदर्भ
description: बेस और रिलेटिव URI से absolute URI को हल करता है।
type: docs
weight: 1
url: /hi/aspose.slides.import/iexternalresourceresolver/resolveuri/
---
## IExternalResourceResolver::ResolveUri(System::String, System::String) विधि


बेस और रिलेटिव URI से absolute URI को हल करता है।

```cpp
virtual System::String Aspose::Slides::Import::IExternalResourceResolver::ResolveUri(System::String baseUri, System::String relativeUri)=0
```


### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| baseUri | [System::String](../../../system/string/) | लिंकिंग ऑब्जेक्ट्स का Base URI |
| relativeUri | [System::String](../../../system/string/) | लिंक्ड ऑब्जेक्ट के लिए Relative URI |

### वापसी मान

यदि Relative URI हल नहीं किया जा सकता तो Absolute URI या null।

## देखें भी

* क्लास [String](../../../system/string/)
* क्लास [IExternalResourceResolver](../)
* नेमस्पेस [Aspose::Slides::Import](../../)
* लाइब्रेरी [Aspose.Slides](../../../)