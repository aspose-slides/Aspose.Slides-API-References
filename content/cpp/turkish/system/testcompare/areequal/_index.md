---
title: AreEqual()
second_title: Aspose.Slides for C++ API Referansı
description: İşaretçi olmayan dizileri karşılaştırır.
type: docs
weight: 1
url: /tr/system/testcompare/areequal/
---
## TestCompare::AreEqual(const SharedPtr\<Array\<T\>\>\&, const SharedPtr\<Array\<U\>\>\&) yöntemi

İşaretçi olmayan dizileri karşılaştırır.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<Array<T>> &arrA, const SharedPtr<Array<U>> &arrB)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | İlk dizi öğesi türü. |
| U | İkinci dizi öğesi türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arrA | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | Sol taraf dizi. |
| arrB | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<U\>\>\& | Sağ taraf dizi. |

### Dönüş değeri

dizilerin boyutları ve verileri eşleşiyorsa true, aksi takdirde false.

## TestCompare::AreEqual(const SharedPtr\<Array\<SharedPtr\<T\>\>\>\&, const SharedPtr\<Array\<SharedPtr\<U\>\>\>\&) yöntemi

İşaretçi olan dizileri karşılaştırır.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<Array<SharedPtr<T>>> &arrA, const SharedPtr<Array<SharedPtr<U>>> &arrB)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | İlk dizi işaretçi öğesi türü. |
| U | İkinci dizi işaretçi öğesi türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arrA | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Sol taraf dizi. |
| arrB | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Sağ taraf dizi. |

### Dönüş değeri

dizilerin boyutları ve verileri eşleşiyorsa true, aksi takdirde false.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<T\>\>\&, const SharedPtr\<SCG::List\<U\>\>\&) yöntemi

İşaretçi olmayan listeleri karşılaştırır.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<T>> &listA, const SharedPtr<SCG::List<U>> &listB)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | İlk liste öğesi türü. |
| U | İkinci liste öğesi türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<T\>\>\& | Sol taraf liste. |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<U\>\>\& | Sağ taraf liste. |

### Dönüş değeri

listelerin boyutları ve verileri eşleşiyorsa true, aksi takdirde false.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::List\<SharedPtr\<U\>\>\>\&) yöntemi

İşaretçi olan listeleri karşılaştırır.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<SharedPtr<T>>> &listA, const SharedPtr<SCG::List<SharedPtr<U>>> &listB)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | İlk liste işaretçi öğesi türü. |
| U | İkinci liste işaretçi öğesi türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Sol taraf liste. |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Sağ taraf liste. |

### Dönüş değeri

listelerin boyutları ve nesneleri eşleşiyorsa true, aksi takdirde false.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<T\>\>\&, const System::ArrayPtr\<U\>\&) yöntemi

İşaretçi olmayan öğeler içeren listeleri dizilerle karşılaştırır.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<T>> &listA, const System::ArrayPtr<U> &arrB)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Liste öğesi türü. |
| U | [Array](../../array/) öğe türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<T\>\>\& | Liste. |
| arrB | const [System::ArrayPtr](../../arrayptr/)\<U\>\& | [Array](../../array/). |

### Dönüş değeri

boyutlar ve veriler eşleşiyorsa true, aksi takdirde false.

## TestCompare::AreEqual(const System::ArrayPtr\<T\>\&, const SharedPtr\<SCG::List\<U\>\>\&) yöntemi

İşaretçi olmayan öğeler içeren dizileri listelerle karşılaştırır.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::ArrayPtr<T> &arrA, const SharedPtr<SCG::List<U>> &listB)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [Array](../../array/) öğe türü. |
| U | Liste öğesi türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arrA | const [System::ArrayPtr](../../arrayptr/)\<T\>\& | [Array](../../array/). |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<U\>\>\& | Liste. |

### Dönüş değeri

boyutlar ve veriler eşleşiyorsa true, aksi takdirde false.

## TestCompare::AreEqual(const System::ArrayPtr\<SharedPtr\<T\>\>\&, const SharedPtr\<SCG::List\<SharedPtr\<U\>\>\>\&) yöntemi

