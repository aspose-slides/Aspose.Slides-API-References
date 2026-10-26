---
title: get_CompressionLevel()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يحدد مستوى الضغط المستخدم عند حفظ مستند العرض التقديمي. القيمة الافتراضية هي CompressionLevel::Level6."
type: docs
weight: 79
url: /ar/aspose.slides.export/pptxoptions/get_compressionlevel/
---
## PptxOptions::get_CompressionLevel() method


يحدد مستوى الضغط المستخدم عند حفظ مستند العرض التقديمي. القيمة الافتراضية هي [CompressionLevel::Level6](../../compressionlevel/).

```cpp
Aspose::Slides::Export::CompressionLevel Aspose::Slides::Export::PptxOptions::get_CompressionLevel() override
```

## ملاحظات


مستويات الضغط الأعلى تنتج ملفات أصغر لكنها تتطلب وقت معالجة أكبر. نسبة الضغط الفعلية تعتمد على محتوى العرض التقديمي. 

مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## انظر أيضًا

* Enum [CompressionLevel](../../compressionlevel/)
* فئة [PptxOptions](../)
* فضاء الأسماء [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)