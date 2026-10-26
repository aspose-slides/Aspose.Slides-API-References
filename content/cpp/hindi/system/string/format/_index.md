---
title: Format()
second_title: Aspose.Slides for C++ एपीआई संदर्भ
description: C# शैली में स्ट्रिंग को फ़ॉर्मेट करता है।
type: docs
weight: 885
url: /hi/system/string/format/
---
## String::Format(const SharedPtr\<IFormatProvider\>\&, const String\&, const Args\&...) विधि

C# शैली में स्ट्रिंग को फ़ॉर्मेट करता है।

```cpp
template<class...> String System::String::Format(const SharedPtr<IFormatProvider> &fp, const String &format, const Args &... args)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Args | स्ट्रिंग को स्वरूपित करने के लिए आर्ग्युमेंट्स। |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fp | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | फ़ॉर्मेट प्रदाता जिसका उपयोग आर्ग्युमेंट्स को स्ट्रिंग में परिवर्तित करने के लिए किया जाता है। |
| format | const [String](../)\& | फ़ॉर्मेट स्ट्रिंग। |
| args | const Args\&... | स्ट्रिंग को स्वरूपित करने के लिए आर्ग्युमेंट्स। |

## String::Format(std::nullptr_t, const String\&, const Args\&...) विधि

C# शैली में स्ट्रिंग को फ़ॉर्मेट करता है।

```cpp
template<class...> String System::String::Format(std::nullptr_t, const String &format, const Args &... args)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Args | स्ट्रिंग को स्वरूपित करने के लिए आर्ग्युमेंट्स। |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| format | std::nullptr_t | फ़ॉर्मेट स्ट्रिंग। |
| args | const [String](../)\& | स्ट्रिंग को स्वरूपित करने के लिए आर्ग्युमेंट्स। |

## String::Format(std::nullptr_t, const char16_t(&), const Args\&...) विधि

C# शैली में स्ट्रिंग को फ़ॉर्मेट करता है।

```cpp
template<std::size_t,class...> String System::String::Format(std::nullptr_t, const char16_t(&format)[N], const Args &... args)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Args | स्ट्रिंग को स्वरूपित करने के लिए आर्ग्युमेंट्स। |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| format | std::nullptr_t | फ़ॉर्मेट स्ट्रिंग। |
| args | const char16_t(&) | स्ट्रिंग को स्वरूपित करने के लिए आर्ग्युमेंट्स। |

## String::Format(const String\&, const Args\&...) विधि

C# शैली में स्ट्रिंग को फ़ॉर्मेट करता है।

```cpp
template<class...> String System::String::Format(const String &format, const Args &... args)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Args | स्ट्रिंग को स्वरूपित करने के लिए आर्ग्युमेंट्स। |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| format | const [String](../)\& | फ़ॉर्मेट स्ट्रिंग। |
| args | const Args\&... | स्ट्रिंग को स्वरूपित करने के लिए आर्ग्युमेंट्स। |

## String::Format(const String\&, const System::ArrayPtr\<T\>\&) विधि

C# शैली में स्ट्रिंग को फ़ॉर्मेट करता है।

```cpp
template<class T> String System::String::Format(const String &format, const System::ArrayPtr<T> &args)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्ट्रिंग को स्वरूपित करने के लिए आर्ग्युमेंट्स। |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| format | const [String](../)\& | फ़ॉर्मेट स्ट्रिंग। |
| args | const [System::ArrayPtr](../../arrayptr/)\<T\>\& | स्ट्रिंग को स्वरूपित करने के लिए आर्ग्युमेंट्स। |

## देखें भी

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)