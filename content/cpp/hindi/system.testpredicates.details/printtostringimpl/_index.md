---
title: PrintToStringImpl()
second_title: Aspose.Slides for C++ API संदर्भ
description: "System::Object उपवर्ग को ToString() मेथड का उपयोग करके स्ट्रिंग में प्रिंट करता है।"
type: docs
weight: 14
url: /hi/system.testpredicates.details/printtostringimpl/
---
## System::TestPredicates::Details::PrintToStringImpl(const SharedPtr\<T\>\&, long long) function

ToString() मेथड का उपयोग करके [System::Object](../../system/object/) उपवर्ग को स्ट्रिंग में प्रिंट करता है।

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const SharedPtr<T> &value, long long s)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T | अंतिम क्लास प्रकार। |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [SharedPtr](../../system/sharedptr/)\<T\>\& | प्रिंट करने के लिए ऑब्जेक्ट का पॉइंटर। |
| s | long long | एक सर्विस पैरामीटर जो इस पैरामीटर के प्रकार के आधार पर फ़ंक्शन ओवरलोड को चुनने के लिए काम करता है; पैरामीटर का मान अनदेखा किया जाता है |

### Return Value

[String](../../system/string/) प्रतिनिधित्व पास किए गए ऑब्जेक्ट का या "nullptr", यदि **value** null है।

## System::TestPredicates::Details::PrintToStringImpl(const WeakPtr\<T\>\&, long long) function

ToString() मेथड का उपयोग करके [System::Object](../../system/object/) उपवर्ग को स्ट्रिंग में प्रिंट करता है।

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const WeakPtr<T> &value, long long s)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T | अंतिम क्लास प्रकार। |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [WeakPtr](../../system/weakptr/)\<T\>\& | प्रिंट करने के लिए ऑब्जेक्ट का पॉइंटर। |
| s | long long | एक सर्विस पैरामीटर जो इस पैरामीटर के प्रकार के आधार पर फ़ंक्शन ओवरलोड को चुनने के लिए काम करता है; पैरामीटर का मान अनदेखा किया जाता है |

### Return Value

[String](../../system/string/) प्रतिनिधित्व पास किए गए ऑब्जेक्ट का या "nullptr", यदि **value** null है।

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) function

ToString() मेथड का उपयोग करके ऑब्जेक्ट को स्ट्रिंग में प्रिंट करता है।

