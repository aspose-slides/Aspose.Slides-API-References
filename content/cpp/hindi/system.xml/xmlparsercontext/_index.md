---
title: XmlParserContext
second_title: Aspose.Slides for C++ API संदर्भ
description: XmlReader द्वारा XML फ़्रैगमेंट को पार्स करने के लिए आवश्यक सभी संदर्भ जानकारी प्रदान करता है।
type: docs
weight: 391
url: /hi/system.xml/xmlparsercontext/
---
## XmlParserContext क्लास


[XmlReader](../xmlreader/) द्वारा XML फ्रैग्मेंट को पार्स करने के लिए आवश्यक सभी संदर्भ जानकारी प्रदान करता है।

```cpp
class XmlParserContext : public System::Object
```

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमैन्टिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | बेस URI लौटाता है। |
| [String](../../system/string/) [get_DocTypeName](./get_doctypename/)() | डॉक्युमेंट टाइप डिक्लेरेशन का नाम लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | एन्कोडिंग प्रकार लौटाता है। |
| [String](../../system/string/) [get_InternalSubset](./get_internalsubset/)() | आंतरिक DTD उपसमुच्चय लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\> [get_NamespaceManager](./get_namespacemanager/)() | [XmlNamespaceManager](../xmlnamespacemanager/) लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | ऑटोमेटेड स्ट्रिंग्स को एटॉमिक करने के लिए उपयोग किए जाने वाले [XmlNameTable](../xmlnametable/) को लौटाता है। ऑटोमेटेड स्ट्रिंग्स के बारे में अधिक जानकारी के लिए [XmlNameTable](../xmlnametable/) देखें। |
| [String](../../system/string/) [get_PublicId](./get_publicid/)() | पब्लिक आइडेंटिफ़ायर लौटाता है। |
| [String](../../system/string/) [get_SystemId](./get_systemid/)() | सिस्टम आइडेंटिफ़ायर लौटाता है। |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | वर्तमान **xml:lang** स्कोप लौटाता है। |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() | वर्तमान **xml:space** स्कोप लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानार्थी। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानार्थी। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानार्थी। कस्टम टाइप्स का क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Value टाइप ऑब्जेक्ट को nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकृत संस्करण स्ट्रिंग और nullptr के केस के लिए। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकृत संस्करण स्ट्रिंग्स के केस के लिए। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट घटाता है। |
| void [set_BaseURI](./set_baseuri/)(const [String](../../system/string/)\&) | बेस URI सेट करता है। |
| void [set_DocTypeName](./set_doctypename/)(const [String](../../system/string/)\&) | डॉक्युमेंट टाइप डिक्लेरेशन का नाम सेट करता है। |
| void [set_Encoding](./set_encoding/)(const [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\>\&) | एन्कोडिंग प्रकार सेट करता है। |
| void [set_InternalSubset](./set_internalsubset/)(const [String](../../system/string/)\&) | आंतरिक DTD उपसमुच्चय सेट करता है। |
| void [set_NamespaceManager](./set_namespacemanager/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | [XmlNamespaceManager](../xmlnamespacemanager/) सेट करता है। |
| void [set_NameTable](./set_nametable/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | [XmlNameTable](../xmlnametable/) सेट करता है जो स्ट्रिंग्स को एटॉमीज़ करने में उपयोग होता है। एटॉमीज़्ड स्ट्रिंग्स के बारे में अधिक जानकारी के लिए [XmlNameTable](../xmlnametable/) देखें। |
| void [set_PublicId](./set_publicid/)(const [String](../../system/string/)\&) | पब्लिक आइडेंटिफ़ायर सेट करता है। |
| void [set_SystemId](./set_systemid/)(const [String](../../system/string/)\&) | सिस्टम आइडेंटिफ़ायर सेट करता है। |
| void [set_XmlLang](./set_xmllang/)(const [String](../../system/string/)\&) | वर्तमान **xml:lang** स्कोप सेट करता है। |
| void [set_XmlSpace](./set_xmlspace/)([System::Xml::XmlSpace](../xmlspace/)) | वर्तमान **xml:space** स्कोप सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्पलेट आर्ग्युमेंट को वीक पॉइंटर (शेयर्ड के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को वीक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट घटाता है और लौटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कन्स्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट घटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
|  [XmlParserContext](./xmlparsercontext/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&, const [String](../../system/string/)\&, [System::Xml::XmlSpace](../xmlspace/)) | [XmlParserContext](./) क्लास की नई इंस्टेंस को निर्दिष्ट [XmlNameTable](../xmlnametable/), [XmlNamespaceManager](../xmlnamespacemanager/), **xml:lang**, और **xml:space** मानों के साथ इनिशियलाइज़ करता है। |
|  [XmlParserContext](./xmlparsercontext/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&, const [String](../../system/string/)\&, [System::Xml::XmlSpace](../xmlspace/), const [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\>\&) | [XmlParserContext](./) क्लास की नई इंस्टेंस को निर्दिष्ट [XmlNameTable](../xmlnametable/), [XmlNamespaceManager](../xmlnamespacemanager/), **xml:lang**, **xml:space**, और एन्कोडिंग के साथ इनिशियलाइज़ करता है। |
|  [XmlParserContext](./xmlparsercontext/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, [System::Xml::XmlSpace](../xmlspace/)) | [XmlParserContext](./) क्लास की नई इंस्टेंस को निर्दिष्ट [XmlNameTable](../xmlnametable/), [XmlNamespaceManager](../xmlnamespacemanager/), बेस URI, **xml:lang**, **xml:space**, और डॉक्युमेंट टाइप मानों के साथ इनिशियलाइज़ करता है। |
|  [XmlParserContext](./xmlparsercontext/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, [System::Xml::XmlSpace](../xmlspace/), const [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\>\&) | [XmlParserContext](./) क्लास की नई इंस्टेंस को निर्दिष्ट [XmlNameTable](../xmlnametable/), [XmlNamespaceManager](../xmlnamespacemanager/), बेस URI, **xml:lang**, **xml:space**, एन्कोडिंग, और डॉक्युमेंट टाइप मानों के साथ इनिशियलाइज़ करता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## टाइपडिफ़

| टाइपडिफ़ | विवरण |
| --- | --- |
| [Ptr](./ptr/) | इस क्लास की इंस्टेंस के साझा पॉइंटर का एक उपनाम। |

## टिप्पणी

इस क्लास के ऑब्जेक्ट्स को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार की इंस्टेंस को स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन फॉल्ट्स हो सकते हैं। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शनों को आर्ग्युमेंट के रूप में पास करने के लिए करें। 

## देखिए

* क्लास [Object](../../system/object/)
* नेमस्पेस [System::Xml](../)
* लाइब्रेरी [Aspose.Slides](../../)