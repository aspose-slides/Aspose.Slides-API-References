---
title: ScopeGuard
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: वह सेवा क्लास जो एक विशिष्ट फ़ंक्शन ऑब्जेक्ट को चलाने के लिए, जब क्लास का एक इंस्टेंस स्कोप से बाहर हो जाता है, सेवाएँ प्रदान करती है।
type: docs
weight: 1886
url: /hi/system/scopeguard/
---
## ScopeGuard struct

क्लास वह सेवा प्रदान करता है जो एक विशिष्ट फ़ंक्शन ऑब्जेक्ट को चलाने के लिए जब क्लास का एक इंस्टेंस स्कोप से बाहर हो जाता है, निष्पादित करता है।

```cpp
template<typename F>class ScopeGuard
```

### Template parameters

| Parameter | Description |
| --- | --- |
| F | ScopedGuard क्लास के इंस्टेंस द्वारा इनवोक किए जाने वाले फ़ंक्शन ऑब्जेक्ट का प्रकार |

## Methods

| Method | Description |
| --- | --- |
| void [Disable](./disable/)() | गार्ड इनवॉकेशन को निष्क्रिय करता है। |
| [ScopeGuard](./scopeguard/)(F) | निर्दिष्ट फ़ंक्शन ऑब्जेक्ट को इनवोक करने के लिए सेट की गई एक इंस्टेंस बनाता है। |
| [~ScopeGuard](./~scopeguard/)() | कंस्ट्रक्टर को पास किए गए फ़ंक्शन ऑब्जेक्ट को इनवोक करता है। |

## See Also

* नामस्थान [System](../)
* लाइब्रेरी [Aspose.Slides](../../)