---
title: GetType()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: typeof() अनुवाद को लागू करता है। स्मार्ट पॉइंटर्स के लिए ओवरलोड।
type: docs
weight: 1
url: /hi/system/objecttype/gettype/
---
## ObjectType::GetType(const T\&) विधि

typeof() अनुवाद को लागू करता है। स्मार्ट पॉइंटर्स के लिए ओवरलोड।

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```

### टेम्प्लेट पैरामीटर्स

| पैरामीटर | विवरण |
| --- | --- |
| T | पॉइंटर ऑब्जेक्ट प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) के लिए [TypeInfo](../../typeinfo/) प्राप्त करने के लिए। |

### वापसी मान

स्थिर संदर्भ [TypeInfo](../../typeinfo/) संरचना जो पास किए गए ऑब्जेक्ट की अंतिम क्लास का वर्णन करती है।

## ObjectType::GetType(const T\&) विधि

typeof() अनुवाद को लागू करता है। संरचनाओं के लिए ओवरलोड।

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```

### टेम्प्लेट पैरामीटर्स

| पैरामीटर | विवरण |
| --- | --- |
| T | संरचना प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) के लिए [TypeInfo](../../typeinfo/) प्राप्त करने के लिए। |

### वापसी मान

स्थिर संदर्भ [TypeInfo](../../typeinfo/) संरचना जो पास किए गए ऑब्जेक्ट की अंतिम क्लास का वर्णन करती है।

## ObjectType::GetType(const T\&) विधि

typeof() अनुवाद को लागू करता है। अपवादों के लिए ओवरलोड।

```cpp
template<typename T> static std::enable_if<IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```

### टेम्प्लेट पैरामीटर्स

| पैरामीटर | विवरण |
| --- | --- |
| T | अपवाद प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) के लिए [TypeInfo](../../typeinfo/) प्राप्त करने के लिए। |

### वापसी मान

स्थिर संदर्भ [TypeInfo](../../typeinfo/) संरचना जो पास किए गए ऑब्जेक्ट की अंतिम क्लास का वर्णन करती है।

## ObjectType::GetType(const T) विधि

typeof() अनुवाद को लागू करता है। प्रिमिटिव प्रकारों के लिए ओवरलोड।

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value||std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```

### टेम्प्लेट पैरामीटर्स

| पैरामीटर | विवरण |
| --- | --- |
| T | प्रिमिटिव प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | const T | IGNORED |

### वापसी मान

स्थिर संदर्भ [TypeInfo](../../typeinfo/) संरचना जो पास किए गए ऑब्जेक्ट की अंतिम क्लास का वर्णन करती है।

## ObjectType::GetType(const T) विधि

typeof() अनुवाद को लागू करता है। [Nullable](../../nullable/) प्रकारों के लिए ओवरलोड।

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```

### टेम्प्लेट पैरामीटर्स

| पैरामीटर | विवरण |
| --- | --- |
| T | [Nullable](../../nullable/) प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | const T | IGNORED |

### वापसी मान

स्थिर संदर्भ [TypeInfo](../../typeinfo/) संरचना जो पास किए गए ऑब्जेक्ट की अंतिम क्लास का वर्णन करती है।

## ObjectType::GetType() विधि

typeof() अनुवाद को लागू करता है। प्रिमिटिव प्रकारों के लिए ओवरलोड।

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value &&!std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### टेम्प्लेट पैरामीटर्स

| पैरामीटर | विवरण |
| --- | --- |
| T | प्रिमिटिव प्रकार। |

### वापसी मान

स्थिर संदर्भ [TypeInfo](../../typeinfo/) संरचना जो निर्दिष्ट प्रकार का वर्णन करती है।

## ObjectType::GetType() विधि

typeof() अनुवाद को लागू करता है। enum प्रकारों के लिए ओवरलोड।

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### टेम्प्लेट पैरामीटर्स

| पैरामीटर | विवरण |
| --- | --- |
| T | प्रिमिटिव प्रकार। |

### वापसी मान

स्थिर संदर्भ [TypeInfo](../../typeinfo/) संरचना जो निर्दिष्ट प्रकार का वर्णन करती है।

