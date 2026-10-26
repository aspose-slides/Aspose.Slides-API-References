---
title: InsertConnector()
second_title: Aspose.Slides برای C++ مرجع API
description: یک شکل اتصال جدید ایجاد می‌کند و آن را در مجموعهٔ شکل‌ها در اندیس مشخص‌شده وارد می‌نماید، استایل پیش‌فرض الگو را اعمال می‌کند.
type: docs
weight: 430
url: /fa/aspose.slides/shapecollection/insertconnector/
---
## ShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float) method

یک شکل اتصال جدید ایجاد می‌کند و آن را در مجموعهٔ شکل‌ها در اندیس مشخص‌شده وارد می‌نماید، به‌صورت پیش‌فرض استایل الگو را اعمال می‌کند.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | اندیس صفر-محور که شکل اتصال در آن وارد می‌شود. |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) شکل اتصال برای وارد کردن. |
| x | **float** | مختصات x قاب اتصال، به پوینت. |
| y | **float** | مختصات y قاب اتصال، به پوینت. |
| width | **float** | عرض قاب اتصال، به پوینت. |
| height | **float** | ارتفاع قاب اتصال، به پوینت. |

### مقدار بازگشت

[IConnector](../../iconnector/) تازه ایجاد شده.

## ShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float, bool) method

یک شکل اتصال جدید ایجاد می‌کند و آن را در مجموعهٔ شکل‌ها در اندیس مشخص‌شده وارد می‌نماید، به‌صورت اختیاری استایل پیش‌فرض الگو را اعمال می‌کند.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | اندیس صفر-محور که شکل اتصال در آن وارد می‌شود. |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) شکل اتصال برای وارد کردن. |
| x | **float** | مختصات x قاب اتصال، به پوینت. |
| y | **float** | مختصات y قاب اتصال، به پوینت. |
| width | **float** | عرض قاب اتصال، به پوینت. |
| height | **float** | ارتفاع قاب اتصال، به پوینت. |
| createFromTemplate | **bool** | True برای اعمال استایل پیش‌فرض الگو (نام غیرخالی، سبک ساده)؛ false برای ایجاد اتصال با مقادیر پیش‌فرض ویژگی‌ها. |

### مقدار بازگشت

[IConnector](../../iconnector/) تازه ایجاد شده.

## موارد مرتبط

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IConnector](../../iconnector/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)