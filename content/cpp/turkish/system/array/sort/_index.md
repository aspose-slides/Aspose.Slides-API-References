---
title: Sort()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen dizideki öğeleri varsayılan karşılaştırıcıyı kullanarak sıralar.
type: docs
weight: 742
url: /tr/system/array/sort/
---
## Array::Sort(const ArrayPtr\<Type\>\&) metod

Belirtilen dizideki öğeleri varsayılan karşılaştırıcıyı kullanarak sıralar.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Hedef dizi |

## Array::Sort(const ArrayPtr\<Type\>\&, int, int) metod

Belirtilen dizideki öğelerin bir aralığını varsayılan karşılaştırıcıyı kullanarak sıralar.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, int startIndex, int count)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Hedef dizi |
| startIndex | int | Sıralanacak öğeler aralığının başlangıcını belirten indeks |
| count | int | Sıralanacak öğeler aralığının boyutu |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) metod

Belirtilen dizideki öğeleri belirtilen karşılaştırıcıyı kullanarak sıralar.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Hedef dizi |
| comparator | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<T\>\>\& | Dizinin öğelerini karşılaştırmak için kullanılan IComparer<T> nesnesi |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<Y\>\>\&) metod

UYGULANMAMIŞTIR.

```cpp
template<typename Type,typename Y> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<Y>> &comparator)
```

## Array::Sort(const ArrayPtr\<Type\>\&, const System::Comparison\<T\>\&) metod

Belirtilen dizideki öğeleri belirtilen karşılaştırmayı kullanarak sıralar.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const System::Comparison<T> &comparison)
```

## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&) metod

Anahtarları içeren bir dizi ile ilgili öğeleri içeren diğer bir diziyi, anahtarları içeren dizinin değerlerine göre, elemanları operator< kullanılarak karşılaştırılarak sıralar.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TKey | **keys** dizisindeki öğelerin türü |
| TValue | **items** dizisindeki öğelerin türü |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) anahtar değerlerini içeren |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) anahtar değerlerine **keys** dizisinde eşlenen öğeleri içeren |

## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&, int, int) metod

Anahtarları içeren bir dizi ile ilgili öğeleri içeren diğer bir diziyi, anahtarları içeren dizinin değerlerine göre, elemanları varsayılan karşılaştırıcıyla karşılaştırılarak sıralar.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items, int index, int length)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TKey | **keys** dizisindeki öğelerin türü |
| TValue | **items** dizisindeki öğelerin türü |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) anahtar değerlerini içeren |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) anahtar değerlerine **keys** dizisinde eşlenen öğeleri içeren |
| index | int | Sıralanacak aralığın başlangıcını belirten indeks |
| length | int | Sıralanacak aralıktaki öğe sayısı |

## İlgili

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Method [Type](../../object/type/)
* Class [Array](../)
* Class [IComparer](../../../system.collections.generic/icomparer/)
* Class [Comparison](../../comparison/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)