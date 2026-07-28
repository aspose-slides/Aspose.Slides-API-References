---
title: get_RotationAngle()
second_title: Aspose.Slides C++ API hivatkozás
description: Meghatározza az egyéni forgatást, amely a határoló keretben lévő szövegre van alkalmazva. Ha nincs megadva, akkor a hozzá tartozó alakzat forgatása kerül felhasználásra. Ha meg van adva, akkor ez függetlenül az alakzattól kerül alkalmazásra. Vagyis az alakzatra is lehet forgatás alkalmazva, miközben a szöveg maga is kap forgatást. A vizuális szövegfordulat eredő értéke ebből a tulajdonságból és a TextVerticalType tulajdonság előre definiált függőleges típusából származik. Olvasandó float.
type: docs
weight: 300
url: /hu/aspose.slides/textframeformat/get_rotationangle/
---
## TextFrameFormat::get_RotationAngle() metódus

Megadja az egyéni forgatást, amely a keretben lévő szövegre van alkalmazva. Ha nincs megadva, akkor a hozzá tartozó alakzat forgatása kerül felhasználásra. Ha meg van adva, akkor ez függetlenül az alakzattól kerül alkalmazásra. Vagyis az alakzatra alkalmazhatnak forgatást, miközben a szöveg maga is kap forgatást. Az ebből a tulajdonságból és a TextVerticalType tulajdonság előre definiált függőleges típusából származó vizuális szövegfordulat eredő értéke. Olvassa **float**.

```cpp
float Aspose::Slides::TextFrameFormat::get_RotationAngle() override
```

## Megjegyzések

Tekintse meg azt az esetet, amikor egy alakzatra 90 fokos, az óramutató járásával megegyező irányú forgatás van alkalmazva. Emellett a szövegtörzs maga -90 fokos, az óramutató járásával ellentétes irányú forgatást kap. Ekkor az eredő alakzat forgatottnak tűnik, de a benne lévő szöveg úgy jelenik meg, mintha egyáltalán nem lenne elfordítva.

## Lásd még

* Osztály [TextFrameFormat](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)