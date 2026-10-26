---
title: PrintTo()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: ostream में मान को प्रिंट करता है। अधिकांशतः डिबग के लिए उपयोग किया जाता है।
type: docs
weight: 2146
url: /hi/system/printto/
---
## System::PrintTo(DateTime, std::ostream *) फ़ंक्शन

ostream में मान को प्रिंट करता है। अधिकांशतः डिबग के लिए उपयोग किया जाता है।

```cpp
void System::PrintTo(DateTime value, std::ostream *stream)
```

## System::PrintTo(DateTimeOffset, std::ostream *) फ़ंक्शन

ostream में मान को प्रिंट करता है। अधिकांशतः डिबग के लिए उपयोग किया जाता है।

```cpp
void System::PrintTo(DateTimeOffset value, std::ostream *stream)
```

## System::PrintTo(const Decimal\&, ::std::ostream *) फ़ंक्शन

निर्दिष्ट ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया मान निर्दिष्ट आउटपुट स्ट्रीम में लिखता है।

```cpp
void System::PrintTo(const Decimal &d, ::std::ostream *os)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| d | const [Decimal](../decimal/)\& | स्ट्रीम में प्रिंट करने के लिए [Decimal](../decimal/) ऑब्जेक्ट |
| os | ::std::ostream * | निर्दिष्ट ऑब्जेक्ट को प्रिंट करने के लिए स्ट्रीम |

## System::PrintTo(const Details_Exception\&, std::ostream *) फ़ंक्शन

ostream में मान को प्रिंट करता है। अधिकांशतः डिबग के लिए उपयोग किया जाता है।

```cpp
void System::PrintTo(const Details_Exception &exception, std::ostream *stream)
```

## System::PrintTo(const ExceptionWrapper\<T\>\&, std::ostream *) फ़ंक्शन

ostream में मान को प्रिंट करता है। अधिकांशतः डिबग के लिए उपयोग किया जाता है।

```cpp
template<typename T> void System::PrintTo(const ExceptionWrapper<T> &exception_wrapper, std::ostream *stream)
```

## System::PrintTo(const Guid\&, std::ostream *) फ़ंक्शन

ostream में मान को प्रिंट करता है। अधिकांशतः डिबग के लिए उपयोग किया जाता है।

```cpp
void System::PrintTo(const Guid &value, std::ostream *stream)
```

## System::PrintTo(const Nullable\<T\>\&, std::ostream *) फ़ंक्शन

ostream में मान को प्रिंट करता है। अधिकांशतः डिबग के लिए उपयोग किया जाता है।

```cpp
template<typename T> void System::PrintTo(const Nullable<T> &value, std::ostream *stream)
```

## System::PrintTo(const System::Object\&, std::ostream *) फ़ंक्शन

ostream में मान को प्रिंट करता है। अधिकांशतः डिबग के लिए उपयोग किया जाता है।

```cpp
void System::PrintTo(const System::Object &value, std::ostream *stream)
```

## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) फ़ंक्शन

ostream में मान को प्रिंट करता है। अधिकांशतः डिबग के लिए उपयोग किया जाता है।

```cpp
template<typename T> std::enable_if_t<detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) फ़ंक्शन

ostream में मान को प्रिंट करता है। अधिकांशतः डिबग के लिए उपयोग किया जाता है।

```cpp
template<typename T> std::enable_if_t<!detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## System::PrintTo(const System::String\&, std::ostream *) फ़ंक्शन

ostream में स्ट्रिंग को प्रिंट करता है। अधिकांशतः डिबग के लिए उपयोग किया जाता है।

```cpp
void System::PrintTo(const System::String &value, std::ostream *os)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const [System::String](../string/)\& | प्रिंट करने के लिए। |
| os | std::ostream * | लक्ष्य ostream। |

## System::PrintTo(TimeSpan, std::ostream *) फ़ंक्शन

ostream में मान को प्रिंट करता है। अधिकांशतः डिबग के लिए उपयोग किया जाता है।

```cpp
void System::PrintTo(TimeSpan value, std::ostream *stream)
```

## System::PrintTo(const WeakPtr\<T\>\&, std::ostream *) फ़ंक्शन

ostream में मान को प्रिंट करता है। अधिकांशतः डिबग के लिए उपयोग किया जाता है।

```cpp
template<typename T> void System::PrintTo(const WeakPtr<T> &object_ptr, std::ostream *stream)
```

## संबंधित देखें

* क्लास [DateTime](../datetime/)
* क्लास [DateTimeOffset](../datetimeoffset/)
* क्लास [Decimal](../decimal/)
* क्लास [Details_Exception](../details_exception/)
* क्लास [ExceptionWrapper](../exceptionwrapper/)
* क्लास [Guid](../guid/)
* क्लास [Nullable](../nullable/)
* क्लास [Object](../object/)
* क्लास [SmartPtr](../smartptr/)
* क्लास [String](../string/)
* क्लास [TimeSpan](../timespan/)
* क्लास [WeakPtr](../weakptr/)
* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)