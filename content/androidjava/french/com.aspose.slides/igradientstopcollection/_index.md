---
title: IGradientStopCollection
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente une collection d'arrêts de dégradé.
type: docs
url: /fr/com.aspose.slides/igradientstopcollection/
---
**Toutes les interfaces implémentées :**
com.aspose.slides.IGenericCollection
```
public interface IGradientStopCollection extends IGenericCollection<IGradientStop>
```

Représente une collection d'arrêts de dégradé.
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retourne l'arrêt de dégradé par index. |
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | Crée le nouvel arrêt de dégradé et l'ajoute à la fin de la collection. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Crée le nouvel arrêt de dégradé et l'ajoute à la fin de la collection. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Crée le nouvel arrêt de dégradé et l'ajoute à la fin de la collection. |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | Crée le nouvel arrêt de dégradé et l'insère à l'index spécifié dans la collection. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Crée le nouvel arrêt de dégradé et l'insère à l'index spécifié dans la collection. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Crée le nouvel arrêt de dégradé et l'insère à l'index spécifié dans la collection. |
| [removeAt(int index)](#removeAt-int-) | Supprime un arrêt de dégradé à l'index spécifié. |
| [clear()](#clear--) | Supprime tous les arrêts de dégradé d'une collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IGradientStop get_Item(int index)
```


Retourne l'arrêt de dégradé par index.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Renvoie:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Integer color) {#add-float-java.lang.Integer-}
```
public abstract IGradientStop add(float position, Integer color)
```


Crée le nouvel arrêt de dégradé et l'ajoute à la fin de la collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | float | Position du nouvel arrêt de dégradé. |
| color | java.lang.Integer | Couleur du nouvel arrêt de dégradé. |

**Renvoie:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Index du nouvel arrêt de dégradé dans la collection.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public abstract IGradientStop addPresetColor(float position, int presetColor)
```


Crée le nouvel arrêt de dégradé et l'ajoute à la fin de la collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | float | Position du nouvel arrêt de dégradé. |
| presetColor | int | Couleur du nouvel arrêt de dégradé. |

**Renvoie:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Index du nouvel arrêt de dégradé dans la collection.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public abstract IGradientStop addSchemeColor(float position, int schemeColor)
```


Crée le nouvel arrêt de dégradé et l'ajoute à la fin de la collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | float | Position du nouvel arrêt de dégradé. |
| schemeColor | int | Couleur du nouvel arrêt de dégradé. |

**Renvoie:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Index du nouvel arrêt de dégradé dans la collection.
### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public abstract void insert(int index, float position, Integer color)
```


Crée le nouvel arrêt de dégradé et l'insère à l'index spécifié dans la collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index dans la collection où le nouvel arrêt de dégradé sera inséré. |
| position | float | Position du nouvel arrêt de dégradé. |
| color | java.lang.Integer | Couleur du nouvel arrêt de dégradé. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public abstract void insertPresetColor(int index, float position, int presetColor)
```


Crée le nouvel arrêt de dégradé et l'insère à l'index spécifié dans la collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index dans la collection où le nouvel arrêt de dégradé sera inséré. |
| position | float | Position du nouvel arrêt de dégradé. |
| presetColor | int | Couleur du nouvel arrêt de dégradé. |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public abstract void insertSchemeColor(int index, float position, int schemeColor)
```


Crée le nouvel arrêt de dégradé et l'insère à l'index spécifié dans la collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index dans la collection où le nouvel arrêt de dégradé sera inséré. |
| position | float | Position du nouvel arrêt de dégradé. |
| schemeColor | int | Couleur du nouvel arrêt de dégradé. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Supprime un arrêt de dégradé à l'index spécifié.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index d'un arrêt de dégradé qui doit être supprimé. |

### clear() {#clear--}
```
public abstract void clear()
```


Supprime tous les arrêts de dégradé d'une collection.