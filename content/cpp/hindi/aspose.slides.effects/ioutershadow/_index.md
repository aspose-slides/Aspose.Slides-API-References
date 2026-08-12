---
title: IOuterShadow
second_title: Aspose.Slides for C++ API संदर्भ
description: एक बाहरी छाया प्रभाव का प्रतिनिधित्व करता है।
type: docs
weight: 885
url: /hi/aspose.slides.effects/ioutershadow/
---
## IOuterShadow क्लास

बाहरी छाया प्रभाव का प्रतिनिधित्व करता है।

```cpp
class IOuterShadow : public virtual Aspose::Slides::Effects::IImageTransformOperation,
                     public Aspose::Slides::IAccessiblePVIObject<System::SharedPtr<Aspose::Slides::Effects::IOuterShadowEffectiveData>>
```

## विधियां

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| virtual **double** [get_BlurRadius](./get_blurradius/)() | [Blur](../blur/) त्रिज्या, पॉइंट में। डिफ़ॉल्ट मान – 0 pt। पढ़ें **double**। |
| virtual **float** [get_Direction](./get_direction/)() | छाया की दिशा, डिग्री में। डिफ़ॉल्ट मान – 0 ° (बाएँ-से-दाएँ)। पढ़ें **float**। |
| virtual **double** [get_Distance](./get_distance/)() | छाया की वस्तु से दूरी, पॉइंट में। डिफ़ॉल्ट मान – 0 pt। पढ़ें **double**। |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | आयत संरेखण। डिफ़ॉल्ट मान – [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/)। पढ़ें [RectangleAlignment](../../aspose.slides/rectanglealignment/)। |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | दर्शाता है कि क्या छाया आकार के साथ घुमती है। डिफ़ॉल्ट मान – true। पढ़ें **bool**। |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | अक्षीय स्केलिंग फ़ैक्टर, मूल आकार के प्रतिशत में। नकारात्मक स्केलिंग से फ़्लिप होता है। डिफ़ॉल्ट मान – 100 %। पढ़ें **double**। |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | ऊर्ध्व स्केलिंग फ़ैक्टर, मूल आकार के प्रतिशत में। नकारात्मक स्केलिंग से फ़्लिप होता है। डिफ़ॉल्ट मान – 100 %। पढ़ें **double**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ShadowColor](./get_shadowcolor/)() | छाया का रंग। डिफ़ॉल्ट मान – स्वचालित काला (थीम-निर्भर)। केवल-पढ़ने योग्य [IColorFormat](../../aspose.slides/icolorformat/)। |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | अक्षीय स्क्यू कोण, डिग्री में। डिफ़ॉल्ट मान – 0 °। पढ़ें **double**। |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | ऊर्ध्व स्क्यू कोण, डिग्री में। डिफ़ॉल्ट मान – 0 °। पढ़ें **double**। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual T [GetEffective](../../aspose.slides/iaccessiblepviobject/geteffective/)() | विरासत लागू किए गए प्रभावी डेटा प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँच करता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स को क्लोन करने में सक्षम बनाता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तविक में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तविक में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्टिंग सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस-तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का स्पेशलाइज़ेशन। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का स्पेशलाइज़ेशन। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंटर को घटाता है। |
| virtual void [set_BlurRadius](./set_blurradius/)(**double**) | [Blur](../blur/) त्रिज्या, पॉइंट में। डिफ़ॉल्ट मान – 0 pt। लिखें **double**। |
| virtual void [set_Direction](./set_direction/)(**float**) | छाया की दिशा, डिग्री में। डिफ़ॉल्ट मान – 0 ° (बाएँ-से-दाएँ)। लिखें **float**। |
| virtual void [set_Distance](./set_distance/)(**double**) | छाया की वस्तु से दूरी, पॉइंट में। डिफ़ॉल्ट मान – 0 pt। लिखें **double**। |
| virtual void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) | आयत संरेखण। डिफ़ॉल्ट मान – [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/)। लिखें [RectangleAlignment](../../aspose.slides/rectanglealignment/)। |
| virtual void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) | दर्शाता है कि क्या छाया आकार के साथ घुमती है। डिफ़ॉल्ट मान – true। लिखें **bool**। |
| virtual void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) | अक्षीय स्केलिंग फ़ैक्टर, मूल आकार के प्रतिशत में। नकारात्मक स्केलिंग से फ़्लिप होता है। डिफ़ॉल्ट मान – 100 %। लिखें **double**। |
| virtual void [set_ScaleVertical](./set_scalevertical/)(**double**) | ऊर्ध्व स्केलिंग फ़ैक्टर, मूल आकार के प्रतिशत में। नकारात्मक स्केलिंग से फ़्लिप होता है। डिफ़ॉल्ट मान – 100 %। लिखें **double**। |
| virtual void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) | अक्षीय स्क्यू कोण, डिग्री में। डिफ़ॉल्ट मान – 0 °। लिखें **double**। |
| virtual void [set_SkewVertical](./set_skewvertical/)(**double**) | ऊर्ध्व स्क्यू कोण, डिग्री में। डिफ़ॉल्ट मान – 0 °। लिखें **double**। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्ग्यूमेंट को कमजोर पॉइंटर (साझा के बजाय) सेट करें। कंटेनरों में पॉइंटर को कमजोर मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंटर को बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंटर को घटाता है और लौटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंटर को बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंटर को घटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## देखें

* क्लास [IImageTransformOperation](../iimagetransformoperation/)
* क्लास [IAccessiblePVIObject](../../aspose.slides/iaccessiblepviobject/)
* नामस्थान [Aspose::Slides::Effects](../)
* लाइब्रेरी [Aspose.Slides](../../)