---
title: get_RefreshThumbnail()
second_title: Aspose.Slides för C++ API-referens
description: Anger huruvida presentationens miniatyrbild ska uppdateras. Läs bool. Standardvärdet är true.
type: docs
weight: 53
url: /sv/aspose.slides.export/pptxoptions/get_refreshthumbnail/
---
## PptxOptions::get_RefreshThumbnail() metod


Anger huruvida presentationens miniatyrbild ska uppdateras. Läs **bool**. Standardvärdet är **true**.

```cpp
bool Aspose::Slides::Export::PptxOptions::get_RefreshThumbnail() override
```

## Anmärkningar


När alternativvärdet är **true**, genereras den nya miniatyrbilden.

När alternativvärdet är **false**, sparas den nuvarande miniatyrbilden som den är.

Exempel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## Se även

* Klass [PptxOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)