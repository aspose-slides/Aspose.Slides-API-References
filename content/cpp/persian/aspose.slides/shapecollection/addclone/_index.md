---
title: AddClone()
second_title: Aspose.Slides برای C++ مرجع API
description: یک نسخهٔ کپی از شکل مشخص‌شده ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید.
type: docs
weight: 547
url: /fa/aspose.slides/shapecollection/addclone/
---
## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) متد

یک نسخهٔ کپی از شکل مشخص‌شده ایجاد کرده و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | شکل برای کلون کردن. |
| x | **float** | مختصات x چارچوب شکل جدید، بر حسب پوینت. |
| y | **float** | مختصات y چارچوب شکل جدید، بر حسب پوینت. |
| width | **float** | عرض چارچوب شکل جدید، بر حسب پوینت. |
| height | **float** | ارتفاع چارچوب شکل جدید، بر حسب پوینت. |

### مقدار بازگشت

شیء تازه ایجاد‌شده [IShape](../../ishape/).

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float) متد

یک نسخهٔ کپی از شکل مشخص‌شده ایجاد کرده و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. شکل جدید عرض و ارتفاع *sourceShape* را حفظ می‌کند.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | شکل برای کلون کردن. |
| x | **float** | مختصات x چارچوب شکل جدید، بر حسب پوینت. |
| y | **float** | مختصات y چارچوب شکل جدید، بر حسب پوینت. |

### مقدار بازگشت

شیء تازه ایجاد‌شده [IShape](../../ishape/).

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>) متد

یک نسخهٔ کپی از شکل مشخص‌شده ایجاد کرده و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. شکل کلون‌شده موقعیت و اندازهٔ اصلی را حفظ می‌کند.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) برای کلون کردن. |

### مقدار بازگشت

شیء تازه ایجاد‌شده [IShape](../../ishape/).

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShape](../../ishape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)