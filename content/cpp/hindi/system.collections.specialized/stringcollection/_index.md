---
title: StringCollection
second_title: Aspose.Slides for C++ API संदर्भ
description: "स्ट्रिंग्स की अनुक्रमित सूची। इस वर्ग की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार के इंस्टेंस को स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन फ़ॉल्ट्स हो सकते हैं। हमेशा इस वर्ग को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग इसे फ़ंक्शनों को तर्क के रूप में पास करने के लिए करें।"
type: docs
weight: 27
url: /hi/system.collections.specialized/stringcollection/
---
## StringCollection क्लास

Indexed list of strings. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class StringCollection : public System::Collections::Generic::IEnumerable<System::String>
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| int [Add](./add/)(const [System::String](../../system/string/)\&) | सूची के अंत में मान जोड़ता है। |
| void [AddRange](./addrange/)(const [ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>\&) | कंटेनर में तत्व जोड़ता है। |
| [iterator](./iterator/) [begin](./begin/)() | कंटेनर के पहले तत्व के लिए एक इटरटर लौटाता है। यदि कंटेनर खाली है, तो लौटाया गया इटरटर [end()](./end/) के बराबर होगा। |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | const-योग्य कंटेनर के पहले तत्व के लिए एक इटरटर लौटाता है। यदि कंटेनर खाली है, तो लौटाया गया इटरटर [end()](./end/) के बराबर होगा। |
| [const_iterator](./const_iterator/) [cbegin](./cbegin/)() const | कंटेनर के पहले const-योग्य तत्व के लिए एक इटरटर लौटाता है। यदि कंटेनर खाली है, तो लौटाया गया इटरटर [cend()](./cend/) के बराबर होगा। |
| [const_iterator](./const_iterator/) [cend](./cend/)() const | कंटेनर के अंतिम तत्व के बाद के तत्व के लिए एक इटरटर लौटाता है। यह तत्व एक प्लेसहोल्डर के रूप में कार्य करता है; इसका एक्सेस करने का प्रयास अनिर्दिष्ट व्यवहार देगा। |
| void [Clear](./clear/)() | सभी तत्वों को हटाता है। |
| **bool** [Contains](./contains/)(const [System::String](../../system/string/)\&) const | जांचता है कि क्या विशेष स्ट्रिंग कंटेनर में मौजूद है। |
| void [CopyTo](./copyto/)(const [ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>\&, const **int32_t**) const | तत्वों को मौजूदा एरे में कॉपी करता है। |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | रिवर्स्ड कंटेनर के पहले तत्व के लिए एक रिवर्स इटरटर लौटाता है। यह गैर-रिवर्स्ड कंटेनर के अंतिम तत्व के अनुरूप है। यदि कंटेनर खाली है, तो लौटाया गया इटरटर [crend()](./crend/) के बराबर होगा। |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | रिवर्स्ड कंटेनर के अंतिम तत्व के बाद के तत्व के लिए एक रिवर्स इटरटर लौटाता है। यह गैर-रिवर्स्ड कंटेनर के पहले तत्व से पहले के तत्व के अनुरूप है। यह तत्व एक प्लेसहोल्डर के रूप में कार्य करता है; इसका एक्सेस करने का प्रयास अनिर्दिष्ट व्यवहार देता है। |
| std::vector\<[System::String](../../system/string/)\>\& [data](./data/)() | आंतरिक डेटा संरचना अभिगामी। |
| const std::vector\<[System::String](../../system/string/)\>\& [data](./data/)() const | आंतरिक डेटा संरचना अभिगामी। |
| [iterator](./iterator/) [end](./end/)() | कंटेनर के अंतिम तत्व के बाद के तत्व के लिए एक इटरटर लौटाता है। यह तत्व एक प्लेसहोल्डर के रूप में कार्य करता है; इसका एक्सेस करने का प्रयास अनिर्दिष्ट व्यवहार देगा। |
| [const_iterator](./const_iterator/) [end](./end/)() const | const-योग्य कंटेनर के अंतिम तत्व के बाद के तत्व के लिए एक इटरटर लौटाता है। यह तत्व एक प्लेसहोल्डर के रूप में कार्य करता है; इसका एक्सेस करने का प्रयास अनिर्दिष्ट व्यवहार देगा। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफरेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| int [get_Count](./get_count/)() const | कलेक्शन में तत्वों की संख्या प्राप्त करता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| [SharedPtr](../../system/sharedptr/)\<[Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[System::String](../../system/string/)\>\> [GetEnumerator](./getenumerator/)() override | वर्तमान कलेक्शन के माध्यम से इटरेट करने वाला एन्यूमरेटर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स की हैशिंग को सक्षम बनाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| [System::String](../../system/string/) [idx_get](./idx_get/)(int) const | निर्दिष्ट स्थिति पर मान प्राप्त करता है। |
| void [idx_set](./idx_set/)(int, const [System::String](../../system/string/)\&) | निर्दिष्ट स्थिति पर मान सेट करता है। |
| int [IndexOf](./indexof/)(const [System::String](../../system/string/)\&) const | कंटेनर में विशिष्ट स्ट्रिंग की खोज करता है। |
| void [Insert](./insert/)(int, const [System::String](../../system/string/)\&) | कंटेनर में विशिष्ट मान को सम्मिलित करता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | एक सीक्वेंस पर एक्क्युम्यूलेटर फ़ंक्शन लागू करता है। |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | निर्धारित करता है कि क्या सीक्वेंस के सभी तत्व किसी शर्त को संतुष्ट करते हैं। |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | निर्धारित करता है कि सीक्वेंस में कोई भी तत्व है या नहीं। |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | निर्धारित करता है कि क्या सीक्वेंस में कोई तत्व मौजूद है या शर्त को संतुष्ट करता है। |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | संख्यात्मक मानों की एक सीक्वेंस का औसत गणना करता है। |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | इनपुट सीक्वेंस के प्रत्येक तत्व पर ट्रांसफ़ॉर्म फ़ंक्शन लागू करके प्राप्त मानों की सीक्वेंस का औसत गणना करता है। |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | तत्वों को निर्दिष्ट प्रकार में कास्ट करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | दो सीक्वेंस को जोड़ता है। |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | निर्धारित करता है कि सीक्वेंस में निर्दिष्ट मान मौजूद है या नहीं। |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | सीक्वेंस में तत्वों की संख्या लौटाता है (प्रत्यक्ष गिनती द्वारा गणना किया गया)। |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | निर्दिष्ट शर्त को संतुष्ट करने वाले सीक्वेंस के तत्वों की संख्या लौटाता है। |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | सीक्वेंस में निर्दिष्ट इंडेक्स पर तत्व लौटाता है। |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | सीक्वेंस में निर्दिष्ट इंडेक्स पर तत्व लौटाता है। |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | सीक्वेंस का पहला तत्व लौटाता है। |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | निर्दिष्ट शर्त को संतुष्ट करने वाले सीक्वेंस का पहला तत्व लौटाता है। |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | सीक्वेंस का पहला तत्व लौटाता है, या यदि सीक्वेंस खाली है तो डिफ़ॉल्ट मान लौटाता है। |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | शर्त को संतुष्ट करने वाला सीक्वेंस का पहला तत्व लौटाता है या यदि ऐसा कोई तत्व न मिले तो डिफ़ॉल्ट मान लौटाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | सीक्वेंस के तत्वों को समूहित करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | सीक्वेंस के तत्वों को समूहित करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | सीक्वेंस का अंतिम तत्व लौटाता है। |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | सीक्वेंस का अंतिम तत्व लौटाता है, या यदि सीक्वेंस खाली है तो डिफ़ॉल्ट मान। |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | जनरिक सीक्वेंस के प्रत्येक तत्व पर ट्रांसफ़ॉर्म फ़ंक्शन लागू करता है और अधिकतम परिणाम मान लौटाता है। |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | जनरिक सीक्वेंस के प्रत्येक तत्व पर ट्रांसफ़ॉर्म फ़ंक्शन लागू करता है और न्यूनतम परिणाम मान लौटाता है। |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | निर्दिष्ट प्रकार के आधार पर सीक्वेंस के तत्वों को फ़िल्टर करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | की सिलेक्टर द्वारा चयनित कुंजी मानों के आधार पर सीक्वेंस के तत्वों को आरोही क्रम में क्रमबद्ध करता है। |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | की सिलेक्टर द्वारा चयनित कुंजी मानों के आधार पर सीक्वेंस के तत्वों को अवरोही क्रम में क्रमबद्ध करता है। |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | सीक्वेंस में तत्वों का क्रम उल्टा करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | सीक्वेंस के तत्वों को ट्रांसफ़ॉर्म करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | सीक्वेंस के प्रत्येक तत्व को उसके इंडेक्स को सम्मिलित करके नई रूप में ट्रांसफ़ॉर्म करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | सीक्वेंस के प्रत्येक तत्व को प्रोजेक्ट करता है और परिणामी सीक्वेंस को एक ही सीक्वेंस में संयोजित करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | सीक्वेंस की शुरुआत से निर्दिष्ट संख्या में क्रमबद्ध तत्वों को छोड़ता है और शेष भाग लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | सीक्वेंस की शुरुआत से निर्दिष्ट संख्या में क्रमबद्ध तत्वों को लौटाता है। |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | सीक्वेंस से एक एरे बनाता है। |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | सीक्वेंस से एक List<T> बनाता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | निर्दिष्ट प्रेडिकेट के आधार पर सीक्वेंस को फ़िल्टर करता है। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉक करने के लिए लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्टिंग को सक्षम करता है। |
| [System::String](../../system/string/)\& [operator[]](./operator[]/)(int) | एक्सेसर फ़ंक्शन। |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | रिवर्स्ड कंटेनर के पहले तत्व के लिए एक रिवर्स इटरटर लौटाता है। यह गैर-रिवर्स्ड कंटेनर के अंतिम तत्व के अनुरूप है। यदि कंटेनर खाली है, तो लौटाया गया इटरटर [rend()](./rend/) के बराबर होगा। |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | रिवर्स्ड कंटेनर के पहले तत्व के लिए एक रिवर्स इटरटर लौटाता है। यह गैर-रिवर्स्ड कंटेनर के अंतिम तत्व के अनुक्रम में है। यदि कंटेनर खाली है, तो लौटाया गया इटरटर [rend()](./rend/) के बराबर होगा। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) की स्ट्रिंग और nullptr के केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) की स्ट्रिंग्स के केस के लिए विशेषीकरण। |
| void [Remove](./remove/)(const [System::String](../../system/string/)\&) | निर्दिष्ट स्ट्रिंग की पहली घटना को हटाता है। |
| void [RemoveAt](./removeat/)(int) | निर्दिष्ट स्थिति पर तत्व को हटाता है। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | रिवर्स्ड कंटेनर के अंतिम तत्व के बाद के तत्व के लिए एक रिवर्स इटरटर लौटाता है। यह गैर-रिवर्स्ड कंटेनर के पहले तत्व से पहले के तत्व के अनुरूप है। यह तत्व एक प्लेसहोल्डर के रूप में कार्य करता है; इसका एक्सेस करने का प्रयास अनिर्दिष्ट व्यवहार देता है। |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | रिवर्स्ड कंटेनर के अंतिम तत्व के बाद के तत्व के लिए एक रिवर्स इटरटर लौटाता है। यह गैर-रिवर्स्ड कंटेनर के पहले तत्व से पहले के तत्व के अनुरूप है। यह तत्व एक प्लेसहोल्डर के रूप में कार्य करता है; इसका एक्सेस करने का प्रयास अनिर्दिष्ट व्यवहार देता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्पलेट आर्गुमेंट को एक कमजोर पोइंटर (shared के बजाय) सेट करता है। कंटेनर में पोइंटरों को weak मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
|  [StringCollection](./stringcollection/)() | खाली स्ट्रिंग कलेक्शन बनाता है। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने के लिए लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| System::Details::VirtualizedIteratorBase\<[System::String](../../system/string/)\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | वर्तमान कंटेनर के begin const इटरटर के इम्प्लीमेंटेशन को प्राप्त करता है। |
| System::Details::VirtualizedIteratorBase\<[System::String](../../system/string/)\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | वर्तमान कंटेनर के begin इटरटर के इम्प्लीमेंटेशन को प्राप्त करता है। |
| System::Details::VirtualizedIteratorBase\<[System::String](../../system/string/)\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | वर्तमान कंटेनर के end const इटरटर के इम्प्लीमेंटेशन को प्राप्त करता है। |
| System::Details::VirtualizedIteratorBase\<[System::String](../../system/string/)\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | वर्तमान कंटेनर के end इटरटर के इम्प्लीमेंटेशन को प्राप्त करता है। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## टाइपडिफ़

| टाइपडिफ़ | विवरण |
| --- | --- |
| [iterator](./iterator/) | इटरटर प्रकार। |
| [const_iterator](./const_iterator/) | कॉन्स्ट इटरटर प्रकार। |
| [reverse_iterator](./reverse_iterator/) | रिवर्स इटरटर प्रकार। |
| [const_reverse_iterator](./const_reverse_iterator/) | कॉन्स्ट रिवर्स इटरटर प्रकार। |

## संबंधित देखें

* क्लास [IEnumerable](../../system.collections.generic/ienumerable/)
* नेमस्पेस [System::Collections::Specialized](../)
* लाइब्रेरी [Aspose.Slides](../../)