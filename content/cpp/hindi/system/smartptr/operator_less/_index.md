---
title: operator<()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: SmartPtr वर्ग के लिए कम-तुलना सेमान्टिक प्रदान करता है।
type: docs
weight: 235
url: /hi/system/smartptr/operator_less/
---
## SmartPtr::operator<(Y *) const method

[SmartPtr](../) क्लास के लिए कम-तुलना सेमान्टिक प्रदान करता है।

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(Y *p) const
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Y | तुलना के लिये वर्तमान प्वाइंटर के प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| p | Y * | तुलना के लिये वर्तमान प्वाइंटर। |

### रिटर्न मान

यदि [SmartPtr](../) द्वारा संदर्भित ऑब्जेक्ट p से ‘कम’ है तो सत्य और अन्यथा असत्य।

## SmartPtr::operator<(SmartPtr\<Y\> const\&) const method

[SmartPtr](../) क्लास के लिए कम-तुलना सेमान्टिक प्रदान करता है।

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(SmartPtr<Y> const &x) const
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Y | तुलना के लिये वर्तमान प्वाइंटर के प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | [SmartPtr](../)\<Y\> const\& | तुलना के लिये वर्तमान प्वाइंटर। |

### रिटर्न मान

यदि [SmartPtr](../) द्वारा संदर्भित ऑब्जेक्ट x से ‘कम’ है तो सत्य और अन्यथा असत्य।

## संबंधित

* क्लास [SmartPtr](../)
* नामस्थान [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)