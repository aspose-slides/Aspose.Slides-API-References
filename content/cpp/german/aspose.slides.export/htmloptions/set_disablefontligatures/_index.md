---
title: set_DisableFontLigatures()
second_title: Aspose.Slides für C++ API-Referenz
description: Legt einen Wert fest, der angibt, ob Text ohne Ligaturen gerendert wird. Wenn auf true gesetzt, werden Ligaturen im gerenderten Output deaktiviert. Standardmäßig ist diese Eigenschaft auf false gesetzt.
type: docs
weight: 105
url: /de/aspose.slides.export/htmloptions/set_disablefontligatures/
---
## HtmlOptions::set_DisableFontLigatures(bool) Methode


Legt einen Wert fest, der angibt, ob Text ohne Ligaturen gerendert wird. Wenn auf **true** gesetzt, werden Ligaturen im gerenderten Output deaktiviert. Standardmäßig ist diese Eigenschaft auf **false** gesetzt.

```cpp
void Aspose::Slides::Export::HtmlOptions::set_DisableFontLigatures(bool value) override
```

## Hinweise


Beispiel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // Ligaturen in der Textdarstellung deaktivieren

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## Siehe auch

* Klasse [HtmlOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)