---
title: get_RefreshThumbnail()
second_title: Aspose.Slides برای C++ مرجع API
description: مشخص می‌کند که آیا تصویر بندانگشتی ارائه بازآفرینی شود یا خیر. نوع خواندنی bool. مقدار پیش‌فرض true است.
type: docs
weight: 53
url: /fa/aspose.slides.export/ipptxoptions/get_refreshthumbnail/
---
## IPptxOptions::get_RefreshThumbnail() متد


مشخص می‌کند که آیا تصویر بندانگشتی ارائه بازآفرینی شود یا خیر. خواندنی **bool**. مقدار پیش‌فرض **true** است.

```cpp
virtual bool Aspose::Slides::Export::IPptxOptions::get_RefreshThumbnail()=0
```

## توضیحات


هنگامی که مقدار گزینه **true** باشد، تصویر بندانگشتی جدید تولید می‌شود.

هنگامی که مقدار گزینه **false** باشد، تصویر بندانگشتی فعلی همان‌گونه ذخیره می‌شود.

مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## موارد مرتبط

* کلاس [IPptxOptions](../)
* فضای نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)