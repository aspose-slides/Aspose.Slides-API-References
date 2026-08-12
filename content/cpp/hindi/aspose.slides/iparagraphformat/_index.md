---
title: IParagraphFormat
second_title: Aspose.Slides for C++ API संदर्भ
description: यह क्लास पैराग्राफ फ़ॉर्मेटिंग गुणों को सम्मिलित करती है। IParagraphFormatEffectiveData के विपरीत, इस क्लास की सभी गुण लेखनीय हैं।
type: docs
weight: 3147
url: /hi/aspose.slides/iparagraphformat/
---
## IParagraphFormat क्लास


यह क्लास पैराग्राफ फ़ॉर्मेटिंग गुणों को सम्मिलित करती है। [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/) के विपरीत, इस क्लास की सभी गुण लेखनीय हैं।

```cpp
class IParagraphFormat : public virtual System::Object
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार की वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() | कोई वंशानुगतता लागू हुए बिना एक पैराग्राफ में टेक्स्ट संरेखण लौटाता है। पढ़ें [TextAlignment](../textalignment/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormat](../ibulletformat/)\> [get_Bullet](./get_bullet/)() | पैराग्राफ का बुलेट फॉर्मेट लौटाता है। केवल पढ़ने योग्य [IBulletFormat](../ibulletformat/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\> [get_DefaultPortionFormat](./get_defaultportionformat/)() | पैराग्राफ का डिफ़ॉल्ट भाग फॉर्मेट लौटाता है। कोई वंशानुगतता लागू नहीं। केवल पढ़ने योग्य [IPortionFormat](../iportionformat/)। |
| virtual **float** [get_DefaultTabSize](./get_defaulttabsize/)() | कोई वंशानुगतता लागू हुए बिना डिफ़ॉल्ट टैबुलेशन आकार लौटाता है। पढ़ें **float**। |
| virtual **int16_t** [get_Depth](./get_depth/)() | पैराग्राफ की गहराई लौटाता है। मान 0 का मतलब अपरिभाषित मान है। पढ़ें **int16_t**। |
| virtual [NullableBool](../nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() | निर्धारित करता है कि क्या पैराग्राफ में ईस्ट एशियन लाइन ब्रेक उपयोग किया जाता है। कोई वंशानुगतता लागू नहीं। पढ़ें [NullableBool](../nullablebool/)। |
| virtual [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() | कोई वंशानुगतता लागू हुए नहीं पैराग्राफ में फ़ॉन्ट संरेखण लौटाता है। पढ़ें [Slides::FontAlignment](../fontalignment/)। |
| virtual [NullableBool](../nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() | निर्धारित करता है कि क्या पैराग्राफ में हैंगिंग पंचुएशन उपयोग किया जाता है। कोई वंशानुगतता लागू नहीं। पढ़ें [NullableBool](../nullablebool/)। |
| virtual **float** [get_Indent](./get_indent/)() | कोई वंशानुगतता लागू हुए बिना पैराग्राफ का पहला लाइन इंडेंट/हैंगिंग इंडेंट लौटाता है। हैंगिंग इंडेंट को नकारात्मक मानों से परिभाषित किया जा सकता है। पढ़ें **float**। |
| virtual [NullableBool](../nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() | निर्धारित करता है कि क्या पैराग्राफ में लैटिन लाइन ब्रेक उपयोग किया जाता है। कोई वंशानुगतता लागू नहीं। पढ़ें [NullableBool](../nullablebool/)। |
| virtual **float** [get_MarginLeft](./get_marginleft/)() | कोई वंशानुगतता लागू हुए बिना पैराग्राफ का बायाँ मार्जिन लौटाता है। पढ़ें **float**। |
| virtual **float** [get_MarginRight](./get_marginright/)() | कोई वंशानुगतता लागू हुए बिना पैराग्राफ का दायाँ मार्जिन लौटाता है। पढ़ें **float**। |
| virtual [NullableBool](../nullablebool/) [get_RightToLeft](./get_righttoleft/)() | निर्धारित करता है कि क्या पैराग्राफ में दाएँ-से-बाएँ लेखन प्रयोग किया जाता है। कोई वंशानुगतता लागू नहीं। पढ़ें [NullableBool](../nullablebool/)। |
| virtual **float** [get_SpaceAfter](./get_spaceafter/)() | कोई वंशानुगतता लागू हुए बिना पैराग्राफ की अंतिम पंक्ति के बाद स्थान की मात्रा लौटाता है। एक सकारात्मक मान सफेद स्थान का फ़ॉन्ट आकार का प्रतिशत निर्दिष्ट करता है। एक नकारात्मक मान सफेद स्थान का आकार बिंदु आकार में निर्दिष्ट करता है। पढ़ें **float**। |
| virtual **float** [get_SpaceBefore](./get_spacebefore/)() | कोई वंशानुगतता लागू हुए बिना पैराग्राफ की पहली पंक्ति से पहले स्थान की मात्रा लौटाता है। एक सकारात्मक मान सफेद स्थान का फ़ॉन्ट आकार का प्रतिशत निर्दिष्ट करता है। एक नकारात्मक मान सफेद स्थान का आकार बिंदु आकार में निर्दिष्ट करता है। पढ़ें **float**। |
| virtual **float** [get_SpaceWithin](./get_spacewithin/)() | पैराग्राफ में बेस लाइनों के बीच का स्थान लौटाता है। सकारात्मक मान प्रतिशत को दर्शाता है, नकारात्मक - बिंदुओं में आकार। कोई वंशानुगतता लागू नहीं। पढ़ें **float**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\> [get_Tab](./get_tab/)(**int32_t**) | निर्दिष्ट इंडेक्स पर पैराग्राफ की टैबुलेशन लौटाता है। कोई वंशानुगतता लागू नहीं। केवल पढ़ने योग्य [Aspose::Slides::ITab](../itab/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../itabcollection/)\> [get_Tabs](./get_tabs/)() | पैराग्राफ की टैबुलेशन लौटाता है। कोई वंशानुगतता लागू नहीं। केवल पढ़ने योग्य [ITabCollection](../itabcollection/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)\> [GetEffective](./geteffective/)() | विरासत लागू हुए प्रभावी पैराग्राफ फ़ॉर्मेटिंग डेटा प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) विधि का समतुल्य। कस्टम ऑब्जेक्ट्स की हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समतुल्य। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक उदाहरण है या नहीं। C# 'is' ऑपरेटर का समतुल्य। |
| void [Lock](../../system/object/lock/)() | C# lock() कथन की लॉकिंग लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) विधि का समतुल्य। कस्टम प्रकारों को क्लोन करने को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को आरंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट आरंभ करता है और सबक्लास की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट आरंभ करता है और सबक्लास की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू प्रकार की ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट घटाता है। |
| virtual void [set_Alignment](./set_alignment/)([TextAlignment](../textalignment/)) | कोई वंशानुगतता लागू हुए बिना पैराग्राफ में टेक्स्ट संरेखण सेट करता है। लिखें [TextAlignment](../textalignment/)। |
| virtual void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) | कोई वंशानुगतता लागू हुए बिना डिफ़ॉल्ट टैबुलेशन आकार सेट करता है। लिखें **float**। |
| virtual void [set_Depth](./set_depth/)(**int16_t**) | पैराग्राफ की गहराई सेट करता है। मान 0 का मतलब अपरिभाषित मान है। लिखें **int16_t**। |
| virtual void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../nullablebool/)) | निर्धारित करता है कि क्या पैराग्राफ में ईस्ट एशियन लाइन ब्रेक उपयोग किया जाता है। कोई वंशानुगतता लागू नहीं। लिखें [NullableBool](../nullablebool/)। |
| virtual void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../fontalignment/)) | कोई वंशानुगतता लागू हुए बिना पैराग्राफ में फ़ॉन्ट संरेखण सेट करता है। लिखें [Slides::FontAlignment](../fontalignment/)। |
| virtual void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../nullablebool/)) | निर्धारित करता है कि क्या पैराग्राफ में हैंगिंग पंचुएशन उपयोग किया जाता है। कोई वंशानुगतता लागू नहीं। लिखें [NullableBool](../nullablebool/)। |
| virtual void [set_Indent](./set_indent/)(**float**) | कोई वंशानुगतता लागू हुए बिना पैराग्राफ का पहला लाइन इंडेंट/हैंगिंग इंडेंट सेट करता है। हैंगिंग इंडेंट को नकारात्मक मानों से परिभाषित किया जा सकता है। लिखें **float**। |
| virtual void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../nullablebool/)) | निर्धारित करता है कि क्या पैराग्राफ में लैटिन लाइन ब्रेक उपयोग किया जाता है। कोई वंशानुगतता लागू नहीं। लिखें [NullableBool](../nullablebool/)। |
| virtual void [set_MarginLeft](./set_marginleft/)(**float**) | कोई वंशानुगतता लागू हुए बिना पैराग्राफ का बायाँ मार्जिन सेट करता है। लिखें **float**। |
| virtual void [set_MarginRight](./set_marginright/)(**float**) | कोई वंशानुगतता लागू हुए बिना पैराग्राफ का दायाँ मार्जिन सेट करता है। लिखें **float**। |
| virtual void [set_RightToLeft](./set_righttoleft/)([NullableBool](../nullablebool/)) | निर्धारित करता है कि क्या पैराग्राफ में दाएँ-से-बाएँ लेखन उपयोग किया जाता है। कोई वंशानुगतता लागू नहीं। लिखें [NullableBool](../nullablebool/)। |
| virtual void [set_SpaceAfter](./set_spaceafter/)(**float**) | कोई वंशानुगतता लागू हुए बिना पैराग्राफ की अंतिम पंक्ति के बाद स्थान की मात्रा सेट करता है। एक सकारात्मक मान सफेद स्थान का फ़ॉन्ट आकार का प्रतिशत निर्दिष्ट करता है। एक नकारात्मक मान सफेद स्थान का आकार बिंदु आकार में निर्दिष्ट करता है। लिखें **float**। |
| virtual void [set_SpaceBefore](./set_spacebefore/)(**float**) | कोई वंशानुगतता लागू हुए बिना पैराग्राफ की पहली पंक्ति से पहले स्थान की मात्रा सेट करता है। एक सकारात्मक मान सफेद स्थान का फ़ॉन्ट आकार का प्रतिशत निर्दिष्ट करता है। एक नकारात्मक मान सफेद स्थान का आकार बिंदु आकार में निर्दिष्ट करता है। लिखें **float**। |
| virtual void [set_SpaceWithin](./set_spacewithin/)(**float**) | पैराग्राफ में बेस लाइनों के बीच स्थान की मात्रा सेट करता है। सकारात्मक मान प्रतिशत को दर्शाता है, नकारात्मक - बिंदुओं में आकार। कोई वंशानुगतता लागू नहीं। लिखें **float**। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n-वें टेम्पलेट आर्ग्यूमेंट को weak पॉइंटर (साझा के बजाय) सेट करता है। कंटेनरों में पॉइंटर को weak मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट बढ़ाता है। इसे सीधे नहीं कॉल किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट घटाता है और लौटाता है। इसे सीधे नहीं कॉल किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) विधि का समतुल्य। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कन्स्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() कथन की अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट बढ़ाता है। इसे सीधे नहीं कॉल किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट घटाता है। इसे सीधे नहीं कॉल किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## टिप्पणी

यह क्लास विशेष पैराग्राफ के लिए परिभाषित पैराग्राफ फ़ॉर्मेटिंग गुणों को लौटाने और बदलने के लिए उपयोग की जाती है। इसका अर्थ है कि मान प्राप्त करते समय कोई विरासत लागू नहीं होती इसलिए अधिकांश मामलों में आपको मान “अपरिभाषित” मिलेंगे।

विरासत सहित प्रभावी फ़ॉर्मेटिंग पैरामीटर मान प्राप्त करने के लिए आपको [IParagraphFormat::GetEffective](./geteffective/) मेथड का उपयोग करना होगा जो एक [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/) इंस्टेंस लौटाता है।

## देखें

* क्लास [Object](../../system/object/)
* नामस्थान [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)