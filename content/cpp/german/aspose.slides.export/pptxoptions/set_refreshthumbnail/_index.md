---
title: set_RefreshThumbnail()
second_title: Aspose.Slides für C++ API Referenz
description: Gibt an, ob das Vorschaubild der Präsentation aktualisiert wird. Schreiben bool. Standardwert ist true.
type: docs
weight: 66
url: /de/aspose.slides.export/pptxoptions/set_refreshthumbnail/
---
## PptxOptions::set_RefreshThumbnail(bool) Methode


Gibt an, ob das Vorschaubild der Präsentation aktualisiert wird. Schreiben **bool**. Standardwert ist **true**.

```cpp
void Aspose::Slides::Export::PptxOptions::set_RefreshThumbnail(bool value) override
```

## Anmerkungen


Wenn der Optionswert **true** ist, wird das neue Vorschaubild erzeugt.

Wenn der Optionswert **false** ist, wird das aktuelle Vorschaubild unverändert gespeichert.

Beispiel:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## Siehe auch

* Klasse [PptxOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)