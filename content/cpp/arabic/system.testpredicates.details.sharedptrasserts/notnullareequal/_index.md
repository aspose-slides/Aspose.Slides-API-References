---
title: NotNullAreEqual()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقارن القواميس ذات أنواع القيمة بالمساواة.
type: docs
weight: 53
url: /ar/system.testpredicates.details.sharedptrasserts/notnullareequal/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Dictionary\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::Dictionary\<K, V\>\>\&) دالة

يقارن القواميس ذات أنواع القيمة بالتساوي.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Dictionary<K, V>> &lhs, const SharedPtr<System::Collections::Generic::Dictionary<K, V>> &rhs)
```

### معاملات القالب

| المعامل | الوصف |
| --- | --- |
| K | نوع المفتاح. |
| V | نوع القيمة. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الطرف الأيسر. |
| rhs_expr | const char * | تعبير الطرف الأيمن. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, V\>\>\& | قيمة الطرف الأيسر. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, V\>\>\& | قيمة الطرف الأيمن. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Dictionary\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::Dictionary\<K, SharedPtr\<V\>\>\>\&) دالة

يقارن القواميس ذات المؤشرات المشتركة بالتساوي.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Dictionary<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::Dictionary<K, SharedPtr<V>>> &rhs)
```

### معاملات القالب

| المعامل | الوصف |
| --- | --- |
| K | نوع المفتاح. |
| V | نوع القيمة. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الطرف الأيسر. |
| rhs_expr | const char * | تعبير الطرف الأيمن. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | قيمة الطرف الأيسر. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | قيمة الطرف الأيمن. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::HashSet\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::HashSet\<T2\>\>\&) دالة

يقارن مجموعات التجزئة بالتساوي.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::HashSet<T1>> &lhs, const SharedPtr<System::Collections::Generic::HashSet<T2>> &rhs)
```

### معاملات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | نوع عنصر الحاوية الطرف الأيسر. |
| T2 | نوع عنصر الحاوية الطرف الأيمن. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الطرف الأيسر. |
| rhs_expr | const char * | تعبير الطرف الأيمن. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<T1\>\>\& | قيمة الطرف الأيسر. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<T2\>\>\& | قيمة الطرف الأيمن. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Queue\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::Queue\<T2\>\>\&) دالة

يقارن قوائم الانتظار (queues) بالتساوي.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Queue<T1>> &lhs, const SharedPtr<System::Collections::Generic::Queue<T2>> &rhs)
```

### معاملات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | نوع عنصر الحاوية الطرف الأيسر. |
| T2 | نوع عنصر الحاوية الطرف الأيمن. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الطرف الأيسر. |
| rhs_expr | const char * | تعبير الطرف الأيمن. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Queue](../../system.collections.generic/queue/)\<T1\>\>\& | قيمة الطرف الأيسر. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Queue](../../system.collections.generic/queue/)\<T2\>\>\& | قيمة الطرف الأيمن. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::Stack\<T1\>\>\&, const SharedPtr\<System::Collections::Generic::Stack\<T2\>\>\&) دالة

يقارن المكدسات (stacks) بالتساوي.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::Stack<T1>> &lhs, const SharedPtr<System::Collections::Generic::Stack<T2>> &rhs)
```

### معاملات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | نوع عنصر الحاوية الطرف الأيسر. |
| T2 | نوع عنصر الحاوية الطرف الأيمن. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الطرف الأيسر. |
| rhs_expr | const char * | تعبير الطرف الأيمن. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Stack](../../system.collections.generic/stack/)\<T1\>\>\& | قيمة الطرف الأيسر. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Stack](../../system.collections.generic/stack/)\<T2\>\>\& | قيمة الطرف الأيمن. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, V\>\>\&) دالة

يقارن القواميس المرتبة ذات أنواع القيمة بالتساوي.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedDictionary<K, V>> &lhs, const SharedPtr<System::Collections::Generic::SortedDictionary<K, V>> &rhs)
```

### معاملات القالب

| المعامل | الوصف |
| --- | --- |
| K | نوع المفتاح. |
| V | نوع القيمة. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الطرف الأيسر. |
| rhs_expr | const char * | تعبير الطرف الأيمن. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, V\>\>\& | قيمة الطرف الأيسر. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, V\>\>\& | قيمة الطرف الأيمن. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::SortedDictionary\<K, SharedPtr\<V\>\>\>\&) دالة

