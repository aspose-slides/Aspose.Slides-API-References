---
title: set_RefreshThumbnail()
second_title: Aspose.Slides för C++ API-referens
description: Anger om presentationens miniatyrbild ska uppdateras. Skriv bool. Standardvärdet är true.
type: docs
weight: 66
url: /sv/aspose.slides.export/pptxoptions/set_refreshthumbnail/
---
## PptxOptions::set_RefreshThumbnail(bool) metod


Anger om presentationens miniatyrbild ska uppdateras. Skriv **bool**. Standardvärdet är **true**.

```cpp
void Aspose::Slides::Export::PptxOptions::set_RefreshThumbnail(bool value) override
```

## Anmärkningar


När alternativvärdet är **true**, kommer den nya miniatyrbilden att genereras.

När alternativvärdet är **false**, sparas den befintliga miniatyrbilden som den är.

Exempel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## Se också

* Klass [PptxOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)