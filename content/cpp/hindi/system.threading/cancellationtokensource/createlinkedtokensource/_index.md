---
title: CreateLinkedTokenSource()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक लिंक्ड टोकन स्रोत बनाता है जो प्रदान किए गए किसी भी टोकन के रद्द होने पर रद्द हो जाता है।
type: docs
weight: 66
url: /hi/system.threading/cancellationtokensource/createlinkedtokensource/
---
## CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken\&, const CancellationToken\&) method


एक लिंक्ड टोकन स्रोत बनाता है जो प्रदान किए गए किसी भी टोकन के रद्द होने पर रद्द हो जाता है।

```cpp
static SharedPtr<CancellationTokenSource> System::Threading::CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken &token1, const CancellationToken &token2)
```


### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| token1 | const [CancellationToken](../../cancellationtoken/)\& | मॉनीटर करने के लिये पहला कैंसेलेशन टोकन। |
| token2 | const [CancellationToken](../../cancellationtoken/)\& | मॉनीटर करने के लिये दूसरा कैंसेलेशन टोकन। |

### रिटर्न वैल्यू

नया टोकन स्रोत जो किसी भी इनपुट टोकन के रद्द होने पर रद्द हो जाएगा।

## टिप्पणियाँ

यदि कोई भी इनपुट टोकन पहले से ही रद्द हो चुका है तो लौटाया गया स्रोत तुरंत रद्द हो जाएगा।

## अधिक देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [CancellationTokenSource](../)
* Class [CancellationToken](../../cancellationtoken/)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)