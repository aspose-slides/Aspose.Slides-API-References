---
title: WebHeaderCollection
second_title: Aspose.Slides for C++ API संदर्भ
description: "प्रोटोकॉल हेडर का संग्रह दर्शाता है। इस क्लास के ऑब्जेक्ट केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किए जाने चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम errors और/या assertion faults उत्पन्न हो सकते हैं। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर को फ़ंक्शनों में तर्क के रूप में पास करें।"
type: docs
weight: 482
url: /hi/system.net/webheadercollection/
---
## WebHeaderCollection क्लास

Represents the collection of the protocol headers. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) फ़ंक्शन. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class WebHeaderCollection : public System::Object
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| void [Add](./add/)([String](../../system/string/), [String](../../system/string/)) | निर्दिष्ट हेडर नाम और हेडर मान की जोड़ी को संग्रह में जोड़ता है। |
| void [Add](./add/)([HttpResponseHeader](../httpresponseheader/), [String](../../system/string/)) | निर्दिष्ट हेडर और हेडर मान की जोड़ी को संग्रह में जोड़ता है। |
| void [Add](./add/)([HttpRequestHeader](../httprequestheader/), [String](../../system/string/)) | निर्दिष्ट हेडर और हेडर मान की जोड़ी को संग्रह में जोड़ता है। |
| [System::ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [AllKeys](./allkeys/)() | संग्रह में संग्रहीत हेडर नामों का संग्रह लौटाता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमान्टिक्स का उपयोग करके करती है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# शैली के फ़्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# शैली के फ़्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| **int32_t** [get_Count](./get_count/)() const | संग्रह में तत्वों की संख्या लौटाता है। |
| [System::ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_Keys](./get_keys/)() | संग्रह में संग्रहीत हेडर नामों का संग्रह लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| [String](../../system/string/) [GetKey](./getkey/)(int) | निर्धारित इंडेक्स पर कुंजी लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [GetValues](./getvalues/)([String](../../system/string/)) | हेडर मानों का संग्रह लौटाता है। |
| [String](../../system/string/) [idx_get](./idx_get/)([HttpRequestHeader](../httprequestheader/)) | निर्दिष्ट अनुरोध के हेडर का उपयोग करके हेडर मान प्राप्त करता है। |
| [String](../../system/string/) [idx_get](./idx_get/)([HttpResponseHeader](../httpresponseheader/)) | निर्दिष्ट प्रतिक्रिया के हेडर का उपयोग करके हेडर मान प्राप्त करता है। |
| [String](../../system/string/) [idx_get](./idx_get/)([String](../../system/string/)) | निर्दिष्ट हेडर नाम का उपयोग करके हेडर मान प्राप्त करता है। |
| void [idx_set](./idx_set/)([HttpRequestHeader](../httprequestheader/), [String](../../system/string/)) | निर्दिष्ट हेडर का हेडर मान सेट करता है। |
| void [idx_set](./idx_set/)([HttpResponseHeader](../httpresponseheader/), [String](../../system/string/)) | निर्दिष्ट प्रतिक्रिया के हेडर का उपयोग करके हेडर मान सेट करता है। |
| void [idx_set](./idx_set/)([String](../../system/string/), [String](../../system/string/)) | निर्दिष्ट हेडर नाम का उपयोग करके हेडर मान सेट करता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक इंस्टेंस है या नहीं। C# 'is' ओपरेटर का समकक्ष। |
| static **bool** [IsRestricted](./isrestricted/)(const [String](../../system/string/)\&) | जाँचता है कि निर्दिष्ट HTTP हेडर को अनुरोध के लिए सेट किया जा सकता है या नहीं। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम प्रकारों को क्लोन करने को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी नहीं कॉपी करता, बस नया ऑब्जेक्ट प्रारंभ करता है और उपवर्गों की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी नहीं कॉपी करता, बस नया ऑब्जेक्ट प्रारंभ करता है और उपवर्गों की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr से रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशेषण। |
| void [Remove](./remove/)([String](../../system/string/)) | निर्दिष्ट हेडर नाम द्वारा हेडर हटाता है। |
| void [Remove](./remove/)([HttpResponseHeader](../httpresponseheader/)) | निर्दिष्ट प्रतिक्रिया के हेडर को हटाता है। |
| void [Remove](./remove/)([HttpRequestHeader](../httprequestheader/)) | निर्दिष्ट अनुरोध के हेडर को हटाता है। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [Set](./set/)([String](../../system/string/), [String](../../system/string/)) | निर्दिष्ट हेडर का मान सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट तर्क को एक कमजोर पॉइंटर (साझा के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को कमजोर मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| [String](../../system/string/) [ToString](./tostring/)() const override | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) संरचना को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट को घटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
|  [WebHeaderCollection](./webheadercollection/)() | एक नया इंस्टेंस बनाता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## संबंधित देखें

* क्लास [Object](../../system/object/)
* नेमस्पेस [System::Net](../)
* लाइब्रेरी [Aspose.Slides](../../)