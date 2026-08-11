---
title: get_RefreshThumbnail()
second_title: Aspose.Slides لـ C++ مرجع API
description: يحدد ما إذا كان سيتم تحديث صورة العرض المصغرة للعرض التقديمي. قراءة bool. القيمة الافتراضية هي true.
type: docs
weight: 53
url: /ar/aspose.slides.export/pptxoptions/get_refreshthumbnail/
---
## PptxOptions::get_RefreshThumbnail() طريقة

Specifies whether the presentation thumbnail will be refreshed. Read **bool**. Default value is **true**.

```cpp
bool Aspose::Slides::Export::PptxOptions::get_RefreshThumbnail() override
```

## ملاحظات

When the option value is **true**, the new thumbnail will be generated.

When the option value is **false**, the current thumbnail will be saved as is.

مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## انظر أيضًا

* الفئة [PptxOptions](../)
* النطاق [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)