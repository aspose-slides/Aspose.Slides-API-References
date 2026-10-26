---
title: AddConnector()
second_title: Aspose.Slides برای مرجع API C++
description: یک شکل connector جدید با استایل پیش‌فرض قالب ایجاد می‌کند و آن را به انتهای مجموعهٔ shapes اضافه می‌نماید.
type: docs
weight: 417
url: /fa/aspose.slides/shapecollection/addconnector/
---
## ShapeCollection::AddConnector(ShapeType, float, float, float, float) متد


یک شکل connector جدید با استایل پیش‌فرض قالب ایجاد می‌کند و آن را به انتهای مجموعهٔ shapes اضافه می‌نماید.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) شکل connector برای افزودن. |
| x | **float** | مختصات x فریم connector\\u2019s، به نقطه. |
| y | **float** | مختصات y فریم connector\\u2019s، به نقطه. |
| width | **float** | عرض فریم connector\\u2019s، به نقطه. |
| height | **float** | ارتفاع فریم connector\\u2019s، به نقطه. |

### مقدار بازگشت

[IConnector](../../iconnector/) جدید ایجاد شده.

## توضیحات



مثال زیر نشان می‌دهد چگونه یک connector (یک connector خمیده) بین دو shape (یک بیضی و یک مستطیل) در PowerPoint [Presentation](../../presentation/) اضافه شود. 
```cpp
// یک نمونه از کلاس Presentation را که نمایانگر فایل PPTX است ایجاد می‌کند
auto input = System::MakeObject<Presentation>();

// به مجموعهٔ اشکال اسلاید خاص دسترسی می‌یابد
auto shapes = input->get_Slides()->idx_get(0)->get_Shapes();
// یک شکل خودکار بیضی اضافه می‌کند
System::SharedPtr<IAutoShape> ellipse = shapes->AddAutoShape(ShapeType::Ellipse, 0.0f, 100.0f, 100.0f, 100.0f);
// یک شکل خودکار مستطیل اضافه می‌کند
System::SharedPtr<IAutoShape> rectangle = shapes->AddAutoShape(ShapeType::Rectangle, 100.0f, 300.0f, 100.0f, 100.0f);

// یک شکل connector را به مجموعهٔ اشکال اسلاید اضافه می‌کند
System::SharedPtr<IConnector> connector = shapes->AddConnector(ShapeType::BentConnector2, 0.0f, 0.0f, 10.0f, 10.0f);
// اشکال را با استفاده از connector وصل می‌کند
connector->set_StartShapeConnectedTo(ellipse);
connector->set_EndShapeConnectedTo(rectangle);
// متد reroute را فراخوانی می‌کند که مسیر کوتاه‌ترین خودکار بین اشکال را تنظیم می‌نماید
connector->Reroute();

// ارائه (presentation) را ذخیره می‌کند
input->Save(u"Shapes-connector.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) متد


یک شکل connector جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ shapes اضافه می‌نماید، به‌صورت اختیاری استایل پیش‌فرض قالب را اعمال می‌کند.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) شکل connector برای ایجاد. |
| x | **float** | مختصات x فریم connector\\u2019s، به نقطه. |
| y | **float** | مختصات y فریم connector\\u2019s، به نقطه. |
| width | **float** | عرض فریم connector\\u2019s، به نقطه. |
| height | **float** | ارتفاع فریم connector\\u2019s، به نقطه. |
| createFromTemplate | **bool** | True برای اعمال استایل قالب پیش‌فرض (نام غیر خالی، استایل ساده)؛ false برای ایجاد connector با مقادیر پیش‌فرض property. |

### مقدار بازگشت

[IConnector](../../iconnector/) جدید ایجاد شده.

## موارد مرتبط

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IConnector](../../iconnector/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)