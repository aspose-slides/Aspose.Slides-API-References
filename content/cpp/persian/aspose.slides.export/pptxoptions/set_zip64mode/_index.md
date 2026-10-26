---
title: set_Zip64Mode()
second_title: مرجع API Aspose.Slides برای C++
description: "مشخص می‌کند که آیا قالب ZIP64 برای سند Presentation استفاده می‌شود. مقدار پیش‌فرض Zip64Mode::IfNecessary است"
type: docs
weight: 40
url: /fa/aspose.slides.export/pptxoptions/set_zip64mode/
---
## PptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode) متد


مشخص می‌کند که آیا فرمت ZIP64 برای سند [Presentation](../../../aspose.slides/presentation/) استفاده می‌شود. مقدار پیش‌فرض [Zip64Mode::IfNecessary](../../zip64mode/) است.

```cpp
void Aspose::Slides::Export::PptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode value) override
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

* عدد [Zip64Mode](../../zip64mode/)
* کلاس [PptxOptions](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)