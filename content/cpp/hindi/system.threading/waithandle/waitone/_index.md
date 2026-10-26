---
title: WaitOne()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: असीमित अवधि के लिए हैंडल के फ़ायर होने की प्रतीक्षा करता है।
type: docs
weight: 27
url: /hi/system.threading/waithandle/waitone/
---
## WaitHandle::WaitOne() मेथड


हैंडल के अनिश्चित काल तक फायर होने का इंतज़ार करता है।

```cpp
virtual bool System::Threading::WaitHandle::WaitOne()
```


### रिटर्न वैल्यू

कोई टाइमआउट न होने के कारण हमेशा true लौटाता है।

## WaitHandle::WaitOne(int) मेथड


हैंडल के फायर होने का इंतज़ार करता है।

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) को इंतज़ार करने के लिए, मिलीसेकंड में; -1 अनंत प्रतीक्षा का अर्थ है, 0 जाँच-और-रिटर्न का अर्थ है, सकारात्मक मान टाइमआउट होते हैं। |

### रिटर्न वैल्यू

यदि हैंडल फायर हो गया तो true, यदि टाइमआउट समाप्त हो गया तो false।

## WaitHandle::WaitOne(TimeSpan) मेथड


हैंडल के फायर होने का इंतज़ार करता है।

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(TimeSpan timeout)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | एक [System::TimeSpan](../../../system/timespan/) जो प्रतीक्षा के लिए मिलीसेकंड की संख्या दर्शाता है, या एक [System::TimeSpan](../../../system/timespan/) जो -1 मिलीसेकंड को अनिश्चित काल तक प्रतीक्षा दर्शाता है। |

### रिटर्न वैल्यू

यदि हैंडल फायर हो गया तो true, यदि टाइमआउट समाप्त हो गया तो false।

## WaitHandle::WaitOne(int, bool) मेथड


हैंडल के फायर होने का इंतज़ार करता है।

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout, bool exitContext)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) को इंतज़ार करने के लिए, मिलीसेकंड में; -1 अनंत प्रतीक्षा का अर्थ है, 0 जाँच-और-रिटर्न का अर्थ है, सकारात्मक मान टाइमआउट होते हैं। |
| exitContext | **bool** | यदि true, तो प्रतीक्षा को हैंडल पर लॉक को छोड़ देना चाहिए इससे पहले कि इसके लिए प्रतीक्षा करे। |

### रिटर्न वैल्यू

यदि हैंडल फायर हो गया तो true, यदि टाइमआउट समाप्त हो गया तो false।

## संबंधित देखें

* क्लास [WaitHandle](../)
* क्लास [TimeSpan](../../../system/timespan/)
* नेमस्पेस [System::Threading](../../)
* लाइब्रेरी [Aspose.Slides](../../../)