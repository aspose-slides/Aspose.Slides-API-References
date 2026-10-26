---
title: SortedList()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: खाली सूची बनाता है।
type: docs
weight: 1
url: /hi/system.collections.generic/sortedlist/sortedlist/
---
## SortedList::SortedList() कन्स्ट्रक्टर

खाली सूची बनाता है।

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList()
```

## SortedList::SortedList(const SharedPtr\<IComparer\<TKey\>\>\&) कन्स्ट्रक्टर

खाली सूची बनाता है।

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const SharedPtr<IComparer<TKey>> &comparer)
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) उपयोग करने के लिए। |

## SortedList::SortedList(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) कन्स्ट्रक्टर

कॉपी कन्स्ट्रक्टर।

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const SharedPtr<IDictionary<TKey, TValue>> &src)
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | [Dictionary](../../dictionary/) डेटा कॉपी करने के लिए। |

## SortedList::SortedList(const map_t\&) कन्स्ट्रक्टर

कॉपी कन्स्ट्रक्टर।

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const map_t &map)
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| map | const [map_t](../map_t/)\& | Map से डेटा कॉपी करने के लिए। |

## SortedList::SortedList(int) कन्स्ट्रक्टर

खाली सूची बनाता है।

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(int capacity)
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| capacity | int | आरक्षित करने के लिए तत्वों की संख्या। |

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [map_t](../map_t/)
* Class [SortedList](../)
* Class [IComparer](../../icomparer/)
* Class [IDictionary](../../idictionary/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)