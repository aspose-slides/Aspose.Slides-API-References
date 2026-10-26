---
title: GroupShape
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Představuje skupinu tvarů na snímku.
type: docs
url: /cs/com.aspose.slides/groupshape/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**Všechny implementované rozhraní:**
[com.aspose.slides.IGroupShape](../../com.aspose.slides/igroupshape)
```
public class GroupShape extends Shape implements IGroupShape
```

Představuje skupinu tvarů na snímku.
## Metody

| Metoda | Popis |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Vrací objekt LineFormat, který obsahuje vlastnosti formátování čáry pro tvar. |
| [getGroupShapeLock()](#getGroupShapeLock--) | Vrací zámky tvaru. |
| [getShapes()](#getShapes--) | Vrací kolekci tvarů uvnitř skupiny. |
### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```


Vrací objekt LineFormat, který obsahuje vlastnosti formátování čáry pro tvar. Poznámka: Vrací null pro objekty GroupShape, protože nemají vlastnosti čáry. Pouze pro čtení [ILineFormat](../../com.aspose.slides/ilineformat).

**Vrací:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getGroupShapeLock() {#getGroupShapeLock--}
```
public final IGroupShapeLock getGroupShapeLock()
```


Vrací zámky tvaru. Pouze pro čtení [IGroupShapeLock](../../com.aspose.slides/igroupshapelock).

**Vrací:**
[IGroupShapeLock](../../com.aspose.slides/igroupshapelock)
### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```


Vrací kolekci tvarů uvnitř skupiny. Pouze pro čtení [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Vrací:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)