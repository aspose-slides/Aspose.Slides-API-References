---
title: set_RefreshThumbnail()
second_title: Aspose.Slides voor C++ API Referentie
description: Specificeert of de presentatiethumbnail wordt ververst. Schrijf bool. Standaardwaarde is true.
type: docs
weight: 66
url: /nl/aspose.slides.export/pptxoptions/set_refreshthumbnail/
---
## PptxOptions::set_RefreshThumbnail(bool) methode


Specificeert of de presentatiethumbnail wordt ververst. Schrijf **bool**. Standaardwaarde is **true**.

```cpp
void Aspose::Slides::Export::PptxOptions::set_RefreshThumbnail(bool value) override
```

## Opmerkingen


Wanneer de optie-waarde **true** is, wordt de nieuwe thumbnail gegenereerd.

Wanneer de optie-waarde **false** is, wordt de huidige thumbnail opgeslagen zoals hij is.

Voorbeeld: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## Zie ook

* Klasse [PptxOptions](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)