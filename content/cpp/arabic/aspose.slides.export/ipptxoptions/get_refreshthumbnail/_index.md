---
title: get_RefreshThumbnail()
second_title: مرجع API ‎لـ Aspose.Slides للغة C++
description: يحدد ما إذا كانت الصورة المصغرة للعرض التقديمي ستُعاد تحديثها. قراءة bool. القيمة الافتراضية هي true.
type: docs
weight: 53
url: /ar/aspose.slides.export/ipptxoptions/get_refreshthumbnail/
---
## IPptxOptions::get_RefreshThumbnail() method


Specifies whether the presentation thumbnail will be refreshed. Read **bool**. Default value is **true**.

```cpp
virtual bool Aspose::Slides::Export::IPptxOptions::get_RefreshThumbnail()=0
```

## ملاحظات


عند كون قيمة الخيار **true**، سيتم إنشاء الصورة المصغرة الجديدة.

عند كون قيمة الخيار **false**، سيتم حفظ الصورة المصغرة الحالية كما هي.

مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## انظر أيضًا

* الفئة [IPptxOptions](../)
* مساحة الاسم [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)