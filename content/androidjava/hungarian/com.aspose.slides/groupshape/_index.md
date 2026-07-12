---
title: GroupShape
second_title: Aspose.Slides Androidhoz a Java API hivatkozás alapján
description: Egy dián lévő alakzatcsoportot képvisel.
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

Egy dián lévő alakzatcsoportot képvisel.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Visszaadja a LineFormat objektumot, amely egy alakzat vonalformázási tulajdonságait tartalmazza. |
| [getGroupShapeLock()](#getGroupShapeLock--) | Visszaadja az alakzat zárolásait. |
| [getShapes()](#getShapes--) | Visszaadja a csoporton belüli alakzatok gyűjteményét. |
### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```


Visszaadja a LineFormat objektumot, amely egy alakzat vonalformázási tulajdonságait tartalmazza. Megjegyzés: GroupShape objektumok esetén null értéket ad vissza, mivel nekik nincsenek vonal tulajdonságaik. Csak olvasható [ILineFormat](../../com.aspose.slides/ilineformat).

**Visszatérési érték:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getGroupShapeLock() {#getGroupShapeLock--}
```
public final IGroupShapeLock getGroupShapeLock()
```


Visszaadja az alakzat zárolásait. Csak olvasható [IGroupShapeLock](../../com.aspose.slides/igroupshapelock).

**Visszatérési érték:**
[IGroupShapeLock](../../com.aspose.slides/igroupshapelock)
### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```


Visszaadja a csoporton belüli alakzatok gyűjteményét. Csak olvasható [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Visszatérési érték:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)