---
title: TestCompare
second_title: مرجع API لـ Aspose.Slides للغة C++
description: هيكل خدمة يوفر واجهة لمقارنة المجموعات.
type: docs
weight: 1912
url: /ar/system/testcompare/
---
## TestCompare بنية

هيكل خدمة يوفر واجهة لمقارنة المجموعات.

```cpp
class TestCompare
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| static **bool** [AbstractEqual](./abstractequal/)([SCG::ICollection](../../system.collections.generic/icollection/)\<T\> *const, [SCG::ICollection](../../system.collections.generic/icollection/)\<T\> *const) | يقارن مجموعتين من نوع غير معروف. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<U\>\>\&) | يقارن مصفوفات غير مؤشرات. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<[SharedPtr](../sharedptr/)\<T\>\>\>\&, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<[SharedPtr](../sharedptr/)\<U\>\>\>\&) | يقارن مصفوفات مؤشرات. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::List](../../system.collections.generic/list/)\<T\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::List](../../system.collections.generic/list/)\<U\>\>\&) | يقارن قوائم غير مؤشرات. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::List](../../system.collections.generic/list/)\<[SharedPtr](../sharedptr/)\<T\>\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::List](../../system.collections.generic/list/)\<[SharedPtr](../sharedptr/)\<U\>\>\>\&) | يقارن قوائم مؤشرات. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::List](../../system.collections.generic/list/)\<T\>\>\&, const [System::ArrayPtr](../arrayptr/)\<U\>\&) | يقارن القوائم مع المصفوفات في حالة عناصر غير مؤشرات. |
| static **bool** [AreEqual](./areequal/)(const [System::ArrayPtr](../arrayptr/)\<T\>\&, const [SharedPtr](../sharedptr/)\<[SCG::List](../../system.collections.generic/list/)\<U\>\>\&) | يقارن القوائم مع المصفوفات في حالة عناصر غير مؤشرات. |
| static **bool** [AreEqual](./areequal/)(const [System::ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<T\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::List](../../system.collections.generic/list/)\<[SharedPtr](../sharedptr/)\<U\>\>\>\&) | يقارن القوائم مع المصفوفات في حالة عناصر مؤشرات. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::List](../../system.collections.generic/list/)\<[SharedPtr](../sharedptr/)\<T\>\>\>\&, const [System::ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<U\>\>\&) | يقارن القوائم مع المصفوفات في حالة عناصر مؤشرات. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::Dictionary](../../system.collections.generic/dictionary/)\<K, U\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::Dictionary](../../system.collections.generic/dictionary/)\<K, U\>\>\&) | يقارن القواميس غير المؤشرات لأنواع مخططة. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::Dictionary](../../system.collections.generic/dictionary/)\<K, [SharedPtr](../sharedptr/)\<U\>\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::Dictionary](../../system.collections.generic/dictionary/)\<K, [SharedPtr](../sharedptr/)\<U\>\>\>\&) | يقارن القواميس المؤشرات لأنواع مخططة. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::Dictionary](../../system.collections.generic/dictionary/)\<K1, U1\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::Dictionary](../../system.collections.generic/dictionary/)\<K2, U2\>\>\&) | يقارن القواميس لأنواع مختلفة. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::HashSet](../../system.collections.generic/hashset/)\<T\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::HashSet](../../system.collections.generic/hashset/)\<U\>\>\&) | يقارن مجموعات التجزئة غير المؤشرات. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::HashSet](../../system.collections.generic/hashset/)\<[SharedPtr](../sharedptr/)\<T\>\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::HashSet](../../system.collections.generic/hashset/)\<[SharedPtr](../sharedptr/)\<U\>\>\>\&) | يقارن مجموعات التجزئة المؤشرات. |
| static **bool** [AreEqual](./areequal/)(const [SCG::QueuePtr](../../system.collections.generic/queueptr/)\<T\>\&, const [SCG::QueuePtr](../../system.collections.generic/queueptr/)\<U\>\&) | يقارن الطوابير غير المؤشرات. |
| static **bool** [AreEqual](./areequal/)(const [SCG::QueuePtr](../../system.collections.generic/queueptr/)\<[SharedPtr](../sharedptr/)\<T\>\>\&, const [SCG::QueuePtr](../../system.collections.generic/queueptr/)\<[SharedPtr](../sharedptr/)\<U\>\>\&) | يقارن الطوابير المؤشرات. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::Stack](../../system.collections.generic/stack/)\<T\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::Stack](../../system.collections.generic/stack/)\<U\>\>\&) | يقارن المكدسات غير المؤشرات. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::Stack](../../system.collections.generic/stack/)\<[SharedPtr](../sharedptr/)\<T\>\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::Stack](../../system.collections.generic/stack/)\<[SharedPtr](../sharedptr/)\<U\>\>\>\&) | يقارن المكدسات المؤشرات. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, U\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, U\>\>\&) | يقارن القواميس المرتبة غير المؤشرات لأنواع مخططة. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../sharedptr/)\<U\>\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../sharedptr/)\<U\>\>\>\&) | يقارن القواميس المرتبة المؤشرات لأنواع مخططة. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K1, U1\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K2, U2\>\>\&) | يقارن القواميس المرتبة لأنواع مختلفة. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::SortedList](../../system.collections.generic/sortedlist/)\<K, U\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::SortedList](../../system.collections.generic/sortedlist/)\<K, U\>\>\&) | يقارن القوائم المرتبة غير المؤشرات لأنواع مخططة. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::SortedList](../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../sharedptr/)\<U\>\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::SortedList](../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../sharedptr/)\<U\>\>\>\&) | يقارن القوائم المرتبة المؤشرات لأنواع مخططة. |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::SortedList](../../system.collections.generic/sortedlist/)\<K1, U1\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::SortedList](../../system.collections.generic/sortedlist/)\<K2, U2\>\>\&) | يقارن القوائم المرتبة لأنواع مختلفة. |
| static **bool** [AreEqual](./areequal/)(const [System::Collections::Specialized::StringCollectionPtr](../../system.collections.specialized/stringcollectionptr/)\&, const [System::Collections::Specialized::StringCollectionPtr](../../system.collections.specialized/stringcollectionptr/)\&) | يقارن مجموعات السلاسل. |
| static **bool** [AreEqual](./areequal/)(const [System::SharedPtr](../sharedptr/)\<[SCG::IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>\&, const [System::SharedPtr](../sharedptr/)\<[SCG::IEnumerable](../../system.collections.generic/ienumerable/)\<U\>\>\&) | يقارن مثيلات IEnumerable. |

## انظر أيضًا

* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)