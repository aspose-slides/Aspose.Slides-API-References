---
title: LegacyDiagram
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar ett gammalt diagramobjekt.
type: docs
url: /sv/com.aspose.slides/legacydiagram/
---
**Arv:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Alla implementerade gränssnitt:**
[com.aspose.slides.ILegacyDiagram](../../com.aspose.slides/ilegacydiagram)
```
public class LegacyDiagram extends GraphicalObject implements ILegacyDiagram
```

Representerar ett gammalt diagramobjekt.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | Konverterar legacy-diagram till redigerbart SmartArt-objekt. |
| [convertToGroupShape()](#convertToGroupShape--) | Konverterar legacy-diagram till redigerbar gruppform. |
### convertToSmartArt() {#convertToSmartArt--}
```
public final ISmartArt convertToSmartArt()
```


Konverterar legacy-diagram till redigerbart SmartArt-objekt. Det skapade SmartArt-objektet läggs till föräldragruppens form på samma position.

**Returnerar:**
[ISmartArt](../../com.aspose.slides/ismartart) - Skapat SmartArt-objekt.
### convertToGroupShape() {#convertToGroupShape--}
```
public final IGroupShape convertToGroupShape()
```


Konverterar legacy-diagram till redigerbar gruppform. Det skapade GroupShape-objektet läggs till föräldragruppens form på samma position.

**Returnerar:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Skapat GroupShape-objekt.