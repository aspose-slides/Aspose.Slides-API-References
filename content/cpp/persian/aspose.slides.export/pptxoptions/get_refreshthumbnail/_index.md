---
title: get_RefreshThumbnail()
second_title: مرجع API Aspose.Slides برای C++
description: مشخص می‌کند که آیا تصویر کوچک ارائه بازسازی شود یا نه. قابل خواندن bool. مقدار پیش‌فرض true است.
type: docs
weight: 53
url: /fa/aspose.slides.export/pptxoptions/get_refreshthumbnail/
---
## PptxOptions::get_RefreshThumbnail() متد

مشخص می‌کند که آیا تصویر کوچک ارائه بازسازی شود یا نه. قابل خواندن **bool**. مقدار پیش‌فرض **true** است.

```cpp
bool Aspose::Slides::Export::PptxOptions::get_RefreshThumbnail() override
```

## توضیحات

زمانی که مقدار گزینه **true** باشد، تصویر کوچک جدید تولید می‌شود.

زمانی که مقدار گزینه **false** باشد، تصویر کوچک فعلی همان‌گونه ذخیره می‌شود.

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## موارد مرتبط

* کلاس [PptxOptions](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)