---
title: SortedSet()
second_title: Aspose.Slides for C++ API संदर्भ
description: खाली सेट बनाता है।
type: docs
weight: 1
url: /hi/system.collections.generic/sortedset/sortedset/
---
## SortedSet::SortedSet() निर्माता

एक खाली सेट बनाता है।

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet()
```

## SortedSet::SortedSet(int) निर्माता

निर्दिष्ट क्षमता के साथ एक खाली सेट बनाता है।

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(int capacity)
```

## SortedSet::SortedSet(const SharedPtr\<IComparer\<T\>\>\&) निर्माता

निर्दिष्ट समानता तुलनाकर्ता का उपयोग करने वाला एक खाली सेट बनाता है।

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(const SharedPtr<IComparer<T>> &comparer)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) ऑब्जेक्ट को [SortedSet](../) के साथ संबद्ध करने के लिए। |

## SortedSet::SortedSet(const SharedPtr\<IEnumerable\<T\>\>\&) निर्माता

[SortedSet](../) को एन्यूमेरेबल मानों के आधार पर बनाता है।

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(const SharedPtr<IEnumerable<T>> &items)
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SortedSet](../)
* Class [IComparer](../../icomparer/)
* Class [IEnumerable](../../ienumerable/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)