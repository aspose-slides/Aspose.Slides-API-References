---
title: ITextFrameFormat
second_title: Aspose.Slides for C++ API संदर्भ
description: TextFrame के स्वरूपण गुणों को शामिल करता है।
type: docs
weight: 4083
url: /hi/aspose.slides/itextframeformat/
---
## ITextFrameFormat क्लास

[TextFrame](../textframe/) की स्वरूपण गुणों को शामिल करता है।

```cpp
class ITextFrameFormat : public virtual System::Object
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमैन्टिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के साथ भी नहीं। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के साथ भी नहीं। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| virtual [TextAnchorType](../textanchortype/) [get_AnchoringType](./get_anchoringtype/)() | एक [TextFrame](../textframe/) में वर्टिकल एंकर टेक्स्ट वापस करता है। पढ़ें [TextAnchorType](../textanchortype/)। |
| virtual [TextAutofitType](../textautofittype/) [get_AutofitType](./get_autofittype/)() | टेक्स्ट का ऑटोफ़िट मोड वापस करता है। पढ़ें [TextAutofitType](../textautofittype/)। |
| virtual [NullableBool](../nullablebool/) [get_CenterText](./get_centertext/)() | यदि [NullableBool::True](../nullablebool/) तो टेक्स्ट को बॉक्स में क्षैतिज रूप से केंद्रित किया जाना चाहिए। पढ़ें [NullableBool](../nullablebool/)। |
| virtual **int32_t** [get_ColumnCount](./get_columncount/)() | टेक्स्ट एरिया में कॉलम की संख्या लौटाता है। यह मान एक सकारात्मक संख्या होना चाहिए। अन्यथा, मान को शून्य सेट किया जाएगा। मान 0 का अर्थ अनिर्धारित मान है। पढ़ें **int32_t**। |
| virtual **double** [get_ColumnSpacing](./get_columnspacing/)() | टेक्स्ट एरिया में टेक्स्ट कॉलमों के बीच की दूरी (पॉइंट्स में) लौटाता है। यह केवल तब लागू होना चाहिए जब एक से अधिक कॉलम मौजूद हों। यह मान एक सकारात्मक संख्या होना चाहिए। अन्यथा, मान को शून्य सेट किया जाएगा। पढ़ें **double**। |
| virtual **bool** [get_KeepTextFlat](./get_keeptextflat/)() | टेक्स्ट को पूरी तरह 3D सीन से बाहर रखने को लौटाता है या सेट करता है। पढ़ें **bool**। |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | एक [TextFrame](../textframe/) में नीचे की मार्जिन (पॉइंट्स) लौटाता है। पढ़ें **double**। |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | एक [TextFrame](../textframe/) में बायाँ मार्जिन (पॉइंट्स) लौटाता है। पढ़ें **double**। |
| virtual **double** [get_MarginRight](./get_marginright/)() | एक [TextFrame](../textframe/) में दायाँ मार्जिन (पॉइंट्स) लौटाता है। पढ़ें **double**। |
| virtual **double** [get_MarginTop](./get_margintop/)() | एक [TextFrame](../textframe/) में शीर्ष मार्जिन (पॉइंट्स) लौटाता है। पढ़ें **double**। |
| virtual **float** [get_RotationAngle](./get_rotationangle/)() | बाउंडिंग बॉक्स के भीतर टेक्स्ट पर लागू कस्टम घुमाव को निर्दिष्ट करता है। यदि निर्दिष्ट नहीं किया गया, तो साथ वाले आकार का घुमाव उपयोग होता है। यदि निर्दिष्ट किया गया, तो यह आकार से स्वतंत्र रूप से लागू होता है। अर्थात् आकार में घुमाव लागू हो सकता है साथ ही टेक्स्ट पर भी घुमाव लागू हो सकता है। इस प्रॉपर्टी और प्रॉपर्टी TextVerticalType में पूर्वनिर्धारित वर्टिकल टाइप से विज़ुअल टेक्स्ट घुमाव का सारांशित मान प्राप्त होता है। पढ़ें **float**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_TextStyle](./get_textstyle/)() | टेक्स्ट की शैली लौटाता है। केवल-पढ़ने योग्य [ITextStyle](../itextstyle/)। |
| virtual [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | टेक्स्ट अभिविन्यास निर्धारित करता है। इस प्रॉपर्टी और प्रॉपर्टी RotationAngle में कस्टम एंगल से विज़ुअल टेक्स्ट घुमाव का सारांशित मान प्राप्त होता है। पढ़ें [Slides::TextVerticalType](../textverticaltype/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() | [ThreeDFormat](../threedformat/) ऑब्जेक्ट लौटाता है जो टेक्स्ट के 3D इफ़ेक्ट प्रॉपर्टीज़ को दर्शाता है। केवल-पढ़ने योग्य [IThreeDFormat](../ithreedformat/)। |
| virtual [TextShapeType](../textshapetype/) [get_Transform](./get_transform/)() | टेक्स्ट रैपिंग शेप प्राप्त करता है। पढ़ें [TextShapeType](../textshapetype/)। |
| virtual [NullableBool](../nullablebool/) [get_WrapText](./get_wraptext/)() | यदि टेक्स्ट [TextFrame](../textframe/) की मार्जिन पर रैप किया गया हो तो **True**। पढ़ें [NullableBool](../nullablebool/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormatEffectiveData](../itextframeformateffectivedata/)\> [GetEffective](./geteffective/)() | विरासत लागू होने के साथ प्रभावी टेक्स्ट फ्रेम फ़ॉर्मेटिंग डेटा प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंटीनी ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स को क्लोन करने को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तविक में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस तुलना nullptr के साथ करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए स्पेशलाइज़ेशन। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए स्पेशलाइज़ेशन। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../textanchortype/)) | [TextFrame](../textframe/) में वर्टिकल एंकर टेक्स्ट सेट करता है। लिखें [TextAnchorType](../textanchortype/)। |
| virtual void [set_AutofitType](./set_autofittype/)([TextAutofitType](../textautofittype/)) | टेक्स्ट का ऑटोफ़िट मोड सेट करता है। लिखें [TextAutofitType](../textautofittype/)। |
| virtual void [set_CenterText](./set_centertext/)([NullableBool](../nullablebool/)) | यदि [NullableBool::True](../nullablebool/) तो टेक्स्ट को बॉक्स में क्षैतिज रूप से केंद्रित किया जाना चाहिए। लिखें [NullableBool](../nullablebool/)। |
| virtual void [set_ColumnCount](./set_columncount/)(**int32_t**) | टेक्स्ट एरिया में कॉलम की संख्या सेट करता है। यह मान एक सकारात्मक संख्या होना चाहिए। अन्यथा, मान को शून्य सेट किया जाएगा। मान 0 का अर्थ अनिर्धारित मान है। लिखें **int32_t**। |
| virtual void [set_ColumnSpacing](./set_columnspacing/)(**double**) | टेक्स्ट एरिया में टेक्स्ट कॉलमों के बीच की दूरी (पॉइंट्स में) सेट करता है। यह केवल तब लागू होना चाहिए जब एक से अधिक कॉलम मौजूद हों। यह मान एक सकारात्मक संख्या होना चाहिए। अन्यथा, मान को शून्य सेट किया जाएगा। लिखें **double**। |
| virtual void [set_KeepTextFlat](./set_keeptextflat/)(**bool**) | टेक्स्ट को पूरी तरह 3D सीन से बाहर रखने को लौटाता है या सेट करता है। लिखें **bool**। |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | [TextFrame](../textframe/) में नीचे की मार्जिन (पॉइंट्स) सेट करता है। लिखें **double**। |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | [TextFrame](../textframe/) में बायाँ मार्जिन (पॉइंट्स) सेट करता है। लिखें **double**। |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | [TextFrame](../textframe/) में दायाँ मार्जिन (पॉइंट्स) सेट करता है। लिखें **double**। |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | [TextFrame](../textframe/) में शीर्ष मार्जिन (पॉइंट्स) सेट करता है। लिखें **double**। |
| virtual void [set_RotationAngle](./set_rotationangle/)(**float**) | बाउंडिंग बॉक्स के भीतर टेक्स्ट पर लागू कस्टम घुमाव को निर्दिष्ट करता है। यदि निर्दिष्ट नहीं किया गया, तो साथ वाले आकार का घुमाव उपयोग होता है। यदि निर्दिष्ट किया गया, तो यह आकार से स्वतंत्र रूप से लागू होता है। अर्थात् आकार में घुमाव लागू हो सकता है साथ ही टेक्स्ट पर भी घुमाव लागू हो सकता है। इस प्रॉपर्टी और प्रॉपर्टी TextVerticalType में पूर्वनिर्धारित वर्टिकल टाइप से विज़ुअल टेक्स्ट घुमाव का सारांशित मान प्राप्त होता है। लिखें **float**। |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) | टेक्स्ट अभिविन्यास निर्धारित करता है। इस प्रॉपर्टी और प्रॉपर्टी RotationAngle में कस्टम एंगल से विज़ुअल टेक्स्ट घुमाव का सारांशित मान प्राप्त होता है। लिखें [Slides::TextVerticalType](../textverticaltype/)। |
| virtual void [set_Transform](./set_transform/)([TextShapeType](../textshapetype/)) | टेक्स्ट रैपिंग शेप सेट करता है। लिखें [TextShapeType](../textshapetype/)। |
| virtual void [set_WrapText](./set_wraptext/)([NullableBool](../nullablebool/)) | यदि टेक्स्ट [TextFrame](../textframe/) की मार्जिन पर रैप किया गया हो तो **True**। लिखें [NullableBool](../nullablebool/)। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्ग्यूमेंट को कमजोर पॉइंटर (शेयर किए हुए के बजाय) सेट करता है। कंटेनरों में पॉइंटर को कमजोर मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | शेयर किए हुए रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | शेयर किए हुए रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | शेयर किए हुए रेफ़रेंस काउंटर को घटाता है और लौटाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंटीनी ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट को घटाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## देखें

* क्लास [Object](../../system/object/)
* नामस्थान [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)