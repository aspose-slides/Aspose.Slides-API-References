---
title: Cast()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: पॉइंटर को उसके स्वयं के प्रकार में कास्ट करता है।
type: docs
weight: 287
url: /hi/system/smartptr/cast/
---
## SmartPtr::Cast() const विधि

Casts pointer to its type itself.

```cpp
template<class Y,typename Check> std::enable_if_t<std::is_same<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Y | संकेतित वस्तु का लक्ष्य प्रकार। |
| Check | यदि कोई कास्ट उपलब्ध नहीं है तो अपवाद फेंकने के लिए फ़्लैग्स। |

### वापसी मान

सदैव साझा मोड में रहने वाला परिवर्तित प्रकार का पॉइंटर।

## SmartPtr::Cast() const विधि

Casts pointer to base type using static_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<!std::is_same<Y, T>::value &&std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Y | संकेतित वस्तु का लक्ष्य प्रकार। |
| Check | यदि कोई कास्ट उपलब्ध नहीं है तो अपवाद फेंकने के लिए फ़्लैग्स। |

### वापसी मान

सदैव साझा मोड में रहने वाला परिवर्तित प्रकार का पॉइंटर।

## SmartPtr::Cast() const विधि

Casts pointer to derived type dynamic_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Y | संकेतित वस्तु का लक्ष्य प्रकार। |
| Check | यदि कोई कास्ट उपलब्ध नहीं है तो अपवाद फेंकने के लिए फ़्लैग्स। |

### वापसी मान

सदैव साझा मोड में रहने वाला परिवर्तित प्रकार का पॉइंटर। Throws InvalidCastException if no conversion available.

## SmartPtr::Cast() const विधि

Casts pointer to derived type dynamic_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<!Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Y | संकेतित वस्तु का लक्ष्य प्रकार। |
| Check | यदि कोई कास्ट उपलब्ध नहीं है तो अपवाद फेंकने के लिए फ़्लैग्स। |

### वापसी मान

सदैव साझा मोड में रहने वाला परिवर्तित प्रकार का पॉइंटर। Returns nullptr if no conversion available.

## देखें

* क्लास [SmartPtr](../)
* नामस्थान [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)