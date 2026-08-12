---
title: IBehaviorPropertyCollection
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: इफ़ेक्ट व्यवहार के लिए टाइमिंग प्रॉपर्टीज़ का प्रतिनिधित्व करता है।
type: docs
weight: 196
url: /hi/aspose.slides.animation/ibehaviorpropertycollection/
---
## IBehaviorPropertyCollection क्लास

इफ़ेक्ट व्यवहार के लिए टाइमिंग प्रॉपर्टीज़ का प्रतिनिधित्व करता है।

```cpp
class IBehaviorPropertyCollection : public System::Collections::Generic::IList<System::SharedPtr<Aspose::Slides::Animation::IBehaviorProperty>>
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| virtual void [Add](./add/)(const [System::String](../../system/string/)\&) | कलेक्शन में नई प्रॉपर्टी जोड़ता है। |
| virtual void [Add](../../system.collections.generic/icollection/add/)(const T\&) | कलेक्शन में तत्व जोड़ता है। |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | कलेक्शन के पहले तत्व (यदि कोई हो) की ओर इशारा करने वाला इटेरेटर लौटाता है। यह इटेरेटर रेफ़रेंस्ड ऑब्जेक्ट को बदलने के लिए उपयोग नहीं किया जा सकता क्योंकि [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) T का कॉपी-ऑब्जेक्ट लौटाता है। |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | कॉन्स्ट-कोटा की गई कलेक्शन इंस्टेंस के पहले तत्व (यदि कोई हो) की ओर इशारा करने वाला इटेरेटर लौटाता है। |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | कलेक्शन के पहले कॉन्स्ट-कोटा तत्व (यदि कोई हो) की ओर इशारा करने वाला इटेरेटर लौटाता है। |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | कलेक्शन के अंतिम कॉन्स्ट-कोटा तत्व के तुरंत बाद की ओर इशारा करने वाला इटेरेटर लौटाता है (यदि कोई हो)। |
| virtual void [Clear](../../system.collections.generic/icollection/clear/)() | कलेक्शन के सभी तत्वों को हटाता है। |
| virtual **bool** [Contains](./contains/)(const [System::String](../../system/string/)\&) const | निर्धारित करता है कि [ICollection](../../system.collections.generic/icollection/) में विशिष्ट मान मौजूद है या नहीं। |
| virtual **bool** [Contains](../../system.collections.generic/icollection/contains/)(const T\&) const | जांचता है कि तत्व कलेक्शन में मौजूद है या नहीं। |
| virtual void [CopyTo](../../system.collections.generic/icollection/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) | सभी कलेक्शन तत्वों को मौजूदा एरे तत्वों में कॉपी करता है। |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | कलेक्शन के अंतिम तत्व (यदि कोई हो) के तुरंत बाद की ओर इशारा करने वाला इटेरेटर लौटाता है। यह इटेरेटर रेफ़रेंस्ड ऑब्जेक्ट को बदलने के लिए उपयोग नहीं किया जा सकता क्योंकि [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) T का कॉपी-ऑब्जेक्ट लौटाता है। |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | कॉन्स्ट-कोटा की गई कलेक्शन इंस्टेंस के अंतिम तत्व के तुरंत बाद की ओर इशारा करने वाला इटेरेटर लौटाता है (यदि कोई हो)। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमान्टिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली की फ्लोटिंग पॉइंट तुलना को एमीुलेट करता है जहाँ दो NaN बराबर माने जाते हैं, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली की फ्लोटिंग पॉइंट तुलना को एमीुलेट करता है जहाँ दो NaN बराबर माने जाते हैं, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual int [get_Count](../../system.collections.generic/icollection/get_count/)() const | कलेक्शन में तत्वों की संख्या लौटाता है। |
| **bool** [get_IsFixedSize](../../system.collections.generic/ilist/get_isfixedsize/)() | जांचता है कि कलेक्शन का आकार स्थिर है या नहीं। |
| virtual **bool** [get_IsReadOnly](../../system.collections.generic/icollection/get_isreadonly/)() const | जांचता है कि कलेक्शन केवल-पढ़ने योग्य है या नहीं। |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | वह ऑब्जेक्ट लौटाता है जिसके माध्यम से कलेक्शन सिंक्रोनाइज़ किया जा रहा है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर लौटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../../system.collections.generic/ienumerator/)\<T\>\> [GetEnumerator](../../system.collections.generic/ienumerable/getenumerator/)() | एन्न्यूमरेटर लौटाता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक टाइप लौटाता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानार्थी। |
|  [ICollection](../../system.collections.generic/icollection/icollection/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |
|  [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | कॉपी कन्स्ट्रक्टर। |
|  [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | मूव कन्स्ट्रक्टर। |
| virtual T [idx_get](../../system.collections.generic/ilist/idx_get/)(int) const | निर्दिष्ट इंडेक्स पर तत्व लौटाता है। |
| virtual void [idx_set](../../system.collections.generic/ilist/idx_set/)(int, T) | निर्दिष्ट इंडेक스를 वाले तत्व को सेट करता है। |
| virtual **int32_t** [IndexOf](./indexof/)(const [System::String](../../system/string/)\&) const | [IList](../../system.collections.generic/ilist/) में प्रॉपर्टी वैल्यू द्वारा विशिष्ट आइटम का इंडेक्स निर्धारित करता है। |
| virtual int [IndexOf](../../system.collections.generic/ilist/indexof/)(const T\&) const | कंटेनर में आइटम की पहली उपस्थिति का इंडेक्स लौटाता है। |
| virtual void [Insert](./insert/)(**int32_t**, [System::String](../../system/string/)) | निर्दिष्ट इंडेक्स पर नई प्रॉपर्टी (निर्दिष्ट प्रॉपर्टी वैल्यू के साथ) को कलेक्शन में डालता है। |
| virtual void [Insert](../../system.collections.generic/ilist/insert/)(int, const T\&) | निर्दिष्ट स्थिति में तत्व डालता है, अन्य तत्वों को शिफ्ट करता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित टाइप की इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानार्थी। |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | सीक्वेंस पर एक एक्यूमुलेटर फ़ंक्शन लागू करता है। |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | तय करता है कि सीक्वेंस के सभी तत्व किसी शर्त को संतुष्ट करते हैं या नहीं। |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | तय करता है कि सीक्वेंस में कोई भी तत्व है या नहीं। |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | तय करता है कि सीक्वेंस में कोई भी तत्व शर्त को संतुष्ट करता है या नहीं। |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | संख्यात्मक मानों की सीक्वेंस का औसत गणना करता है। |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | इनपुट सीक्वेंस के प्रत्येक तत्व पर ट्रांसफ़ॉर्म फ़ंक्शन लागू करके प्राप्त मानों की सीक्वेंस का औसत गणना करता है। |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | तत्वों को निर्दिष्ट टाइप में कास्ट करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | दो सीक्वेंसेज़ को जोड़ता है। |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | तय करता है कि सीक्वेंस में निर्दिष्ट मान मौजूद है या नहीं। |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | सीक्वेंस में तत्वों की संख्या (सीधे गणना द्वारा) लौटाता है। |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | शर्त को संतुष्ट करने वाले तत्वों की संख्या लौटाता है। |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | सीक्वेंस में निर्दिष्ट इंडेक्स पर तत्व लौटाता है। |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | सीक्वेंस में निर्दिष्ट इंडेक्स पर तत्व लौटाता है। |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | सीक्वेंस का पहला तत्व लौटाता है। |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | शर्त को संतुष्ट करने वाला पहला तत्व लौटाता है। |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | सीक्वेंस का पहला तत्व लौटाता है, या यदि सीक्वेंस खाली है तो डिफ़ॉल्ट मान। |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | शर्त को संतुष्ट करने वाला पहला तत्व लौटाता है, या यदि ऐसा कोई तत्व नहीं मिलते तो डिफ़ॉल्ट मान। |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | सीक्वेंस के तत्वों को समूहित करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | सीक्वेंस के तत्वों को समूहित करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | सीक्वेंस का अंतिम तत्व लौटाता है। |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | सीक्वेंस का अंतिम तत्व लौटाता है, या यदि खाली है तो डिफ़ॉल्ट मान। |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | जनरिक सीक्वेंस के प्रत्येक तत्व पर ट्रांसफ़ॉर्म फ़ंक्शन लागू करता है और अधिकतम प्राप्त मान लौटाता है। |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | जनरिक सीक्वेंस के प्रत्येक तत्व पर ट्रांसफ़ॉर्म फ़ंक्शन लागू करता है और न्यूनतम प्राप्त मान लौटाता है। |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | निर्दिष्ट टाइप के आधार पर सीक्वेंस के तत्वों को फ़िल्टर करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | keySelector द्वारा चुनी गई कुंजी मानों के अनुसार सीक्वेंस के तत्वों को आरोही क्रम में सॉर्ट करता है। |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | keySelector द्वारा चुनी गई कुंजी मानों के अनुसार सीक्वेंस के तत्वों को अवरोही क्रम में सॉर्ट करता है। |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | सीक्वेंस में तत्वों का क्रम उलटा करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | क्रम में तत्वों को बदलता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | प्रत्येक तत्व को उसका इंडेक्स सम्मिलित करके नई फॉर्म में बदलता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | प्रत्येक तत्व को प्रोजेक्ट करके प्राप्त सीक्वेंस को एकल सीक्वेंस में मिलाता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | सीक्वेंस की शुरुआत से निरंतर तत्वों को निर्दिष्ट संख्या तक स्किप करता है और शेष लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | सीक्वेंस की शुरुआत से निरंतर निर्दिष्ट संख्या के तत्व लौटाता है। |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | सीक्वेंस से एक एरे बनाता है। |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | सीक्वेंस से एक List<T> बनाता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | निर्दिष्ट प्रेडिकेट के आधार पर सीक्वेंस को फ़िल्टर करता है। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानार्थी। कस्टम टाइप्स की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। असल में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सब-क्लासेज़ के लिए कॉपी कन्स्ट्रक्शन सक्षम करता है। |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | मूव असाइनमेंट ऑपरेटर। |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | मूव असाइनमेंट ऑपरेटर। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। असल में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सब-क्लासेज़ के लिए कॉपी कन्स्ट्रक्शन सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट को nullptr के साथ रेफ़रेंस-कम्पेयर करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) की स्पेशलाइज़ेशन। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) की स्पेशलाइज़ेशन। |
| virtual **bool** [Remove](./remove/)(const [System::String](../../system/string/)\&) | कलेक्शन से निर्दिष्ट प्रॉपर्टी को हटाता है। |
| virtual **bool** [Remove](../../system.collections.generic/icollection/remove/)(const T\&) | कलेक्शन से तत्व को हटाता है। |
| virtual void [RemoveAt](../../system.collections.generic/ilist/removeat/)(int) | निर्दिष्ट इंडेक्स पर तत्व को हटाता है। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से शेयर्ड रेफ़रेंस काउंट को घटाता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n-वें टेम्प्लेट आर्ग्यूमेंट को weak पॉइंटर सेट करता है (shared के बजाय)। कंटेनर्स में पॉइंटर्स को weak मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | वर्तमान शेयर्ड रेफ़रेंस काउंटर मूल्य लौटाता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | शेयर्ड रेफ़रेंस काउंट को इन्क्रिमेंट करता है। सीधे कॉल न करें; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | शेयर्ड रेफ़रेंस काउंट को डिक्रीमेंट करता है और उसका मूल्य लौटाता है। सीधे कॉल न करें; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कन्स्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | वर्तमान कंटेनर के const-बिगिन इटेरेटर की इम्प्लीमेंटेशन लौटाता है। |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | वर्तमान कंटेनर के बिगिन इटेरेटर की इम्प्लीमेंटेशन लौटाता है। |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | वर्तमान कंटेनर के const-एंड इटेरेटर की इम्प्लीमेंटेशन लौटाता है। |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | वर्तमान कंटेनर के एंड इटेरेटर की इम्प्लीमेंटेशन लौटाता है। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट को इन्क्रिमेंट करता है। सीधे कॉल न करें; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट को डिक्रीमेंट करता है। सीधे कॉल न करें; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | डेस्ट्रक्टर। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## संबंधित देखें

* क्लास [IList](../../system.collections.generic/ilist/)
* नेमस्पेस [Aspose::Slides::Animation](../)
* लाइब्रेरी [Aspose.Slides](../../)