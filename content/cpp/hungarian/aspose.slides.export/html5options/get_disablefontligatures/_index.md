---
title: get_DisableFontLigatures()
second_title: Aspose.Slides for C++ API referencia
description: Egy értéket ad vissza, amely jelzi, hogy a szöveg ligatúrák használata nélkül van-e megjelenítve. Ha true-ra van állítva, a ligatúrák le lesznek tiltva a megjelenített kimenetben. Alapértelmezés szerint ez a tulajdonság false-ra van állítva.
type: docs
weight: 131
url: /hu/aspose.slides.export/html5options/get_disablefontligatures/
---
## Html5Options::get_DisableFontLigatures() metódus

Egy értéket ad vissza, amely jelzi, hogy a szöveg ligatúrák használata nélkül van-e megjelenítve. Ha **true**-ra van állítva, a ligatúrák le lesznek tiltva a megjelenített kimenetben. Alapértelmezés szerint ez a tulajdonság **false**-ra van állítva.

```cpp
bool Aspose::Slides::Export::Html5Options::get_DisableFontLigatures() override
```

## Megjegyzések

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