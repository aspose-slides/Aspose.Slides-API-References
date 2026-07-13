---
title: GroupShape
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een groep vormen op een dia voor.
type: docs
url: /nl/com.aspose.slides/groupshape/
---
**Overerving:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**Alle geïmplementeerde interfaces:**  
[com.aspose.slides.IGroupShape](../../com.aspose.slides/igroupshape)  
```
public class GroupShape extends Shape implements IGroupShape
```

Stelt een groep vormen op een dia voor.

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Retourneert het LineFormat-object dat line-formatterings-eigenschappen voor een vorm bevat. |
| [getGroupShapeLock()](#getGroupShapeLock--) | Retourneert de vergrendelingen van de vorm. |
| [getShapes()](#getShapes--) | Retourneert de collectie vormen binnen de groep. |

### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

Retourneert het LineFormat-object dat line-formatterings-eigenschappen voor een vorm bevat. Opmerking: Retourneert null voor GroupShape-objecten omdat ze geen line-eigenschappen hebben. Alleen-lezen [ILineFormat](../../com.aspose.slides/ilineformat).

**Retourneert:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getGroupShapeLock() {#getGroupShapeLock--}
```
public final IGroupShapeLock getGroupShapeLock()
```

Retourneert de vergrendelingen van de vorm. Alleen-lezen [IGroupShapeLock](../../com.aspose.slides/igroupshapelock).

**Retourneert:**  
[IGroupShapeLock](../../com.aspose.slides/igroupshapelock)

### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```

Retourneert de collectie vormen binnen de groep. Alleen-lezen [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Retourneert:**  
[IShapeCollection](../../com.aspose.slides/ishapecollection)