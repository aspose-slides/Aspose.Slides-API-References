---
title: Equals()
second_title: Aspose.Slides for C++ API संदर्भ
description: C# Object.Equals सेमांटिक्स का उपयोग करके वस्तुओं की तुलना करता है।
type: docs
weight: 157
url: /hi/system/object/equals/
---
## Object::Equals(ptr) विधि

C# [Object.Equals](./) सेमांटिक्स का उपयोग करके वस्तुओं की तुलना करता है।

```cpp
virtual bool System::Object::Equals(ptr obj)
```

### आर्ग्युमेंट

| परामितर | प्रकार | विवरण |
| --- | --- | --- |
| obj | [ptr](../ptr/) | [Object](../) वर्तमान वस्तु की तुलना करने के लिए। |

### रिटर्न मान

यदि वस्तुएँ समान मान ली जाती हैं तो true, अन्यथा false।

## Object::Equals(T1 const\&, T2 const\&) विधि

C# शैली में रेफ़रेंस टाइप वस्तुओं की तुलना करता है।

```cpp
template<typename T1,typename T2> static std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```

### टेम्प्लेट पैरामीटर

| परामितर | विवरण |
| --- | --- |
| T1 | पहली तुलना की जाने वाली वस्तु का प्रकार। |
| T2 | दूसरे तुलना की जाने वाली वस्तु का प्रकार। |

### आर्ग्युमेंट

| परामितर | प्रकार | विवरण |
| --- | --- | --- |
| objA | T1 const\& | तुलना के लिए पहली वस्तु। |
| objB | T2 const\& | तुलना के लिए दूसरी वस्तु। |

### रिटर्न मान

यदि वस्तुएँ रेफ़रेंस या सारतः ([Object.Equals](./)-जैसी तुलना द्वारा) मेल खाती हैं तो true, अन्यथा false।

## Object::Equals(T1 const\&, T2 const\&) विधि

C# शैली में वैल्यू टाइप वस्तुओं की तुलना करता है।

```cpp
template<typename T1,typename T2> static std::enable_if<!IsSmartPtr<T1>::value &&!IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```

### टेम्प्लेट पैरामीटर

| परामितर | विवरण |
| --- | --- |
| T1 | पहली तुलना की जाने वाली वस्तु का प्रकार। |
| T2 | दूसरे तुलना की जाने वाली वस्तु का प्रकार। |

### आर्ग्युमेंट

| परामितर | प्रकार | विवरण |
| --- | --- | --- |
| objA | T1 const\& | तुलना के लिए पहली वस्तु। |
| objB | T2 const\& | तुलना के लिए दूसरी वस्तु। |

### रिटर्न मान

यदि वस्तुओं को उपलब्ध समानता ऑपरेटर द्वारा समान माना जाता है तो true, अन्यथा false।

## Object::Equals(float const\&, float const\&) विधि

IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं है, जिसमें NaN भी शामिल है, फिर भी दो NaN को समान माना जाता है, इस प्रकार C#-शैली के फ्लोटिंग पॉइंट तुलना को नकल करता है।

```cpp
bool System::Object::Equals(float const &objA, float const &objB)
```

### आर्ग्युमेंट

| परामितर | प्रकार | विवरण |
| --- | --- | --- |
| objA | **float** const\& | बाएँ हाथ का फ्लोटिंग पॉइंट मान। |
| objB | **float** const\& | दाएँ हाथ का फ्लोटिंग पॉइंट मान। |

### रिटर्न मान

यदि **objA** और **objB** दोनों NaN हैं या बराबर हैं तो true, अन्यथा false।

## Object::Equals(double const\&, double const\&) विधि

IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं है, जिसमें NaN भी शामिल है, फिर भी दो NaN को समान माना जाता है, इस प्रकार C#-शैली के फ्लोटिंग पॉइंट तुलना को नकल करता है।

```cpp
bool System::Object::Equals(double const &objA, double const &objB)
```

### आर्ग्युमेंट

| परामितर | प्रकार | विवरण |
| --- | --- | --- |
| objA | **double** const\& | बाएँ हाथ का फ्लोटिंग पॉइंट मान। |
| objB | **double** const\& | दाएँ हाथ का फ्लोटिंग पॉइंट मान। |

### रिटर्न मान

यदि **objA** और **objB** दोनों NaN हैं या बराबर हैं तो true, अन्यथा false।

## संबंधित देखें

* Typedef [ptr](../ptr/)
* क्लास [Object](../)
* Struct [IsSmartPtr](../../issmartptr/)
* नेमस्पेस [System](../../)
* Library [Aspose.Slides](../../../)