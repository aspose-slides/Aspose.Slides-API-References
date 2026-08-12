---
title: ICollection
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: "तत्वों के संग्रह का इंटरफ़ेस। इस क्लास की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके आवंटित किया जाना चाहिए। कभी भी इस प्रकार का इंस्टांस स्टैक पर या operator new का उपयोग करके न बनाएँ, क्योंकि इससे रन-टाइम त्रुटियाँ और/या अभिकथन दोष उत्पन्न हो सकते हैं। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग करके इसे फ़ंक्शनों को तर्क के रूप में पास करें।"
type: docs
weight: 248
url: /hi/system.collections.generic/icollection/
---
## ICollection क्लास

तत्वों के संग्रह का इंटरफ़ेस। इस क्लास की वस्तुओं को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके आवंटित किया जाना चाहिए। कभी भी इस प्रकार का उदाहरण स्टैक पर या operator new का उपयोग करके न बनाएँ, क्योंकि इससे रन-टाइम त्रुटियाँ और/या अभिकथन त्रुटियाँ उत्पन्न होंगी। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग करके इसे फ़ंक्शनों को तर्क के रूप में पास करें।

```cpp
template<typename T>class ICollection : public virtual System::Collections::Generic::IEnumerable<T>
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual void [Add](./add/)(const T\&) | संग्रह में तत्व जोड़ता है। |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | संग्रह के पहले तत्व (यदि मौजूद हो) की ओर संकेत करने वाला इटरेटर प्राप्त करता है। यह इटरेटर संदर्भित वस्तु को बदलने के लिए उपयोग नहीं किया जा सकता क्योंकि [GetEnumerator()](../ienumerable/getenumerator/) T की प्रतिलिपि-ऑब्जेक्ट लौटाता है। |
| [const_iterator](../ienumerable/const_iterator/) [begin](../ienumerable/begin/)() const | संग्रह के const-योग्य इंस्टेंस के पहले तत्व (यदि मौजूद हो) की ओर संकेत करने वाला इटरेटर प्राप्त करता है। |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../ienumerable/cbegin/)() const | संग्रह के पहले const-योग्य तत्व (यदि मौजूद हो) की ओर संकेत करने वाला इटरेटर प्राप्त करता है। |
| [const_iterator](../ienumerable/const_iterator/) [cend](../ienumerable/cend/)() const | संग्रह के अंतिम const-योग्य तत्व (यदि मौजूद हो) के ठीक बाद की ओर संकेत करने वाला इटरेटर प्राप्त करता है। |
| virtual void [Clear](./clear/)() | संग्रह से सभी तत्व हटाता है। |
| virtual **bool** [Contains](./contains/)(const T\&) const | जांचता है कि तत्व संग्रह में मौजूद है या नहीं। |
| virtual void [CopyTo](./copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) | सभी संग्रह तत्वों को मौजूदा ऐरे तत्वों में कॉपी करता है। |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | संग्रह के अंतिम तत्व (यदि मौजूद हो) के ठीक बाद की ओर संकेत करने वाला इटरेटर प्राप्त करता है। यह इटरेटर संदर्भित वस्तु को बदलने के लिए उपयोग नहीं किया जा सकता क्योंकि [GetEnumerator()](../ienumerable/getenumerator/) T की प्रतिलिपि-ऑब्जेक्ट लौटाता है। |
| [const_iterator](../ienumerable/const_iterator/) [end](../ienumerable/end/)() const | संग्रह के const-योग्य इंस्टेंस के अंतिम तत्व (यदि मौजूद हो) के ठीक बाद की ओर संकेत करने वाला इटरेटर प्राप्त करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सिद्धांतों का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार की वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग-पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के साथ भी नहीं। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग-पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के साथ भी नहीं। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual int [get_Count](./get_count/)() const | संग्रह में तत्वों की संख्या प्राप्त करता है। |
| virtual **bool** [get_IsReadOnly](./get_isreadonly/)() const | जाँचता है कि संग्रह केवल-पढ़ने योग्य है या नहीं। |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](./get_syncroot/)() const | उस वस्तु को प्राप्त करता है जिसके माध्यम से संग्रह समकालीन किया जा रहा है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | वस्तु से जुड़े रेफ़रेंस काउंटर डेटा संरचना को प्राप्त करता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<T\>\> [GetEnumerator](../ienumerable/getenumerator/)() | एन्यूमेरेटर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) विधि का समानांतर। कस्टम वस्तुओं की हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | वस्तु का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
|  [ICollection](./icollection/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |
|  [ICollection](./icollection/)(const [ICollection](./)\&) | कॉपी कन्स्ट्रक्टर। |
|  [ICollection](./icollection/)([ICollection](./)\&&) | मूव कन्स्ट्रक्टर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि वस्तु targetType द्वारा वर्णित प्रकार का एक इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | किसी क्रम पर एक एक्यूमुलेटर फ़ंक्शन लागू करता है। |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | निर्धारित करता है कि क्या क्रम के सभी तत्व किसी शर्त को संतुष्ट करते हैं। |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | निर्धारित करता है कि क्या क्रम में कोई तत्व है। |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | निर्धारित करता है कि क्या क्रम में कोई तत्व मौजूद है या शर्त को संतुष्ट करता है। |
| T [LINQ_Average](../ienumerable/linq_average/)() | संख्यात्मक मानों के एक क्रम का औसत गणना करता है। |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | इनपुट क्रम के प्रत्येक तत्व पर एक ट्रांसफ़ॉर्म फ़ंक्शन को लागू करके प्राप्त मानों का औसत गणना करता है। |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | तत्वों को निर्दिष्ट प्रकार में कास्ट करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | दो क्रमों को जोड़ता है। |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | निर्धारित करता है कि क्या क्रम में निर्दिष्ट मान मौजूद है। |
| int [LINQ_Count](../ienumerable/linq_count/)() | क्रम में तत्वों की संख्या लौटाता है (प्रत्यक्ष गणना द्वारा निर्धारित)। |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | क्रम में उन तत्वों की संख्या लौटाता है जो निर्दिष्ट शर्त को संतुष्ट करते हैं। |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | क्रम में निर्दिष्ट सूचकांक पर तत्व लौटाता है। |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | क्रम में निर्दिष्ट सूचकांक पर तत्व लौटाता है। |
| T [LINQ_First](../ienumerable/linq_first/)() | क्रम का पहला तत्व लौटाता है। |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | क्रम का पहला तत्व लौटाता है जो निर्दिष्ट शर्त को संतुष्ट करता है। |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | क्रम का पहला तत्व लौटाता है, या यदि क्रम खाली है तो डिफ़ॉल्ट मान लौटाता है। |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | क्रम का वह पहला तत्व लौटाता है जो शर्त को संतुष्ट करता है, या यदि ऐसा तत्व नहीं मिलता तो डिफ़ॉल्ट मान लौटाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | क्रम के तत्वों को समूहित करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | क्रम के तत्वों को समूहित करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | क्रम का अंतिम तत्व लौटाता है। |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | क्रम का अंतिम तत्व लौटाता है, या यदि क्रम खाली है तो डिफ़ॉल्ट मान लौटाता है। |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | जनरिक क्रम के प्रत्येक तत्व पर एक ट्रांसफ़ॉर्म फ़ंक्शन को लागू करके प्राप्त अधिकतम मान लौटाता है। |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | जनरिक क्रम के प्रत्येक तत्व पर एक ट्रांसफ़ॉर्म फ़ंक्शन को लागू करके प्राप्त न्यूनतम मान लौटाता है। |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | निर्दिष्ट प्रकार के आधार पर क्रम के तत्वों को फ़िल्टर करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | क्रम के तत्वों को कुंजी चयनकर्ता द्वारा चुनी गई कुंजी मानों के अनुसार आरोही क्रम में व्यवस्थित करता है। |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | क्रम के तत्वों को कुंजी चयनकर्ता द्वारा चुनी गई कुंजी मानों के अनुसार अवरोही क्रम में व्यवस्थित करता है। |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | क्रम में तत्वों का क्रम उलट देता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | क्रम के तत्वों को बदलता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | क्रम के प्रत्येक तत्व को उसके अनुक्रमणिका को सम्मिलित करके नए रूप में बदलता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | क्रम के प्रत्येक तत्व को प्रोजेक्ट करता है और परिणामस्वरूप प्राप्त क्रमों को एक ही क्रम में मिलाता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | क्रम की शुरुआत से निरंतर तत्वों की निर्दिष्ट संख्या को छोड़कर शेष तत्व लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | क्रम की शुरुआत से निरंतर तत्वों की निर्दिष्ट संख्या लौटाता है। |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | क्रम से एक ऐरे बनाता है। |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | क्रम से एक List<T> बनाता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | निर्दिष्ट प्रेडिकेट के आधार पर क्रम को फ़िल्टर करता है। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट का लॉक लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) विधि का समानांतर। कस्टम प्रकारों की क्लोनिंग को सक्षम करता है। |
| [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को इनिशियलाइज़ करता है। |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| [ICollection](./)\& [operator=](./operator_equal/)([ICollection](./)\&&) | मूव असाइनमेंट ऑपरेटर। |
| [ICollection](./)\& [operator=](./operator_equal/)(const [ICollection](./)\&) | मूव असाइनमेंट ऑपरेटर। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू प्रकार की वस्तु की nullptr के साथ रेफ़रेंस-तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) की विशेषीकृत रूपांतरण, स्ट्रिंग और nullptr के मामले के लिए। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) की विशेषीकृत रूपांतरण, स्ट्रिंग्स के मामले के लिए। |
| virtual **bool** [Remove](./remove/)(const T\&) | संग्रह से तत्व हटाता है। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंटर को घटाता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n-वें टेम्पलेट आर्ग्यूमेंट को weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनरों में पॉइंटर को weak मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | वर्तमान साझा रेफ़रेंस काउंटर का मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंटर को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंटर को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) विधि का समानांतर। कस्टम वस्तुओं को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट का अनलॉक लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../ienumerable/virtualizebeginconstiterator/)() const | वर्तमान कंटेनर के begin const इटरेटर के कार्यान्वयन को प्राप्त करता है। |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../ienumerable/virtualizebeginiterator/)() | वर्तमान कंटेनर के begin इटरेटर के कार्यान्वयन को प्राप्त करता है। |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../ienumerable/virtualizeendconstiterator/)() const | वर्तमान कंटेनर के end const इटरेटर के कार्यान्वयन को प्राप्त करता है। |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../ienumerable/virtualizeenditerator/)() | वर्तमान कंटेनर के end इटरेटर के कार्यान्वयन को प्राप्त करता है। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंटर को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंटर को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~ICollection](./~icollection/)() | विनाशकर्ता। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## टाइपडिफ़

| टाइपडिफ़ | विवरण |
| --- | --- |
| [ValueType](./valuetype/) | वैल्यू प्रकार का नाम। |
| [ThisType](./thistype/) | संग्रह प्रकार का नाम। |

## देखें

* क्लास [IEnumerable](../ienumerable/)
* नेमस्पेस [System::Collections::Generic](../)
* लाइब्रेरी [Aspose.Slides](../../)