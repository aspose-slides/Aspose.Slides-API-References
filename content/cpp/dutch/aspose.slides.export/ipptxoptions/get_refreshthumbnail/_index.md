---
title: get_RefreshThumbnail()
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert of de miniatuur van de presentatie wordt vernieuwd. Lees **bool**. Standaardwaarde is **true**.
type: docs
weight: 53
url: /nl/aspose.slides.export/ipptxoptions/get_refreshthumbnail/
---
## IPptxOptions::get_RefreshThumbnail() methode

Specificeert of de miniatuur van de presentatie wordt vernieuwd. Lees **bool**. Standaardwaarde is **true**.

```cpp
virtual bool Aspose::Slides::Export::IPptxOptions::get_RefreshThumbnail()=0
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
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)