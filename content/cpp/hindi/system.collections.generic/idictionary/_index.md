---
title: IDictionary
second_title: Aspose.Slides for C++ API संदर्भ
description: "डिक्शनरी-समकक्ष कंटेनरों के लिए इंटरफ़ेस। इस वर्ग की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टैंस स्टैक पर या operator new का उपयोग करके कभी न बनाएं, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन फॉल्ट्स हो सकते हैं। हमेशा इस वर्ग को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग इसे फ़ंक्शन के तर्क के रूप में पास करने के लिए करें।"
type: docs
weight: 274
url: /hi/system.collections.generic/idictionary/
---
## IDictionary वर्ग

डिक्शनरी-समकक्ष कंटेनरों के लिए इंटरफ़ेस। इस वर्ग की वस्तुओं को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टैंस स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन फॉल्ट्स हो सकते हैं। हमेशा इस वर्ग को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग इसे फ़ंक्शन के तर्क के रूप में पास करने के लिए करें।

```cpp
template<typename TKey,typename TValue>class IDictionary : public System::Collections::Generic::ICollection<KeyValuePair<TKey, TValue>>
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TKey | कुंजी प्रकार। |
| TValue | मूल्य प्रकार। |

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual void [Add](./add/)(const TKey&, const TValue&) | कंटेनर में कुंजी-मूल्य जोड़ी जोड़ता है। |
| virtual void [Add](../icollection/add/)(const T&) | कलेक्शन में तत्व जोड़ता है। |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | कलेक्शन के पहले तत्व (यदि कोई हो) की ओर इशारा करने वाला इटेरेटर प्राप्त करता है। यह इटेरेटर संदर्भित वस्तु को बदलने के लिए उपयोग नहीं किया जा सकता क्योंकि [GetEnumerator()](../ienumerable/getenumerator/) T की कॉपी-ऑब्जेक्ट लौटाता है। |
| [const_iterator](../ienumerable/const_iterator/) [begin](../ienumerable/begin/)() const | कलेक्शन के const-योग्य इंस्टैंस के पहले तत्व (यदि कोई हो) की ओर इशारा करने वाला इटेरेटर प्राप्त करता है। |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../ienumerable/cbegin/)() const | कलेक्शन के पहले const-योग्य तत्व (यदि कोई हो) की ओर इशारा करने वाला इटेरेटर प्राप्त करता है। |
| [const_iterator](../ienumerable/const_iterator/) [cend](../ienumerable/cend/)() const | कलेक्शन के अंतिम const-योग्य तत्व (यदि कोई हो) के तुरंत बाद की ओर इशारा करने वाला इटेरेटर प्राप्त करता है। |
| virtual void [Clear](../icollection/clear/)() | कलेक्शन से सभी तत्वों को हटाता है। |
| virtual **bool** [Contains](../icollection/contains/)(const T&) const | जाँचता है कि तत्व कलेक्शन में मौजूद है या नहीं। |
| virtual **bool** [ContainsKey](./containskey/)(const TKey&) const | जाँचता है कि कंटेनर में कुंजी मौजूद है या नहीं। |
| void [CopyTo](./copyto/)([ArrayPtr](../../system/arrayptr/)<[KeyValuePair](../keyvaluepair/)<TKey, TValue>>, int) override | डिक्शनरी की सामग्री को मौजूदा ऐरे तत्वों में कॉपी करता है। |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | कलेक्शन के अंतिम तत्व (यदि कोई हो) के तुरंत बाद की ओर इशारा करने वाला इटेरेटर प्राप्त करता है। यह इटेरेटर संदर्भित वस्तु को बदलने के लिए उपयोग नहीं किया जा सकता क्योंकि [GetEnumerator()](../ienumerable/getenumerator/) T की कॉपी-ऑब्जेक्ट लौटाता है। |
| [const_iterator](../ienumerable/const_iterator/) [end](../ienumerable/end/)() const | const-योग्य कलेक्शन इंस्टैंस के अंतिम तत्व (यदि कोई हो) के तुरंत बाद की ओर इशारा करने वाला इटेरेटर प्राप्त करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके करता है। |
| static std::enable_if<[IsSmartPtr](../../system/issmartptr/)<T1>::value&&[IsSmartPtr](../../system/issmartptr/)<T2>::value, **bool**>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | C# शैली में रेफरेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)<T1>::value&&\![IsSmartPtr](../../system/issmartptr/)<T2>::value, **bool**>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const&, **float** const&) | C#-शैली के फ्लोटिंग पॉइंट तुलनात्मक को अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान, सहित NaN, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const&, **double** const&) | C#-शैली के फ्लोटिंग पॉइंट तुलनात्मक को अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान, सहित NaN, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase&, void **) const | केवल आंतरिक उपयोग के लिए। |
| virtual int [get_Count](../icollection/get_count/)() const | कलेक्शन में तत्वों की संख्या प्राप्त करता है। |
| **bool** [get_IsFixedSize](./get_isfixedsize/)() const | जाँचता है कि कलेक्शन का आकार स्थिर है या नहीं। |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | जाँचता है कि कलेक्शन केवल-पढ़ने योग्य है या नहीं। |
| **bool** [get_IsSynchronized](./get_issynchronized/)() const | जाँचता है कि कंटेनर थ्रेड-सेफ है या नहीं। |
| virtual [SharedPtr](../../system/sharedptr/)<[ICollection](../icollection/)<TKey>> [get_Keys](./get_keys/)() const | कुंजी संग्रह तक पहुँच प्राप्त करता है। |
| [SharedPtr](../../system/sharedptr/)<[Object](../../system/object/)> [get_SyncRoot](../icollection/get_syncroot/)() const | वह ऑब्जेक्ट प्राप्त करता है जिसके द्वारा कलेक्शन समन्वयित हो रहा है। |
| virtual [SharedPtr](../../system/sharedptr/)<[ICollection](../icollection/)<TValue>> [get_Values](./get_values/)() const | मूल्य संग्रह तक पहुँच प्राप्त करता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual [SharedPtr](../../system/sharedptr/)<[IEnumerator](../ienumerator/)<T>> [GetEnumerator](../ienumerable/getenumerator/)() | एन्यूमरेटर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष। अनुकूलित ऑब्जेक्ट्स को हैश करने में सक्षम बनाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| virtual TValue [GetValueOrDefault](./getvalueordefault/)(const TKey&) const | यदि मिला तो मान लौटाता है; अन्यथा **Value()**। |
| virtual TValue [GetValueOrDefault](./getvalueordefault/)(const TKey&, const TValue&) const | यदि मिला तो मान लौटाता है; अन्यथा **defaultValue**। |
| virtual TValue [GetValueOrNull](./getvalueornull/)(const TKey&) const | यदि मिला तो मान लौटाता है; अन्यथा **null**, जो केवल रेफ़रेंस टाइप्स के लिए अर्थपूर्ण है। |
| [ICollection](../icollection/icollection/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |
| [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)&) | कॉपी कन्स्ट्रक्टर। |
| [ICollection](../icollection/icollection/)([ICollection](../icollection/)&&) | मूव कन्स्ट्रक्टर। |
| virtual TValue [idx_get](./idx_get/)(const TKey&) const | गेटर फ़ंक्शन। |
| virtual void [idx_set](./idx_set/)(const TKey&, TValue) | सेटर फ़ंक्शन। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टैंस दर्शाता है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)<T, T, T>&) | एक अनुक्रम पर एक एक्क्यूम्युलेटर फ़ंक्शन लागू करता है। |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function<**bool**(T)>) | निर्धारित करता है कि अनुक्रम के सभी तत्व किसी शर्त को संतुष्ट करते हैं या नहीं। |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | निर्धारित करता है कि अनुक्रम में कोई भी तत्व है या नहीं। |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function<**bool**(T)>) | निर्धारित करता है कि अनुक्रम में कोई तत्व मौजूद है या शर्त को संतुष्ट करता है। |
| T [LINQ_Average](../ienumerable/linq_average/)() | संख्यात्मक मानों के अनुक्रम का औसत गणना करता है। |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)<T, ResultType>&) | इनपुट अनुक्रम के प्रत्येक तत्व पर ट्रांसफ़ॉर्म फ़ंक्शन लागू करके प्राप्त मानों के अनुक्रम का औसत गणना करता है। |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Cast](../ienumerable/linq_cast/)() | तत्वों को निर्दिष्ट प्रकार में कास्ट करता है। |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>>) | दो अनुक्रमों को जोड़ता है। |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | निर्धारित करता है कि अनुक्रम में निर्दिष्ट मान मौजूद है या नहीं। |
| int [LINQ_Count](../ienumerable/linq_count/)() | अनुक्रम में तत्वों की संख्या (प्रत्यक्ष गिनती द्वारा) लौटाता है। |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)<T, **bool**>&) | निर्धारित शर्त को संतुष्ट करने वाले अनुक्रम के तत्वों की संख्या लौटाता है। |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | अनुक्रम में निर्दिष्ट अनुक्रमांक पर तत्व लौटाता है। |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | अनुक्रम में निर्दिष्ट अनुक्रमांक पर तत्व लौटाता है। |
| T [LINQ_First](../ienumerable/linq_first/)() | अनुक्रम का पहला तत्व लौटाता है। |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)<T, **bool**>&) | निर्धारित शर्त को संतुष्ट करने वाला अनुक्रम का पहला तत्व लौटाता है। |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | अनुक्रम का पहला तत्व लौटाता है, या यदि अनुक्रम खाली है तो डिफ़ॉल्ट मान। |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function<**bool**(T)>) | शर्त को संतुष्ट करने वाला अनुक्रम का पहला तत्व, या यदि ऐसा तत्व न मिले तो डिफ़ॉल्ट मान लौटाता है। |
| [System::SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[System::SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, T>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<T, Key>) | अनुक्रम के तत्वों को समूहित करता है। |
| [System::SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[System::SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Element>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<T, Key>, [System::Func](../../system/func/)<T, Element>) | अनुक्रम के तत्वों को समूहित करता है। |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Source>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<Source, Key>) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Element>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<Source, Key>, [System::Func](../../system/func/)<Source, Element>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | अनुक्रम का अंतिम तत्व लौटाता है। |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | अनुक्रम का अंतिम तत्व लौटाता है, या यदि अनुक्रम खाली है तो डिफ़ॉल्ट मान। |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)<T, ResultType>&) | सामान्य अनुक्रम के प्रत्येक तत्व पर ट्रांसफ़ॉर्म फ़ंक्शन को लागू करता है और अधिकतम प्राप्त मान लौटाता है। |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)<T, ResultType>&) | सामान्य अनुक्रम के प्रत्येक तत्व पर ट्रांसफ़ॉर्म फ़ंक्शन को लागू करता है और न्यूनतम प्राप्त मान लौटाता है। |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_OfType](../ienumerable/linq_oftype/)() | निर्दिष्ट प्रकार के आधार पर अनुक्रम के तत्वों को फ़िल्टर करता है। |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<T>> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)<T, Key>&) | keySelector द्वारा चयनित कुंजी मूल्यों के अनुसार अनुक्रम के तत्वों को आरोही क्रम में सजाता है। |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<Source>> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)<Source, Key>&) |  |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<T>> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)<T, Key>&) | keySelector द्वारा चयनित कुंजी मूल्यों के अनुसार अनुक्रम के तत्वों को अवरोही क्रम में सजाता है। |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<Source>> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)<Source, Key>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Reverse](../ienumerable/linq_reverse/)() | अनुक्रम में तत्वों के क्रम को उलटा देता है। |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<T, ResultType>&) | अनुक्रम के तत्वों को ट्रांसफ़ॉर्म करता है। |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<T, **int32_t**, ResultType>&) | एक अनुक्रम के प्रत्येक तत्व को उसके सूचकांक को शामिल करके एक नए रूप में परिवर्तित करता है। |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<Source, Result>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<Source, **int32_t**, Result>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)<T, [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>>> &) | एक अनुक्रम के प्रत्येक तत्व को प्रोजेक्ट करता है और प्राप्त अनुक्रमों को एक ही अनुक्रम में संयोजित करता है। |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)<Source, [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>>> &) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | अनुक्रम की शुरुआत से निर्दिष्ट संख्या के क्रमागत तत्वों को छोड़ता है और शेष लौटाता है। |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | अनुक्रम की शुरुआत से निर्दिष्ट संख्या के क्रमागत तत्वों को लौटाता है। |
| [System::ArrayPtr](../../system/arrayptr/)<T> [LINQ_ToArray](../ienumerable/linq_toarray/)() | एक अनुक्रम से ऐरे बनाता है। |
| [SharedPtr](../../system/sharedptr/)<[List](../list/)<T>> [LINQ_ToList](../ienumerable/linq_tolist/)() | एक अनुक्रम से List<T> बनाता है। |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Where](../ienumerable/linq_where/)(std::function<**bool**(T)>) | निर्दिष्ट प्रेडिकेट के आधार पर अनुक्रम को फ़िल्टर करता है। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉक करने का कार्यान्वयन करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम टाइप्स को क्लोन करने में सक्षम बनाता है। |
| [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
| [Object](../../system/object/object/)([Object](../../system/object/) const&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासेज़ को कॉपी कन्स्ट्रक्ट करने की अनुमति देता है। |
| [ICollection](../icollection/)& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)&&) | मूव असाइनमेंट ऑपरेटर। |
| [ICollection](../icollection/)& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)&) | मूव असाइनमेंट ऑपरेटर। |
| [Object](../../system/object/)& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासेज़ को कॉपी कन्स्ट्रक्ट करने की अनुमति देता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const&, [ptr](../../system/object/ptr/) const&) | ऑब्जेक्ट्स की तुलना रेफ़रन्स द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, T const&) | ऑब्जेक्ट्स की तुलना रेफ़रन्स द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, [String](../../system/string/) const&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशेषीकरण। |
| virtual **bool** [Remove](./remove/)(const TKey&) | कंटेनर से कुंजी हटाता है। |
| virtual **bool** [Remove](../icollection/remove/)(const T&) | कलेक्शन से तत्व हटाता है। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n-वें टेम्पलेट तर्क को कमजोर पॉइंटर (साझा नहीं) सेट करता है। कंटेनरों में पॉइंटर्स को कमजोर मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने में सक्षम बनाता है। |
| virtual **bool** [TryGetValue](./trygetvalue/)(const TKey&, TValue&) const | मान की खोज करता है और यदि मिला तो उसे प्राप्त करता है। |
| static const [TypeInfo](../../system/typeinfo/)& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट का अनलॉक कार्यान्वयन करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../ienumerable/virtualizebeginconstiterator/)() const | वर्तमान कंटेनर के begin const इटेरेटर का कार्यान्वयन प्राप्त करता है। |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../ienumerable/virtualizebeginiterator/)() | वर्तमान कंटेनर के begin इटेरेटर का कार्यान्वयन प्राप्त करता है। |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../ienumerable/virtualizeendconstiterator/)() const | वर्तमान कंटेनर के end const इटेरेटर का कार्यान्वयन प्राप्त करता है। |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../ienumerable/virtualizeenditerator/)() | वर्तमान कंटेनर के end इटेरेटर का कार्यान्वयन प्राप्त करता है। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~ICollection](../icollection/~icollection/)() | डिस्ट्रक्टर। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## टाइपडिफ़्स

| टाइपडिफ़ | विवरण |
| --- | --- |
| [BaseType](./basetype/) | बेस इंटरफ़ेस प्रकार। |
| [KeyValuePairType](./keyvaluepairtype/) | कुंजी-मूल्य जोड़ी प्रकार। |

## संबंधित देखें

* क्लास [ICollection](../icollection/)
* नेमस्पेस [System::Collections::Generic](../)
* लाइब्रेरी [Aspose.Slides](../../)