---
title: AddOleObjectFrame()
second_title: Aspose.Slides برای C++ مرجع API
description: یک قاب شیء OLE جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید.
type: docs
weight: 66
url: /fa/aspose.slides/ishapecollection/addoleobjectframe/
---
## IShapeCollection::AddOleObjectFrame(float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) متد


یک قاب شیء OLE جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | **float** | مختصات x قاب OLE جدید، بر حسب نقطه. |
| y | **float** | مختصات y قاب OLE جدید، بر حسب نقطه. |
| width | **float** | عرض قاب OLE جدید، بر حسب نقطه. |
| height | **float** | ارتفاع قاب OLE جدید، بر حسب نقطه. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | اطلاعات دادهٔ جاسازی‌شدهٔ OLE ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### مقدار برگشتی

[IOleObjectFrame](../../ioleobjectframe/) جدید ساخته‌شده.

## IShapeCollection::AddOleObjectFrame(float, float, float, float, System::String, System::String) متد


یک قاب شیء OLE جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::String className, System::String path)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | **float** | مختصات x قاب OLE جدید، بر حسب نقطه. |
| y | **float** | مختصات y قاب OLE جدید، بر حسب نقطه. |
| width | **float** | عرض قاب OLE جدید، بر حسب نقطه. |
| height | **float** | ارتفاع قاب OLE جدید، بر حسب نقطه. |
| className | [System::String](../../../system/string/) | نام کلاس شیء OLE. |
| path | [System::String](../../../system/string/) | مسیر به فایل پیوست شده. |

### مقدار برگشتی

[IOleObjectFrame](../../ioleobjectframe/) جدید ساخته‌شده.
## ملاحظات



این مسیر به همان شکل در ارائه ذخیره می‌شود. اگر مسیری نسبی مشخص شود، هنگام باز کردن ارائه از دایرکتوری متفاوت، فایل قابل دسترسی نخواهد بود.

## مراجع مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOleObjectFrame](../../ioleobjectframe/)
* Class [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Class [IShapeCollection](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)