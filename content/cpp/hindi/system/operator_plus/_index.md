---
title: operator+()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट मान और निर्दिष्ट Decimal ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मान के योग को दर्शाने वाला Decimal क्लास का नया इंस्टेंस लौटाता है।
type: docs
weight: 2185
url: /hi/system/operator_plus/
---
## System::operator+(const T\&, const Decimal\&) फ़ंक्शन

एक नया [Decimal](../decimal/) क्लास इंस्टेंस लौटाता है जो उस मान का प्रतिनिधित्व करता है जो निर्दिष्ट मान और निर्दिष्ट [Decimal](../decimal/) ऑब्जेक्ट द्वारा दर्शाए गए मान का योग है।

```cpp
template<typename T,typename _> Decimal System::operator+(const T &x, const Decimal &d)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | const T\& | पहला योगफल |
| d | const [Decimal](../decimal/)\& | दूसरे योगफल को दर्शाने वाले [Decimal](../decimal/) ऑब्जेक्ट का स्थिर संदर्भ |

### रिटर्न वैल्यू

एक नया [Decimal](../decimal/) क्लास इंस्टेंस जो उस मान का प्रतिनिधित्व करता है जो **x** और **d** द्वारा दर्शाए गए मान का योग है।

## System::operator+(MulticastDelegate\<T\>, MulticastDelegate\<T\>) फ़ंक्शन

दाएँ हाथ के डेलिगेट से सभी कॉलबैक को बाएँ हाथ के डेलिगेट कॉलबैक सूची के अंत में जोड़ता है।

```cpp
template<typename T> MulticastDelegate<T> System::operator+(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | डेलिगेट जिसमें कॉलबैक जोड़े जाते हैं। |
| rhv | MulticastDelegate\<T\> | डेलिगेट जिसके कॉलबैक जोड़े जा रहे हैं। |

### रिटर्न वैल्यू

एक डेलिगेट लौटाता है जिसमें बाएँ हाथ के मान के कॉलबैक तथा फिर दाएँ हाथ के कॉलबैक होते हैं।

## System::operator+(const T1\&, const Nullable\<T2\>\&) फ़ंक्शन

नॉन-नल और नल योग्य मानों को जोड़ता है।

```cpp
template<typename T1,typename T2,typename> auto System::operator+(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some+other.get_Value())>
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | बाएँ ऑपरेण्ड प्रकार। |
| T2 | दाएँ ऑपरेण्ड प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| some | const T1\& | बाएँ ऑपरेण्ड। |
| other | const [Nullable](../nullable/)\<T2\>\& | दाएँ ऑपरेण्ड। |

### रिटर्न वैल्यू

योग परिणाम।

## System::operator+(T\&, const String\&) फ़ंक्शन

[String](../string/) संयोजन।

```cpp
template<typename T> std::enable_if<IsStringLiteral<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | [String](../string/) लिटरल प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| left | T\& | स्ट्रिंग में जोड़ने के लिए लिटरल। |
| right | const [String](../string/)\& | [String](../string/) को जोड़ने के लिए। |

### रिटर्न वैल्यू

संयुक्त स्ट्रिंग।

## System::operator+(T\&, const String\&) फ़ंक्शन

[String](../string/) संयोजन।

```cpp
template<typename T> std::enable_if<IsStringPointer<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | [String](../string/) पॉइंटर प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| left | T\& | [String](../string/) पॉइंटर स्ट्रिंग में जोड़ने के लिए। |
| right | const [String](../string/)\& | [String](../string/) को जोड़ने के लिए। |

### रिटर्न वैल्यू

संयुक्त स्ट्रिंग।

## System::operator+(const char_t, const String\&) फ़ंक्शन

[String](../string/) संयोजन।

```cpp
String System::operator+(const char_t left, const String &right)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| left | const char_t | स्ट्रिंग में जोड़ने के लिए अक्षर। |
| right | const [String](../string/)\& | [String](../string/) को जोड़ने के लिए। |

### रिटर्न वैल्यू

संयुक्त स्ट्रिंग।

## सम्बंधित देखें

* क्लास [Decimal](../decimal/)
* क्लास [Nullable](../nullable/)
* क्लास [String](../string/)
* स्ट्रक्चर [IsStringLiteral](../isstringliteral/)
* स्ट्रक्चर [IsStringPointer](../isstringpointer/)
* नामस्थान [System](../)
* लाइब्रेरी [Aspose.Slides](../../)