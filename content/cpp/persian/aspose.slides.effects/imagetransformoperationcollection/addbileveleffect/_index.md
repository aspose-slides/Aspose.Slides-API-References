---
title: AddBiLevelEffect()
second_title: Aspose.Slides برای مرجع API C++
description: افکت جدید Bi-Level (black/white) را به انتهای یک مجموعه اضافه می‌کند.
type: docs
weight: 144
url: /fa/aspose.slides.effects/imagetransformoperationcollection/addbileveleffect/
---
## ImageTransformOperationCollection::AddBiLevelEffect(float) method

افزودن افکت دو-سطحی (black/white) جدید به انتهای یک مجموعه.

```cpp
System::SharedPtr<IBiLevel> Aspose::Slides::Effects::ImageTransformOperationCollection::AddBiLevelEffect(float threshold) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| threshold | **float** | آستانه روشنایی برای افکت Bi-Level. مقادیری که بزرگتر یا مساوی آستانه هستند به white تنظیم می‌شوند. مقادیری که کمتر از آستانه هستند به black تنظیم می‌شوند. |

### مقدار بازگشتی

اندیس افکت تصویر جدید در مجموعه.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IBiLevel](../../ibilevel/)
* Class [ImageTransformOperationCollection](../)
* Namespace [Aspose::Slides::Effects](../../)
* Library [Aspose.Slides](../../../)