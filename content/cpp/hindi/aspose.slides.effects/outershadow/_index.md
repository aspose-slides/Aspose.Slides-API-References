---
title: OuterShadow
second_title: Aspose.Slides C++ के लिए API रेफ़रेंस
description: एक Outer Shadow प्रभाव का प्रतिनिधित्व करता है।
type: docs
weight: 1041
url: /hi/aspose.slides.effects/outershadow/
---
## OuterShadow क्लास

एक Outer Shadow प्रभाव का प्रतिनिधित्व करता है।

```cpp
class OuterShadow : public Aspose::Slides::Effects::IOuterShadow,
                    public Aspose::Slides::Effects::IVisualEffect,
                    public Aspose::Slides::IPVIObject
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | निश्चित करता है कि निर्दिष्ट [OuterShadow](./) वर्तमान [OuterShadow](./) के बराबर है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सिमैंटिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-स्टाइल फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-स्टाइल फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| **double** [get_BlurRadius](./get_blurradius/)() override | [Blur](../blur/) त्रिज्या, पॉइंट्स में। डिफ़ॉल्ट मान \\u2013 0 pt। पढ़ें **double**। |
| **float** [get_Direction](./get_direction/)() override | छाया की दिशा, डिग्री में। डिफ़ॉल्ट मान \\u2013 0 \\u00B0 (बाएँ से दाएँ)। पढ़ें **float**। |
| **double** [get_Distance](./get_distance/)() override | छाया की वस्तु से दूरी, पॉइंट्स में। डिफ़ॉल्ट मान \\u2013 0 pt। पढ़ें **double**। |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | पेरेंट [IPresentationComponent](../../aspose.slides/ipresentationcomponent/) लौटाता है। केवल-पढ़ने-योग्य [IPresentationComponent](../../aspose.slides/ipresentationcomponent/)। |
| [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() override | आयत संरेखण। डिफ़ॉल्ट मान [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/)। पढ़ें [RectangleAlignment](../../aspose.slides/rectanglealignment/)। |
| **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() override | संकेत करता है कि छाया आकार के साथ घुमती है या नहीं। डिफ़ॉल्ट मान – true। पढ़ें **bool**। |
| **double** [get_ScaleHorizontal](./get_scalehorizontal/)() override | क्षैतिज स्केलिंग फैक्टर, मूल आकार के प्रतिशत में। नकारात्मक स्केलिंग एक फ्लिप का कारण बनती है। डिफ़ॉल्ट मान – 100 %。 पढ़ें **double**। |
| **double** [get_ScaleVertical](./get_scalevertical/)() override | लंबवत स्केलिंग फैक्टर, मूल आकार के प्रतिशत में। नकारात्मक स्केलिंग एक फ्लिप का कारण बनती है। डिफ़ॉल्ट मान – 100 %。 पढ़ें **double**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ShadowColor](./get_shadowcolor/)() override | छाया का रंग। डिफ़ॉल्ट मान – स्वचालित काला (थीम-निर्भर)। केवल-पढ़ने-योग्य [IColorFormat](../../aspose.slides/icolorformat/)। |
| **double** [get_SkewHorizontal](./get_skewhorizontal/)() override | क्षैतिज स्क्यू कोण, डिग्री में। डिफ़ॉल्ट मान – 0 °. पढ़ें **double**। |
| **double** [get_SkewVertical](./get_skewvertical/)() override | लंबवत स्क्यू कोण, डिग्री में। डिफ़ॉल्ट मान – 0 °. पढ़ें **double**। |
| virtual ASPOSE_SLIDES_LOCAL_API **uint32_t** [get_Version](../../aspose.slides/ipviobject/get_version/)() | संस्करण। केवल-पढ़ने-योग्य **uint32_t**। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IOuterShadowEffectiveData](../ioutershadoweffectivedata/)\> [GetEffective](./geteffective/)() override | वंशानुक्रम लागू करके प्रभावी Outer Shadow प्रभाव डेटा प्राप्त करता है। |
| **int32_t** [GetHashCode](./gethashcode/)() const override | किसी विशिष्ट प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि क्या ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट का लॉक लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लास की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लास की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | निल पॉइंटर के साथ वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस-तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए स्पेशलाइज़ेशन। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए स्पेशलाइज़ेशन। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा शेयर किए गए रेफ़रेंस काउंटर को कम करता है। |
| void [set_BlurRadius](./set_blurradius/)(**double**) override | [Blur](../blur/) त्रिज्या, पॉइंट्स में। डिफ़ॉल्ट मान \\u2013 0 pt। लिखें **double**। |
| void [set_Direction](./set_direction/)(**float**) override | छाया की दिशा, डिग्री में। डिफ़ॉल्ट मान \\u2013 0 \\u00B0 (बाएँ से दाएँ)। लिखें **float**। |
| void [set_Distance](./set_distance/)(**double**) override | छाया की वस्तु से दूरी, पॉइंट्स में। डिफ़ॉल्ट मान \\u2013 0 pt। लिखें **double**। |
| void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) override | आयत संरेखण। डिफ़ॉल्ट मान \\u2013 [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/)। लिखें [RectangleAlignment](../../aspose.slides/rectanglealignment/)। |
| void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) override | संकेत करता है कि छाया आकार के साथ घुमती है या नहीं। डिफ़ॉल्ट मान – true। लिखें **bool**। |
| void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) override | क्षैतिज स्केलिंग फैक्टर, मूल आकार के प्रतिशत में। नकारात्मक स्केलिंग एक फ्लिप का कारण बनती है। डिफ़ॉल्ट मान – 100 %。 लिखें **double**। |
| void [set_ScaleVertical](./set_scalevertical/)(**double**) override | लंबवत स्केलिंग फैक्टर, मूल आकार के प्रतिशत में। नकारात्मक स्केलिंग एक फ्लिप का कारण बनती है। डिफ़ॉल्ट मान – 100 %。 लिखें **double**। |
| void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) override | क्षैतिज स्क्यू कोण, डिग्री में। डिफ़ॉल्ट मान – 0 °. लिखें **double**। |
| void [set_SkewVertical](./set_skewvertical/)(**double**) override | लंबवत स्क्यू कोण, डिग्री में। डिफ़ॉल्ट मान – 0 °. लिखें **double**। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्यूमेंट को एक वेक पॉइंटर (शेयर किए हुए के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को वेक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | शेयर किए गए रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | शेयर रेफ़रेंस काउंटर को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | शेयर रेफ़रेंस काउंटर को घटाता है और लौटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉक को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वेक रेफ़रेंस काउंटर को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वेक रेफ़रेंस काउंटर को घटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## देखें

* क्लास [IOuterShadow](../ioutershadow/)
* क्लास [IVisualEffect](../ivisualeffect/)
* क्लास [IPVIObject](../../aspose.slides/ipviobject/)
* नेमस्पेस [Aspose::Slides::Effects](../)
* लाइब्रेरी [Aspose.Slides](../../)