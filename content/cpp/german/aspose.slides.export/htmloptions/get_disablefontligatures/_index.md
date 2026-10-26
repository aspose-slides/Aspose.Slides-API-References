---
title: get_DisableFontLigatures()
second_title: Aspose.Slides für C++ API Referenz
description: Ermittelt einen Wert, der angibt, ob Text ohne Ligaturen gerendert wird. Wenn auf true gesetzt, werden Ligaturen in der ausgegebenen Darstellung deaktiviert. Standardmäßig ist diese Eigenschaft auf false gesetzt.
type: docs
weight: 92
url: /de/aspose.slides.export/htmloptions/get_disablefontligatures/
---
## HtmlOptions::get_DisableFontLigatures() Methode

Gibt einen Wert zurück, der angibt, ob Text ohne Ligaturen gerendert wird. Wenn auf **true** gesetzt, werden Ligaturen in der ausgegebenen Darstellung deaktiviert. Standardmäßig ist diese Eigenschaft auf **false** gesetzt.

```cpp
bool Aspose::Slides::Export::HtmlOptions::get_DisableFontLigatures() override
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