---
title: WaitAny()
second_title: C++ के लिए Aspose.Slides API रेफ़रेंस
description: हैंडलों में से किसी भी हैंडल के फायर होने की प्रतीक्षा करता है।
type: docs
weight: 14
url: /hi/system.threading/waithandle/waitany/
---
## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) विधि


हैंडलों में से किसी भी हैंडल के फायर होने की प्रतीक्षा करता है।

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```


### आर्ग्यूमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | इंतजार करने वाले हैंडल। |
| millisecondsTimeout | int | [Timeout](../../timeout/) के लिए प्रतीक्षा करने के लिए, मिलीसेकंड में; -1 अनंत प्रतीक्षा को दर्शाता है, 0 जांच-और-रिटर्न को, सकारात्मक मान टाइमआउट होते हैं। |

### Return Value

True यदि कोई भी हैंडल फायर हो गया, false यदि टाइमआउट समाप्त हो गया।

## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) विधि


हैंडलों में से किसी भी हैंडल के फायर होने की प्रतीक्षा करता है।

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```


### आर्ग्यूमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | इंतजार करने वाले हैंडल। |
| timeout | [TimeSpan](../../../system/timespan/) | [System::TimeSpan](../../../system/timespan/) वह ऑब्जेक्ट है जो प्रतीक्षा करने के मिलिसेकंड की संख्या दर्शाता है, या [System::TimeSpan](../../../system/timespan/) वह ऑब्जेक्ट है जो अनिश्चित काल तक -1 मिलिसेकंड प्रतीक्षा को दर्शाता है। |

### Return Value

True यदि कोई भी हैंडल फायर हो गया, false यदि टाइमआउट समाप्त हो गया।

## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) विधि


हैंडलों में से किसी भी हैंडल के फायर होने की प्रतीक्षा करता है।

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```


### आर्ग्यूमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | इंतजार करने वाले हैंडल। |

### Return Value

True जब waitHandles में हर तत्व ने सिग्नल प्राप्त किया हो; अन्यथा विधि कभी वापस नहीं आती।

## देखें

* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [WaitHandle](../)
* क्लास [TimeSpan](../../../system/timespan/)
* नेमस्पेस [System::Threading](../../)
* लाइब्रेरी [Aspose.Slides](../../../)