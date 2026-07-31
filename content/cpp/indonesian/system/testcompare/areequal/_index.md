---
title: AreEqual()
second_title: Referensi API Aspose.Slides untuk C++
description: Membandingkan array yang bukan pointer.
type: docs
weight: 1
url: /id/system/testcompare/areequal/
---
## TestCompare::AreEqual(const SharedPtr\<Array\<T\>\>\&, const SharedPtr\<Array\<U\>\>\&) method

Membandingkan array yang bukan pointer.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<Array<T>> &arrA, const SharedPtr<Array<U>> &arrB)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T | Tipe elemen array pertama. |
| U | Tipe elemen array kedua. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| arrA | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | Array sisi kiri. |
| arrB | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<U\>\>\& | Array sisi kanan. |

### Return Value

true jika ukuran array dan data cocok, false sebaliknya.

## TestCompare::AreEqual(const SharedPtr\<Array\<SharedPtr\<T\>\>\>\&, const SharedPtr\<Array\<SharedPtr\<U\>\>\>\&) method

Membandingkan array pointer.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<Array<SharedPtr<T>>> &arrA, const SharedPtr<Array<SharedPtr<U>>> &arrB)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T | Tipe elemen yang ditunjuk pada array pertama. |
| U | Tipe elemen yang ditunjuk pada array kedua. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| arrA | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Array sisi kiri. |
| arrB | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Array sisi kanan. |

### Return Value

true jika ukuran array dan objek cocok, false sebaliknya.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<T\>\>\&, const SharedPtr\<SCG::List\<U\>\>\&) method

Membandingkan daftar yang bukan pointer.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<T>> &listA, const SharedPtr<SCG::List<U>> &listB)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T | Tipe elemen daftar pertama. |
| U | Tipe elemen daftar kedua. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<T\>\>\& | Daftar sisi kiri. |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<U\>\>\& | Daftar sisi kanan. |

### Return Value

true jika ukuran dan data cocok, false sebaliknya.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::List\<SharedPtr\<U\>\>\>\&) method

Membandingkan daftar pointer.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<SharedPtr<T>>> &listA, const SharedPtr<SCG::List<SharedPtr<U>>> &listB)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T | Tipe elemen yang ditunjuk pada daftar pertama. |
| U | Tipe elemen yang ditunjuk pada daftar kedua. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Daftar sisi kiri. |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Daftar sisi kanan. |

### Return Value

true jika ukuran daftar dan objek cocok, false sebaliknya.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<T\>\>\&, const System::ArrayPtr\<U\>\&) method

Membandingkan daftar dengan array dalam kasus elemen non-pointer.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<T>> &listA, const System::ArrayPtr<U> &arrB)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T | Tipe elemen daftar. |
| U | [Array](../../array/) tipe elemen. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<T\>\>\& | Daftar. |
| arrB | const [System::ArrayPtr](../../arrayptr/)\<U\>\& | [Array](../../array/). |

### Return Value

true jika ukuran dan data cocok, false sebaliknya.

## TestCompare::AreEqual(const System::ArrayPtr\<T\>\&, const SharedPtr\<SCG::List\<U\>\>\&) method

Membandingkan daftar dengan array dalam kasus elemen non-pointer.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::ArrayPtr<T> &arrA, const SharedPtr<SCG::List<U>> &listB)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T | [Array](../../array/) tipe elemen. |
| U | Tipe elemen daftar. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| arrA | const [System::ArrayPtr](../../arrayptr/)\<T\>\& | [Array](../../array/). |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<U\>\>\& | Daftar. |

### Return Value

true jika ukuran dan data cocok, false sebaliknya.

## TestCompare::AreEqual(const System::ArrayPtr\<SharedPtr\<T\>\>\&, const SharedPtr\<SCG::List\<SharedPtr\<U\>\>\>\&) method

Membandingkan daftar dengan array dalam kasus elemen pointer.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::ArrayPtr<SharedPtr<T>> &arr, const SharedPtr<SCG::List<SharedPtr<U>>> &list)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T | [Array](../../array/) tipe yang ditunjuk. |
| U | Tipe elemen yang ditunjuk pada daftar. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| arr | const [System::ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<T\>\>\& | [Array](../../array/). |
| list | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Daftar. |

### Return Value

true jika ukuran dan objek cocok, false sebaliknya.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<SharedPtr\<T\>\>\>\&, const System::ArrayPtr\<SharedPtr\<U\>\>\&) method

Membandingkan daftar dengan array dalam kasus elemen pointer.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<SharedPtr<T>>> &list, const System::ArrayPtr<SharedPtr<U>> &arr)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T | Tipe elemen yang ditunjuk pada daftar. |
| U | [Array](../../array/) tipe yang ditunjuk. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| list | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Daftar. |
| arr | const [System::ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<U\>\>\& | [Array](../../array/). |

### Return Value

true jika ukuran dan objek cocok, false sebaliknya.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K, U\>\>\&, const SharedPtr\<SCG::Dictionary\<K, U\>\>\&) method

