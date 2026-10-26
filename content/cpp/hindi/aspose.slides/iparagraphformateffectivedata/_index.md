---
title: IParagraphFormatEffectiveData
second_title: Aspose.Slides for C++ API संदर्भ
description: एक अपरिवर्तनीय वस्तु जो प्रभावी अनुच्छेद स्वरूपण गुणधर्मों को सम्मिलित करती है।
type: docs
weight: 3160
url: /hi/aspose.slides/iparagraphformateffectivedata/
---
## IParagraphFormatEffectiveData वर्ग

अपरिवर्तनीय वस्तु जो प्रभावी अनुच्छेद स्वरूपण गुणधर्मों को सम्मिलित करती है।

```cpp
class IParagraphFormatEffectiveData : public virtual System::Object
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में संदर्भ प्रकार की वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में मान प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() | एक अनुच्छेद में पाठ संरेखण लौटाता है। केवल-पढ़ने-योग्य [TextAlignment](../textalignment/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormatEffectiveData](../ibulletformateffectivedata/)\> [get_Bullet](./get_bullet/)() | एक अनुच्छेद का बुलेट स्वरूप लौटाता है। केवल-पढ़ने-योग्य [IBulletFormatEffectiveData](../ibulletformateffectivedata/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormatEffectiveData](../iportionformateffectivedata/)\> [get_DefaultPortionFormat](./get_defaultportionformat/)() | एक अनुच्छेद का डिफ़ॉल्ट भाग स्वरूप लौटाता है। केवल-पढ़ने-योग्य [IPortionFormatEffectiveData](../iportionformateffectivedata/)। |
| virtual **float** [get_DefaultTabSize](./get_defaulttabsize/)() | डिफ़ॉल्ट टैबुलेशन आकार लौटाता है। केवल-पढ़ने-योग्य **float**। |
| virtual **int16_t** [get_Depth](./get_depth/)() | एक अनुच्छेद की गहराई लौटाता है। केवल-पढ़ने-योग्य **int16_t**। |
| virtual **bool** [get_EastAsianLineBreak](./get_eastasianlinebreak/)() | निर्धारित करता है कि क्या किसी अनुच्छेद में ईस्ट एशियन लाइन ब्रेक का उपयोग किया गया है। केवल-पढ़ने-योग्य **bool**। |
| virtual [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() | एक अनुच्छेद में फ़ॉन्ट संरेखण लौटाता है। केवल-पढ़ने-योग्य [Slides::FontAlignment](../fontalignment/)। |
| virtual **bool** [get_HangingPunctuation](./get_hangingpunctuation/)() | निर्धारित करता है कि क्या किसी अनुच्छेद में हैंगिंग विराम चिह्न का उपयोग किया गया है। केवल-पढ़ने-योग्य **bool**। |
| virtual **float** [get_Indent](./get_indent/)() | अनुच्छेद का प्रथम पंक्ति इंडेंट/हैंगिंग इंडेंट लौटाता है। हैंगिंग इंडेंट को नकारात्मक मानों के साथ परिभाषित किया जा सकता है। केवल-पढ़ने-योग्य **float**। |
| virtual **bool** [get_LatinLineBreak](./get_latinlinebreak/)() | निर्धारित करता है कि क्या किसी अनुच्छेद में लैटिन लाइन ब्रेक का उपयोग किया गया है। केवल-पढ़ने-योग्य **bool**। |
| virtual **float** [get_MarginLeft](./get_marginleft/)() | एक अनुच्छेद में बायाँ मार्जिन लौटाता है। केवल-पढ़ने-योग्य **float**। |
| virtual **float** [get_MarginRight](./get_marginright/)() | एक अनुच्छेद में दायाँ मार्जिन लौटाता है। केवल-पढ़ने-योग्य **float**। |
| virtual **bool** [get_RightToLeft](./get_righttoleft/)() | निर्धारित करता है कि क्या किसी अनुच्छेद में दाएँ-से-बाएँ लेखन का उपयोग किया गया है। केवल-पढ़ने-योग्य **bool**। |
| virtual **float** [get_SpaceAfter](./get_spaceafter/)() | एक अनुच्छेद में अंतिम पंक्ति के बाद स्थान की मात्रा लौटाता है। केवल-पढ़ने-योग्य **float**। |
| virtual **float** [get_SpaceBefore](./get_spacebefore/)() | एक अनुच्छेद में प्रथम पंक्ति से पहले स्थान की मात्रा लौटाता है। केवल-पढ़ने-योग्य **float**। |
| virtual **float** [get_SpaceWithin](./get_spacewithin/)() | एक अनुच्छेद में बेस लाइनों के बीच स्थान की मात्रा लौटाता है। केवल-पढ़ने-योग्य **float**। |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITabEffectiveData](../itabeffectivedata/)\>\> [get_Tabs](./get_tabs/)() | एक अनुच्छेद के टैबुलेशन्स लौटाता है। केवल-पढ़ने-योग्य [ITabEffectiveData](../itabeffectivedata/)[]। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | वस्तु से जुड़े रेफरेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) विधि का अनुरूप। कस्टम वस्तुओं की हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | वस्तु का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का अनुरूप। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि क्या वस्तु targetType द्वारा वर्णित प्रकार का एक उदाहरण है। C# 'is' ऑपरेटर का अनुरूप। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) विधि का अनुरूप। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारम्भ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारम्भ करता है और सबक्लासेज़ की कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारम्भ करता है और सबक्लासेज़ की कॉपी निर्माण को.enabled करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | वस्तुओं की रेफरेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | वस्तुओं की रेफरेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफरेंस द्वारा मान प्रकार की वस्तु की nullptr से तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफरेंस काउंट को घटाता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्युमेंट को एक कमजोर पॉइंटर सेट करता है (साझा की बजाय)। कंटेनरों में पॉइंटर्स को कमजोर मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफरेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफरेंस काउंट को बढ़ाता है। सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफरेंस काउंट को घटाता और लौटाता है। सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) विधि का अनुरूप। कस्टम वस्तुओं को स्ट्रिंग में परिवर्तित करना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) संरचना को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफरेंस काउंट को बढ़ाता है। सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफरेंस काउंट को घटाता है। सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## टिप्पणी

यह इंटरफ़ेस [IParagraphFormat](../iparagraphformat/) इंटरफ़ेस के साथ मिलकर उपयोग किया जाता है ताकि विरासत लागू किए हुए प्रभावी स्वरूपण मान लौटाए जा सकें।

## देखें

* वर्ग [Object](../../system/object/)
* नामस्थान [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)