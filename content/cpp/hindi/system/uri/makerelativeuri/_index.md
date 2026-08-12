---
title: MakeRelativeUri()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: वर्तमान और निर्दिष्ट Uri वस्तुओं द्वारा प्रतिनिधित्व किए गए URI के बीच अंतर निर्धारित करता है।
type: docs
weight: 352
url: /hi/system/uri/makerelativeuri/
---
## Uri::MakeRelativeUri(const SharedPtr\<Uri\>\&) विधि

वर्तमान और निर्दिष्ट [Uri](../) वस्तुओं द्वारा प्रतिनिधित्व किए गए URI के बीच अंतर निर्धारित करता है।

```cpp
SharedPtr<Uri> System::Uri::MakeRelativeUri(const SharedPtr<Uri> &uri)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| uri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | तुलनात्मक मान |

### Return Value

यदि वर्तमान वस्तु और **toUri** द्वारा प्रतिनिधित्व किए गए URI के होस्टनेम और स्कीम समान हैं, तो यह विधि एक सापेक्ष [Uri](../) लौटाती है जो वर्तमान URI उदाहरण में जोड़ने पर **toUri** प्राप्त करता है। यदि होस्टनेम या स्कीम अलग है, तो यह विधि एक [Uri](../) वस्तु लौटाती है जो **uri** पैरामीटर का प्रतिनिधित्व करती है।

## See Also

* टाइपडेफ़ [SharedPtr](../../sharedptr/)
* क्लास [Uri](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)