Membandingkan kamus dengan tipe pemetaan non-pointer.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K, U>> &dictA, const SharedPtr<SCG::Dictionary<K, U>> &dictB)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| K | Tipe kunci. |
| U | Tipe nilai yang dipetakan. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, U\>\>\& | Kamus sisi kiri. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, U\>\>\& | Kamus sisi kanan. |

### Return Value

true jika ukuran kamus dan data cocok, false sebaliknya.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::Dictionary\<K, SharedPtr\<U\>\>\>\&) method

Membandingkan kamus dengan tipe pemetaan pointer.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::Dictionary<K, SharedPtr<U>>> &dictB)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| K | Tipe kunci. |
| U | Tipe nilai yang ditunjuk. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Kamus sisi kiri. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Kamus sisi kanan. |

### Return Value

true jika ukuran kamus dan data cocok, false sebaliknya.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K1, U1\>\>\&, const SharedPtr\<SCG::Dictionary\<K2, U2\>\>\&) method

Membandingkan kamus dengan tipe yang berbeda.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K1, U1>> &dictA, const SharedPtr<SCG::Dictionary<K2, U2>> &dictB)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| K1 | Tipe kunci kamus sisi kiri. |
| U1 | Tipe nilai kamus sisi kiri. |
| K2 | Tipe kunci kamus sisi kanan. |
| U2 | Tipe nilai kamus sisi kanan. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K1, U1\>\>\& | Kamus sisi kiri. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K2, U2\>\>\& | Kamus sisi kanan. |

### Return Value

Selalu mengembalikan false karena konversi tipe dilarang di sini.

## TestCompare::AreEqual(const SharedPtr\<SCG::HashSet\<T\>\>\&, const SharedPtr\<SCG::HashSet\<U\>\>\&) method

Membandingkan hashset yang bukan pointer.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::HashSet<T>> &containerPtrA, const SharedPtr<SCG::HashSet<U>> &containerPtrB)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T | Tipe elemen hashset pertama. |
| U | Tipe elemen hashset kedua. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| containerPtrA | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<T\>\>\& | Hashset sisi kiri. |
| containerPtrB | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<U\>\>\& | Hashset sisi kanan. |

### Return Value

true jika ukuran hashset dan data cocok, false sebaliknya.

## TestCompare::AreEqual(const SharedPtr\<SCG::HashSet\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::HashSet\<SharedPtr\<U\>\>\>\&) method

Membandingkan hashset pointer.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::HashSet<SharedPtr<T>>> &contA, const SharedPtr<SCG::HashSet<SharedPtr<U>>> &contB)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T | Tipe elemen yang ditunjuk pada hashset pertama. |
| U | Tipe elemen yang ditunjuk pada hashset kedua. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| contA | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Hashset sisi kiri. |
| contB | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Hashset sisi kanan. |

### Return Value

true jika ukuran hashset dan data cocok, false sebaliknya.

## TestCompare::AreEqual(const SCG::QueuePtr\<T\>\&, const SCG::QueuePtr\<U\>\&) method

Membandingkan antrean yang bukan pointer.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SCG::QueuePtr<T> &queueA, const SCG::QueuePtr<U> &queueB)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T | Tipe elemen antrean pertama. |
| U | Tipe elemen antrean kedua. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| queueA | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<T\>\& | Antrean sisi kiri. |
| queueB | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<U\>\& | Antrean sisi kanan. |

### Return Value

true jika ukuran antrean dan data cocok, false sebaliknya.

## TestCompare::AreEqual(const SCG::QueuePtr\<SharedPtr\<T\>\>\&, const SCG::QueuePtr\<SharedPtr\<U\>\>\&) method

Membandingkan antrean pointer.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SCG::QueuePtr<SharedPtr<T>> &queueA, const SCG::QueuePtr<SharedPtr<U>> &queueB)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T | Tipe elemen yang ditunjuk pada antrean pertama. |
| U | Tipe elemen yang ditunjuk pada antrean kedua. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| queueA | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<[SharedPtr](../../sharedptr/)\<T\>\>\& | Antrean sisi kiri. |
| queueB | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<[SharedPtr](../../sharedptr/)\<U\>\>\& | Antrean sisi kanan. |

### Return Value

true jika ukuran antrean dan data cocok, false sebaliknya.

## TestCompare::AreEqual(const SharedPtr\<SCG::Stack\<T\>\>\&, const SharedPtr\<SCG::Stack\<U\>\>\&) method

Membandingkan tumpukan yang bukan pointer.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Stack<T>> &stackA, const SharedPtr<SCG::Stack<U>> &stackB)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T | Tipe elemen tumpukan pertama. |
| U | Tipe elemen tumpukan kedua. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stackA | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<T\>\>\& | Tumpukan sisi kiri. |
| stackB | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<U\>\>\& | Tumpukan sisi kanan. |

### Return Value

true jika ukuran tumpukan dan data cocok, false sebaliknya.

## TestCompare::AreEqual(const SharedPtr\<SCG::Stack\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::Stack\<SharedPtr\<U\>\>\>\&) method