يقارن القواميس المرتبة ذات المؤشرات المشتركة بالتساوي.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedDictionary<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::SortedDictionary<K, SharedPtr<V>>> &rhs)
```

### معاملات القالب

| المعامل | الوصف |
| --- | --- |
| K | نوع المفتاح. |
| V | نوع القيمة. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الطرف الأيسر. |
| rhs_expr | const char * | تعبير الطرف الأيمن. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | قيمة الطرف الأيسر. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | قيمة الطرف الأيمن. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedList\<K, V\>\>\&, const SharedPtr\<System::Collections::Generic::SortedList\<K, V\>\>\&) دالة

يقارن القوائم المرتبة ذات أنواع القيمة بالتساوي.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedList<K, V>> &lhs, const SharedPtr<System::Collections::Generic::SortedList<K, V>> &rhs)
```

### معاملات القالب

| المعامل | الوصف |
| --- | --- |
| K | نوع المفتاح. |
| V | نوع القيمة. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الطرف الأيسر. |
| rhs_expr | const char * | تعبير الطرف الأيمن. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, V\>\>\& | قيمة الطرف الأيسر. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, V\>\>\& | قيمة الطرف الأيمن. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::SortedList\<K, SharedPtr\<V\>\>\>\&, const SharedPtr\<System::Collections::Generic::SortedList\<K, SharedPtr\<V\>\>\>\&) دالة

يقارن القوائم المرتبة ذات المؤشرات المشتركة بالتساوي.

```cpp
template<typename K,typename V> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::SortedList<K, SharedPtr<V>>> &lhs, const SharedPtr<System::Collections::Generic::SortedList<K, SharedPtr<V>>> &rhs)
```

### معاملات القالب

| المعامل | الوصف |
| --- | --- |
| K | نوع المفتاح. |
| V | نوع القيمة. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الطرف الأيسر. |
| rhs_expr | const char * | تعبير الطرف الأيمن. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | قيمة الطرف الأيسر. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::SortedList](../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../system/sharedptr/)\<V\>\>\>\& | قيمة الطرف الأيمن. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::BitArray\>\&, const SharedPtr\<System::Collections::BitArray\>\&) دالة

يقارن مصفوفات البت بالتساوي.

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::BitArray> &lhs, const SharedPtr<System::Collections::BitArray> &rhs)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الطرف الأيسر. |
| rhs_expr | const char * | تعبير الطرف الأيمن. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::BitArray](../../system.collections/bitarray/)\>\& | قيمة الطرف الأيسر. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::BitArray](../../system.collections/bitarray/)\>\& | قيمة الطرف الأيمن. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Specialized::StringCollection\>\&, const SharedPtr\<System::Collections::Specialized::StringCollection\>\&) دالة

يقارن مجموعات السلاسل النصية بالتساوي.

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Specialized::StringCollection> &lhs, const SharedPtr<System::Collections::Specialized::StringCollection> &rhs)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الطرف الأيسر. |
| rhs_expr | const char * | تعبير الطرف الأيمن. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Specialized::StringCollection](../../system.collections.specialized/stringcollection/)\>\& | قيمة الطرف الأيسر. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Specialized::StringCollection](../../system.collections.specialized/stringcollection/)\>\& | قيمة الطرف الأيمن. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<System::Collections::Generic::ICollection\<T\>\>\&, const SharedPtr\<System::Collections::Generic::ICollection\<T\>\>\&) دالة

يقارن المجموعات المجردة (abstract collections) بالتساوي.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<System::Collections::Generic::ICollection<T>> &lhs, const SharedPtr<System::Collections::Generic::ICollection<T>> &rhs)
```

### معاملات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العنصر. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الطرف الأيسر. |
| rhs_expr | const char * | تعبير الطرف الأيمن. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<T\>\>\& | قيمة الطرف الأيسر. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<T\>\>\& | قيمة الطرف الأيمن. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<Object\>\&, const SharedPtr\<Object\>\&) دالة

يقارن نوعين من [Object](../../system/object/) بالتساوي.

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<Object> &lhs, const SharedPtr<Object> &rhs)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الطرف الأيسر. |
| rhs_expr | const char * | تعبير الطرف الأيمن. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | قيمة الطرف الأيسر. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | قيمة الطرف الأيمن. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *, const char *, const SharedPtr\<T1\>\&, const SharedPtr\<T2\>\&) دالة

يقارن أنواعًا غير معروفة بالتساوي.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<T1> &lhs, const SharedPtr<T2> &rhs)
```

### معاملات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | نوع الكائن الطرف الأيسر. |
| T2 | نوع الكائن الطرف الأيمن. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الطرف الأيسر. |
| rhs_expr | const char * | تعبير الطرف الأيمن. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<T1\>\& | قيمة الطرف الأيسر. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<T2\>\& | قيمة الطرف الأيمن. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## انظر أيضًا

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
* Class [Object](../../system/object/)
* Namespace [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)