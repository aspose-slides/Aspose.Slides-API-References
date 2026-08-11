---
title: Reorder()
second_title: Aspose.Slides برای C++ مرجع API
description: شکل مشخص شده را به موقعیت جدیدی درون مجموعه شکل‌ها جابه‌جا می‌کند.
type: docs
weight: 300
url: /fa/aspose.slides/ishapecollection/reorder/
---
## IShapeCollection::Reorder(int32_t, System::SharedPtr\<IShape\>) متد

شکل مشخص را به موقعیت جدیدی درون مجموعه شکل‌ها جابه‌جا می‌کند.

```cpp
virtual void Aspose::Slides::IShapeCollection::Reorder(int32_t index, System::SharedPtr<IShape> shape)=0
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | اندیس هدف صفر-مبنایی که شکل در آن قرار خواهد گرفت. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) برای جابه‌جایی در مجموعه. |

## IShapeCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<IShape\>\>\&) متد

شکل‌های مشخص را درون مجموعه شکل‌ها جابه‌جا می‌کند و آنها را از اندیس داده شده قرار می‌دهد.

```cpp
virtual void Aspose::Slides::IShapeCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<IShape>> &shapes)=0
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | اندیس هدف صفر-مبنایی که اولین شکل مشخص در آن قرار خواهد گرفت؛ شکل‌های بعدی به ترتیب ارائه شده دنبال می‌شوند. |
| shapes | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>\>\& | یک یا چند نمونه [IShape](../../ishape/) برای جابه‌جایی در مجموعه. |

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IShape](../../ishape/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)