---
title: IBehaviorPropertyCollection
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Représente les propriétés de synchronisation pour le comportement de l'effet.
type: docs
url: /fr/com.aspose.slides/ibehaviorpropertycollection/
---
**Toutes les interfaces implémentées :**
com.aspose.ms.System.Collections.Generic.IGenericList
```
public interface IBehaviorPropertyCollection extends System.Collections.Generic.IGenericList<IBehaviorProperty>
```

Représente les propriétés de synchronisation pour le comportement de l'effet.

## Méthodes

| Méthode | Description |
| --- | --- |
| [add(String propertyValue)](#add-java.lang.String-) | Ajoute une nouvelle propriété à la collection. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | Détermine l'index d'un élément spécifique par valeur de propriété dans la List. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | Insère une nouvelle propriété (avec la valeur de propriété spécifiée) dans la collection à l'index spécifié. |
| [remove(String propertyValue)](#remove-java.lang.String-) | Supprime la propriété spécifiée de la collection. |
| [contains(String propertyValue)](#contains-java.lang.String-) | Détermine si le [IGenericCollection](../../com.aspose.slides/igenericcollection) contient une valeur spécifique. |

### add(String propertyValue) {#add-java.lang.String-}
```
public abstract void add(String propertyValue)
```

Ajoute une nouvelle propriété à la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| propertyValue | java.lang.String | Valeur de la propriété à ajouter. |

### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String propertyValue)
```

Détermine l'index d'un élément spécifique par valeur de propriété dans la List.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| propertyValue | java.lang.String | valeur de la propriété |

**Renvoie :**
int - L'index de la propriété avec la valeur spécifiée

### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public abstract void insert(int index, String propertyValue)
```

Insère une nouvelle propriété (avec la valeur de propriété spécifiée) dans la collection à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index où la nouvelle propriété doit être insérée. |
| propertyValue | java.lang.String | Valeur de la propriété à ajouter. |

### remove(String propertyValue) {#remove-java.lang.String-}
```
public abstract boolean remove(String propertyValue)
```

Supprime la propriété spécifiée de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| propertyValue | java.lang.String | Valeur de la propriété à supprimer. |

**Renvoie :**
boolean - True if a property removed successfully boolean

### contains(String propertyValue) {#contains-java.lang.String-}
```
public abstract boolean contains(String propertyValue)
```

Détermine si le [IGenericCollection](../../com.aspose.slides/igenericcollection) contient une valeur spécifique.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| propertyValue | java.lang.String | Valeur de la propriété à rechercher dans le [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Renvoie :**
boolean - true si propertyValue est trouvé dans le [IGenericCollection](../../com.aspose.slides/igenericcollection) ; sinon, false.