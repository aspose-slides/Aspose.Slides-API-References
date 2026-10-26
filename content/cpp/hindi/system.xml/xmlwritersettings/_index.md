---
title: XmlWriterSettings
second_title: Aspose.Slides for C++ API संदर्भ
description: "XmlWriter::Create मेथड द्वारा निर्मित XmlWriter ऑब्जेक्ट पर समर्थन के लिए सुविधाओं का एक सेट निर्दिष्ट करता है।"
type: docs
weight: 586
url: /hi/system.xml/xmlwritersettings/
---
## XmlWriterSettings क्लास


[XmlWriter](../xmlwriter/) ऑब्जेक्ट पर उन सुविधाओं का एक सेट निर्दिष्ट करता है जिसे [XmlWriter::Create](../xmlwriter/create/) मेथड द्वारा बनाया गया है।

```cpp
class XmlWriterSettings : public System::Object
```

## विधियाँ

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](./)\> [Clone](./clone/)() | [XmlWriterSettings](./) इंस्टेंस की एक प्रति बनाता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमान्टिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली का फ्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली का फ्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | एक मान लौटाता है जो दर्शाता है कि XML राइटर को यह जांचना चाहिए कि दस्तावेज़ के सभी कैरेक्टर W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets) के "2.2 Characters" सेक्शन के अनुरूप हैं या नहीं। |
| **bool** [get_CloseOutput](./get_closeoutput/)() | एक मान लौटाता है जो दर्शाता है कि [XmlWriter](../xmlwriter/) को [XmlWriter::Close](../xmlwriter/close/) मेथड कॉल होने पर बेस स्ट्रीम या TextWriter को भी बंद करना चाहिए या नहीं। |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | XML राइटर द्वारा XML आउटपुट की जांच के लिए जिस अनुरूपता स्तर को वह देखता है, वह लौटाता है। |
| **bool** [get_DoNotEscapeUriAttributes](./get_donotescapeuriattributes/)() | एक मान लौटाता है जो दर्शाता है कि [XmlWriter](../xmlwriter/) URI विशेषताओं को एस्केप नहीं करता। |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | उपयोग करने के लिए टेक्स्ट एन्कोडिंग के प्रकार को लौटाता है। |
| **bool** [get_Indent](./get_indent/)() | एक मान लौटाता है जो दर्शाता है कि एलिमेंट्स को इंडेंट किया जाना चाहिए या नहीं। |
| [String](../../system/string/) [get_IndentChars](./get_indentchars/)() | इंडेंट करने के समय उपयोग करने के लिए कैरेक्टर स्ट्रिंग लौटाता है। यह सेटिंग तब उपयोग होती है जब [XmlWriterSettings::set_Indent](./set_indent/) मान **true** पर सेट हो। |
| [System::Xml::NamespaceHandling](../namespacehandling/) [get_NamespaceHandling](./get_namespacehandling/)() | एक मान लौटाता है जो दर्शाता है कि XML सामग्री लिखते समय [XmlWriter](../xmlwriter/) डुप्लिकेट नेेमस्पेस डिक्लेरेशन्स को हटाए या नहीं। डिफ़ॉल्ट व्यवहार यह है कि राइटर सभी नेेमस्पेस डिक्लेरेशन्स आउटपुट करे जो राइटर के नेेमस्पेस रिजॉल्वर में मौजूद हैं। |
| [String](../../system/string/) [get_NewLineChars](./get_newlinechars/)() | लाइन ब्रेकर के लिए उपयोग करने वाले कैरेक्टर स्ट्रिंग को लौटाता है। |
| [System::Xml::NewLineHandling](../newlinehandling/) [get_NewLineHandling](./get_newlinehandling/)() | एक मान लौटाता है जो दर्शाता है कि आउटपुट में लाइन ब्रेक को सामान्यीकृत किया जाना चाहिए या नहीं। |
| **bool** [get_NewLineOnAttributes](./get_newlineonattributes/)() | एक मान लौटाता है जो दर्शाता है कि एट्रिब्यूट्स को नई लाइन पर लिखा जाना चाहिए या नहीं। |
| **bool** [get_OmitXmlDeclaration](./get_omitxmldeclaration/)() | एक मान लौटाता है जो दर्शाता है कि XML घोषणा को छोड़ दिया जाना चाहिए या नहीं। |
| [XmlOutputMethod](../xmloutputmethod/) [get_OutputMethod](./get_outputmethod/)() | [XmlWriter](../xmlwriter/) आउटपुट को सीरियलाइज़ करने के लिए उपयोग किए जाने वाले मेथड को लौटाता है। |
| **bool** [get_WriteEndDocumentOnClose](./get_writeenddocumentonclose/)() | एक मान लौटाता है जो दर्शाता है कि [XmlWriter](../xmlwriter/) [XmlWriter::Close](../xmlwriter/close/) मेथड कॉल होने पर सभी अनक्लोज्ड एलिमेंट टैग्स में क्लोज़िंग टैग्स जोड़ देगा या नहीं। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स की हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स की क्लोनिंग को सक्षम करता है। |
| [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर्स को इनिशियलाइज़ करता है। |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस के साथ वैल्यू प्रकार के ऑब्जेक्ट की nullptr से तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए विशेषीकृत संस्करण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशेषीकृत संस्करण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [Reset](./reset/)() | सेटिंग्स क्लास के सदस्य को उनके डिफ़ॉल्ट मानों पर रीसेट करता है। |
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | एक मान सेट करता है जो दर्शाता है कि XML राइटर को यह जांचना चाहिए कि दस्तावेज़ के सभी कैरेक्टर W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets) के "2.2 Characters" सेक्शन के अनुरूप हैं या नहीं। |
| void [set_CloseOutput](./set_closeoutput/)(**bool**) | एक मान सेट करता है जो दर्शाता है कि [XmlWriter](../xmlwriter/) को [XmlWriter::Close](../xmlwriter/close/) मेथड कॉल होने पर बेस स्ट्रीम या TextWriter को भी बंद करना चाहिए या नहीं। |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | XML राइटर द्वारा XML आउटपुट की जांच के लिए जिस अनुरूपता स्तर को वह देखता है, उसे सेट करता है। |
| void [set_DoNotEscapeUriAttributes](./set_donotescapeuriattributes/)(**bool**) | एक मान सेट करता है जो दर्शाता है कि [XmlWriter](../xmlwriter/) URI विशेषताओं को एस्केप नहीं करता। |
| void [set_Encoding](./set_encoding/)(const [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\>\&) | उपयोग करने के लिए टेक्स्ट एन्कोडिंग के प्रकार को सेट करता है। |
| void [set_Indent](./set_indent/)(**bool**) | एक मान सेट करता है जो दर्शाता है कि एलिमेंट्स को इंडेंट किया जाना चाहिए या नहीं। |
| void [set_IndentChars](./set_indentchars/)(const [String](../../system/string/)\&) | इंडेंट करने के समय उपयोग करने वाले कैरेक्टर स्ट्रिंग को सेट करता है। यह सेटिंग तब उपयोग होती है जब [XmlWriterSettings::set_Indent](./set_indent/) मान **true** पर सेट हो। |
| void [set_NamespaceHandling](./set_namespacehandling/)([System::Xml::NamespaceHandling](../namespacehandling/)) | एक मान सेट करता है जो दर्शाता है कि XML सामग्री लिखते समय [XmlWriter](../xmlwriter/) डुप्लिकेट नेेमस्पेस डिक्लेरेशन्स को हटाए या नहीं। डिफ़ॉल्ट व्यवहार यह है कि राइटर सभी नेेमस्पेस डिक्लेरेशन्स आउटपुट करे जो राइटर के नेेमस्पेस रिजॉल्वर में मौजूद हैं। |
| void [set_NewLineChars](./set_newlinechars/)(const [String](../../system/string/)\&) | लाइन ब्रेक के लिए उपयोग करने वाले कैरेक्टर स्ट्रिंग को सेट करता है। |
| void [set_NewLineHandling](./set_newlinehandling/)([System::Xml::NewLineHandling](../newlinehandling/)) | एक मान सेट करता है जो दर्शाता है कि आउटपुट में लाइन ब्रेक को सामान्यीकृत किया जाना चाहिए या नहीं। |
| void [set_NewLineOnAttributes](./set_newlineonattributes/)(**bool**) | एक मान सेट करता है जो दर्शाता है कि एट्रिब्यूट्स को नई लाइन पर लिखा जाना चाहिए या नहीं। |
| void [set_OmitXmlDeclaration](./set_omitxmldeclaration/)(**bool**) | एक मान सेट करता है जो दर्शाता है कि XML घोषणा को छोड़ दिया जाना चाहिए या नहीं। |
| void [set_WriteEndDocumentOnClose](./set_writeenddocumentonclose/)(**bool**) | एक मान सेट करता है जो दर्शाता है कि [XmlWriter](../xmlwriter/) [XmlWriter::Close](../xmlwriter/close/) मेथड कॉल होने पर सभी अनक्लोज्ड एलिमेंट टैग्स में क्लोज़िंग टैग्स जोड़ देगा या नहीं। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्ग्युमेंट को वीक पॉइंटर (शेयर्ड के बजाय) सेट करता है। कंटेनरों में पॉइंटर को वीक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को वृद्धि करता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को वृद्धि करता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector उपयोग करें। |
| [XmlWriterSettings](./xmlwritersettings/)() | [XmlWriterSettings](./) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| virtual [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर्स को मुक्त करता है। |

## टाइपडिफ़्स

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | इस क्लास के एक इंस्टेंस के साझा पॉइंटर के लिए एक उपनाम। |

## टिप्पणी

इस क्लास के ऑब्जेक्ट को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार के इंस्टेंस को स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियां और/या असेर्शन फॉल्ट्स हो सकते हैं। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर को फ़ंक्शन्स को आर्ग्यूमेंट के रूप में पास करने के लिए उपयोग करें। 

## देखें

* क्लास [Object](../../system/object/)
* नेमस्पेस [System::Xml](../)
* लाइब्रेरी [Aspose.Slides](../../)