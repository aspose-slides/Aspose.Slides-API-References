---
title: set_RefreshThumbnail()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد ما إذا كانت الصورة المصغرة للعرض التقديمي سيتم تحديثها. اكتب bool. القيمة الافتراضية هي true.
type: docs
weight: 66
url: /ar/aspose.slides.export/pptxoptions/set_refreshthumbnail/
---
## PptxOptions::set_RefreshThumbnail(bool) طريقة

يحدد ما إذا كان سيتم تحديث صورة العرض المصغرة للعرض التقديمي. اكتب **bool**. القيمة الافتراضية هي **true**.

```cpp
void Aspose::Slides::Export::PptxOptions::set_RefreshThumbnail(bool value) override
```

## ملاحظات

عندما تكون قيمة الخيار **true**، سيتم إنشاء الصورة المصغرة الجديدة.

عندما تكون قيمة الخيار **false**، سيتم حفظ الصورة المصغرة الحالية كما هي.

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## انظر أيضًا

* الفئة [PptxOptions](../)
* مساحة الاسم [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)