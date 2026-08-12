---
title: LinkedList
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: LinkedList अग्र घोषणा।
type: docs
weight: 404
url: /hi/system.collections.generic/linkedlist/
---
## LinkedList क्लास

[LinkedList](./) फ़ॉरवर्ड घोषणा।

```cpp
template<typename T>class LinkedList : public virtual System::Object,
                                       public System::Collections::Generic::ICollection<T>,
                                       private System::Collections::Invalidatable
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | समाहित मान प्रकार। |

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| void [Add](./add/)(const T&) override | सूची के अंत में **तत्व** जोड़ता है। |
| [SharedPtr](../../system/sharedptr/)<[LinkedListNode](../linkedlistnode/)<T>> [AddAfter](./addafter/)(const [SharedPtr](../../system/sharedptr/)<[LinkedListNode](../linkedlistnode/)<T>>&, const T&) | सूची के **नोड** के बाद **तत्व** जोड़ता है। |
| void [AddAfter](./addafter/)(const [SharedPtr](../../system/sharedptr/)<[LinkedListNode](../linkedlistnode/)<T>>&, const [SharedPtr](../../system/sharedptr/)<[LinkedListNode](../linkedlistnode/)<T>>&) | सूची के **नोड** के बाद newNode जोड़ता है। |
| [SharedPtr](../../system/sharedptr/)<[LinkedListNode](../linkedlistnode/)<T>> [AddBefore](./addbefore/)(const [SharedPtr](../../system/sharedptr/)<[LinkedListNode](../linkedlistnode/)<T>>&, const T&) | सूची के **नोड** से पहले **तत्व** जोड़ता है। |
| void [AddBefore](./addbefore/)(const [SharedPtr](../../system/sharedptr/)<[LinkedListNode](../linkedlistnode/)<T>>&, const [SharedPtr](../../system/sharedptr/)<[LinkedListNode](../linkedlistnode/)<T>>&) | सूची के **नोड** से पहले newNode जोड़ता है। |
| [SharedPtr](../../system/sharedptr/)<[LinkedListNode](../linkedlistnode/)<T>> [AddFirst](./addfirst/)(const T&) | सूची की शुरुआत में **तत्व** जोड़ता है। |
| void [AddFirst](./addfirst/)(const [SharedPtr](../../system/sharedptr/)<[LinkedListNode](../linkedlistnode/)<T>>&) | सूची की शुरुआत में newNode जोड़ता है। |
| [SharedPtr](../../system/sharedptr/)<[LinkedListNode](../linkedlistnode/)<T>> [AddLast](./addlast/)(const T&) | सूची के अंत में **तत्व** जोड़ता है। |
| void [AddLast](./addlast/)(const [SharedPtr](../../system/sharedptr/)<[LinkedListNode](../linkedlistnode/)<T>>&) | सूची के अंत में newNode जोड़ता है। |
| [iterator](../ienumerable/iterator/) [begin](./begin/)() | संग्रह के पहले **तत्व** के लिए इटेरेटर प्राप्त करता है। |
| [const_iterator](../ienumerable/const_iterator/) [begin](./begin/)() const | कॉन्स्ट-योग्य संग्रह के पहले **तत्व** के लिए इटेरेटर प्राप्त करता है। |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](./cbegin/)() const | संग्रह में पहले कॉन्स्ट-योग्य **तत्व** के लिए इटेरेटर प्राप्त करता है। |
| [const_iterator](../ienumerable/const_iterator/) [cend](./cend/)() const | संग्रह के अंत के पीछे मौजूद गैर-मौजूद कॉन्स्ट-योग्य **तत्व** के लिए इटेरेटर प्राप्त करता है। |
| void [Clear](./clear/)() override | सूची में सभी **तत्व** हटाता है। |
| **bool** [Contains](./contains/)(const T&) const override | जाँचता है कि सूची में **तत्व** मौजूद है या नहीं। |
| void [CopyTo](./copyto/)([ArrayPtr](../../system/arrayptr/)<T>, int) override | कंटेनर डेटा को मौजूदा ऐरे **तत्व** में कॉपी करता है। |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | संग्रह के अंतिम कॉन्स्ट-योग्य **तत्व** के लिए एक रिवर्स इटेरेटर प्राप्त करता है (रिवर्स में पहला)। |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | संग्रह की शुरुआत से पहले मौजूद गैर-मौजूद कॉन्स्ट-योग्य **तत्व** के लिए रिवर्स इटेरेटर प्राप्त करता है। |
| [iterator](../ienumerable/iterator/) [end](./end/)() | संग्रह के अंत के पीछे मौजूद गैर-मौजूद **तत्व** के लिए इटेरेटर प्राप्त करता है। |
| [const_iterator](../ienumerable/const_iterator/) [end](./end/)() const | कॉन्स्ट-योग्य संग्रह के अंत के पीछे मौजूद गैर-मौजूद **तत्व** के लिए इटेरेटर प्राप्त करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सिद्धांतो का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if<[IsSmartPtr](../../system/issmartptr/)<T1>::value&&[IsSmartPtr](../../system/issmartptr/)<T2>::value, **bool**>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | C# शैली में रेफ़रेंस प्रकार की वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)<T1>::value&&\![IsSmartPtr](../../system/issmartptr/)<T2>::value, **bool**>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | C# शैली में वैल्यू प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const&, **float** const&) | C#-शैली का फ़्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, सहित NaN, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const&, **double** const&) | C#-शैली का फ़्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, सहित NaN, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase&, void **) const | केवल आंतरिक उपयोग के लिए। |
| [SharedPtr](../../system/sharedptr/)<[LinkedListNode](../linkedlistnode/)<T>> [Find](./find/)(const T&) const | सूची में **तत्व** को आगे की दिशा में खोजता है। |
| [SharedPtr](../../system/sharedptr/)<[LinkedListNode](../linkedlistnode/)<T>> [FindLast](./findlast/)(const T&) const | सूची में **तत्व** को रिवर्स दिशा में खोजता है। |
| int [get_Count](./get_count/)() const override | सूची में **तत्व** की संख्या प्राप्त करता है। |
| [SharedPtr](../../system/sharedptr/)<[LinkedListNode](../linkedlistnode/)<T>> [get_First](./get_first/)() const | सूची के पहले **तत्व** का पॉइंटर प्राप्त करता है। |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | जाँचता है कि संग्रह केवल-पढ़ने योग्य है या नहीं। |
| [SharedPtr](../../system/sharedptr/)<[LinkedListNode](../linkedlistnode/)<T>> [get_Last](./get_last/)() const | सूची के अंतिम **तत्व** का पॉइंटर प्राप्त करता है। |
| [SharedPtr](../../system/sharedptr/)<[Object](../../system/object/)> [get_SyncRoot](../icollection/get_syncroot/)() const | उस वस्तु को प्राप्त करता है जिसके द्वारा संग्रह सिंक्रनाइज़ किया जाता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | वस्तु से जुड़ी रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| [SharedPtr](../../system/sharedptr/)<[IEnumerator](../ienumerator/)<T>> [GetEnumerator](./getenumerator/)() override | वर्तमान [LinkedList](./) के माध्यम से इटेरेट करने के लिए एन्यूमरेटर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का तुल्य। कस्टम वस्तुओं के हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)& [GetType](../../system/object/gettype/)() const | वस्तु का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का तुल्य। |
| [ICollection](../icollection/icollection/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |
| [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)&) | कॉपी कन्स्ट्रक्टर। |
| [ICollection](../icollection/icollection/)([ICollection](../icollection/)&&) | मूव कन्स्ट्रक्टर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)&) const | जाँचता है कि वस्तु targetType द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# 'is' ऑपरेटर का तुल्य। |
| [LinkedList](./linkedlist/)() | खाली [LinkedList](./) बनाता है। |
| [LinkedList](./linkedlist/)(const [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>>&) | कॉपी कन्स्ट्रक्टर। |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)<T, T, T>&) | एक अनुक्रम पर एसेमुलेटर फ़ंक्शन लागू करता है। |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function<**bool**(T)>) | निर्धारित करता है कि क्या अनुक्रम के सभी **तत्व** एक शर्त को संतुष्ट करते हैं। |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | निर्धारित करता है कि अनुक्रम में कोई भी **तत्व** है या नहीं। |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function<**bool**(T)>) | निर्धारित करता है कि अनुक्रम में कोई **तत्व** मौजूद है या कोई शर्त संतुष्ट करता है। |
| T [LINQ_Average](../ienumerable/linq_average/)() | संख्यात्मक मानों के अनुक्रम का औसत गणना करता है। |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)<T, ResultType>&) | इनपुट अनुक्रम के प्रत्येक **तत्व** पर रूपांतर फ़ंक्शन को लागू करके प्राप्त होने वाले मानों के अनुक्रम का औसत गणना करता है। |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Cast](../ienumerable/linq_cast/)() | **तत्व** को निर्दिष्ट प्रकार में कास्ट करता है। |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>>>) | दो अनुक्रमों को जोड़ता है। |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | निर्धारित करता है कि अनुक्रम में निर्दिष्ट मान है या नहीं। |
| int [LINQ_Count](../ienumerable/linq_count/)() | अनुक्रम में **तत्व** की संख्या वापस करता है (सीधे गिनती द्वारा गणना)। |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)<T, **bool**>&) | निर्दिष्ट शर्त को संतुष्ट करने वाले अनुक्रम में **तत्व** की संख्या वापस करता है। |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | अनुक्रम में निर्दिष्ट सूचकांक पर **तत्व** वापस करता है। |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | अनुक्रम में निर्दिष्ट सूचकांक पर **तत्व** वापस करता है। |
| T [LINQ_First](../ienumerable/linq_first/)() | अनुक्रम का पहला **तत्व** वापस करता है। |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)<T, **bool**>&) | निर्दिष्ट शर्त को संतुष्ट करने वाले अनुक्रम का पहला **तत्व** वापस करता है। |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | अनुक्रम का पहला **तत्व** वापस करता है, या यदि अनुक्रम खाली है तो डिफ़ॉल्ट मान। |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function<**bool**(T)>) | शर्त को संतुष्ट करने वाला अनुक्रम का पहला **तत्व** वापस करता है, या यदि ऐसा कोई **तत्व** नहीं मिला तो डिफ़ॉल्ट मान। |
| [System::SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[System::SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, T>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<T, Key>) | एक अनुक्रम के **तत्व** को समूहित करता है। |
| [System::SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[System::SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Element>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<T, Key>, [System::Func](../../system/func/)<T, Element>) | एक अनुक्रम के **तत्व** को समूहित करता है। |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Source>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<Source, Key>) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Element>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<Source, Key>, [System::Func](../../system/func/)<Source, Element>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | अनुक्रम का अंतिम **तत्व** वापस करता है। |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | अनुक्रम का अंतिम **तत्व** वापस करता है, या यदि अनुक्रम खाली है तो डिफ़ॉल्ट मान। |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)<T, ResultType>&) | एक सामान्य अनुक्रम के प्रत्येक **तत्व** पर रूपांतरण फ़ंक्शन को लागू करता है और अधिकतम परिणाम मान वापस करता है। |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)<T, ResultType>&) | एक सामान्य अनुक्रम के प्रत्येक **तत्व** पर रूपांतरण फ़ंक्शन को लागू करता है और न्यूनतम परिणाम मान वापस करता है। |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_OfType](../ienumerable/linq_oftype/)() | निर्दिष्ट प्रकार के आधार पर अनुक्रम के **तत्व** को फ़िल्टर करता है। |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<T>> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)<T, Key>&) | keySelector द्वारा चयनित कुंजी मानों के अनुसार अनुक्रम के **तत्व** को आरोही क्रम में व्यवस्थित करता है। |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<Source>> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)<Source, Key>&) |  |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<T>> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)<T, Key>&) | keySelector द्वारा चयनित कुंजी मानों के अनुसार अनुक्रम के **तत्व** को अवरोही क्रम में व्यवस्थित करता है। |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<Source>> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)<Source, Key>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Reverse](../ienumerable/linq_reverse/)() | एक अनुक्रम में **तत्व** का क्रम उलटता है। |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<T, ResultType>&) | एक अनुक्रम के **तत्व** को रूपांतरित करता है। |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<T, **int32_t**, ResultType>&) | एक अनुक्रम के प्रत्येक **तत्व** को उसके सूचकांक को सम्मिलित करके नए रूप में रूपांतरित करता है। |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<Source, Result>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<Source, **int32_t**, Result>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)<T, [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>>> &) | एक अनुक्रम के प्रत्येक **तत्व** को प्रोजेक्ट करता है और प्राप्त अनुक्रमों को एक अनुक्रम में सम्मिलित करता है। |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)<Source, [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>>> &) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | एक अनुक्रम की शुरुआत से निर्दिष्ट संख्या में लगातार **तत्व** को छोड़ता है और शेष वापस करता है। |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | एक अनुक्रम की शुरुआत से निर्दिष्ट संख्या में लगातार **तत्व** वापस करता है। |
| [System::ArrayPtr](../../system/arrayptr/)<T> [LINQ_ToArray](../ienumerable/linq_toarray/)() | एक अनुक्रम से एरे बनाता है। |
| [SharedPtr](../../system/sharedptr/)<[List](../list/)<T>> [LINQ_ToList](../ienumerable/linq_tolist/)() | एक अनुक्रम से List<T> बनाता है। |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Where](../ienumerable/linq_where/)(std::function<**bool**(T)>) | निर्दिष्ट प्रेडिकेट के आधार पर एक अनुक्रम को फ़िल्टर करता है। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉक करने का कार्यान्वयन करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) संत्री ऑब्जेक्ट का प्रयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का तुल्य। कस्टम प्रकारों की क्लोनिंग को सक्षम करता है। |
| [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को इनिशियलाइज़ करता है। |
| [Object](../../system/object/object/)([Object](../../system/object/) const&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| [ICollection](../icollection/)& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)&&) | मूव असाइनमेंट ऑपरेटर। |
| [ICollection](../icollection/)& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)&) | मूव असाइनमेंट ऑपरेटर। |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | संग्रह के अंतिम **तत्व** के लिए रिवर्स इटेरेटर प्राप्त करता है (रिवर्स में पहला)। |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | कॉन्स्ट-योग्य संग्रह के अंतिम **तत्व** के लिए रिवर्स इटेरेटर प्राप्त करता है (रिवर्स में पहला)। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const&, [ptr](../../system/object/ptr/) const&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, T const&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, std::nullptr_t) | वैल्यू प्रकार के ऑब्जेक्ट की रेफ़रेंस के साथ nullptr की तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) की स्ट्रिंग और nullptr के केस के लिये विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, [String](../../system/string/) const&) | [Object::ReferenceEquals](../../system/object/referenceequals/) की स्ट्रिंग केस के लिये विशेषीकरण। |
| **bool** [Remove](./remove/)(const T&) override | सूची से निर्दिष्ट **तत्व** की पहली आवृत्ति को हटाता है। |
| void [Remove](./remove/)(const [SharedPtr](../../system/sharedptr/)<[LinkedListNode](../linkedlistnode/)<T>> &) | सूची से नोड हटाता है। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंटर घटाता है। |
| void [RemoveFirst](./removefirst/)() | सूची से पहला नोड हटाता है। |
| void [RemoveLast](./removelast/)() | सूची से अंतिम नोड हटाता है। |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | संग्रह की शुरुआत से पहले मौजूद गैर-मौजूद **तत्व** के लिये रिवर्स इटेरेटर प्राप्त करता है। |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | कॉन्स्ट-योग्य संग्रह की शुरुआत से पहले मौजूद गैर-मौजूद **तत्व** के लिये रिवर्स इटेरेटर प्राप्त करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्यूमेंट को कमजोर पॉइंटर (साझा के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को कमजोर मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंटर बढ़ाता है। सीधे कॉल न करें; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंटर घटाता है और वापस करता है। सीधे कॉल न करें; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का तुल्य। कस्टम ऑब्जेक्ट को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉक करने का कार्यान्वयन करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) संत्री ऑब्जेक्ट का प्रयोग करें। |
| System::Details::VirtualizedIteratorBase<T> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | वर्तमान कंटेनर के begin कॉन्स्ट इटेरेटर की इम्प्लीमेंटेशन प्राप्त करता है। |
| System::Details::VirtualizedIteratorBase<T> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | वर्तमान कंटेनर के begin इटेरेटर की इम्प्लीमेंटेशन प्राप्त करता है। |
| System::Details::VirtualizedIteratorBase<T> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | वर्तमान कंटेनर के end कॉन्स्ट इटेरेटर की इम्प्लीमेंटेशन प्राप्त करता है। |
| System::Details::VirtualizedIteratorBase<T> * [virtualizeEndIterator](./virtualizeenditerator/)() override | वर्तमान कंटेनर के end इटेरेटर की इम्प्लीमेंटेशन प्राप्त करता है। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंटर बढ़ाता है। सीधे कॉल न करें; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंटर घटाता है। सीधे कॉल न करें; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~ICollection](../icollection/~icollection/)() | डिस्ट्रक्टर। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## टाइपडिफ़्स

| टाइपडिफ़ | विवरण |
| --- | --- |
| [list_t](./list_t/) | आधार डेटा प्रकार। |
| [iterator](./iterator/) | इटेरेटर प्रकार। |
| [const_iterator](./const_iterator/) | कॉन्स्ट इटेरेटर प्रकार। |
| [reverse_iterator](./reverse_iterator/) | रिवर्स इटेरेटर प्रकार। |
| [const_reverse_iterator](./const_reverse_iterator/) | कॉन्स्ट रिवर्स इटेरेटर प्रकार। |

## टिप्पणी

Linked list कंटेनर। std::list के ऊपर एक रैपर लागू करता है। इस क्लास की वस्तुओं को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएं, क्योंकि इससे रन-टाइम त्रुटियाँ और/या असेर्शन फ़ॉल्ट्स हो सकते हैं। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शन को तर्क के रूप में पास करने के लिए करें।

```cpp
#include <system/collections/linkedlist.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // LinkedList क्लास का एक उदाहरण बनाएँ।
  auto list = MakeObject<LinkedList<int>>();

  // LinkedList को भरें।
  list->AddFirst(1);
  list->AddLast(30);
  list->AddAfter(list->get_First(), 15);
  list->AddBefore(list->get_Last(), 25);

  // LinkedList के आइटम प्रिंट करें।
  for (const auto item: list)
  {
    std::cout << item << ' ';
  }

  return 0;
}
/*
यह कोड उदाहरण निम्नलिखित आउटपुट उत्पन्न करता है:
1 15 25 30
*/
```

## देखें

* क्लास [Object](../../system/object/)
* क्लास [ICollection](../icollection/)
* क्लास [Invalidatable](../../system.collections/invalidatable/)
* नेमस्पेस [System::Collections::Generic](../)
* लाइब्रेरी [Aspose.Slides](../../)