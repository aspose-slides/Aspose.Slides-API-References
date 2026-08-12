---
title: "System::TestPredicates::Details"
second_title: Aspose.Slides for C++ API रेफ़रेंस
description: 
type: docs
weight: 937
url: /hi/system.testpredicates.details/
---
## फ़ंक्शन

| फ़ंक्शन | विवरण |
| --- | --- |
| std::enable_if_t<\![TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\> [PrintToString](./printtostring/)(const T\&) | ऑब्जेक्ट को स्ट्रिंग में प्रिंट करता है उचित सीरियलाइज़र फ़ंक्शन का चयन करके। |
| std::enable_if_t\<[TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\> [PrintToString](./printtostring/)(const T\&) | ICollection-स्टाइल कंटेनरों को उनके तत्वों को प्रिंट करके स्ट्रिंग में प्रिंट करता है (32 से अधिक नहीं)। |
| std::string [PrintToString](./printtostring/)(std::nullptr_t) | nullptr को स्ट्रिंग में प्रिंट करता है। |
| std::string [PrintToString](./printtostring/)(const [Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<**bool**\>\&) | [IEnumerable<bool>](../system.collections.generic/ienumerable/) कलेक्शनों को उनके तत्वों को प्रिंट करके स्ट्रिंग में प्रिंट करता है (32 से अधिक नहीं)। |
| std::enable_if\<System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const [SharedPtr](../system/sharedptr/)\<T\>\&, long long) | [System::Object](../system/object/) उप वर्ग को ToString() मेथड का उपयोग करके स्ट्रिंग में प्रिंट करता है। |
| std::enable_if\<System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const [WeakPtr](../system/weakptr/)\<T\>\&, long long) | [System::Object](../system/object/) उप वर्ग को ToString() मेथड का उपयोग करके स्ट्रिंग में प्रिंट करता है। |
| std::enable_if<\![TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | ऑब्जेक्ट को ToString() मेथड का उपयोग करके स्ट्रिंग में प्रिंट करता है। |
| std::enable_if\<[TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&\![TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | ऑब्जेक्ट को PrintTo मेथड का उपयोग करके स्ट्रिंग में प्रिंट करता है। |
| std::enable_if\<[TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&[TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | ऑब्जेक्ट को PrintTo मेथड का उपयोग करके स्ट्रिंग में प्रिंट करता है। |
| std::string [PrintToStringImpl](./printtostringimpl/)(const std::pair\<T1, T2\>\&, long long) | पेयर को स्ट्रिंग में प्रिंट करता है। |
| std::string [PrintToStringImpl](./printtostringimpl/)(const [Collections::Generic::KeyValuePair](../system.collections.generic/keyvaluepair/)\<T1, T2\>\&, long long) | पेयर को स्ट्रिंग में प्रिंट करता है। |
| std::enable_if\<[TypeTraits::IsCppContainer](../system.testpredicates.typetraits/iscppcontainer/)\<T\>::value\&&\!std::is_base_of\<[Object](../system/object/), T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | STL-स्टाइल कंटेनरों को उनके तत्वों को प्रिंट करके स्ट्रिंग में प्रिंट करता है (32 से अधिक नहीं)। |
| std::string [PrintToStringImpl](./printtostringimpl/)(const T\&, int) | gtest-प्रदान किए गए फ़ंक्शनों का उपयोग करके अन्य प्रकारों को स्ट्रिंग में प्रिंट करता है। |
| testing::AssertionResult [EqFailure](./eqfailure/)(const char *, const char *, T1\&, T2\&) | आउटपुट के लिए == अभिकथन विफलता को फ़ॉर्मैट करता है। |
| testing::AssertionResult [NotEqFailure](./noteqfailure/)(const char *, const char *, T1\&, T2\&) | आउटपुट के लिए != अभिकथन विफलता को फ़ॉर्मैट करता है। |
| testing::AssertionResult [SameFailure](./samefailure/)(const char *, const char *, T1\&, T2\&) | आउटपुट के लिए 'same' अभिकथन विफलता को फ़ॉर्मैट करता है। |
| testing::AssertionResult [NotSameFailure](./notsamefailure/)(const char *, const char *, T1\&, T2\&) | आउटपुट के लिए 'not same' अभिकथन विफलता को फ़ॉर्मैट करता है। |