---
title: operator<()
second_title: Aspose.Slides for C++ API संदर्भ
description: 
type: docs
weight: 2094
url: /hi/system/operator_less/
---
## System::operator<(std::nullptr_t, DateTime) फ़ंक्शन




```cpp
constexpr bool System::operator<(std::nullptr_t, DateTime)
```

## System::operator<(std::nullptr_t, const DateTimeOffset\&) फ़ंक्शन




```cpp
constexpr bool System::operator<(std::nullptr_t, const DateTimeOffset &)
```

## System::operator<(std::nullptr_t, const Nullable\<T\>\&) फ़ंक्शन


हमेशा false लौटाता है।

```cpp
template<typename T> bool System::operator<(std::nullptr_t, const Nullable<T> &)
```

## System::operator<(const T1\&, const Nullable\<T2\>\&) फ़ंक्शन


निर्दिष्ट मान को निर्दिष्ट [Nullable](../nullable/) ऑब्जेक्ट द्वारा दर्शाए गए मान से कम है या नहीं, इन मानों पर [operator<()](./) लागू करके निर्धारित करता है।

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator<(const T1 &some, const Nullable<T2> &other)
```


### टेम्पलेट पैरामीटर

| परामीटर | विवरण |
| --- | --- |
| T1 | पहले तुलना मान का प्रकार |
| T2 | [Nullable](../nullable/) ऑब्जेक्ट का अंतर्निहित प्रकार जो दूसरे तुलना मान का प्रतिनिधित्व करता है |

### तर्क

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| some | const T1\& | प्रथम तुलना मान के रूप में उपयोग होने वाले मान का स्थिर संदर्भ |
| other | const [Nullable](../nullable/)\<T2\>\& | [Nullable](../nullable/) ऑब्जेक्ट का स्थिर संदर्भ, जिसका दर्शाया गया मान दूसरे तुलना मान के रूप में उपयोग किया जाएगा |

### रिटर्न वैल्यू

True यदि पहला तुलना मान दूसरे तुलना मान से कम है, अन्यथा - false

## System::operator<(std::nullptr_t, TimeSpan) फ़ंक्शन




```cpp
constexpr bool System::operator<(std::nullptr_t, TimeSpan)
```

## देखें

* क्लास [DateTime](../datetime/)
* क्लास [DateTimeOffset](../datetimeoffset/)
* क्लास [Nullable](../nullable/)
* क्लास [TimeSpan](../timespan/)
* संरचना [IsNullable](../isnullable/)
* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)