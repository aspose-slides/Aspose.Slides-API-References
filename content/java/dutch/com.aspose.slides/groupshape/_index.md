---
title: GroupShape
second_title: Aspose.Slides voor Java API-referentie
description: Vertegenwoordigt een groep shapes op een dia.
type: docs
url: /nl/com.aspose.slides/groupshape/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IGroupShape](../../com.aspose.slides/igroupshape)
```
public class GroupShape extends Shape implements IGroupShape
```

Vertegenwoordigt een groep shapes op een dia.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Retourneert het LineFormat-object dat lijnopmaak-eigenschappen voor een shape bevat. |
| [getGroupShapeLock()](#getGroupShapeLock--) | Retourneert de locks van de shape. |
| [getShapes()](#getShapes--) | Retourneert de collectie van shapes binnen de groep. |
### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```


Retourneert het LineFormat-object dat lijnopmaak-eigenschappen voor een shape bevat. Opmerking: Retourneert null voor GroupShape-objecten omdat ze geen lijn-eigenschappen hebben. Alleen-lezen [ILineFormat](../../com.aspose.slides/ilineformat).

**Retour:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getGroupShapeLock() {#getGroupShapeLock--}
```
public final IGroupShapeLock getGroupShapeLock()
```


Retourneert de locks van de shape. Alleen-lezen [IGroupShapeLock](../../com.aspose.slides/igroupshapelock).

**Retour:**
[IGroupShapeLock](../../com.aspose.slides/igroupshapelock)
### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```


Retourneert de collectie van shapes binnen de groep. Alleen-lezen [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Retour:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)