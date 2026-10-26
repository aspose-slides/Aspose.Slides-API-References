---
title: GroupShape
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Représente un groupe de formes sur une diapositive.
type: docs
url: /fr/com.aspose.slides/groupshape/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IGroupShape](../../com.aspose.slides/igroupshape)
```
public class GroupShape extends Shape implements IGroupShape
```

Représente un groupe de formes sur une diapositive.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Renvoie l'objet LineFormat qui contient les propriétés de formatage de ligne pour une forme. |
| [getGroupShapeLock()](#getGroupShapeLock--) | Renvoie les verrous de la forme. |
| [getShapes()](#getShapes--) | Renvoie la collection de formes à l'intérieur du groupe. |
### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

Renvoie l'objet LineFormat qui contient les propriétés de formatage de ligne pour une forme. Remarque : renvoie null pour les objets GroupShape car ils n'ont pas de propriétés de ligne. Lecture seule [ILineFormat](../../com.aspose.slides/ilineformat).

**Renvoie :**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getGroupShapeLock() {#getGroupShapeLock--}
```
public final IGroupShapeLock getGroupShapeLock()
```

Renvoie les verrous de la forme. Lecture seule [IGroupShapeLock](../../com.aspose.slides/igroupshapelock).

**Renvoie :**
[IGroupShapeLock](../../com.aspose.slides/igroupshapelock)
### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```

Renvoie la collection de formes à l'intérieur du groupe. Lecture seule [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Renvoie :**
[IShapeCollection](../../com.aspose.slides/ishapecollection)