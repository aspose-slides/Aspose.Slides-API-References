---
title: AreEqual()
second_title: Aspose.Slides برای C++ مرجع API
description: آرایه‌های غیر اشاره‌گر را مقایسه می‌کند.
type: docs
weight: 1
url: /fa/system/testcompare/areequal/
---
## TestCompare::AreEqual(const SharedPtr\<Array\<T\>\>\&, const SharedPtr\<Array\<U\>\>\&) method

آرایه‌های غیر اشاره‌گر را مقایسه می‌کند.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<Array<T>> &arrA, const SharedPtr<Array<U>> &arrB)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عنصر اول آرایه. |
| U | نوع عنصر دوم آرایه. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| arrA | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | آرایه سمت چپ. |
| arrB | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<U\>\>\& | آرایه سمت راست. |

### مقدار بازگشت

true اگر اندازه‌ها و داده‌های آرایه‌ها مطابقت داشته باشند، false در غیر این صورت.

## TestCompare::AreEqual(const SharedPtr\<Array\<SharedPtr\<T\>\>\>\&, const SharedPtr\<Array\<SharedPtr\<U\>\>\>\&) method

آرایه‌های اشاره‌گر را مقایسه می‌کند.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<Array<SharedPtr<T>>> &arrA, const SharedPtr<Array<SharedPtr<U>>> &arrB)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع شیء اشاره‌گر شده آرایه اول. |
| U | نوع شیء اشاره‌گر شده آرایه دوم. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| arrA | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | آرایه سمت چپ. |
| arrB | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | آرایه سمت راست. |

### مقدار بازگشت

true اگر اندازه‌ها و اشیاء آرایه‌ها مطابقت داشته باشند، false در غیر این صورت.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<T\>\>\&, const SharedPtr\<SCG::List\<U\>\>\&) method

لیست‌های غیر اشاره‌گر را مقایسه می‌کند.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<T>> &listA, const SharedPtr<SCG::List<U>> &listB)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عنصر اول لیست. |
| U | نوع عنصر دوم لیست. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<T\>\>\& | لیست سمت چپ. |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<U\>\>\& | لیست سمت راست. |

### مقدار بازگشت

true اگر اندازه‌ها و داده‌های لیست‌ها مطابقت داشته باشند، false در غیر این صورت.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::List\<SharedPtr\<U\>\>\>\&) method

لیست‌های اشاره‌گر را مقایسه می‌کند.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<SharedPtr<T>>> &listA, const SharedPtr<SCG::List<SharedPtr<U>>> &listB)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع شیء اشاره‌گر شده عنصر اول لیست. |
| U | نوع شیء اشاره‌گر شده عنصر دوم لیست. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | لیست سمت چپ. |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | لیست سمت راست. |

### مقدار بازگشت

true اگر اندازه‌ها و اشیاء لیست‌ها مطابقت داشته باشند، false در غیر این صورت.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<T\>\>\&, const System::ArrayPtr\<U\>\&) method

لیست‌ها را با آرایه‌ها در حالت عناصر غیر اشاره‌گر مقایسه می‌کند.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<T>> &listA, const System::ArrayPtr<U> &arrB)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عنصر لیست. |
| U | نوع عنصر [Array](../../array/). |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<T\>\>\& | لیست. |
| arrB | const [System::ArrayPtr](../../arrayptr/)\<U\>\& | [Array](../../array/). |

### مقدار بازگشت

true اگر اندازه‌ها و داده‌ها مطابقت داشته باشند، false در غیر این صورت.

## TestCompare::AreEqual(const System::ArrayPtr\<T\>\&, const SharedPtr\<SCG::List\<U\>\>\&) method

لیست‌ها را با آرایه‌ها در حالت عناصر غیر اشاره‌گر مقایسه می‌کند.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::ArrayPtr<T> &arrA, const SharedPtr<SCG::List<U>> &listB)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عنصر [Array](../../array/). |
| U | نوع عنصر لیست. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| arrA | const [System::ArrayPtr](../../arrayptr/)\<T\>\& | [Array](../../array/). |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<U\>\>\& | لیست. |

### مقدار بازگشت

true اگر اندازه‌ها و داده‌ها مطابقت داشته باشند، false در غیر این صورت.

## TestCompare::AreEqual(const System::ArrayPtr\<SharedPtr\<T\>\>\&, const SharedPtr\<SCG::List\<SharedPtr\<U\>\>\>\&) method

