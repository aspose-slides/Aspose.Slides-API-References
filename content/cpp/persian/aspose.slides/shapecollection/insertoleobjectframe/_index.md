---
title: InsertOleObjectFrame()
second_title: Aspose.Slides برای C++ مرجع API
description: یک فریم شیء OLE جدید ایجاد می‌کند و آن را در مجموعه شکل‌ها در اندیس مشخص شده قرار می‌دهد.
type: docs
weight: 196
url: /fa/aspose.slides/shapecollection/insertoleobjectframe/
---
## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) متد

یک فریم شیء OLE جدید ایجاد می‌کند و آن را در مجموعه شکل‌ها در اندیس مشخص قرار می‌دهد.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | اندیس صفر مبنا که فریم OLE را در آن وارد می‌کنید. |
| x | **float** | مختصات x فریم OLE جدید، بر حسب نقطه. |
| y | **float** | مختصات y فریم OLE جدید، بر حسب نقطه. |
| width | **float** | عرض فریم OLE جدید، بر حسب نقطه. |
| height | **float** | ارتفاع فریم OLE جدید، بر حسب نقطه. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | اطلاعات داده‌های جاسازی‌شده OLE ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### مقدار بازگشتی

[IOleObjectFrame](../../ioleobjectframe/) تازه ایجاد شده.

## توضیحات

این مثال نحوه درج یک شیء OLE در اندیس دوم را نشان می‌دهد: 
```cpp
ArrayPtr<uint8_t> fileData = IO::File::ReadAllBytes(u"test.zip");
auto dataInfo = MakeObject<OleEmbeddedDataInfo>(fileData, u"zip");
auto oleObjectFrame = slide->get_Shapes()->InsertOleObjectFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, dataInfo);
```

## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::String, System::String) متد

یک فریم شیء OLE جدید ایجاد می‌کند و آن را در مجموعه شکل‌ها در اندیس مشخص قرار می‌دهد.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::String className, System::String path) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | اندیس صفر مبنا که فریم OLE را در آن وارد می‌کنید. |
| x | **float** | مختصات x فریم OLE جدید، بر حسب نقطه. |
| y | **float** | مختصات y فریم OLE جدید، بر حسب نقطه. |
| width | **float** | عرض فریم OLE جدید، بر حسب نقطه. |
| height | **float** | ارتفاع فریم OLE جدید، بر حسب نقطه. |
| className | [System::String](../../../system/string/) | نام کلاس شیء OLE. |
| path | [System::String](../../../system/string/) | مسیر فایل پیوست شده. |

### مقدار بازگشتی

فریم شیء OLE تازه ایجاد شده.

## توضیحات

این مسیر به همان شکل در ارائه ذخیره می‌شود. اگر مسیر نسبی مشخص شود، فایل هنگام باز کردن ارائه از دایرکتوری دیگری در دسترس نخواهد بود.

## مراجعه

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOleObjectFrame](../../ioleobjectframe/)
* Class [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Class [ShapeCollection](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)