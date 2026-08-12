---
title: Is()
second_title: Aspose.Slides for C++ API संदर्भ
description: 'is' ऑपरेटर अनुवाद को लागू करता है। बॉक्सेबल (value) टाइप्स के लिए विशेषीकरण जो ठीक वही हैं।
type: docs
weight: 92
url: /hi/system/objectext/is/
---
## ObjectExt::Is(const T\&) method

‘is’ ऑपरेटर अनुवाद को लागू करता है। बॉक्सेबल (value) टाइप्स के लिए विशेषीकरण जो ठीक वही हैं।

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value, bool>::type System::ObjectExt::Is(const T &obj)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | टार्गेट प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) 'is' ऑपरेटर का परीक्षण करने के लिए। अनदेखा। |

### रिटर्न वैल्यू

हमेशा true

## ObjectExt::Is(const U\&) method

‘is’ ऑपरेटर अनुवाद को लागू करता है। फ़ाइनल क्लासों के लिए अनुकूलित पॉइंटर टाइप्स का विशेषीकरण।

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | टार्गेट प्रकार। |
| U | परीक्षण किया गया प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) 'is' ऑपरेटर का परीक्षण करने के लिए। |

### रिटर्न वैल्यू

‘is’ true लौटाता है तो true, अन्यथा false।

## ObjectExt::Is(const U\&) method

‘is’ ऑपरेटर अनुवाद को लागू करता है। पॉइंटर टाइप्स का विशेषीकरण।

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&!std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | टार्गेट प्रकार। |
| U | परीक्षण किया गया प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) 'is' ऑपरेटर का परीक्षण करने के लिए। |

### रिटर्न वैल्यू

‘is’ true लौटाता है तो true, अन्यथा false।

## ObjectExt::Is(const Object\&) method

‘is’ ऑपरेटर अनुवाद को लागू करता है। वैल्यू टाइप्स का विशेषीकरण।

```cpp
template<class T> static std::enable_if<std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | टार्गेट प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | const [Object](../../object/)\& | [Object](../../object/) 'is' ऑपरेटर का परीक्षण करने के लिए। |

### रिटर्न वैल्यू

‘is’ true लौटाता है तो true, अन्यथा false।

## ObjectExt::Is(const Object\&) method

‘is’ ऑपरेटर अनुवाद को लागू करता है। अपरिवर्तनीय टाइप्स का विशेषीकरण।

```cpp
template<class T> static std::enable_if<!std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | टार्गेट प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | const [Object](../../object/)\& | [Object](../../object/) 'is' ऑपरेटर का परीक्षण करने के लिए। |

### रिटर्न वैल्यू

टाइप्स अपरिवर्तनीय होने के कारण हमेशा false लौटाता है।

## ObjectExt::Is(const SmartPtr\<U\>\&) method

‘is’ ऑपरेटर अनुवाद को लागू करता है। पॉइंटर टाइप्स का विशेषीकरण।

```cpp
template<class T,class U> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | टार्गेट प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<U\>\& | [Object](../../object/) 'is' ऑपरेटर का परीक्षण करने के लिए। |

### रिटर्न वैल्यू

‘is’ true लौटाता है तो true, अन्यथा false।

## ObjectExt::Is(const ExceptionWrapper\<U\>\&) method

‘is’ ऑपरेटर अनुवाद को लागू करता है। एक्सेप्शन रैपर टाइप्स का विशेषीकरण।

```cpp
template<class T,class U> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Is(const ExceptionWrapper<U> &obj)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | टार्गेट प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | const [ExceptionWrapper](../../exceptionwrapper/)\<U\>\& | [Object](../../object/) 'is' ऑपरेटर का परीक्षण करने के लिए। |

### रिटर्न वैल्यू

‘is’ true लौटाता है तो true, अन्यथा false।

## ObjectExt::Is(const SmartPtr\<Object\>\&) method

‘is’ ऑपरेटर अनुवाद को लागू करता है। nullable टाइप्स का विशेषीकरण।

