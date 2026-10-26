---
title: Concat()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: स्ट्रिंग एरे को जोड़ता है।
type: docs
weight: 1
url: /hi/system.stringextra/concat/
---
## System::StringExtra::Concat(const ArrayPtr\<String\>\&) फ़ंक्शन


स्ट्रिंग एरे को जोड़ता है।

```cpp
String System::StringExtra::Concat(const ArrayPtr<String> &parts)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| parts | const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\& | [Array](../../system/array/) of strings to join. |

### रिटर्न मान

जुड़ी हुई स्ट्रिंग।

## System::StringExtra::Concat(const String\&, const String\&) फ़ंक्शन


स्ट्रिंग्स को जोड़ता है।

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | First string to concatenate. |
| str1 | const [String](../../system/string/)\& | Second string to concatenate. |

### रिटर्न मान

जुड़े हुए पैरामीटर स्ट्रिंग्स।

## System::StringExtra::Concat(const String\&, const String\&, const String\&) फ़ंक्शन


स्ट्रिंग्स को जोड़ता है।

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | First string to concatenate. |
| str1 | const [String](../../system/string/)\& | Second string to concatenate. |
| str2 | const [String](../../system/string/)\& | Third string to concatenate. |

### रिटर्न मान

जुड़े हुए पैरामीटर स्ट्रिंग्स।

## System::StringExtra::Concat(const String\&, const String\&, const String\&, const String\&) फ़ंक्शन


स्ट्रिंग्स को जोड़ता है।

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2, const String &str3)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | First string to concatenate. |
| str1 | const [String](../../system/string/)\& | Second string to concatenate. |
| str2 | const [String](../../system/string/)\& | Third string to concatenate. |
| str3 | const [String](../../system/string/)\& | Fourth string to concatenate. |

### रिटर्न मान

जुड़े हुए पैरामीटर स्ट्रिंग्स।

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) फ़ंक्शन


कई ऑब्जेक्ट्स को स्ट्रिंग में बदलता है और परिणामी स्ट्रिंग्स को जोड़ता है। [SmartPtr](../../system/smartptr/) प्रकारों के लिए विशेषीकरण।

```cpp
template<typename T> std::enable_if_t<IsSmartPtr<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) to convert and join. |

### रिटर्न मान

सभी पास किए गए ऑब्जेक्ट्स के स्ट्रिंग प्रतिनिधित्व से संयुक्त [String](../../system/string/) मान।

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) फ़ंक्शन


कई ऑब्जेक्ट्स को स्ट्रिंग में बदलता है और परिणामी स्ट्रिंग्स को जोड़ता है। अंकगणितीय प्रकारों के लिए विशेषीकरण।

```cpp
template<typename T> std::enable_if_t<std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) to convert and join. |

### रिटर्न मान

सभी पास किए गए ऑब्जेक्ट्स के स्ट्रिंग प्रतिनिधित्व से संयुक्त [String](../../system/string/) मान।

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) फ़ंक्शन


कई ऑब्जेक्ट्स को स्ट्रिंग में बदलता है और परिणामी स्ट्रिंग्स को जोड़ता है। संरचनाओं और अन्य मान प्रकारों के लिए विशेषीकरण।

```cpp
template<typename T> std::enable_if_t<!IsSmartPtr<T>::value &&!std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) to convert and join. |

### रिटर्न मान

सभी पास किए गए ऑब्जेक्ट्स के स्ट्रिंग प्रतिनिधित्व से संयुक्त [String](../../system/string/) मान।

## देखें

* टाइपडिफ [ArrayPtr](../../system/arrayptr/)
* क्लास [String](../../system/string/)
* स्ट्रक्ट [IsSmartPtr](../../system/issmartptr/)
* नेमस्पेस [System::StringExtra](../)
* लाइब्रेरी [Aspose.Slides](../../)