---
title: get_Zip64Mode()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يحدد ما إذا كان يتم استخدام تنسيق ZIP64 لمستند Presentation. القيمة الافتراضية هي Zip64Mode::IfNecessary"
type: docs
weight: 27
url: /ar/aspose.slides.export/pptxoptions/get_zip64mode/
---
## PptxOptions::get_Zip64Mode() طريقة


يحدد ما إذا كان يتم استخدام تنسيق ZIP64 لمستند [Presentation](../../../aspose.slides/presentation/). القيمة الافتراضية هي [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
Aspose::Slides::Export::Zip64Mode Aspose::Slides::Export::PptxOptions::get_Zip64Mode() override
```

## ملاحظات


مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_Zip64Mode(Zip64Mode::Always);
pres->Save(u"demo-zip64.pptx", SaveFormat::Pptx, pptxOptions);
```

## انظر أيضًا

* تعداد [Zip64Mode](../../zip64mode/)
* فئة [PptxOptions](../)
* مساحة اسم [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)