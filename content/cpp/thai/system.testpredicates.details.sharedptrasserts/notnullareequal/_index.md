---
title: NotNullAreEqual()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เปรียบเทียบเท่ากันของดิกชันนารีประเภทค่า.
type: docs
weight: 53
url: /th/system.testpredicates.details.sharedptrasserts/notnullareequal/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Dictionary\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::Dictionary\<K, V\>\&) function

เปรียบเทียบเท่ากันของดิกชันนารีประเภทค่า

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Dictionary<K, V>> &lhs, const SharedPtr<System::Collections::Generic::Dictionary<K, V>> &rhs)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| K | ประเภทคีย์ |
| V | ประเภทค่า |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ฝั่งซ้าย |
| rhs_expr | const char * | นิพจน์ฝั่งขวา |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, V\>\>\& | ค่าฝั่งซ้าย |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, V\>\>\& | ค่าฝั่งขวา |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบแบบ gtest

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Dictionary\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::Dictionary\<K, SharedPtr\<V\>\>\&) function

เปรียบเทียบเท่ากันของดิกชันนารีของ shared pointer

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Dictionary<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::Dictionary<K, SharedPtr<V>>> &rhs)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| K | ประเภทคีย์ |
| V | ประเภทค่า |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ฝั่งซ้าย |
| rhs_expr | const char * | นิพจน์ฝั่งขวา |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | ค่าฝั่งซ้าย |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | ค่าฝั่งขวา |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบแบบ gtest

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::HashSet\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::HashSet\<T2\>\>) function

เปรียบเทียบเท่ากันของ hashset

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::HashSet<T1>> &lhs, const SharedPtr<System::Collections::Generic::HashSet<T2>> &rhs)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ประเภทขององค์ประกอบคอนเทนเนอร์ฝั่งซ้าย |
| T2 | ประเภทขององค์ประกอบคอนเทนเนอร์ฝั่งขวา |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ฝั่งซ้าย |
| rhs_expr | const char * | นิพจน์ฝั่งขวา |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<T1\>\>\& | ค่าฝั่งซ้าย |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<T2\>\>\& | ค่าฝั่งขวา |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบแบบ gtest

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Queue\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::Queue\<T2\>\>) function

เปรียบเทียบเท่ากันของคิว

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Queue<T1>> &lhs, const SharedPtr<System::Collections::Generic::Queue<T2>> &rhs)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ประเภทขององค์ประกอบคอนเทนเนอร์ฝั่งซ้าย |
| T2 | ประเภทขององค์ประกอบคอนเทนเนอร์ฝั่งขวา |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ฝั่งซ้าย |
| rhs_expr | const char * | นิพจน์ฝั่งขวา |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Queue](../../system.collections.generic/queue/)\<T1\>\>\& | ค่าฝั่งซ้าย |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Queue](../../system.collections.generic/queue/)\<T2\>\>\& | ค่าฝั่งขวา |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบแบบ gtest

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Stack\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::Stack\<T2\>\>) function

เปรียบเทียบเท่ากันของสแตก

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Stack<T1>> &lhs, const SharedPtr<System::Collections::Generic::Stack<T2>> &rhs)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ประเภทขององค์ประกอบคอนเทนเนอร์ฝั่งซ้าย |
| T2 | ประเภทขององค์ประกอบคอนเทนเนอร์ฝั่งขวา |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ฝั่งซ้าย |
| rhs_expr | const char * | นิพจน์ฝั่งขวา |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Stack](../../system.collections.generic/stack/)\<T1\>\>\& | ค่าฝั่งซ้าย |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Stack](../../system.collections.generic/stack/)\<T2\>\>\& | ค่าฝั่งขวา |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบแบบ gtest

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, V\>\>) function

เปรียบเทียบเท่ากันของดิกชันนารีเรียงลำดับประเภทค่า

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedDictionary<K, V>> &lhs, const SharedPtr<System::Collections::Generic::SortedDictionary<K, V>> &rhs)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| K | ประเภทคีย์ |
| V | ประเภทค่า |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ฝั่งซ้าย |
| rhs_expr | const char * | นิพจน์ฝั่งขวา |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, V\>\>\& | ค่าฝั่งซ้าย |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, V\>\>\& | ค่าฝั่งขวา |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบแบบ gtest

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, SharedPtr\<V\>\>\>) function

เปรียบเทียบเท่ากันของดิกชันนารีเรียงลำดับของ shared pointer

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedDictionary<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::SortedDictionary<K, SharedPtr<V>>> &rhs)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| K | ประเภทคีย์ |
| V | ประเภทค่า |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ฝั่งซ้าย |
| rhs_expr | const char * | นิพจน์ฝั่งขวา |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | ค่าฝั่งซ้าย |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | ค่าฝั่งขวา |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบแบบ gtest

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedList\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::SortedList\<K, V\>\>) function

