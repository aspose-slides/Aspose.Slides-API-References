---
title: operator=()
second_title: Aspose.Slides for C++ API संदर्भ
description: स्मार्ट पॉइंटर को मूव-ऐसाइन करता है।
type: docs
weight: 27
url: /hi/system/dynamicweakptr/operator_equal/
---
## DynamicWeakPtr::operator=(SmartPtr_&&) विधि

स्मार्ट पॉइंटर को मूव-ऐसाइन करता है।

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(SmartPtr_ &&x)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | मूव-ऐसाइन मान से पॉइंटर। |

### रिटर्न मान

स्वयं संदर्भ।

## DynamicWeakPtr::operator=(const SmartPtr_&) विधि

स्मार्ट पॉइंटर को कॉपी-ऐसाइन करता है।

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr_ &x)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)\& | कॉपी-ऐसाइन मान से पॉइंटर। |

### रिटर्न मान

स्वयं संदर्भ।

## DynamicWeakPtr::operator=(const SmartPtr\<Q\>\&) विधि

स्मार्ट पॉइंटर को कॉपी-ऐसाइन करता है।

```cpp
template<typename Q> DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr<Q> &x)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Q | स्रोत पॉइंटी टाइप। |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | कॉपी-ऐसाइन मान से पॉइंटर। |

### रिटर्न मान

स्वयं संदर्भ।

## DynamicWeakPtr::operator=(typename SmartPtr_::Pointee_ *) विधि

स्मार्ट पॉइंटर को असाइन करता है।

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(typename SmartPtr_::Pointee_ *p)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| p | typename [SmartPtr_::Pointee_](../../smartptr/pointee_/) * | पॉइंटर मान। |

### रिटर्न मान

स्वयं संदर्भ।

## DynamicWeakPtr::operator=(std::nullptr_t) विधि

स्मार्ट पॉइंटर को null सेट करता है।

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(std::nullptr_t)
```

### रिटर्न मान

स्वयं संदर्भ।

## संबंधित देखें

* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Typedef [SmartPtr_](../smartptr_/)
* Typedef [Pointee_](../../smartptr/pointee_/)
* Class [DynamicWeakPtr](../)
* Class [SmartPtr](../../smartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)