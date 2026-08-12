---
title: ToString()
second_title: Aspose.Slides for C++ API संदर्भ
description: C# ToString मेथड का प्रतिस्थापन जो किसी भी C++ प्रकार पर काम करता है।
type: docs
weight: 27
url: /hi/system/objectext/tostring/
---
## ObjectExt::ToString(const char_t *) विधि

C# ToString मेथड का प्रतिस्थापन जो किसी भी C++ प्रकार पर काम करता है।

```cpp
static String System::ObjectExt::ToString(const char_t *obj)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | const char_t * | [String](../../string/) लिटरल को स्ट्रिंग में परिवर्तित करने के लिए। |

### रिटर्न मान

[String](../../string/) **obj** का प्रतिनिधित्व।

## ObjectExt::ToString(const Nullable\<T\>\&) विधि

C# ToString मेथड का प्रतिस्थापन जो किसी भी C++ प्रकार पर काम करता है।

```cpp
template<typename T> static String System::ObjectExt::ToString(const Nullable<T> &obj)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | [Nullable](../../nullable/) प्रकार। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | const [Nullable](../../nullable/)\<T\>\& | [Nullable](../../nullable/) ऑब्जेक्ट को स्ट्रिंग में परिवर्तित करने के लिये। |

### रिटर्न मान

[String](../../string/) **obj** का प्रतिनिधित्व।

## ObjectExt::ToString(const T\&) विधि

C# ToString मेथड का प्रतिस्थापन जो किसी भी C++ प्रकार पर काम करता है।

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | [Enum](../../enum/) प्रकार। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | const T\& | [Enum](../../enum/) मान को स्ट्रिंग में परिवर्तित करने के लिये। |

### रिटर्न मान

[String](../../string/) **obj** का प्रतिनिधित्व।

## ObjectExt::ToString(const T\&) विधि

C# ToString मेथड का प्रतिस्थापन जो किसी भी C++ प्रकार पर काम करता है।

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्मार्ट पॉइंटर प्रकार। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | const T\& | [SmartPtr](../../smartptr/) मान को स्ट्रिंग में परिवर्तित करने के लिये। |

### रिटर्न मान

[String](../../string/) **obj** का प्रतिनिधित्व।

## ObjectExt::ToString(T\&) विधि

C# ToString मेथड का प्रतिस्थापन जो किसी भी C++ प्रकार पर काम करता है।

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value||std::is_pointer<T>::value||IsExceptionWrapper<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्मार्ट पॉइंटर प्रकार या [ExceptionWrapper](../../exceptionwrapper/)। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | T\& | स्मार्ट पॉइंटर या [ExceptionWrapper](../../exceptionwrapper/) को स्ट्रिंग में परिवर्तित करने के लिये। |

### रिटर्न मान

[String](../../string/) **obj** का प्रतिनिधित्व।

## ObjectExt::ToString(T\&) विधि

C# ToString मेथड का प्रतिस्थापन जो किसी भी C++ प्रकार पर काम करता है।

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्केलर प्रकार। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | T\& | स्केलर मान को स्ट्रिंग में परिवर्तित करने के लिये। |

### रिटर्न मान

[String](../../string/) **obj** का प्रतिनिधित्व।

## ObjectExt::ToString(T\&&) विधि

C# ToString मेथड का प्रतिस्थापन जो किसी भी C++ प्रकार पर काम करता है।

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्केलर प्रकार। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | T\&& | स्केलर मान को स्ट्रिंग में परिवर्तित करने के लिये। |

### रिटर्न मान

[String](../../string/) **obj** का प्रतिनिधित्व।

## ObjectExt::ToString(T\&) विधि

C# ToString मेथड का प्रतिस्थापन जो किसी भी C++ प्रकार पर काम करता है।

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | संरचना प्रकार। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | T\& | संरचना मान को स्ट्रिंग में परिवर्तित करने के लिये। |

### रिटर्न मान

[String](../../string/) **obj** का प्रतिनिधित्व।

## ObjectExt::ToString(const T\&) विधि

C# ToString मेथड का प्रतिस्थापन जो किसी भी C++ प्रकार पर काम करता है।

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | संरचना प्रकार। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | const T\& | संरचना मान को स्ट्रिंग में परिवर्तित करने के लिये। |

### रिटर्न मान

[String](../../string/) **obj** का प्रतिनिधित्व।

## ObjectExt::ToString(T\&&) विधि

C# ToString मेथड का प्रतिस्थापन जो किसी भी C++ प्रकार पर काम करता है।

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value &&!std::is_reference<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्केलर प्रकार। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | T\&& | स्केलर मान को स्ट्रिंग में परिवर्तित करने के लिये। |

### रिटर्न मान

[String](../../string/) **obj** का प्रतिनिधित्व।

## देखें

* क्लास [String](../../string/)
* क्लास [ObjectExt](../)
* क्लास [Nullable](../../nullable/)
* स्ट्रक्ट [IsSmartPtr](../../issmartptr/)
* स्ट्रक्ट [IsExceptionWrapper](../../isexceptionwrapper/)
* स्ट्रक्ट [IsNullable](../../isnullable/)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)