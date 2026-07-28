---
title: get_DisableFontLigatures()
second_title: Aspose.Slides C++ API Referenciája
description: Lekér egy értéket, amely azt jelzi, hogy a szöveg ligatúrák használata nélkül van-e megjelenítve. Ha true, a ligatúrák le lesznek tiltva a megjelenített kimenetben. Alapértelmezés szerint ez a tulajdonság false.
type: docs
weight: 131
url: /hu/aspose.slides.export/ihtml5options/get_disablefontligatures/
---
## IHtml5Options::get_DisableFontLigatures() metódus

Lekérdezi azt az értéket, amely azt jelzi, hogy a szöveg ligatúrák használata nélkül van-e megjelenítve. Ha **true** értékre van állítva, a ligatúrák le lesznek tiltva a megjelenített kimenetben. Alapértelmezés szerint ez a tulajdonság **false** értékre van állítva.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_DisableFontLigatures()=0
```

## Megjegyzések

Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // Letiltja a ligatúrákat a szöveg renderelésében

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## Lásd még

* Osztály [IHtml5Options](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)