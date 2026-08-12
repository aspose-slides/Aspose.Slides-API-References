---
title: TextFrameFormat
second_title: Aspose.Slides for C++ API संदर्भ
description: TextFrame की formatTextFrameFormatting प्रॉपर्टीज़ शामिल करता है।
type: docs
weight: 5461
url: /hi/aspose.slides/textframeformat/
---
## TextFrameFormat वर्ग

Contains the [TextFrame](../textframe/)'s formatTextFrameFormatting properties.

```cpp
class TextFrameFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::ITextFrameFormat,
                        public Aspose::Slides::Charts::IChartTextBlockFormat
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | निर्दिष्ट ऑब्जेक्ट के साथ तुलना करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटинг पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [TextAnchorType](../textanchortype/) [get_AnchoringType](./get_anchoringtype/)() override | एक [TextFrame](../textframe/) में वर्टिकल एंकर टेक्स्ट लौटाता है। पढ़ें [TextAnchorType](../textanchortype/)। |
| [TextAutofitType](../textautofittype/) [get_AutofitType](./get_autofittype/)() override | टेक्स्ट का ऑटोफिट मोड लौटाता है। पढ़ें [TextAutofitType](../textautofittype/)। |
| [NullableBool](../nullablebool/) [get_CenterText](./get_centertext/)() override | यदि [NullableBool::True](../nullablebool/) तो टेक्स्ट को बॉक्स में क्षैतिज रूप से केंद्रित किया जाना चाहिए। पढ़ें [NullableBool](../nullablebool/)। |
| **int32_t** [get_ColumnCount](./get_columncount/)() override | टेक्स्ट एरिया में कॉलम की संख्या लौटाता है। यह मान एक सकारात्मक संख्या होना चाहिए। अन्यथा, मान को शून्य सेट किया जाएगा। मान 0 अनिर्धारित मान दर्शाता है। पढ़ें **int32_t**। |
| **double** [get_ColumnSpacing](./get_columnspacing/)() override | टेक्स्ट एरिया में टेक्स्ट कॉलमों के बीच की दूरी (पॉइंट्स में) लौटाता है। यह केवल तब लागू होना चाहिए जब 1 से अधिक कॉलम मौजूद हों। यह मान एक सकारात्मक संख्या होना चाहिए। अन्यथा, मान शून्य सेट किया जाएगा। पढ़ें **double**। |
| **bool** [get_KeepTextFlat](./get_keeptextflat/)() override | यदि 3-डी रोटेशन इफ़ेक्ट लागू किया गया हो तब भी टेक्स्ट को सपाट रखने की स्थिति प्राप्त करता है। पढ़ें **bool**। |
| **double** [get_MarginBottom](./get_marginbottom/)() override | एक [TextFrame](../textframe/) में नीचे का मार्जिन (पॉइंट्स) लौटाता है। पढ़ें **double**। |
| **double** [get_MarginLeft](./get_marginleft/)() override | एक [TextFrame](../textframe/) में बायाँ मार्जिन (पॉइंट्स) लौटाता है। पढ़ें **double**। |
| **double** [get_MarginRight](./get_marginright/)() override | एक [TextFrame](../textframe/) में दाहिना मार्जिन (पॉइंट्स) लौटाता है। पढ़ें **double**। |
| **double** [get_MarginTop](./get_margintop/)() override | एक [TextFrame](../textframe/) में ऊपर का मार्जिन (पॉइंट्स) लौटाता है। पढ़ें **double**। |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [IDOMObject](../idomobject/)। |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | पेरेंट [IPresentationComponent](../ipresentationcomponent/) लौटाता है। केवल-पढ़ने योग्य [IPresentationComponent](../ipresentationcomponent/)। |
| **float** [get_RotationAngle](./get_rotationangle/)() override | बाउंडिंग बॉक्स के भीतर टेक्स्ट पर लागू होने वाली कस्टम रोटेशन निर्दिष्ट करता है। यदि निर्दिष्ट नहीं किया गया है, तो साथ वाले आकार का रोटेशन उपयोग किया जाता है। यदि निर्दिष्ट किया गया है, तो यह आकार से स्वतंत्र रूप से लागू होता है। अर्थात् आकार पर रोटेशन लागू हो सकता है और टेक्स्ट पर भी अलग से रोटेशन लागू हो सकता है। इस प्रॉपर्टी और प्रॉपर्टी TextVerticalType में परिभाषित वर्टिकल टाइप से संकलित दृश्य टेक्स्ट रोटेशन का परिणाम मिलता है। पढ़ें **float**। |
| [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() override | टेक्स्ट ओरिएंटेशन निर्धारित करता है। इस प्रॉपर्टी और प्रॉपर्टी RotationAngle में कस्टम एंगल से संकलित दृश्य टेक्स्ट रोटेशन का परिणाम मिलता है। पढ़ें [Slides::TextVerticalType](../textverticaltype/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() override | [ThreeDFormat](../threedformat/) ऑब्जेक्ट लौटाता है जो टेक्स्ट के 3डी इफ़ेक्ट प्रॉपर्टीज़ को दर्शाता है। केवल-पढ़ने योग्य [IThreeDFormat](../ithreedformat/)। |
| [TextShapeType](../textshapetype/) [get_Transform](./get_transform/)() override | टेक्स्ट रैपिंग शैप प्राप्त करता है। पढ़ें [TextShapeType](../textshapetype/)। |
| [NullableBool](../nullablebool/) [get_WrapText](./get_wraptext/)() override | **True** यदि टेक्स्ट [TextFrame](../textframe/) के मार्जिन पर रैप किया गया है। पढ़ें [NullableBool](../nullablebool/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormatEffectiveData](../itextframeformateffectivedata/)\> [GetEffective](./geteffective/)() override | इनहेरिटेंस लागू होते हुए प्रभावी टेक्स्ट फ़्रेम फ़ॉर्मेटिंग डेटा प्राप्त करता है। |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | हैश कोड लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक टाइप प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि ऑब्जेक्ट targetType द्वारा वर्णित टाइप का इंस्टैंस दर्शाता है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉक करने का कार्यान्वयन करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
| [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस द्वारा वैल्यू टाइप ऑब्जेक्ट की nullptr से तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) की स्ट्रिंग और nullptr केस के लिये विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग केस के लिये विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../textanchortype/)) override | एक [TextFrame](../textframe/) में वर्टिकल एंकर टेक्स्ट सेट करता है। लिखें [TextAnchorType](../textanchortype/)। |
| void [set_AutofitType](./set_autofittype/)([TextAutofitType](../textautofittype/)) override | टेक्स्ट का ऑटोफिट मोड सेट करता है। लिखें [TextAutofitType](../textautofittype/)। |
| void [set_CenterText](./set_centertext/)([NullableBool](../nullablebool/)) override | यदि [NullableBool::True](../nullablebool/) तो टेक्स्ट को बॉक्स में क्षैतिज रूप से केंद्रित किया जाना चाहिए। लिखें [NullableBool](../nullablebool/)। |
| void [set_ColumnCount](./set_columncount/)(**int32_t**) override | टेक्स्ट एरिया में कॉलम की संख्या सेट करता है। यह मान एक सकारात्मक संख्या होना चाहिए। अन्यथा, मान शून्य सेट किया जाएगा। मान 0 अनिर्धारित मान दर्शाता है। लिखें **int32_t**। |
| void [set_ColumnSpacing](./set_columnspacing/)(**double**) override | टेक्स्ट एरिया में टेक्स्ट कॉलमों के बीच की दूरी (पॉइंट्स में) सेट करता है। यह केवल तब लागू होना चाहिए जब 1 से अधिक कॉलम मौजूद हों। यह मान एक सकारात्मक संख्या होना चाहिए। अन्यथा, मान शून्य सेट किया जाएगा। लिखें **double**। |
| void [set_KeepTextFlat](./set_keeptextflat/)(**bool**) override | यदि 3-डी रोटेशन इफ़ेक्ट लागू किया गया हो तब भी टेक्स्ट को सपाट रखने की स्थिति सेट करता है। लिखें **bool**। |
| void [set_MarginBottom](./set_marginbottom/)(**double**) override | एक [TextFrame](../textframe/) में नीचे का मार्जिन (पॉइंट्स) सेट करता है। लिखें **double**। |
| void [set_MarginLeft](./set_marginleft/)(**double**) override | एक [TextFrame](../textframe/) में बायाँ मार्जिन (पॉइंट्स) सेट करता है। लिखें **double**। |
| void [set_MarginRight](./set_marginright/)(**double**) override | एक [TextFrame](../textframe/) में दाहिना मार्जिन (पॉइंट्स) सेट करता है। लिखें **double**। |
| void [set_MarginTop](./set_margintop/)(**double**) override | एक [TextFrame](../textframe/) में ऊपर का मार्जिन (पॉइंट्स) सेट करता है। लिखें **double**। |
| void [set_RotationAngle](./set_rotationangle/)(**float**) override | बाउंडिंग बॉक्स के भीतर टेक्स्ट पर लागू होने वाली कस्टम रोटेशन निर्दिष्ट करता है। यदि निर्दिष्ट नहीं किया गया है, तो साथ वाले आकार का रोटेशन उपयोग किया जाता है। यदि निर्दिष्ट किया गया है, तो यह आकार से स्वतंत्र रूप से लागू होता है। अर्थात् आकार पर रोटेशन लागू हो सकता है और टेक्स्ट पर भी अलग से रोटेशन लागू हो सकता है। इस प्रॉपर्टी और प्रॉपर्टी TextVerticalType में परिभाषित वर्टिकल टाइप से संकलित दृश्य टेक्स्ट रोटेशन का परिणाम मिलता है। लिखें **float**। |
| void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) override | टेक्स्ट ओरिएंटेशन निर्धारित करता है। इस प्रॉपर्टी और प्रॉपर्टी RotationAngle में कस्टम एंगल से संकलित दृश्य टेक्स्ट रोटेशन का परिणाम मिलता है। लिखें [Slides::TextVerticalType](../textverticaltype/)। |
| void [set_Transform](./set_transform/)([TextShapeType](../textshapetype/)) override | टेक्स्ट रैपिंग शैप सेट करता है। लिखें [TextShapeType](../textshapetype/)। |
| void [set_WrapText](./set_wraptext/)([NullableBool](../nullablebool/)) override | **True** यदि टेक्स्ट [TextFrame](../textframe/) के मार्जिन पर रैप किया गया है। लिखें [NullableBool](../nullablebool/)। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n-वें टेम्पलेट आर्ग्युमेंट को वीक पॉइंटर (शेयर्ड के बजाय) सेट करता है। कंटेनर में पॉइंटर्स को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| [TextFrameFormat](./textframeformat/)() | [TextFrameFormat](./) वर्ग का नया इंस्टेंस इनिशियलाइज़ करता है। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने का कार्यान्वयन करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## देखें भी

* वर्ग [PVIObject](../pviobject/)
* वर्ग [ITextFrameFormat](../itextframeformat/)
* वर्ग [IChartTextBlockFormat](../../aspose.slides.charts/icharttextblockformat/)
* नामस्थान [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)