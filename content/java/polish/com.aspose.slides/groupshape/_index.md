---
title: GroupShape
second_title: Aspose.Slides dla Java – odniesienie API
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
| [getLineFormat()](#getLineFormat--) | Zwraca obiekt LineFormat, który zawiera właściwości formatowania linii dla kształtu. |
| [getGroupShapeLock()](#getGroupShapeLock--) | Zwraca blokady kształtu. |
| [getShapes()](#getShapes--) | Zwraca kolekcję kształtów wewnątrz grupy. |
### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

Zwraca obiekt LineFormat, który zawiera właściwości formatowania linii dla kształtu. Uwaga: Zwraca null dla obiektów GroupShape, ponieważ nie mają właściwości linii. Tylko do odczytu [ILineFormat](../../com.aspose.slides/ilineformat).

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