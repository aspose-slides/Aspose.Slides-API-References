---
title: XmlTextWriter
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: एक लेखक को दर्शाता है जो तेज़, गैर-कैश्ड, केवल-फ़ॉरवर्ड तरीके से स्ट्रीम या फ़ाइलें उत्पन्न करने की सुविधा प्रदान करता है, जिनमें XML डेटा होता है जो W3C Extensible Markup Language (XML) 1.0 और XML में नेमस्पेसेस की सिफ़ारिशों के अनुरूप है।
type: docs
weight: 521
url: /hi/system.xml/xmltextwriter/
---
## XmlTextWriter क्लास

Represents a writer that provides a fast, non-cached, forward-only way of generating streams or files containing XML data that conforms to the W3C Extensible Markup Language (XML) 1.0 and the Namespaces in XML recommendations.

```cpp
class XmlTextWriter : public System::Xml::XmlWriter
```

## मेथड्स

| Method | Description |
| --- | --- |
| void [Close](./close/)() override | इस स्ट्रीम और अंतर्निहित स्ट्रीम को बंद करता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [String](../../system/string/)\&) | [XmlWriter](../xmlwriter/) का नया उदाहरण निर्दिष्ट फ़ाइलनाम का उपयोग करके बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | [XmlWriter](../xmlwriter/) का नया उदाहरण फ़ाइलनाम और [XmlWriterSettings](../xmlwritersettings/) ऑब्जेक्ट का उपयोग करके बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | [XmlWriter](../xmlwriter/) का नया उदाहरण निर्दिष्ट स्ट्रीम का उपयोग करके बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | [XmlWriter](../xmlwriter/) का नया उदाहरण स्ट्रीम और [XmlWriterSettings](../xmlwritersettings/) ऑब्जेक्ट का उपयोग करके बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | [XmlWriter](../xmlwriter/) का नया उदाहरण निर्दिष्ट TextWriter का उपयोग करके बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | [XmlWriter](../xmlwriter/) का नया उदाहरण TextWriter और [XmlWriterSettings](../xmlwritersettings/) ऑब्जेक्ट्स का उपयोग करके बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | [XmlWriter](../xmlwriter/) का नया उदाहरण निर्दिष्ट [Text::StringBuilder](../../system.text/stringbuilder/) का उपयोग करके बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | [XmlWriter](../xmlwriter/) का नया उदाहरण [Text::StringBuilder](../../system.text/stringbuilder/) और [XmlWriterSettings](../xmlwritersettings/) ऑब्जेक्ट्स का उपयोग करके बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) | [XmlWriter](../xmlwriter/) का नया उदाहरण निर्दिष्ट [XmlWriter](../xmlwriter/) ऑब्जेक्ट का उपयोग करके बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | [XmlWriter](../xmlwriter/) का नया उदाहरण निर्दिष्ट [XmlWriter](../xmlwriter/) और [XmlWriterSettings](../xmlwritersettings/) ऑब्जेक्ट्स का उपयोग करके बनाता है। |
| void [Dispose](../xmlwriter/dispose/)() override | [XmlWriter](../xmlwriter/) क्लास के वर्तमान उदाहरण द्वारा उपयोग किए गए सभी संसाधनों को मुक्त करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सिंटैक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली का फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के साथ भी नहीं। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली का फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के साथ भी नहीं। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| void [Flush](./flush/)() override | बफ़र में मौजूद सभी डेटा को अंतर्निहित स्ट्रीम्स पर फ़्लश करता है तथा अंतर्निहित स्ट्रीम को भी फ़्लश करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [get_BaseStream](./get_basestream/)() | अंतर्निहित स्ट्रीम ऑब्जेक्ट को वापस करता है। |
| [System::Xml::Formatting](../formatting/) [get_Formatting](./get_formatting/)() | आउटपुट के फॉर्मेट को दर्शाता है। |
| **int32_t** [get_Indentation](./get_indentation/)() | जब [XmlTextWriter::set_Formatting](./set_formatting/) को [Formatting::Indented](../formatting/) पर सेट किया जाता है, तो पदानुक्रम में प्रत्येक स्तर के लिए लिखने योग्य IndentChars की संख्या लौटाता है। |
| char16_t [get_IndentChar](./get_indentchar/)() | जब [XmlTextWriter::set_Formatting](./set_formatting/) को [Formatting::Indented](../formatting/) पर सेट किया जाता है, तो इंडेंटिंग के लिए उपयोग होने वाला अक्षर लौटाता है। |
| **bool** [get_Namespaces](./get_namespaces/)() | नामस्थान समर्थन करने की आवश्यकता दर्शाने वाला मान लौटाता है। |
| char16_t [get_QuoteChar](./get_quotechar/)() | एट्रिब्यूट मानों को उद्धरण में रखने के लिए उपयोग होने वाला अक्षर लौटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\> [get_Settings](../xmlwriter/get_settings/)() | इस [XmlWriter](../xmlwriter/) उदाहरण को बनाने के लिए उपयोग किए गए [XmlWriterSettings](../xmlwritersettings/) ऑब्जेक्ट को लौटाता है। |
| [System::Xml::WriteState](../writestate/) [get_WriteState](./get_writestate/)() override | राइटर की स्थिति को लौटाता है। |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | वर्तमान **xml:lang** स्कोप को लौटाता है। |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | वर्तमान **xml:space** स्कोप को दर्शाने वाला XmlSpace लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा संरचना को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक उदाहरण है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंटीरी ऑब्जेक्ट का उपयोग करें। |
| [String](../../system/string/) [LookupPrefix](./lookupprefix/)([String](../../system/string/)) override | वर्तमान नामस्थान स्कोप में नेमस्पेस URI के लिए परिभाषित सबसे निकटतम प्रीफ़िक्स को लौटाता है। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr से रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण, स्ट्रिंग और nullptr के केस के लिए। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण, स्ट्रिंग्स के केस के लिए। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_Formatting](./set_formatting/)([System::Xml::Formatting](../formatting/)) | आउटपुट के फॉर्मेट को दर्शाता है। |
| void [set_Indentation](./set_indentation/)(**int32_t**) | जब [XmlTextWriter::set_Formatting](./set_formatting/) को [Formatting::Indented](../formatting/) पर सेट किया जाता है, तो पदानुक्रम में प्रत्येक स्तर के लिए लिखने योग्य IndentChars की संख्या सेट करता है। |
| void [set_IndentChar](./set_indentchar/)(char16_t) | जब [XmlTextWriter::set_Formatting](./set_formatting/) को [Formatting::Indented](../formatting/) पर सेट किया जाता है, तो इंडेंटिंग के लिए उपयोग होने वाला अक्षर सेट करता है। |
| void [set_Namespaces](./set_namespaces/)(**bool**) | नामस्थान समर्थन करने की आवश्यकता दर्शाने वाला मान सेट करता है। |
| void [set_QuoteChar](./set_quotechar/)(char16_t) | एट्रिब्यूट मानों को उद्धरण में रखने के लिए उपयोग होने वाला अक्षर सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nth टेम्प्लेट आर्गुमेंट को वीक पॉइंटर (शेयर्ड के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को वीक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं कॉल करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे नहीं कॉल करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंटीरी ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं कॉल करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। इसे सीधे नहीं कॉल करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual void [WriteAttributes](../xmlwriter/writeattributes/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | डेराइव्ड क्लास में ओवरराइड किए जाने पर, [XmlReader](../xmlreader/) में वर्तमान स्थिति पर पाए गए सभी एट्रिब्यूट्स को लिखता है। |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | डेराइव्ड क्लास में ओवरराइड किए जाने पर, निर्दिष्ट स्थानीय नाम, नेमस्पेस URI और मान के साथ एक एट्रिब्यूट लिखता है। |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | डेराइव्ड क्लास में ओवरराइड किए जाने पर, निर्दिष्ट स्थानीय नाम और मान के साथ एट्रिब्यूट लिखता है। |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | डेराइव्ड क्लास में ओवरराइड किए जाने पर, निर्दिष्ट प्रीफ़िक्स, स्थानीय नाम, नेमस्पेस URI और मान के साथ एट्रिब्यूट लिखता है। |
| void [WriteBase64](./writebase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | निर्दिष्ट बाइनरी बाइट्स को base64 के रूप में एन्कोड करता है और परिणामस्वरूप टेक्स्ट लिखता है। |
| void [WriteBinHex](./writebinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | निर्दिष्ट बाइनरी बाइट्स को binhex के रूप में एन्कोड करता है और परिणामस्वरूप टेक्स्ट लिखता है। |
| void [WriteCData](./writecdata/)([String](../../system/string/)) override | निर्दिष्ट टेक्स्ट वाला **...** ब्लॉक लिखता है। |
| void [WriteCharEntity](./writecharentity/)(char16_t) override | निर्दिष्ट यूनिकोड कैरेक्टर वैल्यू के लिए कैरेक्टर एंटिटी का सृजन बाध्य करता है। |
| void [WriteChars](./writechars/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | एक बार में एक बफ़र का टेक्स्ट लिखता है। |
| void [WriteComment](./writecomment/)([String](../../system/string/)) override | निर्दिष्ट टेक्स्ट वाला **** टिप्पणी लिखता है। |
| void [WriteDocType](./writedoctype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | निर्दिष्ट नाम और वैकल्पिक एट्रिब्यूट्स के साथ DOCTYPE घोषणा लिखता है। |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | निर्दिष्ट स्थानीय नाम और मान के साथ एक एलिमेंट लिखता है। |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | निर्दिष्ट स्थानीय नाम, नेमस्पेस URI और मान के साथ एक एलिमेंट लिखता है। |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | निर्दिष्ट प्रीफ़िक्स, स्थानीय नाम, नेमस्पेस URI और मान के साथ एक एलिमेंट लिखता है। |
| void [WriteEndAttribute](./writeendattribute/)() override | पिछले [XmlTextWriter::WriteStartAttribute](./writestartattribute/) कॉल को बंद करता है। |
| void [WriteEndDocument](./writeenddocument/)() override | कोई भी खुले एलिमेंट्स या एट्रिब्यूट्स को बंद करता है और राइटर को Start स्थिति में लौटाता है। |
| void [WriteEndElement](./writeendelement/)() override | एक एलिमेंट को बंद करता है और अनुरूप नेमस्पेस स्कोप को पॉप करता है। |
| void [WriteEntityRef](./writeentityref/)(const [String](../../system/string/)\&) override | एक एंटिटी रेफ़रेंस को **&name**; के रूप में लिखता है। |
| void [WriteFullEndElement](./writefullendelement/)() override | एक एलिमेंट को बंद करता है और अनुरूप नेमस्पेस स्कोप को पॉप करता है। |
| void [WriteName](./writename/)(const [String](../../system/string/)\&) override | निर्दिष्ट नाम लिखता है, यह सुनिश्चित करते हुए कि यह [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name) के अनुसार वैध नाम है। |
| void [WriteNmToken](./writenmtoken/)(const [String](../../system/string/)\&) override | निर्दिष्ट नाम लिखता है, यह सुनिश्चित करते हुए कि यह [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name) के अनुसार वैध **NmToken** है। |
| virtual void [WriteNode](../xmlwriter/writenode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | डेराइव्ड क्लास में ओवरराइड किए जाने पर, रीडर से सभी सामग्री को राइटर में कॉपी करता है और रीडर को अगले सिब्लिंग की शुरुआत में ले जाता है। |
| virtual void [WriteNode](../xmlwriter/writenode/)([SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>, **bool**) | XPathNavigator ऑब्जेक्ट से सभी सामग्री को राइटर में कॉपी करता है। XPathNavigator की स्थिति अपरिवर्तित रहती है। |
| void [WriteProcessingInstruction](./writeprocessinginstruction/)([String](../../system/string/), [String](../../system/string/)) override | नाम और टेक्स्ट के बीच स्पेस के साथ प्रोसेसिंग इंस्ट्रक्शन लिखता है, जैसा कि: **<?name text?>**। |
| void [WriteQualifiedName](./writequalifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | नामस्पेस-योग्य नाम लिखता है। यह मेथड दिए गए नेमस्पेस के लिए स्कोप में मौजूद प्रीफ़िक्स को खोजता है। |
| void [WriteRaw](./writeraw/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | कैरेक्टर बफ़र से मैन्युअली रॉ मार्कअप लिखता है। |
| void [WriteRaw](./writeraw/)(const [String](../../system/string/)\&) override | स्ट्रिंग से मैन्युअली रॉ मार्कअप लिखता है। |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | एट्रिब्यूट की शुरुआत लिखता है। |
| void [WriteStartAttribute](../xmlwriter/writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | निर्दिष्ट स्थानीय नाम और नेमस्पेस URI के साथ एट्रिब्यूट की शुरुआत लिखता है। |
| void [WriteStartAttribute](../xmlwriter/writestartattribute/)(const [String](../../system/string/)\&) | निर्दिष्ट स्थानीय नाम के साथ एट्रिब्यूट की शुरुआत लिखता है। |
| void [WriteStartDocument](./writestartdocument/)() override | संस्करण "1.0" के साथ XML घोषणा लिखता है। |
| void [WriteStartDocument](./writestartdocument/)(**bool**) override | संस्करण "1.0" और standalone एट्रिब्यूट के साथ XML घोषणा लिखता है। |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | निर्दिष्ट स्टार्ट टैग लिखता है और इसे दिए गए नेमस्पेस और प्रीफ़िक्स से जोड़ता है। |
| void [WriteStartElement](../xmlwriter/writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | डेराइव्ड क्लास में ओवरराइड किए जाने पर, निर्दिष्ट स्टार्ट टैग लिखता है और इसे दिए गए नेमस्पेस से जोड़ता है। |
| void [WriteStartElement](../xmlwriter/writestartelement/)(const [String](../../system/string/)\&) | डेराइव्ड क्लास में ओवरराइड किए जाने पर, निर्दिष्ट स्थानीय नाम के साथ स्टार्ट टैग लिखता है। |
| void [WriteString](./writestring/)(const [String](../../system/string/)\&) override | दिए गए टेक्स्ट कंटेंट को लिखता है। |
| void [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) override | सर्जेट कैरेक्टर पेयर के लिए सर्जेट कैरेक्टर एंटिटी उत्पन्न करता है और लिखता है। |
| virtual void [WriteValue](../xmlwriter/writevalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | ऑब्जेक्ट वैल्यू लिखता है। |
| virtual void [WriteValue](../xmlwriter/writevalue/)(const [String](../../system/string/)\&) | [String](../../system/string/) मान लिखता है। |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**bool**) | [Boolean](../../system/boolean/) मान लिखता है। |
| virtual void [WriteValue](../xmlwriter/writevalue/)([DateTime](../../system/datetime/)) | [DateTime](../../system/datetime/) मान लिखता है। |
| virtual void [WriteValue](../xmlwriter/writevalue/)([DateTimeOffset](../../system/datetimeoffset/)) | [DateTimeOffset](../../system/datetimeoffset/) मान लिखता है। |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**double**) | [Double](../../system/double/) मान लिखता है। |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**float**) | सिंगल-प्रेसिशन फ्लोटिंग पॉइंट नंबर लिखता है। |
| virtual void [WriteValue](../xmlwriter/writevalue/)([Decimal](../../system/decimal/)) | [Decimal](../../system/decimal/) मान लिखता है। |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**int32_t**) | [Int32](../../system/int32/) मान लिखता है। |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**int64_t**) | [Int64](../../system/int64/) मान लिखता है। |
| void [WriteWhitespace](./writewhitespace/)([String](../../system/string/)) override | दिए गए व्हाइटस्पेस को लिखता है। |
|  [XmlTextWriter](./xmltextwriter/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | [XmlTextWriter](./) क्लास का एक उदाहरण निर्दिष्ट स्ट्रीम और एन्कोडिंग का उपयोग करके बनाता है। |
|  [XmlTextWriter](./xmltextwriter/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | [XmlTextWriter](./) क्लास का एक उदाहरण निर्दिष्ट फ़ाइल का उपयोग करके बनाता है। |
|  [XmlTextWriter](./xmltextwriter/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | [XmlTextWriter](./) क्लास का एक उदाहरण निर्दिष्ट TextWriter का उपयोग करके बनाता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## टाइपडिफ़

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | इस क्लास के एक उदाहरण के लिए शेयरड पॉइंटर का उपनाम। |

## टिप्पणी

यह अनुशंसा की जाती है कि [XmlWriter](../xmlwriter/) क्लास का उपयोग किया जाए।

इस क्लास के ऑब्जेक्ट्स को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। स्टैक पर या operator new का उपयोग करके इस प्रकार के उदाहरण न बनाएँ, क्योंकि इससे रन-टाइम त्रुटियाँ और/या असर्शन फॉल्ट हो सकते हैं। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर को आर्ग्युमेंट के रूप में फ़ंक्शंस में पास करें।

## देखें

* क्लास [XmlWriter](../xmlwriter/)
* नेमस्पेस [System::Xml](../)
* लाइब्रेरी [Aspose.Slides](../../)