---
title: AddPictureFrame()
second_title: مرجع API Aspose.Slides برای C++
description: یک فریم تصویر جدید ایجاد می‌کند که تصویر مشخص‌شده را در بر دارد و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید.
type: docs
weight: 404
url: /fa/aspose.slides/ishapecollection/addpictureframe/
---
## IShapeCollection::AddPictureFrame(ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) متد

یک فریم تصویر جدید با تصویر مشخص‌شده ایجاد می‌کند و آن را به انتهای مجموعه اشکال اضافه می‌نماید.

```cpp
virtual System::SharedPtr<IPictureFrame> Aspose::Slides::IShapeCollection::AddPictureFrame(ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
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
| x | **float** | مختصات x فریم تصویر، بر حسب نقطه. |
| y | **float** | مختصات y فریم تصویر، بر حسب نقطه. |
| width | **float** | عرض فریم تصویر، بر حسب نقطه. |
| height | **float** | ارتفاع فریم تصویر، بر حسب نقطه. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | [IPPImage](../../ippimage/) برای نمایش در فریم تصویر. |

### مقدار بازگشتی

[IPictureFrame](../../ipictureframe/) جدید ایجاد شده.

## همچنین ببینید

* شمارش [ShapeType](../../shapetype/)
* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IPictureFrame](../../ipictureframe/)
* کلاس [IPPImage](../../ippimage/)
* کلاس [IShapeCollection](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)