```cpp
template<class T> static std::enable_if<IsNullable<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | टार्गेट प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) 'is' ऑपरेटर का परीक्षण करने के लिए। |

### रिटर्न वैल्यू

‘is’ true लौटाता है तो true, अन्यथा false।

## ObjectExt::Is(const SmartPtr\<Object\>\&) method

‘is’ ऑपरेटर अनुवाद को लागू करता है। == ऑपरेटर परिभाषित बॉक्सेबल टाइप्स का विशेषीकरण।

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | टार्गेट प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) 'is' ऑपरेटर का परीक्षण करने के लिए। |

### रिटर्न वैल्यू

‘is’ true लौटाता है तो true, अन्यथा false।

## ObjectExt::Is(const SmartPtr\<Object\>\&) method

‘is’ ऑपरेटर अनुवाद को लागू करता है। == परिभाषित नहीं बॉक्सेबल टाइप्स का विशेषीकरण।

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | टार्गेट प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) 'is' ऑपरेटर का परीक्षण करने के लिए। |

### रिटर्न वैल्यू

‘is’ true लौटाता है तो true, अन्यथा false।

## ObjectExt::Is(const SmartPtr\<V\>\&) method

‘is’ ऑपरेटर अनुवाद को लागू करता है। इंटरफ़ेसेस में बॉक्स्ड वैल्यू टाइप्स का विशेषीकरण।

```cpp
template<class T,class V> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!std::is_same<V, Object>::value, bool>::type System::ObjectExt::Is(const SmartPtr<V> &obj)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | टार्गेट प्रकार। |
| V | पॉइंटेड ऑब्जेक्ट का प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<V\>\& | [Object](../../object/) 'is' ऑपरेटर का परीक्षण करने के लिए। |

### रिटर्न वैल्यू

‘is’ true लौटाता है तो true, अन्यथा false।

## ObjectExt::Is(const SmartPtr\<U\>\&) method

‘is’ ऑपरेटर अनुवाद को लागू करता है। enum टाइप्स का विशेषीकरण।

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | टार्गेट प्रकार। |
| U | पॉइंटेड ऑब्जेक्ट का प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<U\>\& | [Object](../../object/) 'is' ऑपरेटर का परीक्षण करने के लिए। |

### रिटर्न वैल्यू

‘is’ true लौटाता है तो true, अन्यथा false।

## ObjectExt::Is(const WeakPtr\<U\>\&) method

‘is’ ऑपरेटर अनुवाद को लागू करता है। enum टाइप्स बनाम weak पॉइंटर्स का विशेषीकरण।

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const WeakPtr<U> &obj)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | टार्गेट प्रकार। |
| U | पॉइंटेड ऑब्जेक्ट का प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | const [WeakPtr](../../weakptr/)\<U\>\& | [Object](../../object/) 'is' ऑपरेटर का परीक्षण करने के लिए। |

### रिटर्न वैल्यू

‘is’ true लौटाता है तो true, अन्यथा false।

## ObjectExt::Is(const Nullable\<U\>\&) method

‘is’ ऑपरेटर अनुवाद को लागू करता है। [Nullable](../../nullable/) टाइप के लिए विशेषीकरण।

```cpp
template<class T,class U> static bool System::ObjectExt::Is(const Nullable<U> &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | टार्गेट प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const [Nullable](../../nullable/)\<U\>\& | [Nullable](../../nullable/) टाइप। |

### रिटर्न वैल्यू

‘is’ true लौटाता है तो true, अन्यथा false।

## ObjectExt::Is(const char16_t *) method

‘is’ ऑपरेटर अनुवाद को लागू करता है। स्ट्रिंग लिटरल के लिए विशेषीकरण।

```cpp
template<class T> static bool System::ObjectExt::Is(const char16_t *str)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | टार्गेट प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| str | const char16_t * | [String](../../string/) लिटरल। |

### रिटर्न वैल्यू

‘is’ true लौटाता है तो true, अन्यथा false।

## ObjectExt::Is(int32_t) method

‘is’ ऑपरेटर अनुवाद को लागू करता है। इंटेजर लिटरल के लिए विशेषीकरण।

```cpp
template<class T> static bool System::ObjectExt::Is(int32_t value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | टार्गेट प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | **int32_t** | इंटेजर लिटरल। |

### रिटर्न वैल्यू

‘is’ true लौटाता है तो true, अन्यथा false।

## संबंधित देखें

* क्लास [ObjectExt](../)
* क्लास [Object](../../object/)
* क्लास [SmartPtr](../../smartptr/)
* क्लास [ExceptionWrapper](../../exceptionwrapper/)
* क्लास [WeakPtr](../../weakptr/)
* क्लास [Nullable](../../nullable/)
* स्ट्रक्ट [IsBoxable](../../isboxable/)
* स्ट्रक्ट [IsSmartPtr](../../issmartptr/)
* स्ट्रक्ट [IsExceptionWrapper](../../isexceptionwrapper/)
* स्ट्रक्ट [IsNullable](../../isnullable/)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)