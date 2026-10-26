---
title: Sort()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट सरणी में तत्वों को डिफ़ॉल्ट comparer की मदद से क्रमबद्ध करता है।
type: docs
weight: 742
url: /hi/system/array/sort/
---
## Array::Sort(const ArrayPtr\<Type\>\&) विधि


निर्दिष्ट सरणी में तत्वों को डिफ़ॉल्ट comparer की मदद से क्रमबद्ध करता है।

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Targed array |

## Array::Sort(const ArrayPtr\<Type\>\&, int, int) विधि


निर्दिष्ट सरणी में तत्वों की एक सीमा को डिफ़ॉल्ट comparer की मदद से क्रमबद्ध करता है।

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, int startIndex, int count)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Targed array |
| startIndex | int | The index designating the beginning of the range of elements to sort |
| count | int | The size of the range of elements to sort |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) विधि


निर्दिष्ट सरणी में तत्वों को निर्दिष्ट comparer की मदद से क्रमबद्ध करता है।

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Targed array |
| comparator | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<T\>\>\& | IComparer<T> object used to compare elements of the array |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<Y\>\>\&) विधि


अभी लागू नहीं किया गया है।

```cpp
template<typename Type,typename Y> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<Y>> &comparator)
```


## Array::Sort(const ArrayPtr\<Type\>\&, const System::Comparison\<T\>\&) विधि


निर्दिष्ट सरणी में तत्वों को निर्दिष्ट comparison की मदद से क्रमबद्ध करता है।

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const System::Comparison<T> &comparison)
```

## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&) विधि


keys और items दो सरणियों को, keys सरणी के मानों के आधार पर, operator< द्वारा तुलना करके क्रमबद्ध करता है।

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items)
```


### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TKey | The type of the elements in the **keys** array |
| TValue | the type of the elements in the **items** array |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) जिसमें कुंजी मान होते हैं |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) जिसमें आइटम हैं जो **keys** array में कुंजी मानों से मैप किए गए हैं |

## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&, int, int) विधि


keys और items दो सरणियों को, keys सरणी के मानों के आधार पर, डिफ़ॉल्ट comparer द्वारा तुलना करके क्रमबद्ध करता है।

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items, int index, int length)
```


### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TKey | The type of the elements in the **keys** array |
| TValue | the type of the elements in the **items** array |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) जिसमें कुंजी मान होते हैं |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) जिसमें आइटम हैं जो **keys** array में कुंजी मानों से मैप किए गए हैं |
| index | int | The index designating the beginning of the range to sort |
| length | int | The number of elements in the range to sort |

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Method [Type](../../object/type/)
* Class [Array](../)
* Class [IComparer](../../../system.collections.generic/icomparer/)
* Class [Comparison](../../comparison/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)