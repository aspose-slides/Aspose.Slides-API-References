---
title: set_DisableFontLigatures()
second_title: Aspose.Slides for C++ API Referencia
description: Beállít egy értéket, amely azt jelzi, hogy a szöveget ligatúrák használata nélkül renderelik-e. Ha true értékre van állítva, a ligatúrák le lesznek tiltva a renderelt kimenetben. Alapértelmezés szerint ez a tulajdonság false értékre van állítva.
type: docs
weight: 339
url: /hu/aspose.slides.export/svgoptions/set_disablefontligatures/
---
## SVGOptions::set_DisableFontLigatures(bool) metódus


Beállít egy értéket, amely azt jelzi, hogy a szöveget ligatúrák használata nélkül renderelik-e. Ha **true** értékre van állítva, a ligatúrák le lesznek tiltva a renderelt kimenetben. Alapértelmezés szerint ez a tulajdonság **false** értékre van állítva.

```cpp
void Aspose::Slides::Export::SVGOptions::set_DisableFontLigatures(bool value) override
```

## Megjegyzések


Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<SVGOptions> options = System::MakeObject<SVGOptions>();
options->set_DisableFontLigatures(true); // Ligatúrák letiltása a szöveg renderelésében

System::SharedPtr<System::IO::FileStream> fileStream = System::MakeObject<System::IO::FileStream>(u"slide-0.svg", System::IO::FileMode::Create, System::IO::FileAccess::Write);
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## Lásd még

* Osztály [SVGOptions](../)
* Névterület [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)