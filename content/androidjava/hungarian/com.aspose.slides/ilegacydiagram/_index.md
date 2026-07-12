---
title: ILegacyDiagram
second_title: Aspose.Slides Androidhoz a Java API hivatkozáson keresztül
description: Egy régi diagramobjektumot képvisel
type: docs
url: /hu/com.aspose.slides/ilegacydiagram/
---
**Minden implementált interfész:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ILegacyDiagram extends IGraphicalObject
```

Egy régi diagramobjektumot képvisel
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | Átalakítja a régi diagramot szerkeszthető SmartArt objektummá. |
| [convertToGroupShape()](#convertToGroupShape--) | Átalakítja a régi diagramot szerkeszthető csoport alakzattá. |
### convertToSmartArt() {#convertToSmartArt--}
```
public abstract ISmartArt convertToSmartArt()
```


Átalakítja a régi diagramot szerkeszthető SmartArt objektummá. A létrehozott SmartArt objektumot a szülő csoport alakzathoz adjuk hozzá ugyanabban a pozícióban.

**Visszatérési érték:**
[ISmartArt](../../com.aspose.slides/ismartart) - Létrehozott SmartArt objektum.
### convertToGroupShape() {#convertToGroupShape--}
```
public abstract IGroupShape convertToGroupShape()
```


Átalakítja a régi diagramot szerkeszthető csoport alakzattá. A létrehozott GroupShape objektumot a szülő csoport alakzathoz adjuk hozzá ugyanabban a pozícióban.

**Visszatérési érték:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Létrehozott GroupShape objektum.