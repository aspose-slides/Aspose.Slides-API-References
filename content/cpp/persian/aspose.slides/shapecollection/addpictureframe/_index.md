---
title: AddPictureFrame()
second_title: مرجع API Aspose.Slides برای C++
description: یک فریم تصویر جدید حاوی تصویر مشخص شده ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید.
type: docs
weight: 443
url: /fa/aspose.slides/shapecollection/addpictureframe/
---
## ShapeCollection::AddPictureFrame(ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) متد

یک فریم تصویر جدید حاوی تصویر مشخص شده ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید.

```cpp
System::SharedPtr<IPictureFrame> Aspose::Slides::ShapeCollection::AddPictureFrame(ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | نوع شکل موجود در [ShapeType](../../shapetype/) را مشخص می‌کند، به‌جز تمامی انواع خطوط:

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
| x | **float** | مختصات x فریم تصویر، به پوینت. |
| y | **float** | مختصات y فریم تصویر، به پوینت. |
| width | **float** | عرض فریم تصویر، به پوینت. |
| height | **float** | ارتفاع فریم تصویر، به پوینت. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | [IPPImage](../../ippimage/) برای نمایش در فریم تصویر. |

### مقدار بازگشت

[IPictureFrame](../../ipictureframe/) تازه‌سازده شده.

## همچنین ببینید

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IPictureFrame](../../ipictureframe/)
* کلاس [IPPImage](../../ippimage/)
* کلاس [ShapeCollection](../)
* فضای‌نام [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)