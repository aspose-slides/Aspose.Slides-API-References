---
title: get_RefreshThumbnail()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt an, ob das Vorschaubild der Präsentation aktualisiert wird. Lesen bool. Standardwert ist true.
type: docs
weight: 53
url: /de/aspose.slides.export/pptxoptions/get_refreshthumbnail/
---
## PptxOptions::get_RefreshThumbnail() Methode


Gibt an, ob das Präsentations-Vorschaubild aktualisiert wird. Lesen **bool**. Standardwert ist **true**.

```cpp
bool Aspose::Slides::Export::PptxOptions::get_RefreshThumbnail() override
```

## Hinweise


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