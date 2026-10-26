---
title: operator+()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: स्ट्रिंग संयोजन ऑपरेटर.
type: docs
weight: 274
url: /hi/system/string/operator_plus/
---
## String::operator+(const String\&) const विधि

[String](../) संयोजन ऑपरेटर।

```cpp
String System::String::operator+(const String &str) const
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) को वर्तमान स्ट्रिंग के अंत में जोड़ने के लिए। |

### रिटर्न मान

संयोजित स्ट्रिंग।

## String::operator+(const T\&) const विधि

[String](../) स्ट्रिंग लिटरल या कैरेक्टर स्ट्रिंग पॉइंटर के साथ संयोजन।

```cpp
template<typename T,std::enable_if_t< IsStringLiteral< T, char_t >::value > *> String System::String::operator+(const T &arg) const
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्ट्रिंग लिटरल या कैरेक्टर स्ट्रिंग पॉइंटर फॉर्म में से एक। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg | const T\& | वर्तमान स्ट्रिंग के साथ संयोजित करने के लिए इकाई। |

### रिटर्न मान

संयोजित स्ट्रिंग।

## String::operator+(char_t) const विधि

स्ट्रिंग के अंत में अक्षर जोड़ता है।

```cpp
String System::String::operator+(char_t x) const
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | char_t | जोड़ने के लिए अक्षर। |

### रिटर्न मान

[String](../) संयोजन परिणाम।

## String::operator+(int) const विधि

स्ट्रिंग के अंत में पूर्णांक मान की स्ट्रिंग प्रतिनिधित्व जोड़ता है।

```cpp
String System::String::operator+(int i) const
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| i | int | स्ट्रिंग में बदलने और जोड़ने के लिए पूर्णांक मान। |

### रिटर्न मान

[String](../) संयोजन परिणाम।

## String::operator+(uint32_t) const विधि

स्ट्रिंग के अंत में अनसाइन्ड पूर्णांक मान की स्ट्रिंग प्रतिनिधित्व जोड़ता है।

```cpp
String System::String::operator+(uint32_t i) const
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| i | **uint32_t** | स्ट्रिंग में बदलने और जोड़ने के लिए मान। |

### रिटर्न मान

[String](../) संयोजन परिणाम।

## String::operator+(double) const विधि

स्ट्रिंग के अंत में फ्लोटिंग पॉइंट मान की स्ट्रिंग प्रतिनिधित्व जोड़ता है।

```cpp
String System::String::operator+(double d) const
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| d | **double** | स्ट्रिंग में बदलने और जोड़ने के लिए मान। |

### रिटर्न मान

[String](../) संयोजन परिणाम।

## String::operator+(int64_t) const विधि

स्ट्रिंग के अंत में पूर्णांक मान की स्ट्रिंग प्रतिनिधित्व जोड़ता है।

```cpp
String System::String::operator+(int64_t v) const
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| v | **int64_t** | स्ट्रिंग में बदलने और जोड़ने के लिए मान। |

### रिटर्न मान

[String](../) संयोजन परिणाम।

## String::operator+(const T\&) const विधि

स्ट्रिंग के अंत में रेफ़रेंस टाइप ऑब्जेक्ट की स्ट्रिंग प्रतिनिधित्व जोड़ता है।

```cpp
template<typename T,std::enable_if_t< IsSmartPtr< T >::value > *> String System::String::operator+(const T &value) const
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | पोइंटर टाइप। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) को [ToString()](../tostring/) कॉल का उपयोग करके स्ट्रिंग में बदलने और वर्तमान स्ट्रिंग में जोड़ने के लिए। |

### रिटर्न मान

[String](../) संयोजन परिणाम।

## String::operator+(const T\&) const विधि

स्ट्रिंग के अंत में वैल्यू टाइप ऑब्जेक्ट की स्ट्रिंग प्रतिनिधित्व जोड़ता है।

```cpp
template<typename T,std::enable_if_t<!IsSmartPtr< T >::value &&!std::is_scalar< T >::value &&!std::is_array< T >::value > *> String System::String::operator+(const T &value) const
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | [ToString()](../tostring/) को कॉल करने के लिए वैल्यू टाइप। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) को [ToString()](../tostring/) कॉल का उपयोग करके स्ट्रिंग में बदलने और वर्तमान स्ट्रिंग में जोड़ने के लिए। |

### रिटर्न मान

[String](../) संयोजन परिणाम।

## String::operator+(T) const विधि

स्ट्रिंग के अंत में बूलियन मान की स्ट्रिंग प्रतिनिधित्व जोड़ता है।

```cpp
template<typename T,std::enable_if_t< std::is_same< T, bool >::value > *> String System::String::operator+(T arg) const
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्ट्रिंग के साथ संयोजित करने के लिए वैल्यू टाइप। Must be bool |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg | T | [Boolean](../../boolean/) को स्ट्रिंग में बदलने और जोड़ने के लिए। |

### रिटर्न मान

[String](../) संयोजन परिणाम।

## देखें

* क्लास [String](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)