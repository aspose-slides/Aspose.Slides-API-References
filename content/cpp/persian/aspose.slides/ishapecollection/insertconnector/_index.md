---
title: InsertConnector()
second_title: Aspose.Slides برای C++ مرجع API
description: یک شکل اتصال جدید ایجاد می‌کند و آن را در مجموعهٔ اشکال در ایندکس مشخص شده درج می‌کند، استایل پیش‌فرض قالب را اعمال می‌کند.
type: docs
weight: 391
url: /fa/aspose.slides/ishapecollection/insertconnector/
---
## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float) method

یک شکل اتصال جدید ایجاد می‌کند و آن را در مجموعهٔ اشکال در ایندکس مشخص شده درج می‌کند، استایل پیش‌فرض قالب اعمال می‌شود.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | ایندکس صفر-مبنا که در آن شکل اتصال درج می‌شود. |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) شکل اتصال که باید درج شود. |
| x | **float** | مختصات x چارچوب connector\\u2019s، بر حسب نقاط. |
| y | **float** | مختصات y چارچوب connector\\u2019s، بر حسب نقاط. |
| width | **float** | عرض چارچوب connector\\u2019s، بر حسب نقاط. |
| height | **float** | ارتفاع چارچوب connector\\u2019s، بر حسب نقاط. |

### مقدار بازگشت

[IConnector](../../iconnector/) جدید ایجاد شده.

## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float, bool) method

یک شکل اتصال جدید ایجاد می‌کند و آن را در مجموعهٔ اشکال در ایندکس مشخص شده درج می‌کند، به‌صورت اختیاری استایل پیش‌فرض قالب را اعمال می‌کند.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | ایندکس صفر-مبنا که در آن شکل اتصال درج می‌شود. |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) شکل اتصال که باید درج شود. |
| x | **float** | مختصات x چارچوب connector\\u2019s، بر حسب نقاط. |
| y | **float** | مختصات y چارچوب connector\\u2019s، بر حسب نقاط. |
| width | **float** | عرض چارچوب connector\\u2019s، بر حسب نقاط. |
| height | **float** | ارتفاع چارچوب connector\\u2019s، بر حسب نقاط. |
| createFromTemplate | **bool** | True برای اعمال استایل پیش‌فرض قالب (نام غیر خالی، استایل ساده)؛ false برای ایجاد connector با مقادیر پیش‌فرض ویژگی‌ها. |

### مقدار بازگشت

[IConnector](../../iconnector/) جدید ایجاد شده.

## موارد مرتبط

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IConnector](../../iconnector/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)