لیست‌ها را با آرایه‌ها در حالت عناصر اشاره‌گر مقایسه می‌کند.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::ArrayPtr<SharedPtr<T>> &arr, const SharedPtr<SCG::List<SharedPtr<U>>> &list)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع شیء اشاره‌گر شده [Array](../../array/). |
| U | نوع شیء اشاره‌گر شده لیست. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| arr | const [System::ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<T\>\>\& | [Array](../../array/). |
| list | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | لیست. |

### مقدار بازگشت

true اگر اندازه‌ها و اشیاء مطابقت داشته باشند، false در غیر این صورت.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<SharedPtr\<T\>\>\>\&, const System::ArrayPtr\<SharedPtr\<U\>\>\&) method

لیست‌ها را با آرایه‌ها در حالت عناصر اشاره‌گر مقایسه می‌کند.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<SharedPtr<T>>> &list, const System::ArrayPtr<SharedPtr<U>> &arr)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع شیء اشاره‌گر شده لیست. |
| U | نوع شیء اشاره‌گر شده [Array](../../array/). |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| list | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | لیست. |
| arr | const [System::ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<U\>\>\& | [Array](../../array/). |

### مقدار بازگشت

true اگر اندازه‌ها و اشیاء مطابقت داشته باشند، false در غیر این صورت.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K, U\>\>\&, const SharedPtr\<SCG::Dictionary\<K, U\>\>\&) method

دیکشنری‌های نوع‌نقشه‌گذاری غیر اشاره‌گر را مقایسه می‌کند.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K, U>> &dictA, const SharedPtr<SCG::Dictionary<K, U>> &dictB)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| K | نوع کلید. |
| U | نوع مقدار. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, U\>\>\& | دیکشنری سمت چپ. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, U\>\>\& | دیکشنری سمت راست. |

### مقدار بازگشت

true اگر اندازه‌ها و داده‌های دیکشنری‌ها مطابقت داشته باشند، false در غیر این صورت.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::Dictionary\<K, SharedPtr\<U\>\>\>) method

دیکشنری‌های نوع‌نقشه‌گذاری اشاره‌گر را مقایسه می‌کند.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::Dictionary<K, SharedPtr<U>>> &dictB)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| K | نوع کلید. |
| U | نوع شیء اشاره‌گر شده مقدار. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | دیکشنری سمت چپ. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | دیکشنری سمت راست. |

### مقدار بازگشت

true اگر اندازه‌ها و داده‌های دیکشنری‌ها مطابقت داشته باشند، false در غیر این صورت.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K1, U1\>\>\&, const SharedPtr\<SCG::Dictionary\<K2, U2\>\>\&) method

دیکشنری‌های انواع مختلف را مقایسه می‌کند.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K1, U1>> &dictA, const SharedPtr<SCG::Dictionary<K2, U2>> &dictB)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| K1 | نوع کلید دیکشنری سمت چپ. |
| U1 | نوع مقدار دیکشنری سمت چپ. |
| K2 | نوع کلید دیکشنری سمت راست. |
| U2 | نوع مقدار دیکشنری سمت راست. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K1, U1\>\>\& | دیکشنری سمت چپ. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K2, U2\>\>\& | دیکشنری سمت راست. |

### مقدار بازگشت

همیشه false باز می‌گردد زیرا تبدیل نوع در اینجا ممنوع است.

## TestCompare::AreEqual(const SharedPtr\<SCG::HashSet\<T\>\>\&, const SharedPtr\<SCG::HashSet\<U\>\>\&) method

مجموعه‌های هش غیر اشاره‌گر را مقایسه می‌کند.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::HashSet<T>> &containerPtrA, const SharedPtr<SCG::HashSet<U>> &containerPtrB)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عنصر اول مجموعه هش. |
| U | نوع عنصر دوم مجموعه هش. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| containerPtrA | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<T\>\>\& | مجموعه هش سمت چپ. |
| containerPtrB | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<U\>\>\& | مجموعه هش سمت راست. |

### مقدار بازگشت

true اگر اندازه‌ها و داده‌های مجموعه‌ها مطابقت داشته باشند، false در غیر این صورت.

## TestCompare::AreEqual(const SharedPtr\<SCG::HashSet\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::HashSet\<SharedPtr\<U\>\>\>\&) method

