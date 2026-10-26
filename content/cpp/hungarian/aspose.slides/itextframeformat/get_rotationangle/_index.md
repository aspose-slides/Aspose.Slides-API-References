---
title: get_RotationAngle()
second_title: Aspose.Slides C++ API referenciája
description: Megadja a kereten belüli szövegre alkalmazott egyedi forgatást. Ha nincs megadva, akkor a hozzá tartozó alakzat forgatása lesz használva. Ha meg van adva, akkor ez függetlenül kerül alkalmazásra az alakzattól. Ez azt jelenti, hogy az alakzat forgatást kaphat, miközben a szöveg is saját forgatással rendelkezik. A vizuális szövegforgatás eredő értéke ebből a tulajdonságból és a TextVerticalType tulajdonságban előre definiált függőleges típusból kerül összegzésre. Olvasd float.
type: docs
weight: 339
url: /hu/aspose.slides/itextframeformat/get_rotationangle/
---
## ITextFrameFormat::get_RotationAngle() metódus

Meghatározza a keretben lévő szövegre alkalmazott egyedi forgatást. Ha nincs megadva, akkor a hozzá tartozó alakzat forgatása lesz használva. Ha meg van adva, akkor ez függetlenül alkalmazásra kerül az alakzattól. Ez azt jelenti, hogy az alakzat kaphat forgatást, miközben a szöveg is saját forgatással rendelkezik. A vizuális szövegforgatás eredő értéke ebből a tulajdonságból és a TextVerticalType tulajdonságban előre definiált függőleges típusból kerül összegzésre. Olvasd **float**.

```cpp
virtual float Aspose::Slides::ITextFrameFormat::get_RotationAngle()=0
```

## Megjegyzések

Vegyük figyelembe azt az esetet, amikor egy alakzaton 90 fokos, az óramutató járásával megegyező irányú forgatás van alkalmazva. Ehhez képest a szövegtest is -90 fokos, az óramutatóval ellentétes irányú forgatással rendelkezik. Így a keletkezett alakzat forgatottnak tűnik, de a benne lévő szöveg úgy jelenik meg, mintha egyáltalán nem lenne elfordítva.

## Lásd még

* Osztály [ITextFrameFormat](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)