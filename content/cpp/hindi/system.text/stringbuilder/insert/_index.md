---
title: Insert()
second_title: Aspose.Slides for C++ API संदर्भ
description: बिल्डर की निश्चित स्थिति में स्ट्रिंग सम्मिलित करता है।
type: docs
weight: 183
url: /hi/system.text/stringbuilder/insert/
---
## StringBuilder::Insert(int, const String\&) विधि

बिल्डर की निश्चित स्थिति में स्ट्रिंग सम्मिलित करता है।

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, const String &str)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| startIndex | int | अक्षरों को सम्मिलित करने की स्थिति। |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) को सम्मिलित करने के लिए। |

### रिटर्न मान

यह पॉइंटर।

## StringBuilder::Insert(int32_t, const String\&, int32_t) विधि

बिल्डर की निश्चित स्थिति में दोहराई गई स्ट्रिंग सम्मिलित करता है।

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int32_t index, const String &value, int32_t count)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | अक्षरों को सम्मिलित करने की स्थिति। |
| value | const [String](../../../system/string/)\& | [String](../../../system/string/) को सम्मिलित करने के लिए। |
| count | **int32_t** | **value** स्ट्रिंग को कितनी बार दोहराना है। |

### रिटर्न मान

यह पॉइंटर।

## StringBuilder::Insert(int, char_t) विधि

बिल्डर की निश्चित स्थिति में अक्षर सम्मिलित करता है।

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, char_t ch)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| startIndex | int | अक्षरों को सम्मिलित करने की स्थिति। |
| ch | char_t | समाविष्ट करने के लिये अक्षर। |

### रिटर्न मान

यह पॉइंटर।

## StringBuilder::Insert(int, const System::ArrayPtr\<char_t\>\&, int, int) विधि

बिल्डर की निश्चित स्थिति में अक्षर सम्मिलित करता है।

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int index, const System::ArrayPtr<char_t> &chars, int startIndex, int charCount)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | अक्षरों को सम्मिलित करने की स्थिति। |
| chars | const [System::ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | [Array](../../../system/array/) से स्लाइस सम्मिलित करने के लिये। |
| startIndex | int | [Array](../../../system/array/) स्लाइस की शुरूआत इन्डेक्स। |
| charCount | int | [Array](../../../system/array/) स्लाइस की लंबाई। |

### रिटर्न मान

यह पॉइंटर।

## StringBuilder::Insert(int, T) विधि

बिल्डर की निश्चित स्थिति में मान सम्मिलित करता है।

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Insert(int startIndex, T value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| पैरामीटर | प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| startIndex | int | अक्षरों को सम्मिलित करने की स्थिति। |
| value | T | फॉर्मेट करने और सम्मिलित करने के लिये मान। |

### रिटर्न मान

यह पॉइंटर।

## देखें अन्य

* टाइपडेफ़ [ArrayPtr](../../../system/arrayptr/)
* क्लास [StringBuilder](../)
* क्लास [String](../../../system/string/)
* नेमस्पेस [System::Text](../../)
* लाइब्रेरी [Aspose.Slides](../../../)