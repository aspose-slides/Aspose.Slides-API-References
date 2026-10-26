---
title: InsertClone()
second_title: مرجع API Aspose.Slides برای C++
description: یک نسخه از شکل مشخص‌شده ایجاد می‌کند و آن را در مجموعهٔ شکل‌ها در شاخص مشخص شده درج می‌نماید.
type: docs
weight: 508
url: /fa/aspose.slides/ishapecollection/insertclone/
---
## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float, float, float) method

یک نسخه از شکل مشخص‌شده ایجاد می‌کند و آن را در مجموعهٔ شکل‌ها در شاخص مشخص شده درج می‌نماید.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | اندیس صفرمبنا که در آن شکل کپی‌شده درج می‌شود. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) برای کپی. |
| x | **float** | مختصات x قاب شکل کپی‌شده، به نقاط. |
| y | **float** | مختصات y قاب شکل کپی‌شده، به نقاط. |
| width | **float** | عرض قاب شکل کپی‌شده، به نقاط. |
| height | **float** | ارتفاع قاب شکل کپی‌شده، به نقاط. |

### مقدار بازگشت

[IShape](../../ishape/) جدیداً ایجاد شده.

## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float) method

یک نسخه از شکل مشخص‌شده ایجاد می‌کند و آن را در مجموعهٔ شکل‌ها در شاخص مشخص شده درج می‌نماید. شکل جدید عرض و ارتفاع *sourceShape* را حفظ می‌کند.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | اندیس صفرمبنا که در آن شکل کپی‌شده درج می‌شود. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) برای کپی. |
| x | **float** | مختصات x قاب شکل کپی‌شده، به نقاط. |
| y | **float** | مختصات y قاب شکل کپی‌شده، به نقاط. |

### مقدار بازگشت

[IShape](../../ishape/) جدیداً ایجاد شده.

## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>) method

یک نسخه از شکل مشخص‌شده ایجاد می‌کند و آن را در مجموعهٔ شکل‌ها در شاخص مشخص شده درج می‌نماید. شکل کپی‌شده موقعیت و اندازهٔ اصلی را حفظ می‌کند.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | اندیس صفرمبنا که در آن شکل کپی‌شده درج می‌شود. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) برای کپی. |

### مقدار بازگشت

[IShape](../../ishape/) جدیداً ایجاد شده.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShape](../../ishape/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)