---
title: Cookie
second_title: Aspose.Slides for C++ API संदर्भ
description: "एक HTTP कुकी का प्रतिनिधित्व करता है। इस क्लास की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन त्रुटियाँ होंगी। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शनों में तर्क के रूप में पास करने के लिए करें।"
type: docs
weight: 1
url: /hi/system.net/cookie/
---
## Cookie क्लास

एक HTTP कुकी का प्रतिनिधित्व करता है। इस क्लास की वस्तुओं को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या असेर्शन त्रुटियाँ होंगी। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग करके इसे फ़ंक्शनों में तर्क के रूप में पास करें।

```cpp
class Cookie : public System::Object
```

## विधियाँ

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Cookie](./)\> [Clone](./clone/)() | वर्तमान इंस्टेंस की एक कॉपी बनाता है। |
|  [Cookie](./cookie/)() | एक नया इंस्टेंस बनाता है। |
|  [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/)) | एक नया इंस्टेंस बनाता है। |
|  [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | एक नया इंस्टेंस बनाता है। |
|  [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | एक नया इंस्टेंस बनाता है। |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | C# [Object.Equals](../../system/object/equals/) सेमैंटिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमैंटिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग प्वाइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालाँकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग प्वाइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालाँकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| [String](../../system/string/) [get_Comment](./get_comment/)() const | 'Comment' एट्रिब्यूट का मान प्राप्त करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_CommentUri](./get_commenturi/)() const | 'CommentURL' एट्रिब्यूट का मान प्राप्त करता है। |
| **bool** [get_Discard](./get_discard/)() const | 'Discard' एट्रिब्यूट का मान प्राप्त करता है। |
| [String](../../system/string/) [get_Domain](./get_domain/)() const | 'Domain' एट्रिब्यूट का मान प्राप्त करता है। |
| **bool** [get_DomainImplicit](./get_domainimplicit/)() | डोमेन के अप्रत्यक्ष होने का संकेत देने वाला मान प्राप्त करता है। |
| [String](../../system/string/) [get_DomainKey](./get_domainkey/)() const | डोमेन कुंजी लौटाता है। |
| **bool** [get_Expired](./get_expired/)() | कुकी के समाप्त होने का संकेत देने वाला मान प्राप्त करता है। |
| [DateTime](../../system/datetime/) [get_Expires](./get_expires/)() | 'Expires' एट्रिब्यूट का मान प्राप्त करता है। |
| **bool** [get_HttpOnly](./get_httponly/)() const | 'HttpOnly' एट्रिब्यूट का मान प्राप्त करता है। |
| [String](../../system/string/) [get_Name](./get_name/)() const | कुकी का नाम प्राप्त करता है। |
| [String](../../system/string/) [get_Path](./get_path/)() const | 'Path' एट्रिब्यूट का मान प्राप्त करता है। |
| **bool** [get_Plain](./get_plain/)() const | कुकी विनिर्देश 'Plain' है या नहीं, इसका संकेत देने वाला मान लौटाता है। |
| [String](../../system/string/) [get_Port](./get_port/)() const | 'Port' एट्रिब्यूट का मान प्राप्त करता है। |
| [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\> [get_PortList](./get_portlist/)() const | 'Port' एट्रिब्यूट के मानों का संग्रह लौटाता है। |
| **bool** [get_Secure](./get_secure/)() const | 'Secure' एट्रिब्यूट का मान प्राप्त करता है। |
| [DateTime](../../system/datetime/) [get_TimeStamp](./get_timestamp/)() const | कुकी बनाने का समय लौटाता है। |
| [String](../../system/string/) [get_Value](./get_value/)() const | कुकी का मान प्राप्त करता है। |
| [CookieVariant](../cookievariant/) [get_Variant](./get_variant/)() const | कुकी का विनिर्देश प्राप्त करता है। |
| **int32_t** [get_Version](./get_version/)() const | '[Version](../../system/version/)' एट्रिब्यूट का मान प्राप्त करता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| **int32_t** [GetHashCode](./gethashcode/)() const override | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| **bool** [InternalSetName](./internalsetname/)([String](../../system/string/)) | यह मेथड अन्य मेथड्स द्वारा मेथड नाम सेट करने के लिए कॉल किया जाता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार की इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लागू करके लॉक करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम टाइप्स की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr मामले के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_Comment](./set_comment/)([String](../../system/string/)) | 'Comment' एट्रिब्यूट का मान सेट करता है। |
| void [set_CommentUri](./set_commenturi/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | 'CommentURL' एट्रिब्यूट का मान सेट करता है। |
| void [set_Discard](./set_discard/)(**bool**) | 'Discard' एट्रिब्यूट का मान सेट करता है। |
| void [set_Domain](./set_domain/)([String](../../system/string/)) | 'Domain' एट्रिब्यूट का मान सेट करता है। |
| void [set_DomainImplicit](./set_domainimplicit/)(**bool**) | डोमेन के अप्रत्यक्ष होने का संकेत देने वाला मान सेट करता है। |
| void [set_Expired](./set_expired/)(**bool**) | कुकी के समाप्त होने का संकेत देने वाला मान सेट करता है। |
| void [set_Expires](./set_expires/)([DateTime](../../system/datetime/)) | 'Expires' एट्रिब्यूट का मान सेट करता है। |
| void [set_HttpOnly](./set_httponly/)(**bool**) | 'HttpOnly' एट्रिब्यूट का मान सेट करता है। |
| void [set_Name](./set_name/)([String](../../system/string/)) | कुकी का नाम सेट करता है। |
| void [set_Path](./set_path/)([String](../../system/string/)) | 'Path' एट्रिब्यूट का मान सेट करता है। |
| void [set_Port](./set_port/)([String](../../system/string/)) | 'Port' एट्रिब्यूट का मान सेट करता है। |
| void [set_Secure](./set_secure/)(**bool**) | 'Secure' एट्रिब्यूट का मान सेट करता है। |
| void [set_Value](./set_value/)([String](../../system/string/)) | कुकी का मान सेट करता है। |
| void [set_Variant](./set_variant/)([CookieVariant](../cookievariant/)) | कुकी का विनिर्देश सेट करता है। |
| void [set_Version](./set_version/)(**int32_t**) | '[Version](../../system/version/)' एट्रिब्यूट का मान सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्ग्युमेंट को एक weak पॉइंटर सेट करता है (shared के बजाय)। कंटेनर्स में पॉइंटर्स को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| [String](../../system/string/) [ToServerString](./toserverstring/)() | वर्तमान इंस्टेंस को स्ट्रिंग प्रतिनिधित्व में सीरियलाइज़ करता है। |
| [String](../../system/string/) [ToString](./tostring/)() const override | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| **bool** [VerifySetDefaults](./verifysetdefaults/)([CookieVariant](../cookievariant/), [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, **bool**, [String](../../system/string/), **bool**, **bool**) | डिफ़ॉल्ट एट्रिब्यूट्स के मानों को सत्यापित करता है और सेट करता है। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट को घटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## फ़ील्ड्स

| Field | Description |
| --- | --- |
| static [CommentAttributeName](./commentattributename/) | 'Comment' एट्रिब्यूट का नाम। |
| static [CommentUrlAttributeName](./commenturlattributename/) | 'CommentURL' एट्रिब्यूट का नाम। |
| static [DiscardAttributeName](./discardattributename/) | 'Discard' एट्रिब्यूट का नाम। |
| static [DomainAttributeName](./domainattributename/) | 'Domain' एट्रिब्यूट का नाम। |
| static [EqualsLiteral](./equalsliteral/) | एट्रिब्यूट के नाम और मान को अलग करने के लिए उपयोग किया जाने वाला सेपरेटर। |
| static [ExpiresAttributeName](./expiresattributename/) | 'Expires' एट्रिब्यूट का नाम। |
| static [HttpOnlyAttributeName](./httponlyattributename/) | 'HttpOnly' एट्रिब्यूट का नाम। |
| static [MaxAgeAttributeName](./maxageattributename/) | 'Max-Age' एट्रिब्यूट का नाम। |
| static [MaxSupportedVersion](./maxsupportedversion/) | समर्थित अधिकतम संस्करण। |
| static [MaxSupportedVersionString](./maxsupportedversionstring/) | समर्थित अधिकतम संस्करण का स्ट्रिंग प्रतिनिधित्व। |
| static [PathAttributeName](./pathattributename/) | 'Path' एट्रिब्यूट का नाम। |
| static [PortAttributeName](./portattributename/) | 'Port' एट्रिब्यूट का नाम। |
| static [PortSplitDelimiters](./portsplitdelimiters/) | 'Port' एट्रिब्यूट के मानों के लिए डिलिमिटर्स युक्त एरे। |
| static [QuotesLiteral](./quotesliteral/) | एट्रिब्यूट भागों को लपेटने के लिए उपयोग किया गया प्रतीक। |
| static [ReservedToName](./reservedtoname/) | कुकी नाम के लिए आरक्षित मान। |
| static [ReservedToValue](./reservedtovalue/) | कुकी मान के लिए आरक्षित मान। |
| static [SecureAttributeName](./secureattributename/) | 'Secure' एट्रिब्यूट का नाम। |
| static [SeparatorLiteral](./separatorliteral/) | एट्रिब्यूट सेपरेटर। |
| static [SpecialAttributeLiteral](./specialattributeliteral/) | विशेष एट्रिब्यूट नामों का प्रीफ़िक्स। |
| static [VersionAttributeName](./versionattributename/) | '[Version](../../system/version/)' एट्रिब्यूट का नाम। |

## देखें

* क्लास [Object](../../system/object/)
* नेमस्पेस [System::Net](../)
* लाइब्रेरी [Aspose.Slides](../../)