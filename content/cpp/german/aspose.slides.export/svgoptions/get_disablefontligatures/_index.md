---
title: get_DisableFontLigatures()
second_title: Aspose.Slides für C++ API Referenz
description: Ruft einen Wert ab, der angibt, ob Text ohne Verwendung von Ligaturen gerendert wird. Wenn er auf true gesetzt ist, werden Ligaturen in der gerenderten Ausgabe deaktiviert. Standardmäßig ist diese Eigenschaft auf false gesetzt.
type: docs
weight: 326
url: /de/aspose.slides.export/svgoptions/get_disablefontligatures/
---
## SVGOptions::get_DisableFontLigatures() Methode


Ruft einen Wert ab, der angibt, ob Text ohne Verwendung von Ligaturen gerendert wird. Wenn er auf **true** gesetzt ist, werden Ligaturen in der gerenderten Ausgabe deaktiviert. Standardmäßig ist diese Eigenschaft auf **false** gesetzt.

```cpp
bool Aspose::Slides::Export::SVGOptions::get_DisableFontLigatures() override
```

## Hinweise


Beispiel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<SVGOptions> options = System::MakeObject<SVGOptions>();
options->set_DisableFontLigatures(true); // Ligaturen bei der Textdarstellung deaktivieren

System::SharedPtr<System::IO::FileStream> fileStream = System::MakeObject<System::IO::FileStream>(u"slide-0.svg", System::IO::FileMode::Create, System::IO::FileAccess::Write);
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## Siehe auch

* Klasse [SVGOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)