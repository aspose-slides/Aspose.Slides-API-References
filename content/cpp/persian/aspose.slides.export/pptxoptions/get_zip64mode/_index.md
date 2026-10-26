---
title: get_Zip64Mode()
second_title: مرجع API Aspose.Slides برای C++
description: "مشخص می‌کند که آیا قالب ZIP64 برای سند Presentation استفاده می‌شود یا خیر. مقدار پیش‌فرض Zip64Mode::IfNecessary است"
type: docs
weight: 27
url: /fa/aspose.slides.export/pptxoptions/get_zip64mode/
---
## PptxOptions::get_Zip64Mode() متد

مشخص می‌کند که آیا قالب ZIP64 برای سند [Presentation](../../../aspose.slides/presentation/) استفاده می‌شود یا خیر. مقدار پیش‌فرض [Zip64Mode::IfNecessary](../../zip64mode/) است.

```cpp
Aspose::Slides::Export::Zip64Mode Aspose::Slides::Export::PptxOptions::get_Zip64Mode() override
```

## یادداشت‌ها

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_Zip64Mode(Zip64Mode::Always);
pres->Save(u"demo-zip64.pptx", SaveFormat::Pptx, pptxOptions);
```

## موارد مرتبط

* Enum [Zip64Mode](../../zip64mode/)
* کلاس [PptxOptions](../)
* فضای نام [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)