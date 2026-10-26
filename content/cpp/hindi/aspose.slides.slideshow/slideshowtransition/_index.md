---
title: SlideShowTransition
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: स्लाइड शो ट्रांज़िशन को दर्शाता है।
type: docs
weight: 404
url: /hi/aspose.slides.slideshow/slideshowtransition/
---
## SlideShowTransition वर्ग

Represents slide show transition.

```cpp
class SlideShowTransition : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::BaseSlide>>,
                            public Aspose::Slides::ISlideShowTransition
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | निर्धारित करता है कि दो [SlideShowTransition](./) उदाहरण समान हैं या नहीं। पढ़ें/लिखें **bool**. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमान्टिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| **bool** [get_AdvanceAfter](./get_advanceafter/)() override | यह एट्रीब्यूट निर्दिष्ट करता है कि स्लाइडशो एक निश्चित समय के बाद अगले स्लाइड पर जाएगा या नहीं। पढ़ें **bool**. |
| **uint32_t** [get_AdvanceAfterTime](./get_advanceaftertime/)() override | ट्रांज़िशन शुरू होने के बाद मिलीसेकंड में समय निर्दिष्ट करता है। यह सेटिंग advClick एट्रीब्यूट के साथ उपयोग की जा सकती है। यदि यह एट्रीब्यूट निर्दिष्ट नहीं है तो माना जाता है कि कोई ऑटो-एडवांस नहीं होगा। पढ़ें **uint32_t**. |
| **bool** [get_AdvanceOnClick](./get_advanceonclick/)() override | निर्दिष्ट करता है कि माउस क्लिक स्लाइड को आगे बढ़ाएगा या नहीं। यदि यह एट्रीब्यूट निर्दिष्ट नहीं है तो मान true माना जाता है। पढ़ें **bool**. |
| **int32_t** [get_Duration](./get_duration/)() override | मिलीसेकंड में स्लाइड ट्रांज़िशन इफ़ेक्ट की अवधि प्राप्त करता है। पढ़ें **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\> [get_Sound](./get_sound/)() override | एम्बेडेड ऑडियो डेटा लौटाता है। पढ़ें [IAudio](../../aspose.slides/iaudio/). |
| **bool** [get_SoundIsBuiltIn](./get_soundisbuiltin/)() override | निर्धारित करता है कि यह साउंड बिल्ट-इन है या नहीं। यदि यह एट्रीब्यूट true पर सेट है तो जनरेटिंग एप्लिकेशन को इस साउंड के नाम एट्रीब्यूट को उसकी बिल्ट-इन साउंड सूची में जांचने के लिए सूचित किया जाता है और फिर आवश्यकतानुसार कस्टम नाम या UI प्रदर्शित कर सकता है। पढ़ें **bool**. |
| **bool** [get_SoundLoop](./get_soundloop/)() override | यह एट्रीब्यूट निर्दिष्ट करता है कि साउंड स्लाइडशो में अगले साउंड इवेंट तक लूप करेगा या नहीं। पढ़ें **bool**. |
| [TransitionSoundMode](../transitionsoundmode/) [get_SoundMode](./get_soundmode/)() override | स्लाइड ट्रांज़िशन के लिए साउंड मोड सेट करता है या लौटाता है। पढ़ें [TransitionSoundMode](../transitionsoundmode/). |
| [System::String](../../system/string/) [get_SoundName](./get_soundname/)() override | ट्रांज़िशन के साउंड के लिए मानव-पठनीय नाम निर्दिष्ट करता है। साउंड नाम प्राप्त या सेट करने के लिए [ISlideShowTransition::set_Sound](../../aspose.slides/islideshowtransition/set_sound/) को असाइन किया जाना चाहिए। पढ़ें [System::String](../../system/string/). |
| [TransitionSpeed](../transitionspeed/) [get_Speed](./get_speed/)() override | वर्तमान स्लाइड से अगले में ट्रांज़िशन के दौरान उपयोग की जाने वाली ट्रांज़िशन गति निर्दिष्ट करता है। पढ़ें [TransitionSpeed](../transitionspeed/). |
| [TransitionType](../transitiontype/) [get_Type](./get_type/)() override | ट्रांज़िशन का प्रकार। पढ़ें [TransitionType](../transitiontype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITransitionValueBase](../itransitionvaluebase/)\> [get_Value](./get_value/)() override | [Slide](../../aspose.slides/slide/) शो ट्रांज़िशन वैल्यू। केवल-पढ़ाई [ITransitionValueBase](../itransitionvaluebase/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| **int32_t** [GetHashCode](./gethashcode/)() const override | निर्दिष्ट प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है, जो हैशिंग एल्गोरिदम और हैश टेबल जैसे डेटा स्ट्रक्चर्स में उपयोग के लिए उपयुक्त है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक टाइप प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित टाइप का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() कथन को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम टाइप्स को क्लोन करने में सक्षम बनाता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ को कॉपी कंस्ट्रक्ट करने में सक्षम बनाता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ को कॉपी कंस्ट्रक्ट करने में सक्षम बनाता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस द्वारा वैल्यू टाइप ऑब्जेक्ट की तुलना nullptr से करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) के स्ट्रिंग और nullptr केस के लिए विशिष्टीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) के स्ट्रिंग्स केस के लिए विशिष्टीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट घटाता है। |
| void [set_AdvanceAfter](./set_advanceafter/)(**bool**) override | यह एट्रीब्यूट निर्दिष्ट करता है कि स्लाइडशो एक निश्चित समय के बाद अगले स्लाइड पर जाएगा या नहीं। लिखें **bool**. |
| void [set_AdvanceAfterTime](./set_advanceaftertime/)(**uint32_t**) override | ट्रांज़िशन शुरू होने के बाद मिलीसेकंड में समय निर्दिष्ट करता है। यह सेटिंग advClick एट्रीब्यूट के साथ उपयोग की जा सकती है। यदि यह एट्रीब्यूट निर्दिष्ट नहीं है तो माना जाता है कि कोई ऑटो-एडवांस नहीं होगा। लिखें **uint32_t**. |
| void [set_AdvanceOnClick](./set_advanceonclick/)(**bool**) override | निर्दिष्ट करता है कि माउस क्लिक स्लाइड को आगे बढ़ाएगा या नहीं। यदि यह एट्रीब्यूट निर्दिष्ट नहीं है तो मान true माना जाता है। लिखें **bool**. |
| void [set_Duration](./set_duration/)(**int32_t**) override | मिलीसेकंड में स्लाइड ट्रांज़िशन इफ़ेक्ट की अवधि सेट करता है। लिखें **int32_t**. |
| void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\>) override | एम्बेडेड ऑडियो डेटा सेट करता है। लिखें [IAudio](../../aspose.slides/iaudio/). |
| void [set_SoundIsBuiltIn](./set_soundisbuiltin/)(**bool**) override | निर्दिष्ट करता है कि यह साउंड बिल्ट-इन है या नहीं। यदि यह एट्रीब्यूट true पर सेट है तो जनरेटिंग एप्लिकेशन को इस साउंड के नाम एट्रीब्यूट को उसकी बिल्ट-इन साउंड सूची में जांचने के लिए सूचित किया जाता है और फिर आवश्यकतानुसार कस्टम नाम या UI प्रदर्शित कर सकता है। लिखता है **bool**. |
| void [set_SoundLoop](./set_soundloop/)(**bool**) override | यह एट्रीब्यूट निर्दिष्ट करता है कि साउंड स्लाइडशो में अगले साउंड इवेंट तक लूप करेगा या नहीं। लिखें **bool**. |
| void [set_SoundMode](./set_soundmode/)([TransitionSoundMode](../transitionsoundmode/)) override | स्लाइड ट्रांज़िशन के लिए साउंड मोड सेट करता है या लौटाता है। लिखें [TransitionSoundMode](../transitionsoundmode/). |
| void [set_SoundName](./set_soundname/)([System::String](../../system/string/)) override | ट्रांज़िशन के साउंड के लिए मानव-पठनीय नाम निर्दिष्ट करता है। साउंड नाम प्राप्त या सेट करने के लिए [ISlideShowTransition::set_Sound](../../aspose.slides/islideshowtransition/set_sound/) को असाइन किया जाना चाहिए। लिखता है [System::String](../../system/string/). |
| void [set_Speed](./set_speed/)([TransitionSpeed](../transitionspeed/)) override | वर्तमान स्लाइड से अगले में ट्रांज़िशन के दौरान उपयोग की जाने वाली ट्रांज़िशन गति निर्दिष्ट करता है। लिखें [TransitionSpeed](../transitionspeed/). |
| void [set_Type](./set_type/)([TransitionType](../transitiontype/)) override | ट्रांज़िशन का प्रकार। लिखें [TransitionType](../transitiontype/). |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | nth टेम्पलेट आर्ग्यूमेंट को वीक पॉइंटर (शेयर्ड नहीं) सेट करता है। कंटेनरों में पॉइंटर को वीक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट घटाता और लौटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने में सक्षम बनाता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() कथन को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट घटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## संबंधित देखें

* क्लास [DomObject](../../aspose.slides/domobject/)
* क्लास [ISlideShowTransition](../../aspose.slides/islideshowtransition/)
* नामस्थान [Aspose::Slides::SlideShow](../)
* लाइब्रेरी [Aspose.Slides](../../)