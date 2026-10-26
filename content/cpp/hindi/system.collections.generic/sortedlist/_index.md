---
title: SortedList
second_title: Aspose.Slides for C++ API संदर्भ
description: "FlatMap संरचना को लपेटने वाली क्रमबद्ध सूची। इस क्लास की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का उदाहरण स्टैक पर या operator new का उपयोग करके कभी न बनाएं, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन त्रुटियाँ उत्पन्न हो सकती हैं। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शनों को तर्क के रूप में पास करने के लिए करें।"
type: docs
weight: 547
url: /hi/system.collections.generic/sortedlist/
---
## SortedList क्लास

Sorted list wrapping FlatMap structure. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename TKey,typename TValue>class SortedList : public System::Collections::Generic::SortedListHelper<TKey, TValue>,
                                                          public System::Collections::Generic::BaseDictionary<Detail::FlatMap<TKey, TValue, ComparerAdapter<TKey>>>
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TKey | कुंजी प्रकार। |
| TValue | मान प्रकार। |

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| virtual void [Add](../idictionary/add/)(const TKey\&, const TValue\&) | कंटेनर में कुंजी-मान युग्म जोड़ता है। |
| virtual void [Add](../icollection/add/)(const T\&) | संग्रह में तत्व जोड़ता है। |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | संग्रह के पहले तत्व (यदि कोई हो) की ओर इंगित करने वाला इटेरेटर प्राप्त करता है। इस इटेरेटर का उपयोग संदर्भित वस्तु को बदलने के लिए नहीं किया जा सकता क्योंकि [GetEnumerator()](../ienumerable/getenumerator/) T की एक कॉपी-ऑब्जेक्ट लौटाता है। |
| [const_iterator](../ienumerable/const_iterator/) [begin](../ienumerable/begin/)() const | संग्रह की const-योग्य इंस्टेंस के पहले तत्व (यदि कोई हो) की ओर इंगित करने वाला इटेरेटर प्राप्त करता है। |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../ienumerable/cbegin/)() const | संग्रह के पहले const-योग्य तत्व (यदि कोई हो) की ओर इंगित करने वाला इटेरेटर प्राप्त करता है। |
| [const_iterator](../ienumerable/const_iterator/) [cend](../ienumerable/cend/)() const | संग्रह के अंतिम const-योग्य तत्व (यदि कोई हो) के ठीक बाद की ओर इंगित करने वाला इटेरेटर प्राप्त करता है। |
| virtual void [Clear](../icollection/clear/)() | संग्रह से सभी तत्व हटाता है। |
| virtual **bool** [Contains](../icollection/contains/)(const T\&) const | जाँचता है कि तत्व संग्रह में मौजूद है या नहीं। |
| virtual **bool** [ContainsKey](../idictionary/containskey/)(const TKey\&) const | जाँचता है कि कंटेनर में कुंजी मौजूद है या नहीं। |
| void [CopyTo](../idictionary/copyto/)([ArrayPtr](../../system/arrayptr/)\<[KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\>, int) override | डिक्शनरी की सामग्री को मौजूदा ऐरे तत्वों में कॉपी करता है। |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | संग्रह के अंतिम const-योग्य तत्व (उलटे क्रम में पहला) की ओर इंगित करने वाला रिवर्स इटेरेटर प्राप्त करता है। |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | संग्रह की शुरुआत से पहले एक न मौजूद const-योग्य तत्व के लिए रिवर्स इटेरेटर प्राप्त करता है। |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | संग्रह के अंतिम तत्व (यदि कोई हो) के ठीक बाद की ओर इंगित करने वाला इटेरेटर प्राप्त करता है। इस इटेरेटर का उपयोग संदर्भित वस्तु को बदलने के लिए नहीं किया जा सकता क्योंकि [GetEnumerator()](../ienumerable/getenumerator/) T की एक कॉपी-ऑब्जेक्ट लौटाता है। |
| [const_iterator](../ienumerable/const_iterator/) [end](../ienumerable/end/)() const | const-योग्य इंस्टेंस के अंतिम तत्व (यदि कोई हो) के ठीक बाद की ओर इंगित करने वाला इटेरेटर प्राप्त करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार की वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग-पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN बराबर माने जाते हैं, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग-पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN बराबर माने जाते हैं, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| int [get_Capacity](./get_capacity/)() const | वर्तमान सूची क्षमता प्राप्त करता है। |
| virtual int [get_Count](../icollection/get_count/)() const | संग्रह में तत्वों की संख्या प्राप्त करता है। |
| **bool** [get_IsFixedSize](../idictionary/get_isfixedsize/)() const | जाँचता है कि संग्रह का आकार स्थिर है या नहीं। |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | जाँचता है कि संग्रह केवल-पढ़ने योग्य है या नहीं। |
| **bool** [get_IsSynchronized](../idictionary/get_issynchronized/)() const | जाँचता है कि कंटेनर थ्रेड-सेफ है या नहीं। |
| virtual [SharedPtr](../../system/sharedptr/)\<[IList](../ilist/)\<TKey\>\> [get_Keys](./get_keys/)() const | कुंजी संग्रह तक पहुँचता है। |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | वह ऑब्जेक्ट प्राप्त करता है जिसके माध्यम से संग्रह समन्वयित किया जा रहा है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[IList](../ilist/)\<TValue\>\> [get_Values](./get_values/)() const | मान संग्रह तक पहुँचता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | वर्तमान सूची के माध्यम से इटररेट करने वाला एन्यूमरेटर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानार्थी। |
| virtual TValue [GetValueOrDefault](../idictionary/getvalueordefault/)(const TKey\&) const | यदि मिला तो मान लौटाता है; अन्यथा **Value()**। |
| virtual TValue [GetValueOrDefault](../idictionary/getvalueordefault/)(const TKey\&, const TValue\&) const | यदि मिला तो मान लौटाता है; अन्यथा **defaultValue**। |
| virtual TValue [GetValueOrNull](../idictionary/getvalueornull/)(const TKey\&) const | यदि मिला तो मान लौटाता है; अन्यथा **null**, यह केवल रेफ़रेंस प्रकारों के लिए लागू है। |
|  [ICollection](../icollection/icollection/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | कॉपी कन्स्ट्रक्टर। |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | मूव कन्स्ट्रक्टोर। |
| virtual TValue [idx_get](../idictionary/idx_get/)(const TKey\&) const | गेटर फ़ंक्शन। |
| virtual void [idx_set](../idictionary/idx_set/)(const TKey\&, TValue) | सेटर फ़ंक्शन। |
| int [IndexOfKey](./indexofkey/)(TKey) const | विशिष्ट कुंजी की खोज करता है। |
| int [IndexOfValue](./indexofvalue/)(TValue) const | विशिष्ट मान की खोज करता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार की इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानार्थी। |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | एक अनुक्रम पर एकरीमेंटर फ़ंक्शन लागू करता है। |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | निर्धारित करता है कि क्या अनुक्रम के सभी तत्व किसी शर्त को संतुष्ट करते हैं। |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | निर्धारित करता है कि अनुक्रम में कोई तत्व हैं या नहीं। |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | निर्धारित करता है कि अनुक्रम का कोई तत्व मौजूद है या शर्त को संतुष्ट करता है। |
| T [LINQ_Average](../ienumerable/linq_average/)() | संख्यात्मक मानों की अनुक्रम का औसत गणना करता है। |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | इनपुट अनुक्रम के प्रत्येक तत्व पर ट्रांसफ़ॉर्म फ़ंक्शन को बुलाकर मानों की अनुक्रम का औसत गणना करता है। |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | तत्वों को निर्दिष्ट प्रकार में कास्ट करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | दो अनुक्रमों को जोड़ता है। |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | निर्धारित करता है कि अनुक्रम में निर्दिष्ट मान है या नहीं। |
| int [LINQ_Count](../ienumerable/linq_count/)() | अनुक्रम में तत्वों की संख्या लौटाता है (प्रत्यक्ष गिनती द्वारा गणना किया गया)। |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | अनुक्रम में उन तत्वों की संख्या लौटाता है जो निर्दिष्ट शर्त को संतुष्ट करते हैं। |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | अनुक्रम में निर्दिष्ट इंडेक्स पर तत्व लौटाता है। |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | अनुक्रम में निर्दिष्ट इंडेक्स पर तत्व लौटाता है। |
| T [LINQ_First](../ienumerable/linq_first/)() | अनुक्रम का पहला तत्व लौटाता है। |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | अनुक्रम का पहला तत्व लौटाता है जो निर्दिष्ट शर्त को संतुष्ट करता है। |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | अनुक्रम का पहला तत्व लौटाता है, या यदि अनुक्रम खाली है तो डिफ़ॉल्ट मान। |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | अनुक्रम का पहला तत्व लौटाता है जो शर्त को संतुष्ट करता है, या यदि ऐसा कोई तत्व नहीं मिला तो डिफ़ॉल्ट मान। |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | अनुक्रम के तत्वों को समूहित करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | अनुक्रम के तत्वों को समूहित करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | अनुक्रम का अंतिम तत्व लौटाता है। |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | अनुक्रम का अंतिम तत्व लौटाता है, या यदि अनुक्रम खाली है तो डिफ़ॉल्ट मान। |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | प्रत्येक तत्व पर ट्रांसफ़ॉर्म फ़ंक्शन को लागू करता है और अधिकतम प्राप्त मान लौटाता है। |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | प्रत्येक तत्व पर ट्रांसफ़ॉर्म फ़ंक्शन को लागू करता है और न्यूनतम प्राप्त मान लौटाता है। |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | निर्दिष्ट प्रकार के आधार पर अनुक्रम के तत्वों को फ़िल्टर करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | की चयनकर्ता द्वारा चयनित कुंजी मानों के अनुसार अनुक्रम के तत्वों को आरोही क्रम में सॉर्ट करता है। |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | की चयनकर्ता द्वारा चयनित कुंजी मानों के अनुसार अनुक्रम के तत्वों को अवरोही क्रम में सॉर्ट करता है। |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | अनुक्रम में तत्वों का क्रम उलटता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | अनुक्रम के तत्वों को रूपांतरण करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | तत्व के इंडेक्स को सम्मिलित करके अनुक्रम के प्रत्येक तत्व को नए रूप में परिवर्तित करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | प्रत्येक तत्व को प्रोजेक्ट करता है और परिणामी अनुक्रमों को एक ही अनुक्रम में संयोजित करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | अनुक्रम की शुरुआत से निर्दिष्ट संख्या में सतत तत्वों को छोड़ देता है और शेष लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | अनुक्रम की शुरुआत से निर्दिष्ट संख्या में सतत तत्व लौटाता है। |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | अनुक्रम से एक ऐरे बनाता है। |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | अनुक्रम से एक List<T> बनाता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | निर्दिष्ट प्रेडिकेट के आधार पर अनुक्रम को फ़िल्टर करता है। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानार्थी। कस्टम प्रकारों को क्लोन करने को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारम्भ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट प्रारम्भ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | मूव असाइनमेंट ऑपरेटर। |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | मूव असाइनमेंट ऑपरेटर। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट प्रारम्भ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | संग्रह के अंतिम तत्व (उलटे क्रम में पहला) की ओर इंगित करने वाला रिवर्स इटेरेटर प्राप्त करता है। |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | const-योग्य संग्रह के अंतिम तत्व (उलटे क्रम में पहला) की ओर इंगित करने वाला रिवर्स इटेरेटर प्राप्त करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस-कम्पेयर वैल्यू-टाइप ऑब्जेक्ट को nullptr से करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण, स्ट्रिंग और nullptr के मामले के लिए। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण, स्ट्रिंग्स के मामले के लिए। |
| virtual **bool** [Remove](../idictionary/remove/)(const TKey\&) | कंटेनर से कुंजी हटाता है। |
| virtual **bool** [Remove](../icollection/remove/)(const T\&) | संग्रह से तत्व हटाता है। |
| void [RemoveAt](./removeat/)(int) | निर्दिष्ट स्थान पर आइटम हटाता है। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंटर को घटाता है। |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | संग्रह की शुरुआत से पहले एक न मौजूद तत्व के लिए रिवर्स इटेरेटर प्राप्त करता है। |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | const-योग्य संग्रह की शुरुआत से पहले एक न मौजूद तत्व के लिए रिवर्स इटेरेटर प्राप्त करता है। |
| void [set_Capacity](./set_capacity/)(int) | वर्तमान सूची क्षमता सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्ग्यूमेंट को कमजोर पॉइंटर (साझा के बजाय) सेट करता है। कंटेनर में पॉइंटर को कमजोर मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंटर को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; बल्कि स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंटर को घटाता है और लौटाता है। सीधे कॉल नहीं करना चाहिए; बल्कि स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
|  [SortedList](./sortedlist/)() | खाली सूची बनाता है। |
|  [SortedList](./sortedlist/)(const [SharedPtr](../../system/sharedptr/)\<[IComparer](../icomparer/)\<TKey\>\>\&) | खाली सूची बनाता है। |
|  [SortedList](./sortedlist/)(const [SharedPtr](../../system/sharedptr/)\<[IDictionary](../idictionary/)\<TKey, TValue\>\>\&) | कॉपी कन्स्ट्रक्टर। |
|  [SortedList](./sortedlist/)(const [map_t](./map_t/)\&) | कॉपी कन्स्ट्रक्टर। |
|  [SortedList](./sortedlist/)(int) | खाली सूची बनाता है। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| virtual **bool** [TryGetValue](../idictionary/trygetvalue/)(const TKey\&, TValue\&) const | मान की खोज करता है और यदि मिला तो उसे पुनः प्राप्त करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../ienumerable/virtualizebeginconstiterator/)() const | वर्तमान कंटेनर के लिए begin const इटेरेटर की इम्प्लीमेंटेशन प्राप्त करता है। |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../ienumerable/virtualizebeginiterator/)() | वर्तमान कंटेनर के लिए begin इटेरेटर की इम्प्लीमेंटेशन प्राप्त करता है। |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../ienumerable/virtualizeendconstiterator/)() const | वर्तमान कंटेनर के लिए end const इटेरेटर की इम्प्लीमेंटेशन प्राप्त करता है। |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../ienumerable/virtualizeenditerator/)() | वर्तमान कंटेनर के लिए end इटेरेटर की इम्प्लीमेंटेशन प्राप्त करता है। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंटर को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; बल्कि स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंटर को घटाता है। सीधे कॉल नहीं करना चाहिए; बल्कि स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual  [~ICollection](../icollection/~icollection/)() | डिस्ट्रक्टर। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## टाइपडेफ़

