---
title: Thread
second_title: "Aspose.Slides के लिए C++ API संदर्भ"
description: "थ्रेड कार्यान्वयन। इस क्लास की ऑब्जेक्ट्स को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का उदाहरण कभी भी स्टैक पर या operator new का उपयोग करके न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या अभिकथन दोष उत्पन्न हो सकते हैं। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शन को तर्क के रूप में पास करने के लिए करें।"
type: docs
weight: 209
url: /hi/system.threading/thread/
---
## Thread क्लास

[Thread](./) कार्यान्वयन। इस क्लास के वस्तुओं को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का उदाहरण कभी भी स्टैक पर या operator new का उपयोग करके न बनाएं, क्योंकि इससे रनटाइम त्रुटियां और/या अभिकथन दोष उत्पन्न होंगे। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शन को तर्क के रूप में पास करने के लिए करें।

```cpp
class Thread : public System::Object
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| void [Abort](./abort/)() | थ्रेड को रोकता है। लागू नहीं किया गया। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमान्टिक का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# शैली की फ्लोटिंग पॉइंट तुलना की नकल करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के साथ भी नहीं। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# शैली की फ्लोटिंग पॉइंट तुलना की नकल करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के साथ भी नहीं। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\> [get_CurrentCulture](./get_currentculture/)() | थ्रेड संस्कृति प्राप्त करता है। |
| static [System::SharedPtr](../../system/sharedptr/)\<[Thread](./)\> [get_CurrentThread](./get_currentthread/)() | वर्तमान थ्रेड का वर्णन करने वाला ऑब्जेक्ट प्राप्त करता है। |
| [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\> [get_CurrentUICulture](./get_currentuiculture/)() | थ्रेड द्वारा उपयोग की जाने वाली उपयोगकर्ता इंटरफ़ेस संस्कृति प्राप्त करता है। |
| **bool** [get_IsAlive](./get_isalive/)() | जाँचता है कि थ्रेड जीवित है या नहीं। |
| **bool** [get_IsBackground](./get_isbackground/)() | जाँचता है कि थ्रेड बैकग्राउंड है या नहीं। |
| **bool** [get_IsThreadPoolThread](./get_isthreadpoolthread/)() | जाँचता है कि थ्रेड एक थ्रेड पूल द्वारा स्वामित्व में है या नहीं। |
| int [get_ManagedThreadId](./get_managedthreadid/)() const | थ्रेड पहचानकर्ता प्राप्त करता है। इसे OS से प्राप्त किया जा सकता है, लेकिन यदि OS थ्रेड पहचानकर्ता int सीमा से अधिक हो जाता है, तो थ्रेड के आईडी आपस में टकरा सकते हैं। |
| [System::String](../../system/string/) [get_Name](./get_name/)() | थ्रेड का नाम प्राप्त करता है। |
| [ThreadState](../threadstate/) [get_ThreadState](./get_threadstate/)() | थ्रेड की स्थिति प्राप्त करता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| static int [GetCurrentThreadId](./getcurrentthreadid/)() | वर्तमान थ्रेड का पहचानकर्ता प्राप्त करता है। |
| int [GetHashCode](./gethashcode/)() const override |  |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट के वास्तविक प्रकार को प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल के समान। |
| void [Interrupt](./interrupt/)() | थ्रेड को बाधित करता है। लागू नहीं किया गया। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक उदाहरण प्रतिनिधित्व करता है या नहीं। C# 'is' ऑपरेटर के समान। |
| void [Join](./join/)() | प्रबंधित थ्रेड से जुड़ता है। यदि आवश्यक हो तो असीमित प्रतीक्षा करता है। |
| **bool** [Join](./join/)(int) | प्रबंधित थ्रेड से जुड़ता है। सीमित प्रतीक्षा करता है। |
| **bool** [Join](./join/)([TimeSpan](../../system/timespan/)) | प्रबंधित थ्रेड से जुड़ता है। सीमित प्रतीक्षा करता है। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट के लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड के समान। कस्टम टाइप्स को क्लोन करने में सक्षम बनाता है। |
| static void [MemoryBarrier](./memorybarrier/)() | मेमोरी एक्सेस को सिंक्रनाइज़ करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास कॉपी निर्माण को सक्षम करता है। |
| [Thread](./)\& [operator=](./operator_equal/)(const [Thread](./)\&) | भिन्न थ्रेड से TLS डेटा कॉपी करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास कॉपी निर्माण को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस तुलना nullptr के साथ करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंटर को घटाता है। |
| void [set_CurrentCulture](./set_currentculture/)(const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | थ्रेड संस्कृति सेट करता है। |
| void [set_CurrentUICulture](./set_currentuiculture/)(const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | थ्रेड द्वारा उपयोग की जाने वाली उपयोगकर्ता इंटरफ़ेस संस्कृति सेट करता है। |
| void [set_IsBackground](./set_isbackground/)(**bool**) | थ्रेड को बैकग्राउंड या फ़ोरग्राउंड में सेट करता है। |
| void [set_Name](./set_name/)(const [System::String](../../system/string/)\&) | थ्रेड का नाम सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्पलेट आर्ग्यूमेंट को एक कमजोर पॉइंटर सेट करता है (साझा के बजाय)। कंटेनरों में पॉइंटर को कमजोर मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंटर को बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंटर को घटाता है और लौटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| static void [Sleep](./sleep/)(int) | निर्दिष्ट टाइमआउट के लिए वर्तमान थ्रेड को रोकता है। |
| static void [Sleep](./sleep/)([TimeSpan](../../system/timespan/)) | निर्दिष्ट टाइमआउट के लिए वर्तमान थ्रेड को रोकता है। |
| static void [SpinWait](./spinwait/)(int) | विशिष्ट संख्या में लूप इटरैशन्स की प्रतीक्षा करता है। |
| void [Start](./start/)() | नल आर्ग्यूमेंट ऑब्जेक्ट का उपयोग करके थ्रेड शुरू करता है। |
| void [Start](./start/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | थ्रेड शुरू करता है। |
|  [Thread](./thread/)() | कन्स्ट्रक्टर। |
|  [Thread](./thread/)([ThreadStart](../threadstart/)) | कन्स्ट्रक्टर। |
|  [Thread](./thread/)([ParameterizedThreadStart](../parameterizedthreadstart/)) | कन्स्ट्रक्टर। |
|  [Thread](./thread/)([Thread](./)\&) | कॉपी कन्स्ट्रक्टर। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड के समान। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने में सक्षम बनाता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंटर को बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंटर को घटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके अलावा, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| static **bool** [Yield](./yield/)() | थ्रेड को यील्ड करता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |
| virtual  [~Thread](./~thread/)() | डिस्ट्रक्टर। |

## टिप्पणी

```cpp
#include "system/threading/thread.h"
#include "system/smart_ptr.h"

int main()
{
  auto thread = System::MakeObject<System::Threading::Thread>([]()
  {
    std::cout << "Child thread ID: " << System::Threading::Thread::GetCurrentThreadId() << std::endl;
    System::Threading::Thread::Sleep(200);
  });

  std::cout << "Main thread ID: " << System::Threading::Thread::GetCurrentThreadId() << std::endl;

  thread->Start();
  thread->Join();

  return 0;
}
/*
यह कोड उदाहरण निम्नलिखित आउटपुट उत्पन्न करता है:
Main thread ID: 2
Child thread ID: 1
*/
```

## देखें

* क्लास [Object](../../system/object/)
* नेमस्पेस [System::Threading](../)
* लाइब्रेरी [Aspose.Slides](../../)