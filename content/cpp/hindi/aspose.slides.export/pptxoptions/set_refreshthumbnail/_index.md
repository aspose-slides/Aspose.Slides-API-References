---
title: set_RefreshThumbnail()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्धारित करता है कि प्रस्तुति थंबनेल को रीफ़्रेश किया जाएगा या नहीं। bool लिखें। डिफ़ॉल्ट मान true है।
type: docs
weight: 66
url: /hi/aspose.slides.export/pptxoptions/set_refreshthumbnail/
---
## PptxOptions::set_RefreshThumbnail(bool) विधि

Specifies whether the presentation thumbnail will be refreshed. Write **bool**. Default value is **true**.

```cpp
void Aspose::Slides::Export::PptxOptions::set_RefreshThumbnail(bool value) override
```

## टिप्पणी

When the option value is **true**, the new thumbnail will be generated.

When the option value is **false**, the current thumbnail will be saved as is.

Example: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## देखें भी

* क्लास [PptxOptions](../)
* नामस्थान [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)