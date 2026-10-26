---
title: IGradientStopCollection
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente une collection de points d'arrêt de dégradé.
type: docs
url: /fr/com.aspose.slides/igradientstopcollection/
---
**Toutes les interfaces implémentées:**  
com.aspose.slides.IGenericCollection
```
public interface IGradientStopCollection extends IGenericCollection<IGradientStop>
```

Représente une collection de points d'arrêt de dégradé.
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Renvoie le point d'arrêt de dégradé à l'index. |
| [add(float position, Color color)](#add-float-java.awt.Color-) | Crée le nouveau point d'arrêt de dégradé et l'ajoute à la fin de la collection. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Crée le nouveau point d'arrêt de dégradé et l'ajoute à la fin de la collection. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Crée le nouveau point d'arrêt de dégradé et l'ajoute à la fin de la collection. |
| [insert(int index, float position, Color color)](#insert-int-float-java.awt.Color-) | Crée le nouveau point d'arrêt de dégradé et l'insère à l'index spécifié dans la collection. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Crée le nouveau point d'arrêt de dégradé et l'insère à l'index spécifié dans la collection. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Crée le nouveau point d'arrêt de dégradé et l'insère à l'index spécifié dans la collection. |
| [removeAt(int index)](#removeAt-int-) | Supprime un point d'arrêt de dégradé à l'index spécifié. |
| [clear()](#clear--) | Supprime tous les points d'arrêt de dégradé d'une collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IGradientStop get_Item(int index)
```

Renvoie le point d'arrêt de dégradé à l'index.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Retour:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Color color) {#add-float-java.awt.Color-}
```
public abstract IGradientStop add(float position, Color color)
```

Crée le nouveau point d'arrêt de dégradé et l'ajoute à la fin de la collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | float | Position du nouveau point d'arrêt de dégradé. |
| color | java.awt.Color | Couleur du nouveau point d'arrêt de dégradé. |

**Retour:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Index du nouveau point d'arrêt de dégradé dans la collection.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public abstract IGradientStop addPresetColor(float position, int presetColor)
```

Crée le nouveau point d'arrêt de dégradé et l'ajoute à la fin de la collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | float | Position du nouveau point d'arrêt de dégradé. |
| presetColor | int | Couleur du nouveau point d'arrêt de dégradé. |

**Retour:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Index du nouveau point d'arrêt de dégradé dans la collection.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public abstract IGradientStop addSchemeColor(float position, int schemeColor)
```

Crée le nouveau point d'arrêt de dégradé et l'ajoute à la fin de la collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | float | Position du nouveau point d'arrêt de dégradé. |
| schemeColor | int | Couleur du nouveau point d'arrêt de dégradé. |

**Retour:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Index du nouveau point d'arrêt de dégradé dans la collection.
### insert(int index, float position, Color color) {#insert-int-float-java.awt.Color-}
```
public abstract void insert(int index, float position, Color color)
```

Crée le nouveau point d'arrêt de dégradé et l'insère à l'index spécifié dans la collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Indice dans la collection où le nouveau point d'arrêt de dégradé sera inséré. |
| position | float | Position du nouveau point d'arrêt de dégradé. |
| color | java.awt.Color | Couleur du nouveau point d'arrêt de dégradé. |
### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public abstract void insertPresetColor(int index, float position, int presetColor)
```

Crée le nouveau point d'arrêt de dégradé et l'insère à l'index spécifié dans la collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Indice dans la collection où le nouveau point d'arrêt de dégradé sera inséré. |
| position | float | Position du nouveau point d'arrêt de dégradé. |
| presetColor | int | Couleur du nouveau point d'arrêt de dégradé. |
### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public abstract void insertSchemeColor(int index, float position, int schemeColor)
```

Crée le nouveau point d'arrêt de dégradé et l'insère à l'index spécifié dans la collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Indice dans la collection où le nouveau point d'arrêt de dégradé sera inséré. |
| position | float | Position du nouveau point d'arrêt de dégradé. |
| schemeColor | int | Couleur du nouveau point d'arrêt de dégradé. |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Supprime un point d'arrêt de dégradé à l'index spécifié.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Indice du point d'arrêt de dégradé qui doit être supprimé. |
### clear() {#clear--}
```
public abstract void clear()
```

Supprime tous les points d'arrêt de dégradé d'une collection.