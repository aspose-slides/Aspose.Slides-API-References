---
title: Delay()
second_title: Aspose.Slides के लिये C++ API संदर्भ
description: एक टास्क बनाता है जो समय देरी के बाद पूरा हो जाता है।
type: docs
weight: 105
url: /hi/system.threading.tasks/delay/
---
## System::Threading::Tasks::Delay(int32_t) फ़ंक्शन

एक टास्क बनाता है जो समय देरी के बाद पूरा हो जाता है।

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay)
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | वापसी टास्क को पूरा करने से पहले प्रतीक्षा करने वाले मिलीसेकंड की संख्या, या -1 अनिश्चित काल तक प्रतीक्षा करने के लिए। |

### वापसी मान

एक टास्क जो समय देरी को दर्शाता है।

## System::Threading::Tasks::Delay(int32_t, const CancellationToken&) फ़ंक्शन

एक टास्क बनाता है जो समय देरी के बाद पूरा हो जाता है और रद्द किया जा सकता है।

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay, const CancellationToken &cancellationToken)
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | वापसी टास्क को पूरा करने से पहले प्रतीक्षा करने वाले मिलीसेकंड की संख्या, या -1 अनिश्चित काल तक प्रतीक्षा करने के लिए। |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | देरी को रद्द करने के लिये उपयोग किया जाने वाला कैंसलेशन टोकन। |

### वापसी मान

एक टास्क जो समय देरी को दर्शाता है।

## संबंधित देखें

* टाइपडिफ [TaskPtr](../../system/taskptr/)
* क्लास [CancellationToken](../../system.threading/cancellationtoken/)
* नेमस्पेस [System::Threading::Tasks](../)
* लाइब्रेरी [Aspose.Slides](../../)