---
title: Equals()
second_title: مرجع API Aspose.Slides للغة C++
description: يحدد ما إذا كانت المنطقة المحددة مطابقة للمنطقة التي يمثلها الكائن الحالي على سطح الرسم المحدد.
type: docs
weight: 157
url: /ar/system.drawing/region/equals/
---
## Region::Equals(const SharedPtr\<Region\>\&, const SharedPtr\<Graphics\>\&) الطريقة


يحدد ما إذا كانت المنطقة المحددة مطابقة تمامًا للمنطقة التي يمثلها الكائن الحالي على سطح الرسم المحدد.

```cpp
bool System::Drawing::Region::Equals(const SharedPtr<Region> &r, const SharedPtr<Graphics> &g)
```


### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| r | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | المنطقة التي يُقارن معها هذا الكائن |
| g | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | سطح الرسم |

### قيمة الإرجاع

صحيح إذا كان داخل المنطقة المحددة مطابقًا لداخل المنطقة التي يمثلها الكائن الحالي عندما يُطبق التحويل المرتبط بالمعلمة **g**؛ وإلا - خطأ

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* الفئة [Region](../)
* الفئة [Graphics](../../graphics/)
* مساحة الاسم [System::Drawing](../../)
* المكتبة [Aspose.Slides](../../../)