مجموعه‌های هش اشاره‌گر را مقایسه می‌کند.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::HashSet<SharedPtr<T>>> &contA, const SharedPtr<SCG::HashSet<SharedPtr<U>>> &contB)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع شیء اشاره‌گر شده عنصر اول مجموعه هش. |
| U | نوع شیء اشاره‌گر شده عنصر دوم مجموعه هش. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| contA | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | مجموعه هش سمت چپ. |
| contB | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | مجموعه هش سمت راست. |

### مقدار بازگشت

true اگر اندازه‌ها و داده‌های مجموعه‌ها مطابقت داشته باشند، false در غیر این صورت.

## TestCompare::AreEqual(const SCG::QueuePtr\<T\>\&, const SCG::QueuePtr\<U\>\&) method

صف‌های غیر اشاره‌گر را مقایسه می‌کند.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SCG::QueuePtr<T> &queueA, const SCG::QueuePtr<U> &queueB)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عنصر اول صف. |
| U | نوع عنصر دوم صف. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| queueA | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<T\>\& | صف سمت چپ. |
| queueB | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<U\>\& | صف سمت راست. |

### مقدار بازگشت

true اگر اندازه‌ها و داده‌های صف‌ها مطابقت داشته باشند، false در غیر این صورت.

## TestCompare::AreEqual(const SCG::QueuePtr\<SharedPtr\<T\>\>\&, const SCG::QueuePtr\<SharedPtr\<U\>\>\&) method

صف‌های اشاره‌گر را مقایسه می‌کند.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SCG::QueuePtr<SharedPtr<T>> &queueA, const SCG::QueuePtr<SharedPtr<U>> &queueB)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع شیء اشاره‌گر شده عنصر اول صف. |
| U | نوع شیء اشاره‌گر شده عنصر دوم صف. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| queueA | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<[SharedPtr](../../sharedptr/)\<T\>\>\& | صف سمت چپ. |
| queueB | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<[SharedPtr](../../sharedptr/)\<U\>\>\& | صف سمت راست. |

### مقدار بازگشت

true اگر اندازه‌ها و داده‌های صف‌ها مطابقت داشته باشند، false در غیر این صورت.

## TestCompare::AreEqual(const SharedPtr\<SCG::Stack\<T\>\>\&, const SharedPtr\<SCG::Stack\<U\>\>\&) method

پشته‌های غیر اشاره‌گر را مقایسه می‌کند.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Stack<T>> &stackA, const SharedPtr<SCG::Stack<U>> &stackB)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عنصر اول پشته. |
| U | نوع عنصر دوم پشته. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stackA | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<T\>\>\& | پشته سمت چپ. |
| stackB | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<U\>\>\& | پشته سمت راست. |

### مقدار بازگشت

true اگر اندازه‌ها و داده‌های پشته‌ها مطابقت داشته باشند، false در غیر این صورت.

## TestCompare::AreEqual(const SharedPtr\<SCG::Stack\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::Stack\<SharedPtr\<U\>\>\>\&) method

پشته‌های اشاره‌گر را مقایسه می‌کند.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Stack<SharedPtr<T>>> &stackA, const SharedPtr<SCG::Stack<SharedPtr<U>>> &stackB)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع شیء اشاره‌گر شده عنصر اول پشته. |
| U | نوع شیء اشاره‌گر شده عنصر دوم پشته. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stackA | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | پشته سمت چپ. |
| stackB | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | پشته سمت راست. |

### مقدار بازگشت

true اگر اندازه‌ها و داده‌های پشته‌ها مطابقت داشته باشند، false در غیر این صورت.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K, U\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K, U\>\>\&) method

دیکشنری‌های مرتب غیر اشاره‌گر را مقایسه می‌کند.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K, U>> &dictA, const SharedPtr<SCG::SortedDictionary<K, U>> &dictB)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| K | نوع کلید. |
| U | نوع مقدار. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, U\>\>\& | دیکشنری سمت چپ. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, U\>\>\& | دیکشنری سمت راست. |

### مقدار بازگشت

true اگر اندازه‌ها و داده‌های دیکشنری‌ها مطابقت داشته باشند، false در غیر این صورت.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K, SharedPtr\<U\>\>\>) method

دیکشنری‌های مرتب اشاره‌گر را مقایسه می‌کند.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::SortedDictionary<K, SharedPtr<U>>> &dictB)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| K | نوع کلید. |
| U | نوع شیء اشاره‌گر شده مقدار. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | دیکشنری سمت چپ. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | دیکشنری سمت راست. |

### مقدار بازگشت

