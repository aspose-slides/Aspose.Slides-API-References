---
title: set_RefreshThumbnail()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt an, ob die Präsentationsminiatur aktualisiert wird. Schreiben Sie bool. Standardwert ist true.
type: docs
weight: 66
url: /de/aspose.slides.export/ipptxoptions/set_refreshthumbnail/
---
## IPptxOptions::set_RefreshThumbnail(bool) Methode

Gibt an, ob die Präsentationsminiatur aktualisiert werden soll. Schreiben Sie **bool**. Standardwert ist **true**.

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_RefreshThumbnail(bool value)=0
```

## Hinweise

Wenn der Optionswert **true** ist, wird die neue Miniatur generiert.

Wenn der Optionswert **false** ist, wird die aktuelle Miniatur unverändert gespeichert.

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