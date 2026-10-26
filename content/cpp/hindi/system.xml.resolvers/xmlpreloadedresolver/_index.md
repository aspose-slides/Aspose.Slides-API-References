---
title: XmlPreloadedResolver
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: एक क्लास को दर्शाता है जो DTDs या XML streams के साथ कैश को पूर्व-लोड करने के लिए उपयोग की जाती है।
type: docs
weight: 1
url: /hi/system.xml.resolvers/xmlpreloadedresolver/
---
## XmlPreloadedResolver क्लास

एक क्लास का प्रतिनिधित्व करता है जो DTDs या XML streams के साथ कैश को पूर्व-लोड करने के लिए उपयोग किया जाता है।

```cpp
class XmlPreloadedResolver : public System::Xml::XmlResolver
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| void [Add](./add/)(const [SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | एक बाइट ऐरे को [XmlPreloadedResolver](./) स्टोर में जोड़ता है और इसे एक URI से मैप करता है। यदि स्टोर में पहले से ही समान URI के लिए एक मैपिंग मौजूद है, तो मौजूदा मैपिंग ओवरराइड कर दी जाती है। |
| void [Add](./add/)(const [SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | एक बाइट ऐरे को [XmlPreloadedResolver](./) स्टोर में जोड़ता है और इसे एक URI से मैप करता है। यदि स्टोर में पहले से ही समान URI के लिए एक मैपिंग मौजूद है, तो मौजूदा मैपिंग ओवरराइड कर दी जाती है। |
| void [Add](./add/)(const [SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | एक स्ट्रीम को [XmlPreloadedResolver](./) स्टोर में जोड़ता है और इसे एक URI से मैप करता है। यदि स्टोर में पहले से ही समान URI के लिए एक मैपिंग मौजूद है, तो मौजूदा मैपिंग ओवरराइड कर दी जाती है। |
| void [Add](./add/)(const [SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>\&, const [String](../../system/string/)\&) | एक स्ट्रिंग को पूर्व-लोडेड डेटा के साथ [XmlPreloadedResolver](./) स्टोर में जोड़ता है और इसे एक URI से मैप करता है। यदि स्टोर में पहले से ही समान URI के लिए एक मैपिंग मौजूद है, तो मौजूदा मैपिंग ओवरराइड कर दी जाती है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमैटिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफरेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-स्टाइल फ़्लोटिंग प्वाइंट तुलना को एम्यूलेट करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान, सहित NaN, के बराबर नहीं है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-स्टाइल फ़्लोटिंग प्वाइंट तुलना को एम्यूलेट करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान, सहित NaN, के बराबर नहीं है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>\>\> [get_PreloadedUris](./get_preloadeduris/)() | पूर्व-लोडेड URI का संग्रह लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफरेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetEntity](./getentity/)([SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, [String](../../system/string/), const [TypeInfo](../../system/typeinfo/)\&) override | URI को वास्तविक रिसोर्स वाले ऑब्जेक्ट से मैप करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट के वास्तविक प्रकार को प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# ‘is’ ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का प्रयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सब-क्लासेज़ के कॉपी कन्स्ट्रक्टिंग को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सब-क्लासेज़ के कॉपी कन्स्ट्रक्टिंग को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफरेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफरेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट को nullptr के साथ रेफरेंस-कम्पेयर करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के केस के लिये [Object::ReferenceEquals](../../system/object/referenceequals/) का स्पेशलाइज़ेशन। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स के केस के लिये [Object::ReferenceEquals](../../system/object/referenceequals/) का स्पेशलाइज़ेशन। |
| void [Remove](./remove/)(const [SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>\&) | [XmlPreloadedResolver](./) में से उस URI से संबंधित डेटा को हटाता है। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफरेंस काउंट को घटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [ResolveUri](./resolveuri/)([SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, [String](../../system/string/)) override | बेस और रिलेटिव URI से पूर्ण URI को हल करता है। |
| void [set_Credentials](./set_credentials/)([SharedPtr](../../system/sharedptr/)\<[Net::ICredentials](../../system.net/icredentials/)\>) override | अंतर्निहित [Net::WebRequest](../../system.net/webrequest/) को प्रामाणिक करने के लिये प्रयुक्त क्रेडेंशियल्स को सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n-वें टेम्पलेट आर्ग्यूमेंट को वीक पॉइंटर (शेयर्ड नहीं) सेट करता है। कंटेनर्स में पॉइंटर्स को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफरेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफरेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफरेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| **bool** [SupportsType](./supportstype/)([SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, const [TypeInfo](../../system/typeinfo/)\&) override | निर्धारित करता है कि रेज़ोल्वर सिर्फ Stream के अलावा अन्य Types का समर्थन करता है या नहीं। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफरेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफरेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
|  [XmlPreloadedResolver](./xmlpreloadedresolver/)() | नया [XmlPreloadedResolver](./) क्लास इंस्टेंस इनिशियलाइज़ करता है। |
|  [XmlPreloadedResolver](./xmlpreloadedresolver/)([XmlKnownDtds](../xmlknowndtds/)) | निर्दिष्ट पूर्व-लोडेड वेल-नॉन् DTDs के साथ नया [XmlPreloadedResolver](./) क्लास इंस्टेंस इनिशियलाइज़ करता है। |
|  [XmlPreloadedResolver](./xmlpreloadedresolver/)(const [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>\&) | निर्दिष्ट फॉल्बैक रिज़ॉल्वर के साथ नया [XmlPreloadedResolver](./) क्लास इंस्टेंस इनिशियलाइज़ करता है। |
|  [XmlPreloadedResolver](./xmlpreloadedresolver/)(const [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>\&, [XmlKnownDtds](../xmlknowndtds/)) | निर्दिष्ट फॉल्बैक रिज़ॉल्वर और पूर्व-लोडेड वेल-नॉन् DTDs के साथ नया [XmlPreloadedResolver](./) क्लास इंस्टेंस इनिशियलाइज़ करता है। |
|  [XmlPreloadedResolver](./xmlpreloadedresolver/)(const [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>\&, [XmlKnownDtds](../xmlknowndtds/), const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>\>\>\&) | निर्दिष्ट फॉल्बैक रिज़ॉल्वर, पूर्व-लोडेड वेल-नॉन् DTDs, और URI इक़्वैलिटी कम्पेयरर के साथ नया [XmlPreloadedResolver](./) क्लास इंस्टेंस इनिशियलाइज़ करता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |
## टाइपडिफ़

| टाइपडिफ़ | विवरण |
| --- | --- |
| [Ptr](./ptr/) | इस क्लास के किसी इंस्टेंस के लिए साझा पॉइंटर का उपनाम। |
## टिप्पणियाँ

इस क्लास की ऑब्जेक्ट्स को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार के इंस्टेंस को स्टैक पर या operator new का उपयोग करके कभी नहीं बनाना चाहिए, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन फॉल्ट्स हो सकते हैं। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का प्रयोग फ़ंक्शन्स में तर्क के रूप में पास करने के लिए करें। 

## और देखें

* क्लास [XmlResolver](../../system.xml/xmlresolver/)
* नेमस्पेस [System::Xml::Resolvers](../)
* लाइब्रेरी [Aspose.Slides](../../)