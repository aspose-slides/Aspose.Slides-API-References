---
title: set_DisableFontLigatures()
second_title: Aspose.Slides für C++ API-Referenz
description: Legt einen Wert fest, der angibt, ob Text ohne Ligaturen gerendert wird. Wenn auf true gesetzt, werden Ligaturen in der gerenderten Ausgabe deaktiviert. Standardmäßig ist diese Eigenschaft auf false gesetzt.
type: docs
weight: 196
url: /de/aspose.slides.export/ihtmloptions/set_disablefontligatures/
---
## IHtmlOptions::set_DisableFontLigatures(bool) Methode


Legt einen Wert fest, der angibt, ob Text ohne Ligaturen gerendert wird. Wenn auf **true** gesetzt, werden Ligaturen in der gerenderten Ausgabe deaktiviert. Standardmäßig ist diese Eigenschaft auf **false** gesetzt.

```cpp
virtual void Aspose::Slides::Export::IHtmlOptions::set_DisableFontLigatures(bool value)=0
```

## Anmerkungen


Beispiel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // Ligaturen beim Textrendering deaktivieren

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## Siehe auch

* Klasse [IHtmlOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)