---
title: set_RefreshThumbnail()
second_title: Aspose.Slides voor C++ API-referentie
description: Geeft aan of de presentatie-miniatuur wordt vernieuwd. Schrijf bool. Standaardwaarde is true.
type: docs
weight: 66
url: /nl/aspose.slides.export/ipptxoptions/set_refreshthumbnail/
---
## IPptxOptions::set_RefreshThumbnail(bool) method


Geeft aan of de presentatie miniatuur wordt vernieuwd. Schrijf **bool**. Standaardwaarde is **true**.

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_RefreshThumbnail(bool value)=0
```

## Opmerkingen


Wanneer de optie-waarde **true** is, wordt de nieuwe miniatuur gegenereerd.

Wanneer de optie-waarde **false** is, wordt de huidige miniatuur ongewijzigd opgeslagen.

Voorbeeld: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## Zie ook

* Klasse [IPptxOptions](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)