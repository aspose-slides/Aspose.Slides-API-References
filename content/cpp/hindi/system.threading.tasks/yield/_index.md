---
title: Yield()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: एक awaitable टास्क बनाता है जो await किए जाने पर असिंक्रोनस रूप से वर्तमान कॉन्टेक्स्ट पर वापस लौटता है।
type: docs
weight: 222
url: /hi/system.threading.tasks/yield/
---
## System::Threading::Tasks::Yield() फ़ंक्शन

Creates an awaitable task that asynchronously yields back to the current context when awaited.

```cpp
Runtime::CompilerServices::YieldAwaitable System::Threading::Tasks::Yield()
```

### रिटर्न वैल्यू

एक YieldAwaitable जिसे await किया जा सकता है ताकि नियंत्रण को yield किया जा सके।

## टिप्पणियाँ

यह मेथड असिंक्रोनस मेथड को नियंत्रण yield करने के लिए मजबूर करने में उपयोगी है, जिससे अन्य लंबित कार्यों को जारी रखने से पहले प्रोसेस किया जा सके।

## देखें

* क्लास [YieldAwaitable](../../system.runtime.compilerservices/yieldawaitable/)
* नेमस्पेस [System::Threading::Tasks](../)
* लाइब्रेरी [Aspose.Slides](../../)