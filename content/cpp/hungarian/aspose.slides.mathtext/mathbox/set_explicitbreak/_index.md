---
title: set_ExplicitBreak()
second_title: Aspose.Slides C++ API hivatkozás
description: "Az explicit sortörés megadja, hogy van-e sortörés a Box objektum elején, úgy, hogy a sor a doboz objektum elején törik. Megadja a matematikai szöveg előző sorában lévő operátor számát, amely a jelenlegi sor igazítási pontjaként szolgál. Lehetséges értékek: 1..255 Alapértelmezett: 0 (nincs explicit sortörés)"
type: docs
weight: 131
url: /hu/aspose.slides.mathtext/mathbox/set_explicitbreak/
---
## MathBox::set_ExplicitBreak(uint8_t) metódus


Az explicit sortörés megadja, hogy van-e sortörés a Box objektum elején, úgy, hogy a sor a Box objektum elején történik. Megadja a matematikai szöveg előző sorában található operátor számát, amely a jelenlegi matematikai szöveg sorának igazítási pontjaként lesz használva. Lehetséges értékek: 1..255 Alapértelmezett: 0 (nincs explicit sortörés)

```cpp
void Aspose::Slides::MathText::MathBox::set_ExplicitBreak(uint8_t value) override
```

## Megjegyzés


Példa:
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## Lásd még

* Osztály [MathBox](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)