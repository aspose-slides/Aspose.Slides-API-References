---
title: set_ExplicitBreak()
second_title: Aspose.Slides C++ API hivatkozás
description: "A kifejezett sortörés meghatározza, hogy van-e sortörés a Box objektum elején, úgy hogy a sor a doboz objektum elején törik. Meghatározza az előző sor matematikai szövegében található operátor számát, amely a jelenlegi sor matematikai szövegének igazítási pontjaként szolgál. lehetséges értékek: 1..255 Alapértelmezett: 0 (nincs kifejezett sortörés)"
type: docs
weight: 131
url: /hu/aspose.slides.mathtext/imathbox/set_explicitbreak/
---
## IMathBox::set_ExplicitBreak(uint8_t) metódus

Kifejezett sortörés meghatározza, hogy van-e sortörés a Box objektum elején, úgy hogy a sor a doboz objektum elején törik. Meghatározza az előző sor matematikai szövegén található operátor számát, amely a jelenlegi sor matematikai szövegének igazítási pontjaként szolgál. lehetséges értékek: 1..255 Alapértelmezett: 0 (nincs kifejezett sortörés)

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_ExplicitBreak(uint8_t value)=0
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