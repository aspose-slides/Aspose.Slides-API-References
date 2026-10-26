---
title: Append()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: बिल्डर में अक्षर जोड़ता है।
type: docs
weight: 118
url: /hi/system.text/stringbuilder/append/
---
## StringBuilder::Append(char_t) मेथड

बिल्डर में अक्षर जोड़ता है।

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| c | char_t | अक्षर मान। |

### वापसी मान

यह पॉइंटर।

## StringBuilder::Append(char_t, int) मेथड

बिल्डर में अक्षर जोड़ता है।

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c, int count)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| c | char_t | अक्षर मान। |
| count | int | इंसर्ट किए गए अक्षर को कितनी बार दोहराना है। |

### वापसी मान

यह पॉइंटर।

## StringBuilder::Append(const ArrayPtr\<char_t\>\&) मेथड

बिल्डर में अक्षर एरे जोड़ता है।

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | जोड़ने के लिए अक्षर। |

### वापसी मान

यह पॉइंटर।

## StringBuilder::Append(const ArrayPtr\<char_t\>\&, int, int) मेथड

बिल्डर में अक्षर एरे का स्लाइस जोड़ता है।

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr, int startIndex, int charCount)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | जोड़ने के लिए अक्षर। |
| startIndex | int | स्लाइस की प्रारम्भिक इंडेक्स। |
| charCount | int | स्लाइस की लंबाई। |

### वापसी मान

यह पॉइंटर।

## StringBuilder::Append(const String\&) मेथड

बिल्डर में स्ट्रिंग जोड़ता है।

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) जोड़ने के लिए। |

### वापसी मान

यह पॉइंटर।

## StringBuilder::Append(const String\&, int, int) मेथड

बिल्डर में स्ट्रिंग स्लाइस जोड़ता है।

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str, int startIndex, int charCount)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) जोड़ने के लिए। |
| startIndex | int | स्लाइस की प्रारम्भिक इंडेक्स। |
| charCount | int | स्लाइस की लंबाई। |

### वापसी मान

यह पॉइंटर।

## StringBuilder::Append(const SharedPtr\<T\>\&) मेथड

बिल्डर में ऑब्जेक्ट की स्ट्रिंग प्रतिनिधित्व जोड़ता है।

```cpp
template<class T> StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<T> &obj)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | [Object](../../../system/object/) प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<T\>\& | [Object](../../../system/object/) को सीरियलाइज़ करके जोड़ने के लिए। |

### वापसी मान

यह पॉइंटर।

## StringBuilder::Append(const SharedPtr\<StringBuilder\>\&) मेथड

बिल्डर की सामग्री को बिल्डर में जोड़ता है।

```cpp
StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<StringBuilder> &builder)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| builder | const [SharedPtr](../../../system/sharedptr/)\<[StringBuilder](../)\>\& | सामग्री जोड़ने के लिए बिल्डर। |

### वापसी मान

यह पॉइंटर।

## StringBuilder::Append(float) मेथड

बिल्डर में फ्लोटिंग पॉइंट मान जोड़ता है।

```cpp
StringBuilder * System::Text::StringBuilder::Append(float f)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| f | **float** | सीरियलाइज़ करके जोड़ने के लिए मान। |

### वापसी मान

यह पॉइंटर।

## StringBuilder::Append(double) मेथड

बिल्डर में फ्लोटिंग पॉइंट मान जोड़ता है।

```cpp
StringBuilder * System::Text::StringBuilder::Append(double df)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| df | **double** | सीरियलाइज़ करके जोड़ने के लिए मान। |

### वापसी मान

यह पॉइंटर।

## StringBuilder::Append(int) मेथड

बिल्डर में इंटीजर मान जोड़ता है।

```cpp
StringBuilder * System::Text::StringBuilder::Append(int i)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| i | int | सीरियलाइज़ करके जोड़ने के लिए मान। |

### वापसी मान

यह पॉइंटर।

## StringBuilder::Append(T) मेथड

बिल्डर में अरिथ्मेटिक मान जोड़ता है।

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Append(T value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | अरिथ्मेटिक प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | T | सीरियलाइज़ करके जोड़ने के लिए मान। |

### वापसी मान

यह पॉइंटर।

## StringBuilder::Append(E) मेथड

बिल्डर में एनीम मान की स्ट्रिंग प्रतिनिधित्व जोड़ता है।

```cpp
template<class E> std::enable_if<std::is_enum<E>::value, StringBuilder *>::type System::Text::StringBuilder::Append(E e)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| E | [Enum](../../../system/enum/) प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| e | E | सीरियलाइज़ करके जोड़ने के लिए मान। |

### वापसी मान

यह पॉइंटर।

## संबंधित देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [StringBuilder](../)
* Class [String](../../../system/string/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)