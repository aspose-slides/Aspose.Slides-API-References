---
title: IChartTextBlockFormat
second_title: Aspose.Slides for C++ API संदर्भ
description: चार्ट टेक्स्ट तत्वों के लिए फ़ॉर्मेटिंग विशेषताएँ दर्शाता है।
type: docs
weight: 885
url: /hi/aspose.slides.charts/icharttextblockformat/
---
## IChartTextBlockFormat क्लास

चार्ट टेक्स्ट तत्वों के लिए फ़ॉर्मैटिंग प्रॉपर्टी को दर्शाता है।

```cpp
class IChartTextBlockFormat : public virtual System::Object
```

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantics का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-स्टाइल फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-स्टाइल फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual [TextAnchorType](../../aspose.slides/textanchortype/) [get_AnchoringType](./get_anchoringtype/)() | एक [TextFrame](../../aspose.slides/textframe/) में वर्टिकल एंकर टेक्स्ट लौटाता है। पढ़ें [TextAnchorType](../../aspose.slides/textanchortype/)। |
| virtual [TextAutofitType](../../aspose.slides/textautofittype/) [get_AutofitType](./get_autofittype/)() | टेक्स्ट के autofit मोड को लौटाता है। इस प्रॉपर्टी को बदलने से केवल इन चार्ट भागों पर विशेष प्रभाव पड़ सकता है: [DataLabel](../datalabel/) और [DataLabelFormat](../datalabelformat/) (PowerPoint 2013 में पूर्ण समर्थन; PowerPoint 2007 में रेंडरिंग के लिए कोई प्रभाव नहीं)। पढ़ें [TextAutofitType](../../aspose.slides/textautofittype/)। |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_CenterText](./get_centertext/)() | यदि [NullableBool::True](../../aspose.slides/nullablebool/) तो टेक्स्ट बॉक्स में क्षैतिज रूप से केंद्रित होना चाहिए। पढ़ें [NullableBool](../../aspose.slides/nullablebool/)। |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | एक [TextFrame](../../aspose.slides/textframe/) में नीचे का मार्जिन (पॉइंट) लौटाता है। इस प्रॉपर्टी को बदलने से केवल इन चार्ट भागों पर विशेष प्रभाव पड़ सकता है: [DataLabel](../datalabel/) और [DataLabelFormat](../datalabelformat/) (PowerPoint 2013 में पूर्ण समर्थन; PowerPoint 2007 में रेंडरिंग के लिए कोई प्रभाव नहीं)। पढ़ें **double**। |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | एक [TextFrame](../../aspose.slides/textframe/) में बाएं मार्जिन (पॉइंट) लौटाता है। इस प्रॉपर्टी को बदलने से केवल इन चार्ट भागों पर विशेष प्रभाव पड़ सकता है: [DataLabel](../datalabel/) और [DataLabelFormat](../datalabelformat/) (PowerPoint 2013 में पूर्ण समर्थन; PowerPoint 2007 में रेंडरिंग के लिए कोई प्रभाव नहीं)। पढ़ें **double**। |
| virtual **double** [get_MarginRight](./get_marginright/)() | एक [TextFrame](../../aspose.slides/textframe/) में दायें मार्जिन (पॉइंट) लौटाता है। इस प्रॉपर्टी को बदलने से केवल इन चार्ट भागों पर विशेष प्रभाव पड़ सकता है: [DataLabel](../datalabel/) और [DataLabelFormat](../datalabelformat/) (PowerPoint 2013 में पूर्ण समर्थन; PowerPoint 2007 में रेंडरिंग के लिए कोई प्रभाव नहीं)। पढ़ें **double**। |
| virtual **double** [get_MarginTop](./get_margintop/)() | एक [TextFrame](../../aspose.slides/textframe/) में ऊपर का मार्जिन (पॉइंट) लौटाता है। इस प्रॉपर्टी को बदलने से केवल इन चार्ट भागों पर विशेष प्रभाव पड़ सकता है: [DataLabel](../datalabel/) और [DataLabelFormat](../datalabelformat/) (PowerPoint 2013 में पूर्ण समर्थन; PowerPoint 2007 में रेंडरिंग के लिए कोई प्रभाव नहीं)। पढ़ें **double**। |
| virtual **float** [get_RotationAngle](./get_rotationangle/)() | बाउंडिंग बॉक्स के भीतर टेक्स्ट पर लागू कस्टम रोटेशन को निर्दिष्ट करता है। यदि निर्दिष्ट नहीं किया गया है, तो साथ वाले shape की रोटेशन उपयोग होती है। यदि निर्दिष्ट है, तो यह shape से स्वतंत्र रूप से लागू होता है। अर्थात् shape में रोटेशन के साथ टेक्स्ट में भी रोटेशन हो सकता है। इस प्रॉपर्टी और प्री-डिफाइन्ड वर्टिकल टाइप TextVerticalType से मिलकर विज़ुअल टेक्स्ट रोटेशन का परिणाम स्वरूप मान बनता है। पढ़ें **float**। |
| virtual [Aspose::Slides::TextVerticalType](../../aspose.slides/textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | टेक्स्ट उन्मुखीकरण निर्धारित करता है। इस प्रॉपर्टी और RotationAngle प्रॉपर्टी के कस्टम एंगल से मिलकर विज़ुअल टेक्स्ट रोटेशन का परिणाम बनता है। पढ़ें [Slides::TextVerticalType](../../aspose.slides/textverticaltype/)। |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_WrapText](./get_wraptext/)() | **True** यदि टेक्स्ट [TextFrame](../../aspose.slides/textframe/) के मार्जिन पर रैप किया गया है। इस प्रॉपर्टी को बदलने से केवल इन चार्ट भागों पर विशेष प्रभाव पड़ सकता है: [DataLabel](../datalabel/) और [DataLabelFormat](../datalabelformat/) (PowerPoint 2007/2013 में पूर्ण समर्थन)। पढ़ें [NullableBool](../../aspose.slides/nullablebool/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स की हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr से रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का स्पेशलाइजेशन। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स के केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का स्पेशलाइजेशन। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../../aspose.slides/textanchortype/)) | एक [TextFrame](../../aspose.slides/textframe/) में वर्टिकल एंकर टेक्स्ट सेट करता है। लिखें [TextAnchorType](../../aspose.slides/textanchortype/)। |
| virtual void [set_AutofitType](./set_autofittype/)([TextAutofitType](../../aspose.slides/textautofittype/)) | टेक्स्ट के autofit मोड को सेट करता है। इस प्रॉपर्टी को बदलने से केवल इन चार्ट भागों पर विशेष प्रभाव पड़ सकता है: [DataLabel](../datalabel/) और [DataLabelFormat](../datalabelformat/) (PowerPoint 2013 में पूर्ण समर्थन; PowerPoint 2007 में रेंडरिंग के लिए कोई प्रभाव नहीं)। लिखें [TextAutofitType](../../aspose.slides/textautofittype/)। |
| virtual void [set_CenterText](./set_centertext/)([NullableBool](../../aspose.slides/nullablebool/)) | यदि [NullableBool::True](../../aspose.slides/nullablebool/) तो टेक्स्ट बॉक्स में क्षैतिज रूप से केंद्रित होना चाहिए। लिखें [NullableBool](../../aspose.slides/nullablebool/)। |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | एक [TextFrame](../../aspose.slides/textframe/) में नीचे का मार्जिन (पॉइंट) सेट करता है। इस प्रॉपर्टी को बदलने से केवल इन चार्ट भागों पर विशेष प्रभाव पड़ सकता है: [DataLabel](../datalabel/) और [DataLabelFormat](../datalabelformat/) (PowerPoint 2013 में पूर्ण समर्थन; PowerPoint 2007 में रेंडरिंग के लिए कोई प्रभाव नहीं)। लिखें **double**। |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | एक [TextFrame](../../aspose.slides/textframe/) में बाएं मार्जिन (पॉइंट) सेट करता है। इस प्रॉपर्टी को बदलने से केवल इन चार्ट भागों पर विशेष प्रभाव पड़ सकता है: [DataLabel](../datalabel/) और [DataLabelFormat](../datalabelformat/) (PowerPoint 2013 में पूर्ण समर्थन; PowerPoint 2007 में रेंडरिंग के लिए कोई प्रभाव नहीं)। लिखें **double**। |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | एक [TextFrame](../../aspose.slides/textframe/) में दायें मार्जिन (पॉइंट) सेट करता है। इस प्रॉपर्टी को बदलने से केवल इन चार्ट भागों पर विशेष प्रभाव पड़ सकता है: [DataLabel](../datalabel/) और [DataLabelFormat](../datalabelformat/) (PowerPoint 2013 में पूर्ण समर्थन; PowerPoint 2007 में रेंडरिंग के लिए कोई प्रभाव नहीं)। लिखें **double**। |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | एक [TextFrame](../../aspose.slides/textframe/) में ऊपर का मार्जिन (पॉइंट) सेट करता है। इस प्रॉपर्टी को बदलने से केवल इन चार्ट भागों पर विशेष प्रभाव पड़ सकता है: [DataLabel](../datalabel/) और [DataLabelFormat](../datalabelformat/) (PowerPoint 2013 में पूर्ण समर्थन; PowerPoint 2007 में रेंडरिंग के लिए कोई प्रभाव नहीं)। लिखें **double**। |
| virtual void [set_RotationAngle](./set_rotationangle/)(**float**) | बाउंडिंग बॉक्स के भीतर टेक्स्ट पर लागू कस्टम रोटेशन को निर्दिष्ट करता है। यदि निर्दिष्ट नहीं किया गया है, तो साथ वाले shape की रोटेशन उपयोग होती है। यदि निर्दिष्ट है, तो यह shape से स्वतंत्र रूप से लागू होता है। अर्थात् shape में रोटेशन के साथ टेक्स्ट में भी रोटेशन हो सकता है। इस प्रॉपर्टी और प्री-डिफाइन्ड वर्टिकल टाइप TextVerticalType से मिलकर विज़ुअल टेक्स्ट रोटेशन का परिणाम स्वरूप मान बनता है। लिखें **float**। |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../../aspose.slides/textverticaltype/)) | टेक्स्ट उन्मुखीकरण निर्धारित करता है। इस प्रॉपर्टी और RotationAngle प्रॉपर्टी के कस्टम एंगल से मिलकर विज़ुअल टेक्स्ट रोटेशन का परिणाम बनता है। लिखें [Slides::TextVerticalType](../../aspose.slides/textverticaltype/)। |
| virtual void [set_WrapText](./set_wraptext/)([NullableBool](../../aspose.slides/nullablebool/)) | **True** यदि टेक्स्ट [TextFrame](../../aspose.slides/textframe/) के मार्जिन पर रैप किया गया है। इस प्रॉपर्टी को बदलने से केवल इन चार्ट भागों पर विशेष प्रभाव पड़ सकता है: [DataLabel](../datalabel/) और [DataLabelFormat](../datalabelformat/) (PowerPoint 2007/2013 में पूर्ण समर्थन)। लिखें [NullableBool](../../aspose.slides/nullablebool/)। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्यूमेंट को कमजोर पॉइंटर सेट करता है (shared के बजाय)। कंटेनरों में पॉइंटर्स को कमजोर मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## संबंधित देखें

* क्लास [Object](../../system/object/)
* नेमस्पेस [Aspose::Slides::Charts](../)
* लाइब्रेरी [Aspose.Slides](../../)