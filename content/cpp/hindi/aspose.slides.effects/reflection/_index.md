---
title: Reflection
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: एक Reflection प्रभाव का प्रतिनिधित्व करता है।
type: docs
weight: 1067
url: /hi/aspose.slides.effects/reflection/
---
## Reflection क्लास

एक [Reflection](./) प्रभाव का प्रतिनिधित्व करता है।

```cpp
class Reflection : public Aspose::Slides::Effects::IReflection,
                   public Aspose::Slides::Effects::IVisualEffect,
                   public Aspose::Slides::IPVIObject
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | निर्धारित करता है कि निर्दिष्ट [Reflection](./) वर्तमान [Reflection](./) के बराबर है या नहीं। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमान्टिक का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| **double** [get_BlurRadius](./get_blurradius/)() override | [Blur](../blur/) त्रिज्या। पढ़ें **double**। |
| **float** [get_Direction](./get_direction/)() override | परावर्तन की दिशा। पढ़ें **float**। |
| **double** [get_Distance](./get_distance/)() override | परावर्तन की दूरियाँ। पढ़ें **double**। |
| **float** [get_EndPosAlpha](./get_endposalpha/)() override | अंत अल्फा मान (प्रतिशत) की अंत स्थिति (अल्फा ग्रेडिएंट रैंप के साथ) निर्दिष्ट करता है। पढ़ें **float**। |
| **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() override | अंत परावर्तन अपारदर्शिता। (प्रतिशत)। पढ़ें **float**। |
| **float** [get_FadeDirection](./get_fadedirection/)() override | परावर्तन को ऑफसेट करने की दिशा निर्दिष्ट करता है। (कोण)। पढ़ें **float**। |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | पैरेंट [IPresentationComponent](../../aspose.slides/ipresentationcomponent/) लौटाता है। केवल पढ़ने योग्य [IPresentationComponent](../../aspose.slides/ipresentationcomponent/)। |
| [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() override | आयत संरेखण। पढ़ें [RectangleAlignment](../../aspose.slides/rectanglealignment/)। |
| **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() override | यदि आकार घुमाया गया है तो परावर्तन को आकार के साथ घुमाना चाहिए या नहीं, निर्दिष्ट करता है। पढ़ें **bool**। |
| **double** [get_ScaleHorizontal](./get_scalehorizontal/)() override | क्षैतिज स्केलिंग फ़ैक्टर निर्दिष्ट करता है, नकारात्मक स्केलिंग फ़्लिप उत्पन्न करता है। (प्रतिशत) पढ़ें **double**। |
| **double** [get_ScaleVertical](./get_scalevertical/)() override | लंबवत स्केलिंग फ़ैक्टर निर्दिष्ट करता है, नकारात्मक स्केलिंग फ़्लिप उत्पन्न करता है। (प्रतिशत) पढ़ें **double**। |
| **double** [get_SkewHorizontal](./get_skewhorizontal/)() override | क्षैतिज विकृति कोण निर्दिष्ट करता है। पढ़ें **double**। |
| **double** [get_SkewVertical](./get_skewvertical/)() override | लंबवत विकृति कोण निर्दिष्ट करता है। पढ़ें **double**। |
| **float** [get_StartPosAlpha](./get_startposalpha/)() override | प्रारम्भिक अल्फा मान (प्रतिशत) की शुरूआती स्थिति (अल्फा ग्रेडिएंट रैंप के साथ) निर्दिष्ट करता है। पढ़ें **float**। |
| **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() override | प्रारम्भिक परावर्तन अपारदर्शिता। (प्रतिशत)। पढ़ें **float**। |
| virtual ASPOSE_SLIDES_LOCAL_API **uint32_t** [get_Version](../../aspose.slides/ipviobject/get_version/)() | संस्करण। केवल पढ़ने योग्य **uint32_t**। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IReflectionEffectiveData](../ireflectioneffectivedata/)\> [GetEffective](./geteffective/)() override | विरासत लागू के साथ प्रभावी [Reflection](./) प्रभाव डेटा प्राप्त करता है। |
| **int32_t** [GetHashCode](./gethashcode/)() const override | विशिष्ट प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को आरंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, सिर्फ नया ऑब्जेक्ट आरंभ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, सिर्फ नया ऑब्जेक्ट आरंभ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस द्वारा वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से शेयर्ड रेफ़रेंस काउण्ट घटाता है। |
| void [set_BlurRadius](./set_blurradius/)(**double**) override | [Blur](../blur/) त्रिज्या। लिखें **double**। |
| void [set_Direction](./set_direction/)(**float**) override | परावर्तन की दिशा। लिखें **float**। |
| void [set_Distance](./set_distance/)(**double**) override | परावर्तन की दूरी। लिखें **double**। |
| void [set_EndPosAlpha](./set_endposalpha/)(**float**) override | अंत अल्फा मान (प्रतिशत) की अंत स्थिति (अल्फा ग्रेडिएंट रैंप के साथ) निर्दिष्ट करता है। लिखें **float**। |
| void [set_EndReflectionOpacity](./set_endreflectionopacity/)(**float**) override | अंत परावर्तन अपारदर्शिता। (प्रतिशत)। लिखें **float**। |
| void [set_FadeDirection](./set_fadedirection/)(**float**) override | परावर्तन को ऑफसेट करने की दिशा निर्दिष्ट करता है। (कोण)। लिखें **float**। |
| void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) override | आयत संरेखण। लिखें [RectangleAlignment](../../aspose.slides/rectanglealignment/)। |
| void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) override | यदि आकार घुमाया गया है तो परावर्तन को आकार के साथ घुमाना चाहिए या नहीं, निर्दिष्ट करता है। लिखें **bool**। |
| void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) override | क्षैतिज स्केलिंग फ़ैक्टर निर्दिष्ट करता है, नकारात्मक स्केलिंग फ़्लिप उत्पन्न करता है। (प्रतिशत) लिखें **double**। |
| void [set_ScaleVertical](./set_scalevertical/)(**double**) override | लंबवत स्केलिंग फ़ैक्टर निर्दिष्ट करता है, नकारात्मक स्केलिंग फ़्लिप उत्पन्न करता है। (प्रतिशत) लिखें **double**। |
| void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) override | क्षैतिज विकृति कोण निर्दिष्ट करता है। लिखें **double**। |
| void [set_SkewVertical](./set_skewvertical/)(**double**) override | लंबवत विकृति कोण निर्दिष्ट करता है। लिखें **double**। |
| void [set_StartPosAlpha](./set_startposalpha/)(**float**) override | शुरूआती अल्फा मान (प्रतिशत) की शुरूआती स्थिति (अल्फा ग्रेडिएंट रैंप के साथ) निर्दिष्ट करता है। लिखें **float**। |
| void [set_StartReflectionOpacity](./set_startreflectionopacity/)(**float**) override | शुरूआती परावर्तन अपारदर्शिता। (प्रतिशत)। लिखें **float**। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्गुमेंट को weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनर्स में पॉइंटर्स को weak मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | शेयर्ड रेफ़रेंस काउण्टर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | शेयर्ड रेफ़रेंस काउण्ट बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | शेयर्ड रेफ़रेंस काउण्ट घटाता है और वापस करता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कॉन्स्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉक को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउण्ट बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउण्ट घटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## संबंधित देखें

* क्लास [IReflection](../ireflection/)
* क्लास [IVisualEffect](../ivisualeffect/)
* क्लास [IPVIObject](../../aspose.slides/ipviobject/)
* नेमस्पेस [Aspose::Slides::Effects](../)
* लाइब्रेरी [Aspose.Slides](../../)