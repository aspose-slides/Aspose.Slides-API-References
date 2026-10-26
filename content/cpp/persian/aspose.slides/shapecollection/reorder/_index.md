---
title: Reorder()
second_title: Aspose.Slides برای مرجع API C++
description: شکل مشخص‌شده را به موقعیت جدیدی درون مجموعهٔ شکل‌ها منتقل می‌کند.
type: docs
weight: 339
url: /fa/aspose.slides/shapecollection/reorder/
---
## ShapeCollection::Reorder(int32_t, System::SharedPtr\<IShape\>) متد

شکل مشخص‌شده را به موقعیت جدیدی درون مجموعهٔ شکل‌ها منتقل می‌کند.

```cpp
void Aspose::Slides::ShapeCollection::Reorder(int32_t index, System::SharedPtr<IShape> shape) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | اندیس هدف صفر-مبنا که شکل در آن قرار می‌گیرد. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) برای جابجایی در مجموعه. |

## ShapeCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<IShape\>\>\&) متد

شکل‌های مشخص‌شده را درون مجموعهٔ شکل‌ها جابجا می‌کند و آن‌ها را از اندیس داده‌شده شروع می‌کند.

```cpp
void Aspose::Slides::ShapeCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<IShape>> &shapes) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | اندیس هدف صفر-مبنا که اولین شکل مشخص‌شده در آن قرار می‌گیرد؛ شکل‌های بعدی به ترتیب ارائه شده دنبال می‌شوند. |
| shapes | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>\>\& | یک یا چند نمونه [IShape](../../ishape/) برای جابجایی در مجموعه. |

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* کلاس [IShape](../../ishape/)
* کلاس [ShapeCollection](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)