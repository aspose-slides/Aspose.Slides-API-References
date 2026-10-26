---
title: set_RefreshThumbnail()
second_title: Aspose.Slides برای C++ مرجع API
description: مشخص می‌کند که آیا تصویر بندانگشتی ارائه تازه شود یا نه. نوشتن bool. مقدار پیش‌فرض true است.
type: docs
weight: 66
url: /fa/aspose.slides.export/ipptxoptions/set_refreshthumbnail/
---
## IPptxOptions::set_RefreshThumbnail(bool) متد


مشخص می‌کند که آیا تصویر بندانگشتی ارائه تازه شود یا نه. نوشتن **bool**. مقدار پیش‌فرض **true** است.

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_RefreshThumbnail(bool value)=0
```

## توضیحات


زمانی که مقدار گزینه **true** باشد، تصویر بندانگشتی جدید تولید خواهد شد.

زمانی که مقدار گزینه **false** باشد، تصویر بندانگشتی فعلی همان‌گونه ذخیره می‌شود.

مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## مراجع مرتبط

* کلاس [IPptxOptions](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)