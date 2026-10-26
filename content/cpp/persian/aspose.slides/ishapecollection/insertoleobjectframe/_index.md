---
title: InsertOleObjectFrame()
second_title: Aspose.Slides برای C++ مرجع API
description: یک چارچوب شیء OLE جدید ایجاد می‌کند و آن را در مجموعه شکل‌ها در اندیس مشخص شده درج می‌کند.
type: docs
weight: 79
url: /fa/aspose.slides/ishapecollection/insertoleobjectframe/
---
## IShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) متد

یک چارچوب شیء OLE جدید ایجاد می‌کند و آن را در مجموعه شکل‌ها در شاخص مشخص شده درج می‌کند.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | اندیس صفر-پایه‌ای که چارچوب شیء OLE در آن درج می‌شود. |
| x | **float** | مختصات x چارچوب OLE جدید، بر حسب نقطه. |
| y | **float** | مختصات y چارچوب OLE جدید، بر حسب نقطه. |
| width | **float** | عرض چارچوب OLE جدید، بر حسب نقطه. |
| height | **float** | ارتفاع چارچوب OLE جدید، بر حسب نقطه. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | اطلاعات داده‌های توکار OLE ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### مقدار بازگشت

[IOleObjectFrame](../../ioleobjectframe/) تازه ایجاد شده.

## IShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::String, System::String) متد

یک چارچوب شیء OLE جدید ایجاد می‌کند و آن را در مجموعه شکل‌ها در شاخص مشخص شده درج می‌کند.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::String className, System::String path)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | اندیس صفر-پایه‌ای که چارچوب شیء OLE در آن درج می‌شود. |
| x | **float** | مختصات x چارچوب OLE جدید، بر حسب نقطه. |
| y | **float** | مختصات y چارچوب OLE جدید، بر حسب نقطه. |
| width | **float** | عرض چارچوب OLE جدید، بر حسب نقطه. |
| height | **float** | ارتفاع چارچوب OLE جدید، بر حسب نقطه. |
| className | [System::String](../../../system/string/) | نام کلاس شیء OLE. |
| path | [System::String](../../../system/string/) | مسیر به فایل لینک شده. |

### مقدار بازگشت

[IOleObjectFrame](../../ioleobjectframe/) تازه ایجاد شده.

## توضیحات

این مسیر به‌صورت دقیق در ارائه ذخیره می‌شود. اگر مسیر نسبی مشخص شود، هنگام باز کردن ارائه از یک پوشه متفاوت فایل در دسترس نخواهد بود.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IOleObjectFrame](../../ioleobjectframe/)
* کلاس [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* کلاس [IShapeCollection](../)
* کلاس [String](../../../system/string/)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)