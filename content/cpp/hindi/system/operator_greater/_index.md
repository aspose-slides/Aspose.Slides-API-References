---
title: operator>()
second_title: Aspose.Slides for C++ API संदर्भ
description: 
type: docs
weight: 2120
url: /hi/system/operator_greater/
---
## System::operator>(std::nullptr_t, DateTime) फ़ंक्शन




```cpp
constexpr bool System::operator>(std::nullptr_t, DateTime)
```

## System::operator>(std::nullptr_t, const DateTimeOffset\&) फ़ंक्शन




```cpp
constexpr bool System::operator>(std::nullptr_t, const DateTimeOffset &)
```

## System::operator>(std::nullptr_t, const Nullable\<T\>\&) फ़ंक्शन


हमेशा false लौटाता है।

```cpp
template<typename T> bool System::operator>(std::nullptr_t, const Nullable<T> &)
```

## System::operator>(const T1\&, const Nullable\<T2\>\&) फ़ंक्शन


निर्धारित करता है कि निर्दिष्ट मान, निर्दिष्ट [Nullable](../nullable/) वस्तु द्वारा प्रस्तुत मान से बड़ा है या नहीं, इन मानों पर [operator>()](./) लागू करके।

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator>(const T1 &some, const Nullable<T2> &other)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | पहले तुलना मान का प्रकार |
| T2 | दूसरे तुलना मान को प्रतिनिधित्व करने वाले [Nullable](../nullable/) वस्तु का अंतर्निहित प्रकार |

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| some | const T1\& | पहले तुलना मान के रूप में उपयोग किए जाने वाले मान का स्थिर रेफ़रेंस |
| other | const [Nullable](../nullable/)\<T2\>\& | दोसरि तुलना मान के रूप में उपयोग किए जाने वाले मान को प्रतिनिधित्व करने वाले [Nullable](../nullable/) वस्तु का स्थिर रेफ़रेंस |

### रिटर्न वैल्यू

पहला तुलना मान दूसरे तुलना मान से बड़ा हो तो true, अन्यथा false

## System::operator>(std::nullptr_t, TimeSpan) फ़ंक्शन




```cpp
constexpr bool System::operator>(std::nullptr_t, TimeSpan)
```

## संबंधित देखें

* वर्ग [DateTime](../datetime/)
* वर्ग [DateTimeOffset](../datetimeoffset/)
* वर्ग [Nullable](../nullable/)
* वर्ग [TimeSpan](../timespan/)
* संरचना [IsNullable](../isnullable/)
* नामस्थान [System](../)
* लाइब्रेरी [Aspose.Slides](../../)