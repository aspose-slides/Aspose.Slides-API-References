---
title: operator>=()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: 
type: docs
weight: 2133
url: /hi/system/operator_greater_equal/
---
## System::operator>=(std::nullptr_t, DateTime) फ़ंक्शन




```cpp
constexpr bool System::operator>=(std::nullptr_t, DateTime)
```

## System::operator>=(std::nullptr_t, const DateTimeOffset\&) फ़ंक्शन




```cpp
constexpr bool System::operator>=(std::nullptr_t, const DateTimeOffset &)
```

## System::operator>=(std::nullptr_t, const Nullable\<T\>\&) फ़ंक्शन


Always returns false.

```cpp
template<typename T> bool System::operator>=(std::nullptr_t, const Nullable<T> &)
```

## System::operator>=(const T1\&, const Nullable\<T2\>\&) फ़ंक्शन


निर्धारित करता है कि निर्दिष्ट मान [Nullable](../nullable/) ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मान के बराबर या बड़ा है या नहीं, इन मानों पर [operator>=()](./) लागू करके।

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator>=(const T1 &some, const Nullable<T2> &other)
```


### Template parameters

| पैरामीटर | विवरण |
| --- | --- |
| T1 | पहला तुलना मान का प्रकार |
| T2 | [Nullable](../nullable/) ऑब्जेक्ट का अंतर्निहित प्रकार जो दूसरे तुलना मान को दर्शाता है |

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| some | const T1\& | पहला तुलना मान के रूप में प्रयुक्त मान का एक स्थायी संदर्भ |
| other | const [Nullable](../nullable/)\<T2\>\& | [Nullable](../nullable/) ऑब्जेक्ट का एक स्थायी संदर्भ जिसकी प्रतिनिधित्व मान को दूसरे तुलना मान के रूप में उपयोग किया जाएगा |

### Return Value

True if the first comparand is greater or equal than the second comparand, otherwise - false

## System::operator>=(std::nullptr_t, TimeSpan) फ़ंक्शन




```cpp
constexpr bool System::operator>=(std::nullptr_t, TimeSpan)
```

## देखिए

* क्लास [DateTime](../datetime/)
* क्लास [DateTimeOffset](../datetimeoffset/)
* क्लास [Nullable](../nullable/)
* क्लास [TimeSpan](../timespan/)
* स्ट्रक्ट [IsNullable](../isnullable/)
* नामस्थान [System](../)
* लाइब्रेरी [Aspose.Slides](../../)