| टाइपडिफ़ | विवरण |
| --- | --- |
| [KeyCollection](./keycollection/) | कुंजी संग्रह प्रकार। |
| [ValueCollection](./valuecollection/) | मान संग्रह प्रकार। |
| [map_t](./map_t/) | अंतर्निहित डेटा प्रकार। |
| [this_t](./this_t/) | यह प्रकार। |
| [Ptr](./ptr/) | पॉइंटर प्रकार। |
| [KVPair](./kvpair/) | कुंजी-मान युग्म प्रकार। |
| [IEnumerablePtr](./ienumerableptr/) | समान युग्मों का संग्रह प्रकार। |
| [IEnumeratorPtr](./ienumeratorptr/) | **Enumerator** प्रकार। |
| [iterator](./iterator/) | इटेरेटर प्रकार। |
| [const_iterator](./const_iterator/) | कॉन्स्ट इटेरेटर प्रकार। |
| [reverse_iterator](./reverse_iterator/) | रिवर्स इटेरेटर प्रकार। |
| [const_reverse_iterator](./const_reverse_iterator/) | कॉन्स्ट रिवर्स इटेरेटर प्रकार। |

## देखें

* क्लास [SortedListHelper](../sortedlisthelper/)
* क्लास [BaseDictionary](../basedictionary/)
* नेमस्पेस [System::Collections::Generic](../)
* लाइब्रेरी [Aspose.Slides](../../)