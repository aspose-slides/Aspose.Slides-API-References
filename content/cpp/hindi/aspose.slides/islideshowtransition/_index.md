---
title: ISlideShowTransition
second_title: Aspose.Slides for C++ API संदर्भ
description: स्लाइड शो ट्रांज़िशन का प्रतिनिधित्व करता है।
type: docs
weight: 3810
url: /hi/aspose.slides/islideshowtransition/
---
## ISlideShowTransition क्लास

स्लाइड शो ट्रांज़िशन का प्रतिनिधित्व करता है।

```cpp
class ISlideShowTransition : public virtual System::Object
```

## विधियां

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली का फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं है, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली का फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं है, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| virtual **bool** [get_AdvanceAfter](./get_advanceafter/)() | यह एट्रिब्यूट निर्दिष्ट करता है कि स्लाइडशो निश्चित समय के बाद अगले स्लाइड पर जाएगा या नहीं। पढ़ें **bool**। |
| virtual **uint32_t** [get_AdvanceAfterTime](./get_advanceaftertime/)() | ट्रांज़िशन शुरू होने के बाद मिलीसेकंड में समय निर्दिष्ट करता है। इस सेटिंग का उपयोग advClick एट्रिब्यूट के साथ किया जा सकता है। यदि यह एट्रिब्यूट निर्दिष्ट नहीं किया गया है तो माना जाता है कि कोई ऑटो-एडवांस नहीं होगा। पढ़ें **uint32_t**। |
| virtual **bool** [get_AdvanceOnClick](./get_advanceonclick/)() | स्लाइड को आगे बढ़ाने के लिये माउस क्लिक की आवश्यकता होगी या नहीं यह निर्दिष्ट करता है। यदि यह एट्रिब्यूट निर्दिष्ट नहीं किया गया है तो true मान माना जाता है। पढ़ें **bool**। |
| virtual **int32_t** [get_Duration](./get_duration/)() | स्लाइड ट्रांज़िशन प्रभाव की अवधि मिलीसेकंड में प्राप्त करता है। पढ़ें **int32_t**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_Sound](./get_sound/)() | एंबेडेड ऑडियो डेटा वापस करता है। पढ़ें [IAudio](../iaudio/)। |
| virtual **bool** [get_SoundIsBuiltIn](./get_soundisbuiltin/)() | निर्दिष्ट करता है कि यह ध्वनि बिल्ट-इन ध्वनि है या नहीं। यदि यह एट्रिब्यूट true पर सेट है तो जेनरेटिंग एप्लिकेशन को इस ध्वनि की नाम एट्रिब्यूट को उसकी बिल्ट-इन ध्वनियों की सूची में जांचने के लिए अलर्ट किया जाता है और आवश्यकता अनुसार कस्टम नाम या UI दिखा सकता है। पढ़ें **bool**। |
| virtual **bool** [get_SoundLoop](./get_soundloop/)() | यह एट्रिब्यूट निर्दिष्ट करता है कि ध्वनि अगले ध्वनि इवेंट तक लूप करेगी या नहीं। पढ़ें **bool**। |
| virtual [SlideShow::TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/) [get_SoundMode](./get_soundmode/)() | स्लाइड ट्रांज़िशन के लिए साउंड मोड सेट या लौटाता है। पढ़ें [TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/)। |
| virtual [System::String](../../system/string/) [get_SoundName](./get_soundname/)() | ट्रांज़िशन की ध्वनि के लिए मानव-पठन योग्य नाम निर्दिष्ट करता है। ध्वनि नाम प्राप्त या सेट करने के लिये [ISlideShowTransition::set_Sound](./set_sound/) को असाइन करना आवश्यक है। पढ़ें [System::String](../../system/string/)। |
| virtual [SlideShow::TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/) [get_Speed](./get_speed/)() | ट्रांज़िशन गति निर्दिष्ट करता है जिसे वर्तमान स्लाइड से अगले तक ट्रांज़िशन करते समय उपयोग किया जाएगा। पढ़ें [TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/)। |
| virtual [SlideShow::TransitionType](../../aspose.slides.slideshow/transitiontype/) [get_Type](./get_type/)() | ट्रांज़िशन का प्रकार। पढ़ें [TransitionType](../../aspose.slides.slideshow/transitiontype/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[SlideShow::ITransitionValueBase](../../aspose.slides.slideshow/itransitionvaluebase/)\> [get_Value](./get_value/)() | [Slide](../slide/) शो ट्रांज़िशन मान। केवल-पढ़ने योग्य [SlideShow::ITransitionValueBase](../../aspose.slides.slideshow/itransitionvaluebase/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट की वास्तविक टाइप प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि ऑब्जेक्ट targetType द्वारा वर्णित टाइप का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट के लॉक को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स को क्लोन करने को सक्षम करता है। |
| [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को इनिशियलाइज़ करता है। |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस तुलना nullptr के साथ करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण स्ट्रिंग और nullptr के केस के लिए। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण स्ट्रिंग्स के केस के लिए। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा शेयरड रेफ़रेंस काउंट को घटाता है। |
| virtual void [set_AdvanceAfter](./set_advanceafter/)(**bool**) | यह एट्रिब्यूट निर्दिष्ट करता है कि स्लाइडशो निश्चित समय के बाद अगले स्लाइड पर जाएगा या नहीं। लिखें **bool**। |
| virtual void [set_AdvanceAfterTime](./set_advanceaftertime/)(**uint32_t**) | ट्रांज़िशन शुरू होने के बाद मिलीसेकंड में समय निर्दिष्ट करता है। इस सेटिंग का उपयोग advClick एट्रिब्यूट के साथ किया जा सकता है। यदि यह एट्रिब्यूट निर्दिष्ट नहीं किया गया है तो माना जाता है कि कोई ऑटो-एडवांस नहीं होगा। लिखें **uint32_t**। |
| virtual void [set_AdvanceOnClick](./set_advanceonclick/)(**bool**) | स्लाइड को आगे बढ़ाने के लिये माउस क्लिक की आवश्यकता होगी या नहीं यह निर्दिष्ट करता है। यदि यह एट्रिब्यूट निर्दिष्ट नहीं किया गया है तो true मान माना जाता है। लिखें **bool**। |
| virtual void [set_Duration](./set_duration/)(**int32_t**) | स्लाइड ट्रांज़िशन प्रभाव की अवधि मिलीसेकंड में सेट करता है। लिखें **int32_t**। |
| virtual void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) | एंबेडेड ऑडियो डेटा सेट करता है। लिखें [IAudio](../iaudio/)। |
| virtual void [set_SoundIsBuiltIn](./set_soundisbuiltin/)(**bool**) | निर्दिष्ट करता है कि यह ध्वनि बिल्ट-इन ध्वनि है या नहीं। यदि यह एट्रिब्यूट true पर सेट है तो जेनरेटिंग एप्लिकेशन को इस ध्वनि की नाम एट्रिब्यूट को उसकी बिल्ट-इन ध्वनियों की सूची में जांचने के लिए अलर्ट किया जाता है और आवश्यकता अनुसार कस्टम नाम या UI दिखा सकता है। लिखें **bool**। |
| virtual void [set_SoundLoop](./set_soundloop/)(**bool**) | यह एट्रिब्यूट निर्दिष्ट करता है कि ध्वनि अगले ध्वनि इवेंट तक लूप करेगी या नहीं। लिखें **bool**। |
| virtual void [set_SoundMode](./set_soundmode/)([SlideShow::TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/)) | स्लाइड ट्रांज़िशन के लिए साउंड मोड सेट या लौटाता है। लिखें [TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/)। |
| virtual void [set_SoundName](./set_soundname/)([System::String](../../system/string/)) | ट्रांज़िशन की ध्वनि के लिए मानव-पठन योग्य नाम निर्दिष्ट करता है। ध्वनि नाम प्राप्त या सेट करने के लिये [ISlideShowTransition::set_Sound](./set_sound/) को असाइन करना आवश्यक है। लिखें [System::String](../../system/string/)। |
| virtual void [set_Speed](./set_speed/)([SlideShow::TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/)) | ट्रांज़िशन गति निर्दिष्ट करता है जिसे वर्तमान स्लाइड से अगले तक ट्रांज़िशन करते समय उपयोग किया जाएगा। लिखें [TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/)। |
| virtual void [set_Type](./set_type/)([SlideShow::TransitionType](../../aspose.slides.slideshow/transitiontype/)) | ट्रांज़िशन का प्रकार। लिखें [TransitionType](../../aspose.slides.slideshow/transitiontype/)। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्युमेंट को weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनर्स में पॉइंटर्स को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | शेयरड रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | शेयरड रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | शेयरड रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट के अनलॉक को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## देखें भी

* क्लास [Object](../../system/object/)
* नेमस्पेस [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)