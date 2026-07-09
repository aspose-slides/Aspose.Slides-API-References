---
title: ILegacyDiagram
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente un objet diagramme hérité
type: docs
url: /fr/com.aspose.slides/ilegacydiagram/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ILegacyDiagram extends IGraphicalObject
```

Représente un objet diagramme hérité
## Méthodes

| Méthode | Description |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | Convertit le diagramme hérité en objet SmartArt modifiable. |
| [convertToGroupShape()](#convertToGroupShape--) | Convertit le diagramme hérité en groupe de formes modifiable. |
### convertToSmartArt() {#convertToSmartArt--}
```
public abstract ISmartArt convertToSmartArt()
```


Convertit le diagramme hérité en objet SmartArt modifiable. L'objet SmartArt créé est ajouté au GroupShape parent à la même position.

**Retourne :**
[ISmartArt](../../com.aspose.slides/ismartart) - Objet SmartArt créé.
### convertToGroupShape() {#convertToGroupShape--}
```
public abstract IGroupShape convertToGroupShape()
```


Convertit le diagramme hérité en groupe de formes modifiable. L'objet GroupShape créé est ajouté au GroupShape parent à la même position.

**Retourne :**
[IGroupShape](../../com.aspose.slides/igroupshape) - Objet GroupShape créé.