true اگر اندازه‌ها و داده‌های دیکشنری‌ها مطابقت داشته باشند، false در غیر این صورت.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K1, U1\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K2, U2\>\>\&) method

دیکشنری‌های مرتب انواع مختلف را مقایسه می‌کند.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K1, U1>> &dictA, const SharedPtr<SCG::SortedDictionary<K2, U2>> &dictB)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| K1 | نوع کلید دیکشنری سمت چپ. |
| U1 | نوع مقدار دیکشنری سمت چپ. |
| K2 | نوع کلید دیکشنری سمت راست. |
| U2 | نوع مقدار دیکشنری سمت راست. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K1, U1\>\>\& | دیکسینری سمت چپ. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K2, U2\>\>\& | دیکسینری سمت راست. |

### مقدار بازگشت

همیشه false باز می‌گردد زیرا تبدیل نوع در اینجا ممنوع است.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K, U\>\>\&, const SharedPtr\<SCG::SortedList\<K, U\>\>\&) method

لیست‌های مرتب غیر اشاره‌گر را مقایسه می‌کند.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K, U>> &dictA, const SharedPtr<SCG::SortedList<K, U>> &dictB)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| K | نوع کلید. |
| U | نوع مقدار. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, U\>\>\& | لیست سمت چپ. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, U\>\>\& | لیست سمت راست. |

### مقدار بازگشت

true اگر اندازه‌ها و داده‌های لیست‌ها مطابقت داشته باشند، false در غیر این صورت.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::SortedList\<K, SharedPtr\<U\>\>\>\&) method

لیست‌های مرتب اشاره‌گر را مقایسه می‌کند.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::SortedList<K, SharedPtr<U>>> &dictB)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| K | نوع کلید. |
| U | نوع شیء اشاره‌گر شده مقدار. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | لیست سمت چپ. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | لیست سمت راست. |

### مقدار بازگشت

true اگر اندازه‌ها و داده‌های لیست‌ها مطابقت داشته باشند، false در غیر این صورت.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K1, U1\>\>\&, const SharedPtr\<SCG::SortedList\<K2, U2\>\>\&) method

لیست‌های مرتب انواع مختلف را مقایسه می‌کند.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K1, U1>> &dictA, const SharedPtr<SCG::SortedList<K2, U2>> &dictB)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| K1 | نوع کلید لیست سمت چپ. |
| U1 | نوع مقدار لیست سمت چپ. |
| K2 | نوع کلید لیست سمت راست. |
| U2 | نوع مقدار لیست سمت راست. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K1, U1\>\>\& | لیست سمت چپ. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K2, U2\>\>\& | لیست سمت راست. |

### مقدار بازگشت

همیشه false باز می‌گردد زیرا تبدیل نوع در اینجا ممنوع است.

## TestCompare::AreEqual(const System::Collections::Specialized::StringCollectionPtr\&, const System::Collections::Specialized::StringCollectionPtr\&) method

مجموعه‌های رشته‌ای را مقایسه می‌کند.

```cpp
static bool System::TestCompare::AreEqual(const System::Collections::Specialized::StringCollectionPtr &arrA, const System::Collections::Specialized::StringCollectionPtr &arrB)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| arrA | const [System::Collections::Specialized::StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)\& | مجموعه سمت چپ. |
| arrB | const [System::Collections::Specialized::StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)\& | مجموعه سمت راست. |

### مقدار بازگشت

True اگر اندازه‌ها و داده‌ها مطابقت داشته باشند، false در غیر این صورت.

## TestCompare::AreEqual(const System::SharedPtr\<SCG::IEnumerable\<T\>\>\&, const System::SharedPtr\<SCG::IEnumerable\<U\>\>\&) method

نمونه‌های IEnumerable را مقایسه می‌کند.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::SharedPtr<SCG::IEnumerable<T>> &et, const System::SharedPtr<SCG::IEnumerable<U>> &eu)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| et | const [System::SharedPtr](../../sharedptr/)\<[SCG::IEnumerable](../../../system.collections.generic/ienumerable/)\<T\>\>\& | شیء قابل شمارش سمت چپ. |
| eu | const [System::SharedPtr](../../sharedptr/)\<[SCG::IEnumerable](../../../system.collections.generic/ienumerable/)\<U\>\>\& | شیء قابل شمارش سمت راست. |

### مقدار بازگشت

True اگر اندازه‌ها و داده‌ها مطابقت داشته باشند، false در غیر این است.

## موارد مرتبط

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