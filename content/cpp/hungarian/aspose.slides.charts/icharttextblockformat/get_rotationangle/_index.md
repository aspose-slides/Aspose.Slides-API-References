---
title: get_RotationAngle()
second_title: Aspose.Slides for C++ API Referencia
description: A megadja a kerethez tartozó szövegre alkalmazott egyedi forgatást. Ha nincs megadva, akkor a hozzá tartozó alakzat forgatását használja. Ha meg van adva, akkor ez függetlenül alkalmazódik az alakzattól. Tehát az alakzat kaphat forgatást, miközben a szöveg maga is forgatásra kerül. A vizuális szövegforgatás eredő értéke ebből a tulajdonságból és a TextVerticalType tulajdonságban előre definiált függőleges típusból kerül összegzésre. Olvasható float.
type: docs
weight: 235
url: /hu/aspose.slides.charts/icharttextblockformat/get_rotationangle/
---
## IChartTextBlockFormat::get_RotationAngle() metódus

Meghatározza a keretet körülvevő szövegre alkalmazott egyedi forgatást. Ha nincs megadva, a hozzá tartozó alakzat forgatását használja. Ha meg van adva, akkor ez függetlenül alkalmazódik az alakzattól. Tehát az alakzat kaphat forgatást, miközben a szöveg önmagában is alkalmazhat forgatást. A vizuális szövegfogás értéke ebből a tulajdonságból és a TextVerticalType tulajdonságban előre definiált függőleges típusból kerül összesítésre. Olvasható **float**.

```cpp
virtual float Aspose::Slides::Charts::IChartTextBlockFormat::get_RotationAngle()=0
```

## Megjegyzés

Fontolja meg azt az esetet, amikor egy alakzatra 90 fokos óramutató járásával megegyező fordulatot alkalmaznak. Ezen felül a szövegtörzs maga -90 fokos óramutató járásával ellentétes fordulatot kap. Ebben az esetben az eredményül kapott alakzat forgottnak tűnik, de a benne lévő szöveg úgy jelenik meg, mintha egyáltalán nem lett volna elfordítva. 
## Lásd még

* Osztály [IChartTextBlockFormat](../)
* Névterület [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)