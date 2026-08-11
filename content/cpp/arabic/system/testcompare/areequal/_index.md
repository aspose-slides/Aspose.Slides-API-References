---
title: AreEqual()
second_title: مرجع Aspose.Slides للـ C++ API
description: يقارن المصفوفات غير المؤشرة.
type: docs
weight: 1
url: /ar/system/testcompare/areequal/
---
## TestCompare::AreEqual(const SharedPtr\<Array\<T\>\>\&, const SharedPtr\<Array\<U\>\>\&) method

يقارن المصفوفات التي لا تحتوي على مؤشرات.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<Array<T>> &arrA, const SharedPtr<Array<U>> &arrB)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع عنصر المصفوفة الأول. |
| U | نوع عنصر المصفوفة الثاني. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| arrA | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | المصفوفة اليسرى. |
| arrB | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<U\>\>\& | المصفوفة اليمنى. |

### قيمة الإرجاع

صحيح إذا كانت أحجام المصفوفات والبيانات متطابقة، وإلا خطأ.

## TestCompare::AreEqual(const SharedPtr\<Array\<SharedPtr\<T\>\>\>\&, const SharedPtr\<Array\<SharedPtr\<U\>\>\>\&) method

يقارن المصفوفات التي تحتوي على مؤشرات.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<Array<SharedPtr<T>>> &arrA, const SharedPtr<Array<SharedPtr<U>>> &arrB)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع كائن المؤشر الأول. |
| U | نوع كائن المؤشر الثاني. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| arrA | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | المصفوفة اليسرى. |
| arrB | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | المصفوفة اليمنى. |

### قيمة الإرجاع

صحيح إذا كانت أحجام المصفوفات والكائنات متطابقة، وإلا خطأ.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<T\>\>\&, const SharedPtr\<SCG::List\<U\>\>\&) method

يقارن القوائم التي لا تحتوي على مؤشرات.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<T>> &listA, const SharedPtr<SCG::List<U>> &listB)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع عنصر القائمة الأول. |
| U | نوع عنصر القائمة الثاني. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<T\>\>\& | القائمة اليسرى. |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<U\>\>\& | القائمة اليمنى. |

### قيمة الإرجاع

صحيح إذا كانت الأحجام والبيانات متطابقة، وإلا خطأ.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::List\<SharedPtr\<U\>\>\>\&) method

يقارن القوائم التي تحتوي على مؤشرات.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<SharedPtr<T>>> &listA, const SharedPtr<SCG::List<SharedPtr<U>>> &listB)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع كائن المؤشر للقائمة الأول. |
| U | نوع كائن المؤشر للقائمة الثاني. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | القائمة اليسرى. |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | القائمة اليمنى. |

### قيمة الإرجاع

صحيح إذا كانت أحجام القوائم والكائنات متطابقة، وإلا خطأ.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<T\>\>\&, const System::ArrayPtr\<U\>\&) method

يقارن القوائم مع المصفوفات في حالة العناصر غير المؤشرية.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<T>> &listA, const System::ArrayPtr<U> &arrB)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع عنصر القائمة. |
| U | [Array](../../array/) نوع العنصر. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<T\>\>\& | القائمة. |
| arrB | const [System::ArrayPtr](../../arrayptr/)\<U\>\& | [Array](../../array/). |

### قيمة الإرجاع

صحيح إذا كانت الأحجام والبيانات متطابقة، وإلا خطأ.

## TestCompare::AreEqual(const System::ArrayPtr\<T\>\&, const SharedPtr\<SCG::List\<U\>\>\&) method

يقارن القوائم مع المصفوفات في حالة العناصر غير المؤشرية.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::ArrayPtr<T> &arrA, const SharedPtr<SCG::List<U>> &listB)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | [Array](../../array/) نوع العنصر. |
| U | نوع عنصر القائمة. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| arrA | const [System::ArrayPtr](../../arrayptr/)\<T\>\& | [Array](../../array/). |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<U\>\>\& | القائمة. |

### قيمة الإرجاع

صحيح إذا كانت الأحجام والبيانات متطابقة، وإلا خطأ.

## TestCompare::AreEqual(const System::ArrayPtr\<SharedPtr\<T\>\>\&, const SharedPtr\<SCG::List\<SharedPtr\<U\>\>\>\&) method

