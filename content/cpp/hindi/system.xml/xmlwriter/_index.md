---
title: XmlWriter
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक राइटर को दर्शाता है जो तेज़, गैर-कैश्ड, केवल-फ़ॉरवर्ड तरीका प्रदान करता है जिससे XML डेटा वाली स्ट्रीम्स या फ़ाइलें जनरेट की जा सकें।
type: docs
weight: 573
url: /hi/system.xml/xmlwriter/
---
## XmlWriter क्लास

Represents a writer that provides a fast, non-cached, forward-only way to generate streams or files that contain XML data.

```cpp
class XmlWriter : public System::IDisposable
```

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| virtual void [Close](./close/)() | जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो यह स्ट्रीम और अंतर्निहित स्ट्रीम को बंद कर देता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&) | निर्दिष्ट फ़ाइलनाम का उपयोग करके एक नया [XmlWriter](./) इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | फ़ाइलनाम और [XmlWriterSettings](../xmlwritersettings/) ऑब्जेक्ट का उपयोग करके एक नया [XmlWriter](./) इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | निर्दिष्ट स्ट्रीम का उपयोग करके एक नया [XmlWriter](./) इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | स्ट्रीम और [XmlWriterSettings](../xmlwritersettings/) ऑब्जेक्ट का उपयोग करके एक नया [XmlWriter](./) इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | निर्दिष्ट TextWriter का उपयोग करके एक नया [XmlWriter](./) इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | TextWriter और [XmlWriterSettings](../xmlwritersettings/) ऑब्जेक्ट्स का उपयोग करके एक नया [XmlWriter](./) इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | निर्दिष्ट [Text::StringBuilder](../../system.text/stringbuilder/) का उपयोग करके एक नया [XmlWriter](./) इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | [Text::StringBuilder](../../system.text/stringbuilder/) और [XmlWriterSettings](../xmlwritersettings/) ऑब्जेक्ट्स का उपयोग करके एक नया [XmlWriter](./) इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&) | निर्दिष्ट [XmlWriter](./) ऑब्जेक्ट का उपयोग करके एक नया [XmlWriter](./) इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | निर्दिष्ट [XmlWriter](./) और [XmlWriterSettings](../xmlwritersettings/) ऑब्जेक्ट्स का उपयोग करके एक नया [XmlWriter](./) इंस्टेंस बनाता है। |
| void [Dispose](./dispose/)() override | वर्तमान [XmlWriter](./) क्लास के इस इंस्टेंस द्वारा उपयोग किए गए सभी संसाधनों को रिलीज़ करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफरेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual void [Flush](./flush/)() | जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो बफ़र में मौजूद सभी डेटा को अंतर्निहित स्ट्रीम्स में फ़्लश करता है और अंतर्निहित स्ट्रीम को भी फ़्लश करता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\> [get_Settings](./get_settings/)() | इस [XmlWriter](./) इंस्टेंस को बनाने के लिए उपयोग किए गए [XmlWriterSettings](../xmlwritersettings/) ऑब्जेक्ट को लौटाता है। |
| virtual [System::Xml::WriteState](../writestate/) [get_WriteState](./get_writestate/)() | जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो राइटर की स्थिति प्राप्त करता है। |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो वर्तमान **xml:lang** स्कोप प्राप्त करता है। |
| virtual [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() | जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो वर्तमान **xml:space** स्कोप का प्रतिनिधित्व करने वाला XmlSpace प्राप्त करता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स की हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार के इंस्टेंस का प्रतिनिधित्व करता है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट की लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [String](../../system/string/) [LookupPrefix](./lookupprefix/)([String](../../system/string/)) | जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो वर्तमान नेमस्पेस स्कोप में परिभाषित सबसे नज़दीकी प्रीफ़िक्स को लौटाता है। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम टाइप्स को क्लोन करने में सक्षम बनाता है। |
| [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को प्रारंभ करता है। |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट प्रारंत करता है और सबक्लासेस की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट प्रारंत करता है और सबक्लासेस की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस-तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण, स्ट्रिंग और nullptr के मामले के लिए। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण, स्ट्रिंग्स के मामले के लिए। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट घटाता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्ग्यूमेंट को वैक पॉइंटर सेट करता है (शेयर्ड के बजाय)। कंटेनर में पॉइंटर को वैक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट की अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वैक रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वैक रेफ़रेंस काउंट को घटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual void [WriteAttributes](./writeattributes/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो [XmlReader](../xmlreader/) में वर्तमान स्थिति पर मिलने वाले सभी एट्रिब्यूट्स को लिखता है। |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो निर्दिष्ट स्थानीय नाम, नेमस्पेस URI, और मान के साथ एक एट्रिब्यूट लिखता है। |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो निर्दिष्ट स्थानीय नाम और मान के साथ एट्रिब्यूट लिखता है। |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो निर्दिष्ट प्रीफ़िक्स, स्थानीय नाम, नेमस्पेस URI और मान के साथ एट्रिब्यूट लिखता है। |
| virtual void [WriteBase64](./writebase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो निर्दिष्ट बाइनरी बाइट्स को Base64 में एन्कोड करता है और परिणामी टेक्स्ट लिखता है। |
| virtual void [WriteBinHex](./writebinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो निर्दिष्ट बाइनरी बाइट्स को **BinHex** में एन्कोड करता है और परिणामी टेक्स्ट लिखता है। |
| virtual void [WriteCData](./writecdata/)([String](../../system/string/)) | जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो निर्दिष्ट टेक्स्ट वाला **...** ब्लॉक लिखता है। |
| virtual void [WriteCharEntity](./writecharentity/)(char16_t) | जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो निर्दिष्ट यूनिकोड कैरेक्टर वैल्यू के लिए कैरेक्टर एंटिटी जेनरेट करने को मजबूर करता है। |
| virtual void [WriteChars](./writechars/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो टेक्स्ट को एक बफ़र एक समय में लिखता है। |
| virtual void [WriteComment](./writecomment/)([String](../../system/string/)) | जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो निर्दिष्ट टेक्स्ट वाला **** टिप्पणी लिखता है। |
| virtual void [WriteDocType](./writedoctype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो निर्दिष्ट नाम और वैकल्पिक एट्रिब्यूट्स के साथ DOCTYPE घोषणा लिखता है। |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | निर्दिष्ट स्थानीय नाम और मान के साथ एक एलिमेंट लिखता है। |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | निर्दिष्ट स्थानीय नाम, नेमस्पेस URI, और मान के साथ एक एलिमेंट लिखता है। |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | निर्दिष्ट प्रीफ़िक्स, स्थानीय नाम, नेमस्पेस URI, और मान के साथ एक एलिमेंट लिखता है। |
| virtual void [WriteEndAttribute](./writeendattribute/)() | जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो पिछले XmlWriter::WriteStartAttribute(String,String) कॉल को बंद करता है। |
| virtual void [WriteEndDocument](./writeenddocument/)() | जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो सभी खुले तत्व या एट्रिब्यूट्स को बंद करता है और राइटर को स्टार्ट अवस्था में ले जाता है। |
| virtual void [WriteEndElement](./writeendelement/)() | जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो एक तत्व को बंद करता है और संबंधित नेमस्पेस स्कोप को पॉप करता है। |
| virtual void [WriteEntityRef](./writeentityref/)(const [String](../../system/string/)\&) | जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो एंटिटी रेफ़रेंस को **&name**; के रूप में लिखता है। |
| virtual void [WriteFullEndElement](./writefullendelement/)() | जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो एक तत्व को बंद करता है और संबंधित नेमस्पेस स्कोप को पॉप करता है। |
| virtual void [WriteName](./writename/)(const [String](../../system/string/)\&) | जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो निर्दिष्ट नाम लिखता है, यह सुनिश्चित करते हुए कि वह W3C XML 1.0 सिफ़ारिश ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)) के अनुसार वैध है। |
| virtual void [WriteNmToken](./writenmtoken/)(const [String](../../system/string/)\&) | जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो निर्दिष्ट नाम लिखता है, यह सुनिश्चित करते हुए कि वह W3C XML 1.0 सिफ़ारिश ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)) के अनुसार वैध NmToken है। |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो रीडर से राइटर तक सब कुछ कॉपी करता है और रीडर को अगले सिब्लिंग की शुरुआत में ले जाता है। |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>, **bool**) | XPathNavigator ऑब्जेक्ट से राइटर तक सब कुछ कॉपी करता है। XPathNavigator की स्थिति अपरिवर्तित रहती है। |
| virtual void [WriteProcessingInstruction](./writeprocessinginstruction/)([String](../../system/string/), [String](../../system/string/)) | जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो नाम और टेक्स्ट के बीच स्पेस के साथ प्रोसेसिंग इंस्ट्रक्शन लिखता है, इस प्रकार: **<?name text?>**। |
| virtual void [WriteQualifiedName](./writequalifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो नेमस्पेस-योग्य नाम लिखता है। यह मेथड दिए गए नेमस्पेस के लिए स्कोप में मौजूद प्रीफ़िक्स को खोजता है। |
| virtual void [WriteRaw](./writeraw/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो कैरेक्टर बफ़र से मैन्युअली रॉ मार्कअप लिखता है। |
| virtual void [WriteRaw](./writeraw/)(const [String](../../system/string/)\&) | जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो स्ट्रिंग से मैन्युअली रॉ मार्कअप लिखता है। |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | निर्दिष्ट स्थानीय नाम और नेमस्पेस URI के साथ एट्रिब्यूट की शुरुआत लिखता है। |
| virtual void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो निर्दिष्ट प्रीफ़िक्स, स्थानीय नाम और नेमस्पेस URI के साथ एट्रिब्यूट की शुरुआत लिखता है। |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&) | निर्दिष्ट स्थानीय नाम के साथ एट्रिब्यूट की शुरुआत लिखता है। |
| virtual void [WriteStartDocument](./writestartdocument/)() | जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो संस्करण "1.0" के साथ XML घोषणा लिखता है। |
| virtual void [WriteStartDocument](./writestartdocument/)(**bool**) | जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो संस्करण "1.0" और स्टैंडअलोन एट्रिब्यूट के साथ XML घोषणा लिखता है। |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो निर्दिष्ट स्टार्ट टैग लिखता है और उसे दिए गए नेमस्पेस से जोड़ता है। |
| virtual void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो निर्दिष्ट स्टार्ट टैग लिखता है और उसे दिए गए नेमस्पेस और प्रीफ़िक्स से जोड़ता है। |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&) | जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो निर्दिष्ट स्थानीय नाम के साथ एक स्टार्ट टैग लिखता है। |
| virtual void [WriteString](./writestring/)(const [String](../../system/string/)\&) | जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो दिया गया टेक्स्ट कंटेंट लिखता है। |
| virtual void [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) | जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो सरोगेट कैरेक्टर जोड़ी के लिए सरोगेट कैरेक्टर एंटिटी उत्पन्न करता है और लिखता है। |
| virtual void [WriteValue](./writevalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | ऑब्जेक्ट वैल्यू लिखता है। |
| virtual void [WriteValue](./writevalue/)(const [String](../../system/string/)\&) | [String](../../system/string/) वैल्यू लिखता है। |
| virtual void [WriteValue](./writevalue/)(**bool**) | [Boolean](../../system/boolean/) वैल्यू लिखता है। |
| virtual void [WriteValue](./writevalue/)([DateTime](../../system/datetime/)) | [DateTime](../../system/datetime/) वैल्यू लिखता है। |
| virtual void [WriteValue](./writevalue/)([DateTimeOffset](../../system/datetimeoffset/)) | [DateTimeOffset](../../system/datetimeoffset/) वैल्यू लिखता है। |
| virtual void [WriteValue](./writevalue/)(**double**) | [Double](../../system/double/) वैल्यू लिखता है। |
| virtual void [WriteValue](./writevalue/)(**float**) | एक सिंगल-प्रिसीजन फ्लोटिंग पॉइंट संख्या लिखता है। |
| virtual void [WriteValue](./writevalue/)([Decimal](../../system/decimal/)) | [Decimal](../../system/decimal/) वैल्यू लिखता है। |
| virtual void [WriteValue](./writevalue/)(**int32_t**) | [Int32](../../system/int32/) वैल्यू लिखता है। |
| virtual void [WriteValue](./writevalue/)(**int64_t**) | [Int64](../../system/int64/) वैल्यू लिखता है। |
| virtual void [WriteWhitespace](./writewhitespace/)([String](../../system/string/)) | जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो दिया गया व्हाइटस्पेस लिखता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## टाइपडिफ़

| टाइपडिफ़ | विवरण |
| --- | --- |
| [Ptr](./ptr/) | इस क्लास के इंस्टेंस के लिए साझा पॉइंटर का उपनाम। |

## संबंधित

* क्लास [IDisposable](../../system/idisposable/)
* नेमस्पेस [System::Xml](../)
* लाइब्रेरी [Aspose.Slides](../../)