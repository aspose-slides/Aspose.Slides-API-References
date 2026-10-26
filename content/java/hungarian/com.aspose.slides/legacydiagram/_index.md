---
title: LegacyDiagram
second_title: Aspose.Slides Java API Referencia
description: Egy legacy diagramobjektumot képvisel.
type: docs
url: /hu/com.aspose.slides/legacydiagram/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Minden megvalósított interfész:**
[com.aspose.slides.ILegacyDiagram](../../com.aspose.slides/ilegacydiagram)
```
public class LegacyDiagram extends GraphicalObject implements ILegacyDiagram
```

Legacy diagramobjektumot képvisel.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | Átalakítja a legacy diagramot szerkeszthető SmartArt objektummá. |
| [convertToGroupShape()](#convertToGroupShape--) | Átalakítja a legacy diagramot szerkeszthető csoport alakzattá. |
### convertToSmartArt() {#convertToSmartArt--}
```
public final ISmartArt convertToSmartArt()
```

Átalakítja a legacy diagramot szerkeszthető SmartArt objektummá. A létrehozott SmartArt objektum hozzáadódik a szülő csoport alakzathoz ugyanazon a pozíción.

**Visszatér:**
[ISmartArt](../../com.aspose.slides/ismartart) - Létrehozott SmartArt objektum.
### convertToGroupShape() {#convertToGroupShape--}
```
public final IGroupShape convertToGroupShape()
```

Átalakítja a legacy diagramot szerkeszthető csoport alakzattá. A létrehozott GroupShape objektum hozzáadódik a szülő csoport alakzathoz ugyanazon a pozíción.

**Visszatér:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Létrehozott GroupShape objektum.