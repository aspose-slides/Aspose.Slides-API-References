---
title: DynamicWeakPtr()
second_title: Aspose.Slides for C++ API संदर्भ
description: null स्मार्ट पॉइंटर बनाता है।
type: docs
weight: 1
url: /hi/system/dynamicweakptr/dynamicweakptr/
---
## DynamicWeakPtr::DynamicWeakPtr(std::nullptr_t) निर्माता

null स्मार्ट पॉइंटर बनाता है।

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(std::nullptr_t=nullptr)
```

## DynamicWeakPtr::DynamicWeakPtr(Pointee_ *) निर्माता

दिए गए वस्तु की ओर इशारा करने वाला स्मार्ट पॉइंटर बनाता है।

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(Pointee_ *object)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | पॉइंटी। |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr_\&) निर्माता

स्मार्ट पॉइंटर को कॉपी-निर्माता करता है।

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr_ &ptr)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)\& | पॉइंटी जानकारी को कॉपी करने के लिए स्मार्ट पॉइंटर। |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr\<Q\>\&) निर्माता

स्मार्ट पॉइंटर को कॉपी-निर्माता करता है।

```cpp
template<class Q> System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr<Q> &x)
```

### टेम्पलेट पैरामीटर्स

| पैरामीटर | विवरण |
| --- | --- |
| Q | स्रोत पॉइंटर पॉइंटी प्रकार। |

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | पॉइंटी जानकारी को कॉपी करने के लिए स्मार्ट पॉइंटर। |

## DynamicWeakPtr::DynamicWeakPtr(const DynamicWeakPtr_\&) निर्माता

स्मार्ट पॉइंटर को कॉपी-निर्माता करता है।

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const DynamicWeakPtr_ &ptr)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| ptr | const [DynamicWeakPtr_](../dynamicweakptr_/)\& | पॉइंटी जानकारी को कॉपी करने के लिए स्मार्ट पॉइंटर। |

## DynamicWeakPtr::DynamicWeakPtr(SmartPtr_\&&) निर्माता

स्मार्ट पॉइंटर को स्थानांतरण-निर्माता करता है।

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(SmartPtr_ &&x)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | पॉइंटी जानकारी को स्थानांतरित करने के लिए स्मार्ट पॉइंटर। कॉल के बाद उपयोग में नहीं रहेगा। |

## संबंधित देखें

* टाइपडिफ [Pointee_](../../smartptr/pointee_/)
* टाइपडिफ [SmartPtr_](../smartptr_/)
* टाइपडिफ [DynamicWeakPtr_](../dynamicweakptr_/)
* क्लास [DynamicWeakPtr](../)
* क्लास [SmartPtr](../../smartptr/)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)