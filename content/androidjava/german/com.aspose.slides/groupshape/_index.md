---
title: GroupShape
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt eine Gruppe von Formen auf einer Folie dar.
type: docs
url: /de/com.aspose.slides/groupshape/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IGroupShape](../../com.aspose.slides/igroupshape)
```
public class GroupShape extends Shape implements IGroupShape
```

Stellt eine Gruppe von Formen auf einer Folie dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Gibt das LineFormat-Objekt zurück, das die Linienformatierungseigenschaften für eine Form enthält. |
| [getGroupShapeLock()](#getGroupShapeLock--) | Gibt die Sperren der Form zurück. |
| [getShapes()](#getShapes--) | Gibt die Sammlung von Formen innerhalb der Gruppe zurück. |
### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```


Gibt das LineFormat-Objekt zurück, das die Linienformatierungseigenschaften für eine Form enthält. Hinweis: Gibt null zurück für GroupShape-Objekte, weil sie keine Linieneigenschaften besitzen. Nur lesbar [ILineFormat](../../com.aspose.slides/ilineformat).

**Rückgabe:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getGroupShapeLock() {#getGroupShapeLock--}
```
public final IGroupShapeLock getGroupShapeLock()
```


Gibt die Sperren der Form zurück. Nur lesbar [IGroupShapeLock](../../com.aspose.slides/igroupshapelock).

**Rückgabe:**
[IGroupShapeLock](../../com.aspose.slides/igroupshapelock)
### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```


Gibt die Sammlung von Formen innerhalb der Gruppe zurück. Nur lesbar [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Rückgabe:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)