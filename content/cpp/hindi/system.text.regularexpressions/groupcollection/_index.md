---
title: GroupCollection
second_title: C++ के लिए Aspose.Slides API रेफ़रेंस
description: "एकल मैच में कैप्चर समूहों की सूची। इस क्लास की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार के इंस्टेंस को स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या एसेर्शन त्रुटियाँ हो सकती हैं। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शनों को आर्ग्युमेंट के रूप में पास करने के लिए करें।"
type: docs
weight: 40
url: /hi/system.text.regularexpressions/groupcollection/
---
## GroupCollection क्लास

एकल मैच में कैप्चर समूहों की सूची। इस क्लास की वस्तुओं को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार के इंस्टेंस को स्टैक पर या operator new का उपयोग करके कभी न बनाएं, क्योंकि यह रनटाइम त्रुटियों और/या एसेर्शन त्रुटियों का कारण बन सकता है। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शनों को आर्ग्यूमेंट के रूप में पास करने के लिए करें।

```cpp
class GroupCollection : public System::Collections::Generic::List<GroupPtr>
```

## Methods

| Method | Description |
| --- | --- |
| void [_add_range](../../system.collections.generic/list/_add_range/)(std::initializer_list\<T\>) | C++ विशिष्ट। |
| void [Add](./add/)(const [GroupPtr](../groupptr/)\&) override | संग्रह में तत्व जोड़ने को निष्क्रिय करता है। |
| void [Add](../../system.collections.generic/list/add/)(const T\&) override | तत्व को सूची के अंत में जोड़ता है। |
| void [AddGroup](./addgroup/)(const [GroupPtr](../groupptr/)\&) | समूह को संग्रह में जोड़ता है। |
| void [AddInitializer](../../system.collections.generic/list/addinitializer/)(int, const T *) | प्रारंभिक मानों को अनुवादित करने के समय सूची में तत्व जोड़ता है। |
| void [AddRange](../../system.collections.generic/list/addrange/)([IEnumerablePtr](../../system.collections.generic/list/ienumerableptr/)) | संग्रह (या स्वयं) के सभी तत्वों को वर्तमान सूची के अंत में जोड़ता है। |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](../../system.collections.generic/list/asreadonly/)() | इस संग्रह का केवल-पढ़ने योग्य संदर्भ प्राप्त करता है। |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/list/begin/)() | संग्रह के पहले तत्व के लिए इटररेटर प्राप्त करता है। |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/list/begin/)() const | const-योग्य संग्रह के पहले तत्व के लिए इटररेटर प्राप्त करता है। |
| int [BinarySearch](../../system.collections.generic/list/binarysearch/)(const T\&) const | क्रमबद्ध सूची में आइटम खोजता है। |
| int [BinarySearch](../../system.collections.generic/list/binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) const | क्रमबद्ध सूची में आइटम खोजता है। |
| int [BinarySearch](../../system.collections.generic/list/binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) const | क्रमबद्ध सूची में आइटम खोजता है। |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/list/cbegin/)() const | const-योग्य संग्रह के पहले तत्व के लिए इटररेटर प्राप्त करता है। |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/list/cend/)() const | संग्रह के अंत के पीछे मौजूद गैर-मौजूद const-योग्य तत्व के लिए इटररेटर प्राप्त करता है। |
| void [Clear](./clear/)() override | संग्रह से तत्व हटाने को निष्क्रिय करता है। |
| **bool** [Contains](../../system.collections.generic/list/contains/)(const T\&) const override | जांचता है कि सूची में आइटम मौजूद है या नहीं। |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<OutputType\>\> [ConvertAll](../../system.collections.generic/list/convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | विभिन्न प्रकार में परिवर्तित तत्वों की सूची बनाता है। |
| void [CopyTo](../../system.collections.generic/list/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | सूची तत्वों को मौजूदा एरे तत्वों में कॉपी करता है। |
| void [CopyTo](../../system.collections.generic/list/copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | सभी तत्वों को मौजूदा एरे तत्वों में कॉपी करता है। |
| void [CopyTo](../../system.collections.generic/list/copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | निर्दिष्ट इंडेक्स से शुरू करके तत्वों को मौजूदा एरे में कॉपी करता है। |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [crbegin](../../system.collections.generic/list/crbegin/)() const | सूची के अंतिम const-योग्य तत्व (रिवर्स में पहला) के लिए रिवर्स इटररेटर प्राप्त करता है। |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [crend](../../system.collections.generic/list/crend/)() const | संग्रह की शुरुआत से पहले मौजूद गैर-मौजूद const-योग्य तत्व के लिए रिवर्स इटररेटर प्राप्त करता है। |
| [vector_t](../../system.collections.generic/list/vector_t/)\& [data](../../system.collections.generic/list/data/)() | अंतर्निहित डेटा संरचना तक पहुंच फ़ंक्शन। |
| const [vector_t](../../system.collections.generic/list/vector_t/)\& [data](../../system.collections.generic/list/data/)() const | अंतर्निहित डेटा संरचना तक पहुंच फ़ंक्शन। |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/list/end/)() | संग्रह के अंत के पीछे मौजूद गैर-मौजूद तत्व के लिए इटररेटर प्राप्त करता है। |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/list/end/)() const | const-योग्य संग्रह के अंत के पीछे मौजूद गैर-मौजूद तत्व के लिए इटररेटर प्राप्त करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) विशिष्टताओं का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-स्टाइल फ्लोटिंग-पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN बराबर माने जाते हैं, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-स्टाइल फ्लोटिंग-पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN बराबर माने जाते हैं, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN के बराबर नहीं होता। |
| **bool** [Exists](../../system.collections.generic/list/exists/)([System::Predicate](../../system/predicate/)\<T\>) | जांचता है कि सूची में निर्दिष्ट प्रेडिकेट को संतुष्ट करने वाला तत्व मौजूद है या नहीं। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिये। |
| T [Find](../../system.collections.generic/list/find/)([System::Predicate](../../system/predicate/)\<T\>) | निर्दिष्ट प्रेडिकेट को संतुष्ट करने वाला तत्व खोजता है। |
| [ListPtr](../../system.collections.generic/listptr/)\<T\> [FindAll](../../system.collections.generic/list/findall/)([System::Predicate](../../system/predicate/)\<T\>) | निर्दिष्ट प्रेडिकेट को संतुष्ट करने वाले तत्व खोजता है। |
| int [FindIndex](../../system.collections.generic/list/findindex/)([System::Predicate](../../system/predicate/)\<T\>) | निर्दिष्ट प्रेडिकेट को संतुष्ट करने वाला तत्व खोजता है। |
| int [FindIndex](../../system.collections.generic/list/findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | निर्दिष्ट प्रेडिकेट को संतुष्ट करने वाला तत्व खोजता है। |
| int [FindIndex](../../system.collections.generic/list/findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | निर्दिष्ट प्रेडिकेट को संतुष्ट करने वाला तत्व खोजता है। |
| T [FindLast](../../system.collections.generic/list/findlast/)([System::Predicate](../../system/predicate/)\<T\>) | निर्दिष्ट प्रेडिकेट को संतुष्ट करने वाला अंतिम तत्व खोजता है। |
| void [ForEach](../../system.collections.generic/list/foreach/)([System::Action](../../system/action/)\<T\>) | सूची के सभी तत्वों पर कार्रवाई लागू करता है। |
| int [get_Capacity](../../system.collections.generic/list/get_capacity/)() const | वर्तमान सूची क्षमता प्राप्त करता है। |
| int [get_Count](../../system.collections.generic/list/get_count/)() const override | वर्तमान सूची में तत्वों की संख्या प्राप्त करता है। |
| **bool** [get_IsFixedSize](../../system.collections.generic/ilist/get_isfixedsize/)() | जांचता है कि संग्रह का आकार निश्चित है या नहीं। |
| virtual **bool** [get_IsReadOnly](../../system.collections.generic/icollection/get_isreadonly/)() const | जांचता है कि संग्रह केवल-पढ़ने योग्य है या नहीं। |
| [GroupPtr](../groupptr/) [get_Item](./get_item/)(int) const | [Group](../group/) अभिगामी। |
| [GroupPtr](../groupptr/) [get_Item](./get_item/)(const [String](../../system/string/)\&) const | [Group](../group/) अभिगामी। |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | उस वस्तु को प्राप्त करता है जिसके माध्यम से संग्रह सिंक्रनाइज़ किया जाता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | वस्तु के साथ जुड़े रेफ़रेंस काउंटर डेटा संरचना को प्राप्त करता है। |
| [IEnumeratorPtr](../../system.collections.generic/list/ienumeratorptr/) [GetEnumerator](../../system.collections.generic/list/getenumerator/)() override | सूची के तत्वों पर इटररेट करने के लिये एनेमरेटर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स की हैशिंग सक्षम करता है। |
| **ThisPtr** [GetRange](../../system.collections.generic/list/getrange/)(int, int) | सूची का स्लाइस बनाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | वस्तु का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
|  [GroupCollection](./groupcollection/)(const [WeakPtr](../../system/weakptr/)\<[Match](../match/)\>\&) | कन्स्ट्रक्टर। |
|  [ICollection](../../system.collections.generic/icollection/icollection/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |
|  [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | कॉपी कन्स्ट्रक्टर। |
|  [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | मूव कन्स्ट्रक्टर। |
| virtual [GroupPtr](../groupptr/) [idx_get](./idx_get/)([String](../../system/string/)) const | [Group](../group/) अभिगामी। |
| [GroupPtr](../groupptr/) [idx_get](./idx_get/)(int) const override | [Group](../group/) अभिगामी। |
| void [idx_set](../../system.collections.generic/list/idx_set/)(int, T) override | निर्दिष्ट स्थिति पर तत्व सेट करता है। |
| int [IndexOf](../../system.collections.generic/list/indexof/)(const T\&) const override | निर्दिष्ट आइटम का पहला इंडेक्स प्राप्त करता है। |
| int [IndexOf](../../system.collections.generic/list/indexof/)(const T\&, int) const | सूची में निर्दिष्ट आइटम खोजता है। |
| void [Insert](../../system.collections.generic/list/insert/)(int, const T\&) override | निर्दिष्ट स्थिति पर आइटम सम्मिलित करता है। |
| void [InsertRange](../../system.collections.generic/list/insertrange/)(int, [IEnumerablePtr](../../system.collections.generic/list/ienumerableptr/)) | निर्दिष्ट स्थिति पर डेटा रेंज सम्मिलित करता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि वस्तु targetType द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| **bool** [IsReadOnly](./isreadonly/)() const | संग्रह को केवल-पढ़ने योग्य के रूप में चिह्नित करता है। |
| **int32_t** [LastIndexOf](../../system.collections.generic/list/lastindexof/)(const T\&) const | निर्दिष्ट वस्तु की खोज करता है और पूरी सूची में उसकी अंतिम उपस्थिति का शून्य-आधारित इंडेक्स लौटाता है। |
| **int32_t** [LastIndexOf](../../system.collections.generic/list/lastindexof/)(const T\&, **int32_t**) const | निर्दिष्ट वस्तु की खोज करता है और [List](../../system.collections.generic/list/) में तत्वों की रेंज के भीतर उसकी अंतिम उपस्थिति का शून्य-आधारित इंडेक्स लौटाता है। |
| **int32_t** [LastIndexOf](../../system.collections.generic/list/lastindexof/)(const T\&, **int32_t**, **int32_t**) const | निर्दिष्ट वस्तु की खोज करता है और [List](../../system.collections.generic/list/) में निर्दिष्ट संख्या के तत्वों की रेंज के भीतर उसकी अंतिम उपस्थिति का शून्य-आधारित इंडेक्स लौटाता है। |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | अनुक्रम पर एग्रीगेटर फ़ंक्शन लागू करता है। |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | निर्धारित करता है कि क्या अनुक्रम के सभी तत्व किसी शर्त को संतुष्ट करते हैं। |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | निर्धारित करता है कि क्या अनुक्रम में कोई तत्व है। |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | निर्धारित करता है कि क्या अनुक्रम में कोई तत्व मौजूद है या शर्त को संतुष्ट करता है। |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | संख्यात्मक मानों के अनुक्रम का औसत गणना करता है। |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | इनपुट अनुक्रम के प्रत्येक तत्व पर ट्रांसफ़ॉर्म फ़ंक्शन लागू करके प्राप्त मानों के अनुक्रम का औसत गणना करता है। |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | तत्वों को निर्दिष्ट प्रकार में कास्ट करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | दो अनुक्रमों को जोड़ता है। |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | निर्धारित करता है कि अनुक्रम में निर्दिष्ट मान मौजूद है या नहीं। |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | अनुक्रम में तत्वों की संख्या लौटाता है (सीधे गिनती द्वारा गणना किया गया)। |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | उन तत्वों की संख्या लौटाता है जो निर्दिष्ट शर्त को संतुष्ट करते हैं। |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | अनुक्रम में निर्दिष्ट इंडेक्स पर तत्व लौटाता है। |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | अनुक्रम में निर्दिष्ट इंडेक्स पर तत्व लौटाता है। |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | अनुक्रम का पहला तत्व लौटाता है। |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | शर्त को संतुष्ट करने वाले अनुक्रम के पहले तत्व को लौटाता है। |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | अनुक्रम का पहला तत्व लौटाता है, या अनुक्रम खाली होने पर डिफ़ॉल्ट मान। |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | शर्त को संतुष्ट करने वाले अनुक्रम के पहले तत्व को लौटाता है, या ऐसी कोई तत्व न मिलने पर डिफ़ॉल्ट मान। |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | अनुक्रम के तत्वों को समूहित करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | अनुक्रम के तत्वों को समूहित करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | अनुक्रम का अंतिम तत्व लौटाता है। |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | अनुक्रम का अंतिम तत्व लौटाता है, या अनुक्रम खाली होने पर डिफ़ॉल्ट मान। |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | जनरिक अनुक्रम के प्रत्येक तत्व पर ट्रांसफ़ॉर्म फ़ंक्शन लागू करता है और अधिकतम प्राप्त मान लौटाता है। |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | जनरिक अनुक्रम के प्रत्येक तत्व पर ट्रांसफ़ॉर्म फ़ंक्शन लागू करता है और न्यूनतम प्राप्त मान लौटाता है। |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | निर्दिष्ट प्रकार के आधार पर अनुक्रम के तत्वों को फ़िल्टर करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | keySelector द्वारा चयनित कुंजी मानों के अनुसार अनुक्रम के तत्वों को आरोही क्रम में क्रमबद्ध करता है। |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | keySelector द्वारा चयनित कुंजी मानों के अनुसार अनुक्रम के तत्वों को अवरोही क्रम में क्रमबद्ध करता है। |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | अनुक्रम के तत्वों के क्रम को उलटता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | अनुक्रम के तत्वों को ट्रांसफ़ॉर्म करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | प्रत्येक तत्व के इंडेक्स को शामिल करके अनुक्रम के प्रत्येक तत्व को नई रूप में ट्रांसफ़ॉर्म करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | प्रत्येक तत्व को प्रोजेक्ट करता है और परिणामस्वरूप अनुक्रमों को एक ही अनुक्रम में सम्मिलित करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | अनुक्रम के शुरुआती हिस्से से निर्दिष्ट संख्या में क्रमागत तत्वों को छोड़ता है और शेष लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | अनुक्रम के शुरुआती हिस्से से निर्दिष्ट संख्या में क्रमागत तत्वों को लौटाता है। |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | अनुक्रम से एक एरे बनाता है। |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | अनुक्रम से एक List<T> बनाता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | निर्दिष्ट प्रेडिकेट के आधार पर अनुक्रम को फ़िल्टर करता है। |
|  [List](../../system.collections.generic/list/list/)() | खाली सूची बनाता है। |
|  [List](../../system.collections.generic/list/list/)(int) | पूर्व-परिभाषित क्षमता के साथ सूची बनाता है। |
|  [List](../../system.collections.generic/list/list/)([IEnumerablePtr](../../system.collections.generic/list/ienumerableptr/)) | कॉपी कन्स्ट्रक्टर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सब-क्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सब-क्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | मूव असाइनमेंट ऑपरेटर। |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | मूव असाइनमेंट ऑपरेटर। |
| [GroupPtr](../groupptr/) [operator[]](./operator[]/)(const [String](../../system/string/)\&) const | [Group](../group/) अभिगामी। |
| vector_t::reference [operator[]](../../system.collections.generic/list/operator[]/)(int) | अभिगामी फ़ंक्शन। |
| vector_t::const_reference [operator[]](../../system.collections.generic/list/operator[]/)(int) const | अभिगामी फ़ंक्शन। |
| [reverse_iterator](../../system.collections.generic/list/reverse_iterator/) [rbegin](../../system.collections.generic/list/rbegin/)() | संग्रह के अंतिम तत्व (रिवर्स में पहला) के लिए रिवर्स इटररेटर प्राप्त करता है। |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [rbegin](../../system.collections.generic/list/rbegin/)() const | const-योग्य संग्रह के अंतिम तत्व (रिवर्स में पहला) के लिए रिवर्स इटररेटर प्राप्त करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | nullptr के साथ वैल्यू-टाइप ऑब्जेक्ट की रेफ़रेंस-तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स के केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| **bool** [Remove](./remove/)(const [GroupPtr](../groupptr/)\&) override | संग्रह से तत्व हटाने को निष्क्रिय करता है। |
| **bool** [Remove](../../system.collections.generic/list/remove/)(const T\&) override | सूची से विशिष्ट आइटम की पहली घटना को हटाता है। |
| int [RemoveAll](../../system.collections.generic/list/removeall/)([Predicate](../../system/predicate/)\<T\>) | निर्दिष्ट प्रेडिकेट को संतुष्ट करने वाले सभी तत्वों को हटाता है। |
| void [RemoveAt](../../system.collections.generic/list/removeat/)(int) override | निर्दिष्ट स्थिति पर आइटम हटाता है। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट को घटाता है। |
| void [RemoveRange](../../system.collections.generic/list/removerange/)(int, int) | सूची का स्लाइस हटाता है। |
| [reverse_iterator](../../system.collections.generic/list/reverse_iterator/) [rend](../../system.collections.generic/list/rend/)() | संग्रह की शुरुआत से पहले एक गैर-मौजूद तत्व के लिए रिवर्स इटररेटर प्राप्त करता है। |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [rend](../../system.collections.generic/list/rend/)() const | const-योग्य संग्रह की शुरुआत से पहले एक गैर-मौजूद तत्व के लिए रिवर्स इटररेटर प्राप्त करता है। |
| void [Reverse](../../system.collections.generic/list/reverse/)() | पूरी सूची के तत्वों का क्रम उलटता है। |
| void [Reverse](../../system.collections.generic/list/reverse/)(int, int) | सूची स्लाइस के तत्वों का क्रम उलटता है। |
| void [set_Capacity](../../system.collections.generic/list/set_capacity/)(int) | सूची क्षमता सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | टेम्प्लेट के n-वें आर्ग्यूमेंट को weak पॉइंटर (shared के बजाय) बनाता है। कंटेनर में पॉइंटर को weak मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| void [Sort](../../system.collections.generic/list/sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) | सूची के तत्वों को क्रमबद्ध करता है। |
| void [Sort](../../system.collections.generic/list/sort/)() | डिफ़ॉल्ट कम्पैरटर का उपयोग करके सूची के तत्वों को क्रमबद्ध करता है। |
| void [Sort](../../system.collections.generic/list/sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>) | सूची स्लाइस के तत्वों को क्रमबद्ध करता है। |
| void [Sort](../../system.collections.generic/list/sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | सूची के तत्वों को क्रमबद्ध करता है। |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](../../system.collections.generic/list/toarray/)() const | सूची को एरे में परिवर्तित करता है। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| void [TrimExcess](../../system.collections.generic/list/trimexcess/)() | सूची क्षमता को उनके आकार के अनुरूप बनाता है। |
| **bool** [TrueForAll](../../system.collections.generic/list/trueforall/)([System::Predicate](../../system/predicate/)\<T\>) | निर्धारित करता है कि क्या संग्रह के सभी तत्व निर्दिष्ट प्रेडिकेट द्वारा परिभाषित शर्तों को संतुष्ट करते हैं। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](../../system.collections.generic/list/virtualizebeginconstiterator/)() const override | वर्तमान कंटेनर के लिए const begin इटररेटर का कार्यान्वयन प्राप्त करता है। |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](../../system.collections.generic/list/virtualizebeginiterator/)() override | वर्तमान कंटेनर के लिए begin इटररेटर का कार्यान्वयन प्राप्त करता है। |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](../../system.collections.generic/list/virtualizeendconstiterator/)() const override | वर्तमान कंटेनर के लिए const end इटररेटर का कार्यान्वयन प्राप्त करता है। |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](../../system.collections.generic/list/virtualizeenditerator/)() override | वर्तमान कंटेनर के लिए end इटररेटर का कार्यान्वयन प्राप्त करता है। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | डेस्ट्रक्टर। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## Typedefs

| Typedef | Description |
| --- | --- |
| [Base](./base/) | बेस क्लास। |

## See Also

* क्लास [List](../../system.collections.generic/list/)
* नेमस्पेस [System::Text::RegularExpressions](../)
* लाइब्रेरी [Aspose.Slides](../../)