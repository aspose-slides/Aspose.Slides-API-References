---
title: get_Zip64Mode()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يحدد ما إذا تم استخدام تنسيق ZIP64 لمستند العرض التقديمي. القيمة الافتراضية هي Zip64Mode::IfNecessary"
type: docs
weight: 27
url: /ar/aspose.slides.export/ipptxoptions/get_zip64mode/
---
## IPptxOptions::get_Zip64Mode() طريقة

يحدد ما إذا تم استخدام تنسيق ZIP64 للمستند [Presentation](../../../aspose.slides/presentation/). القيمة الافتراضية هي [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
virtual Aspose::Slides::Export::Zip64Mode Aspose::Slides::Export::IPptxOptions::get_Zip64Mode()=0
```

## ملاحظات

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_Zip64Mode(Zip64Mode::Always);
pres->Save(u"demo-zip64.pptx", SaveFormat::Pptx, pptxOptions);
```

## انظر أيضاً

* تعداد [Zip64Mode](../../zip64mode/)
* فئة [IPptxOptions](../)
* مساحة الاسم [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)