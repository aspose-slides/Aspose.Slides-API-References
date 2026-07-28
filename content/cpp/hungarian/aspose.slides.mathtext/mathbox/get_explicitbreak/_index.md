---
title: get_ExplicitBreak()
second_title: Aspose.Slides C++ API referencia
description: "Az explicit break meghatározza, hogy van-e sortörés a Box objektum elején, így a sor a box objektum kezdetén törik. Megadja az előző sorban lévő operátor számát a matematikai szövegben, amely a jelenlegi sor matematikai szövegének igazítási pontjaként szolgál. Lehetséges értékek: 1..255 Alapértelmezett: 0 (nincs explicit break)"
type: docs
weight: 118
url: /hu/aspose.slides.mathtext/mathbox/get_explicitbreak/
---
## MathBox::get_ExplicitBreak() metódus

Az explicit break meghatározza, hogy van-e sortörés a Box objektum elején, így a sor a box objektum kezdetén törik. Megadja a matematikai szöveg előző sorában lévő operátor sorszámát, amely a jelenlegi sor matematikai szövegének igazítási pontjaként szolgál. Lehetséges értékek: 1..255 Alapértelmezett: 0 (nincs explicit break)

```cpp
uint8_t Aspose::Slides::MathText::MathBox::get_ExplicitBreak() override
```

## Megjegyzés

Példa:
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## Lásd még

* Osztály [MathBox](../)
* Névterület [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)