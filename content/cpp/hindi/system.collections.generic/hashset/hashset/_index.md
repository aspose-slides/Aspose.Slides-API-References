---
title: HashSet()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: RTTI जानकारी।
type: docs
weight: 1
url: /hi/system.collections.generic/hashset/hashset/
---
## HashSet::HashSet() constructor

RTTI जानकारी।

```cpp
System::Collections::Generic::HashSet<T>::HashSet()
```

## टिप्पणी

एक खाली सेट बनाता है।

## HashSet::HashSet(int) constructor

निर्दिष्ट क्षमता के साथ एक खाली सेट बनाता है।

```cpp
System::Collections::Generic::HashSet<T>::HashSet(int capacity)
```

## HashSet::HashSet(const SharedPtr\<IEqualityComparer\<T\>\>\&) constructor

निर्दिष्ट समानता तुलना करने वाले का उपयोग करने वाला एक खाली सेट बनाता है।

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEqualityComparer<T>> &comparer)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<T\>\>\& | [Comparer](../../comparer/) ऑब्जेक्ट जो hashset के साथ संबद्ध करने के लिए है। |

## HashSet::HashSet(const SharedPtr\<IEnumerable\<T\>\>\&) constructor

इटेरेबल मानों के आधार पर हैशसेट बनाता है।

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEnumerable<T>> &items)
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HashSet](../)
* Class [IEqualityComparer](../../iequalitycomparer/)
* Class [IEnumerable](../../ienumerable/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)