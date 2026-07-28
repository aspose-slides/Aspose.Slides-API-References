---
title: get_DisableFontLigatures()
second_title: Aspose.Slides C++ API hivatkozás
description: Egy értéket ad, amely azt jelzi, hogy a szöveg ligatúrák használata nélkül jelenik meg. Ha true értékre van állítva, a ligatúrák le lesznek tiltva a megjelenített kimenetben. Alapértelmezés szerint ez a tulajdonság false értékre van állítva.
type: docs
weight: 326
url: /hu/aspose.slides.export/isvgoptions/get_disablefontligatures/
---
## ISVGOptions::get_DisableFontLigatures() method


Egy értéket kap, amely azt jelzi, hogy a szöveg ligatúrák használata nélkül jelenik meg. Ha **true** értékre van beállítva, a ligatúrák le lesznek tiltva a megjelenített kimenetben. Alapértelmezés szerint ez a tulajdonság **false** értékre van beállítva.

```cpp
virtual bool Aspose::Slides::Export::ISVGOptions::get_DisableFontLigatures()=0
```

## Megjegyzések


Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<SVGOptions> options = System::MakeObject<SVGOptions>();
options->set_DisableFontLigatures(true); // Letiltja a ligatúrákat a szöveg renderelésében

System::SharedPtr<System::IO::FileStream> fileStream = System::MakeObject<System::IO::FileStream>(u"slide-0.svg", System::IO::FileMode::Create, System::IO::FileAccess::Write);
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## Lásd még

* Osztály [ISVGOptions](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)