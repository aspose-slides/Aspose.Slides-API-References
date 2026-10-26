---
title: set_DisableFontLigatures()
second_title: Aspose.Slides for C++ API hivatkozás
description: Beállít egy értéket, amely jelzi, hogy a szöveg ligatúrák használata nélkül kerül renderelésre. Ha true-ra van állítva, a ligatúrák le lesznek tiltva a megjelenített kimenetben. Alapértelmezés szerint ez a tulajdonság false értékre van állítva.
type: docs
weight: 144
url: /hu/aspose.slides.export/html5options/set_disablefontligatures/
---
## Html5Options::set_DisableFontLigatures(bool) metódus

Beállít egy értéket, amely jelzi, hogy a szöveg ligatúrák használata nélkül kerül renderelésre. Ha **true**-ra van állítva, a ligatúrák le lesznek tiltva a megjelenített kimenetben. Alapértelmezés szerint ez a tulajdonság **false** értékre van állítva.

```cpp
void Aspose::Slides::Export::Html5Options::set_DisableFontLigatures(bool value) override
```

## Megjegyzés

Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // Ligatúrák letiltása a szöveg renderelésében

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## Lásd még

* Osztály [Html5Options](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)