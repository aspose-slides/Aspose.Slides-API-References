---
title: RippleTransition
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: Ripple स्लाइड संक्रमण प्रभाव।
type: docs
weight: 365
url: /hi/aspose.slides.slideshow/rippletransition/
---
## RippleTransition वर्ग


Ripple स्लाइड संक्रमण प्रभाव.

```cpp
class RippleTransition : public Aspose::Slides::SlideShow::TransitionValueBase,
                         public Aspose::Slides::SlideShow::IRippleTransition
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| **bool** [Equals](../transitionvaluebase/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | निर्धारित करता है कि दो [TransitionValueBase](../transitionvaluebase/) उदाहरण समान हैं या नहीं। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सिद्धान्तों का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [TransitionCornerAndCenterDirectionType](../transitioncornerandcenterdirectiontype/) [get_Direction](./get_direction/)() override | संक्रमण की दिशा। पढ़ें [TransitionCornerAndCenterDirectionType](../transitioncornerandcenterdirectiontype/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| **int32_t** [GetHashCode](../transitionvaluebase/gethashcode/)() const override | किसी विशेष प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है, जो हैशिंग एल्गोरिदम और हैश तालिका जैसी डेटा संरचनाओं में उपयोग के योग्य है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानार्थी। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# 'is' ऑपरेटर का समानार्थी। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉक करने का कार्यान्वयन करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सुरक्षा ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानार्थी। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारम्भ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट प्रारम्भ करता है और उपवर्गों की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट प्रारम्भ करता है और उपवर्गों की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | नलपॉइंटर (nullptr) के साथ वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_Direction](./set_direction/)([TransitionCornerAndCenterDirectionType](../transitioncornerandcenterdirectiontype/)) override | संक्रमण की दिशा। लिखें [TransitionCornerAndCenterDirectionType](../transitioncornerandcenterdirectiontype/)। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 'n'वें टेम्प्लेट आर्ग्यूमेंट को एक कमजोर पॉइंटर (साझा के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को कमजोर मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने का कार्यान्वयन करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सुरक्षा ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट को घटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## देखें

* कक्षा [TransitionValueBase](../transitionvaluebase/)
* कक्षा [IRippleTransition](../irippletransition/)
* नामस्थान [Aspose::Slides::SlideShow](../)
* लाइब्रेरी [Aspose.Slides](../../)