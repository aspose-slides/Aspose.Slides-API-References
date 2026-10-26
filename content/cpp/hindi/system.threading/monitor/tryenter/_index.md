---
title: TryEnter()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट वस्तु पर एक विशेष लॉक प्राप्त करने का प्रयास करता है। लागू नहीं किया गया।
type: docs
weight: 27
url: /hi/system.threading/monitor/tryenter/
---
## Monitor::TryEnter(const SharedPtr\<Object\>\&) मेथड

निर्दिष्ट वस्तु पर एक विशेष लॉक प्राप्त करने का प्रयास करता है। लागू नहीं किया गया।

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj)
```
## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, bool\&) मेथड

निर्दिष्ट वस्तु पर एक विशेष लॉक प्राप्त करने का प्रयास करता है, और एटॉमिक रूप से एक मान सेट करता है जो दर्शाता है कि लॉक लिया गया था या नहीं।

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```
## Monitor::TryEnter(const SharedPtr\<Object\>\&, int32_t) मेथड

निर्दिष्ट मिलीसेकंड की संख्या के लिए, निर्दिष्ट वस्तु पर एक विशेष लॉक प्राप्त करने का प्रयास करता है। लागू नहीं किया गया।

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```
## Monitor::TryEnter(const SharedPtr\<Object\>\&, TimeSpan) मेथड

निर्दिष्ट अवधि के लिए, निर्दिष्ट वस्तु पर एक विशेष लॉक प्राप्त करने का प्रयास करता है। लागू नहीं किया गया।

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, TimeSpan timeout)
```
## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, int32_t, bool\&) मेथड

निर्दिष्ट अवधि के लिए, निर्दिष्ट वस्तु पर एक विशेष लॉक प्राप्त करने का प्रयास करता है, और एटॉमिक रूप से एक मान सेट करता है जो दर्शाता है कि लॉक लिया गया था या नहीं।

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool &lockTaken)
```
## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, TimeSpan, bool\&) मेथड

निर्दिष्ट अवधि के लिए, निर्दिष्ट वस्तु पर एक विशेष लॉक प्राप्त करने का प्रयास करता है, और एटॉमिक रूप से एक मान सेट करता है जो दर्शाता है कि लॉक लिया गया था या नहीं।

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, TimeSpan timeout, bool &lockTaken)
```
## संबंधित

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [Object](../../../system/object/)
* क्लास [Monitor](../)
* क्लास [TimeSpan](../../../system/timespan/)
* नामस्थान [System::Threading](../../)
* Library [Aspose.Slides](../../../)