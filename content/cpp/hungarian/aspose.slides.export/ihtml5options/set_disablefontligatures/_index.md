---
title: set_DisableFontLigatures()
second_title: Aspose.Slides C++ API referenciája
description: Beállít egy értéket, amely azt jelzi, hogy a szöveget ligatúrák használata nélkül jeleníti meg. Ha true-ra van állítva, a ligatúrák le lesznek tiltva a megjelenített kimenetben. Alapértelmezés szerint ez a tulajdonság false-ra van állítva.
type: docs
weight: 144
url: /hu/aspose.slides.export/ihtml5options/set_disablefontligatures/
---
## IHtml5Options::set_DisableFontLigatures(bool) metódus

Beállít egy értéket, amely azt jelzi, hogy a szöveget ligatúrák használata nélkül jeleníti meg. Ha **true**-ra van állítva, a ligatúrák le lesznek tiltva a megjelenített kimenetben. Alapértelmezés szerint ez a tulajdonság **false**-ra van állítva.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_DisableFontLigatures(bool value)=0
```

## Megjegyzések

Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // Letiltja a ligatúrákat a szöveg megjelenítésében

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## Lásd még

* Osztály [IHtml5Options](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)