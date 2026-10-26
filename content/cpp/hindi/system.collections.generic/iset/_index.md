---
title: ISet
second_title: Aspose.Slides for C++ API संदर्भ
description: "एक संग्रह का इंटरफ़ेस जो अद्वितीय तत्वों के सेट को शामिल करता है। इस क्लास के ऑब्जेक्ट को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन दोष उत्पन्न हो सकते हैं। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शन को तर्क के रूप में पास करने के लिए करें।"
type: docs
weight: 352
url: /hi/system.collections.generic/iset/
---
## ISet क्लास

इंटरफ़ेस जो एक संग्रह है जिसमें अद्वितीय तत्वों का सेट होता है। इस क्लास के ऑब्जेक्ट को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस कभी भी स्टैक पर या operator new का उपयोग करके न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन त्रुटियां हो सकती हैं। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर को फ़ंक्शन के तर्क के रूप में पास करें।

```cpp
template<typename T>class ISet : public System::Collections::Generic::ICollection<T>
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | तत्व प्रकार। |

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| virtual void [Add](../icollection/add/)(const T\&) | कलेक्शन में तत्व जोड़ता है। |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | कलेक्शन के प्रथम तत्व (यदि कोई हो) की ओर संकेत करने वाला इटरैटर प्राप्त करता है। इस इटरैटर का उपयोग संदर्भित ऑब्जेक्ट को बदलने के लिए नहीं किया जा सकता क्योंकि [GetEnumerator()](../ienumerable/getenumerator/) T की कॉपी-ऑब्जेक्ट लौटाता है। |
| [const_iterator](../ienumerable/const_iterator/) [begin](../ienumerable/begin/)() const | कंस्ट-योग्य कलेक्शन इंस्टेंस के प्रथम तत्व (यदि कोई हो) की ओर संकेत करने वाला इटरैटर प्राप्त करता है। |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../ienumerable/cbegin/)() const | कलेक्शन के प्रथम कंस्ट-योग्य तत्व (यदि कोई हो) की ओर संकेत करने वाला इटरैटर प्राप्त करता है। |
| [const_iterator](../ienumerable/const_iterator/) [cend](../ienumerable/cend/)() const | कलेक्शन के अंतिम कंस्ट-योग्य तत्व (यदि कोई हो) के ठीक बाद की ओर संकेत करने वाला इटरैटर प्राप्त करता है। |
| virtual void [Clear](../icollection/clear/)() | कलेक्शन से सभी तत्व हटाता है। |
| virtual **bool** [Contains](../icollection/contains/)(const T\&) const | जाँचता है कि तत्व कलेक्शन में मौजूद है या नहीं। |
| virtual void [CopyTo](../icollection/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) | सभी कलेक्शन तत्वों को मौजूदा एरे तत्वों में कॉपी करता है। |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | कलेक्शन के अंतिम तत्व (यदि कोई हो) के ठीक बाद की ओर संकेत करने वाला इटरैटर प्राप्त करता है। इस इटरैटर का उपयोग संदर्भित ऑब्जेक्ट को बदलने के लिए नहीं किया जा सकता क्योंकि [GetEnumerator()](../ienumerable/getenumerator/) T की कॉपी-ऑब्जेक्ट लौटाता है। |
| [const_iterator](../ienumerable/const_iterator/) [end](../ienumerable/end/)() const | कंस्ट-योग्य कलेक्शन इंस्टेंस के अंतिम तत्व (यदि कोई हो) के ठीक बाद की ओर संकेत करने वाला इटरैटर प्राप्त करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सिद्धांतों का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग-पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN मानों को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के साथ भी नहीं। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग-पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN मानों को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के साथ भी नहीं। |
| virtual void [ExceptWith](./exceptwith/)([IEnumerablePtr](./ienumerableptr/)) | तत्वों के समूह को हटाता है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual int [get_Count](../icollection/get_count/)() const | कलेक्शन में तत्वों की संख्या प्राप्त करता है। |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | जाँचता है कि कलेक्शन केवल-पढ़ने योग्य है या नहीं। |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | वह ऑब्जेक्ट प्राप्त करता है जिसके माध्यम से कलेक्शन समक्रमित किया जा रहा है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा संरचना को प्राप्त करता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<T\>\> [GetEnumerator](../ienumerable/getenumerator/)() | एन्यूमेरेटर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
|  [ICollection](../icollection/icollection/)() | डिफ़ॉल्ट कंस्ट्रक्टर। |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | कॉपी कंस्ट्रक्टर। |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | मूव कंस्ट्रक्टर। |
| virtual void [IntersectWith](./intersectwith/)([IEnumerablePtr](./ienumerableptr/)) | विभिन्न कंटेनर में न मौजूद तत्वों को हटाता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| virtual **bool** [IsProperSubsetOf](./ispropersubsetof/)([IEnumerablePtr](./ienumerableptr/)) | जाँचता है कि वर्तमान सेट अन्य कंटेनर का सख़्त उपसमुच्चय है या नहीं। |
| virtual **bool** [IsProperSupersetOf](./ispropersupersetof/)([IEnumerablePtr](./ienumerableptr/)) | जाँचता है कि वर्तमान सेट अन्य कंटेनर का सख़्त सुपरसेट है या नहीं। |
| virtual **bool** [IsSubsetOf](./issubsetof/)([IEnumerablePtr](./ienumerableptr/)) | जाँचता है कि वर्तमान सेट अन्य कंटेनर का उपसमुच्चय है या नहीं। |
| virtual **bool** [IsSupersetOf](./issupersetof/)([IEnumerablePtr](./ienumerableptr/)) | जाँचता है कि वर्तमान सेट अन्य कंटेनर का सुपरसेट है या नहीं। |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | सीक्वेंस पर एक एक्यूम्युलेटर फ़ंक्शन लागू करता है। |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | निर्धारित करता है कि सीक्वेंस के सभी तत्व किसी शर्त को पूरा करते हैं या नहीं। |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | निर्धारित करता है कि सीक्वेंस में कोई भी तत्व मौजूद है या नहीं। |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | निर्धारित करता है कि सीक्वेंस में कोई भी तत्व मौजूद है या शर्त को पूरा करता है या नहीं। |
| T [LINQ_Average](../ienumerable/linq_average/)() | संख्यात्मक मानों की एक सीक्वेंस का औसत गणना करता है। |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | इनपुट सीक्वेंस के प्रत्येक तत्व पर ट्रांसफ़ॉर्म फ़ंक्शन लागू करके प्राप्त मानों की सीक्वेंस का औसत गणना करता है। |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | तत्वों को निर्दिष्ट प्रकार में कास्ट करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | दो सीक्वेंसेज़ को जोड़ता है। |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | निर्धारित करता है कि सीक्वेंस में निर्दिष्ट मान मौजूद है या नहीं। |
| int [LINQ_Count](../ienumerable/linq_count/)() | सीक्वेंस में तत्वों की संख्या लौटाता है (प्रत्यक्ष गणना द्वारा)। |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | सीक्वेंस में उन तत्वों की संख्या लौटाता है जो निर्दिष्ट शर्त को पूरा करते हैं। |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | सीक्वेंस में निर्दिष्ट इंडेक्स पर तत्व लौटाता है। |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | सीक्वेंस में निर्दिष्ट इंडेक्स पर तत्व लौटाता है। |
| T [LINQ_First](../ienumerable/linq_first/)() | सीक्वेंस का पहला तत्व लौटाता है। |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | सीक्वेंस का पहला तत्व लौटाता है जो निर्दिष्ट शर्त को पूरा करता है। |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | सीक्वेंस का पहला तत्व लौटाता है, या यदि सीक्वेंस खाली है तो डिफ़ॉल्ट मान लौटाता है। |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | सीक्वेंस का पहला तत्व लौटाता है जो शर्त को पूरा करता है, या यदि ऐसा कोई तत्व न मिले तो डिफ़ॉल्ट मान लौटाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | सीक्वेंस के तत्वों को समूहित करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | सीक्वेंस के तत्वों को समूहित करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | सीक्वेंस का अंतिम तत्व लौटाता है। |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | सीक्वेंस का अंतिम तत्व लौटाता है, या यदि सीक्वेंस खाली है तो डिफ़ॉल्ट मान लौटाता है। |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | सामान्य सीक्वेंस के प्रत्येक तत्व पर ट्रांसफ़ॉर्म फ़ंक्शन लागू करता है और अधिकतम प्राप्त मान लौटाता है। |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | सामान्य सीक्वेंस के प्रत्येक तत्व पर ट्रांसफ़ॉर्म फ़ंक्शन लागू करता है और न्यूनतम प्राप्त मान लौटाता है। |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | निर्दिष्ट प्रकार के आधार पर सीक्वेंस के तत्वों को फिल्टर करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | सीक्वेंस के तत्वों को keySelector द्वारा चुनी गई कुंजी मूल्यों के आधार पर आरोही क्रम में क्रमबद्ध करता है। |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | सीक्वेंस के तत्वों को keySelector द्वारा चुनी गई कुंजी मूल्यों के आधार पर अवरोही क्रम में क्रमबद्ध करता है। |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | सीक्वेंस में तत्वों का क्रम उलट देता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | सीक्वेंस के तत्वों को बदलता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | प्रत्येक तत्व के इंडेक्स को सम्मिलित करके सीक्वेंस के प्रत्येक तत्व को नई रूप में बदलता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | सीक्वेंस के प्रत्येक तत्व को प्रोजेक्ट करता है और प्राप्त सीक्वेंसों को एक साथ जोड़ता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | सीक्वेंस की शुरुआत से निर्दिष्ट संख्या में क्रमिक तत्वों को छोड़ता है और शेष लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | सीक्वेंस की शुरुआत से निर्दिष्ट संख्या में क्रमिक तत्वों को लौटाता है। |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | सीक्वेंस से एक एरे बनाता है। |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | सीक्वेंस से एक List<T> बनाता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | निर्दिष्ट प्रेडिकेट के आधार पर सीक्वेंस को फ़िल्टर करता है। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट के लॉक को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम प्रकारों की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | मूव असाइनमेंट ऑपरेटर। |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | मूव असाइनमेंट ऑपरेटर। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| virtual **bool** [Overlaps](./overlaps/)([IEnumerablePtr](./ienumerableptr/)) | जाँचता है कि सेट अन्य कंटेनर के साथ ओवरलैप करता है या नहीं। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू प्रकार के ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के मामले के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के मामले के लिए विशेषीकरण। |
| virtual **bool** [Remove](../icollection/remove/)(const T\&) | कलेक्शन से तत्व हटाता है। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट को घटाता है। |
| virtual **bool** [SetEquals](./setequals/)([IEnumerablePtr](./ienumerableptr/)) | जाँचता है कि सेट और कंटेनर में समान तत्व हैं या नहीं। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्प्लेट आर्ग्यूमेंट को एक कमजोर पॉइंटर सेट करता है (साझा के बजाय)। कंटेनर में पॉइंटर को कमजोर मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual void [SymmetricExceptWith](./symmetricexceptwith/)([IEnumerablePtr](./ienumerableptr/)) | दो कंटेनरों का सममित अपवर्जन गणना करता है। दोनों कंटेनरों में मौजूद सभी तत्वों को हटाता है, लेकिन साथ ही **other** में मौजूद लेकिन वर्तमान सेट में न मौजूद सभी तत्वों को जोड़ता है। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) संरचना को लागू करता है। |
| virtual void [UnionWith](./unionwith/)([IEnumerablePtr](./ienumerableptr/)) | निर्दिष्ट कलेक्शन से उन तत्वों को जोड़ता है जो अभी तक वर्तमान सेट में नहीं हैं। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट के अनलॉक को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../ienumerable/virtualizebeginconstiterator/)() const | वर्तमान कंटेनर के begin const इटरैटर का कार्यान्वयन प्राप्त करता है। |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../ienumerable/virtualizebeginiterator/)() | वर्तमान कंटेनर के begin इटरैटर का कार्यान्वयन प्राप्त करता है। |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../ienumerable/virtualizeendconstiterator/)() const | वर्तमान कंटेनर के end const इटरैटर का कार्यान्वयन प्राप्त करता है। |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../ienumerable/virtualizeenditerator/)() | वर्तमान कंटेनर के end इटरैटर का कार्यान्वयन प्राप्त करता है। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~ICollection](../icollection/~icollection/)() | डिस्ट्रक्टर। |
| virtual  [~ISet](./~iset/)() | डिस्ट्रक्टर। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## टाइपडिफ़्स

| टाइपडेफ | विवरण |
| --- | --- |
| [IEnumerablePtr](./ienumerableptr/) | वर्तमान सेट की सामग्री की तुलना करने के लिए उपयोग किया जाने वाला एनेमरेबल प्रकार। |

## देखें

* क्लास [ICollection](../icollection/)
* नेमस्पेस [System::Collections::Generic](../)
* लाइब्रेरी [Aspose.Slides](../../)