يقارن القوائم مع المصفوفات في حالة العناصر المؤشرية.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::ArrayPtr<SharedPtr<T>> &arr, const SharedPtr<SCG::List<SharedPtr<U>>> &list)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | [Array](../../array/) نوع الكائن المؤشر. |
| U | نوع كائن المؤشر للقائمة. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| arr | const [System::ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<T\>\>\& | [Array](../../array/). |
| list | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | القائمة. |

### قيمة الإرجاع

صحيح إذا كانت الأحجام والكائنات متطابقة، وإلا خطأ.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<SharedPtr\<T\>\>\>\&, const System::ArrayPtr\<SharedPtr\<U\>\>\&) method

يقارن القوائم مع المصفوفات في حالة العناصر المؤشرية.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<SharedPtr<T>>> &list, const System::ArrayPtr<SharedPtr<U>> &arr)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع كائن المؤشر للقائمة. |
| U | [Array](../../array/) نوع الكائن المؤشر. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| list | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | القائمة. |
| arr | const [System::ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<U\>\>\& | [Array](../../array/). |

### قيمة الإرجاع

صحيح إذا كانت الأحجام والكائنات متطابقة، وإلا خطأ.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K, U\>\>\&, const SharedPtr\<SCG::Dictionary\<K, U\>\>\&) method

يقارن القواميس التي لا تحتوي على مؤشرات للأنواع المرتبطة.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K, U>> &dictA, const SharedPtr<SCG::Dictionary<K, U>> &dictB)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| K | نوع المفتاح. |
| U | النوع المرتبط. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, U\>\>\& | القاموس اليساري. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, U\>\>\& | القاموس اليمني. |

### قيمة الإرجاع

صحيح إذا كانت أحجام القواميس والبيانات متطابقة، وإلا خطأ.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::Dictionary\<K, SharedPtr\<U\>\>\>\&) method

يقارن القواميس التي تحتوي على مؤشرات للأنواع المرتبطة.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::Dictionary<K, SharedPtr<U>>> &dictB)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| K | نوع المفتاح. |
| U | نوع الكائن المؤشر المرتبط. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | القاموس اليساري. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | القاموس اليمني. |

### قيمة الإرجاع

صحيح إذا كانت أحجام القواميس والبيانات متطابقة، وإلا خطأ.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K1, U1\>\>\&, const SharedPtr\<SCG::Dictionary\<K2, U2\>\>\&) method

يقارن القواميس ذات الأنواع المختلفة.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K1, U1>> &dictA, const SharedPtr<SCG::Dictionary<K2, U2>> &dictB)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| K1 | نوع مفتاح القاموس اليساري. |
| U1 | نوع العنصر المرتبط في القاموس اليساري. |
| K2 | نوع مفتاح القاموس اليمني. |
| U2 | نوع العنصر المرتبط في القاموس اليمني. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K1, U1\>\>\& | القاموس اليساري. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K2, U2\>\>\& | القاموس اليمني. |

### قيمة الإرجاع

دائمًا ما تُعيد خطأ لأن تحويل النوع ممنوع هنا.

## TestCompare::AreEqual(const SharedPtr\<SCG::HashSet\<T\>\>\&, const SharedPtr\<SCG::HashSet\<U\>\>\&) method

يقارن مجموعات التجزئة التي لا تحتوي على مؤشرات.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::HashSet<T>> &containerPtrA, const SharedPtr<SCG::HashSet<U>> &containerPtrB)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع عنصر مجموعة التجزئة الأول. |
| U | نوع عنصر مجموعة التجزئة الثاني. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| containerPtrA | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<T\>\>\& | مجموعة التجزئة اليسارية. |
| containerPtrB | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<U\>\>\& | مجموعة التجزئة اليمنية. |

### قيمة الإرجاع

صحيح إذا كانت أحجام مجموعات التجزئة والبيانات متطابقة، وإلا خطأ.

## TestCompare::AreEqual(const SharedPtr\<SCG::HashSet\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::HashSet\<SharedPtr\<U\>\>\>\&) method

يقارن مجموعات التجزئة التي تحتوي على مؤشرات.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::HashSet<SharedPtr<T>>> &contA, const SharedPtr<SCG::HashSet<SharedPtr<U>>> &contB)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع كائن المؤشر لمجموعة التجزئة الأول. |
| U | نوع كائن المؤشر لمجموعة التجزئة الثاني. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| contA | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | مجموعة التجزئة اليسارية. |
| contB | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | مجموعة التجزئة اليمنية. |

### قيمة الإرجاع

صحيح إذا كانت أحجام مجموعات التجزئة والبيانات متطابقة، وإلا خطأ.

