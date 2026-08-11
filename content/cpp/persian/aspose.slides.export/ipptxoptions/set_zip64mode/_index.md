---
title: set_Zip64Mode()
second_title: Aspose.Slides برای C++ API مرجع
description: "مشخص می‌کند که آیا فرمت ZIP64 برای سند ارائه استفاده می‌شود یا خیر. مقدار پیش‌فرض Zip64Mode::IfNecessary است"
type: docs
weight: 40
url: /fa/aspose.slides.export/ipptxoptions/set_zip64mode/
---
## IPptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode) متد

مشخص می‌کند که آیا فرمت ZIP64 برای سند [Presentation](../../../aspose.slides/presentation/) استفاده می‌شود یا خیر. مقدار پیش‌فرض [Zip64Mode::IfNecessary](../../zip64mode/) است.

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode value)=0
```

## توضیحات

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_Zip64Mode(Zip64Mode::Always);
pres->Save(u"demo-zip64.pptx", SaveFormat::Pptx, pptxOptions);
```

## موارد مرتبط

* Enum [Zip64Mode](../../zip64mode/)
* کلاس [IPptxOptions](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)