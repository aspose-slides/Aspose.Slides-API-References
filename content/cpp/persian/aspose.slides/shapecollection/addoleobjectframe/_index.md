---
title: AddOleObjectFrame()
second_title: Aspose.Slides برای C++ مرجع API
description: یک قاب شی OLE جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید.
type: docs
weight: 183
url: /fa/aspose.slides/shapecollection/addoleobjectframe/
---
## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) متد

یک قاب شیٔ OLE جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌‎دارد.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | **float** | مختصات x قاب OLE جدید، به نقطه. |
| y | **float** | مختصات y قاب OLE جدید، به نقطه. |
| width | **float** | عرض قاب OLE جدید، به نقطه. |
| height | **float** | ارتفاع قاب OLE جدید، به نقطه. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | اطلاعات دربارهٔ دادهٔ OLE جاسازی‌شده ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### مقدار بازگشتی

[IOleObjectFrame](../../ioleobjectframe/) جدید ایجاد‌شده.

## توضیحات

مثالهای زیر نشان می‌دهند که چگونه قاب‌های شیٔ OLE را به [Slides](../../) در [Presentation](../../presentation/) پاورپوینت اضافه کنیم.
```cpp
auto pres = System::MakeObject<Presentation>();

// به اولین اسلاید دسترسی می‌یابد
auto slide = pres->get_Slides()->idx_get(0);
// یک فایل اکسل را به استریم بارگذاری می‌کند
System::SharedPtr<System::IO::MemoryStream> mstream = System::MakeObject<System::IO::MemoryStream>();
auto fs = System::MakeObject<System::IO::FileStream>(u"book1.xlsx", System::IO::FileMode::Open, System::IO::FileAccess::Read);

System::ArrayPtr<uint8_t> buf = System::MakeArray<uint8_t>(4096, 0);
while (true)
{
    int32_t bytesRead = fs->Read(buf, 0, buf->get_Length());
    if (bytesRead <= 0)
    {
        break;
    }
    mstream->Write(buf, 0, bytesRead);
}

// یک شی داده برای جاسازی ایجاد می‌کند
auto dataInfo = System::MakeObject<OleEmbeddedDataInfo>(mstream->ToArray(), u"xlsx");
// یک فریم شی OLE به شکل‌ها اضافه می‌کند
auto slideSize = pres->get_SlideSize()->get_Size();
auto oleObjectFrame = slide->get_Shapes()->AddOleObjectFrame(0.0f, 0.0f, slideSize.get_Width(), slideSize.get_Height(), dataInfo);
// فایل PPTX را روی دیسک می‌نویسد
pres->Save(u"OleEmbed_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::String, System::String) متد

یک قاب شیٔ OLE جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌‎دارد.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::String className, System::String path) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | **float** | مختصات x قاب OLE جدید، به نقطه. |
| y | **float** | مختصات y قاب OLE جدید، به نقطه. |
| width | **float** | عرض قاب OLE جدید، به نقطه. |
| height | **float** | ارتفاع قاب OLE جدید، به نقطه. |
| className | [System::String](../../../system/string/) | نام کلاس شی OLE. |
| path | [System::String](../../../system/string/) | مسیر به فایل پیوند شده. |

### مقدار بازگشتی

[IOleObjectFrame](../../ioleobjectframe/) جدید ایجاد‌شده.

## توضیحات

این مسیر به‌صورت دقیق در ارائه ذخیره می‌شود. اگر مسیر نسبی مشخص شود، فایل هنگام باز کردن ارائه از یک فهرست متفاوت در دسترس نخواهد بود.

## همچنین

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOleObjectFrame](../../ioleobjectframe/)
* Class [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Class [ShapeCollection](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)