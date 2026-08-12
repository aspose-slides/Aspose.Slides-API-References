---
title: WaitAll()
second_title: Aspose.Slides for C++ API संदर्भ
description: सभी हैंडल के फायर होने का इंतजार करता है।
type: docs
weight: 1
url: /hi/system.threading/waithandle/waitall/
---
## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) विधि

सभी हैंडल के फायर होने का इंतजार करता है।

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | प्रतीक्षा करने वाले हैंडल। |
| millisecondsTimeout | int | [Timeout](../../timeout/) को मिलिसेकंड में प्रतीक्षा करने के लिए; -1 अनंत प्रतीक्षा को दर्शाता है, 0 जाँच-और-रिटर्न को दर्शाता है, सकारात्मक मान टाइमआउट होते हैं। |

### रिटर्न मान

यदि सभी हैंडल फायर हो गए हों तो true, यदि टाइमआउट समाप्त हो गया हो तो false।

## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) विधि

सभी हैंडल के फायर होने का इंतजार करता है।

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | प्रतीक्षा करने वाले हैंडल। |
| timeout | [TimeSpan](../../../system/timespan/) | एक [System::TimeSpan](../../../system/timespan/) जो प्रतीक्षा करने के मिलिसेकंड की संख्या को दर्शाता है, या एक [System::TimeSpan](../../../system/timespan/) जो -1 मिलिसेकंड को अनिश्चित काल तक प्रतीक्षा करने को दर्शाता है। |

### रिटर्न मान

यदि सभी हैंडल फायर हो गए हों तो true, यदि टाइमआउट समाप्त हो गया हो तो false।

## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) विधि

सभी हैंडल के फायर होने का इंतजार करता है।

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | प्रतीक्षा करने वाले हैंडल। |

### रिटर्न मान

यदि waitHandles में प्रत्येक तत्व ने संकेत प्राप्त कर लिया हो तो true; अन्यथा विधि कभी वापस नहीं आती।

## देखें भी

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [WaitHandle](../)
* क्लास [TimeSpan](../../../system/timespan/)
* नामस्थान [System::Threading](../../)
* Library [Aspose.Slides](../../../)