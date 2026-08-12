---
title: ReferenceEquals()
second_title: Aspose.Slides का C++ API संदर्भ
description: "Object::ReferenceEquals का विशेषीकरण string और nullptr के केस के लिए."
type: docs
weight: 261
url: /hi/system/object/referenceequals/
---
## Object::ReferenceEquals(String const\&, std::nullptr_t) विधि

स्ट्रिंग और nullptr के मामले के लिए [Object::ReferenceEquals](./) का विशेषीकरण।

```cpp
bool System::Object::ReferenceEquals(String const &str, std::nullptr_t)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| str | [String](../../string/) const\& | [String](../../string/) को nullptr से तुलना करने के लिये। |

### वापसी मान

यदि स्ट्रिंग null है तो true, अन्यथा false।

## Object::ReferenceEquals(String const\&, String const\&) विधि

[Object::ReferenceEquals](./) का स्ट्रिंग्स के मामले के लिए विशेषीकरण।

```cpp
bool System::Object::ReferenceEquals(String const &str1, String const &str2)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| str1 | [String](../../string/) const\& | तुलना के लिए पहला स्ट्रिंग। |
| str2 | [String](../../string/) const\& | तुलना के लिए दूसरा स्ट्रिंग। |

### वापसी मान

यदि स्ट्रिंग्स मेल खाते हैं तो true, अन्यथा false।

## Object::ReferenceEquals(ptr const\&, ptr const\&) विधि

ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है।

```cpp
static bool System::Object::ReferenceEquals(ptr const &objA, ptr const &objB)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| objA | [ptr](../ptr/) const\& | तुलना के लिए पहला पॉइंटर। |
| objB | [ptr](../ptr/) const\& | तुलना के लिए दूसरा पॉइंटर। |

### वापसी मान

यदि पॉइंटर मेल खाते हैं तो True, अन्यथा false।

## Object::ReferenceEquals(T const\&, T const\&) विधि

ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है।

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, T const &objB)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | तुलना के लिए ऑब्जेक्ट्स का प्रकार। |

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| objA | T const\& | तुलना के लिए पहला ऑब्जेक्ट। |
| objB | T const\& | तुलना के लिए दूसरा ऑब्जेक्ट। |

### वापसी मान

यदि ऑब्जेक्ट पते मेल खाते हैं तो True, अन्यथा false।

## Object::ReferenceEquals(T const\&, std::nullptr_t) विधि

nullptr के साथ मान प्रकार के ऑब्जेक्ट की रेफ़रेंस तुलना करता है।

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, std::nullptr_t)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | वर्णन |
| --- | --- |
| T | तुलना के लिए ऑब्जेक्ट का प्रकार। |

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| objA | T const\& | तुलना के लिए पहला ऑब्जेक्ट। |

### वापसी मान

हमेशा false लौटाता है क्योंकि मान प्रकार को null नहीं किया जा सकता।

## देखें

* टाइपडिफ़ [ptr](../ptr/)
* क्लास [String](../../string/)
* क्लास [Object](../)
* स्ट्रक्ट [IsSmartPtr](../../issmartptr/)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)