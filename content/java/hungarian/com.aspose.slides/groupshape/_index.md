---
title: GroupShape
second_title: Aspose.Slides Java API hivatkozás
description: A dián lévő formák egy csoportját jelenti.
type: docs
url: /hu/com.aspose.slides/groupshape/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**Minden megvalósított interfész:**
[com.aspose.slides.IGroupShape](../../com.aspose.slides/igroupshape)
```
public class GroupShape extends Shape implements IGroupShape
```

A dián lévő formák egy csoportját reprezentálja.
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Visszaadja a LineFormat objektumot, amely a forma vonalformázási tulajdonságait tartalmazza. |
| [getGroupShapeLock()](#getGroupShapeLock--) | Visszaadja a forma zárolásait. |
| [getShapes()](#getShapes--) | Visszaadja a csoporton belüli formák gyűjteményét. |
### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```


Visszaadja a LineFormat objektumot, amely a forma vonalformázási tulajdonságait tartalmazza. Megjegyzés: Visszaadja a null értéket a GroupShape objektumok számára, mivel azoknak nincs vonal tulajdonsága. Csak olvasható [ILineFormat](../../com.aspose.slides/ilineformat).

**Visszatér:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getGroupShapeLock() {#getGroupShapeLock--}
```
public final IGroupShapeLock getGroupShapeLock()
```


Visszaadja a forma zárolásait. Csak olvasható [IGroupShapeLock](../../com.aspose.slides/igroupshapelock).

**Visszatér:**
[IGroupShapeLock](../../com.aspose.slides/igroupshapelock)
### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```


Visszaadja a csoporton belüli formák gyűjteményét. Csak olvasható [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Visszatér:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)