---
title: Wait()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: वस्तु पर लॉक को रिलीज़ करता है और वर्तमान थ्रेड को तब तक ब्लॉक करता है जब तक वह लॉक फिर से प्राप्त नहीं करता। यदि निर्दिष्ट टाइम-आउट अंतराल समाप्त हो जाता है, तो थ्रेड तैयार कतार में प्रवेश करता है। वैकल्पिक रूप से, प्रतीक्षा से पहले सिंक्रोनाइज़्ड कॉन्टेक्स्ट के लिए सिंक्रोनाइज़ेशन डोमेन को छोड़ता है और बाद में डोमेन को फिर से प्राप्त करता है। लागू नहीं किया गया है।
type: docs
weight: 53
url: /hi/system.threading/monitor/wait/
---
## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t, bool) मेथड

ऑब्जेक्ट पर लॉक को रिलीज़ करता है और वर्तमान थ्रेड को तब तक ब्लॉक करता है जब तक वह लॉक फिर से प्राप्त नहीं करता। यदि निर्दिष्ट टाइम-आउट अंतराल समाप्त हो जाता है, तो थ्रेड तैयार क्यू में चला जाता है। वैकल्पिक रूप से, प्रतीक्षा से पहले सिंक्रोनाइज़्ड कॉन्टेक्स्ट के लिए सिंक्रोनाइज़ेशन डोमेन को छोड़ता है और बाद में डोमेन को फिर से प्राप्त करता है। लागू नहीं किया गया है।

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool exitContext)
```

## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan, bool) मेथड

ऑब्जेक्ट पर लॉक को रिलीज़ करता है और वर्तमान थ्रेड को तब तक ब्लॉक करता है जब तक वह लॉक फिर से प्राप्त नहीं करता। यदि निर्दिष्ट टाइम-आउट अंतराल समाप्त हो जाता है, तो थ्रेड तैयार क्यू में चला जाता है। वैकल्पिक रूप से, प्रतीक्षा से पहले सिंक्रोनाइज़्ड कॉन्टेक्स्ट के लिए सिंक्रोनाइज़ेशन डोमेन को छोड़ता है और बाद में डोमेन को फिर से प्राप्त करता है। लागू नहीं किया गया है।

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout, bool exitContext)
```

## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t) मेथड

ऑब्जेक्ट पर लॉक को रिलीज़ करता है और वर्तमान थ्रेड को तब तक ब्लॉक करता है जब तक वह लॉक फिर से प्राप्त नहीं करता। यदि निर्दिष्ट टाइम-आउट अंतराल समाप्त हो जाता है, तो थ्रेड तैयार क्यू में चला जाता है। लागू नहीं किया गया है।

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```

## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan) मेथड

ऑब्जेक्ट पर लॉक को रिलीज़ करता है और वर्तमान थ्रेड को तब तक ब्लॉक करता है जब तक वह लॉक फिर से प्राप्त नहीं करता। यदि निर्दिष्ट टाइम-आउट अंतराल समाप्त हो जाता है, तो थ्रेड तैयार क्यू में चला जाता है। लागू नहीं किया गया है।

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout)
```

## Monitor::Wait(const SharedPtr\<Object\>\&) मेथड

ऑब्जेक्ट पर लॉक को रिलीज़ करता है और वर्तमान थ्रेड को तब तक ब्लॉक करता है जब तक वह लॉक फिर से प्राप्त नहीं करता। लागू नहीं किया गया है।

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj)
```

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [Object](../../../system/object/)
* क्लास [Monitor](../)
* क्लास [TimeSpan](../../../system/timespan/)
* नामस्थान [System::Threading](../../)
* लाइब्रेरी [Aspose.Slides](../../../)