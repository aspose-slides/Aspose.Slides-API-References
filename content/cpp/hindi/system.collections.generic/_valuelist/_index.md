---
title: _ValueList
second_title: "Aspose.Slides - C++ API संदर्भ"
description: "डिक्शनरी के मानों की सूची को लागू करता है। इस क्लास की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का उदाहरण कभी भी स्टैक पर या operator new का उपयोग करके न बनाएँ, क्योंकि इससे रन-टाइम त्रुटियां और/या एसेर्शन त्रुटियां हो सकती हैं। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शनों को तर्क के रूप में पास करने के लिए करें।"
type: docs
weight: 40
url: /hi/system.collections.generic/_valuelist/
---
## _ValueList क्लास

डिक्शनरी के मानों की सूची को लागू करता है। [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का प्रयोग करके ही इस क्लास की वस्तुओं को आवंटित किया जाना चाहिए। स्टैक पर या operator new का उपयोग करके इस प्रकार का उदाहरण कभी न बनाएँ, क्योंकि इससे रन-टाइम त्रुटियाँ और/या एसेर्शन त्रुटियाँ होंगी। इस क्लास को हमेशा [System::SmartPtr](../../system/smartptr/) पोइंटर में लपेटें और इस पोइंटर का उपयोग फ़ंक्शनों को तर्क के रूप में पास करने के लिए करें।

```cpp
template<typename Dict>class _ValueList : public System::Collections::Generic::_ValueCollection<Dict>
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Dict | [Dictionary](../dictionary/) प्रकार। |

## विधियाँ

| विधि | विवरण |
| --- | --- |
|  [_ValueCollection](../_valuecollection/_valuecollection/)(const typename Dict::Ptr\&) | निर्दिष्ट शब्दकोश को संदर्भित करता हुआ संग्रह को आरंभ करता है। |
|  [_ValueList](./_valuelist/)(const typename Dict::Ptr\&) | निर्दिष्ट शब्दकोश को संदर्भित करता हुआ संग्रह को आरंभ करता है। |
| void [Add](../ikvcollection/add/)(const T\&) override | कंटेनर में आइटम जोड़ता है। |
|  [BaseKVCollection](../basekvcollection/basekvcollection/)(const typename Dict::Ptr\&) | संग्रह बनाता है। |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | संग्रह के प्रथम तत्व (यदि मौजूद हो) की ओर संकेत करने वाला इटरेटर्स प्राप्त करता है। यह इटरेटर्स संदर्भित वस्तु को बदलने के लिए उपयोग नहीं किया जा सकता क्योंकि [GetEnumerator()](../ienumerable/getenumerator/) T की कॉपी वस्तु लौटाता है। |
| [const_iterator](../ienumerable/const_iterator/) [begin](../ienumerable/begin/)() const | संग्रह के const-क्वालिफाइड इंस्टेंस के प्रथम तत्व (यदि मौजूद हो) की ओर संकेत करने वाला इटरेटर्स प्राप्त करता है। |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../ienumerable/cbegin/)() const | संग्रह के प्रथम const-क्वालिफाइड तत्व (यदि मौजूद हो) की ओर संकेत करने वाला इटरेटर्स प्राप्त करता है। |
| [const_iterator](../ienumerable/const_iterator/) [cend](../ienumerable/cend/)() const | संग्रह के अंतिम const-क्वालिफाइड तत्व (यदि मौजूद हो) के तुरंत बाद का इटरेटर्स प्राप्त करता है। |
| void [Clear](../ikvcollection/clear/)() override | कंटेनर से सभी तत्व हटाता है। |
| **bool** [Contains](../_valuecollection/contains/)(const [TValue](../_valuecollection/tvalue/)\&) const override | जाँचता है कि आइटम कंटेनर में मौजूद है या नहीं। |
| void [CopyTo](../basekvcollection/copyto/)([ArrayPtr](../../system/arrayptr/)\<KV\>, int) override | मौजूदा एरे तत्वों में डेटा कॉपी करता है। |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | संग्रह के अंतिम तत्व (यदि मौजूद हो) के तुरंत बाद का इटरेटर्स प्राप्त करता है। यह इटरेटर्स संदर्भित वस्तु को बदलने के लिए उपयोग नहीं किया जा सकता क्योंकि [GetEnumerator()](../ienumerable/getenumerator/) T की कॉपी वस्तु लौटाता है। |
| [const_iterator](../ienumerable/const_iterator/) [end](../ienumerable/end/)() const | संग्रह के अंतिम तत्व (यदि मौजूद हो) के तुरंत बाद का इटरेटर्स प्राप्त करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) अर्थशास्त्र का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली का फ़्लोटिंग-पॉइंट तुलना बनाता है जहाँ दो NaN बराबर माने जाते हैं, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं है, यहाँ तक कि NaN के साथ भी नहीं। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली का फ़्लोटिंग-पॉइंट तुलना बनाता है जहाँ दो NaN बराबर माने जाते हैं, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं है, यहाँ तक कि NaN के साथ भी नहीं। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| int [get_Count](../basekvcollection/get_count/)() const override | तत्वों की संख्या प्राप्त करता है। |
| **bool** [get_IsFixedSize](../ilist/get_isfixedsize/)() | जाँचता है कि संग्रह की आकार स्थिर है या नहीं। |
| **bool** [get_IsReadOnly](../ikvcollection/get_isreadonly/)() const override | जाँचता है कि कंटेनर केवल-पढ़ने योग्य है या नहीं। |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | वह वस्तु प्राप्त करता है जिसके द्वारा संग्रह समन्वित किया जा रहा है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | वस्तु से जुड़ा रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<[TValue](../_valuecollection/tvalue/)\>\> [GetEnumerator](../_valuecollection/getenumerator/)() override | मानों के माध्यम से इटेरेटर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष। कस्टम वस्तुओं की हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | वस्तु का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
|  [ICollection](../icollection/icollection/)() | डिफ़ॉल्ट कंस्ट्रक्टर्स। |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | कॉपी कंस्ट्रक्टर। |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | मूव कंस्ट्रक्टर। |
| virtual [TValue](../_valuecollection/tvalue/) [idx_get](./idx_get/)(int) const | निर्दिष्ट स्थिति पर मान प्राप्त करता है। |
| void [idx_set](../ikvcollection/idx_set/)(int, T) override | सेटर फ़ंक्शन। |
| int [IndexOf](../ikvcollection/indexof/)(const T\&) const override | कंटेनर में आइटम का इंडेक्स प्राप्त करता है। |
| void [Insert](../ikvcollection/insert/)(int, const T\&) override | निर्दिष्ट स्थिति पर आइटम डालता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि वस्तु targetType द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | क्रम पर एक एग्रीगेटर फ़ंक्शन लागू करता है। |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | निर्धारित करता है कि क्या क्रम के सभी तत्व किसी शर्त को पूरा करते हैं। |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | निर्धारित करता है कि क्रम में कोई तत्व है या नहीं। |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | निर्धारित करता है कि क्या क्रम में कोई तत्व मौजूद है या शर्त को पूरा करता है। |
| T [LINQ_Average](../ienumerable/linq_average/)() | संख्यात्मक मानों के क्रम का औसत गणना करता है। |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | इनपुट क्रम के प्रत्येक तत्व पर ट्रांसफ़ॉर्म फ़ंक्शन लागू कर प्राप्त मानों के क्रम का औसत निकालता है। |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | तत्वों को निर्दिष्ट प्रकार में कास्ट करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | दो क्रमों को जोड़ता है। |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | निर्धारित करता है कि क्रम में निर्दिष्ट मान मौजूद है या नहीं। |
| int [LINQ_Count](../ienumerable/linq_count/)() | क्रम में तत्वों की संख्या लौटाता है (प्रत्यक्ष गिनती द्वारा)। |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | निर्दिष्ट शर्त को पूरा करने वाले क्रम में तत्वों की संख्या लौटाता है। |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | निर्दिष्ट इंडेक्स पर क्रम से तत्व लौटाता है। |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | निर्दिष्ट इंडेक्स पर क्रम से तत्व लौटाता है। |
| T [LINQ_First](../ienumerable/linq_first/)() | क्रम का पहला तत्व लौटाता है। |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | निर्दिष्ट शर्त को पूरा करने वाला क्रम का पहला तत्व लौटाता है। |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | क्रम का पहला तत्व लौटाता है, या यदि क्रम खाली है तो डिफ़ॉल्ट मान। |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | शर्त को पूरा करने वाला क्रम का पहला तत्व लौटाता है या यदि ऐसा कोई तत्व नहीं मिला तो डिफ़ॉल्ट मान। |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | क्रम के तत्वों को समूहित करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | क्रम के तत्वों को समूहित करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | क्रम का अंतिम तत्व लौटाता है। |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | क्रम का अंतिम तत्व लौटाता है, या यदि क्रम खाली है तो डिफ़ॉल्ट मान। |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | जनरल क्रम के प्रत्येक तत्व पर ट्रांसफ़ॉर्म फ़ंक्शन लागू करता है और अधिकतम परिणाम मान लौटाता है। |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | जनरल क्रम के प्रत्येक तत्व पर ट्रांसफ़ॉर्म फ़ंक्शन लागू करता है और न्यूनतम परिणाम मान लौटाता है। |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | निर्दिष्ट प्रकार के आधार पर क्रम के तत्वों को फ़िल्टर करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | की चयनकर्ता द्वारा चुनी गई कुंजी मानों के आधार पर क्रम के तत्वों को आरोही क्रम में सॉर्ट करता है। |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | की चयनकर्ता द्वारा चुनी गई कुंजी मानों के आधार पर क्रम के तत्वों को अवरोही क्रम में सॉर्ट करता है। |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | क्रम के तत्वों का क्रम उल्टा करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | क्रम के तत्वों को बदलता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | क्रम के प्रत्येक तत्व को उसके इंडेक्स को शामिल करके नई रूप में परिवर्तित करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | क्रम के प्रत्येक तत्व को प्रोजेक्ट करता है और परिणामी क्रमों को एक क्रम में संयोजित करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | क्रम की शुरुआत से निर्दिष्ट संख्या में क्रमागत तत्वों को छोड़ता है और शेष लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | क्रम की शुरुआत से निर्दिष्ट संख्या में क्रमागत तत्वों को लौटाता है। |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | क्रम से एक एरे बनाता है। |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | क्रम से एक List<T> बनाता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | निर्दिष्ट प्रेडिकेट के आधार पर क्रम को फ़िल्टर करता है। |
| void [Lock](../../system/object/lock/)() | C# lock() कथन के लॉक को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का प्रयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम प्रकारों की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को आरंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट आरंभ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | मूव असाइनमेंट ऑपरेटर। |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | मूव असाइनमेंट ऑपरेटर। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट आरंभ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | वस्तुओं की रेफ़रेंस से तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | वस्तुओं की रेफ़रेंस से तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस के द्वारा वैल्यू टाइप वस्तु की nullptr से तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) की स्ट्रिंग और nullptr केस के लिए विशिष्टता। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) की स्ट्रिंग्स केस के लिए विशिष्टता। |
| **bool** [Remove](../ikvcollection/remove/)(const T\&) override | कंटेनर से आइटम हटाता है। |
| void [RemoveAt](../ikvcollection/removeat/)(int) override | निर्दिष्ट स्थिति पर आइटम हटाता है। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंटर को घटाता है। |
| void [SetTemplateWeakPtr](../basekvcollection/settemplateweakptr/)(**uint32_t**) override | कम्पाइलेशन को सक्षम करता है, लेकिन वास्तविक रूप से कुछ नहीं करता क्योंकि यह संरचना डेटा का स्वामी नहीं है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंटर को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंटर को घटाता है और लौटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम वस्तुओं को स्ट्रिंग में परिवर्तित करना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() कथन का अनलॉक लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| System::Details::VirtualizedIteratorBase\<[TValue](../_valuecollection/tvalue/)\> * [virtualizeBeginConstIterator](../_valuecollection/virtualizebeginconstiterator/)() const override | वर्तमान कंटेनर के begin const इटरेटर्स की इम्प्लीमेंटेशन प्राप्त करता है। |
| System::Details::VirtualizedIteratorBase\<[TValue](../_valuecollection/tvalue/)\> * [virtualizeBeginIterator](../_valuecollection/virtualizebeginiterator/)() override | वर्तमान कंटेनर के begin इटरेटर्स की इम्प्लीमेंटेशन प्राप्त करता है। |
| System::Details::VirtualizedIteratorBase\<[TValue](../_valuecollection/tvalue/)\> * [virtualizeEndConstIterator](../_valuecollection/virtualizeendconstiterator/)() const override | वर्तमान कंटेनर के end const इटरेटर्स की इम्प्लीमेंटेशन प्राप्त करता है। |
| System::Details::VirtualizedIteratorBase\<[TValue](../_valuecollection/tvalue/)\> * [virtualizeEndIterator](../_valuecollection/virtualizeenditerator/)() override | वर्तमान कंटेनर के end इटरेटर्स की इम्प्लीमेंटेशन प्राप्त करता है। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Weak रेफ़रेंस काउंटर को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Weak रेफ़रेंस काउंटर को घटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~ICollection](../icollection/~icollection/)() | डिस्ट्रक्टर। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## टाइपडिफ़

| टाइपडिफ़ | विवरण |
| --- | --- |
| [TValue](./tvalue/) | मान प्रकार। |

## देखें

* क्लास [_ValueCollection](../_valuecollection/)
* नेमस्पेस [System::Collections::Generic](../)
* लाइब्रेरी [Aspose.Slides](../../)