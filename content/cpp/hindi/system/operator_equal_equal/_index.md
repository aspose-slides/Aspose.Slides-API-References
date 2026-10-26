---
title: operator==()
second_title: Aspose.Slides for C++ API संदर्भ
description: 
type: docs
weight: 2042
url: /hi/system/operator_equal_equal/
---
## System::operator==(ArraySegment\<T\>, ArraySegment\<T\>) फ़ंक्शन




```cpp
template<typename T> bool System::operator==(ArraySegment<T> a, ArraySegment<T> b)
```

## System::operator==(std::nullptr_t, DateTime) फ़ंक्शन




```cpp
constexpr bool System::operator==(std::nullptr_t, DateTime)
```

## System::operator==(std::nullptr_t, const DateTimeOffset\&) फ़ंक्शन




```cpp
constexpr bool System::operator==(std::nullptr_t, const DateTimeOffset &)
```

## System::operator==(std::nullptr_t, const Nullable\<T\>\&) फ़ंक्शन


निर्धारित करता है कि निर्दिष्ट [Nullable](../nullable/) ऑब्जेक्ट का मान null के बराबर है या नहीं।

```cpp
template<typename T> bool System::operator==(std::nullptr_t, const Nullable<T> &other)
```


### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | std::nullptr_t | परीक्षण के लिए एक [Nullable](../nullable/) ऑब्जेक्ट का स्थायी संदर्भ |

### वापसी मान

यदि निर्दिष्ट ऑब्जेक्ट null मान का प्रतिनिधित्व करता है तो true, अन्यथा false

## System::operator==(const T1\&, const Nullable\<T2\>\&) फ़ंक्शन


निर्धारित करता है कि निर्दिष्ट मान निर्दिष्ट [Nullable](../nullable/) ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मान के बराबर है या नहीं, इन मानों पर [operator==()](./) लागू करके।

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator==(const T1 &some, const Nullable<T2> &other)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | पहले तुलना मान का प्रकार |
| T2 | [Nullable](../nullable/) ऑब्जेक्ट का मूल प्रकार जो दूसरे तुलना मान का प्रतिनिधित्व करता है |

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| some | const T1\& | पहला तुलना मान के रूप में उपयोग किए जाने वाले मान का स्थायी संदर्भ |
| other | const [Nullable](../nullable/)\<T2\>\& | दूसरे तुलना मान के रूप में उपयोग किए जाने वाले [Nullable](../nullable/) ऑब्जेक्ट का स्थायी संदर्भ |

### वापसी मान

यदि तुलना मान समान हैं तो true, अन्यथा false

## System::operator==(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) फ़ंक्शन


दो स्मार्ट पॉइंटरों की समानता-तुलना करता है।

```cpp
template<class X,class Y> bool System::operator==(const SmartPtr<X> &x, const SmartPtr<Y> &y)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| X | पहले पॉइंटर का पॉइंटी टाइप |
| Y | दूसरे पॉइंटर का पॉइंटी टाइप |

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | तुलना करने के लिए पहला पॉइंटर |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | तुलना करने के लिए दूसरा पॉइंटर |

### वापसी मान

यदि पॉइंटर मिलते हैं तो true, अन्यथा false।

## System::operator==(std::nullptr_t, SmartPtr\<X\> const\&) फ़ंक्शन


जाँचता है कि स्मार्ट पॉइंटर null है या नहीं।

```cpp
template<class X> bool System::operator==(std::nullptr_t, SmartPtr<X> const &x)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| X | पॉइंटर का पॉइंटी टाइप |

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | std::nullptr_t | जांचने के लिए पॉइंटर |

### वापसी मान

यदि पॉइंटर null है तो true, अन्यथा false।

## System::operator==(const SmartPtr\<X\>\&, const Y *) फ़ंक्शन


स्मार्ट पॉइंटर की साधारण (C) पॉइंटर के विरुद्ध समानता तुलना।

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const SmartPtr<X> &x, const Y *y)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| X | स्मार्ट पॉइंटर का प्रकार |
| Y | साधारण पॉइंटर का प्रकार |

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | तुलना करने के लिए स्मार्ट पॉइंटर (बायाँ) |
| y | const Y * | तुलना करने के लिए पॉइंटर (दायाँ) |

### वापसी मान

यदि पॉइंटर मिलते हैं तो true, अन्यथा false।

## System::operator==(const X *, const SmartPtr\<Y\>\&) फ़ंक्शन


