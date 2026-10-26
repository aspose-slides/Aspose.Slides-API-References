---
title: set_DisableFontLigatures()
second_title: Aspose.Slides C++ API referencia
description: Beállít egy értéket, amely megadja, hogy a szöveget ligatúrák használata nélkül jelenítik-e meg. Ha true értékre van állítva, a ligatúrák le lesznek tiltva a megjelenített kimenetben. Alapértelmezés szerint ez a tulajdonság false értékre van állítva.
type: docs
weight: 196
url: /hu/aspose.slides.export/ihtmloptions/set_disablefontligatures/
---
## IHtmlOptions::set_DisableFontLigatures(bool) metódus


Beállít egy értéket, amely megadja, hogy a szöveget ligatúrák használata nélkül jelenítik-e meg. Ha **true** értékre van állítva, a ligatúrák le lesznek tiltva a megjelenített kimenetben. Alapértelmezés szerint ez a tulajdonság **false** értékre van állítva.

```cpp
virtual void Aspose::Slides::Export::IHtmlOptions::set_DisableFontLigatures(bool value)=0
```

## Megjegyzés


Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // Letiltja a ligatúrákat a szöveg megjelenítésében

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## Lásd még

* Osztály [IHtmlOptions](../)
* Névterület [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)