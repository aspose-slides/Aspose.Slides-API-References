---
title: get_ExplicitBreak()
second_title: Aspose.Slides C++ API referencia
description: "Az explicit sortörés megadja, hogy van-e sortörés a Box objektum elején, így a sor a box objektum kezdetén törik meg. Megadja a matematikai szöveg előző sorában lévő operátor számát, amelyet a jelenlegi sor matematikai szövegének igazítási pontjaként kell használni. Lehetséges értékek: 1..255 Alapértelmezett: 0 (nincs explicit sortörés)"
type: docs
weight: 118
url: /hu/aspose.slides.mathtext/imathbox/get_explicitbreak/
---
## IMathBox::get_ExplicitBreak() metódus


Az explicit sortörés megadja, hogy van-e sortörés a Box objektum elején, így a sor a box objektum kezdetén törik meg. Megadja a matematikai szöveg előző sorában lévő operátor számát, amelyet a jelenlegi sor matematikai szövegének igazítási pontjaként kell használni. Lehetséges értékek: 1..255 Alapértelmezett: 0 (nincs explicit sortörés)

```cpp
virtual uint8_t Aspose::Slides::MathText::IMathBox::get_ExplicitBreak()=0
```

## Megjegyzések


Példa: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## Lásd még

* Osztály [IMathBox](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)