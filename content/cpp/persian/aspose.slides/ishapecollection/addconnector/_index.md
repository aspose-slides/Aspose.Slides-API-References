---
title: AddConnector()
second_title: مرجع API Aspose.Slides برای C++
description: یک شکل اتصال‌دهنده جدید را با استایل پیش‌فرض قالب ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌کند.
type: docs
weight: 378
url: /fa/aspose.slides/ishapecollection/addconnector/
---
## IShapeCollection::AddConnector(ShapeType, float, float, float, float) متد

یک شکل اتصال‌دهندهٔ جدید را با استایل پیش‌فرض قالب ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌کند.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) شکل اتصال‌دهنده برای افزودن. |
| x | **float** | مختصات x قاب اتصال‌دهنده، به پوینت. |
| y | **float** | مختصات y قاب اتصال‌دهنده، به پوینت. |
| width | **float** | عرض قاب اتصال‌دهنده، به پوینت. |
| height | **float** | ارتفاع قاب اتصال‌دهنده، به پوینت. |

### مقدار بازگشت

[IConnector](../../iconnector/) تازه ایجاد شده.

## IShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) متد

یک شکل اتصال‌دهندهٔ جدید را ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌کند، به‌صورت اختیاری استایل پیش‌فرض قالب را اعمال می‌کند.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) شکل اتصال‌دهنده برای ایجاد. |
| x | **float** | مختصات x قاب اتصال‌دهنده، به پوینت. |
| y | **float** | مختصات y قاب اتصال‌دهنده، به پوینت. |
| width | **float** | عرض قاب اتصال‌دهنده، به پوینت. |
| height | **float** | ارتفاع قاب اتصال‌دهنده، به پوینت. |
| createFromTemplate | **bool** | True برای اعمال استایل پیش‌فرض قالب (نام غیر خالی، سبک ساده)؛ false برای ایجاد اتصال‌دهنده با مقادیر پیش‌فرض ویژگی‌ها. |

### مقدار بازگشت

[IConnector](../../iconnector/) تازه ایجاد شده.

## مراجع

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IConnector](../../iconnector/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)