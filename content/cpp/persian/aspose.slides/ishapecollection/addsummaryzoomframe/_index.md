---
title: AddSummaryZoomFrame()
second_title: مرجع API Aspose.Slides برای C++
description: یک قاب زوم خلاصه جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌نماید.
type: docs
weight: 144
url: /fa/aspose.slides/ishapecollection/addsummaryzoomframe/
---
## IShapeCollection::AddSummaryZoomFrame(float, float, float, float) متد

یک قاب زوم خلاصه جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌نماید.

```cpp
virtual System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::IShapeCollection::AddSummaryZoomFrame(float x, float y, float width, float height)=0
```


### آرگومان‌ها

| پارامتر | نوع | توصیف |
| --- | --- | --- |
| x | **float** | مختصات x قاب زوم خلاصهٔ جدید، به نقطه. |
| y | **float** | مختصات y قاب زوم خلاصهٔ جدید، به نقطه. |
| width | **float** | عرض قاب زوم خلاصهٔ جدید، به نقطه. |
| height | **float** | ارتفاع قاب زوم خلاصهٔ جدید، به نقطه. |

### مقدار بازگشت

[ISummaryZoomFrame](../../isummaryzoomframe/) جدید ایجاد شده.

## توضیحات

این متد یک قاب زوم خلاصه ایجاد می‌کند که پیوندهای خلاصهٔ تمام بخش‌های ارائه را تجمیع می‌نماید.

این مثال افزودن یک شیء زوم خلاصه را به انتهای یک مجموعه نشان می‌دهد (فرض کنید در ارائهٔ "Presentation.pptx" حداقل دو بخش وجود دارد):
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSummaryZoomFrame(150.0f, 20.0f, 500.0f, 250.0f);
```


## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISummaryZoomFrame](../../isummaryzoomframe/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)