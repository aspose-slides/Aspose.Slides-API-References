---
title: CompareInfo
second_title: Aspose.Slides for C++ API संदर्भ
description: "संस्कृति-संवेदनशील स्ट्रिंग तुलना बनाता है। इस क्लास की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएं, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन त्रुटियाँ हो सकती हैं। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शनों में तर्क के रूप में पास करने के लिए करें।"
type: docs
weight: 40
url: /hi/system.globalization/compareinfo/
---
## CompareInfo क्लास

सांस्कृति-संवेदनशील स्ट्रिंग तुलना बनाता है। इस क्लास की वस्तुओं को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके आवंटित किया जाना चाहिए। कभी भी इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके न बनाएँ, क्योंकि इससे रन-टाइम त्रुटियाँ और/या असर्शन त्रुटियाँ होंगी। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में रखें और इस पॉइंटर का उपयोग करके इसे फ़ंक्शनों में तर्क के रूप में पास करें।

```cpp
class CompareInfo : public virtual System::Object
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | स्ट्रिंग्स की तुलना करता है। लागू नहीं किया गया। |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | स्ट्रिंग्स की तुलना करता है। केवल Ordinal और OrdinalIgnoreCase मोड समर्थित हैं। |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, int, const [String](../../system/string/)\&, int, int) const | एक स्ट्रिंग के एक भाग की दूसरी स्ट्रिंग के भाग से तुलना करता है। लागू नहीं किया गया। |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, const [String](../../system/string/)\&, int, [CompareOptions](../compareoptions/)) const | स्ट्रिंग तुलना विधियों का उपयोग करके एक स्ट्रिंग के अंत भाग की दूसरी स्ट्रिंग के अंत भाग से तुलना करता है। लागू नहीं किया गया। |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, const [String](../../system/string/)\&, int) const | एक स्ट्रिंग के अंत भाग की दूसरी स्ट्रिंग के अंत भाग से तुलना करता है। लागू नहीं किया गया। |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, int, const [String](../../system/string/)\&, int, int, [CompareOptions](../compareoptions/)) const | स्ट्रिंग तुलना विधियों का उपयोग करके एक स्ट्रिंग के भाग की दूसरी स्ट्रिंग के भाग से तुलना करता है। लागू नहीं किया गया। |
|  [CompareInfo](./compareinfo/)(const [CompareInfo](./)\&) | RTTI जानकारी। |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override |  |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमैंटिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली की फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं है, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली की फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं है, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| int [get_LCID](./get_lcid/)() const | कम्पेयरर से जुड़े संस्कृति का LCID प्राप्त करता है। |
| virtual [String](../../system/string/) [get_Name](./get_name/)() const | कम्पेयरर से जुड़े संस्कृति का नाम प्राप्त करता है। |
| [SortVersionPtr](../sortversionptr/) [get_Version](./get_version/)() const | सॉर्ट संस्करण के बारे में जानकारी प्राप्त करता है। |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(int, const [SharedPtr](../../system/sharedptr/)\<[Reflection::Assembly](../../system.reflection/assembly/)\>\&) | निर्दिष्ट असेंबली में स्ट्रिंग तुलना विधियों का उपयोग करके निर्दिष्ट संस्कृति से जुड़े [CompareInfo](./) को प्राप्त करता है। |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Reflection::Assembly](../../system.reflection/assembly/)\>\&) | निर्दिष्ट असेंबली में स्ट्रिंग तुलना विधियों का उपयोग करके निर्दिष्ट संस्कृति से जुड़े [CompareInfo](./) को प्राप्त करता है। |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(int) | निर्दिष्ट संस्कृति से जुड़े [CompareInfo](./) को प्राप्त करता है। |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(const [String](../../system/string/)\&) | निर्दिष्ट संस्कृति से जुड़े [CompareInfo](./) को प्राप्त करता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| virtual int [GetHashCode](./gethashcode/)(const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | निर्दिष्ट तुलना विकल्पों के आधार पर स्ट्रिंग हैश कोड प्राप्त करता है। |
| int [GetHashCode](./gethashcode/)() const override | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual [SortKeyPtr](../sortkeyptr/) [GetSortKey](./getsortkey/)(const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | निर्दिष्ट स्ट्रिंग के लिए निर्दिष्ट तुलना विकल्पों का उपयोग करके [SortKey](../sortkey/) ऑब्जेक्ट प्राप्त करता है। |
| virtual [SortKeyPtr](../sortkeyptr/) [GetSortKey](./getsortkey/)(const [String](../../system/string/)\&) const | निर्दिष्ट स्ट्रिंग के लिए [SortKey](../sortkey/) ऑब्जेक्ट प्राप्त करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) const | सबस्ट्रिंग की खोज करता है। |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, [CompareOptions](../compareoptions/)) const | सबस्ट्रिंग की खोज करता है। केवल Ordinal मोड समर्थित है। |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int, [CompareOptions](../compareoptions/)) const | सबस्ट्रिंग की खोज करता है। केवल Ordinal मोड समर्थित है। |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int, int, [CompareOptions](../compareoptions/)) const | निर्दिष्ट अक्षर की खोज करता है। केवल Ordinal मोड समर्थित है। |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int) const | सबस्ट्रिंग की खोज करता है। |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t) const | निर्दिष्ट अक्षर की खोज करता है। |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | सबस्ट्रिंग की खोज करता है। |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int, [CompareOptions](../compareoptions/)) const | निर्दिष्ट अक्षर की खोज करता है। केवल Ordinal मोड समर्थित है। |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int, int) const | निर्दिष्ट अक्षर की खोज करता है। |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int) const | निर्दिष्ट अक्षर की खोज करता है। |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | सबस्ट्रिंग की खोज करता है। केवल Ordinal मोड समर्थित है। |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, [CompareOptions](../compareoptions/)) const | निर्दिष्ट अक्षर की खोज करता है। केवल Ordinal मोड समर्थित है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| virtual **bool** [IsPrefix](./isprefix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | निर्दिष्ट तुलना विकल्पों का उपयोग करके जांचता है कि निर्दिष्ट स्ट्रिंग निर्दिष्ट प्रीफिक्स से शुरू होती है या नहीं। |
| virtual **bool** [IsPrefix](./isprefix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | जांचता है कि निर्दिष्ट स्ट्रिंग निर्दिष्ट प्रीफिक्स से शुरू होती है या नहीं। |
| static **bool** [IsSortable](./issortable/)(char16_t) | जांचता है कि निर्दिष्ट अक्षर सॉर्टेबल है या नहीं। |
| static **bool** [IsSortable](./issortable/)(const [String](../../system/string/)\&) | जांचता है कि निर्दिष्ट स्ट्रिंग सॉर्टेबल है या नहीं। |
| virtual **bool** [IsSuffix](./issuffix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | निर्दिष्ट तुलना विकल्पों का उपयोग करके जांचता है कि निर्दिष्ट स्ट्रिंग निर्दिष्ट सफ़िक्स पर समाप्त होती है या नहीं। |
| virtual **bool** [IsSuffix](./issuffix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | जांचता है कि निर्दिष्ट स्ट्रिंग निर्दिष्ट सफ़िक्स पर समाप्त होती है या नहीं। |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | निर्दिष्ट सबस्ट्रिंग की अंतिम उपस्थिति की खोज करता है। |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int, [CompareOptions](../compareoptions/)) const | निर्दिष्ट तुलना विकल्पों का उपयोग करके निर्दिष्ट सबस्ट्रिंग की अंतिम उपस्थिति की खोज करता है। |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int, int, [CompareOptions](../compareoptions/)) const | निर्दिष्ट तुलना विकल्पों का उपयोग करके निर्दिष्ट अक्षर की अंतिम उपस्थिति की खोज करता है। |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) const | निर्दिष्ट स्ट्रिंग की अंतिम उपस्थिति की खोज करता है। |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, [CompareOptions](../compareoptions/)) const | निर्दिष्ट तुलना विकल्पों का उपयोग करके निर्दिष्ट स्ट्रिंग की अंतिम उपस्थिति की खोज करता है। |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int, [CompareOptions](../compareoptions/)) const | निर्दिष्ट तुलना विकल्पों का उपयोग करके निर्दिष्ट अक्षर की अंतिम उपस्थिति की खोज करता है। |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int) const | निर्दिष्ट स्ट्रिंग की अंतिम उपस्थिति की खोज करता है। |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int) const | निर्दिष्ट अक्षर की अंतिम उपस्थिति की खोज करता है। |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | निर्दिष्ट तुलना विकल्पों का उपयोग करके निर्दिष्ट स्ट्रिंग की अंतिम उपस्थिति की खोज करता है। |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, [CompareOptions](../compareoptions/)) const | निर्दिष्ट तुलना विकल्पों का उपयोग करके निर्दिष्ट अक्षर की अंतिम उपस्थिति की खोज करता है। |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t) const | निर्दिष्ट अक्षर की अंतिम उपस्थिति की खोज करता है। |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int, int) const | निर्दिष्ट अक्षर की अंतिम उपस्थिति की खोज करता है। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉक करने का कार्यान्वयन करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासों की कॉपी कंस्ट्रक्शन सक्षम करता है। |
| [CompareInfo](./)\& [operator=](./operator_equal/)(const [CompareInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासों की कॉपी कंस्ट्रक्शन सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रीफ़रेंस-तुलना करता है वैल्यू टाइप ऑब्जेक्ट को nullptr के साथ। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) की विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) की स्ट्रिंग्स के मामले के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्यूमेंट को वीक पॉइंटर (शेयर्ड नहीं) सेट करता है। कंटेनरों में पॉइंटर को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| [String](../../system/string/) [ToString](./tostring/)() const override | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट का कार्यान्वयन करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने का कार्यान्वयन करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## देखें

* क्लास [Object](../../system/object/)
* नेमस्पेस [System::Globalization](../)
* लाइब्रेरी [Aspose.Slides](../../)