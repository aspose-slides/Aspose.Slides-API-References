---
title: NotNullAreNotEqual()
second_title: Aspose.Slides for C++ API Referansı
description: Eşit olmayan karşılaştırma, değer tipli sözlükleri karşılaştırır.
type: docs
weight: 118
url: /tr/system.testpredicates.details.sharedptrasserts/notnullarenotequal/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Dictionary\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::Dictionary\<K, V\>\>\&) function

Eşit olmayan karşılaştırma, değer tipli sözlükleri karşılaştırır.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Dictionary<K, V>> &lhs, const SharedPtr<System::Collections::Generic::Dictionary<K, V>> &rhs)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| K | Anahtar tipi. |
| V | Değer tipi. |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | Sol taraf ifadesi. |
| rhs_expr | const char * | Sağ taraf ifadesi. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, V\>\>\& | Sol taraf değeri. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, V\>\>\& | Sağ taraf değeri. |

### Dönüş Değeri

gtest biçimli doğrulama sonucu.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Dictionary\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::Dictionary\<K, SharedPtr\<V\>\>\>\&) function

Eşit olmayan karşılaştırma, paylaşımlı işaretçilerin sözlüklerini karşılaştırır.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Dictionary<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::Dictionary<K, SharedPtr<V>>> &rhs)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| K | Anahtar tipi. |
| V | Değer tipi. |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | Sol taraf ifadesi. |
| rhs_expr | const char * | Sağ taraf ifadesi. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | Sol taraf değeri. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | Sağ taraf değeri. |

### Dönüş Değeri

gtest biçimli doğrulama sonucu.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::HashSet\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::HashSet\<T2\>\>\&) function

Eşit olmayan karşılaştırma, hashset'leri karşılaştırır.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::HashSet<T1>> &lhs, const SharedPtr<System::Collections::Generic::HashSet<T2>> &rhs)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | Sol taraf kapsayıcı eleman tipi. |
| T2 | Sağ taraf kapsayıcı eleman tipi. |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | Sol taraf ifadesi. |
| rhs_expr | const char * | Sağ taraf ifadesi. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<T1\>\>\& | Sol taraf değeri. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<T2\>\>\& | Sağ taraf değeri. |

### Dönüş Değeri

gtest biçimli doğrulama sonucu.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Queue\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::Queue\<T2\>\>\&) function

Eşit olmayan karşılaştırma, kuyrukları karşılaştırır.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Queue<T1>> &lhs, const SharedPtr<System::Collections::Generic::Queue<T2>> &rhs)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | Sol taraf kapsayıcı eleman tipi. |
| T2 | Sağ taraf kapsayıcı eleman tipi. |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | Sol taraf ifadesi. |
| rhs_expr | const char * | Sağ taraf ifadesi. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Queue](../../system.collections.generic/queue/)\<T1\>\>\& | Sol taraf değeri. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Queue](../../system.collections.generic/queue/)\<T2\>\>\& | Sağ taraf değeri. |

### Dönüş Değeri

gtest biçimli doğrulama sonucu.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Stack\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::Stack\<T2\>\>\&) function

Eşit olmayan karşılaştırma, yığınları karşılaştırır.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Stack<T1>> &lhs, const SharedPtr<System::Collections::Generic::Stack<T2>> &rhs)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | Sol taraf kapsayıcı eleman tipi. |
| T2 | Sağ taraf kapsayıcı eleman tipi. |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | Sol taraf ifadesi. |
| rhs_expr | const char * | Sağ taraf ifadesi. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Stack](../../system.collections.generic/stack/)\<T1\>\>\& | Sol taraf değeri. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Stack](../../system.collections.generic/stack/)\<T2\>\>\& | Sağ taraf değeri. |

### Dönüş Değeri

gtest biçimli doğrulama sonucu.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, V\>\>\&) function

Eşit olmayan karşılaştırma, değer tipli sıralı sözlükleri karşılaştırır.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedDictionary<K, V>> &lhs, const SharedPtr<System::Collections::Generic::SortedDictionary<K, V>> &rhs)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| K | Anahtar tipi. |
| V | Değer tipi. |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | Sol taraf ifadesi. |
| rhs_expr | const char * | Sağ taraf ifadesi. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, V\>\>\& | Sol taraf değeri. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, V\>\>\& | Sağ taraf değeri. |

### Dönüş Değeri

gtest biçimli doğrulama sonucu.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, SharedPtr\<V\>\>\>\&) function

