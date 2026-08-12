---
title: operator=()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: SmartPtr ऑब्जेक्ट को स्थानांतरित-असाइन करता है। x अब उपयोग योग्य नहीं रहता।
type: docs
weight: 27
url: /hi/system/smartptr/operator_equal/
---
## SmartPtr::operator=(SmartPtr_&&) विधि

स्थानांतरित असाइन करता है [SmartPtr](../) ऑब्जेक्ट। x अब उपयोग योग्य नहीं रहता।

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(SmartPtr_ &&x) noexcept
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | move-assign करने के लिए पॉइंटर। |

### रिटर्न मान

इस ऑब्जेक्ट का संदर्भ।

## SmartPtr::operator=(const SmartPtr_&) विधि

कॉपी-असाइन करता है [SmartPtr](../) ऑब्जेक्ट।

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr_ &x)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)\& | copy-assign करने के लिए पॉइंटर। |

### रिटर्न मान

इस ऑब्जेक्ट का संदर्भ।

## SmartPtr::operator=(const SmartPtr\<Q\>\&) विधि

कॉपी-असाइन करता है [SmartPtr](../) ऑब्जेक्ट। आवश्यक टाइप रूपांतरण करता है।

```cpp
template<typename Q> SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr<Q> &x)
```

### टेम्प्लेट पैरामीटर्स

| पैरामीटर | विवरण |
| --- | --- |
| Q | x द्वारा इंगित ऑब्जेक्ट का प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| x | const [SmartPtr](../)\<Q\>\& | copy-assign करने के लिए पॉइंटर। |

### रिटर्न मान

इस ऑब्जेक्ट का संदर्भ।

## SmartPtr::operator=(Pointee_ *) विधि

रॉ पॉइंटर को [SmartPtr](../) ऑब्जेक्ट को असाइन करता है।

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(Pointee_ *p)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| p | [Pointee_](../pointee_/) * | असाइन करने के लिए पॉइंटर वैल्यू। |

### रिटर्न मान

इस ऑब्जेक्ट का संदर्भ।

## SmartPtr::operator=(std::nullptr_t) विधि

पॉइंटर वैल्यू को nullptr सेट करता है।

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(std::nullptr_t)
```

### रिटर्न मान

इस ऑब्जेक्ट का संदर्भ।

## देखें

* टाइपडिफ [SmartPtr_](../smartptr_/)
* टाइपडिफ [Pointee_](../pointee_/)
* क्लास [SmartPtr](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)