İşaretçi olan öğeler içeren listeleri dizilerle karşılaştırır.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::ArrayPtr<SharedPtr<T>> &arr, const SharedPtr<SCG::List<SharedPtr<U>>> &list)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [Array](../../array/) işaretçi öğe türü. |
| U | Liste işaretçi öğe türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arr | const [System::ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<T\>\>\& | [Array](../../array/). |
| list | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Liste. |

### Dönüş değeri

boyutlar ve nesneler eşleşiyorsa true, aksi takdirde false.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<SharedPtr\<T\>\>\>\&, const System::ArrayPtr\<SharedPtr\<U\>\>\&) yöntemi

İşaretçi olan öğeler içeren listeleri dizilerle karşılaştırır.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<SharedPtr<T>>> &list, const System::ArrayPtr<SharedPtr<U>> &arr)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Liste işaretçi öğe türü. |
| U | [Array](../../array/) işaretçi öğe türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| list | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Liste. |
| arr | const [System::ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<U\>\>\& | [Array](../../array/). |

### Dönüş değeri

boyutlar ve nesneler eşleşiyorsa true, aksi takdirde false.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K, U\>\>\&, const SharedPtr\<SCG::Dictionary\<K, U\>\>\&) yöntemi

İşaretçi olmayan eşlenmiş tipli sözlükleri karşılaştırır.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K, U>> &dictA, const SharedPtr<SCG::Dictionary<K, U>> &dictB)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| K | Anahtar türü. |
| U | Eşlenmiş tür. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, U\>\>\& | Sol taraf sözlük. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, U\>\>\& | Sağ taraf sözlük. |

### Dönüş değeri

sözlüklerin boyutları ve verileri eşleşiyorsa true, aksi takdirde false.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::Dictionary\<K, SharedPtr\<U\>\>\>) yöntemi

İşaretçi olan eşlenmiş tipli sözlükleri karşılaştırır.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::Dictionary<K, SharedPtr<U>>> &dictB)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| K | Anahtar türü. |
| U | Eşlenmiş işaretçi öğe türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Sol taraf sözlük. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Sağ taraf sözlük. |

### Dönüş değeri

sözlüklerin boyutları ve verileri eşleşiyorsa true, aksi takdirde false.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K1, U1\>\>\&, const SharedPtr\<SCG::Dictionary\<K2, U2\>\>\&) yöntemi

Farklı tipte sözlükleri karşılaştırır.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K1, U1>> &dictA, const SharedPtr<SCG::Dictionary<K2, U2>> &dictB)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| K1 | Sol taraf sözlük anahtar türü. |
| U1 | Sol taraf sözlük eşlenmiş türü. |
| K2 | Sağ taraf sözlük anahtar türü. |
| U2 | Sağ taraf sözlük eşlenmiş türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K1, U1\>\>\& | Sol taraf sözlük. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K2, U2\>\>\& | Sağ taraf sözlük. |

### Dönüş değeri

tip dönüşümünün burada yasak olduğu için her zaman false döner.

## TestCompare::AreEqual(const SharedPtr\<SCG::HashSet\<T\>\>\&, const SharedPtr\<SCG::HashSet\<U\>\>\&) yöntemi

İşaretçi olmayan hashsetleri karşılaştırır.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::HashSet<T>> &containerPtrA, const SharedPtr<SCG::HashSet<U>> &containerPtrB)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | İlk hashset öğesi türü. |
| U | İkinci hashset öğesi türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| containerPtrA | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<T\>\>\& | Sol taraf hashset. |
| containerPtrB | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<U\>\>\& | Sağ taraf hashset. |

### Dönüş değeri

hashsetlerin boyutları ve verileri eşleşiyorsa true, aksi takdirde false.

## TestCompare::AreEqual(const SharedPtr\<SCG::HashSet\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::HashSet\<SharedPtr\<U\>\>\>) yöntemi

İşaretçi olan hashsetleri karşılaştırır.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::HashSet<SharedPtr<T>>> &contA, const SharedPtr<SCG::HashSet<SharedPtr<U>>> &contB)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | İlk hashset işaretçi öğesi türü. |
| U | İkinci hashset işaretçi öğesi türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| contA | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Sol taraf hashset. |
| contB | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Sağ taraf hashset. |

### Dönüş değeri

hashsetlerin boyutları ve verileri eşleşiyorsa true, aksi takdirde false.

