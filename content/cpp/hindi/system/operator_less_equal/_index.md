---
title: operator<=()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: 
type: docs
weight: 2107
url: /hi/system/operator_less_equal/
---
## System::operator<=(std::nullptr_t, DateTime) फ़ंक्शन




```cpp
constexpr bool System::operator<=(std::nullptr_t, DateTime)
```

## System::operator<=(std::nullptr_t, const DateTimeOffset\&) फ़ंक्शन




```cpp
constexpr bool System::operator<=(std::nullptr_t, const DateTimeOffset &)
```

## System::operator<=(std::nullptr_t, const Nullable\<T\>\&) फ़ंक्शन

हमेशा false लौटाता है।

```cpp
template<typename T> bool System::operator<=(std::nullptr_t, const Nullable<T> &)
```

## System::operator<=(const T1\&, const Nullable\<T2\>\&) फ़ंक्शन

निर्धारित करता है कि निर्दिष्ट मान, निर्दिष्ट [Nullable](../nullable/) ऑब्जेक्ट द्वारा दर्शाए गए मान के बराबर या उससे कम है या नहीं, इन मानों पर [operator<=()](./) लागू करके।

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator<=(const T1 &some, const Nullable<T2> &other)
```


### टेम्पलेट पैरामीटर

| पैरामीटर | वर्णन |
| --- | --- |
| T1 | पहले तुलना मान का प्रकार |
| T2 | दूसरे तुलना मान को दर्शाने वाले [Nullable](../nullable/) ऑब्जेक्ट का आधारभूत प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| some | const T1\& | पहले तुलना मान के रूप में उपयोग किए जाने वाले मान का स्थिर संदर्भ |
| other | const [Nullable](../nullable/)\<T2\>\& | दूसरे तुलना मान के रूप में उपयोग किए जाने वाले [Nullable](../nullable/) ऑब्जेक्ट के प्रतिनिधित्व मान का स्थिर संदर्भ |

### रिटर्न वैल्यू

True यदि पहला तुलना मान दूसरा तुलना मान से कम या बराबर है, अन्यथा false

## System::operator<=(std::nullptr_t, TimeSpan) फ़ंक्शन




```cpp
constexpr bool System::operator<=(std::nullptr_t, TimeSpan)
```

## संबंधित देखें

* क्लास [DateTime](../datetime/)
* क्लास [DateTimeOffset](../datetimeoffset/)
* क्लास [Nullable](../nullable/)
* क्लास [TimeSpan](../timespan/)
* स्ट्रक्ट [IsNullable](../isnullable/)
* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)