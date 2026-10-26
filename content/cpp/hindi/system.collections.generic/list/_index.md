---
title: List
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: List फ़ॉरवर्ड घोषणा।
type: docs
weight: 430
url: /hi/system.collections.generic/list/
---
## List क्लास

[List](./) फ़ॉरवर्ड डिक्लेरेशन।

```cpp
template<typename T>class List : public virtual System::Object,
                                 public System::Collections::Generic::IList<T>
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | तत्व प्रकार। |

## Methods

| विधि | विवरण |
| --- | --- |
| void [_add_range](./_add_range/)(std::initializer_list\<T\>) | C++ विशिष्ट। |
| void [Add](./add/)(const T\&) override | सूची के अंत में तत्व जोड़ता है। |
| void [AddInitializer](./addinitializer/)(int, const T *) | सूची में तत्व जोड़ता है; प्रारम्भिक मानों को अनुवादित करने के समय उपयोग किया जाता है। |
| void [AddRange](./addrange/)([IEnumerablePtr](./ienumerableptr/)) | संग्रह (या स्वयं) से सभी तत्व वर्तमान सूची के अंत में जोड़ता है। |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](./asreadonly/)() | इस संग्रह का केवल-पढ़ने योग्य रेफ़रेंस प्राप्त करता है। |
| [iterator](../ienumerable/iterator/) [begin](./begin/)() | संग्रह के पहले तत्व के लिए इटररेटर प्राप्त करता है। |
| [const_iterator](../ienumerable/const_iterator/) [begin](./begin/)() const | स्थिर-योग्य संग्रह के पहले तत्व के लिए इटररेटर प्राप्त करता है। |
| int [BinarySearch](./binarysearch/)(const T\&) const | सॉर्टेड सूची में आइटम खोजता है। |
| int [BinarySearch](./binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | सॉर्टेड सूची में आइटम खोजता है। |
| int [BinarySearch](./binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | सॉर्टेड सूची में आइटम खोजता है। |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](./cbegin/)() const | स्थिर-योग्य संग्रह के पहले तत्व के लिए इटररेटर प्राप्त करता है। |
| [const_iterator](../ienumerable/const_iterator/) [cend](./cend/)() const | संग्रह के अंत के बाद मौजूद न होने वाले स्थिर-योग्य तत्व के लिए इटररेटर प्राप्त करता है। |
| void [Clear](./clear/)() override | सभी तत्वों को हटाता है। |
| **bool** [Contains](./contains/)(const T\&) const override | जाँचता है कि आइटम सूची में मौजूद है या नहीं। |
| [SharedPtr](../../system/sharedptr/)\<[List](./)\<OutputType\>\> [ConvertAll](./convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | भिन्न प्रकार में परिवर्तित तत्वों की सूची बनाता है। |
| void [CopyTo](./copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | सूची के तत्वों को मौजूदा एरे तत्वों में कॉपी करता है। |
| void [CopyTo](./copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | सभी तत्वों को मौजूदा एरे तत्वों में कॉपी करता है। |
| void [CopyTo](./copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | निर्दिष्ट इंडेक्स से शुरू करके तत्वों को मौजूदा एरे तत्वों में कॉपी करता है। |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | संग्रह के अंतिम स्थिर-योग्य तत्व (रिवर्स में पहला) के लिए रिवर्स इटररेटर प्राप्त करता है। |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | संग्रह की शुरुआत से पहले मौजूद न होने वाले स्थिर-योग्य तत्व के लिए रिवर्स इटररेटर प्राप्त करता है। |
| [vector_t](./vector_t/)\& [data](./data/)() | अधारभूत डेटा संरचना एक्सेस फ़ंक्शन। |
| const [vector_t](./vector_t/)\& [data](./data/)() const | अधारभूत डेटा संरचना एक्सेस फ़ंक्शन। |
| [iterator](../ienumerable/iterator/) [end](./end/)() | संग्रह के अंत के बाद मौजूद न होने वाले तत्व के लिए इटररेटर प्राप्त करता है। |
| [const_iterator](../ienumerable/const_iterator/) [end](./end/)() const | स्थिर-योग्य संग्रह के अंत के बाद मौजूद न होने वाले तत्व के लिए इटररेटर प्राप्त करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सारंसे का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार की वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, सहित NaN, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, सहित NaN, के बराबर नहीं होता। |
| **bool** [Exists](./exists/)([System::Predicate](../../system/predicate/)\<T\>) | जाँचता है कि सूची में विशेष प्रेडिकेट को पूरा करने वाला तत्व मौजूद है या नहीं। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| T [Find](./find/)([System::Predicate](../../system/predicate/)\<T\>) | विशिष्ट प्रेडिकेट को पूरा करने वाला तत्व खोजता है। |
| [ListPtr](../listptr/)\<T\> [FindAll](./findall/)([System::Predicate](../../system/predicate/)\<T\>) | विशिष्ट प्रेडिकेट को पूरा करने वाले तत्वों को खोजता है। |
| int [FindIndex](./findindex/)([System::Predicate](../../system/predicate/)\<T\>) | विशिष्ट प्रेडिकेट को पूरा करने वाला तत्व खोजता है। |
| int [FindIndex](./findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | विशिष्ट प्रेडिकेट को पूरा करने वाला तत्व खोजता है। |
| int [FindIndex](./findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | विशिष्ट प्रेडिकेट को पूरा करने वाला तत्व खोजता है। |
| T [FindLast](./findlast/)([System::Predicate](../../system/predicate/)\<T\>) | विशिष्ट प्रेडिकेट को पूरा करने वाला अंतिम तत्व खोजता है। |
| void [ForEach](./foreach/)([System::Action](../../system/action/)\<T\>) | सूची के सभी तत्वों पर कार्रवाई लागू करता है। |
| int [get_Capacity](./get_capacity/)() const | वर्तमान सूची क्षमता प्राप्त करता है। |
| int [get_Count](./get_count/)() const override | वर्तमान सूची में तत्वों की संख्या प्राप्त करता है। |
| **bool** [get_IsFixedSize](../ilist/get_isfixedsize/)() | जाँचता है कि संग्रह स्थिर आकार का है या नहीं। |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | जाँचता है कि संग्रह केवल-पढ़ने योग्य है या नहीं। |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | वह वस्तु प्राप्त करता है जिसके माध्यम से संग्रह समकालिक किया जाता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | वस्तु से जुड़ी रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | सूची तत्वों पर इटरेट करने के लिए एन्यूमरेटर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) विधि का समानांतर। कस्टम वस्तुओं की हैशिंग सक्षम करता है। |
| **ThisPtr** [GetRange](./getrange/)(int, int) | सूची का एक स्लाइस बनाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | वस्तु का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समान। |
|  [ICollection](../icollection/icollection/)() | डिफ़ॉल्ट कंस्ट्रक्टर। |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | कॉपी कंस्ट्रक्टर। |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | मूव कंस्ट्रक्टर। |
| T [idx_get](./idx_get/)(int) const override | निर्दिष्ट स्थिती पर तत्व प्राप्त करता है। |
| void [idx_set](./idx_set/)(int, T) override | निर्दिष्ट स्थिती पर तत्व सेट करता है। |
| int [IndexOf](./indexof/)(const T\&) const override | विशिष्ट आइटम का पहला इंडेक्स प्राप्त करता है। |
| int [IndexOf](./indexof/)(const T\&, int) const | सूची में विशिष्ट आइटम खोजता है। |
| void [Insert](./insert/)(int, const T\&) override | निर्दिष्ट स्थिती पर आइटम डालता है। |
| void [InsertRange](./insertrange/)(int, [IEnumerablePtr](./ienumerableptr/)) | निर्दिष्ट स्थिती पर डेटा रेंज सम्मिलित करता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि वस्तु targetType द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# 'is' ऑपरेटर का समान। |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&) const | निर्दिष्ट वस्तु को खोजता है और पूरी सूची में अंतिम प्रकट होने का शून्य-आधारित इंडेक्स लौटाता है। |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&, **int32_t**) const | निर्दिष्ट वस्तु को खोजता है और [List](./) में पहले तत्व से लेकर निर्दिष्ट इंडेक्स तक के तत्वों की रेंज में अंतिम प्रकट होने का शून्य-आधारित इंडेक्स लौटाता है। |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&, **int32_t**, **int32_t**) const | निर्दिष्ट वस्तु को खोजता है और [List](./) में निर्दिष्ट संख्या के तत्वों की रेंज में, जो निर्दिष्ट इंडेक्स पर समाप्त होती है, अंतिम प्रकट होने का शून्य-आधारित इंडेक्स लौटाता है। |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | एक अनुक्रम पर संचायक फ़ंक्शन लागू करता है। |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | निर्धारित करता है कि क्या अनुक्रम के सभी तत्व एक शर्त को संतुष्ट करते हैं। |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | निर्धारित करता है कि क्या अनुक्रम में कोई तत्व है। |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | निर्धारित करता है कि क्या अनुक्रम का कोई तत्व मौजूद है या शर्त को संतुष्ट करता है। |
| T [LINQ_Average](../ienumerable/linq_average/)() | संख्यात्मक मानों के अनुक्रम का औसत गणना करता है। |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | इनपुट अनुक्रम के प्रत्येक तत्व पर ट्रांसफ़ॉर्म फ़ंक्शन लागू करके प्राप्त मानों के अनुक्रम का औसत गणना करता है। |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | तत्वों को निर्दिष्ट प्रकार में रूपांतरित करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | दो अनुक्रमों को जोड़ता है। |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | निर्धारित करता है कि अनुक्रम में निर्दिष्ट मूल्य मौजूद है या नहीं। |
| int [LINQ_Count](../ienumerable/linq_count/)() | सीधे गिनती द्वारा अनुक्रम में तत्वों की संख्या लौटाता है। |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | निर्दिष्ट शर्त को संतुष्ट करने वाले अनुक्रम के तत्वों की संख्या लौटाता है। |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | अनुक्रम में निर्दिष्ट इंडेक्स पर तत्व लौटाता है। |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | अनुक्रम में निर्दिष्ट इंडेक्स पर तत्व लौटाता है। |
| T [LINQ_First](../ienumerable/linq_first/)() | अनुक्रम का पहला तत्व लौटाता है। |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | निर्दिष्ट शर्त को संतुष्ट करने वाला अनुक्रम का पहला तत्व लौटाता है। |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | अनुक्रम का पहला तत्व लौटाता है, या यदि अनुक्रम खाली है तो डिफ़ॉल्ट मान। |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | शर्त को संतुष्ट करने वाला अनुक्रम का पहला तत्व लौटाता है, या यदि ऐसा तत्व नहीं मिलता तो डिफ़ॉल्ट मान। |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | अनुक्रम के तत्वों को समूहबद्ध करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | अनुक्रम के तत्वों को समूहबद्ध करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | अनुक्रम का अंतिम तत्व लौटाता है। |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | अनुक्रम का अंतिम तत्व लौटाता है, या यदि अनुक्रम खाली है तो डिफ़ॉल्ट मान। |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | सामान्य अनुक्रम के प्रत्येक तत्व पर ट्रांसफ़ॉर्म फ़ंक्शन लागू करता है और अधिकतम परिणाम मान लौटाता है। |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | सामान्य अनुक्रम के प्रत्येक तत्व पर ट्रांसफ़ॉर्म फ़ंक्शन लागू करता है और न्यूनतम परिणाम मान लौटाता है। |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | निर्दिष्ट प्रकार के आधार पर अनुक्रम के तत्वों को फ़िल्टर करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | keySelector द्वारा चयनित कुंजी मानों के आधार पर अनुक्रम के तत्वों को आरोही क्रम में क्रमबद्ध करता है। |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | keySelector द्वारा चयनित कुंजी मानों के आधार पर अनुक्रम के तत्वों को अवरोही क्रम में क्रमबद्ध करता है। |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | अनुक्रम के तत्वों के क्रम को उलटता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | अनुक्रम के तत्वों को रूपांतरित करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | प्रत्येक तत्व के इंडेक्स को सम्मिलित करके अनुक्रम के प्रत्येक तत्व को नए रूप में रूपांतरित करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | अनुक्रम के प्रत्येक तत्व को प्रोजेक्ट करता है और परिणामी अनुक्रमों को एक अनुक्रम में संयोजित करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | अनुक्रम की शुरुआत से निर्दिष्ट संख्या के लगातार तत्वों को छोड़ता है और शेष लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | अनुक्रम की शुरुआत से निर्दिष्ट संख्या के लगातार तत्व लौटाता है। |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | अनुक्रम से एक एरे बनाता है। |
| [SharedPtr](../../system/sharedptr/)\<[List](./)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | अनुक्रम से एक List<T> बनाता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | निर्दिष्ट प्रेडिकेट के आधार पर अनुक्रम को फ़िल्टर करता है। |
|  [List](./list/)() | खाली सूची बनाता है। |
|  [List](./list/)(int) | पूर्व-परिभाषित क्षमता के साथ सूची बनाता है। |
|  [List](./list/)([IEnumerablePtr](./ienumerableptr/)) | कॉपी कंस्ट्रक्टर। |
| void [Lock](../../system/object/lock/)() | C# lock() कथन को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) विधि का समानांतर। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट प्रारंभ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट प्रारंभ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | मूव असाइनमेंट ऑपरेटर। |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | मूव असाइनमेंट ऑपरेटर। |
| vector_t::reference [operator[]](./operator[]/)(int) | एक्सेसर फ़ंक्शन। |
| vector_t::const_reference [operator[]](./operator[]/)(int) const | एक्सेसर फ़ंक्शन। |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | संग्रह के अंतिम तत्व (रिवर्स में पहला) के लिए रिवर्स इटररेटर प्राप्त करता है। |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | स्थिर-योग्य संग्रह के अंतिम तत्व (रिवर्स में पहला) के लिए रिवर्स इटररेटर प्राप्त करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | nullptr के साथ वैल्यू प्रकार की वस्तु की रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकृत संस्करण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग केस के लिए विशेषीकृत संस्करण। |
| **bool** [Remove](./remove/)(const T\&) override | सूची से विशिष्ट आइटम की पहली उपस्थिति हटाता है। |
| int [RemoveAll](./removeall/)([Predicate](../../system/predicate/)\<T\>) | विशिष्ट प्रेडिकेट से मेल खाने वाले सभी तत्वों को हटाता है। |
| void [RemoveAt](./removeat/)(int) override | निर्दिष्ट स्थिती पर आइटम हटाता है। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंटर घटाता है। |
| void [RemoveRange](./removerange/)(int, int) | सूची का स्लाइस हटाता है। |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | संग्रह की शुरुआत से पहले मौजूद न होने वाले तत्व के लिए रिवर्स इटररेटर प्राप्त करता है। |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | स्थिर-योग्य संग्रह की शुरुआत से पहले मौजूद न होने वाले तत्व के लिए रिवर्स इटररेटर प्राप्त करता है। |
| void [Reverse](./reverse/)() | पूरी सूची के तत्वों के क्रम को उलटता है। |
| void [Reverse](./reverse/)(int, int) | सूची स्लाइस के तत्वों के क्रम को उलटता है। |
| void [set_Capacity](./set_capacity/)(int) | सूची क्षमता सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्प्लेट आर्ग्युमेंट को साझा के बजाय वीक पॉइंटर सेट करता है। कंटेनर में पॉइंटर को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंटर बढ़ाता है। सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंटर घटाता है और उसे लौटाता है। सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [Sort](./sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | सूची के तत्वों को क्रमबद्ध करता है। |
| void [Sort](./sort/)() | डिफ़ॉल्ट कंपेरेटर का उपयोग करके सूची के तत्वों को क्रमबद्ध करता है। |
| void [Sort](./sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>) | सूची स्लाइस के तत्वों को क्रमबद्ध करता है। |
| void [Sort](./sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | सूची के तत्वों को क्रमबद्ध करता है। |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](./toarray/)() const | सूची को एरे में परिवर्तित करता है। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) विधि का समानांतर। कस्टम वस्तुओं को स्ट्रिंग में कनवर्ट करने की सुविधा देता है। |
| void [TrimExcess](./trimexcess/)() | सूची क्षमता को आकार के अनुसार समायोजित करता है। |
| **bool** [TrueForAll](./trueforall/)([System::Predicate](../../system/predicate/)\<T\>) | निर्धारित करता है कि क्या संग्रह में प्रत्येक तत्व निर्दिष्ट प्रेडिकेट द्वारा परिभाषित शर्तों को मिलाता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() कथन को अनलॉक करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | वर्तमान कंटेनर के begin const इटररेटर की कार्यान्वयन प्राप्त करता है। |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | वर्तमान कंटेनर के begin इटररेटर की कार्यान्वयन प्राप्त करता है। |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | वर्तमान कंटेनर के end const इटररेटर की कार्यान्वयन प्राप्त करता है। |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | वर्तमान कंटेनर के end इटररेटर की कार्यान्वयन प्राप्त करता है। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंटर बढ़ाता है। सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंटर घटाता है। सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~ICollection](../icollection/~icollection/)() | डिस्ट्रक्टर। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## Typedefs

| टाइपडिफ | विवरण |
| --- | --- |
| [ValueType](./valuetype/) | यह प्रकार। |
| [BaseType](./basetype/) | इंटरफ़ेस प्रकार। |
| [vector_t](./vector_t/) | अधारभूत डेटा प्रकार। |
| [iterator](./iterator/) | इटररेटर प्रकार। |
| [const_iterator](./const_iterator/) | स्थिर इटररेटर प्रकार। |
| [reverse_iterator](./reverse_iterator/) | रिवर्स इटररेटर प्रकार। |
| [const_reverse_iterator](./const_reverse_iterator/) | स्थिर रिवर्स इटररेटर प्रकार। |
| [IEnumerablePtr](./ienumerableptr/) | हमारे समान प्रकार के तत्वों को धारण करने वाला कंटेनर। |
| [IEnumeratorPtr](./ienumeratorptr/) | **Enumerator** प्रकार। |

## टिप्पणियाँ

[List](./) - std::vector के चारों ओर रैपर जो अनूदित कोड में उपयोग किया जाएगा। तत्व प्रकार के लिए operator == को लागू करने की आवश्यकता होती है। इस क्लास की वस्तुओं को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। कभी भी इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके न बनाएँ, क्योंकि इससे रनटाइम त्रुटियां और/या असर्शन दोष हो सकते हैं। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग करके इसे फ़ंक्शनों में तर्क के रूप में पास करें।

```cpp
#include <system/collections/list.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // पहली सूची बनाएँ।
  auto list1 = MakeObject<List<int>>();

  // पहली सूची भरें।
  list1->Add(3);
  list1->Add(1);
  list1->Add(-5);
  list1->Add(8);

  // पहली सूची को क्रमबद्ध करें।
  // पहली सूची के आइटम होंगे: {-5, 1, 3, 8}
  list1->Sort();

  // इंडेक्स 2 पर आइटम हटाएँ।
  // पहली सूची के आइटम होंगे: {-5, 1, 8}
  list1->RemoveAt(2);

  // इंडेक्स 1 पर आइटम डालें।
  // पहली सूची के आइटम होंगे: {-5, 15, 1, 8}
  list1->Insert(1, 15);

  // दूसरी सूची बनाएँ।
  auto list2 = MakeObject<List<int>>();

  // दूसरी सूची भरें।
  list2->Add(10);
  list2->Add(20);
  list2->Add(30);

  // दूसरी सूची के तत्वों को पहली सूची में जोड़ें।
  list1->AddRange(list2);

  // पहली सूची के आइटम प्रिंट करें।
  for (const auto item: list1)
  {
    std::cout << item << ' ';
  }

  return 0;
}
/*
यह कोड उदाहरण निम्नलिखित आउटपुट उत्पन्न करता है:
- 5 15 1 8 10 20 30
*/
```

## संदर्भ

* क्लास [Object](../../system/object/)
* क्लास [IList](../ilist/)
* नामस्थान [System::Collections::Generic](../)
* लाइब्रेरी [Aspose.Slides](../../)