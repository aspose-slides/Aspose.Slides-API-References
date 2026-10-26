---
title: ParagraphFormat
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: यह वर्ग पैराग्राफ फ़ॉर्मेटिंग गुणों को सम्मिलित करता है। IParagraphFormatEffectiveData के विपरीत, इस वर्ग की सभी गुण लिखने योग्य हैं।
type: docs
weight: 4668
url: /hi/aspose.slides/paragraphformat/
---
## ParagraphFormat क्लास

यह क्लास पैराग्राफ़ फ़ॉर्मेटिंग प्रॉपर्टीज़ को शामिल करती है। [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/) के विपरीत, इस क्लास की सभी प्रॉपर्टीज़ लिखने योग्य हैं।

```cpp
class ParagraphFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::IParagraphFormat,
                        public Aspose::Slides::Charts::IChartParagraphFormat
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | निर्दिष्ट ऑब्जेक्ट के साथ तुलना करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-स्टाइल फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-स्टाइल फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() override | पैराग्राफ में बिना विरासत के टेक्स्ट एलाइनमेंट लौटाता है। पढ़ें [TextAlignment](../textalignment/)। |
| **float** [get_DefaultTabSize](./get_defaulttabsize/)() override | पैराग्राफ में बिना विरासत के डिफ़ॉल्ट टैबुलेशन आकार लौटाता है। पढ़ें **float**। |
| [NullableBool](../nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() override | निर्धारित करता है कि क्या पैराग्राफ में ईस्ट एशियन लाइन ब्रेक उपयोग किया गया है। कोई विरासत नहीं लागू। पढ़ें [NullableBool](../nullablebool/)। |
| [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() override | पैराग्राफ में बिना विरासत के फ़ॉन्ट एलाइनमेंट लौटाता है। पढ़ें [Slides::FontAlignment](../fontalignment/)। |
| [NullableBool](../nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() override | निर्धारित करता है कि पैराग्राफ में हैंगिंग पंक्चुएशन उपयोग किया गया है। कोई विरासत नहीं लागू। पढ़ें [NullableBool](../nullablebool/)। |
| **float** [get_Indent](./get_indent/)() override | पैराग्राफ फर्स्ट लाइन इंडेंट/हैंगिंग इंडेंट बिना विरासत के लौटाता है। हैंगिंग इंडेंट नकारात्मक मानों से परिभाषित किया जा सकता है। पढ़ें **float**। |
| [NullableBool](../nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() override | निर्धारित करता है कि पैराग्राफ में लैटिन लाइन ब्रेक उपयोग किया गया है। कोई विरासत नहीं लागू। पढ़ें [NullableBool](../nullablebool/)। |
| **float** [get_MarginLeft](./get_marginleft/)() override | पैराग्राफ में बिना विरासत के बाएँ मार्जिन लौटाता है। पढ़ें **float**। |
| **float** [get_MarginRight](./get_marginright/)() override | पैराग्राफ में बिना विरासत के दाएँ मार्जिन लौटाता है। पढ़ें **float**। |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पढ़ने-योग्य [IDOMObject](../idomobject/)। |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | पैरेंट [IPresentationComponent](../ipresentationcomponent/) लौटाता है। केवल-पढ़ने-योग्य [IPresentationComponent](../ipresentationcomponent/)। |
| [NullableBool](../nullablebool/) [get_RightToLeft](./get_righttoleft/)() override | निर्धारित करता है कि पैराग्राफ में राइट-टू-लेफ़्ट लेखन उपयोग किया गया है। कोई विरासत नहीं लागू। पढ़ें [NullableBool](../nullablebool/)। |
| **float** [get_SpaceAfter](./get_spaceafter/)() override | पैराग्राफ में अंतिम लाइन के बाद का स्पेस लौटाता है। सकारात्मक मान फ़ॉन्ट आकार के प्रतिशत को दर्शाता है; नकारात्मक मान पॉइंट आकार में स्पेस को दर्शाता है। पढ़ें **float**। |
| **float** [get_SpaceBefore](./get_spacebefore/)() override | पैराग्राफ में पहली लाइन से पहले का स्पेस लौटाता है। सकारात्मक मान फ़ॉन्ट आकार के प्रतिशत को दर्शाता है; नकारात्मक मान पॉइंट आकार में स्पेस को दर्शाता है। पढ़ें **float**। |
| **float** [get_SpaceWithin](./get_spacewithin/)() override | पैराग्राफ में बेस लाइनों के बीच का स्पेस लौटाता है। सकारात्मक मान प्रतिशत, नकारात्मक मान पॉइंट में। कोई विरासत नहीं लागू। पढ़ें **float**। |
| [System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\> [get_Tab](./get_tab/)(**int32_t**) override | निर्दिष्ट इंडेक्स पर पैराग्राफ की टैबुलेशन लौटाता है। कोई विरासत नहीं लागू। केवल-पढ़ने-योग्य [Aspose::Slides::ITab](../itab/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../itabcollection/)\> [get_Tabs](./get_tabs/)() override | पैराग्राफ की टैबुलेशन लौटाता है। कोई विरासत नहीं लागू। केवल-पढ़ने-योग्य [ITabCollection](../itabcollection/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)\> [GetEffective](./geteffective/)() override | विरासत लागू होकर प्रभावी पैराग्राफ फ़ॉर्मेटिंग डेटा प्राप्त करता है। |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | हैश कोड लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक टाइप प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि ऑब्जेक्ट targetType द्वारा वर्णित टाइप का इंस्टेंस है या नहीं। C# ‘is’ ऑपरेटर का समकक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉक करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का प्रयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
|  [ParagraphFormat](./paragraphformat/)() | [ParagraphFormat](./) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट को nullptr के साथ रेफ़रेंस-कम्पेयर करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा शेयरड रेफ़रेंस काउंटर घटाता है। |
| void [set_Alignment](./set_alignment/)([TextAlignment](../textalignment/)) override | पैराग्राफ में बिना विरासत के टेक्स्ट एलाइनमेंट सेट करता है। लिखें [TextAlignment](../textalignment/)। |
| void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) override | पैराग्राफ में बिना विरासत के डिफ़ॉल्ट टैबुलेशन आकार सेट करता है। लिखें **float**। |
| void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../nullablebool/)) override | निर्धारित करता है कि पैराग्राफ में ईस्ट एशियन लाइन ब्रेक उपयोग किया गया है। कोई विरासत नहीं लागू। लिखें [NullableBool](../nullablebool/)। |
| void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../fontalignment/)) override | पैराग्राफ में बिना विरासत के फ़ॉन्ट एलाइनमेंट सेट करता है। लिखें [Slides::FontAlignment](../fontalignment/)। |
| void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../nullablebool/)) override | निर्धारित करता है कि पैराग्राफ में हैंगिंग पंक्चुएशन उपयोग किया गया है। कोई विरासत नहीं लागू। लिखें [NullableBool](../nullablebool/)। |
| void [set_Indent](./set_indent/)(**float**) override | पैराग्राफ फर्स्ट लाइन इंडेंट/हैंगिंग इंडेंट बिना विरासत के सेट करता है। हैंगिंग इंडेंट नकारात्म मानों से परिभाषित किया जा सकता है। लिखें **float**। |
| void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../nullablebool/)) override | निर्धारित करता है कि पैराग्राफ में लैटिन लाइन ब्रेक उपयोग किया गया है। कोई विरासत नहीं लागू। लिखें [NullableBool](../nullablebool/)। |
| void [set_MarginLeft](./set_marginleft/)(**float**) override | पैराग्राफ में बिना विरासत के बाएँ मार्जिन सेट करता है। लिखें **float**। |
| void [set_MarginRight](./set_marginright/)(**float**) override | पैराग्राफ में बिना विरासत के दाएँ मार्जिन सेट करता है। लिखें **float**। |
| void [set_RightToLeft](./set_righttoleft/)([NullableBool](../nullablebool/)) override | निर्धारित करता है कि पैराग्राफ में राइट-टू-लेफ़्ट लेखन उपयोग किया गया है। कोई विरासत नहीं लागू। लिखें [NullableBool](../nullablebool/)। |
| void [set_SpaceAfter](./set_spaceafter/)(**float**) override | पैराग्राफ में अंतिम लाइन के बाद का स्पेस बिना विरासत के सेट करता है। सकारात्मक मान फ़ॉन्ट आकार के प्रतिशत को दर्शाता है; नकारात्मक मान पॉइंट आकार में स्पेस को दर्शाता है। लिखें **float**। |
| void [set_SpaceBefore](./set_spacebefore/)(**float**) override | पैराग्राफ में पहली लाइन से पहले का स्पेस बिना विरासत के सेट करता है। सकारात्मक मान फ़ॉन्ट आकार के प्रतिशत को दर्शाता है; नकारात्मक मान पॉइंट आकार में स्पेस को दर्शाता है। लिखें **float**। |
| void [set_SpaceWithin](./set_spacewithin/)(**float**) override | पैराग्राफ में बेस लाइनों के बीच का स्पेस बिना विरासत के सेट करता है। सकारात्मक मान प्रतिशत, नकारात्मक मान पॉइंट में। लिखें **float**। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्युमेंट को कमजोर पॉइंटर (शेर्ड के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को कमजोर मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | वर्तमान शेयरड रेफ़रेंस काउंटर मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | शेयरड रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector प्रयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | शेयरड रेफ़रेंस काउंटर घटाता और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector प्रयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का प्रयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector प्रयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector प्रयोग करें। |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर मुक्त करता है। |
## टिप्पणी

यह क्लास विशेष पैराग्राफ़ के लिए परिभाषित पैराग्राफ़ फ़ॉर्मेटिंग प्रॉपर्टीज़ को लौटाने और संशोधित करने के लिए उपयोग की जाती है। इसका अर्थ है कि मान प्राप्त करते समय कोई विरासत लागू नहीं होती, इसलिए अधिकांश मामलों में आपको "undefined" अर्थ वाले मान मिलेंगे।

इनहेरिटेड मानों सहित प्रभावी फ़ॉर्मेटिंग पैरामीटर मान प्राप्त करने के लिए आपको [ParagraphFormat::GetEffective](./geteffective/) मेथड का उपयोग करना होगा जो एक [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/) इंस्टेंस लौटाता है।

## देखें

* क्लास [PVIObject](../pviobject/)
* क्लास [IParagraphFormat](../iparagraphformat/)
* क्लास [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat/)
* नेमस्पेस [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)