เปรียบเทียบเท่ากันของรายการเรียงลำดับประเภทค่า

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedList<K, V>> &lhs, const SharedPtr<System::Collections::Generic::SortedList<K, V>> &rhs)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| K | ประเภทคีย์ |
| V | ประเภทค่า |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ฝั่งซ้าย |
| rhs_expr | const char * | นิพจน์ฝั่งขวา |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, V\>\>\& | ค่าฝั่งซ้าย |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, V\>\>\& | ค่าฝั่งขวา |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบแบบ gtest

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedList\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::SortedList\<K, SharedPtr\<V\>\>\>) function

เปรียบเทียบเท่ากันของรายการเรียงลำดับของ shared pointer

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedList<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::SortedList<K, SharedPtr<V>>> &rhs)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| K | ประเภทคีย์ |
| V | ประเภทค่า |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ฝั่งซ้าย |
| rhs_expr | const char * | นิพจน์ฝั่งขวา |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | ค่าฝั่งซ้าย |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | ค่าฝั่งขวา |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบแบบ gtest

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::BitArray\>\&, const SharedPtr\<System::Collections::BitArray\>\&) function

เปรียบเทียบเท่ากันของอาเรย์บิต

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::BitArray> &lhs, const SharedPtr<System::Collections::BitArray> &rhs)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ฝั่งซ้าย |
| rhs_expr | const char * | นิพจน์ฝั่งขวา |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::BitArray](../../system.collections/bitarray/)\>\& | ค่าฝั่งซ้าย |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::BitArray](../../system.collections/bitarray/)\>\& | ค่าฝั่งขวา |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบแบบ gtest

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Specialized::StringCollection\>\&, const SharedPtr\<System::Collections::Specialized::StringCollection\>\&) function

เปรียบเทียบเท่ากันของคอลเลกชันสตริง

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Specialized::StringCollection> &lhs, const SharedPtr<System::Collections::Specialized::StringCollection> &rhs)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ฝั่งซ้าย |
| rhs_expr | const char * | นิพจน์ฝั่งขวา |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Specialized::StringCollection](../../system.collections.specialized/stringcollection/)\>\& | ค่าฝั่งซ้าย |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Specialized::StringCollection](../../system.collections.specialized/stringcollection/)\>\& | ค่าฝั่งขวา |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบแบบ gtest

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::ICollection\<T\>\>\&, const SharedPtr\<System::Collections::Generic::ICollection\<T\>\>\&) function

เปรียบเทียบเท่ากันของคอลเลกชันแบบนามธรรม

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::ICollection<T>> &lhs, const SharedPtr<System::Collections::Generic::ICollection<T>> &rhs)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ฝั่งซ้าย |
| rhs_expr | const char * | นิพจน์ฝั่งขวา |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<T\>\>\& | ค่าฝั่งซ้าย |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<T\>\>\& | ค่าฝั่งขวา |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบแบบ gtest

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<Object\>\&, const SharedPtr\<Object\>\&) function

เปรียบเทียบเท่ากันของสองประเภท [Object](../../system/object/)

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<Object> &lhs, const SharedPtr<Object> &rhs)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ฝังค้าซ้าย |
| rhs_expr | const char * | นิพจน์ฝั่งขวา |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | ค่าฝั่งซ้าย |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | ค่าฝั่งขวา |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบแบบ gtest

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<T1\>\&, const SharedPtr\<T2\>\&) function

เปรียบเทียบเท่ากันของประเภทที่ไม่ทราบ

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<T1> &lhs, const SharedPtr<T2> &rhs)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ประเภทวัตถุฝั่งซ้าย |
| T2 | ประเภทวัตถุฝั่งขวา |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ฝั่งซ้าย |
| rhs_expr | const char * | นิพจน์ฝั่งขวา |
| lhs | const [SharedPtr](../../system/sharedptr/)\<T1\>\& | ค่าฝั่งซ้าย |
| rhs | const [SharedPtr](../../system/sharedptr/)\<T2\>\& | ค่าฝั่งขวา |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบแบบ gtest

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../system/sharedptr/)
* คลาส [Dictionary](../../system.collections.generic/dictionary/)
* คลาส [HashSet](../../system.collections.generic/hashset/)
* คลาส [Queue](../../system.collections.generic/queue/)
* คลาส [Stack](../../system.collections.generic/stack/)
* คลาส [SortedDictionary](../../system.collections.generic/sorteddictionary/)
* คลาส [SortedList](../../system.collections.generic/sortedlist/)
* คลาส [BitArray](../../system.collections/bitarray/)
* คลาส [StringCollection](../../system.collections.specialized/stringcollection/)
* คลาส [ICollection](../../system.collections.generic/icollection/)
* คลาส [Object](../../system/object/)
* เนมสเปซ [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)