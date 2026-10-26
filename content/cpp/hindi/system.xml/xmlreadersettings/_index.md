---
title: XmlReaderSettings
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: "XmlReader::Create मेथड द्वारा निर्मित XmlReader ऑब्जेक्ट पर समर्थन करने के लिए विशेषताओं का एक सेट निर्दिष्ट करता है।"
type: docs
weight: 443
url: /hi/system.xml/xmlreadersettings/
---
## XmlReaderSettings क्लास

एक सेट विशेषताएँ निर्दिष्ट करता है जिसे [XmlReader](../xmlreader/) ऑब्जेक्ट पर समर्थन किया जा सके, जिसे [XmlReader::Create](../xmlreader/create/) मेथड द्वारा बनाया गया है।

```cpp
class XmlReaderSettings : public System::Object
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| void [CheckReadOnly](./checkreadonly/)(const [String](../../system/string/)\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](./)\> [Clone](./clone/)() | एक [XmlReaderSettings](./) उदाहरण की प्रति बनाता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सिमेंटिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | एक मान लौटाता है जो यह दर्शाता है कि क्या कैरेक्टर जांच करना है। |
| **bool** [get_CloseInput](./get_closeinput/)() | एक मान लौटाता है जो यह दर्शाता है कि रीडर बंद होने पर मूल स्ट्रीम या TextReader को बंद किया जाना चाहिए या नहीं। |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | वह अनुरूपता स्तर लौटाता है जिससे [XmlReader](../xmlreader/) अनुपूर्ण होगा। |
| [System::Xml::DtdProcessing](../dtdprocessing/) [get_DtdProcessing](./get_dtdprocessing/)() | एक मान लौटाता है जो DTDs की प्रक्रिया निर्धारित करता है। |
| **bool** [get_IgnoreComments](./get_ignorecomments/)() | एक मान लौटाता है जो यह दर्शाता है कि टिप्पणियों को अनदेखा करना है या नहीं। |
| **bool** [get_IgnoreProcessingInstructions](./get_ignoreprocessinginstructions/)() | एक मान लौटाता है जो यह दर्शाता है कि प्रोसेसिंग इंस्ट्रक्शन को अनदेखा करना है या नहीं। |
| **bool** [get_IgnoreWhitespace](./get_ignorewhitespace/)() | एक मान लौटाता है जो यह दर्शाता है कि महत्वहीन व्हाइट स्पेस को अनदेखा करना है या नहीं। |
| **int32_t** [get_LineNumberOffset](./get_linenumberoffset/)() | [XmlReader](../xmlreader/) ऑब्जेक्ट की लाइन नंबर ऑफसेट लौटाता है। |
| **int32_t** [get_LinePositionOffset](./get_linepositionoffset/)() | [XmlReader](../xmlreader/) ऑब्जेक्ट की लाइन पोजीशन ऑफसेट लौटाता है। |
| **int64_t** [get_MaxCharactersFromEntities](./get_maxcharactersfromentities/)() | एक मान लौटाता है जो यह दर्शाता है कि इकाइयों को विस्तार करने से उत्पन्न दस्तावेज़ में अधिकतम अनुकूल अक्षर संख्या क्या है। |
| **int64_t** [get_MaxCharactersInDocument](./get_maxcharactersindocument/)() | एक मान लौटाता है जो XML दस्तावेज़ में अधिकतम अनुमत अक्षर संख्या दर्शाता है। शून्य (0) मान का अर्थ है कि XML दस्तावेज़ के आकार पर कोई सीमा नहीं है। गैर-शून्य मान अधिकतम आकार को अक्षरों में निर्दिष्ट करता है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | एटॉमाइज्ड स्ट्रिंग तुलना के लिए उपयोग किए जाने वाले [XmlNameTable](../xmlnametable/) को लौटाता है। |
| **bool** [get_ProhibitDtd](./get_prohibitdtd/)() | एक मान लौटाता है जो यह दर्शाता है कि दस्तावेज़ प्रकार परिभाषा (DTD) प्रक्रिया को प्रतिबंधित करना है या नहीं। |
| [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\> [get_Schemas](./get_schemas/)() | स्कीमा वैधता के दौरान उपयोग किए जाने वाले XmlSchemaSet को लौटाता है। |
| [Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/) [get_ValidationFlags](./get_validationflags/)() | स्कीमा वैधता सेटिंग्स दर्शाने वाला मान लौटाता है। यह सेटिंग उन [XmlReader](../xmlreader/) ऑब्जेक्ट्स पर लागू होती है जो स्कीमा को वैध करता है ([XmlReaderSettings::get_ValidationType](./get_validationtype/) मान [ValidationType::Schema](../validationtype/) है)। |
| [System::Xml::ValidationType](../validationtype/) [get_ValidationType](./get_validationtype/)() | एक मान लौटाता है जो यह दर्शाता है कि पढ़ते समय [XmlReader](../xmlreader/) वैधता या टाइप असाइनमेंट करेगा या नहीं। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स की हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक टाइप प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित टाइप का एक उदाहरण है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम टाइप्स की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस द्वारा वैल्यू टाइप ऑब्जेक्ट की nullptr से तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के मामले के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट को घटाते हैं। |
| void [Reset](./reset/)() | सेटिंग्स क्लास के सदस्यों को उनकी डिफ़ॉल्ट मानों पर रीसेट करता है। |
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | एक मान सेट करता है जो यह दर्शाता है कि कैरेक्टर जांच करना है या नहीं। |
| void [set_CloseInput](./set_closeinput/)(**bool**) | एक मान सेट करता है जो यह दर्शाता है कि रीडर बंद होने पर मूल स्ट्रीम या TextReader को बंद करना चाहिए या नहीं। |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | वह अनुरूपता स्तर सेट करता है जिससे [XmlReader](../xmlreader/) अनुरूप होगा। |
| void [set_DtdProcessing](./set_dtdprocessing/)([System::Xml::DtdProcessing](../dtdprocessing/)) | एक मान सेट करता है जो DTDs की प्रक्रिया निर्धारित करता है। |
| void [set_IgnoreComments](./set_ignorecomments/)(**bool**) | एक मान सेट करता है जो यह दर्शाता है कि टिप्पणियों को अनदेखा करना है या नहीं। |
| void [set_IgnoreProcessingInstructions](./set_ignoreprocessinginstructions/)(**bool**) | एक मान सेट करता है जो यह दर्शाता है कि प्रोसेसिंग इंस्ट्रक्शन को अनदेखा करना है या नहीं। |
| void [set_IgnoreWhitespace](./set_ignorewhitespace/)(**bool**) | एक मान सेट करता है जो यह दर्शाता है कि महत्वहीन व्हाइट स्पेस को अनदेखा करना है या नहीं। |
| void [set_LineNumberOffset](./set_linenumberoffset/)(**int32_t**) | [XmlReader](../xmlreader/) ऑब्जेक्ट की लाइन नंबर ऑफसेट सेट करता है। |
| void [set_LinePositionOffset](./set_linepositionoffset/)(**int32_t**) | [XmlReader](../xmlreader/) ऑब्जेक्ट की लाइन पोजीशन ऑफसेट सेट करता है। |
| void [set_MaxCharactersFromEntities](./set_maxcharactersfromentities/)(**int64_t**) | एक मान सेट करता है जो इकाइयों को विस्तार करने से उत्पन्न दस्तावेज़ में अधिकतम अनुमत अक्षर संख्या दर्शाता है। |
| void [set_MaxCharactersInDocument](./set_maxcharactersindocument/)(**int64_t**) | एक मान सेट करता है जो XML दस्तावेज़ में अधिकतम अनुमत अक्षर संख्या दर्शाता है। शून्य (0) मान का अर्थ है XML दस्तावेज़ के आकार पर कोई सीमा नहीं। गैर-शून्य मान अधिकतम आकार को अक्षरों में निर्दिष्ट करता है। |
| void [set_NameTable](./set_nametable/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | एटॉमाइज्ड स्ट्रिंग तुलना के लिए उपयोग किए जाने वाले [XmlNameTable](../xmlnametable/) को सेट करता है। |
| void [set_ProhibitDtd](./set_prohibitdtd/)(**bool**) | एक मान सेट करता है जो यह दर्शाता है कि दस्तावेज़ प्रकार परिभाषा (DTD) प्रक्रिया को प्रतिबंधित करना है या नहीं। |
| void [set_Schemas](./set_schemas/)(const [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>\&) | स्कीमा वैधता के दौरान उपयोग किए जाने वाले XmlSchemaSet को सेट करता है। |
| void [set_ValidationFlags](./set_validationflags/)([Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/)) | स्कीमा वैधता सेटिंग्स को दर्शाने वाला मान सेट करता है। यह सेटिंग उन [XmlReader](../xmlreader/) ऑब्जेक्ट्स पर लागू होती है जो स्कीमा को वैध करता है ([XmlReaderSettings::get_ValidationType](./get_validationtype/) मान [ValidationType::Schema](../validationtype/) है)। |
| void [set_ValidationType](./set_validationtype/)([System::Xml::ValidationType](../validationtype/)) | एक मान सेट करता है जो यह दर्शाता है कि पढ़ते समय [XmlReader](../xmlreader/) वैधता या टाइप असाइनमेंट करेगा या नहीं। |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | बाहरी दस्तावेज़ों तक पहुँचने के लिए उपयोग किए जाने वाले [XmlResolver](../xmlresolver/) को सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्प्लेट आर्ग्यूमेंट को एक weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनर में पॉइंटर्स को weak मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट घटाता और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) संरचना को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | जब रीडर वैधता त्रुटियों का सामना करता है तो एक इवेंट हैंडलर जोड़ता है। |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | जब रीडर वैधता त्रुटियों का सामना करता है तो इवेंट हैंडलर हटाता है। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Weak रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Weak रेफ़रेंस काउंट घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
|  [XmlReaderSettings](./xmlreadersettings/)() | [XmlReaderSettings](./) क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## टाइपडिफ़

| टाइपडिफ़ | विवरण |
| --- | --- |
| [Ptr](./ptr/) | इस क्लास की एक इंस्टेंस के लिए shared पॉइंटर का उपनाम। |

## टिप्पणियाँ

इस क्लास की वस्तुओं को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित करना चाहिए। इस प्रकार की इंस्टेंस को स्टैक पर या operator new का उपयोग करके कभी न बनाएं, क्योंकि इससे रनटाइम त्रुटियों और/या एसर्शन फ़ॉल्ट्स हो सकते हैं। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर को फ़ंक्शन्स को तर्क के रूप में पास करने के लिए उपयोग करें। 

## संबंधित देखें

* क्लास [Object](../../system/object/)
* नेमस्पेस [System::Xml](../)
* लाइब्रेरी [Aspose.Slides](../../)