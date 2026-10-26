---
title: get_RefreshThumbnail()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt an, ob das Vorschaubild der Präsentation aktualisiert wird. Lesen bool. Standardwert ist true.
type: docs
weight: 53
url: /de/aspose.slides.export/ipptxoptions/get_refreshthumbnail/
---
## IPptxOptions::get_RefreshThumbnail() Methode


Gibt an, ob das Vorschaubild der Präsentation aktualisiert wird. Lesen **bool**. Standardwert ist **true**.

```cpp
virtual bool Aspose::Slides::Export::IPptxOptions::get_RefreshThumbnail()=0
```

## Anmerkungen


Wenn der Optionswert **true** ist, wird das neue Vorschaubild generiert.

Wenn der Optionswert **false** ist, wird das aktuelle Vorschaubild unverändert gespeichert.

Beispiel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## Siehe auch

* Klasse [IPptxOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)