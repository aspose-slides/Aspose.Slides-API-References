---
title: SoapHeaderCollection
second_title: Aspose.Slides for C++ API संदर्भ
description: SoapHeader क्लास के उदाहरणों का संग्रह रखता है।
type: docs
weight: 105
url: /hi/system.web.services.protocols/soapheadercollection/
---
## SoapHeaderCollection क्लास

[SoapHeader](../soapheader/) क्लास के उदाहरणों का संग्रह रखती है।

```cpp
class SoapHeaderCollection : public System::Collections::Generic::List<System::SharedPtr<SoapHeader>>
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| void [_add_range](../../system.collections.generic/list/_add_range/)(std::initializer_list\<T\>) | C++ विशिष्ट। |
| void [Add](../../system.collections.generic/list/add/)(const T\&) override | सूची के अंत में तत्व जोड़ता है। |
| void [AddInitializer](../../system.collections.generic/list/addinitializer/)(int, const T *) | सूची में तत्व जोड़ता है; प्रारम्भिककर्ताओं का अनुवाद करते समय उपयोग किया जाता है। |
| void [AddRange](../../system.collections.generic/list/addrange/)([IEnumerablePtr](../../system.collections.generic/list/ienumerableptr/)) | संग्रह (या स्वयं) के सभी तत्वों को वर्तमान सूची के अंत में जोड़ता है। |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](../../system.collections.generic/list/asreadonly/)() | इस संग्रह का केवल-रेड रेफ़रेंस प्राप्त करता है। |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/list/begin/)() | संग्रह के पहले तत्व के लिए इटररेटर प्राप्त करता है। |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/list/begin/)() const | कॉन्स्ट-योग्य संग्रह के पहले तत्व के लिए इटररेटर प्राप्त करता है। |
| int [BinarySearch](../../system.collections.generic/list/binarysearch/)(const T\&) const | सॉर्टेड सूची में आइटम की खोज करता है। |
| int [BinarySearch](../../system.collections.generic/list/binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) const | सॉर्टेड सूची में आइटम की खोज करता है। |
| int [BinarySearch](../../system.collections.generic/list/binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) const | सॉर्टेड सूची में आइटम की खोज करता है। |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/list/cbegin/)() const | संग्रह के पहले कॉन्स्ट-योग्य तत्व के लिए इटररेटर प्राप्त करता है। |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/list/cend/)() const | संग्रह के अंत के पीछे एक गैर-मौजूद कॉन्स्ट-योग्य तत्व के लिए इटररेटर प्राप्त करता है। |
| void [Clear](../../system.collections.generic/list/clear/)() override | सभी तत्वों को हटाता है। |
| **bool** [Contains](../../system.collections.generic/list/contains/)(const T\&) const override | जाँचता है कि सूची में आइटम मौजूद है या नहीं। |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<OutputType\>\> [ConvertAll](../../system.collections.generic/list/convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | विभिन्न प्रकार में परिवर्तित तत्वों की सूची बनाता है। |
| void [CopyTo](../../system.collections.generic/list/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | सूची के तत्वों को मौजूदा ऐरे तत्वों में कॉपी करता है। |
| void [CopyTo](../../system.collections.generic/list/copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | सभी तत्वों को मौजूदा ऐरे तत्वों में कॉपी करता है। |
| void [CopyTo](../../system.collections.generic/list/copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | निर्दिष्ट इंडेक्स से शुरू होकर तत्वों को मौजूदा ऐरे तत्वों में कॉपी करता है। |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [crbegin](../../system.collections.generic/list/crbegin/)() const | संग्रह के अंतिम कॉन्स्ट-योग्य तत्व के लिए रिवर्स इटररेटर प्राप्त करता है (रिवर्स में पहला)। |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [crend](../../system.collections.generic/list/crend/)() const | संग्रह के शुरू से पहले एक गैर-मौजूद कॉन्स्ट-योग्य तत्व के लिए रिवर्स इटररेटर प्राप्त करता है। |
| [vector_t](../../system.collections.generic/list/vector_t/)\& [data](../../system.collections.generic/list/data/)() | आधारभूत डेटा संरचना तक पहुँच फ़ंक्शन। |
| const [vector_t](../../system.collections.generic/list/vector_t/)\& [data](../../system.collections.generic/list/data/)() const | आधारभूत डेटा संरचना तक पहुँच फ़ंक्शन। |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/list/end/)() | संग्रह के अंत के पीछे एक गैर-मौजूद तत्व के लिए इटररेटर प्राप्त करता है। |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/list/end/)() const | कॉन्स्ट-योग्य संग्रह के अंत के पीछे एक गैर-मौजूद तत्व के लिए इटररेटर प्राप्त करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमान्टिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली का फ्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को समान माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली का फ्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को समान माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| **bool** [Exists](../../system.collections.generic/list/exists/)([System::Predicate](../../system/predicate/)\<T\>) | सूची में निर्दिष्ट प्रेडिकेट को पूरा करने वाला तत्व मौजूद है या नहीं जाँचता है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| T [Find](../../system.collections.generic/list/find/)([System::Predicate](../../system/predicate/)\<T\>) | निर्दिष्ट प्रेडिकेट को पूरा करने वाले तत्व की खोज करता है। |
| [ListPtr](../../system.collections.generic/listptr/)\<T\> [FindAll](../../system.collections.generic/list/findall/)([System::Predicate](../../system/predicate/)\<T\>) | निर्दिष्ट प्रेडिकेट को पूरा करने वाले तत्वों की खोज करता है। |
| int [FindIndex](../../system.collections.generic/list/findindex/)([System::Predicate](../../system/predicate/)\<T\>) | निर्दिष्ट प्रेडिकेट को पूरा करने वाले तत्व की खोज करता है। |
| int [FindIndex](../../system.collections.generic/list/findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | निर्दिष्ट प्रेडिकेट को पूरा करने वाले तत्व की खोज करता है। |
| int [FindIndex](../../system.collections.generic/list/findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | निर्दिष्ट प्रेडिकेट को पूरा करने वाले तत्व की खोज करता है। |
| T [FindLast](../../system.collections.generic/list/findlast/)([System::Predicate](../../system/predicate/)\<T\>) | निर्दिष्ट प्रेडिकेट को पूरा करने वाले अंतिम तत्व की खोज करता है। |
| void [ForEach](../../system.collections.generic/list/foreach/)([System::Action](../../system/action/)\<T\>) | सूची के सभी तत्वों पर क्रिया लागू करता है। |
| int [get_Capacity](../../system.collections.generic/list/get_capacity/)() const | वर्तमान सूची की क्षमता प्राप्त करता है। |
| int [get_Count](../../system.collections.generic/list/get_count/)() const override | वर्तमान सूची में तत्वों की संख्या प्राप्त करता है। |
| **bool** [get_IsFixedSize](../../system.collections.generic/ilist/get_isfixedsize/)() | जाँचता है कि संग्रह निश्चित आकार का है या नहीं। |
| virtual **bool** [get_IsReadOnly](../../system.collections.generic/icollection/get_isreadonly/)() const | जाँचता है कि संग्रह केवल-रीड है या नहीं। |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | वह ऑब्जेक्ट प्राप्त करता है जिसके माध्यम से संग्रह को सिंक्रनाइज़ किया जा रहा है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबद्ध रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| [IEnumeratorPtr](../../system.collections.generic/list/ienumeratorptr/) [GetEnumerator](../../system.collections.generic/list/getenumerator/)() override | सूची के तत्वों पर इटररेट करने के लिए एन्यूमरेटर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| **ThisPtr** [GetRange](../../system.collections.generic/list/getrange/)(int, int) | सूची का स्लाइस बनाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानार्थी। |
| [ICollection](../../system.collections.generic/icollection/icollection/)() | डिफ़ॉल्ट निर्माणकर्ता। |
| [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | कॉपी निर्माणकर्ता। |
| [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | मूव निर्माणकर्ता। |
| T [idx_get](../../system.collections.generic/list/idx_get/)(int) const override | निर्दिष्ट स्थित पर तत्व प्राप्त करता है। |
| void [idx_set](../../system.collections.generic/list/idx_set/)(int, T) override | निर्दिष्ट स्थित पर तत्व सेट करता है। |
| int [IndexOf](../../system.collections.generic/list/indexof/)(const T\&) const override | निर्दिष्ट आइटम का पहला इंडेक्स प्राप्त करता है। |
| int [IndexOf](../../system.collections.generic/list/indexof/)(const T\&, int) const | सूची में विशिष्ट आइटम की खोज करता है। |
| void [Insert](../../system.collections.generic/list/insert/)(int, const T\&) override | निर्दिष्ट स्थित पर आइटम सम्मिलित करता है। |
| void [InsertRange](../../system.collections.generic/list/insertrange/)(int, [IEnumerablePtr](../../system.collections.generic/list/ienumerableptr/)) | निर्दिष्ट स्थित पर डेटा रेंज सम्मिलित करता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# 'is' ऑपरेटर का समानार्थी। |
| **int32_t** [LastIndexOf](../../system.collections.generic/list/lastindexof/)(const T\&) const | निर्दिष्ट ऑब्जेक्ट की खोज करता है और पूरी सूची में अंतिम प्रकट होने का शून्य-आधारित इंडेक्स लौटाता है। |
| **int32_t** [LastIndexOf](../../system.collections.generic/list/lastindexof/)(const T\&, **int32_t**) const | निर्दिष्ट ऑब्जेक्ट की खोज करता है और [List](../../system.collections.generic/list/) में तत्वों की रेंज (पहले तत्व से निर्दिष्ट इंडेक्स तक) में अंतिम प्रकट होने का शून्य-आधारित इंडेक्स लौटाता है। |
| **int32_t** [LastIndexOf](../../system.collections.generic/list/lastindexof/)(const T\&, **int32_t**, **int32_t**) const | निर्दिष्ट ऑब्जेक्ट की खोज करता है और [List](../../system.collections.generic/list/) में उन तत्वों की रेंज में जहाँ निर्दिष्ट संख्या के तत्व होते हैं और निर्दिष्ट इंडेक्स पर समाप्त होते हैं, अंतिम प्रकट होने का शून्य-आधारित इंडेक्स लौटाता है। |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | एक अनुक्रम पर एक्क्यूमुलेटर फ़ंक्शन लागू करता है। |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | निर्धारित करता है कि क्या अनुक्रम के सभी तत्व एक शर्त को पूरा करते हैं। |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | निर्धारित करता है कि अनुक्रम में कोई तत्व है या नहीं। |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | निर्धारित करता है कि अनुक्रम का कोई तत्व मौजूद है या शर्त को पूरा करता है। |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | संख्यात्मक मानों के अनुक्रम का औसत गणना करता है। |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | इनपुट अनुक्रम के प्रत्येक तत्व पर ट्रांसफ़ॉर्म फ़ंक्शन लागू करके प्राप्त मानों के अनुक्रम का औसत गणना करता है। |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | तत्वों को निर्दिष्ट प्रकार में कास्ट करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | दो अनुक्रमों को जोड़ता है। |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | निर्धारित करता है कि अनुक्रम में निर्दिष्ट मान मौजूद है या नहीं। |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | अनुक्रम में तत्वों की संख्या लौटाता है (सीधे गिनती द्वारा गणना)। |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | अनुक्रम में उन तत्वों की संख्या लौटाता है जो निर्दिष्ट शर्त को पूरा करते हैं। |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | एक अनुक्रम में निर्दिष्ट इंडेक्स पर तत्व लौटाता है। |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | एक अनुक्रम में निर्दिष्ट इंडेक्स पर तत्व लौटाता है। |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | अनुक्रम का पहला तत्व लौटाता है। |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | अनुक्रम का पहला तत्व लौटाता है जो निर्दिष्ट शर्त को पूरा करता है। |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | एक अनुक्रम का पहला तत्व लौटाता है, या यदि अनुक्रम ख़ाली है तो डिफ़ॉल्ट मान। |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | अनुक्रम का वह पहला तत्व लौटाता है जो शर्त को पूरा करता है या यदि ऐसा कोई तत्व नहीं मिला तो डिफ़ॉल्ट मान। |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | एक अनुक्रम के तत्वों को समूहित करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | एक अनुक्रम के तत्वों को समूहित करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | अनुक्रम का अंतिम तत्व लौटाता है। |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | अनुक्रम का अंतिम तत्व लौटाता है, या यदि अनुक्रम ख़ाली है तो डिफ़ॉल्ट मान। |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | एक सामान्य अनुक्रम के प्रत्येक तत्व पर ट्रांसफ़ॉर्म फ़ंक्शन लागू करता है और अधिकतम परिणाम मान लौटाता है। |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | एक सामान्य अनुक्रम के प्रत्येक तत्व पर ट्रांसफ़ॉर्म फ़ंक्शन लागू करता है और न्यूनतम परिणाम मान लौटाता है। |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | निर्धारित प्रकार के आधार पर अनुक्रम के तत्वों को फ़िल्टर करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | keySelector द्वारा चयनित कुंजी मानों के अनुसार अनुक्रम के तत्वों को आरोही क्रम में सॉर्ट करता है। |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | keySelector द्वारा चयनित कुंजी मानों के अनुसार अनुक्रम के तत्वों को अवरोही क्रम में सॉर्ट करता है। |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | एक अनुक्रम में तत्वों का क्रम उल्टा करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | एक अनुक्रम के तत्वों को परिवर्तित करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | क्रम के प्रत्येक तत्व को उसके इंडेक्स को सम्मिलित करके नई रूप में परिवर्तित करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | एक अनुक्रम के प्रत्येक तत्व को प्रोजेक्ट करता है और परिणामी अनुक्रमों को एक में संयोजित करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | एक अनुक्रम की शुरुआत से निर्दिष्ट संख्या में क्रमागत तत्वों को स्किप करता है और शेष लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | एक अनुक्रम की शुरुआत से निर्दिष्ट संख्या में क्रमागत तत्व लौटाता है। |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | एक अनुक्रम से एरे बनाता है। |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | एक अनुक्रम से List<T> बनाता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | निर्धारित प्रेडिकेट के आधार पर अनुक्रम को फ़िल्टर करता है। |
| [List](../../system.collections.generic/list/list/)() | खाली सूची बनाता है। |
| [List](../../system.collections.generic/list/list/)(int) | पूर्व-निर्धारित क्षमता वाली सूची बनाता है। |
| [List](../../system.collections.generic/list/list/)([IEnumerablePtr](../../system.collections.generic/list/ienumerableptr/)) | कॉपी निर्माणकर्ता। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट का लॉकिंग लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानार्थी। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
| [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को इनिशियलाइज़ करता है। |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी निर्माणकर्ता। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन सक्षम करता है। |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | मूव असाइनमेंट ऑपरेटर। |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | मूव असाइनमेंट ऑपरेटर। |
| vector_t::reference [operator[]](../../system.collections.generic/list/operator[]/)(int) | एक्सेसर फ़ंक्शन। |
| vector_t::const_reference [operator[]](../../system.collections.generic/list/operator[]/)(int) const | एक्सेसर फ़ंक्शन। |
| [reverse_iterator](../../system.collections.generic/list/reverse_iterator/) [rbegin](../../system.collections.generic/list/rbegin/)() | संग्रह के अंतिम तत्व के लिए रिवर्स इटररेटर प्राप्त करता है (रिवर्स में पहला)। |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [rbegin](../../system.collections.generic/list/rbegin/)() const | कॉन्स्ट-योग्य संग्रह के अंतिम तत्व के लिए रिवर्स इटररेटर प्राप्त करता है (रिवर्स में पहला)। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट को nullptr के साथ रेफ़रेंस-तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग केस के लिए विशेषीकरण। |
| **bool** [Remove](../../system.collections.generic/list/remove/)(const T\&) override | सूची से विशिष्ट आइटम का पहला उदाहरण हटाता है। |
| int [RemoveAll](../../system.collections.generic/list/removeall/)([Predicate](../../system/predicate/)\<T\>) | निर्दिष्ट प्रेडिकेट से मेल खाते सभी तत्वों को हटाता है। |
| void [RemoveAt](../../system.collections.generic/list/removeat/)(int) override | निर्दिष्ट स्थित पर आइटम हटाता है। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट घटाता है। |
| void [RemoveRange](../../system.collections.generic/list/removerange/)(int, int) | सूची का स्लाइस हटाता है। |
| [reverse_iterator](../../system.collections.generic/list/reverse_iterator/) [rend](../../system.collections.generic/list/rend/)() | संग्रह के शुरू से पहले एक गैर-मौजूद तत्व के लिए रिवर्स इटररेटर प्राप्त करता है। |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [rend](../../system.collections.generic/list/rend/)() const | कॉन्स्ट-योग्य संग्रह के शुरू से पहले एक गैर-मौजूद तत्व के लिए रिवर्स इटररेटर प्राप्त करता है। |
| void [Reverse](../../system.collections.generic/list/reverse/)() | पूरी सूची के तत्वों के क्रम को उलटता है। |
| void [Reverse](../../system.collections.generic/list/reverse/)(int, int) | सूची स्लाइस के तत्वों के क्रम को उलटता है। |
| void [set_Capacity](../../system.collections.generic/list/set_capacity/)(int) | सूची क्षमता सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्प्लेट आर्ग्यूमेंट को वाटर पॉइंटर सेट करता है (शेर्ड के बजाय)। कंटेनरों में पॉइंटर्स को वाटर मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट घटाता है और लौटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| [SoapHeaderCollection](./soapheadercollection/)() | [SoapHeaderCollection](./) क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
| void [Sort](../../system.collections.generic/list/sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) | सूची में तत्वों को सॉर्ट करता है। |
| void [Sort](../../system.collections.generic/list/sort/)() | डिफ़ॉल्ट कम्पेरेटर का उपयोग करके सूची के तत्वों को सॉर्ट करता है। |
| void [Sort](../../system.collections.generic/list/sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>) | सूची स्लाइस में तत्वों को सॉर्ट करता है। |
| void [Sort](../../system.collections.generic/list/sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | सूची के तत्वों को सॉर्ट करता है। |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](../../system.collections.generic/list/toarray/)() const | सूची को एरे में बदलता है। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| void [TrimExcess](../../system.collections.generic/list/trimexcess/)() | सूची क्षमता को उसके आकार के अनुसार समायोजित करता है। |
| **bool** [TrueForAll](../../system.collections.generic/list/trueforall/)([System::Predicate](../../system/predicate/)\<T\>) | जाँचता है कि संग्रह के सभी तत्व निर्दिष्ट प्रेडिकेट द्वारा परिभाषित शर्तों को पूरा करते हैं या नहीं। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कॉन्स्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट का अनलॉकिंग लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](../../system.collections.generic/list/virtualizebeginconstiterator/)() const override | वर्तमान कंटेनर के लिए begin const इटररेटर की इम्प्लीमेंटेशन प्राप्त करता है। |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](../../system.collections.generic/list/virtualizebeginiterator/)() override | वर्तमान कंटेनर के लिए begin इटररेटर की इम्प्लीमेंटेशन प्राप्त करता है। |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](../../system.collections.generic/list/virtualizeendconstiterator/)() const override | वर्तमान कंटेनर के लिए end const इटररेटर की इम्प्लीमेंटेशन प्राप्त करता है। |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](../../system.collections.generic/list/virtualizeenditerator/)() override | वर्तमान कंटेनर के लिए end इटररेटर की इम्प्लीमेंटेशन प्राप्त करता है। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट घटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | डिस्ट्रक्टर। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## देखें

* क्लास [List](../../system.collections.generic/list/)
* नेमस्पेस [System::Web::Services::Protocols](../)
* लाइब्रेरी [Aspose.Slides](../../)