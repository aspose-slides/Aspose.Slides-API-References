---
title: Equals()
second_title: Aspose.Slides لمرجع API الخاص بـ C++
description: يحدد ما إذا كانت مثيلتا IBaseSlide متساويتين. يتم حساب قيمة الإرجاع بناءً على بنية الشريحة والمحتوى الثابت. تكون الشريحتان متساويتين إذا كانت جميع الأشكال والأنماط والنصوص والرسوم المتحركة والإعدادات الأخرى، إلخ، متساوية. لا تأخذ المقارنة في الاعتبار قيم المعرفات الفريدة، مثل SlideId، والمحتوى الديناميكي، مثل قيمة التاريخ الحالية في عنصر نائب للتاريخ.
type: docs
weight: 183
url: /ar/aspose.slides/ibaseslide/equals/
---
## IBaseSlide::Equals(System::SharedPtr\<IBaseSlide\>) طريقة

تحدد ما إذا كانت مثيلتا [IBaseSlide](../) متساويتين. يتم حساب قيمة الإرجاع بناءً على بنية الشريحة والمحتوى الثابت. تكون الشريحتان متساويتين إذا كانت جميع الأشكال والأنماط والنصوص والرسوم المتحركة والإعدادات الأخرى، إلخ، متساوية. لا يأخذ المقارنة في الاعتبار قيم المعرفات الفريدة، مثل SlideId، والمحتوى الديناميكي، مثل قيمة التاريخ الحالي في Date [Placeholder](../../placeholder/).

```cpp
virtual bool Aspose::Slides::IBaseSlide::Equals(System::SharedPtr<IBaseSlide> slide)=0
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../)\> | [IBaseSlide](../) للمقارنة مع [IBaseSlide](../) الحالي. |

### قيمة الإرجاع

**true** إذا كان [IBaseSlide](../) المحدد يساوي [IBaseSlide](../) الحالي؛ وإلا، **false**.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IBaseSlide](../)
* فضاء الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)