## TestCompare::AreEqual(const SCG::QueuePtr\<T\>\&, const SCG::QueuePtr\<U\>\&) method

يقارن الطوابير التي لا تحتوي على مؤشرات.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SCG::QueuePtr<T> &queueA, const SCG::QueuePtr<U> &queueB)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع عنصر الطابور الأول. |
| U | نوع عنصر الطابور الثاني. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| queueA | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<T\>\& | الطابور اليساري. |
| queueB | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<U\>\& | الطابور اليمني. |

### قيمة الإرجاع

صحيح إذا كانت أحجام الطوابير والبيانات متطابقة، وإلا خطأ.

## TestCompare::AreEqual(const SCG::QueuePtr\<SharedPtr\<T\>\>\&, const SCG::QueuePtr\<SharedPtr\<U\>\>\&) method

يقارن الطوابير التي تحتوي على مؤشرات.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SCG::QueuePtr<SharedPtr<T>> &queueA, const SCG::QueuePtr<SharedPtr<U>> &queueB)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع كائن المؤشر للطابور الأول. |
| U | نوع كائن المؤشر للطابور الثاني. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| queueA | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<[SharedPtr](../../sharedptr/)\<T\>\>\& | الطابور اليساري. |
| queueB | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<[SharedPtr](../../sharedptr/)\<U\>\>\& | الطابور اليمني. |

### قيمة الإرجاع

صحيح إذا كانت أحجام الطوابير والبيانات متطابقة، وإلا خطأ.

## TestCompare::AreEqual(const SharedPtr\<SCG::Stack\<T\>\>\&, const SharedPtr\<SCG::Stack\<U\>\>\&) method

يقارن المكدسات التي لا تحتوي على مؤشرات.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Stack<T>> &stackA, const SharedPtr<SCG::Stack<U>> &stackB)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع عنصر المكدس الأول. |
| U | نوع عنصر المكدس الثاني. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stackA | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<T\>\>\& | المكدس اليساري. |
| stackB | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<U\>\>\& | المكدس اليمني. |

### قيمة الإرجاع

صحيح إذا كانت أحجام المكدسات والبيانات متطابقة، وإلا خطأ.

## TestCompare::AreEqual(const SharedPtr\<SCG::Stack\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::Stack\<SharedPtr\<U\>\>\>\&) method

يقارن المكدسات التي تحتوي على مؤشرات.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Stack<SharedPtr<T>>> &stackA, const SharedPtr<SCG::Stack<SharedPtr<U>>> &stackB)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع كائن المؤشر للمكدس الأول. |
| U | نوع كائن المؤشر للمكدس الثاني. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stackA | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | المكدس اليساري. |
| stackB | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | المكدس اليمني. |

### قيمة الإرجاع

صحيح إذا كانت أحجام المكدسات والبيانات متطابقة، وإلا خطأ.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K, U\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K, U\>\>\&) method

يقارن القواميس المرتبة التي لا تحتوي على مؤشرات للأنواع المرتبطة.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K, U>> &dictA, const SharedPtr<SCG::SortedDictionary<K, U>> &dictB)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| K | نوع المفتاح. |
| U | النوع المرتبط. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, U\>\>\& | القاموس اليساري. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, U\>\>\& | القاموس اليمني. |

### قيمة الإرجاع

صحيح إذا كانت أحجام القواميس والبيانات متطابقة، وإلا خطأ.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K, SharedPtr\<U\>\>\>) method

يقارن القواميس المرتبة التي تحتوي على مؤشرات للأنواع المرتبطة.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::SortedDictionary<K, SharedPtr<U>>> &dictB)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| K | نوع المفتاح. |
| U | نوع الكائن المؤشر المرتبط. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | القاموس اليساري. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | القاموس اليمني. |

### قيمة الإرجاع

صحيح إذا كانت أحجام القواميس والبيانات متطابقة، وإلا خطأ.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K1, U1\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K2, U2\>\>\&) method

يقارن القواميس المرتبة ذات الأنواع المختلفة.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K1, U1>> &dictA, const SharedPtr<SCG::SortedDictionary<K2, U2>> &dictB)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| K1 | نوع مفتاح القاموس اليساري. |
| U1 | نوع العنصر المرتبط في القاموس اليساري. |
| K2 | نوع مفتاح القاموس اليمني. |
| U2 | نوع العنصر المرتبط في القاموس اليمني. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K1, U1\>\>\& | القاموس اليساري. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K2, U2\>\>\& | القاموس اليمني. |

