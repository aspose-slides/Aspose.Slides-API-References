---
title: set_Zip64Mode()
second_title: Aspose.Slides مرجع API للغة C++
description: "يحدد ما إذا كان يتم استخدام تنسيق ZIP64 لمستند Presentation. القيمة الافتراضية هي Zip64Mode::IfNecessary"
type: docs
weight: 40
url: /ar/aspose.slides.export/pptxoptions/set_zip64mode/
---
## PptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode) طريقة

يحدد ما إذا كان يتم استخدام تنسيق ZIP64 للمستند [Presentation](../../../aspose.slides/presentation/). القيمة الافتراضية هي [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
void Aspose::Slides::Export::PptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode value) override
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
* نطاق [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)