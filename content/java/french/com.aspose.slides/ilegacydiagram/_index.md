---
title: ILegacyDiagram
second_title: Référence de l'API Aspose.Slides pour Java
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
| [convertToGroupShape()](#convertToGroupShape--) | Convertit le diagramme hérité en forme de groupe modifiable. |
### convertToSmartArt() {#convertToSmartArt--}
```
public abstract ISmartArt convertToSmartArt()
```


Convertit le diagramme hérité en objet SmartArt modifiable. L'objet SmartArt créé est ajouté à la forme de groupe parent à la même position.

**Retourne :**
[ISmartArt](../../com.aspose.slides/ismartart) - Objet SmartArt créé.
### convertToGroupShape() {#convertToGroupShape--}
```
public abstract IGroupShape convertToGroupShape()
```


Convertit le diagramme hérité en forme de groupe modifiable. L'objet GroupShape créé est ajouté à la forme de groupe parent à la même position.

**Retourne :**
[IGroupShape](../../com.aspose.slides/igroupshape) - Objet GroupShape créé.