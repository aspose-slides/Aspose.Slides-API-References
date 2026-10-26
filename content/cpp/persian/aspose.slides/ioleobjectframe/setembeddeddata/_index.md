---
title: SetEmbeddedData()
second_title: مرجع API Aspose.Slides برای C++
description: اطلاعات درباره داده‌های جاسازی شده OLE را تنظیم می‌کند.
type: docs
weight: 248
url: /fa/aspose.slides/ioleobjectframe/setembeddeddata/
---
## IOleObjectFrame::SetEmbeddedData(System::SharedPtr\<IOleEmbeddedDataInfo\>) متد

اطلاعات درباره داده‌های جاسازی شده OLE را تنظیم می‌کند.

```cpp
virtual void Aspose::Slides::IOleObjectFrame::SetEmbeddedData(System::SharedPtr<IOleEmbeddedDataInfo> embeddedData)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| embeddedData | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | داده‌های جاسازی شده [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/) |

## توضیحات

این متد ویژگی‌های شیء را برای بازتاب داده‌های جدید تغییر می‌دهد و پرچم IsObjectLink را به false تنظیم می‌کند، که نشان می‌دهد شیء OLE جاسازی شده است.

مثال زیر نشان می‌دهد چگونه داده‌های جاسازی شده OLE و نوع آن را برای شیء [IOleObjectFrame](../) موجود تغییر داد
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<OleObjectFrame> oof = System::AsCast<Aspose::Slides::OleObjectFrame>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
if (oof != nullptr)
{
    System::SharedPtr<IOleEmbeddedDataInfo> newData = System::MakeObject<OleEmbeddedDataInfo>(System::IO::File::ReadAllBytes(u"Picture.png"), u"png");
    oof->SetEmbeddedData(newData);
}
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* کلاس [IOleObjectFrame](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)