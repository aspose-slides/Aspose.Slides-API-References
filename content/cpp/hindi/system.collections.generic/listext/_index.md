---
title: ListExt
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: सामान्य List क्लास जो IListWrapper इंटरफ़ेस को लागू करती है
type: docs
weight: 443
url: /hi/system.collections.generic/listext/
---
## ListExt क्लास

सामान्य [List](../list/) क्लास जो [IListWrapper](../../system.collections/ilistwrapper/) इंटरफ़ेस को लागू करता है

```cpp
template<typename T>class ListExt : public System::Collections::Generic::List<T>,
                                    public System::Collections::IListWrapper
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| void [_add_range](../list/_add_range/)(std::initializer_list\<T\>) | C++ विशिष्ट। |
| void [Add](../list/add/)(const T\&) override | सूची के अंत में तत्व जोड़ता है। |
| void [AddInitializer](../list/addinitializer/)(int, const T *) | सूची में तत्व जोड़ता है; इनिशियलाइज़र का अनुवाद करते समय उपयोग किया जाता है। |
| void [AddRange](../list/addrange/)([IEnumerablePtr](../list/ienumerableptr/)) | वर्तमान सूची के अंत में संग्रह (या स्वयं) से सभी तत्व जोड़ता है। |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](../list/asreadonly/)() | इस संग्रह का केवल-पढ़ने योग्य संदर्भ प्राप्त करता है। |
| [iterator](../ienumerable/iterator/) [begin](../list/begin/)() | संग्रह के पहले तत्व के लिए इटरेटर प्राप्त करता है। |
| [const_iterator](../ienumerable/const_iterator/) [begin](../list/begin/)() const | स्थिर (const) योग्य संग्रह के पहले तत्व के लिए इटरेटर प्राप्त करता है। |
| int [BinarySearch](../list/binarysearch/)(const T\&) const | सॉर्टेड सूची में आइटम खोजता है। |
| int [BinarySearch](../list/binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | सॉर्टेड सूची में आइटम खोजता है। |
| int [BinarySearch](../list/binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | सॉर्टेड सूची में आइटम खोजता है। |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../list/cbegin/)() const | संग्रह के पहले const-योग्य तत्व के लिए इटरेटर प्राप्त करता है। |
| [const_iterator](../ienumerable/const_iterator/) [cend](../list/cend/)() const | संग्रह के अंत के पीछे एक गैर-मौजूद const-योग्य तत्व के लिए इटरेटर प्राप्त करता है। |
| void [Clear](../list/clear/)() override | सभी तत्वों को हटाता है। |
| **bool** [Contains](../list/contains/)(const T\&) const override | जाँचता है कि सूची में आइटम मौजूद है या नहीं। |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<OutputType\>\> [ConvertAll](../list/convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | विभिन्न प्रकार में परिवर्तित तत्वों की सूची बनाता है। |
| void [CopyTo](../list/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | सूची के तत्वों को मौजूदा ऐरे तत्वों में कॉपी करता है। |
| void [CopyTo](../list/copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | सभी तत्वों को मौजूदा ऐरे तत्वों में कॉपी करता है। |
| void [CopyTo](../list/copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | निर्दिष्ट अनुक्रमणिका से शुरू करके तत्वों को मौजूदा ऐरे तत्वों में कॉपी करता है। |
| [const_reverse_iterator](../list/const_reverse_iterator/) [crbegin](../list/crbegin/)() const | संग्रह के अंतिम const-योग्य तत्व (रिवर्स में पहला) के लिए रिवर्स इटरेटर प्राप्त करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\> [CreateIListWrapper](./createilistwrapper/)() override | [IListWrapper](../../system.collections/ilistwrapper/) इंटरफ़ेस कार्यान्वयन। |
| std::enable_if\<[System::IsSmartPtr](../../system/issmartptr/)\<T1\>::value, [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\>\>::type [CreateIListWrapperImpl](./createilistwrapperimpl/)() | [IListWrapper](../../system.collections/ilistwrapper/) रेफ़रेंस प्रकारों के लिए कार्यान्वयन सहायक। |
| std::enable_if<\![System::IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[System::IsBoxable](../../system/isboxable/)\<T1\>::value, [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\>\>::type [CreateIListWrapperImpl](./createilistwrapperimpl/)() | [IListWrapper](../../system.collections/ilistwrapper/) वैल्यू प्रकारों के लिए कार्यान्वयन सहायक। |
| std::enable_if<\![System::IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![System::IsBoxable](../../system/isboxable/)\<T\>::value, [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\>\>::type [CreateIListWrapperImpl](./createilistwrapperimpl/)() | [IListWrapper](../../system.collections/ilistwrapper/) अन्य प्रकारों के लिए कार्यान्वयन सहायक। |
| [const_reverse_iterator](../list/const_reverse_iterator/) [crend](../list/crend/)() const | संग्रह की शुरुआत से पहले एक गैर-मौजूद const-योग्य तत्व के लिए रिवर्स इटरेटर प्राप्त करता है। |
| [vector_t](../list/vector_t/)\& [data](../list/data/)() | आधारभूत डेटा संरचना तक पहुँच फ़ंक्शन। |
| const [vector_t](../list/vector_t/)\& [data](../list/data/)() const | आधारभूत डेटा संरचना तक पहुँच फ़ंक्शन। |
| [iterator](../ienumerable/iterator/) [end](../list/end/)() | संग्रह के अंत के पीछे एक गैर-मौजूद तत्व के लिए इटरेटर प्राप्त करता है। |
| [const_iterator](../ienumerable/const_iterator/) [end](../list/end/)() const | स्थिर (const) संग्रह के अंत के पीछे एक गैर-मौजूद तत्व के लिए इटरेटर प्राप्त करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सिद्धांतों का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार की वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं है, लेकिन दो NaN को बराबर मानते हुए C#-शैली का फ्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, सहित NaN, के बराबर नहीं है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं है, लेकिन दो NaN को बराबर मानते हुए C#-शैली का फ्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, सहित NaN, के बराबर नहीं है। |
| **bool** [Exists](../list/exists/)([System::Predicate](../../system/predicate/)\<T\>) | सूची में विशिष्ट प्रेडिकेट का पालन करने वाला तत्व मौजूद है या नहीं, यह जाँचता है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| T [Find](../list/find/)([System::Predicate](../../system/predicate/)\<T\>) | विशिष्ट प्रेडिकेट का पालन करने वाला तत्व खोजता है। |
| [ListPtr](../listptr/)\<T\> [FindAll](../list/findall/)([System::Predicate](../../system/predicate/)\<T\>) | विशिष्ट प्रेडिकेट का पालन करने वाले तत्वों को खोजता है। |
| int [FindIndex](../list/findindex/)([System::Predicate](../../system/predicate/)\<T\>) | विशिष्ट प्रेडिकेट का पालन करने वाला तत्व खोजता है। |
| int [FindIndex](../list/findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | विशिष्ट प्रेडिकेट का पालन करने वाला तत्व खोजता है। |
| int [FindIndex](../list/findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | विशिष्ट प्रेडिकेट का पालन करने वाला तत्व खोजता है। |
| T [FindLast](../list/findlast/)([System::Predicate](../../system/predicate/)\<T\>) | विशिष्ट प्रेडिकेट का पालन करने वाला अंतिम तत्व खोजता है। |
| void [ForEach](../list/foreach/)([System::Action](../../system/action/)\<T\>) | सूची के सभी तत्वों पर कार्रवाई लागू करता है। |
| int [get_Capacity](../list/get_capacity/)() const | वर्तमान सूची क्षमता प्राप्त करता है। |
| int [get_Count](../list/get_count/)() const override | वर्तमान सूची में तत्वों की संख्या प्राप्त करता है। |
| **bool** [get_IsFixedSize](../ilist/get_isfixedsize/)() | जाँचता है कि संग्रह स्थिर आकार का है या नहीं। |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | जाँचता है कि संग्रह केवल-पढ़ने योग्य है या नहीं। |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | उस वस्तु को प्राप्त करता है जिसके माध्यम से संग्रह समन्वित किया जा रहा है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | वस्तु से जुड़ी रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| [IEnumeratorPtr](../list/ienumeratorptr/) [GetEnumerator](../list/getenumerator/)() override | सूची तत्वों पर इटरैट करने के लिए एनेमरेटर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम वस्तुओं की हैशिंग सक्षम करता है। |
| **ThisPtr** [GetRange](../list/getrange/)(int, int) | सूची का एक स्लाइस बनाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | वस्तु के वास्तविक प्रकार को प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
|  [ICollection](../icollection/icollection/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | कॉपी कन्स्ट्रक्टर। |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | मूव कन्स्ट्रक्टर। |
| T [idx_get](../list/idx_get/)(int) const override | निर्दिष्ट स्थिति पर तत्व प्राप्त करता है। |
| void [idx_set](../list/idx_set/)(int, T) override | निर्दिष्ट स्थिति पर तत्व सेट करता है। |
| int [IndexOf](../list/indexof/)(const T\&) const override | विशिष्ट आइटम की पहली अनुक्रमणिका प्राप्त करता है। |
| int [IndexOf](../list/indexof/)(const T\&, int) const | सूची में विशिष्ट आइटम खोजता है। |
| void [Insert](../list/insert/)(int, const T\&) override | निर्दिष्ट स्थिति पर आइटम डालता है। |
| void [InsertRange](../list/insertrange/)(int, [IEnumerablePtr](../list/ienumerableptr/)) | निर्दिष्ट स्थिति पर डेटा रेंज डालता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि वस्तु targetType द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| **int32_t** [LastIndexOf](../list/lastindexof/)(const T\&) const | निर्दिष्ट वस्तु खोजता है और पूरी सूची में अंतिम घटित होने की शून्य-आधारित अनुक्रमणिका लौटाता है। |
| **int32_t** [LastIndexOf](../list/lastindexof/)(const T\&, **int32_t**) const | निर्दिष्ट वस्तु खोजता है और [List](../list/) में तत्वों की रेंज में (पहले तत्व से निर्दिष्ट अनुक्रमणिका तक) अंतिम घटित होने की शून्य-आधारित अनुक्रमणिका लौटाता है। |
| **int32_t** [LastIndexOf](../list/lastindexof/)(const T\&, **int32_t**, **int32_t**) const | निर्दिष्ट वस्तु खोजता है और [List](../list/) में तत्वों की रेंज में (निर्दिष्ट संख्या के तत्व और निर्दिष्ट अनुक्रमणिका पर समाप्त) अंतिम घटित होने की शून्य-आधारित अनुक्रमणिका लौटाता है। |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | एक क्रम पर एग्रीगेटर फ़ंक्शन लागू करता है। |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | जाँचता है कि क्रम के सभी तत्व शर्त को संतुष्ट करते हैं या नहीं। |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | जाँचता है कि क्रम में कोई तत्व है या नहीं। |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | जाँचता है कि क्रम में कोई तत्व मौजूद है या शर्त को संतुष्ट करता है। |
| T [LINQ_Average](../ienumerable/linq_average/)() | संख्यात्मक मानों के क्रम का औसत गणना करता है। |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | इनपुट क्रम के प्रत्येक तत्व पर ट्रांसफ़ॉर्म फ़ंक्शन लागू करके प्राप्त मानों के क्रम का औसत गणना करता है। |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | तत्वों को निर्दिष्ट प्रकार में कास्ट करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | दो क्रमों को क्रमबद्ध करता है। |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | जाँचता है कि क्रम में निर्दिष्ट मान मौजूद है या नहीं। |
| int [LINQ_Count](../ienumerable/linq_count/)() | क्रम में तत्वों की संख्या लौटाता है (सीधे गिनती द्वारा गणना)। |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | क्रम में उन तत्वों की संख्या लौटाता है जो निर्दिष्ट शर्त को संतुष्ट करते हैं। |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | क्रम में निर्दिष्ट अनुक्रमणिका पर तत्व लौटाता है। |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | क्रम में निर्दिष्ट अनुक्रमणिका पर तत्व लौटाता है। |
| T [LINQ_First](../ienumerable/linq_first/)() | क्रम का पहला तत्व लौटाता है। |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | क्रम का पहला तत्व लौटाता है जो निर्दिष्ट शर्त को संतुष्ट करता है। |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | क्रम का पहला तत्व लौटाता है, या यदि क्रम खाली हो तो एक डिफ़ॉल्ट मान। |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | क्रम का वह पहला तत्व लौटाता है जो शर्त को संतुष्ट करता है, या यदि ऐसा कोई तत्व नहीं मिला तो डिफ़ॉल्ट मान। |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | क्रम के तत्वों को समूहित करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | क्रम के तत्वों को समूहित करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | क्रम का अंतिम तत्व लौटाता है। |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | क्रम का अंतिम तत्व लौटाता है, या यदि क्रम खाली हो तो एक डिफ़ॉल्ट मान। |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | सामान्य क्रम के प्रत्येक तत्व पर ट्रांसफ़ॉर्म फ़ंक्शन लागू करता है और अधिकतम प्राप्त मान लौटाता है। |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | सामान्य क्रम के प्रत्येक तत्व पर ट्रांसफ़ॉर्म फ़ंक्शन लागू करता है और न्यूनतम प्राप्त मान लौटाता है। |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | निर्दिष्ट प्रकार के आधार पर क्रम के तत्वों को फ़िल्टर करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | की चयनकर्ता द्वारा चयनित कुंजी मानों के अनुसार क्रम के तत्वों को आरोही क्रम में सॉर्ट करता है। |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | की चयनकर्ता द्वारा चयनित कुंजी मानों के अनुसार क्रम के तत्वों को अवरोही क्रम में सॉर्ट करता है। |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | क्रम के तत्वों का क्रम उलट देता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | क्रम के तत्वों को रूपांतरित करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | प्रत्येक तत्व के अनुक्रमणिका को शामिल करके क्रम के प्रत्येक तत्व को नए रूप में रूपांतरित करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | क्रम के प्रत्येक तत्व को प्रोजेक्ट करता है और प्राप्त क्रमों को एक क्रम में संयोजित करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | क्रम की शुरुआत से निर्दिष्ट संख्या में सतत तत्वों को छोड़ता है और शेष लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | क्रम की शुरुआत से निर्दिष्ट संख्या में सतत तत्वों को लौटाता है। |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | क्रम से एक ऐरे बनाता है। |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | क्रम से List<T> बनाता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | निर्दिष्ट प्रेडिकेट के आधार पर क्रम को फ़िल्टर करता है। |
|  [List](../list/list/)() | खाली सूची बनाता है। |
|  [List](../list/list/)(int) | पूर्व-परिभाषित क्षमता वाली सूची बनाता है। |
|  [List](../list/list/)([IEnumerablePtr](../list/ienumerableptr/)) | कॉपी कन्स्ट्रक्टर। |
| void [Lock](../../system/object/lock/)() | C# lock() बयान के लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | मूव असाइनमेंट ऑपरेटर। |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | मूव असाइनमेंट ऑपरेटर। |
| vector_t::reference [operator[]](../list/operator[]/)(int) | एक्सेसर फ़ंक्शन। |
| vector_t::const_reference [operator[]](../list/operator[]/)(int) const | एक्सेसर फ़ंक्शन। |
| [reverse_iterator](../list/reverse_iterator/) [rbegin](../list/rbegin/)() | संग्रह के अंतिम तत्व (रिवर्स में पहला) के लिए रिवर्स इटरेटर प्राप्त करता है। |
| [const_reverse_iterator](../list/const_reverse_iterator/) [rbegin](../list/rbegin/)() const | स्थिर (const) संग्रह के अंतिम तत्व (रिवर्स में पहला) के लिए रिवर्स इटरेटर प्राप्त करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) की स्ट्रिंग और nullptr के केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) की स्ट्रिंग्स के केस के लिए विशेषीकरण। |
| **bool** [Remove](../list/remove/)(const T\&) override | सूची से विशिष्ट आइटम का पहला उदाहरण हटाता है। |
| int [RemoveAll](../list/removeall/)([Predicate](../../system/predicate/)\<T\>) | विशिष्ट प्रेडिकेट से मेल खाने वाले सभी तत्व हटाता है। |
| void [RemoveAt](../list/removeat/)(int) override | निर्दिष्ट स्थिति पर आइटम हटाता है। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से शेयर्ड रेफ़रेंस काउंट घटाता है। |
| void [RemoveRange](../list/removerange/)(int, int) | सूची की स्लाइस हटाता है। |
| [reverse_iterator](../list/reverse_iterator/) [rend](../list/rend/)() | संग्रह की शुरुआत से पहले एक गैर-मौजूद तत्व के लिए रिवर्स इटरेटर प्राप्त करता है। |
| [const_reverse_iterator](../list/const_reverse_iterator/) [rend](../list/rend/)() const | स्थिर (const) संग्रह की शुरुआत से पहले एक गैर-मौजूद तत्व के लिए रिवर्स इटरेटर प्राप्त करता है। |
| void [Reverse](../list/reverse/)() | पूरी सूची के तत्वों का क्रम उलट देता है। |
| void [Reverse](../list/reverse/)(int, int) | सूची स्लाइस के तत्वों का क्रम उलट देता है। |
| void [set_Capacity](../list/set_capacity/)(int) | सूची की क्षमता सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्युमेंट को विंड पॉइंटर (शेर्ड के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को विंड मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | शेयर्ड रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | शेयर्ड रेफ़रेंस काउंट बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | शेयर्ड रेफ़रेंस काउंट घटाता और लौटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| void [Sort](../list/sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | सूची के तत्वों को सॉर्ट करता है। |
| void [Sort](../list/sort/)() | डिफ़ॉल्ट कंपेरेटर का उपयोग करके सूची के तत्वों को सॉर्ट करता है। |
| void [Sort](../list/sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>) | सूची स्लाइस के तत्वों को सॉर्ट करता है। |
| void [Sort](../list/sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | सूची के तत्वों को सॉर्ट करता है। |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](../list/toarray/)() const | सूची को ऐरे में परिवर्तित करता है। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम वस्तुओं को स्ट्रिंग में बदलने में सक्षम बनाता है। |
| void [TrimExcess](../list/trimexcess/)() | सूची की क्षमता को उसके आकार के अनुसार समायोजित करता है। |
| **bool** [TrueForAll](../list/trueforall/)([System::Predicate](../../system/predicate/)\<T\>) | जाँचता है कि संग्रह में प्रत्येक तत्व निर्दिष्ट प्रेडिकेट द्वारा परिभाषित शर्तों को मिलाता है या नहीं। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() बयान के अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](../list/virtualizebeginconstiterator/)() const override | वर्तमान कंटेनर के begin const इटरेटर का कार्यान्वयन प्राप्त करता है। |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](../list/virtualizebeginiterator/)() override | वर्तमान कंटेनर के begin इटरेटर का कार्यान्वयन प्राप्त करता है। |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](../list/virtualizeendconstiterator/)() const override | वर्तमान कंटेनर के end const इटरेटर का कार्यान्वयन प्राप्त करता है। |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](../list/virtualizeenditerator/)() override | वर्तमान कंटेनर के end इटरेटर का कार्यान्वयन प्राप्त करता है। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | विकड रेफ़रेंस काउंट बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | विकड रेफ़रेंस काउंट घटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual  [~ICollection](../icollection/~icollection/)() | डिस्ट्रक्टर। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## टाइपडिफ़

| टाइपडिफ़ | विवरण |
| --- | --- |
| [ThisType](./thistype/) |  |
| [ListType](./listtype/) |  |
| [BaseTypes](./basetypes/) |  |
| [ValueType](./valuetype/) |  |
| [BaseType](./basetype/) |  |

## देखें

* क्लास [List](../list/)
* क्लास [IListWrapper](../../system.collections/ilistwrapper/)
* नेमस्पेस [System::Collections::Generic](../)
* लाइब्रेरी [Aspose.Slides](../../)