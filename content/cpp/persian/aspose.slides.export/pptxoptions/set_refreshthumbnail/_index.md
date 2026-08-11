---
title: set_RefreshThumbnail()
second_title: مرجع API Aspose.Slides برای C++
description: مشخص می‌کند که آیا تصویر کوچک ارائه بازآفرینی شود یا خیر. نوشتن bool. مقدار پیش‌فرض true است.
type: docs
weight: 66
url: /fa/aspose.slides.export/pptxoptions/set_refreshthumbnail/
---
## PptxOptions::set_RefreshThumbnail(bool) متد

مشخص می‌کند که آیا تصویر کوچک ارائه بازآفرینی شود یا خیر. نوشتن **bool**. مقدار پیش‌فرض **true** است.

```cpp
void Aspose::Slides::Export::PptxOptions::set_RefreshThumbnail(bool value) override
```

## توضیحات

وقتی مقدار گزینه **true** باشد، تصویر کوچک جدید تولید خواهد شد.

وقتی مقدار گزینه **false** باشد، تصویر کوچک فعلی همان‌طور ذخیره می‌شود.

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## مراجع

* کلاس [PptxOptions](../)
* فضای نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)