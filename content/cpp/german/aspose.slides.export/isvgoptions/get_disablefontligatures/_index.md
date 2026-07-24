---
title: get_DisableFontLigatures()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt einen Wert zurück, der angibt, ob Text ohne Verwendung von Ligaturen gerendert wird. Wenn er auf true gesetzt ist, werden Ligaturen in der Ausgabe deaktiviert. Standardmäßig ist diese Eigenschaft auf false gesetzt.
type: docs
weight: 326
url: /de/aspose.slides.export/isvgoptions/get_disablefontligatures/
---
## ISVGOptions::get_DisableFontLigatures() Methode

Gibt einen Wert zurück, der angibt, ob Text ohne Verwendung von Ligaturen gerendert wird. Wenn er auf **true** gesetzt ist, werden Ligaturen in der Ausgabe deaktiviert. Standardmäßig ist diese Eigenschaft auf **false** gesetzt.

```cpp
virtual bool Aspose::Slides::Export::ISVGOptions::get_DisableFontLigatures()=0
```

## Anmerkungen

Beispiel:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<SVGOptions> options = System::MakeObject<SVGOptions>();
options->set_DisableFontLigatures(true); // Deaktiviert Ligaturen bei der Textdarstellung

System::SharedPtr<System::IO::FileStream> fileStream = System::MakeObject<System::IO::FileStream>(u"slide-0.svg", System::IO::FileMode::Create, System::IO::FileAccess::Write);
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## Siehe auch

* Klasse [ISVGOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)