## TestCompare::AreEqual(const SCG::QueuePtr\<T\>\&, const SCG::QueuePtr\<U\>\&) yöntemi

İşaretçi olmayan kuyrukları karşılaştırır.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SCG::QueuePtr<T> &queueA, const SCG::QueuePtr<U> &queueB)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | İlk kuyruk öğesi türü. |
| U | İkinci kuyruk öğesi türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| queueA | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<T\>\& | Sol taraf kuyruk. |
| queueB | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<U\>\& | Sağ taraf kuyruk. |

### Dönüş değeri

kuyrukların boyutları ve verileri eşleşiyorsa true, aksi takdirde false.

## TestCompare::AreEqual(const SCG::QueuePtr\<SharedPtr\<T\>\>\&, const SCG::QueuePtr\<SharedPtr\<U\>\>\&) yöntemi

İşaretçi olan kuyrukları karşılaştırır.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SCG::QueuePtr<SharedPtr<T>> &queueA, const SCG::QueuePtr<SharedPtr<U>> &queueB)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | İlk kuyruk işaretçi öğesi türü. |
| U | İkinci kuyruk işaretçi öğesi türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| queueA | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<[SharedPtr](../../sharedptr/)\<T\>\>\& | Sol taraf kuyruk. |
| queueB | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<[SharedPtr](../../sharedptr/)\<U\>\>\& | Sağ taraf kuyruk. |

### Dönüş değeri

kuyrukların boyutları ve verileri eşleşiyorsa true, aksi takdirde false.

## TestCompare::AreEqual(const SharedPtr\<SCG::Stack\<T\>\>\&, const SharedPtr\<SCG::Stack\<U\>\>\&) yöntemi

İşaretçi olmayan yığınları karşılaştırır.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Stack<T>> &stackA, const SharedPtr<SCG::Stack<U>> &stackB)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | İlk yığın öğesi türü. |
| U | İkinci yığın öğesi türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stackA | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<T\>\>\& | Sol taraf yığın. |
| stackB | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<U\>\>\& | Sağ taraf yığın. |

### Dönüş değeri

yığınların boyutları ve verileri eşleşiyorsa true, aksi takdirde false.

## TestCompare::AreEqual(const SharedPtr\<SCG::Stack\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::Stack\<SharedPtr\<U\>\>\>) yöntemi

İşaretçi olan yığınları karşılaştırır.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Stack<SharedPtr<T>>> &stackA, const SharedPtr<SCG::Stack<SharedPtr<U>>> &stackB)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | İlk yığın işaretçi öğesi türü. |
| U | İkinci yığın işaretçi öğesi türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stackA | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Sol taraf yığın. |
| stackB | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Sağ taraf yığın. |

### Dönüş değeri

yığınların boyutları ve verileri eşleşiyorsa true, aksi takdirde false.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K, U\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K, U\>\>\&) yöntemi

İşaretçi olmayan eşlenmiş tipli sıralı sözlükleri karşılaştırır.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K, U>> &dictA, const SharedPtr<SCG::SortedDictionary<K, U>> &dictB)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| K | Anahtar türü. |
| U | Eşlenmiş tür. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, U\>\>\& | Sol taraf sözlük. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, U\>\>\& | Sağ taraf sözlük. |

### Dönüş değeri

sözlüklerin boyutları ve verileri eşleşiyorsa true, aksi takdirde false.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K, SharedPtr\<U\>\>\>) yöntemi

İşaretçi olan eşlenmiş tipli sıralı sözlükleri karşılaştırır.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::SortedDictionary<K, SharedPtr<U>>> &dictB)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| K | Anahtar türü. |
| U | Eşlenmiş işaretçi öğesi türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Sol taraf sözlük. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Sağ taraf sözlük. |

### Dönüş değeri

sözlüklerin boyutları ve verileri eşleşiyorsa true, aksi takdirde false.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K1, U1\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K2, U2\>\>\&) yöntemi

Farklı tipte sıralı sözlükleri karşılaştırır.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K1, U1>> &dictA, const SharedPtr<SCG::SortedDictionary<K2, U2>> &dictB)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| K1 | Sol taraf sözlük anahtar türü. |
| U1 | Sol taraf sözlük eşlenmiş türü. |
| K2 | Sağ taraf sözlük anahtar türü. |
| U2 | Sağ taraf sözlük eşlenmiş türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K1, U1\>\>\& | Sol taraf sözlük. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K2, U2\>\>\& | Sağ taraf sözlük. |