स्मार्ट पॉइंटर की साधारण (C) पॉइंटर के विरुद्ध समानता तुलना।

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const X *x, const SmartPtr<Y> &y)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| X | साधारण पॉइंटर का प्रकार |
| Y | स्मार्ट पॉइंटर का प्रकार |

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | const X * | तुलना करने के लिए पॉइंटर (दायाँ) |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | तुलना करने के लिए स्मार्ट पॉइंटर (बायाँ) |

### वापसी मान

यदि पॉइंटर मिलते हैं तो true, अन्यथा false।

## System::operator==(T const\&, std::nullptr_t) फ़ंक्शन


जाँचता है कि मान प्रकार ऑब्जेक्ट (अनूदित C# संरचना आदि) null है या नहीं।

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(T const &x, std::nullptr_t)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | मान प्रकार |

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | T const\& | जांचने के लिए [Object](../object/) |

### वापसी मान

यदि ऑब्जेक्ट null है तो true, अन्यथा false।

## System::operator==(std::nullptr_t, T const\&) फ़ंक्शन


जाँचता है कि मान प्रकार ऑब्जेक्ट (अनूदित C# संरचना आदि) null है या नहीं।

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(std::nullptr_t, T const &x)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | मान प्रकार |

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | std::nullptr_t | जांचने के लिए [Object](../object/) |

### वापसी मान

यदि ऑब्जेक्ट null है तो true, अन्यथा false।

## System::operator==(Chars\&, const String\&) फ़ंक्शन


[String](../string/) तुलना।

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator==(Chars &left, const String &right)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Chars | [String](../string/) लिटरल प्रकार |

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| left | Chars\& | तुलना करने के लिए [String](../string/) लिटरल |
| right | const [String](../string/)\& | तुलना करने के लिए [String](../string/) |

### वापसी मान

यदि स्ट्रिंग समान हैं तो true, अन्यथा false।

## System::operator==(T\&, const String\&) फ़ंक्शन


[String](../string/) तुलना।

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator==(T &left, const String &right)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | [String](../string/) पॉइंटर प्रकार |

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| left | T\& | तुलना करने के लिए [String](../string/) पॉइंटर |
| right | const [String](../string/)\& | तुलना करने के लिए [String](../string/) |

### वापसी मान

यदि स्ट्रिंग समान हैं तो true, अन्यथा false।

## System::operator==(const SharedPtr\<Object\>\&, const String\&) फ़ंक्शन


[Object](../object/) और स्ट्रिंग तुलना।

```cpp
bool System::operator==(const SharedPtr<Object> &left, const String &right)
```


### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| left | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | स्ट्रिंग में परिवर्तित करने और तुलना करने के लिए [Object](../object/) |
| right | const [String](../string/)\& | तुलना करने के लिए [String](../string/) |

### वापसी मान

यदि ऑब्जेक्ट की स्ट्रिंग प्रतिनिधित्व स्ट्रिंग के बराबर है तो true, अन्यथा false।

## System::operator==(std::nullptr_t, const String\&) फ़ंक्शन


जाँचता है कि स्ट्रिंग null है या नहीं।

```cpp
bool System::operator==(std::nullptr_t, const String &str)
```


### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| str | std::nullptr_t | जांचने के लिए [String](../string/) |

### वापसी मान

यदि स्ट्रिंग null है तो true, अन्यथा false।

## System::operator==(std::nullptr_t, TimeSpan) फ़ंक्शन




```cpp
constexpr bool System::operator==(std::nullptr_t, TimeSpan)
```

## System::operator==(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) फ़ंक्शन


वर्तमान और निर्दिष्ट ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए URI समान हैं या नहीं, निर्धारित करता है।

```cpp
bool System::operator==(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```


### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| uri1 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | तुलना करने के लिए पहला [Uri](../uri/) ऑब्जेक्ट |
| uri2 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | तुलना करने के लिए दूसरा [Uri](../uri/) ऑब्जेक्ट |

### वापसी मान

यदि URI समान हैं तो true, अन्यथा false

## देखें

* Typedef [SharedPtr](../sharedptr/)
* Class [ArraySegment](../arraysegment/)
* Class [DateTime](../datetime/)
* Class [DateTimeOffset](../datetimeoffset/)
* Class [Nullable](../nullable/)
* Class [SmartPtr](../smartptr/)
* Class [Object](../object/)
* Class [String](../string/)
* Class [TimeSpan](../timespan/)
* Class [Uri](../uri/)
* Struct [IsNullable](../isnullable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)