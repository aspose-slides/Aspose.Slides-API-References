---
title: get_RefreshThumbnail()
second_title: Aspose.Slides för C++ API-referens
description: Anger om presentationsminiatyren ska uppdateras. Läs bool. Standardvärdet är true.
type: docs
weight: 53
url: /sv/aspose.slides.export/ipptxoptions/get_refreshthumbnail/
---
## IPptxOptions::get_RefreshThumbnail() metod

Anger om presentationsminiatyren ska uppdateras. Läs **bool**. Standardvärdet är **true**.

```cpp
virtual bool Aspose::Slides::Export::IPptxOptions::get_RefreshThumbnail()=0
```

## Anmärkningar

När alternativvärdet är **true**, kommer den nya miniatyren att genereras.

När alternativvärdet är **false**, sparas den aktuella miniatyren som den är.

Exempel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## Se även

* Klass [IPptxOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)