---
title: LegacyDiagram
second_title: Aspose.Slides Androidhoz Java API hivatkozáson keresztül
description: Egy örökölt diagramobjektumot képvisel.
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

Egy örökölt diagramobjektumot képvisel.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | Átalakítja a régi digramot szerkeszthető SmartArt objektummá. |
| [convertToGroupShape()](#convertToGroupShape--) | Átalakítja a régi digramot szerkeszthető csoport alakzattá. |
### convertToSmartArt() {#convertToSmartArt--}
```
public final ISmartArt convertToSmartArt()
```


Átalakítja a régi digramot szerkeszthető SmartArt objektummá. A létrehozott SmartArt objektum a szülő csoport alakzatba kerül ugyanarra a pozícióra.

**Visszatér:**
[ISmartArt](../../com.aspose.slides/ismartart) - Létrehozott SmartArt objektum.
### convertToGroupShape() {#convertToGroupShape--}
```
public final IGroupShape convertToGroupShape()
```


Átalakítja a régi digramot szerkeszthető csoport alakzattá. A létrehozott GroupShape objektum a szülő csoport alakzatba kerül ugyanarra a pozícióra.

**Visszatér:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Létrehozott GroupShape objektum.