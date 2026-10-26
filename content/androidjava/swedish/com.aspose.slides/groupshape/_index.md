---
title: GroupShape
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en grupp former på en bild.
type: docs
url: /sv/com.aspose.slides/groupshape/
---
**Arv:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IGroupShape](../../com.aspose.slides/igroupshape)
```
public class GroupShape extends Shape implements IGroupShape
```

Representerar en grupp former på en bild.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Returnerar LineFormat-objektet som innehåller linjeformaterings-egenskaper för en form. |
| [getGroupShapeLock()](#getGroupShapeLock--) | Returnerar formens lås. |
| [getShapes()](#getShapes--) | Returnerar samlingen av former i gruppen. |
### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

Returnerar LineFormat-objektet som innehåller linjeformaterings-egenskaper för en form. Obs: Returnerar null för GroupShape-objekt eftersom de inte har linjeegenskaper. Skrivskyddad [ILineFormat](../../com.aspose.slides/ilineformat).

**Returnerar:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getGroupShapeLock() {#getGroupShapeLock--}
```
public final IGroupShapeLock getGroupShapeLock()
```

Returnerar formens lås. Skrivskyddad [IGroupShapeLock](../../com.aspose.slides/igroupshapelock).

**Returnerar:**
[IGroupShapeLock](../../com.aspose.slides/igroupshapelock)
### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```

Returnerar samlingen av former i gruppen. Skrivskyddad [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Returnerar:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)