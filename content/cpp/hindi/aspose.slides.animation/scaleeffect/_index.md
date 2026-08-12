---
title: ScaleEffect
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एनिमेशन स्केल इफ़ेक्ट का प्रतिनिधित्व करता है।
type: docs
weight: 547
url: /hi/aspose.slides.animation/scaleeffect/
---
## ScaleEffect क्लास

एनिमेशन स्केल इफ़ेक्ट का प्रतिनिधित्व करता है।

```cpp
class ScaleEffect : public Aspose::Slides::Animation::Behavior,
                    public Aspose::Slides::Animation::IScaleEffect
```

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सिमेंटिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, हालाँकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, हालाँकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [NullableBool](../../aspose.slides/nullablebool/) [get_Accumulate](../behavior/get_accumulate/)() override | एनिमेशन व्यवहारों के संचित होने का प्रतिनिधित्व करता है। पढ़ें [NullableBool](../../aspose.slides/nullablebool/)। |
| [BehaviorAdditiveType](../behavioradditivetype/) [get_Additive](../behavior/get_additive/)() override | वर्तमान एनिमेशन व्यवहार अन्य चल रहे एनिमेशन के साथ संयोजित है या नहीं, इसे दर्शाता है। पढ़ें [BehaviorAdditiveType](../behavioradditivetype/)। |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_By](./get_by/)() override | एनिमेशन के लिए सापेक्ष ऑफ़सेट मान (प्रतिशत में) का वर्णन करता है। पढ़ें [System::Drawing::PointF](../../system.drawing/pointf/)। |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_From](./get_from/)() override | एनिमेशन शुरू करने के लिए x/y निर्देशांक (प्रतिशत में) निर्दिष्ट करता है। पढ़ें [System::Drawing::PointF](../../system.drawing/pointf/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorPropertyCollection](../ibehaviorpropertycollection/)\> [get_Properties](../behavior/get_properties/)() override | व्यवहार की प्रॉपर्टीज़ का प्रतिनिधित्व करता है। केवल पढ़ने योग्य [IBehaviorPropertyCollection](../ibehaviorpropertycollection/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](../behavior/get_timing/)() override | इफ़ेक्ट व्यवहार के टाइमिंग प्रॉपर्टीज़ का प्रतिनिधित्व करता है। पढ़ें [ITiming](../itiming/)। |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_To](./get_to/)() override | एनिमेशन स्केल इफ़ेक्ट के लक्ष्य स्थान (प्रतिशत में) को निर्दिष्ट करता है। पढ़ें [System::Drawing::PointF](../../system.drawing/pointf/)। |
| [NullableBool](../../aspose.slides/nullablebool/) [get_ZoomContent](./get_zoomcontent/)() override | निर्धारित करता है कि सामग्री को ज़ूम किया जाना चाहिए या नहीं। पढ़ें [NullableBool](../../aspose.slides/nullablebool/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचें कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉक करने के लिए लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) संटेरी ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स को क्लोन करने में सक्षम बनाता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर्स को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कॉन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और उप-क्लासों के कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और उप-क्लासों के कॉपी निर्माण को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस के साथ वैल्यू टाइप ऑब्जेक्ट की nullptr से तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्धारित मान से शेयर किए गए रेफ़रेंस काउंट को घटाता है। |
|  [ScaleEffect](./scaleeffect/)() |  |
| void [set_Accumulate](../behavior/set_accumulate/)([NullableBool](../../aspose.slides/nullablebool/)) override | एनिमेशन व्यवहारों के संचित होने को दर्शाता है। लिखें [NullableBool](../../aspose.slides/nullablebool/)। |
| void [set_Additive](../behavior/set_additive/)([BehaviorAdditiveType](../behavioradditivetype/)) override | वर्तमान एनिमेशन व्यवहार अन्य चल रहे एनिमेशन के साथ संयोजित है या नहीं, इसे दर्शाता है। लिखें [BehaviorAdditiveType](../behavioradditivetype/)। |
| void [set_By](./set_by/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | एनिमेशन के लिए सापेक्ष ऑफ़सेट मान (प्रतिशत में) का वर्णन करता है। लिखें [System::Drawing::PointF](../../system.drawing/pointf/)। |
| void [set_From](./set_from/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | एनिमेशन शुरू करने के लिए x/y निर्देशांक (प्रतिशत में) निर्दिष्ट करता है। लिखें [System::Drawing::PointF](../../system.drawing/pointf/)। |
| void [set_Timing](../behavior/set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) override | इफ़ेक्ट व्यवहार के टाइमिंग प्रॉपर्टीज़ का प्रतिनिधित्व करता है। लिखें [ITiming](../itiming/)। |
| void [set_To](./set_to/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | एनिमेशन स्केल इफ़ेक्ट के लक्ष्य स्थान (प्रतिशत में) को निर्दिष्ट करता है। लिखें [System::Drawing::PointF](../../system.drawing/pointf/)। |
| void [set_ZoomContent](./set_zoomcontent/)([NullableBool](../../aspose.slides/nullablebool/)) override | निर्धारित करता है कि सामग्री को ज़ूम किया जाना चाहिए या नहीं। लिखें [NullableBool](../../aspose.slides/nullablebool/)। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्गुमेंट को एक weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | शेयर किए गए रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | शेयर किया गया रेफ़रेंस काउंट बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | शेयर किया गया रेफ़रेंस काउंट घटाता है और लौटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में कनवर्ट करना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने के लिए लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) संटेरी ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट घटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स और ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर्स को मुक्त करता है। |

## संबंधित देखें

* क्लास [Behavior](../behavior/)
* क्लास [IScaleEffect](../iscaleeffect/)
* नेमस्पेस [Aspose::Slides::Animation](../)
* लाइब्रेरी [Aspose.Slides](../../)