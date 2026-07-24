---
title: set_DisableFontLigatures()
second_title: Aspose.Slides für C++ API-Referenz
description: Legt einen Wert fest, der angibt, ob Text ohne Ligaturen gerendert wird. Wenn er auf true gesetzt ist, werden Ligaturen in der gerenderten Ausgabe deaktiviert. Standardmäßig ist diese Eigenschaft auf false gesetzt.
type: docs
weight: 144
url: /de/aspose.slides.export/ihtml5options/set_disablefontligatures/
---
## IHtml5Options::set_DisableFontLigatures(bool) Methode

Legt einen Wert fest, der angibt, ob Text ohne Ligaturen gerendert wird. Wenn er auf **true** gesetzt ist, werden Ligaturen in der gerenderten Ausgabe deaktiviert. Standardmäßig ist diese Eigenschaft auf **false** gesetzt.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_DisableFontLigatures(bool value)=0
```

## Anmerkungen

Beispiel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // Ligaturen beim Textrendering deaktivieren

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## Siehe auch

* Klasse [IHtml5Options](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)