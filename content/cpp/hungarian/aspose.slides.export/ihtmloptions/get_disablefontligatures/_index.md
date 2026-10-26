---
title: get_DisableFontLigatures()
second_title: Aspose.Slides a C++ API referencia
description: Visszaad egy értéket, amely azt jelzi, hogy a szöveget ligatúrák használata nélkül renderelik. Ha true-ra van állítva, a ligatúrák le lesznek tiltva a megjelenített kimenetben. Alapértelmezés szerint ez a tulajdonság false-ra van beállítva.
type: docs
weight: 183
url: /hu/aspose.slides.export/ihtmloptions/get_disablefontligatures/
---
## IHtmlOptions::get_DisableFontLigatures() metódus


Visszaad egy értéket, amely azt jelzi, hogy a szöveg ligatúrák használata nélkül kerül-e renderelésre. Ha **true**-ra van állítva, a ligatúrák le lesznek tiltva a megjelenített kimenetben. Alapértelmezés szerint ez a tulajdonság **false**-ra van beállítva.

```cpp
virtual bool Aspose::Slides::Export::IHtmlOptions::get_DisableFontLigatures()=0
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

* Osztály [IHtmlOptions](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)