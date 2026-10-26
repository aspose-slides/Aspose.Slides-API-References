---
title: MakeRelative()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: दो Uri उदाहरणों के बीच अंतर निर्धारित करता है।
type: docs
weight: 365
url: /hi/system/uri/makerelative/
---
## Uri::MakeRelative(const SharedPtr\<Uri\>\&) विधि


दो [Uri](../) उदाहरणों के बीच अंतर निर्धारित करता है।

```cpp
String System::Uri::MakeRelative(const SharedPtr<Uri> &toUri)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| toUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | वर्तमान URI की तुलना के लिए URI |

### रिटर्न मान

यदि वर्तमान ऑब्जेक्ट और **toUri** द्वारा प्रतिनिधित्व किए गए URIs के होस्टनेम और स्कीम समान हैं, तो यह विधि एक [String](../../string/) लौटाती है जो एक रिलेटिव [Uri](../) का प्रतिनिधित्व करती है, जिसे वर्तमान URI उदाहरण में जोड़ने पर **toUri** प्राप्त होता है। यदि होस्टनेम या स्कीम अलग है, तो यह विधि एक [String](../../string/) लौटाती है जो **uri** पैरामीटर का प्रतिनिधित्व करती है।

## देखें

* टाइपडिफ [SharedPtr](../../sharedptr/)
* क्लास [String](../../string/)
* क्लास [Uri](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)