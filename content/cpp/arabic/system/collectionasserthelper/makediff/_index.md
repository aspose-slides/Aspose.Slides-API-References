---
title: MakeDiff()
second_title: Aspose.Slides لمرجع API C++
description: يحسب 'diff' بين مجموعتين. لكل عنصر من كل مجموعة كمفتاح ستكون القيمة الناتجة موجبة إذا تكرّر العنصر عددًا أكبر في مجموعة \"expected\"، وسالبة إذا تكرّر العنصر عددًا أكبر في مجموعة \"actual\"، وصفر إذا تكرّر العنصر نفس العدد في كلتا المجموعتين.
type: docs
weight: 1
url: /ar/system/collectionasserthelper/makediff/
---
## CollectionAssertHelper::MakeDiff(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T1\>\>\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T2\>\>\&) طريقة

تحسب 'diff' بين مجموعتين. لكل عنصر في كل مجموعة كمفتاح ستكون القيمة الناتجة موجبة إذا تكرّر العنصر أكثر في مجموعة "expected"، وسالبة إذا تكرر العنصر أكثر في مجموعة "actual"، وصفر إذا تكرر العنصر نفس عدد المرات في كل مجموعة.

```cpp
template<typename T1,typename T2> static System::SharedPtr<System::Collections::Generic::Dictionary<T1, int32_t>> System::CollectionAssertHelper::MakeDiff(const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | نوع عنصر مجموعة متوقعة. |
| T2 | نوع عنصر مجموعة فعلية. |

### وسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| expected | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T1\>\>\& | المجموعة المتوقعة. |
| actual | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T2\>\>\& | المجموعة الفعلية. |

### قيمة الإرجاع

خريطة نتائج المقارنة لكل قيمة وفق القواعد المذكورة أعلاه.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../sharedptr/)
* فئة [Dictionary](../../../system.collections.generic/dictionary/)
* فئة [IEnumerable](../../../system.collections.generic/ienumerable/)
* بنية [CollectionAssertHelper](../)
* مساحة الاسم [System](../../)
* مكتبة [Aspose.Slides](../../../)