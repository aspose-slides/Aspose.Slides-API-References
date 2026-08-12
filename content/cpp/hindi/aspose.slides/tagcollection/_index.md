---
title: TagCollection
second_title: Aspose.Slides for C++ API संदर्भ
description: टैग्स के संग्रह का प्रतिनिधित्व करता है (उपयोगकर्ता द्वारा परिभाषित स्ट्रिंग जोड़े)
type: docs
weight: 5435
url: /hi/aspose.slides/tagcollection/
---
## TagCollection क्लास

टैग्स (उपयोगकर्ता द्वारा परिभाषित स्ट्रिंग जोड़े) के संग्रह का प्रतिनिधित्व करता है।

```cpp
class TagCollection : public Aspose::Slides::ITagCollection
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| **int32_t** [Add](./add/)([System::String](../../system/string/), [System::String](../../system/string/)) override | संग्रह में नया टैग जोड़ता है। |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | संग्रह के पहले तत्व (यदि हो) की ओर इशारा करने वाला इटररेटर प्राप्त करता है। यह इटररेटर संदर्भित वस्तु को बदलने के लिये उपयोग नहीं किया जा सकता क्योंकि [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) T का कॉपी-ऑब्जेक्ट लौटाता है। |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | संग्रह के const-योग्य इंस्टांस के पहले तत्व (यदि हो) की ओर इशारा करने वाला इटररेटर प्राप्त करता है। |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | संग्रह के पहले const-योग्य तत्व (यदि हो) की ओर इशारा करने वाला इटररेटर प्राप्त करता है। |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | संग्रह के अंतिम const-योग्य तत्व के ठीक बाद की ओर इशारा करने वाला इटररेटर प्राप्त करता है। |
| void [Clear](./clear/)() override | संग्रह से सभी टैग हटाता है। |
| **bool** [Contains](./contains/)([System::String](../../system/string/)) override | निर्धारित करता है कि संग्रह में कोई विशिष्ट नाम मौजूद है या नहीं। |
| void [CopyTo](./copyto/)([System::ArrayPtr](../../system/arrayptr/)\<[System::Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<[System::String](../../system/string/), [System::String](../../system/string/)\>\>, **int32_t**) override | सभी तत्वों को निर्दिष्ट एरे में कॉपी करता है। |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | संग्रह के अंतिम तत्व (यदि हो) के ठीक बाद की ओर इशारा करने वाला इटररेटर प्राप्त करता है। यह इटररेटर संदर्भित वस्तु को बदलने के लिये उपयोग नहीं किया जा सकता क्योंकि [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) T का कॉपी-ऑब्जेक्ट लौटाता है। |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | const-योग्य इंस्टांस के अंतिम तत्व (यदि हो) के ठीक बाद की ओर इशारा करने वाला इटररेटर प्राप्त करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) क्रमश:शास्त्र का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रिफ़रेंस टाइप वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली का फ़्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN समान माने जाते हैं, यद्यपि IEC 60559:1989 के अनुसार NaN किसी भी मान से, NaN सहित, समान नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली का फ़्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN समान माने जाते हैं, यद्यपि IEC 60559:1989 के अनुसार NaN किसी भी मान से, NaN सहित, समान नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| **int32_t** [get_Count](./get_count/)() override | संग्रह में टैग्स की संख्या लौटाता है। पढ़ने-के-लिए-केवल **int32_t**। |
| **bool** [get_IsSynchronized](./get_issynchronized/)() override | लौटाता है कि क्या संग्रह तक पहुँच synchronized (थ्रेड-सेफ़) है। पढ़ने-के-लिए-केवल **bool**। |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_SyncRoot](./get_syncroot/)() override | एक synchronization root लौटाता है। पढ़ने-के-लिए-केवल [System::Object](../../system/object/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | वस्तु से सम्बंधित रेफरेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[System::Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<[System::String](../../system/string/), [System::String](../../system/string/)\>\>\> [GetEnumerator](./getenumerator/)() override | एक enumerator लौटाता है जो संग्रह को इटररेट करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समतुल्य। कस्टम वस्तुओं के हैशिंग को सक्षम करता है। |
| [System::String](../../system/string/) [GetNameByIndex](./getnamebyindex/)(**int32_t**) override | निर्दिष्ट अनुक्रमणिका पर टैग की कुंजी लौटाता है। |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [GetNamesOfTags](./getnamesoftags/)() override | टैग्स के नाम लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | वस्तु का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समतुल्य। |
| [System::String](../../system/string/) [GetValueByIndex](./getvaluebyindex/)(**int32_t**) override | निर्दिष्ट अनुक्रमणिका पर टैग का मान लौटाता है। |
| [System::String](../../system/string/) [idx_get](./idx_get/)([System::String](../../system/string/)) override | टैग की कुंजी-और-मान जोड़ी लौटाता है। |
| void [idx_set](./idx_set/)([System::String](../../system/string/), [System::String](../../system/string/)) override | टैग की कुंजी-और-मान जोड़ी सेट करता है। |
| **int32_t** [IndexOfName](./indexofname/)([System::String](../../system/string/)) override | संग्रह में निर्दिष्ट कुंजी का शून्य-आधारित अनुक्रमणिका लौटाता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि वस्तु targetType द्वारा वर्णित प्रकार की इंस्टांस है या नहीं। C# 'is' ऑपरेटर का समतुल्य। |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | क्रम पर एक accumulator फ़ंक्शन लागू करता है। |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | निर्धारित करता है कि क्या क्रम के सभी तत्व किसी शर्त को संतुष्ट करते हैं। |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | निर्धारित करता है कि क्रम में कोई तत्व है या नहीं। |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | निर्धारित करता है कि क्या क्रम में कोई तत्व मौजूद है या शर्त को संतुष्ट करता है। |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | संख्यात्मक मानों के क्रम का औसत निकालता है। |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | इनपुट क्रम के प्रत्येक तत्व पर ट्रांसफ़ॉर्म फ़ंक्शन लागू कर प्राप्त मानों के क्रम का औसत निकालता है। |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | तत्वों को निर्दिष्ट प्रकार में कास्ट करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | दो क्रमों को संयोजित करता है। |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | निर्धारित करता है कि क्रम में कोई निर्दिष्ट मान मौजूद है या नहीं। |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | क्रम में तत्वों की संख्या लौटाता है (प्रत्यक्ष गिनती द्वारा)। |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | क्रम में उन तत्वों की संख्या लौटाता है जो निर्दिष्ट शर्त को संतुष्ट करते हैं। |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | क्रम में निर्दिष्ट अनुक्रमणिका पर तत्व लौटाता है। |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | क्रम में निर्दिष्ट अनुक्रमणिका पर तत्व लौटाता है। |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | क्रम का पहला तत्व लौटाता है। |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | शर्त को संतुष्ट करने वाला पहला तत्व लौटाता है। |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | क्रम का पहला तत्व लौटाता है, या यदि क्रम खाली है तो डिफ़ॉल्ट मान। |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | शर्त को संतुष्ट करने वाला पहला तत्व लौटाता है, या यदि कोई ऐसा तत्व नहीं मिला तो डिफ़ॉल्ट मान। |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | क्रम के तत्वों को समूहित करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | क्रम के तत्वों को समूहित करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | क्रम का अंतिम तत्व लौटाता है। |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | क्रम का अंतिम तत्व लौटाता है, या यदि क्रम खाली है तो डिफ़ॉल्ट मान। |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | क्रम के प्रत्येक तत्व पर ट्रांसफ़ॉर्म फ़ंक्शन लागू करता है और अधिकतम प्राप्त मान लौटाता है। |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | क्रम के प्रत्येक तत्व पर ट्रांसफ़ॉर्म फ़ंक्शन लागू करता है और न्यूनतम प्राप्त मान लौटाता है। |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | निर्दिष्ट प्रकार के आधार पर क्रम के तत्वों को फ़िल्टर करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | keySelector द्वारा चुनी गई कुंजी मानों के अनुसार क्रम के तत्वों को आरोही क्रम में सॉर्ट करता है। |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | keySelector द्वारा चुनी गई कुंजी मानों के अनुसार क्रम के तत्वों को अवरोही क्रम में सॉर्ट करता है। |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | क्रम में तत्वों के क्रम को उल्टा करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | क्रम के तत्वों को रूपांतरित करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | प्रत्येक तत्व को उसके अनुक्रमणिका को सम्मिलित करके नई रूप में रूपांतरित करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | क्रम के प्रत्येक तत्व को प्रोजेक्ट करता है और परिणामी क्रमों को एक क्रम में संयोजित करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | क्रम की शुरुआत से निर्दिष्ट संख्या में क्रमिक तत्वों को छोड़ता है और शेष लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | क्रम की शुरुआत से निर्दिष्ट संख्या में क्रमिक तत्वों को लौटाता है। |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | क्रम से एक एरे बनाता है। |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | क्रम से एक List<T> बनाता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | निर्दिष्ट प्रेडिकेट के आधार पर क्रम को फ़िल्टर करता है। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट की लॉक को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समतुल्य। कस्टम प्रकारों की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सब-क्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सब-क्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू-टाइप ऑब्जेक्ट की nullptr से रेफ़रेंस-तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के केस के लिये [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स के केस के लिये [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| void [Remove](./remove/)([System::String](../../system/string/)) override | संग्रह से निर्दिष्ट नाम वाले टैग को हटाता है। |
| void [RemoveAt](./removeat/)(**int32_t**) override | निर्दिष्ट अनुक्रमणिका पर टैग को हटाता है। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से shared रेफ़रेंस काउंट को घटाता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nth टेम्पलेट आर्ग्यूमेंट को weak पॉइंटर सेट करता है (shared के बजाय)। कंटेनरों में पॉइंटर को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | वर्तमान shared रेफ़रेंस काउंटर मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | shared रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | shared रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समतुल्य। कस्टम वस्तुओं को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट की अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | वर्तमान कंटेनर के begin const इटररेटर का इम्प्लीमेंटेशन प्राप्त करता है। |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | वर्तमान कंटेनर के begin इटररेटर का इम्प्लीमेंटेशन प्राप्त करता है। |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | वर्तमान कंटेनर के end const इटररेटर का इम्प्लीमेंटेशन प्राप्त करता है। |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | वर्तमान कंटेनर के end इटररेटर का इम्प्लीमेंटेशन प्राप्त करता है। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## टिप्पणी

निम्न उदाहरण दिखाता है कि PowerPoint [Presentation](../presentation/) में टैग कैसे जोड़ें। 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto tags = pres->get_CustomData()->get_Tags();
pres->get_CustomData()->get_Tags()->idx_set(u"MyTag", u"My Tag Value");
```

## देखें भी

* क्लास [ITagCollection](../itagcollection/)
* नेमस्पेस [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)