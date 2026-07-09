---
title: IChartCategoryLevelsManager
second_title: Aspose.Slides pour Android via Référence de l'API Java
description: Conteneur géré des valeurs des niveaux de catégorie du graphique.
type: docs
url: /fr/com.aspose.slides/ichartcategorylevelsmanager/
---```
public interface IChartCategoryLevelsManager
```

Conteneur géré des valeurs des niveaux de catégorie du graphique.
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Renvoie l'objet IChartDataCell pour le niveau défini. |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | Définit l'élément de regroupement pour le niveau défini. |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | Supprime l'élément de regroupement pour le niveau défini. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int level)
```

Renvoie l'objet IChartDataCell pour le niveau défini.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| level | int |  |

**Renvoie:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setGroupingItem(int level, Object value) {#setGroupingItem-int-java.lang.Object-}
```
public abstract void setGroupingItem(int level, Object value)
```

Définit l'élément de regroupement pour le niveau défini.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| level | int | Niveau de catégorie int |
| value | java.lang.Object | Objet d'élément de regroupement |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public abstract void deleteGroupingItem(int level)
```

Supprime l'élément de regroupement pour le niveau défini.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| level | int | Niveau de catégorie int |