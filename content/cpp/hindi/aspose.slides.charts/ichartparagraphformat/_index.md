---
title: IChartParagraphFormat
second_title: Aspose.Slides for C++ API संदर्भ
description: चार्ट के पैराग्राफ फ़ॉर्मेटिंग गुणों का प्रतिनिधित्व करता है।
type: docs
weight: 781
url: /hi/aspose.slides.charts/ichartparagraphformat/
---
## IChartParagraphFormat क्लास

Represents a paragraph formatting properties of a chart.

```cpp
class IChartParagraphFormat : public virtual System::Object
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| virtual [TextAlignment](../../aspose.slides/textalignment/) [get_Alignment](./get_alignment/)() | एक पैराग्राफ में टेक्स्ट संरेखन लौटाता है। पढ़ें [TextAlignment](../../aspose.slides/textalignment/)। |
| virtual **float** [get_DefaultTabSize](./get_defaulttabsize/)() | डिफ़ॉल्ट टैब्यूलेशन आकार लौटाता है। पढ़ें **float**। |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() | निर्धारित करता है कि क्या एक पैराग्राफ में ईस्ट एशियन लाइन ब्रेक उपयोग किया जाता है। पढ़ें [NullableBool](../../aspose.slides/nullablebool/)। |
| virtual [Aspose::Slides::FontAlignment](../../aspose.slides/fontalignment/) [get_FontAlignment](./get_fontalignment/)() | एक पैराग्राफ में फ़ॉन्ट संरेखन लौटाता है। पढ़ें [Slides::FontAlignment](../../aspose.slides/fontalignment/)। |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() | निर्धारित करता है कि क्या एक पैराग्राफ में हैंगिंग पंक्चुएशन उपयोग किया जाता है। पढ़ें [NullableBool](../../aspose.slides/nullablebool/)। |
| virtual **float** [get_Indent](./get_indent/)() | पैराग्राफ का प्रथम पंक्ति इंडेंट/हैंगिंग इंडेंट लौटाता है। हैंगिंग इंडेंट नकारात्मक मानों से निर्धारित किया जा सकता है। पढ़ें **float**। |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() | निर्धारित करता है कि क्या एक पैराग्राफ में लैटिन लाइन ब्रेक उपयोग किया जाता है। पढ़ें [NullableBool](../../aspose.slides/nullablebool/)। |
| virtual **float** [get_MarginLeft](./get_marginleft/)() | पैराग्राफ में बायाँ मार्जिन लौटाता है। पढ़ें **float**। |
| virtual **float** [get_MarginRight](./get_marginright/)() | पैराग्राफ में दायाँ मार्जिन लौटाता है। पढ़ें **float**। |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_RightToLeft](./get_righttoleft/)() | निर्धारित करता है कि क्या एक पैराग्राफ में राइट-टु-लेफ्ट लेखन इस्तेमाल होता है। पढ़ें [NullableBool](../../aspose.slides/nullablebool/)। |
| virtual **float** [get_SpaceAfter](./get_spaceafter/)() | पैराग्राफ में अंतिम पंक्ति के बाद के स्पेस की मात्रा लौटाता है। पढ़ें **float**। |
| virtual **float** [get_SpaceBefore](./get_spacebefore/)() | पैराग्राफ में पहली पंक्ति से पहले स्पेस की मात्रा लौटाता है। पढ़ें **float**। |
| virtual **float** [get_SpaceWithin](./get_spacewithin/)() | पैराग्राफ में बेस लाइनों के बीच के स्पेस की मात्रा लौटाता है। पढ़ें **float**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITab](../../aspose.slides/itab/)\> [get_Tab](./get_tab/)(**int32_t**) | निर्दिष्ट इंडेक्स पर पैराग्राफ का टैब्यूलेशन लौटाता है। केवल पढ़ने योग्य [Aspose::Slides::ITab](../../aspose.slides/itab/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../../aspose.slides/itabcollection/)\> [get_Tabs](./get_tabs/)() | पैराग्राफ के टैब्यूलेशन लौटाता है। केवल पढ़ने योग्य [ITabCollection](../../aspose.slides/itabcollection/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानार्थी। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार के इंस्टेंस का प्रतिनिधित्व करता है या नहीं। C# 'is' ऑपरेटर का समानार्थी। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट के लॉकिंग को कार्यान्वित करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानार्थी। कस्टम टाइप्स की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सब क्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सब क्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण स्ट्रिंग और nullptr के मामले के लिए। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण स्ट्रिंग्स के मामले के लिए। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [set_Alignment](./set_alignment/)([TextAlignment](../../aspose.slides/textalignment/)) | एक पैराग्राफ में टेक्स्ट संरेखन सेट करता है। लिखें [TextAlignment](../../aspose.slides/textalignment/)। |
| virtual void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) | डिफ़ॉल्ट टैब्यूलेशन आकार सेट करता है। लिखें **float**। |
| virtual void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../../aspose.slides/nullablebool/)) | निर्धारित करता है कि क्या एक पैराग्राफ में ईस्ट एशियन लाइन ब्रेक उपयोग किया जाता है। लिखें [NullableBool](../../aspose.slides/nullablebool/)। |
| virtual void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../../aspose.slides/fontalignment/)) | एक पैराग्राफ में फ़ॉन्ट संरेखन सेट करता है। लिखें [Slides::FontAlignment](../../aspose.slides/fontalignment/)। |
| virtual void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../../aspose.slides/nullablebool/)) | निर्धारित करता है कि क्या एक पैराग्राफ में हैंगिंग पंक्चुएशन उपयोग किया जाता है। लिखें [NullableBool](../../aspose.slides/nullablebool/)। |
| virtual void [set_Indent](./set_indent/)(**float**) | पैराग्राफ का प्रथम पंक्ति इंडेंट/हैंगिंग इंडेंट सेट करता है। हैंगिंग इंडेंट नकारात्मक मानों से निर्धारित किया जा सकता है। लिखें **float**। |
| virtual void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../../aspose.slides/nullablebool/)) | निर्धारित करता है कि क्या एक पैराग्राफ में लैटिन लाइन ब्रेक उपयोग किया जाता है। लिखें [NullableBool](../../aspose.slides/nullablebool/)। |
| virtual void [set_MarginLeft](./set_marginleft/)(**float**) | पैराग्राफ में बायाँ मार्जिन सेट करता है। लिखें **float**। |
| virtual void [set_MarginRight](./set_marginright/)(**float**) | पैराग्राफ में दायाँ मार्जिन सेट करता है। लिखें **float**। |
| virtual void [set_RightToLeft](./set_righttoleft/)([NullableBool](../../aspose.slides/nullablebool/)) | निर्धारित करता है कि क्या एक पैराग्राफ में राइट-टु-लेफ्ट लेखन उपयोग किया है। लिखें [NullableBool](../../aspose.slides/nullablebool/)। |
| virtual void [set_SpaceAfter](./set_spaceafter/)(**float**) | पैराग्राफ में अंतिम पंक्ति के बाद के स्पेस की मात्रा सेट करता है। लिखें **float**। |
| virtual void [set_SpaceBefore](./set_spacebefore/)(**float**) | पैराग्राफ में पहली पंक्ति से पहले स्पेस की मात्रा सेट करता है। लिखें **float**। |
| virtual void [set_SpaceWithin](./set_spacewithin/)(**float**) | पैराग्राफ में बेस लाइनों के बीच के स्पेस की मात्रा सेट करता है। लिखें **float**। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्यूमेंट को एक वीक पॉइंटर (शेयरड के बजाय) सेट करता है। कंटेनर्स में पॉइंटर्स को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | शेयरड रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | शेयरड रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | शेयरड रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को कार्यान्वित करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट के अनलॉकिंग को कार्यान्वित करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## संबंधित

* क्लास [Object](../../system/object/)
* नेमस्पेस [Aspose::Slides::Charts](../)
* लाइब्रेरी [Aspose.Slides](../../)