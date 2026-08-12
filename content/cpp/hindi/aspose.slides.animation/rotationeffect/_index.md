---
title: RotationEffect
second_title: Aspose.Slides for C++ API संदर्भ
description: इफ़ेक्ट के घूर्णन व्यवहार को दर्शाता है।
type: docs
weight: 534
url: /hi/aspose.slides.animation/rotationeffect/
---
## RotationEffect क्लास

Represent rotation behavior of effect.

```cpp
class RotationEffect : public Aspose::Slides::Animation::Behavior,
                       public Aspose::Slides::Animation::IRotationEffect
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमैन्टिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, यद्यपि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, यद्यपि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [NullableBool](../../aspose.slides/nullablebool/) [get_Accumulate](../behavior/get_accumulate/)() override | एनीमेेशन व्यवहार संचित हैं या नहीं दर्शाता है। पढ़ें [NullableBool](../../aspose.slides/nullablebool/)। |
| [BehaviorAdditiveType](../behavioradditivetype/) [get_Additive](../behavior/get_additive/)() override | वर्तमान एनीमेेशन व्यवहार अन्य चल रहे एनीमेेशनों के साथ संयुक्त है या नहीं दर्शाता है। पढ़ें [BehaviorAdditiveType](../behavioradditivetype/)। |
| **float** [get_By](./get_by/)() override | एनीमेेशन के लिए रिलेटिव ऑफसेट वैल्यू का वर्णन करता है। पढ़ें **float**। |
| **float** [get_From](./get_from/)() override | एनीमेेशन के लिए प्रारंभिक वैल्यू का वर्णन करता है। पढ़ें **float**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorPropertyCollection](../ibehaviorpropertycollection/)\> [get_Properties](../behavior/get_properties/)() override | व्यवहार की प्रॉपर्टीज़ दर्शाता है। केवल- पढ़ने योग्य [IBehaviorPropertyCollection](../ibehaviorpropertycollection/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](../behavior/get_timing/)() override | इफ़ेक्ट व्यवहार के टाइमिंग प्रॉपर्टीज़ दर्शाता है। पढ़ें [ITiming](../itiming/)। |
| **float** [get_To](./get_to/)() override | एनीमेेशन के लिए समाप्ति वैल्यू का वर्णन करता है। पढ़ें **float**। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का अनुरूप। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक टाइप प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का अनुरूप। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँच करता है कि ऑब्जेक्ट targetType द्वारा वर्णित टाइप का इंस्टेंस दर्शाता है या नहीं। C# 'is' ऑपरेटर का अनुरूप। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट का लॉक कार्यान्वित करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का अनुरूप। कस्टम टाइप्स का क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेस की कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेस की कॉपी निर्माण को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से शेयर्ड रेफ़रेंस काउंट को घटाता है। |
|  [RotationEffect](./rotationeffect/)() |  |
| void [set_Accumulate](../behavior/set_accumulate/)([NullableBool](../../aspose.slides/nullablebool/)) override | एनीमेेशन व्यवहार संचित हैं या नहीं दर्शाता है। लिखें [NullableBool](../../aspose.slides/nullablebool/)। |
| void [set_Additive](../behavior/set_additive/)([BehaviorAdditiveType](../behavioradditivetype/)) override | वर्तमान एनीमेेशन व्यवहार अन्य चल रहे एनीमेेशनों के साथ संयुक्त है या नहीं दर्शाता है। लिखें [BehaviorAdditiveType](../behavioradditivetype/)। |
| void [set_By](./set_by/)(**float**) override | एनीमेेशन के लिए रिलेटिव ऑफसेट वैल्यू का वर्णन करता है। लिखें **float**। |
| void [set_From](./set_from/)(**float**) override | एनीमेेशन के लिए प्रारंभिक वैल्यू का वर्णन करता है। लिखें **float**। |
| void [set_Timing](../behavior/set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) override | इफ़ेक्ट व्यवहार के टाइमिंग प्रॉपर्टीज़ दर्शाता है। लिखें [ITiming](../itiming/)। |
| void [set_To](./set_to/)(**float**) override | एनीमेेशन के लिए समाप्ति वैल्यू का वर्णन करता है। लिखें **float**। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्प्लेट आर्ग्यूमेंट को वीक पॉइंटर (शेयर्ड के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | शेयर्ड रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | शेयर्ड रेफ़रेंस काउंट बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | शेयर्ड रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का अनुरूप। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट का अनलॉक कार्यान्वित करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट घटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## देखें

* क्लास [Behavior](../behavior/)
* क्लास [IRotationEffect](../irotationeffect/)
* नेमस्पेस [Aspose::Slides::Animation](../)
* लाइब्रेरी [Aspose.Slides](../../)