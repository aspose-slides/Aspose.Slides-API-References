---
title: set_RefreshThumbnail()
second_title: Aspose.Slides för C++ API-referens
description: Anger om presentationsminiatyren ska uppdateras. Skriv bool. Standardvärdet är true.
type: docs
weight: 66
url: /sv/aspose.slides.export/ipptxoptions/set_refreshthumbnail/
---
## IPptxOptions::set_RefreshThumbnail(bool) metod

Anger om presentationsminiatyren ska uppdateras. Skriv **bool**. Standardvärdet är **true**.

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_RefreshThumbnail(bool value)=0
```

## Anmärkningar

När alternativvärdet är **true**, genereras den nya miniatyren.

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