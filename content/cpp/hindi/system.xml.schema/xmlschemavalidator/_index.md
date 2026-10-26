---
title: XmlSchemaValidator
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: एक XML Schema Definition Language (XSD) स्कीमा वैधता इंजन का प्रतिनिधित्व करता है। XmlSchemaValidator क्लास को विरासत में नहीं लिया जा सकता।
type: docs
weight: 937
url: /hi/system.xml.schema/xmlschemavalidator/
---
## XmlSchemaValidator क्लास

XML [Schema](../) डिफिनिशन लैंग्वेज (XSD) [Schema](../) वैधता इंजन का प्रतिनिधित्व करता है। [XmlSchemaValidator](./) क्लास को विरासत में नहीं ले सकती।

```cpp
class XmlSchemaValidator : public System::Object
```

## विधियां

| विधि | विवरण |
| --- | --- |
| void [AddSchema](./addschema/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | XML [Schema](../) डिफिनिशन लैंग्वेज (XSD) स्कीमा को वैधता के लिए उपयोग किए जाने वाले स्कीमा सेट में जोड़ता है। |
| void [EndValidation](./endvalidation/)() | वैधता समाप्त करता है और पूरे XML दस्तावेज़ के लिए पहचान बाधाओं की जाँच करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) अर्थविन्यास का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफरेंस प्रकार की वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# शैली की फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के साथ भी नहीं। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# शैली की फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के साथ भी नहीं। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| [SharedPtr](../../system/sharedptr/)\<[IXmlLineInfo](../../system.xml/ixmllineinfo/)\> [get_LineInfoProvider](./get_lineinfoprovider/)() | वैधता की जा रही XML नोड के लिए लाइन नंबर सूचना लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_SourceUri](./get_sourceuri/)() | वैधता की जा रही XML नोड के स्रोत URI को लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_ValidationEventSender](./get_validationeventsender/)() | वैधता घटना के प्रेषक ऑब्जेक्ट के रूप में भेजे गए ऑब्जेक्ट को लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchemaAttribute](../xmlschemaattribute/)\>\> [GetExpectedAttributes](./getexpectedattributes/)() | वर्तमान तत्व संदर्भ के लिए अपेक्षित एट्रीब्यूट्स को लौटाता है। |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchemaParticle](../xmlschemaparticle/)\>\> [GetExpectedParticles](./getexpectedparticles/)() | वर्तमान तत्व संदर्भ में अपेक्षित पार्टिकल्स को लौटाता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| void [GetUnspecifiedDefaultAttributes](./getunspecifieddefaultattributes/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\>\&) | डिफ़ॉल्ट एट्रीब्यूट्स पर पहचान बाधाओं को वैधता करता है और सूची को [XmlSchemaAttribute](../xmlschemaattribute/) ऑब्जेक्ट्स से भरता है उन सभी एट्रीब्यूट्स के लिए जिनके डिफ़ॉल्ट मान हैं और जिन्हें तत्व संदर्भ में [XmlSchemaValidator::ValidateAttribute](./validateattribute/) मेथड का उपयोग करके पहले वैधता नहीं किया गया है। |
| void [Initialize](./initialize/)() | [XmlSchemaValidator](./) ऑब्जेक्ट की स्थिति को प्रारंभ करता है। |
| void [Initialize](./initialize/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | [XmlSchemaValidator](./) ऑब्जेक्ट की स्थिति को [XmlSchemaObject](../xmlschemaobject/) का उपयोग करके प्रारंभ करता है, जिसे अंशिक वैधता के लिए निर्दिष्ट किया गया है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लास की कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लास की कॉपी निर्माण को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू प्रकार के ऑब्जेक्ट की रेफ़रेंस तुलना nullptr के साथ करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_LineInfoProvider](./set_lineinfoprovider/)(const [SharedPtr](../../system/sharedptr/)\<[IXmlLineInfo](../../system.xml/ixmllineinfo/)\>\&) | वैधता की जा रही XML नोड के लिए लाइन नंबर सूचना सेट करता है। |
| void [set_SourceUri](./set_sourceuri/)(const [SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>\&) | वैधता की जा रही XML नोड के स्रोत URI को सेट करता है। |
| void [set_ValidationEventSender](./set_validationeventsender/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | वैधता घटना के प्रेषक ऑब्जेक्ट के रूप में भेजे गए ऑब्जेक्ट को सेट करता है। |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | [XmlResolver](../../system.xml/xmlresolver/) ऑब्जेक्ट सेट करता है जो **xs:import** और **xs:include** तत्वों तथा **xsi:schemaLocation** और **xsi:noNamespaceSchemaLocation** एट्रीब्यूट्स को हल करने के लिए उपयोग होता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्पलेट आर्ग्युमेंट को कमजोर पॉइंटर (साझा के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को कमजोर मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [SkipToEndElement](./skiptoendelement/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | वर्तमान तत्व सामग्री की वैधता को छोड़ता है और [XmlSchemaValidator](./) ऑब्जेक्ट को पैरेंट तत्व के संदर्भ में सामग्री वैधता के लिए तैयार करता है। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) संरचना को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValidateAttribute](./validateattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | वर्तमान तत्व संदर्भ में एट्रीब्यूट नाम, नेमस्पेस URI और मान को वैधता करता है। |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValidateAttribute](./validateattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [XmlValueGetter](../xmlvaluegetter/), const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | वर्तमान तत्व संदर्भ में एट्रीब्यूट नाम, नेमस्पेस URI और मान को वैधता करता है। |
| void [ValidateElement](./validateelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | वर्तमान संदर्भ में तत्व को वैधता करता है। |
| void [ValidateElement](./validateelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | वर्तमान संदर्भ में तत्व को **xsi:Type**, **xsi:Nil**, **xsi:SchemaLocation**, और **xsi:NoNamespaceSchemaLocation** एट्रीब्यूट मानों के साथ वैधता करता है। |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValidateEndElement](./validateendelement/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | सरल सामग्री वाले तत्वों के लिए उसके डेटा प्रकार के अनुसार तत्व की टेक्स्ट सामग्री वैध है या नहीं, और जटिल सामग्री वाले तत्वों के लिए वर्तमान तत्व की सामग्री पूर्ण है या नहीं, इसकी पुष्टि करता है। |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValidateEndElement](./validateendelement/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | निर्दिष्ट तत्व की टेक्स्ट सामग्री उसके डेटा प्रकार के अनुसार वैध है या नहीं, इसकी पुष्टि करता है। |
| void [ValidateEndOfAttributes](./validateendofattributes/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | तत्व संदर्भ में सभी आवश्यक एट्रीब्यूट्स मौजूद हैं या नहीं, इसकी पुष्टि करता है और [XmlSchemaValidator](./) ऑब्जेक्ट को तत्व की चाइल्ड सामग्री वैधता के लिए तैयार करता है। |
| void [ValidateText](./validatetext/)(const [String](../../system/string/)\&) | जाँचता है कि निर्दिष्ट टेक्स्ट **string** वर्तमान तत्व संदर्भ में अनुमति है या नहीं, और यदि वर्तमान तत्व में सरल सामग्री है तो वैधता के लिए टेक्स्ट को संग्रहीत करता है। |
| void [ValidateText](./validatetext/)([XmlValueGetter](../xmlvaluegetter/)) | जाँचता है कि XmlValueGetter ऑब्जेक्ट द्वारा लौटाए गए टेक्स्ट वर्तमान तत्व संदर्भ में अनुमति है या नहीं, और यदि वर्तमान तत्व में सरल सामग्री है तो वैधता के लिए टेक्स्ट को संग्रहीत करता है। |
| void [ValidateWhitespace](./validatewhitespace/)(const [String](../../system/string/)\&) | जाँचता है कि निर्दिष्ट **string** में व्हाइट स्पेस वर्तमान तत्व संदर्भ में अनुमति है या नहीं, और यदि वर्तमान तत्व में सरल सामग्री है तो वैधता के लिए व्हाइट स्पेस को संग्रहीत करता है। |
| void [ValidateWhitespace](./validatewhitespace/)([XmlValueGetter](../xmlvaluegetter/)) | जाँचता है कि XmlValueGetter ऑब्जेक्ट द्वारा लौटाए गए व्हाइट स्पेस वर्तमान तत्व संदर्भ में अनुमति है या नहीं, और यदि वर्तमान तत्व में सरल सामग्री है तो वैधता के लिए व्हाइट स्पेस को संग्रहीत करता है। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
|  [XmlSchemaValidator](./xmlschemavalidator/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSet](../xmlschemaset/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>\&, [XmlSchemaValidationFlags](../xmlschemavalidationflags/)) | नई [XmlSchemaValidator](./) क्लास की इंस्टेंस को प्रारंभ करता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## टाइपडिफ़

| टाइपडिफ़ | विवरण |
| --- | --- |
| [Ptr](./ptr/) | इस क्लास की इंस्टेंस के लिए साझा पॉइंटर का उपनाम। |

## टिप्पणी



इस क्लास के ऑब्जेक्ट्स को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही एलोकेट किया जाना चाहिए। कभी भी इस प्रकार की इंस्टेंस को स्टैक पर या operator new का उपयोग करके न बनाएं, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन त्रुटियाँ हो सकती हैं। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर को फ़ंक्शन में आर्ग्यूमेंट के रूप में पास करें। 

## देखें

* क्लास [Object](../../system/object/)
* नेमस्पेस [System::Xml::Schema](../)
* लाइब्रेरी [Aspose.Slides](../../)