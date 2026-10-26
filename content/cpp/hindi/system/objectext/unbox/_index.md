---
title: Unbox()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: ऑब्जेक्ट में परिवर्तित करने के बाद वैल्यू टाइप्स को अनबॉक्स करता है। एन्कम प्रकारों के लिए कार्यान्वयन।
type: docs
weight: 53
url: /hi/system/objectext/unbox/
---
## ObjectExt::Unbox(const SmartPtr\<Object\>\&) मेथड


[Object](../../object/) में परिवर्तित करने के बाद वैल्यू टाइप्स को अनबॉक्स करता है। एन्कम प्रकारों के लिए कार्यान्वयन।

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | [Enum](../../enum/) प्रकार। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) को अनबॉक्स करने के लिए। |

### वापसी मान

[Enum](../../enum/) मान।

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) मेथड


[Object](../../object/) में परिवर्तित करने के बाद वैल्यू टाइप्स को अनबॉक्स करता है। नॉन-एन्यूम और नॉन-नलएबल प्रकारों के लिए कार्यान्वयन।

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | वैल्यू प्रकार। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) को अनबॉक्स करने के लिए। |

### वापसी मान

अनबॉक्स्ड मान।

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) मेथड


[Object](../../object/) में परिवर्तित करने के बाद वैल्यू टाइप्स को अनबॉक्स करता है। नॉन-एन्यूम और नॉन-नलएबल प्रकारों के लिए कार्यान्वयन।

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | वैल्यू प्रकार। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) को अनबॉक्स करने के लिए। |

### वापसी मान

अनबॉक्स्ड मान।

## ObjectExt::Unbox(E) मेथड


enum प्रकारों को इंटीजर में अनबॉक्स करता है।

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::numeric_limits<T>::is_integer, T>::type System::ObjectExt::Unbox(E e)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | गंतव्य इंटीजर प्रकार। |
| E | स्रोत enum प्रकार। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| e | E | अनबॉक्स करने के लिए मान। |

### वापसी मान

enum का इंटीजर प्रतिनिधित्व।

## ObjectExt::Unbox(E) मेथड


enum प्रकारों को परिवर्तित करता है।

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(E e)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | गंतव्य enum प्रकार। |
| E | स्रोत enum प्रकार। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| e | E | अनबॉक्स करने के लिए मान। |

### वापसी मान

परिवर्तित enum मान।

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) मेथड


स्ट्रिंग वैल्यूज़ को अनबॉक्स करता है।

```cpp
String System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) को अनबॉक्स करने के लिए। |

### वापसी मान

बॉक्स्ड स्ट्रिंग का [String](../../string/) प्रस्तुतीकरण, यदि बॉक्स्ड स्ट्रिंग नल थी तो यह नल हो सकता है।

## देखें

* क्लास [SmartPtr](../../smartptr/)
* क्लास [Object](../../object/)
* क्लास [ObjectExt](../)
* क्लास [String](../../string/)
* नामस्थान [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)