Eşit olmayan karşılaştırma, paylaşımlı işaretçilerin sıralı sözlüklerini karşılaştırır.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedDictionary<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::SortedDictionary<K, SharedPtr<V>>> &rhs)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| K | Anahtar tipi. |
| V | Değer tipi. |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | Sol taraf ifadesi. |
| rhs_expr | const char * | Sağ taraf ifadesi. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | Sol taraf değeri. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | Sağ taraf değeri. |

### Dönüş Değeri

gtest biçimli doğrulama sonucu.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedList\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::SortedList\<K, V\>\>\&) function

Eşit olmayan karşılaştırma, değer tipli sıralı listeleri karşılaştırır.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedList<K, V>> &lhs, const SharedPtr<System::Collections::Generic::SortedList<K, V>> &rhs)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| K | Anahtar tipi. |
| V | Değer tipi. |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | Sol taraf ifadesi. |
| rhs_expr | const char * | Sağ taraf ifadesi. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, V\>\>\& | Sol taraf değeri. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, V\>\>\& | Sağ taraf değeri. |

### Dönüş Değeri

gtest biçimli doğrulama sonucu.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedList\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::SortedList\<K, SharedPtr\<V\>\>\>\&) function

Eşit olmayan karşılaştırma, paylaşımlı işaretçilerin sıralı listelerini karşılaştırır.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedList<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::SortedList<K, SharedPtr<V>>> &rhs)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| K | Anahtar tipi. |
| V | Değer tipi. |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | Sol taraf ifadesi. |
| rhs_expr | const char * | Sağ taraf ifadesi. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | Sol taraf değeri. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | Sağ taraf değeri. |

### Dönüş Değeri

gtest biçimli doğrulama sonucu.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::BitArray\>\&, const SharedPtr\<System::Collections::BitArray\>\&) function

Eşit olmayan karşılaştırma, bit dizilerini karşılaştırır.

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::BitArray> &lhs, const SharedPtr<System::Collections::BitArray> &rhs)
```

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | Sol taraf ifadesi. |
| rhs_expr | const char * | Sağ taraf ifadesi. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::BitArray](../../system.collections/bitarray/)\>\& | Sol taraf değeri. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::BitArray](../../system.collections/bitarray/)\>\& | Sağ taraf değeri. |

### Dönüş Değeri

gtest biçimli doğrulama sonucu.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Specialized::StringCollection\>\&, const SharedPtr\<System::Collections::Specialized::StringCollection\>\&) function

Eşit olmayan karşılaştırma, dize koleksiyonlarını karşılaştırır.

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Specialized::StringCollection> &lhs, const SharedPtr<System::Collections::Specialized::StringCollection> &rhs)
```

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | Sol taraf ifadesi. |
| rhs_expr | const char * | Sağ taraf ifadesi. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Specialized::StringCollection](../../system.collections.specialized/stringcollection/)\>\& | Sol taraf değeri. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Specialized::StringCollection](../../system.collections.specialized/stringcollection/)\>\& | Sağ taraf değeri. |

### Dönüş Değeri

gtest biçimli doğrulama sonucu.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::ICollection\<T\>\>\&, const SharedPtr\<System::Collections::Generic::ICollection\<T\>\>\&) function

Eşit olmayan karşılaştırma, soyut koleksiyonları karşılaştırır.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::ICollection<T>> &lhs, const SharedPtr<System::Collections::Generic::ICollection<T>> &rhs)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Eleman tipi. |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | Sol taraf ifadesi. |
| rhs_expr | const char * | Sağ taraf ifadesi. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<T\>\>\& | Sol taraf değeri. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<T\>\>\& | Sağ taraf değeri. |

### Dönüş Değeri

gtest biçimli doğrulama sonucu.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<T1\>\&, const SharedPtr\<T2\>\&) function

Eşit olmayan karşılaştırma, bilinmeyen türleri karşılaştırır.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<T1> &lhs, const SharedPtr<T2> &rhs)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | Sol taraf nesne tipi. |
| T2 | Sağ taraf nesne tipi. |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | Sol taraf ifadesi. |
| rhs_expr | const char * | Sağ taraf ifadesi. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<T1\>\& | Sol taraf değeri. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<T2\>\& | Sağ taraf değeri. |

### Dönüş Değeri

gtest biçimli doğrulama sonucu.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Dictionary](../../system.collections.generic/dictionary/)
* Class [HashSet](../../system.collections.generic/hashset/)
* Class [Queue](../../system.collections.generic/queue/)
* Class [Stack](../../system.collections.generic/stack/)
* Class [SortedDictionary](../../system.collections.generic/sorteddictionary/)
* Class [SortedList](../../system.collections.generic/sortedlist/)
* Class [BitArray](../../system.collections/bitarray/)
* Class [StringCollection](../../system.collections.specialized/stringcollection/)
* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)