## ObjectType::GetType() विधि

typeof() अनुवाद को लागू करता है। संरचनाओं और पॉइंटर्स के लिए ओवरलोड।

```cpp
template<typename T> static std::enable_if<(!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsBoxable<T>::value)||IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### टेम्प्लेट पैरामीटर्स

| पैरामीटर | विवरण |
| --- | --- |
| T | प्रिमिटिव प्रकार। |

### वापसी मान

स्थिर संदर्भ [TypeInfo](../../typeinfo/) संरचना जो निर्दिष्ट संरचना का वर्णन करती है।

## ObjectType::GetType() विधि

typeof() अनुवाद को लागू करता है। [Nullable](../../nullable/) के लिए ओवरलोड।

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### टेम्प्लेट पैरामीटर्स

| पैरामीटर | विवरण |
| --- | --- |
| T | [Nullable](../../nullable/) प्रकार। |

### वापसी मान

स्थिर संदर्भ [TypeInfo](../../typeinfo/) संरचना जो निर्दिष्ट संरचना का वर्णन करती है।

## ObjectType::GetType() विधि

typeof() अनुवाद को लागू करता है। MutlicastDelegate के लिए ओवरलोड।

```cpp
template<typename T> static std::enable_if<detail::is_a<T, MulticastDelegate>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### टेम्प्लेट पैरामीटर्स

| पैरामीटर | विवरण |
| --- | --- |
| T | MutlicastDelegate प्रकार। |

### वापसी मान

स्थिर संदर्भ [TypeInfo](../../typeinfo/) संरचना जो निर्दिष्ट संरचना का वर्णन करती है।

## ObjectType::GetType() विधि

typeof() अनुवाद को लागू करता है। संरचनाओं और पॉइंटर्स के लिए ओवरलोड।

```cpp
template<typename T> static std::enable_if<!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&IsBoxable<T>::value &&!detail::is_a<T, MulticastDelegate>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### टेम्प्लेट पैरामीटर्स

| पैरामीटर | विवरण |
| --- | --- |
| T | प्रिमिटिव प्रकार। |

### वापसी मान

स्थिर संदर्भ [TypeInfo](../../typeinfo/) संरचना जो निर्दिष्ट संरचना या यदि [SmartPtr](../../smartptr/) के लिए बुलाया गया हो तो पॉइंटी टाइप का वर्णन करती है।

## ObjectType::GetType(const String\&) विधि

typeof() अनुवाद को लागू करता है। स्ट्रिंग प्रकार के लिए ओवरलोड।

```cpp
static const System::TypeInfo & System::ObjectType::GetType(const String &obj)
```

### टेम्प्लेट पैरामीटर्स

| पैरामीटर | विवरण |
| --- | --- |
| T | प्रिमिटिव प्रकार। |

### वापसी मान

स्थिर संदर्भ [TypeInfo](../../typeinfo/) संरचना जो [String](../../string/) प्रकार का वर्णन करती है।

## ObjectType::GetType() विधि

typeof() अनुवाद को लागू करता है। **uint8_t** के लिए ओवरलोड।

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() विधि

typeof() अनुवाद को लागू करता है। char16_t के लिए ओवरलोड।

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() विधि

typeof() अनुवाद को लागू करता है। **int32_t** के लिए ओवरलोड।

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() विधि

typeof() अनुवाद को लागू करता है। **int64_t** के लिए ओवरलोड।

```cpp
const System::TypeInfo & System::ObjectInfo::GetType()
```

## ObjectType::GetType() विधि

typeof() अनुवाद को लागू करता है। bool के लिए ओवरलोड।

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() विधि

typeof() अनुवाद को लागू करता है। [Void](../../void/) के लिए ओवरलोड।

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## संबंधित

* क्लास [ObjectType](../)
* क्लास [TypeInfo](../../typeinfo/)
* क्लास [String](../../string/)
* संरचना [IsSmartPtr](../../issmartptr/)
* संरचना [IsExceptionWrapper](../../isexceptionwrapper/)
* संरचना [IsNullable](../../isnullable/)
* संरचना [IsBoxable](../../isboxable/)
* नामस्थान [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)