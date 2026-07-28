---
title: set_DisableFontLigatures()
second_title: Aspose.Slides C++ API-referencia
description: Egy értéket állít be, amely jelzi, hogy a szöveget ligatúrák használata nélkül renderelik-e. Ha true-ra van állítva, a ligatúrák le lesznek tiltva a megjelenített kimenetben. Alapértelmezés szerint ez a tulajdonság false-ra van beállítva.
type: docs
weight: 105
url: /hu/aspose.slides.export/htmloptions/set_disablefontligatures/
---
## HtmlOptions::set_DisableFontLigatures(bool) metódus


Beállít egy értéket, amely azt jelzi, hogy a szöveg ligatúrák használata nélkül kerül-e renderelésre. Ha **true** értékre van állítva, a ligatúrák le lesznek tiltva a megjelenített kimenetben. Alapértelmezés szerint ez a tulajdonság **false** értékre van beállítva.

```cpp
void Aspose::Slides::Export::HtmlOptions::set_DisableFontLigatures(bool value) override
```

## Megjegyzések


Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // Ligatúrák letiltása a szöveg renderelésében

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## Lásd még

* Osztály [HtmlOptions](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)