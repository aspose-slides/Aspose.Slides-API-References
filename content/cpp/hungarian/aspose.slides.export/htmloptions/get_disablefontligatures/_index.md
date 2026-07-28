---
title: get_DisableFontLigatures()
second_title: Aspose.Slides C++ API referencia
description: Értéket ad vissza, amely azt jelzi, hogy a szöveget ligatúrák használata nélkül jelenítik meg. Ha igazra van állítva, a ligatúrák le lesznek tiltva a megjelenített kimenetben. Alapértelmezés szerint ez a tulajdonság hamis értékre van beállítva.
type: docs
weight: 92
url: /hu/aspose.slides.export/htmloptions/get_disablefontligatures/
---
## HtmlOptions::get_DisableFontLigatures() metódus


Értéket ad vissza, amely azt jelzi, hogy a szöveget ligatúrák használata nélkül jelenítik meg. Ha **true**-ra van állítva, a ligatúrák le lesznek tiltva a megjelenített kimenetben. Alapértelmezés szerint ez a tulajdonság **false**-ra van beállítva.

```cpp
bool Aspose::Slides::Export::HtmlOptions::get_DisableFontLigatures() override
```

## Megjegyzések


Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // Letiltja a ligatúrákat a szöveg megjelenítésében

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## Lásd még

* Osztály [HtmlOptions](../)
* Névtere [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)