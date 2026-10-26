---
title: InsertPictureFrame()
second_title: Aspose.Slides برای C++ مرجع API
description: یک قاب تصویر جدید حاوی تصویر مشخص ایجاد می‌کند و آن را در مجموعهٔ اشکال در اندیس مشخص درج می‌کند.
type: docs
weight: 456
url: /fa/aspose.slides/shapecollection/insertpictureframe/
---
## ShapeCollection::InsertPictureFrame(int32_t, ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) متد

یک قاب تصویر جدید حاوی تصویر مشخص ایجاد می‌کند و آن را در ShapeCollection در اندیس مشخص درج می‌کند.

```cpp
System::SharedPtr<IPictureFrame> Aspose::Slides::ShapeCollection::InsertPictureFrame(int32_t index, ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | اندیس صفر-محور که قاب تصویر در آن درج می‌شود. |
| shapeType | [ShapeType](../../shapetype/) | نوع شکل موجود در [ShapeType](../../shapetype/) را مشخص می‌کند، به‌جز تمام انواع خطوط:

[ShapeType::Line](../../shapetype/),

[ShapeType::StraightConnector1](../../shapetype/),

[ShapeType::BentConnector2](../../shapetype/),

[ShapeType::BentConnector3](../../shapetype/),

[ShapeType::BentConnector4](../../shapetype/),

[ShapeType::BentConnector5](../../shapetype/),

[ShapeType::CurvedConnector2](../../shapetype/),

[ShapeType::CurvedConnector3](../../shapetype/),

[ShapeType::CurvedConnector4](../../shapetype/),

[ShapeType::CurvedConnector5](../../shapetype/). |
| x | **float** | مختصات x قاب تصویر، بر حسب نقطه. |
| y | **float** | مختصات y قاب تصویر، بر حسب نقطه. |
| width | **float** | عرض قاب تصویر، بر حسب نقطه. |
| height | **float** | ارتفاع قاب تصویر، بر حسب نقطه. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | [IPPImage](../../ippimage/) برای نمایش در قاب تصویر. |

### مقدار بازگشت

[IPictureFrame](../../ipictureframe/) جدید ایجاد شده.

## موارد مرتبط

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPictureFrame](../../ipictureframe/)
* Class [IPPImage](../../ippimage/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)