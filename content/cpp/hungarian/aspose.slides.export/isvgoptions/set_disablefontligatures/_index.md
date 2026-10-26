---
title: set_DisableFontLigatures()
second_title: Aspose.Slides C++ API-referencia
description: Beállít egy értéket, amely azt jelzi, hogy a szöveg ligatúrák használata nélkül jelenik meg. Ha true-ra van állítva, a ligatúrák le lesznek tiltva a megjelenített kimenetben. Alapértelmezés szerint ez a tulajdonság false-ra van állítva.
type: docs
weight: 339
url: /hu/aspose.slides.export/isvgoptions/set_disablefontligatures/
---
## ISSVGOptions::set_DisableFontLigatures(bool) metódus

Beállít egy értéket, amely azt jelzi, hogy a szöveget ligatúrák használata nélkül jelenítik-e meg. Ha **true**-ra van állítva, a ligatúrák le lesznek tiltva a megjelenített kimenetben. Alapértelmezés szerint ez a tulajdonság **false**-ra van állítva.

```cpp
virtual void Aspose::Slides::Export::ISVGOptions::set_DisableFontLigatures(bool value)=0
```

## Megjegyzések

Példa:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<SVGOptions> options = System::MakeObject<SVGOptions>();
options->set_DisableFontLigatures(true); // Letiltja a ligatúrákat a szöveg renderelésekor

System::SharedPtr<System::IO::FileStream> fileStream = System::MakeObject<System::IO::FileStream>(u"slide-0.svg", System::IO::FileMode::Create, System::IO::FileAccess::Write);
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## Lásd még

* Osztály [ISVGOptions](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)