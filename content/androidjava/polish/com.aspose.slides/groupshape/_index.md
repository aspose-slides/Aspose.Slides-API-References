---
title: GroupShape
second_title: Aspose.Slides dla Androida poprzez odniesienie API Java
description: Reprezentuje grupę kształtów na slajdzie.
type: docs
url: /pl/com.aspose.slides/groupshape/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IGroupShape](../../com.aspose.slides/igroupshape)
```
public class GroupShape extends Shape implements IGroupShape
```

Reprezentuje grupę kształtów na slajdzie.
## Metody

| Metoda | Opis |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Zwraca obiekt LineFormat zawierający właściwości formatowania linii dla kształtu. |
| [getGroupShapeLock()](#getGroupShapeLock--) | Zwraca blokady kształtu. |
| [getShapes()](#getShapes--) | Zwraca kolekcję kształtów wewnątrz grupy. |
### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```


Zwraca obiekt LineFormat zawierający właściwości formatowania linii dla kształtu. Note: Returns null for GroupShape objects because they don't have line properties. Tylko do odczytu [ILineFormat](../../com.aspose.slides/ilineformat).

**Zwraca:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getGroupShapeLock() {#getGroupShapeLock--}
```
public final IGroupShapeLock getGroupShapeLock()
```


Zwraca blokady kształtu. Tylko do odczytu [IGroupShapeLock](../../com.aspose.slides/igroupshapelock).

**Zwraca:**
[IGroupShapeLock](../../com.aspose.slides/igroupshapelock)
### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```


Zwraca kolekcję kształtów wewnątrz grupy. Tylko do odczytu [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Zwraca:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)