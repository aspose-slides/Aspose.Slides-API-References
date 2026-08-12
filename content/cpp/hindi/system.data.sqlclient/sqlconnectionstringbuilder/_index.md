---
title: SqlConnectionStringBuilder
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "SQL-आधारित कनेक्शन बिल्डर। इस वर्ग की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन दोष हो सकते हैं। हमेशा इस वर्ग को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर को फ़ंक्शन को तर्क के रूप में पास करने के लिए उपयोग करें।"
type: docs
weight: 1
url: /hi/system.data.sqlclient/sqlconnectionstringbuilder/
---
## SqlConnectionStringBuilder वर्ग

SQL-आधारित कनेक्शन बिल्डर। इस वर्ग की वस्तुओं को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके आवंटित किया जाना चाहिए। इस प्रकार के उदाहरण को स्टैक पर या ऑपरेटर new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियों और/या असर्शन दोष उत्पन्न हो सकते हैं। हमेशा इस वर्ग को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर को फ़ंक्शन को तर्क के रूप में पास करने के लिए उपयोग करें।

```cpp
class SqlConnectionStringBuilder : public System::Data::Common::DbConnectionStringBuilder
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमेंटिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली की फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली की फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual [String](../../system/string/) [get_ConnectionString](../../system.data.common/dbconnectionstringbuilder/get_connectionstring/)() const | पूरा कनेक्शन स्ट्रिंग प्राप्त करता है। |
| [String](../../system/string/) [get_DataSource](./get_datasource/)() const | डेटा स्रोत प्राप्त करता है (उदा. होस्टनाम और पोर्ट)। |
| **bool** [get_Encrypt](./get_encrypt/)() const | जाँचता है कि क्या लाइन पर एन्क्रिप्शन सक्षम है। |
| [String](../../system/string/) [get_InitialCatalog](./get_initialcatalog/)() const | कनेक्शन से संबद्ध डेटाबेस का नाम प्राप्त करता है। |
| [String](../../system/string/) [get_NetworkLibrary](./get_networklibrary/)() const | प्रयुक्त नेटवर्क लाइब्रेरी का नाम प्राप्त करता है। |
| [String](../../system/string/) [get_Password](./get_password/)() const | डेटाबेस से कनेक्ट होने के लिए उपयोग किया गया पासवर्ड प्राप्त करता है। |
| **bool** [get_TrustServerCertificate](./get_trustservercertificate/)() const | जाँचता है कि कनेक्शन ट्रस्ट सर्वर प्रमाणपत्र का उपयोग करके संरक्षित है या नहीं। |
| [String](../../system/string/) [get_UserID](./get_userid/)() const | कनेक्शन के लिए उपयोग किया गया यूज़र आईडी प्राप्त करता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | वस्तु से सम्बद्ध रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानार्थी। कस्टम वस्तुओं की हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | वस्तु का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानार्थी। |
| [Object::ptr](../../system/object/ptr/) [idx_get](./idx_get/)([String](../../system/string/)) override | RTTI जानकारी। |
| [Object::ptr](../../system/object/ptr/) [idx_set](./idx_set/)([String](../../system/string/), [Object::ptr](../../system/object/ptr/)) override | कीड ऑब्जेक्ट सेट करता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानार्थी। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानार्थी। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | वस्तु बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, सिर्फ नई वस्तु को इनिशियलाइज़ करता है और सबक्लासेज़ के कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, सिर्फ नई वस्तु को इनिशियलाइज़ करता है और सबक्लासेज़ के कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | वस्तुओं की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | वस्तुओं की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंटर को घटाता है। |
| virtual void [set_ConnectionString](../../system.data.common/dbconnectionstringbuilder/set_connectionstring/)([String](../../system/string/)) | पूरा कनेक्शन स्ट्रिंग सेट करता है। |
| void [set_DataSource](./set_datasource/)(const [String](../../system/string/)\&) | डेटा स्रोत प्राप्त करता है (उदा. होस्टनाम और पोर्ट)। |
| void [set_Encrypt](./set_encrypt/)(**bool**) | एन्क्रिप्शन को ऑन या ऑफ टॉगल करता है। |
| void [set_InitialCatalog](./set_initialcatalog/)(const [String](../../system/string/)\&) | कनेक्शन से संबद्ध डेटाबेस का नाम सेट करता है। |
| void [set_NetworkLibrary](./set_networklibrary/)(const [String](../../system/string/)\&) | उपयोग करने के लिए नेटवर्क लाइब्रेरी का चयन करता है। |
| void [set_Password](./set_password/)(const [String](../../system/string/)\&) | डेटाबेस से कनेक्ट होने के लिए उपयोग किया जाने वाला पासवर्ड सेट करता है। |
| void [set_TrustServerCertificate](./set_trustservercertificate/)(**bool**) | निर्धारित करता है कि कनेक्शन ट्रस्ट सर्वर प्रमाणपत्र का उपयोग करके संरक्षित है या नहीं। |
| void [set_UserID](./set_userid/)(const [String](../../system/string/)\&) | कनेक्शन के लिए उपयोग करने वाला यूज़र आईडी सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nth टेम्प्लेट आर्ग्युमेंट को एक वीक पॉइंटर (साझा के बजाय) सेट करता है। कंटेनरों में पॉइंटर को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंटर को बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंटर को घटाता है और लौटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंटर को बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंटर को घटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## देखें

* वर्ग [DbConnectionStringBuilder](../../system.data.common/dbconnectionstringbuilder/)
* नामस्थान [System::Data::SqlClient](../)
* लाइब्रेरी [Aspose.Slides](../../)