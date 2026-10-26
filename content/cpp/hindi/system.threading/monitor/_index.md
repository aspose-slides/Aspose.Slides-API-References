---
title: Monitor
second_title: Aspose.Slides for C++ API संदर्भ
description: क्लास Monitor वस्तुओं तक पहुँच को सिंक्रनाइज़ करने के लिए एक तंत्र प्रदान करता है।
type: docs
weight: 157
url: /hi/system.threading/monitor/
---
## Monitor क्लास

Class [Monitor](./) provides a mechanism that synchronizes access to objects.

```cpp
class Monitor : public System::Object
```

## विधियाँ

| Method | Description |
| --- | --- |
| static void [Enter](./enter/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | निर्दिष्ट वस्तु पर एक विशेष लॉक प्राप्त करता है। |
| static void [Enter](./enter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **bool**\&) | निर्दिष्ट वस्तु पर एक विशेष लॉक प्राप्त करता है, और एटॉमिक रूप से एक मान सेट करता है जो दर्शाता है कि लॉक लिया गया था या नहीं। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-स्टाइल फ़्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है, यद्यपि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं है, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-स्टाइल फ़्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है, यद्यपि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं है, जिसमें NaN भी शामिल है। |
| static void [Exit](./exit/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | निर्दिष्ट वस्तु पर विशेष लॉक को रिलीज़ करता है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | वस्तु से संबंधित रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स की हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानार्थी। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक उदाहरण है या नहीं। C# 'is' ऑपरेटर का समानार्थी। |
| static **bool** [IsEntered](./isentered/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | निर्धारित करता है कि क्या वर्तमान थ्रेड निर्दिष्ट वस्तु पर लॉक रखता है। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानार्थी। कस्टम टाइप्स की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| static void [Pulse](./pulse/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | लॉकेड ऑब्जेक्ट की स्थिति में परिवर्तन के बारे में प्रतीक्षा कतार में थ्रेड को सूचित करता है। लागू नहीं किया गया। |
| static void [PulseAll](./pulseall/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | ऑब्जेक्ट की स्थिति में परिवर्तन के बारे में सभी प्रतीक्षा थ्रेड्स को सूचित करता है। लागू नहीं किया गया। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस-तुलना वैल्यू टाइप ऑब्जेक्ट को nullptr के साथ करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए विशेषीकृत संस्करण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशेषीकृत संस्करण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्पलेट आर्ग्यूमेंट को एक weak पॉइंटर सेट करता है (shared के बजाय)। कंटेनर्स में पॉइंटर्स को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static **bool** [TryEnter](./tryenter/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | निर्दिष्ट वस्तु पर एक विशेष लॉक प्राप्त करने का प्रयास करता है। लागू नहीं किया गया। |
| static void [TryEnter](./tryenter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **bool**\&) | निर्दिष्ट वस्तु पर एक विशेष लॉक प्राप्त करने का प्रयास करता है, और एटॉमिक रूप से एक मान सेट करता है जो दर्शाता है कि लॉक लिया गया था या नहीं। |
| static **bool** [TryEnter](./tryenter/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **int32_t**) | निर्दिष्ट मिलिसेकंड्स की संख्या के लिए, निर्दिष्ट वस्तु पर एक विशेष लॉक प्राप्त करने का प्रयास करता है। लागू नहीं किया गया। |
| static **bool** [TryEnter](./tryenter/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, [TimeSpan](../../system/timespan/)) | निर्दिष्ट समय अवधि के लिए, निर्दिष्ट वस्तु पर एक विशेष लॉक प्राप्त करने का प्रयास करता है। लागू नहीं किया गया। |
| static void [TryEnter](./tryenter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **int32_t**, **bool**\&) | निर्दिष्ट समय अवधि के लिए, निर्दिष्ट वस्तु पर एक विशेष लॉक प्राप्त करने का प्रयास करता है, और एटॉमिक रूप से एक मान सेट करता है जो दर्शाता है कि लॉक लिया गया था या नहीं। |
| static void [TryEnter](./tryenter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, [TimeSpan](../../system/timespan/), **bool**\&) | निर्दिष्ट समय अवधि के लिए, निर्दिष्ट वस्तु पर एक विशेष लॉक प्राप्त करने का प्रयास करता है, और एटॉमिक रूप से एक मान सेट करता है जो दर्शाता है कि लॉक लिया गया था या नहीं। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कन्स्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| static **bool** [Wait](./wait/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **int32_t**, **bool**) | ऑब्जेक्ट पर लॉक रिलीज़ करता है और वर्तमान थ्रेड को तब तक ब्लॉक करता है जब तक वह लॉक फिर से प्राप्त न कर ले। यदि निर्दिष्ट टाइम-आउट अंतराल समाप्त हो जाता है, तो थ्रेड रेडी क्यू में प्रवेश करता है। वैकल्पिक रूप से, प्रतीक्षा से पहले सिंक्रोनाइज़्ड कॉन्टेक्स्ट के लिए सिंक्रोनाइज़ेशन डोमेन से बाहर निकलता है और बाद में डोमेन को फिर से प्राप्त करता है। लागू नहीं किया गया। |
| static **bool** [Wait](./wait/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, [TimeSpan](../../system/timespan/), **bool**) | ऑब्जेक्ट पर लॉक रिलीज़ करता है और वर्तमान थ्रेड को तब तक ब्लॉक करता है जब तक वह लॉक फिर से प्राप्त न कर ले। यदि निर्दिष्ट टाइम-आउट अंतराल समाप्त हो जाता है, तो थ्रेड रेडी क्यू में प्रवेश करता है। वैकल्पिक रूप से, प्रतीक्षा से पहले सिंक्रोनाइज़्ड कॉन्टेक्स्ट के लिए सिंक्रोनाइज़ेशन डोमेन से बाहर निकलता है और बाद में डोमेन को फिर से प्राप्त करता है। लागू नहीं किया गया। |
| static **bool** [Wait](./wait/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **int32_t**) | ऑब्जेक्ट पर लॉक रिलीज़ करता है और वर्तमान थ्रेड को तब तक ब्लॉक करता है जब तक वह लॉक फिर से प्राप्त न कर ले। यदि निर्दिष्ट टाइम-आउट अंतराल समाप्त हो जाता है, तो थ्रेड रेडी क्यू में प्रवेश करता है। लागू नहीं किया गया। |
| static **bool** [Wait](./wait/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, [TimeSpan](../../system/timespan/)) | ऑब्जेक्ट पर लॉक रिलीज़ करता है और वर्तमान थ्रेड को तब तक ब्लॉक करता है जब तक वह लॉक फिर से प्राप्त न कर ले। यदि निर्दिष्ट टाइम-आउट अंतराल समाप्त हो जाता है, तो थ्रेड रेडी क्यू में प्रवेश करता है। लागू नहीं किया गया। |
| static **bool** [Wait](./wait/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | ऑब्जेक्ट पर लॉक रिलीज़ करता है और वर्तमान थ्रेड को तब तक ब्लॉक करता है जब तक वह लॉक फिर से प्राप्त न कर ले। लागू नहीं किया गया। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## Remarks



```cpp
#include "system/threading/monitor.h"
#include "system/threading/thread.h"
#include "system/smart_ptr.h"
#include "system/string.h"
#include <iostream>
#include <vector>

int main()
{
  using namespace System::Threading;

  const auto threadsCount = 3;
  std::cout << "Threads count: " << threadsCount << std::endl;
  auto locker = System::MakeObject<System::Object>();
  int x = 0;

  std::vector<System::SharedPtr<Thread>> threads;
  threads.reserve(threadsCount);
  for (auto i = 0; i < threadsCount; ++i)
  {
    threads.emplace_back(System::MakeObject<Thread>([&x, &locker]() -> void {
      Monitor::Enter(locker);

      x = 1;
      for (auto i = 0; i < 5; ++i)
      {
        std::cout << Thread::get_CurrentThread()->get_Name() << ": " << x++ << std::endl;
        Thread::Sleep(100);
      }

      Monitor::Exit(locker);
    }));
    threads.back()->set_Name(System::String("Thread " + std::to_string(i)));
    threads.back()->Start();
  }

  Thread::Sleep(threadsCount * 100);

  for (auto& thread : threads)
  {
    thread->Join();
  }

  return 0;
}
/*
यह कोड उदाहरण निम्नलिखित आउटपुट उत्पन्न करता है:
थ्रेड्स गिनती: 3
थ्रेड 0: 1
थ्रेड 0: 2
थ्रेड 0: 3
थ्रेड 0: 4
थ्रेड 0: 5
थ्रेड 1: 1
थ्रेड 1: 2
थ्रेड 1: 3
थ्रेड 1: 4
थ्रेड 1: 5
थ्रेड 2: 1
थ्रेड 2: 2
थ्रेड 2: 3
थ्रेड 2: 4
थ्रेड 2: 5
*/
```

## देखें

* क्लास [Object](../../system/object/)
* नामस्थान [System::Threading](../)
* पुस्तकालय [Aspose.Slides](../../)