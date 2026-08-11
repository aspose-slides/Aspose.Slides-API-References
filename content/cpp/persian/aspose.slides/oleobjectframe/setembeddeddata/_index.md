---
title: SetEmbeddedData()
second_title: مرجع API Aspose.Slides برای C++
description: اطلاعات مربوط به داده‌های جاسازی شده OLE را تنظیم می‌کند.
type: docs
weight: 248
url: /fa/aspose.slides/oleobjectframe/setembeddeddata/
---
## OleObjectFrame::SetEmbeddedData(System::SharedPtr\<IOleEmbeddedDataInfo\>) متد

اطلاعات مربوط به داده‌های جاسازی شده OLE را تنظیم می‌کند.

```cpp
void Aspose::Slides::OleObjectFrame::SetEmbeddedData(System::SharedPtr<IOleEmbeddedDataInfo> embeddedData) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| embeddedData | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | داده‌های جاسازی شده [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/) |

## ملاحظات

این متد ویژگی‌های شیء را برای بازتاب داده‌های جدید تغییر می‌دهد و پرچم IsObjectLink را به مقدار false تنظیم می‌کند، که نشان می‌دهد شیء OLE جاسازی شده است. 

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<OleObjectFrame> oof = System::AsCast<Aspose::Slides::OleObjectFrame>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
if (oof != nullptr)
{
    System::SharedPtr<IOleEmbeddedDataInfo> newData = System::MakeObject<OleEmbeddedDataInfo>(System::IO::File::ReadAllBytes(u"Picture.png"), u"png");
    oof->SetEmbeddedData(newData);
}
```

## مراجع

* نوع تعریف [SharedPtr](../../../system/sharedptr/)
* کلاس [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* کلاس [OleObjectFrame](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)