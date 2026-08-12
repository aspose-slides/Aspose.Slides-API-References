---
title: IReflectionEffectiveData
second_title: Aspose.Slides for C++ API संदर्भ
description: एक अपरिवर्तनीय ऑब्जेक्ट जो परावर्तन प्रभाव का प्रतिनिधित्व करता है।
type: docs
weight: 950
url: /hi/aspose.slides.effects/ireflectioneffectivedata/
---
## IReflectionEffectiveData वर्ग

एक अपरिवर्तनीय ऑब्जेक्ट जो [Reflection](../reflection/) इफ़ेक्ट का प्रतिनिधित्व करता है।

```cpp
class IReflectionEffectiveData : public virtual Aspose::Slides::Effects::IEffectEffectiveData
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमान्टिक का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली का फ्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को समान माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली का फ्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को समान माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual **double** [get_BlurRadius](./get_blurradius/)() | [Blur](../blur/) त्रिज्या। केवल पढ़ने योग्य **double**। |
| virtual **float** [get_Direction](./get_direction/)() | परावर्तन की दिशा। केवल पढ़ने योग्य **float**। |
| virtual **double** [get_Distance](./get_distance/)() | परावर्तन की दूरी। केवल पढ़ने योग्य **double**। |
| virtual **float** [get_EndPosAlpha](./get_endposalpha/)() | अंत अल्फा मान (प्रतिशत) की अंत स्थिति (अल्फा ग्रेडिएंट रैंप के साथ) को निर्दिष्ट करता है। केवल पढ़ने योग्य **float**। |
| virtual **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() | परावर्तन की अंतिम अपारदर्शिता (प्रतिशत)। केवल पढ़ने योग्य **float**। |
| virtual **float** [get_FadeDirection](./get_fadedirection/)() | परावर्तन को ऑफ़सेट करने की दिशा (कोण) निर्दिष्ट करता है। केवल पढ़ने योग्य **float**। |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | आयत संरेखण। केवल पढ़ने योग्य [RectangleAlignment](../../aspose.slides/rectanglealignment/)। |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | यदि आकार घुमाया गया हो तो परावर्तन को आकार के साथ घुमाया जाना चाहिए या नहीं निर्दिष्ट करता है। केवल पढ़ने योग्य **bool**। |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | क्षैतिज स्केलिंग कारक निर्दिष्ट करता है, नकारात्मक स्केलिंग फ़्लिप का कारण बनती है। (प्रतिशत) केवल पढ़ने योग्य **double**। |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | ऊर्ध्वाधर स्केलिंग कारक निर्दिष्ट करता है, नकारात्मक स्केलिंग फ़्लिप का कारण बनती है। (प्रतिशत) केवल पढ़ने योग्य **double**। |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | क्षैतिज स्क्यू कोण निर्दिष्ट करता है। केवल पढ़ने योग्य **double**। |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | ऊर्ध्वाधर स्क्यू कोण निर्दिष्ट करता है। केवल पढ़ने योग्य **double**। |
| virtual **float** [get_StartPosAlpha](./get_startposalpha/)() | शुरू अल्फा मान (प्रतिशत) की प्रारम्भिक स्थिति (अल्फा ग्रेडिएंट रैंप के साथ) निर्दिष्ट करता है। केवल पढ़ने योग्य **float**। |
| virtual **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() | परावर्तन की प्रारम्भिक अपारदर्शिता (प्रतिशत)। केवल पढ़ने योग्य **float**। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक टाइप प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित टाइप का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स को क्लोन करने में सक्षम बनाता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेस की कॉपी कंस्ट्रक्शन सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेस की कॉपी कंस्ट्रक्टिंग सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस द्वारा वैल्यू टाइप ऑब्जेक्ट की तुलना nullptr के साथ करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्धारित मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्गुमेंट को वीक पॉइंटर (शेयर किए हुए के बजाय) सेट करता है। कंटेनर्स में पॉइंटर्स को वीक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने में सक्षम बनाता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## संबंधित देखें

* वर्ग [IEffectEffectiveData](../ieffecteffectivedata/)
* नामस्थान [Aspose::Slides::Effects](../)
* लाइब्रेरी [Aspose.Slides](../../)