```cpp
template<typename T> std::enable_if<!TypeTraits::has_print_to_method<T>::value &&System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) प्रकार। |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) को प्रिंट करने के लिए। |
| s | long long | एक सर्विस पैरामीटर जो इस पैरामीटर के प्रकार के आधार पर फ़ंक्शन ओवरलोड को चुनने के लिए काम करता है; पैरामीटर का मान अनदेखा किया जाता है |

### Return Value

[String](../../system/string/) पास किए गए ऑब्जेक्ट का प्रतिनिधित्व।

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) function

PrintTo मेथड का उपयोग करके ऑब्जेक्ट को स्ट्रिंग में प्रिंट करता है।

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&!TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) प्रकार। |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) को प्रिंट करने के लिए। |
| s | long long | एक सर्विस पैरामीटर जो इस पैरामीटर के प्रकार के आधार पर फ़ंक्शन ओवरलोड को चुनने के लिए काम करता है; पैरामीटर का मान अनदेखा किया जाता है |

### Return Value

[String](../../system/string/) पास किए गए ऑब्जेक्ट का प्रतिनिधित्व।

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) function

PrintTo मेथड का उपयोग करके ऑब्जेक्ट को स्ट्रिंग में प्रिंट करता है।

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) प्रकार। |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) को प्रिंट करने के लिए। |
| s | long long | एक सर्विस पैरामीटर जो इस पैरामीटर के प्रकार के आधार पर फ़ंक्शन ओवरलोड को चुनने के लिए काम करता है; पैरामीटर का मान अनदेखा किया जाता है |

### Return Value

[String](../../system/string/) पास किए गए ऑब्जेक्ट का प्रतिनिधित्व।

## System::TestPredicates::Details::PrintToStringImpl(const std::pair\<T1, T2\>\&, long long) function

पेयर को स्ट्रिंग में प्रिंट करता है।

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const std::pair<T1, T2> &value, long long s)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | पहला पेयर प्रकार तर्क। |
| T2 | दूसरा पेयर प्रकार तर्क। |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const std::pair\<T1, T2\>\& | [Object](../../system/object/) को प्रिंट करने के लिए। |
| s | long long | एक सर्विस पैरामीटर जो इस पैरामीटर के प्रकार के आधार पर फ़ंक्शन ओवरलोड को चुनने के लिए काम करता है; पैरामीटर का मान अनदेखा किया जाता है |

### Return Value

पहले और दूसरे पेयर घटकों के संयुक्त स्ट्रिंग प्रतिनिधित्व।

## System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair\<T1, T2\>\&, long long) function

पेयर को स्ट्रिंग में प्रिंट करता है।

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair<T1, T2> &value, long long s)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | पहला पेयर प्रकार तर्क। |
| T2 | दूसरा पेयर प्रकार तर्क। |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<T1, T2\>\& | [Object](../../system/object/) को प्रिंट करने के लिए। |
| s | long long | एक सर्विस पैरामीटर जो इस पैरामीटर के प्रकार के आधार पर फ़ंक्शन ओवरलोड को चुनने के लिए काम करता है; पैरामीटर का मान अनदेखा किया जाता है |

### Return Value

पहले और दूसरे पेयर घटकों के संयुक्त स्ट्रिंग प्रतिनिधित्व।

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) function

STL-शैली के कंटेनरों को स्ट्रिंग में प्रिंट करता है उनके तत्वों को प्रिंट करके (अधिकतम 32)।

```cpp
template<typename T> std::enable_if<TypeTraits::IsCppContainer<T>::value &&!std::is_base_of<Object, T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &container, long long s)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) प्रकार। |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| container | const T\& | [Object](../../system/object/) को प्रिंट करने के लिए। |
| s | long long | एक सर्विस पैरामीटर जो इस पैरामीटर के प्रकार के आधार पर फ़ंक्शन ओवरलोड को चुनने के लिए काम करता है; पैरामीटर का मान अनदेखा किया जाता है |

### Return Value

निहित तत्वों के संयुक्त स्ट्रिंग प्रतिनिधित्व।

## System::TestPredicates::Details::PrintToStringImpl(const T\&, int) function

gtest-प्रदान किए गए फ़ंक्शनों का उपयोग करके अन्य प्रकारों को स्ट्रिंग में प्रिंट करता है।

```cpp
template<typename T> std::string System::TestPredicates::Details::PrintToStringImpl(const T &value, int s)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) प्रकार। |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) को प्रिंट करने के लिए। |
| s | int | एक सर्विस पैरामीटर जो इस पैरामीटर के प्रकार के आधार पर फ़ंक्शन ओवरलोड को चुनने के लिए काम करता है; पैरामीटर का मान अनदेखा किया जाता है |

### Return Value

[String](../../system/string/) पास किए गए ऑब्जेक्ट के प्रतिनिधित्व।

## See Also

* टाइपडिफ [SharedPtr](../../system/sharedptr/)
* क्लास [WeakPtr](../../system/weakptr/)
* क्लास [KeyValuePair](../../system.collections.generic/keyvaluepair/)
* क्लास [Object](../../system/object/)
* स्ट्रक्ट [has_print_to_method](../../system.testpredicates.typetraits/has_print_to_method/)
* स्ट्रक्ट [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* स्ट्रक्ट [IsCppContainer](../../system.testpredicates.typetraits/iscppcontainer/)
* नेमस्पेस [System::TestPredicates::Details](../)
* लाइब्रेरी [Aspose.Slides](../../)