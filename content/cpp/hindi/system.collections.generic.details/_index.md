---
title: "System::Collections::Generic::Details"
second_title: Aspose.Slides for C++ API संदर्भ
description: 
type: docs
weight: 352
url: /hi/system.collections.generic.details/
---
## क्लासेस

| क्लास | विवरण |
| --- | --- |
| [EnumerableAdapter](./enumerableadapter/) | IEnumerable.Cast() और IEnumerable.OfType() एक्सटेंशन मेथड्स द्वारा प्रयुक्त Enumerable। |
| [EnumerableSelectAdapter](./enumerableselectadapter/) | IEnumerable.Select() एक्सटेंशन मेथड द्वारा प्रयुक्त Enumerable। |
| [EnumerableSelectIndexAdapter](./enumerableselectindexadapter/) |  |
| [EnumerableSelectManyAdapter](./enumerableselectmanyadapter/) |  |
| [EnumeratorCastAdapter](./enumeratorcastadapter/) | IEnumerable.Cast() एक्सटेंशन मेथड द्वारा प्रयुक्त Enumerator। |
| [EnumeratorOfTypeAdapter](./enumeratoroftypeadapter/) | IEnumerable.OfType() एक्सटेंशन मेथड द्वारा प्रयुक्त Enumerator। |
| [EnumeratorSelectAdapter](./enumeratorselectadapter/) | IEnumerable.Select() एक्सटेंशन मेथड द्वारा प्रयुक्त Enumerator। |
| [EnumeratorSelectIndexAdapter](./enumeratorselectindexadapter/) |  |
| [EnumeratorSelectManyAdapter](./enumeratorselectmanyadapter/) |  |
| [GroupEnumerable](./groupenumerable/) |  |
| [Grouping](./grouping/) |  |
## संरचनाएँ

| संरचना | विवरण |
| --- | --- |
| [ComparerType](./comparertype/) | 'less' सेमान्टिक्स का उपयोग करके तत्वों की तुलना करता है। |
| [ComparerType< SharedPtr< T > >](./comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/) | 'less' सेमान्टिक्स का उपयोग करके तत्वों की तुलना करता है। |
| [has_method_compareto](./has_method_compareto/) | जांचता है कि निर्दिष्ट प्रकार में CompareTo मेथड मौजूद है या नहीं। यदि मौजूद है तो std::true_type को इनहेरिट करता है, अन्यथा std::false_type को इनहेरिट करता है। std::enable_if में उपयोग किया जा सकता है। |
| [has_method_compareto_shared_ptr](./has_method_compareto_shared_ptr/) | जांचता है कि निर्दिष्ट प्रकार में CompareTo(SharedPtr<T>) मेथड मौजूद है या नहीं। यदि मौजूद है तो std::true_type को इनहेरिट करता है, अन्यथा std::false_type को इनहेरिट करता है। std::enable_if में उपयोग किया जा सकता है। |
| [IsEqualExist](./isequalexist/) | जांचता है कि प्रकार operator == प्रदान करता है या नहीं। |
## फ़ंक्शन

| फ़ंक्शन | विवरण |
| --- | --- |
| **bool** [IsOutOfBounds](./isoutofbounds/)(int, const Container\&) | इंडेक्स कंटेनर की सीमाओं के बाहर है या नहीं जाँचता है, कंटेनर आकार को छोड़कर। |
| **bool** [IsOutOfBounds](./isoutofbounds/)(std::int64_t, const Container\&) | इंडेक्स कंटेनर की सीमाओं के बाहर है या नहीं जाँचता है, कंटेनर आकार को छोड़कर। |
| **bool** [IsOutOfSize](./isoutofsize/)(int, const Container\&) | इंडेक्स कंटेनर की सीमाओं के बाहर है या नहीं जाँचता है, कंटेनर आकार सहित। |
| **bool** [IsOutOfSize](./isoutofsize/)(std::int64_t, const Container\&) | इंडेक्स कंटेनर की सीमाओं के बाहर है या नहीं जाँचता है, कंटेनर आकार सहित। |
| std::true_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(T *, T *) | यह मददगार फ़ंक्शन निर्धारित करता है कि विशिष्ट क्लास में operator == है या नहीं। |
| std::false_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(void *, void *) | यह मददगार फ़ंक्शन निर्धारित करता है कि विशिष्ट क्लास में operator == है या नहीं। |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | संग्रह के पहले तत्व को प्राप्त करने का प्रयत्न करता है। |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, const [Func](../system/func/)\<T, **bool**\>\&, **bool**\&) | संग्रह के पहले तत्व को प्राप्त करने का प्रयत्न करता है, जो प्रेडिकेट फ़ंक्शन को संतुष्ट करता है। |
| T [TryGetLast](./trygetlast/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | संग्रह के अंतिम तत्व को प्राप्त करने का प्रयत्न करता है। |
## टाइपडिफ़

| टाइपडिफ़ | विवरण |
| --- | --- |
| [has_operator_equals](./has_operator_equals/) | operator == की मौजूदगी जाँचने के लिए डमी टाइपडिफ़। |