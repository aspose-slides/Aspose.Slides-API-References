---
title: get_RefreshThumbnail()
second_title: Aspose.Slides for C++ API-referentie
description: Specificeert of de presentatiethumbnail wordt vernieuwd. Lees bool. Standaardwaarde is true.
type: docs
weight: 53
url: /nl/aspose.slides.export/pptxoptions/get_refreshthumbnail/
---
## PptxOptions::get_RefreshThumbnail() methode

Specificeert of de presentatithumbnail wordt vernieuwd. Lees **bool**. Standaardwaarde is **true**.

```cpp
bool Aspose::Slides::Export::PptxOptions::get_RefreshThumbnail() override
```

## Opmerkingen

Wanneer de optiewaarde **true** is, wordt de nieuwe thumbnail gegenereerd.

Wanneer de optiewaarde **false** is, wordt de huidige thumbnail opgeslagen zoals deze is.

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