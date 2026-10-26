---
title: InsertPictureFrame()
second_title: Aspose.Slides برای C++ مرجع API
description: یک فریم تصویر جدید که شامل تصویر مشخص شده است ایجاد می‌کند و آن را در مجموعهٔ اشکال در اندیس مشخص شده وارد می‌کند.
type: docs
weight: 417
url: /fa/aspose.slides/ishapecollection/insertpictureframe/
---
## IShapeCollection::InsertPictureFrame(int32_t, ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) متد

یک فریم تصویر جدید که شامل تصویر مشخص شده است ایجاد می‌کند و آن را در مجموعهٔ اشکال در اندیس مشخص شده وارد می‌کند.

```cpp
virtual System::SharedPtr<IPictureFrame> Aspose::Slides::IShapeCollection::InsertPictureFrame(int32_t index, ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image)=0
```

### آرگومان‌ها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| index | **int32_t** | اندیس مبتنی بر صفر که فریم تصویر در آن درج می‌شود. |
| shapeType | [ShapeType](../../shapetype/) | نوع شکلی که در [ShapeType](../../shapetype/) وجود دارد را مشخص می‌کند، به‌جز تمام انواع خطوط:

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

### مقدار بازگردانده شده

شیء تازه ایجاد شده [IPictureFrame](../../ipictureframe/).

## موارد مرتبط

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IPictureFrame](../../ipictureframe/)
* کلاس [IPPImage](../../ippimage/)
* کلاس [IShapeCollection](../)
* فضای نام [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)