### قيمة الإرجاع

دائمًا ما تُعيد خطأ لأن تحويل النوع ممنوع هنا.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K, U\>\>\&, const SharedPtr\<SCG::SortedList\<K, U\>\>\&) method

يقارن القوائم المرتبة التي لا تحتوي على مؤشرات للأنواع المرتبطة.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K, U>> &dictA, const SharedPtr<SCG::SortedList<K, U>> &dictB)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| K | نوع المفتاح. |
| U | النوع المرتبط. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, U\>\>\& | القائمة اليسارية. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, U\>\>\& | القائمة اليمنية. |

### قيمة الإرجاع

صحيح إذا كانت أحجام القوائم والبيانات متطابقة، وإلا خطأ.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::SortedList\<K, SharedPtr\<U\>\>\>\&) method

يقارن القوائم المرتبة التي تحتوي على مؤشرات للأنواع المرتبطة.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::SortedList<K, SharedPtr<U>>> &dictB)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| K | نوع المفتاح. |
| U | نوع الكائن المؤشر المرتبط. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | القائمة اليسارية. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | القائمة اليمنية. |

### قيمة الإرجاع

صحيح إذا كانت أحجام القوائم والبيانات متطابقة، وإلا خطأ.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K1, U1\>\>\&, const SharedPtr\<SCG::SortedList\<K2, U2\>\>\&) method

يقارن القوائم المرتبة ذات الأنواع المختلفة.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K1, U1>> &dictA, const SharedPtr<SCG::SortedList<K2, U2>> &dictB)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| K1 | نوع مفتاح القائمة اليسارية. |
| U1 | نوع العنصر المرتبط في القائمة اليسارية. |
| K2 | نوع مفتاح القائمة اليمنية. |
| U2 | نوع العنصر المرتبط في القائمة اليمنية. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K1, U1\>\>\& | القائمة اليسارية. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K2, U2\>\>\& | القائمة اليمنية. |

### قيمة الإرجاع

دائمًا ما تُعيد خطأ لأن تحويل النوع ممنوع هنا.

## TestCompare::AreEqual(const System::Collections::Specialized::StringCollectionPtr\&, const System::Collections::Specialized::StringCollectionPtr\&) method

يقارن مجموعات السلاسل.

```cpp
static bool System::TestCompare::AreEqual(const System::Collections::Specialized::StringCollectionPtr &arrA, const System::Collections::Specialized::StringCollectionPtr &arrB)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| arrA | const [System::Collections::Specialized::StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)\& | المجموعة اليسارية. |
| arrB | const [System::Collections::Specialized::StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)\& | المجموعة اليمنية. |

### قيمة الإرجاع

صحيح إذا كانت الأحجام والبيانات متطابقة، وإلا خطأ.

## TestCompare::AreEqual(const System::SharedPtr\<SCG::IEnumerable\<T\>\>\&, const System::SharedPtr\<SCG::IEnumerable\<U\>\>\&) method

يقارن مثيلات IEnumerable.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::SharedPtr<SCG::IEnumerable<T>> &et, const System::SharedPtr<SCG::IEnumerable<U>> &eu)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| et | const [System::SharedPtr](../../sharedptr/)\<[SCG::IEnumerable](../../../system.collections.generic/ienumerable/)\<T\>\>\& | كائن التعداد اليساري. |
| eu | const [System::SharedPtr](../../sharedptr/)\<[SCG::IEnumerable](../../../system.collections.generic/ienumerable/)\<U\>\>\& | كائن التعداد اليمني. |

### قيمة الإرجاع

صحيح إذا كانت الأحجام والبيانات متطابقة، وإلا خطأ.

## انظر أيضًا

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* الفئة [Array](../../array/)
* الفئة [List](../../../system.collections.generic/list/)
* الفئة [Dictionary](../../../system.collections.generic/dictionary/)
* الفئة [HashSet](../../../system.collections.generic/hashset/)
* الفئة [QueuePtr](../../../system.collections.generic/queueptr/)
* الفئة [Stack](../../../system.collections.generic/stack/)
* الفئة [SortedDictionary](../../../system.collections.generic/sorteddictionary/)
* الفئة [SortedList](../../../system.collections.generic/sortedlist/)
* الفئة [StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)
* الفئة [IEnumerable](../../../system.collections.generic/ienumerable/)
* البنية [TestCompare](../)
* مساحة الاسم [System](../../)
* المكتبة [Aspose.Slides](../../../)