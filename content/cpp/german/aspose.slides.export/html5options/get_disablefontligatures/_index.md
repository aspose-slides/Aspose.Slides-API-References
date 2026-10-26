---
title: get_DisableFontLigatures()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt einen Wert, der angibt, ob Text ohne Ligaturen gerendert wird. Wenn er auf true gesetzt ist, werden Ligaturen in der Ausgabe deaktiviert. Standardmäßig ist diese Eigenschaft auf false gesetzt.
type: docs
weight: 131
url: /de/aspose.slides.export/html5options/get_disablefontligatures/
---
## Html5Options::get_DisableFontLigatures() Methode


Ermittelt einen Wert, der angibt, ob Text ohne Ligaturen gerendert wird. Wenn er auf **true** gesetzt ist, werden Ligaturen in der Ausgabe deaktiviert. Standardmäßig ist diese Eigenschaft auf **false** gesetzt.

```cpp
bool Aspose::Slides::Export::Html5Options::get_DisableFontLigatures() override
```

## Hinweise

Beispiel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // Ligaturen bei der Textdarstellung deaktivieren

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## Siehe auch

* Klasse [Html5Options](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)