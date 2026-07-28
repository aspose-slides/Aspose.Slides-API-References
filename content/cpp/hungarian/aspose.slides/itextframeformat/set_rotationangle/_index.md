---
title: set_RotationAngle()
second_title: Aspose.Slides C++ API referencia
description: A határoló keretben lévő szövegre alkalmazott egyéni forgást adja meg. Ha nincs megadva, akkor a kísérő alakzat forgása kerül használatra. Ha meg van adva, akkor ez függetlenül van alkalmazva az alakzattól. Ez azt jelenti, hogy az alakzat kaphat forgást, miközben a szöveg maga is saját forgással rendelkezik. A vizuális szövegforgatás eredő értéke ebből a tulajdonságból és a TextVerticalType tulajdonságban előre meghatározott függőleges típussal kerül összegzésre. Írja float.
type: docs
weight: 352
url: /hu/aspose.slides/itextframeformat/set_rotationangle/
---
## ITextFrameFormat::set_RotationAngle(float) metódus

Meghatározza az egyéni forgást, amely a határoló keretben lévő szövegre van alkalmazva. Ha nincs megadva, akkor a kísérő alakzat forgása kerül felhasználásra. Ha meg van adva, akkor ez függetlenül van alkalmazva az alakzattól. Ez azt jelenti, hogy az alakzat kap egy forgást, miközben a szöveg önmagában is rendelkezik saját forgással. Az eredő vizuális szövegfogás értéke ebből a tulajdonságból és a TextVerticalType előre definiált függőleges típusból kerül összegzésre. Írja **float**.

```cpp
virtual void Aspose::Slides::ITextFrameFormat::set_RotationAngle(float value)=0
```

## Megjegyzések

Vegyük figyelembe azt az esetet, amikor egy alakzatra 90 fokos óramutató járásával megegyező forgás van alkalmazva. Ezen felül a szövegtörzsnek magának -90 fokos óramutató járásával ellentétes forgása van alkalmazva. Ekkor a keletkezett alakzat forgottnak tűnik, de a benne lévő szöveg úgy jelenik meg, mintha egyáltalán nem lett volna forgatva.

## Lásd még

* Osztály [ITextFrameFormat](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)