Membandingkan tumpukan pointer.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Stack<SharedPtr<T>>> &stackA, const SharedPtr<SCG::Stack<SharedPtr<U>>> &stackB)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T | Tipe elemen yang ditunjuk pada tumpukan pertama. |
| U | Tipe elemen yang ditunjuk pada tumpukan kedua. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stackA | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | Tumpukan sisi kiri. |
| stackB | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | Tumpukan sisi kanan. |

### Return Value

true jika ukuran tumpukan dan data cocok, false sebaliknya.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K, U\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K, U\>\>\&) method

Membandingkan kamus terurut dengan tipe pemetaan non-pointer.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K, U>> &dictA, const SharedPtr<SCG::SortedDictionary<K, U>> &dictB)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| K | Tipe kunci. |
| U | Tipe nilai yang dipetakan. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, U\>\>\& | Kamus sisi kiri. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, U\>\>\& | Kamus sisi kanan. |

### Return Value

true jika ukuran kamus dan data cocok, false sebaliknya.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K, SharedPtr\<U\>\>\>\&) method

Membandingkan kamus terurut dengan tipe pemetaan pointer.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::SortedDictionary<K, SharedPtr<U>>> &dictB)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| K | Tipe kunci. |
| U | Tipe nilai yang ditunjuk. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Kamus sisi kiri. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Kamus sisi kanan. |

### Return Value

true jika ukuran kamus dan data cocok, false sebaliknya.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K1, U1\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K2, U2\>\>\&) method

Membandingkan kamus terurut dengan tipe yang berbeda.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K1, U1>> &dictA, const SharedPtr<SCG::SortedDictionary<K2, U2>> &dictB)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| K1 | Tipe kunci kamus sisi kiri. |
| U1 | Tipe nilai kamus sisi kiri. |
| K2 | Tipe kunci kamus sisi kanan. |
| U2 | Tipe nilai kamus sisi kanan. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K1, U1\>\>\& | Kamus sisi kiri. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K2, U2\>\>\& | Kamus sisi kanan. |

### Return Value

Selalu mengembalikan false karena konversi tipe dilarang di sini.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K, U\>\>\&, const SharedPtr\<SCG::SortedList\<K, U\>\>\&) method

Membandingkan daftar terurut dengan tipe pemetaan non-pointer.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K, U>> &dictA, const SharedPtr<SCG::SortedList<K, U>> &dictB)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| K | Tipe kunci. |
| U | Tipe nilai yang dipetakan. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, U\>\>\& | Daftar sisi kiri. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, U\>\>\& | Daftar sisi kanan. |

### Return Value

true jika ukuran daftar dan data cocok, false sebaliknya.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::SortedList\<K, SharedPtr\<U\>\>\>\&) method

Membandingkan daftar terurut dengan tipe pemetaan pointer.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::SortedList<K, SharedPtr<U>>> &dictB)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| K | Tipe kunci. |
| U | Tipe nilai yang ditunjuk. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Daftar sisi kiri. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | Daftar sisi kanan. |

### Return Value

true jika ukuran daftar dan data cocok, false sebaliknya.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K1, U1\>\>\&, const SharedPtr\<SCG::SortedList\<K2, U2\>\>\&) method

Membandingkan daftar terurut dengan tipe yang berbeda.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K1, U1>> &dictA, const SharedPtr<SCG::SortedList<K2, U2>> &dictB)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| K1 | Tipe kunci daftar sisi kiri. |
| U1 | Tipe nilai daftar sisi kiri. |
| K2 | Tipe kunci daftar sisi kanan. |
| U2 | Tipe nilai daftar sisi kanan. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K1, U1\>\>\& | Daftar sisi kiri. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K2, U2\>\>\& | Daftar sisi kanan. |

### Return Value

Selalu mengembalikan false karena konversi tipe dilarang di sini.

## TestCompare::AreEqual(const System::Collections::Specialized::StringCollectionPtr\&, const System::Collections::Specialized::StringCollectionPtr\&) method

Membandingkan koleksi string.

```cpp
static bool System::TestCompare::AreEqual(const System::Collections::Specialized::StringCollectionPtr &arrA, const System::Collections::Specialized::StringCollectionPtr &arrB)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| arrA | const [System::Collections::Specialized::StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)\& | Koleksi sisi kiri. |
| arrB | const [System::Collections::Specialized::StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)\& | Koleksi sisi kanan. |

### Return Value

True jika ukuran dan data cocok, false sebaliknya.

## TestCompare::AreEqual(const System::SharedPtr\<SCG::IEnumerable\<T\>\>\&, const System::SharedPtr\<SCG::IEnumerable\<U\>\>\&) method

Membandingkan instance IEnumerable.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::SharedPtr<SCG::IEnumerable<T>> &et, const System::SharedPtr<SCG::IEnumerable<U>> &eu)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| et | const [System::SharedPtr](../../sharedptr/)\<[SCG::IEnumerable](../../../system.collections.generic/ienumerable/)\<T\>\>\& | Objek enumerable sisi kiri. |
| eu | const [System::SharedPtr](../../sharedptr/)\<[SCG::IEnumerable](../../../system.collections.generic/ienumerable/)\<U\>\>\& | Objek enumerable sisi kanan. |

### Return Value

True jika ukuran dan data cocok, false sebaliknya.

## See Also

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