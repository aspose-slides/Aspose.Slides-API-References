---
title: IReflection
second_title: Aspose.Slides for C++ API संदर्भ
description: परावर्तन प्रभाव का प्रतिनिधित्व करता है।
type: docs
weight: 937
url: /hi/aspose.slides.effects/ireflection/
---
## IReflection क्लास

परावर्तन प्रभाव का प्रतिनिधित्व करता है।

```cpp
class IReflection : public virtual Aspose::Slides::Effects::IImageTransformOperation,
                    public Aspose::Slides::IAccessiblePVIObject<System::SharedPtr<Aspose::Slides::Effects::IReflectionEffectiveData>>
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantics का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-style फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के लिए भी नहीं। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-style फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के लिए भी नहीं। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual **double** [get_BlurRadius](./get_blurradius/)() | [Blur](../blur/) त्रिज्या। पढ़ें **double**। |
| virtual **float** [get_Direction](./get_direction/)() | परावर्तन की दिशा। पढ़ें **float**। |
| virtual **double** [get_Distance](./get_distance/)() | परावर्तन की दूरी। पढ़ें **double**। |
| virtual **float** [get_EndPosAlpha](./get_endposalpha/)() | अंत अल्फा मान (प्रतिशत) की अंत स्थिति (अल्फा ग्रेडिएंट रैंप के साथ) निर्दिष्ट करता है। पढ़ें **float**। |
| virtual **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() | अंत परावर्तन अपारदर्शिता। (प्रतिशत)। पढ़ें **float**। |
| virtual **float** [get_FadeDirection](./get_fadedirection/)() | परावर्तन को ऑफ़सेट करने की दिशा (कोण) निर्दिष्ट करता है। पढ़ें **float**। |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | आयत संरेखण। पढ़ें [RectangleAlignment](../../aspose.slides/rectanglealignment/)। |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | यदि आकृति घुमाई गई है तो परावर्तन को आकृति के साथ घुमाना चाहिए या नहीं निर्दिष्ट करता है। पढ़ें **bool**। |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | क्षैतिज स्केलिंग फ़ैक्टर निर्दिष्ट करता है, नकारात्मक स्केलिंग उलटा बनाता है। (प्रतिशत) पढ़ें **double**। |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | ऊर्ध्वाधर स्केलिंग फ़ैक्टर निर्दिष्ट करता है, नकारात्मक स्केलिंग उलटा बनाता है। (प्रतिशत) पढ़ें **double**। |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | क्षैतिज स्क्यू कोण निर्दिष्ट करता है। पढ़ें **double**। |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | ऊर्ध्वाधर स्क्यू कोण निर्दिष्ट करता है। पढ़ें **double**। |
| virtual **float** [get_StartPosAlpha](./get_startposalpha/)() | शुरूआत अल्फा मान (प्रतिशत) की प्रारंभ स्थिति (अल्फा ग्रेडिएंट रैंप के साथ) निर्दिष्ट करता है। पढ़ें **float**। |
| virtual **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() | प्रारंभिक परावर्तन अपारदर्शिता। (प्रतिशत)। पढ़ें **float**। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual T [GetEffective](../../aspose.slides/iaccessiblepviobject/geteffective/)() | विरासत लागू होने के साथ प्रभावी डेटा प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समान। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समान। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक इंस्टेंस दर्शाता है या नहीं। C# 'is' ऑपरेटर का समान। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समान। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को आरंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट आरंभ करता है और सबक्लासेज की कॉपी कंस्ट्रक्शन सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट आरंभ करता है और सबक्लासेज की कॉपी कंस्ट्रक्शन सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू प्रकार ऑब्जेक्ट को nullptr के साथ रेफ़रेंस-तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | string और nullptr के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के मामले के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंटर को घटाता है। |
| virtual void [set_BlurRadius](./set_blurradius/)(**double**) | [Blur](../blur/) त्रिज्या। लिखें **double**। |
| virtual void [set_Direction](./set_direction/)(**float**) | परावर्तन की दिशा। लिखें **float**। |
| virtual void [set_Distance](./set_distance/)(**double**) | परावर्तन की दूरी। लिखें **double**। |
| virtual void [set_EndPosAlpha](./set_endposalpha/)(**float**) | अंत अल्फा मान (प्रतिशत) की अंत स्थिति (अल्फा ग्रेडिएंट रैंप के साथ) निर्दिष्ट करता है। लिखें **float**। |
| virtual void [set_EndReflectionOpacity](./set_endreflectionopacity/)(**float**) | अंत परावर्तन अपारदर्शिता। (प्रतिशत)। लिखें **float**। |
| virtual void [set_FadeDirection](./set_fadedirection/)(**float**) | परावर्तन को ऑफ़सेट करने की दिशा (कोण) निर्दिष्ट करता है। लिखें **float**। |
| virtual void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) | आयत संरेखण। लिखें [RectangleAlignment](../../aspose.slides/rectanglealignment/)। |
| virtual void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) | यदि आकृति घुमाई गई है तो परावर्तन को आकृति के साथ घुमाना चाहिए या नहीं निर्दिष्ट करता है। लिखें **bool**। |
| virtual void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) | क्षैतिज स्केलिंग फ़ैक्टर निर्दिष्ट करता है, नकारात्मक स्केलिंग उलटा बनाता है। (प्रतिशत) लिखें **double**। |
| virtual void [set_ScaleVertical](./set_scalevertical/)(**double**) | ऊर्ध्वाधर स्केलिंग फ़ैक्टर निर्दिष्ट करता है, नकारात्मक स्केलिंग उलटा बनाता है। (प्रतिशत) लिखें **double**। |
| virtual void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) | क्षैतिज स्क्यू कोण निर्दिष्ट करता है। लिखें **double**। |
| virtual void [set_SkewVertical](./set_skewvertical/)(**double**) | ऊर्ध्वाधर स्क्यू कोण निर्दिष्ट करता है। लिखें **double**। |
| virtual void [set_StartPosAlpha](./set_startposalpha/)(**float**) | शुरूआत अल्फा मान (प्रतिशत) की प्रारंभ स्थिति (अल्फा ग्रेडिएंट रैंप के साथ) निर्दिष्ट करता है। लिखें **float**। |
| virtual void [set_StartReflectionOpacity](./set_startreflectionopacity/)(**float**) | प्रारंभिक परावर्तन अपारदर्शिता। (प्रतिशत)। लिखें **float**। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्यूमेंट को कमजोर पॉइंटर (शेयर किए गए के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को कमजोर मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समान। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |
## देखें भी

* क्लास [IImageTransformOperation](../iimagetransformoperation/)
* क्लास [IAccessiblePVIObject](../../aspose.slides/iaccessiblepviobject/)
* नामस्थान [Aspose::Slides::Effects](../)
* लाइब्रेरी [Aspose.Slides](../../)