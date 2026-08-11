---
title: get_CompressionLevel()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: "يحدد مستوى الضغط المستخدم عند حفظ مستند العرض. القيمة الافتراضية هي CompressionLevel::Level6."
type: docs
weight: 79
url: /ar/aspose.slides.export/ipptxoptions/get_compressionlevel/
---
## IPptxOptions::get_CompressionLevel() method

يحدد مستوى الضغط المستخدم عند حفظ مستند العرض. القيمة الافتراضية هي [CompressionLevel::Level6](../../compressionlevel/).

```cpp
virtual Aspose::Slides::Export::CompressionLevel Aspose::Slides::Export::IPptxOptions::get_CompressionLevel()=0
```

## ملاحظات

مستويات الضغط الأعلى تنتج ملفات أصغر ولكنها تتطلب وقت معالجة أكبر. نسبة الضغط الفعلية تعتمد على محتوى العرض. 

مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## انظر أيضًا

* تعداد [CompressionLevel](../../compressionlevel/)
* فئة [IPptxOptions](../)
* نطاق [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)