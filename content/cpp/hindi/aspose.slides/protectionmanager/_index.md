---
title: ProtectionManager
second_title: Aspose.Slides for C++ API संदर्भ
description: प्रस्तुति पासवर्ड सुरक्षा प्रबंधन।
type: docs
weight: 4915
url: /hi/aspose.slides/protectionmanager/
---
## ProtectionManager क्लास


[Presentation](../presentation/) पासवर्ड संरक्षण प्रबंधन।

```cpp
class ProtectionManager : public Aspose::Slides::IProtectionManager
```

## विधियाँ

| विधि | वर्णन |
| --- | --- |
| **bool** [CheckWriteProtection](./checkwriteprotection/)([System::String](../../system/string/)) override | निर्धारित करता है कि क्या प्रस्तुतिकरण संशोधन के लिए पासवर्ड द्वारा संरक्षित है। |
| void [Encrypt](./encrypt/)([System::String](../../system/string/)) override | [Presentation](../presentation/) को निर्दिष्ट पासवर्ड के साथ एन्क्रिप्ट करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-स्टाइल फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-स्टाइल फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| **bool** [get_EncryptDocumentProperties](./get_encryptdocumentproperties/)() override | यह प्रॉपर्टी तभी अर्थपूर्ण होती है जब प्रस्तुतिकरण पासवर्ड द्वारा संरक्षित हो। यदि सत्य है तो दस्तावेज़ गुण प्रस्तुतिकरण फ़ाइल में एन्क्रिप्ट होते हैं। यदि असत्य है तो दस्तावेज़ गुण सार्वजनिक होते हैं जबकि प्रस्तुतिकरण एन्क्रिप्ट किया गया है। पढ़ें **bool**। |
| [System::String](../../system/string/) [get_EncryptionPassword](./get_encryptionpassword/)() override | प्रस्तुतिकरण एन्क्रिप्शन के लिए उपयोग होने वाला पासवर्ड प्राप्त करता है। केवल-पठनीय [System::String](../../system/string/)। |
| **bool** [get_IsEncrypted](./get_isencrypted/)() override | इस उदाहरण के एन्क्रिप्टेड होने को दर्शाने वाला मान प्राप्त करता है। केवल-पठनीय **bool**। |
| **bool** [get_IsOnlyDocumentPropertiesLoaded](./get_isonlydocumentpropertiesloaded/)() override | यह प्रॉपर्टी तभी अर्थपूर्ण होती है जब प्रस्तुतिकरण फ़ाइल पासवर्ड द्वारा संरक्षित हो और इस फ़ाइल की दस्तावेज़ गुण सार्वजनिक हों। सत्य मान का अर्थ है कि केवल दस्तावेज़ गुण एन्क्रिप्टेड प्रस्तुतिकरण फ़ाइल से पासवर्ड के बिना लोड होते हैं। असत्य मान का अर्थ है कि पूरी एन्क्रिप्टेड प्रस्तुतिकरण सही पासवर्ड के साथ लोड होती है, केवल दस्तावेज़ गुण नहीं। यदि प्रस्तुतिकरण एन्क्रिप्ट नहीं है तो प्रॉपर्टी मान हमेशा असत्य रहता है। यदि एन्क्रिप्टेड फ़ाइल के दस्तावेज़ गुण सार्वजनिक नहीं हैं तो प्रॉपर्टी मान हमेशा असत्य रहता है। यदि Presentation.EncryptDocumentProperties सत्य है तो IsOnlyDocumentPropertiesLoaded प्रॉपर्टी मान हमेशा असत्य रहता है। केवल-पठनीय **bool**। |
| **bool** [get_IsWriteProtected](./get_iswriteprotected/)() override | इस प्रस्तुतिकरण के लिखने से संरक्षित होने को दर्शाने वाला मान प्राप्त करता है। केवल-पठनीय **bool**। |
| **bool** [get_ReadOnlyRecommended](./get_readonlyrecommended/)() override | केवल-पठनीय सिफ़ारिश प्राप्त करता है। पढ़ें **bool**। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स की हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानार्थी। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँच करता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक उदाहरण है या नहीं। C# 'is' ऑपरेटर का समानार्थी। |
| void [Lock](../../system/object/lock/)() | C# lock() कथन की लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानार्थी। कस्टम प्रकारों की क्लोनिंग को सक्षम करता है। |
| [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू प्रकार के ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [RemoveEncryption](./removeencryption/)() override | एन्क्रिप्शन को हटाता है। |
| void [RemoveWriteProtection](./removewriteprotection/)() override | इस प्रस्तुतिकरण की लिखने से सुरक्षा हटाता है। |
| void [set_EncryptDocumentProperties](./set_encryptdocumentproperties/)(**bool**) override | यह प्रॉपर्टी तभी अर्थपूर्ण होती है जब प्रस्तुतिकरण पासवर्ड द्वारा संरक्षित हो। यदि सत्य है तो दस्तावेज़ गुण प्रस्तुतिकरण फ़ाइल में एन्क्रिप्ट होते हैं। यदि असत्य है तो दस्तावेज़ गुण सार्वजनिक होते हैं जबकि प्रस्तुतिकरण एन्क्रिप्ट किया गया है। लिखें **bool**। |
| void [set_ReadOnlyRecommended](./set_readonlyrecommended/)(**bool**) override | केवल-पठनीय सिफ़ारिश सेट करता है। लिखें **bool**। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्पलेट आर्ग्यूमेंट को एक कमजोर पॉइंटर (साझा के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को कमजोर मोड में स्विच करने की अनुमति देता है। |
| void [SetWriteProtection](./setwriteprotection/)([System::String](../../system/string/)) override | निर्दिष्ट पासवर्ड के साथ इस प्रस्तुतिकरण के लिए लिखने से सुरक्षा सेट करता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() कथन की अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## संबंधित देखें

* क्लास [IProtectionManager](../iprotectionmanager/)
* नेमस्पेस [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)