### Dönüş değeri

tip dönüşümünün burada yasak olduğu için her zaman false döner.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K, U\>\>\&, const SharedPtr\<SCG::SortedList\<K, U\>\>\&) yöntemi

İşaretçi olmayan eşlenmiş tipli sıralı listeleri karşılaştırır.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K, U>> &dictA, const SharedPtr<SCG::SortedList<K, U>> &dictB)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| K | Anahtar türü. |
| U | Eşlenmiş tür. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, U\>\>\& | Sol taraf liste. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, U\>\>\& | Sağ taraf liste. |

### Dönüş değeri

listelerin boyutları ve verileri eşleşiyorsa true, aksi takdirde false.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::SortedList\<K, SharedPtr\<U\>\>\>) yöntemi

İşaretçi olan eşlenmiş tipli sıralı listeleri karşılaştırır.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::SortedList<K, SharedPtr<U>>> &dictB)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| K | Anahtar türü. |
| U | Eşlenmiş işaretçi öğesi türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Sol taraf liste. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Sağ taraf liste. |

### Dönüş değeri

listelerin boyutları ve verileri eşleşiyorsa true, aksi takdirde false.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K1, U1\>\>\&, const SharedPtr\<SCG::SortedList\<K2, U2\>\>\&) yöntemi

Farklı tipte sıralı listeleri karşılaştırır.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K1, U1>> &dictA, const SharedPtr<SCG::SortedList<K2, U2>> &dictB)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| K1 | Sol taraf liste anahtar türü. |
| U1 | Sol taraf liste eşlenmiş türü. |
| K2 | Sağ taraf liste anahtar türü. |
| U2 | Sağ taraf liste eşlenmiş türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K1, U1\>\>\& | Sol taraf liste. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K2, U2\>\>\& | Sağ taraf liste. |

### Dönüş değeri

tip dönüşümünün burada yasak olduğu için her zaman false döner.

## TestCompare::AreEqual(const System::Collections::Specialized::StringCollectionPtr\&, const System::Collections::Specialized::StringCollectionPtr\&) yöntemi

Dize koleksiyonlarını karşılaştırır.

```cpp
static bool System::TestCompare::AreEqual(const System::Collections::Specialized::StringCollectionPtr &arrA, const System::Collections::Specialized::StringCollectionPtr &arrB)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arrA | const [System::Collections::Specialized::StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)\& | Sol taraf koleksiyon. |
| arrB | const [System::Collections::Specialized::StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)\& | Sağ taraf koleksiyon. |

### Dönüş değeri

boyutlar ve veriler eşleşiyorsa True, aksi takdirde false.

## TestCompare::AreEqual(const System::SharedPtr\<SCG::IEnumerable\<T\>\>\&, const System::SharedPtr\<SCG::IEnumerable\<U\>\>\&) yöntemi

IEnumerable örneklerini karşılaştırır.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::SharedPtr<SCG::IEnumerable<T>> &et, const System::SharedPtr<SCG::IEnumerable<U>> &eu)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| et | const [System::SharedPtr](../../sharedptr/)\<[SCG::IEnumerable](../../../system.collections.generic/ienumerable/)\<T\>\>\& | Sol taraf enumerable nesnesi. |
| eu | const [System::SharedPtr](../../sharedptr/)\<[SCG::IEnumerable](../../../system.collections.generic/ienumerable/)\<U\>\>\& | Sağ taraf enumerable nesnesi. |

### Dönüş değeri

boyutlar ve veriler eşleşiyorsa True, aksi takdirde false.

## Ayrıca bakınız

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../../array/)
* Class [List](../../../system.collections.generic/list/)
* Class [Dictionary](../../../system.collections.generic/dictionary/)
* Class [HashSet](../../../system.collections.generic/hashset/)
* Class [QueuePtr](../../../system.collections.generic/queueptr/)
* Class [Stack](../../../system.collections.generic/stack/)
* Class [SortedDictionary](../../../system.collections.generic/sorteddictionary/)
* Class [SortedList](../../../system.collections.generic/sortedlist/)
* Class [StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Struct [TestCompare](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)