---
title: ILegacyDiagram
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar ett legacy-diagramobjekt
type: docs
url: /sv/com.aspose.slides/ilegacydiagram/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ILegacyDiagram extends IGraphicalObject
```

Representerar ett legacy-diagramobjekt
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | Konverterar legacy-diagram till redigerbart SmartArt-objekt. |
| [convertToGroupShape()](#convertToGroupShape--) | Konverterar legacy-diagram till redigerbar gruppform. |
### convertToSmartArt() {#convertToSmartArt--}
```
public abstract ISmartArt convertToSmartArt()
```

Konverterar legacy-diagram till redigerbart SmartArt-objekt. Det skapade SmartArt-objektet läggs till i föräldragruppformen på samma position.

**Returnerar:**
[ISmartArt](../../com.aspose.slides/ismartart) - Skapat SmartArt-objekt.
### convertToGroupShape() {#convertToGroupShape--}
```
public abstract IGroupShape convertToGroupShape()
```

Konverterar legacy-diagram till redigerbar gruppform. Det skapade GroupShape-objektet läggs till i föräldragruppformen på samma position.

**Returnerar:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Skapat GroupShape-objekt.