---
title: CollectionAssertHelper
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: واجهة برمجة التطبيقات المساعدة للعمليات المتعلقة بالمجموعات.
type: docs
weight: 1548
url: /ar/system/collectionasserthelper/
---
## CollectionAssertHelper struct

واجهة برمجة التطبيقات للمساعد في عمليات تتعلق بالمجموعات.

```cpp
class CollectionAssertHelper
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| static **bool** [CheckDiffForAll](./checkdiffforall/)(const std::function\<**bool**(int)>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<**int32_t**\>\>\&) | يتحقق من أن جميع عناصر المجموعة تلتزم بالشرط. |
| static **bool** [CheckDiffForAny](./checkdiffforany/)(const std::function\<**bool**(int)>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<**int32_t**\>\>\&) | يتحقق من أن أي عنصر من المجموعة يلتزم بالشرط. |
| static [System::String](../string/) [CollectionsToMsg](./collectionstomsg/)(const [System::String](../string/)\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T1\>\>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T2\>\>\&) | يسلسل مجموعتين لتمثيل الرسالة. |
| static [System::String](../string/) [IEnumerableToStr](./ienumerabletostr/)(const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>\&) | يحول المجموعة إلى سلسلة عبر دمج تمثيلات السلاسل للعناصر. |
| static [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<T1, **int32_t**\>\> [MakeDiff](./makediff/)(const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T1\>\>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T2\>\>\&) | يحسب 'الفرق' بين مجموعتين. لكل عنصر من كل مجموعة باعتباره مفتاحًا، ستكون القيمة الناتجة موجبة إذا ظهر العنصر أكثر مرات في "المتوقعة" مجموعة، وسالبة إذا ظهر أكثر مرات في "الفعلية" مجموعة، وصفرًا إذا ظهر بنفس عدد المرات في كلتا المجموعتين. |
| static [System::String](../string/) [ToFullMessage](./tofullmessage/)(const [System::String](../string/)\&) | يقوم بتنسيق السلسلة لاستخدامها كنص الرسالة. |

## انظر أيضًا

* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)