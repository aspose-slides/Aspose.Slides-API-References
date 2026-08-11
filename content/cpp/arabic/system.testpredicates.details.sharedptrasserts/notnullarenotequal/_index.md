---
title: NotNullAreNotEqual()
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: يقارن القواميس ذات أنواع القيم بالمقارنة غير المتساوية.
type: docs
weight: 118
url: /ar/system.testpredicates.details.sharedptrasserts/notnullarenotequal/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Dictionary\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::Dictionary\<K, V\>\>\&) function

يقارن القواميس ذات أنواع القيم بالمقارنة غير المتساوية.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Dictionary<K, V>> &lhs, const SharedPtr<System::Collections::Generic::Dictionary<K, V>> &rhs)
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| K | نوع المفتاح. |
| V | نوع القيمة. |

### المعاملات

| معامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الجانب الأيسر. |
| rhs_expr | const char * | تعبير الجانب الأيمن. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, V\>\>\& | قيمة الجانب الأيسر. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, V\>\>\& | قيمة الجانب الأيمن. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Dictionary\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::Dictionary\<K, SharedPtr\<V\>\>\>\&) function

يقارن القواميس ذات مؤشرات مشتركة بالمقارنة غير المتساوية.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Dictionary<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::Dictionary<K, SharedPtr<V>>> &rhs)
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| K | نوع المفتاح. |
| V | نوع القيمة. |

### المعاملات

| معامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الجانب الأيسر. |
| rhs_expr | const char * | تعبير الجانب الأيمن. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | قيمة الجانب الأيسر. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | قيمة الجانب الأيمن. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::HashSet\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::HashSet\<T2\>\>\&) function

يقارن مجموعات التجزئة بالمقارنة غير المتساوية.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::HashSet<T1>> &lhs, const SharedPtr<System::Collections::Generic::HashSet<T2>> &rhs)
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| T1 | نوع عنصر الحاوية في الجانب الأيسر. |
| T2 | نوع عنصر الحاوية في الجانب الأيمن. |

### المعاملات

| معامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الجانب الأيسر. |
| rhs_expr | const char * | تعبير الجانب الأيمن. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<T1\>\>\& | قيمة الجانب الأيسر. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<T2\>\>\& | قيمة الجانب الأيمن. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Queue\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::Queue\<T2\>\>\&) function

يقارن الطوابير بالمقارنة غير المتساوية.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Queue<T1>> &lhs, const SharedPtr<System::Collections::Generic::Queue<T2>> &rhs)
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| T1 | نوع عنصر الحاوية في الجانب الأيسر. |
| T2 | نوع عنصر الحاوية في الجانب الأيمن. |

### المعاملات

| معامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الجانب الأيسر. |
| rhs_expr | const char * | تعبير الجانب الأيمن. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Queue](../../system.collections.generic/queue/)\<T1\>\>\& | قيمة الجانب الأيسر. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Queue](../../system.collections.generic/queue/)\<T2\>\>\& | قيمة الجانب الأيمن. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Stack\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::Stack\<T2\>\>\&) function

يقارن المكدسات بالمقارنة غير المتساوية.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Stack<T1>> &lhs, const SharedPtr<System::Collections::Generic::Stack<T2>> &rhs)
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| T1 | نوع عنصر الحاوية في الجانب الأيسر. |
| T2 | نوع عنصر الحاوية في الجانب الأيمن. |

### المعاملات

| معامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الجانب الأيسر. |
| rhs_expr | const char * | تعبير الجانب الأيمن. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Stack](../../system.collections.generic/stack/)\<T1\>\>\& | قيمة الجانب الأيسر. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Stack](../../system.collections.generic/stack/)\<T2\>\>\& | قيمة الجانب الأيمن. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, V\>\>\&) function

يقارن القواميس المرتبة ذات أنواع القيم بالمقارنة غير المتساوية.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedDictionary<K, V>> &lhs, const SharedPtr<System::Collections::Generic::SortedDictionary<K, V>> &rhs)
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| K | نوع المفتاح. |
| V | نوع القيمة. |

### المعاملات

| معامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الجانب الأيسر. |
| rhs_expr | const char * | تعبير الجانب الأيمن. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, V\>\>\& | قيمة الجانب الأيسر. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, V\>\>\& | قيمة الجانب الأيمن. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, SharedPtr\<V\>\>\>\&) function

يقارن القواميس المرتبة ذات مؤشرات مشتركة بالمقارنة غير المتساوية.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedDictionary<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::SortedDictionary<K, SharedPtr<V>>> &rhs)
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| K | نوع المفتاح. |
| V | نوع القيمة. |

### المعاملات

| معامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الجانب الأيسر. |
| rhs_expr | const char * | تعبير الجانب الأيمن. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | قيمة الجانب الأيسر. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | قيمة الجانب الأيمن. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedList\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::SortedList\<K, V\>\>\&) function

يقارن القوائم المرتبة ذات أنواع القيم بالمقارنة غير المتساوية.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedList<K, V>> &lhs, const SharedPtr<System::Collections::Generic::SortedList<K, V>> &rhs)
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| K | نوع المفتاح. |
| V | نوع القيمة. |

### المعاملات

| معامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الجانب الأيسر. |
| rhs_expr | const char * | تعبير الجانب الأيمن. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, V\>\>\& | قيمة الجانب الأيسر. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, V\>\>\& | قيمة الجانب الأيمن. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedList\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::SortedList\<K, SharedPtr\<V\>\>\>\&) function

يقارن القوائم المرتبة ذات مؤشرات مشتركة بالمقارنة غير المتساوية.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedList<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::SortedList<K, SharedPtr<V>>> &rhs)
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| K | نوع المفتاح. |
| V | نوع القيمة. |

### المعاملات

| معامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الجانب الأيسر. |
| rhs_expr | const char * | تعبير الجانب الأيمن. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | قيمة الجانب الأيسر. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | قيمة الجانب الأيمن. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::BitArray\>\&, const SharedPtr\<System::Collections::BitArray\>\&) function

يقارن مصفوفات البت بالمقارنة غير المتساوية.

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::BitArray> &lhs, const SharedPtr<System::Collections::BitArray> &rhs)
```

### المعاملات

| معامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الجانب الأيسر. |
| rhs_expr | const char * | تعبير الجانب الأيمن. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::BitArray](../../system.collections/bitarray/)\>\& | قيمة الجانب الأيسر. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::BitArray](../../system.collections/bitarray/)\>\& | قيمة الجانب الأيمن. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Specialized::StringCollection\>\&, const SharedPtr\<System::Collections::Specialized::StringCollection\>\&) function

يقارن مجموعات السلاسل النصية بالمقارنة غير المتساوية.

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Specialized::StringCollection> &lhs, const SharedPtr<System::Collections::Specialized::StringCollection> &rhs)
```

### المعاملات

| معامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الجانب الأيسر. |
| rhs_expr | const char * | تعبير الجانب الأيمن. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Specialized::StringCollection](../../system.collections.specialized/stringcollection/)\>\& | قيمة الجانب الأيسر. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Specialized::StringCollection](../../system.collections.specialized/stringcollection/)\>\& | قيمة الجانب الأيمن. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::ICollection\<T\>\>\&, const SharedPtr\<System::Collections::Generic::ICollection\<T\>\>\&) function

يقارن المجموعات التجريدية بالمقارنة غير المتساوية.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::ICollection<T>> &lhs, const SharedPtr<System::Collections::Generic::ICollection<T>> &rhs)
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| T | نوع العنصر. |

### المعاملات

| معامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الجانب الأيسر. |
| rhs_expr | const char * | تعبير الجانب الأيمن. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<T\>\>\& | قيمة الجانب الأيسر. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<T\>\>\& | قيمة الجانب الأيمن. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *, const char *, const SharedPtr\<T1\>\&, const SharedPtr\<T2\>\&) function

يقارن الأنواع غير المعروفة بالمقارنة غير المتساوية.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<T1> &lhs, const SharedPtr<T2> &rhs)
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| T1 | نوع الكائن في الجانب الأيسر. |
| T2 | نوع الكائن في الجانب الأيمن. |

### المعاملات

| معامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الجانب الأيسر. |
| rhs_expr | const char * | تعبير الجانب الأيمن. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<T1\>\& | قيمة الجانب الأيسر. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<T2\>\& | قيمة الجانب الأيمن. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## أنظر أيضًا

* تعريف نوع [SharedPtr](../../system/sharedptr/)
* فئة [Dictionary](../../system.collections.generic/dictionary/)
* فئة [HashSet](../../system.collections.generic/hashset/)
* فئة [Queue](../../system.collections.generic/queue/)
* فئة [Stack](../../system.collections.generic/stack/)
* فئة [SortedDictionary](../../system.collections.generic/sorteddictionary/)
* فئة [SortedList](../../system.collections.generic/sortedlist/)
* فئة [BitArray](../../system.collections/bitarray/)
* فئة [StringCollection](../../system.collections.specialized/stringcollection/)
* فئة [ICollection](../../system.collections.generic/icollection/)
* نطاق [System::TestPredicates::Details::SharedPtrAsserts](../)
* مكتبة [Aspose.Slides](../../)