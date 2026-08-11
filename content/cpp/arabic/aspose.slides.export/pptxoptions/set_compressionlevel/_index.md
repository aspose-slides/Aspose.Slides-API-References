---
title: set_CompressionLevel()
second_title: مرجع API Aspose.Slides للـ C++
description: "يحدد مستوى الضغط المستخدم عند حفظ ملف العرض التقديمي. القيمة الافتراضية هي CompressionLevel::Level6."
type: docs
weight: 92
url: /ar/aspose.slides.export/pptxoptions/set_compressionlevel/
---
## PptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel) طريقة

يحدد مستوى الضغط المستخدم عند حفظ ملف العرض التقديمي. القيمة الافتراضية هي [CompressionLevel::Level6](../../compressionlevel/).

```cpp
void Aspose::Slides::Export::PptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel value) override
```

## ملاحظات

المستويات الأعلى للضغط تنتج ملفات أصغر ولكنها تتطلب وقت معالجة أكبر. نسبة الضغط الفعلية تعتمد على محتوى العرض التقديمي.

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## انظر أيضًا

* تعداد [CompressionLevel](../../compressionlevel/)
* فئة [PptxOptions](../)
* نطاق الاسم [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)