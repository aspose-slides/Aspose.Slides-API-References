---
title: ILegacyDiagram
second_title: Aspose.Slides Java API referencia
description: Egy régi diagramobjektumot képvisel
type: docs
url: /hu/com.aspose.slides/ilegacydiagram/
---
**All Implemented Interfaces:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ILegacyDiagram extends IGraphicalObject
```

Egy régi diagram objektumot képvisel
## Metódusok

| Method | Description |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | Átalakítja a régi diagramot szerkeszthető SmartArt objektummá. |
| [convertToGroupShape()](#convertToGroupShape--) | Átalakítja a régi diagramot szerkeszthető GroupShape objektummá. |
### convertToSmartArt() {#convertToSmartArt--}
```
public abstract ISmartArt convertToSmartArt()
```


Átalakítja a régi diagramot szerkeszthető SmartArt objektummá. A létrehozott SmartArt objektum a szülő GroupShape-hez adódik ugyanazon a pozícióban.

**Returns:**
[ISmartArt](../../com.aspose.slides/ismartart) - Létrehozott SmartArt objektum.
### convertToGroupShape() {#convertToGroupShape--}
```
public abstract IGroupShape convertToGroupShape()
```


Átalakítja a régi diagramot szerkeszthető GroupShape objektummá. A létrehozott GroupShape objektum a szülő GroupShape-hez adódik ugyanazon a pozícióban.

**Returns:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Létrehozott GroupShape objektum.