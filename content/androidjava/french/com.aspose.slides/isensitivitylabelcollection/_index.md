---
title: ISensitivityLabelCollection
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente une collection d'étiquettes de sensibilité appliquées au document.
type: docs
url: /fr/com.aspose.slides/isensitivitylabelcollection/
---
**Toutes les interfaces implémentées :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISensitivityLabelCollection extends System.Collections.Generic.IGenericEnumerable<ISensitivityLabel>
```

Représente une collection d'étiquettes de sensibilité appliquées au document.

## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Renvoie l'étiquette de sensibilité par indice. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | Ajoute l'étiquette de sensibilité à la fin de la collection. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | Ajoute un SensitivityLabel à la collection. |
| [removeAt(int index)](#removeAt-int-) | Supprime l'étiquette de sensibilité à l'indice spécifié. |
| [clear()](#clear--) | Supprime tous les éléments de la collection. |
| [getCount()](#getCount--) | Obtient le nombre de tous les éléments de la collection. |

### get_Item(int index) {#get-Item-int-}
```
public abstract ISensitivityLabel get_Item(int index)
```

Renvoie l'étiquette de sensibilité par indice. Lecture seule [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Valeur de retour :**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)

### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public abstract ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```

Ajoute l'étiquette de sensibilité à la fin de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| id | java.lang.String | L'identifiant de l'étiquette de sensibilité. |
| siteId | java.util.UUID | L'identifiant du site Azure Active Directory (Azure AD). |
| isEnabled | boolean | Indicateur indiquant si l'étiquette de sensibilité est activée. |
| methodType | int | La méthode d'affectation de l'étiquette de sensibilité. |

**Valeur de retour :**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)

### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public abstract int add(ISensitivityLabel label)
```

Ajoute un SensitivityLabel à la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | L'objet SensitivityLabel à ajouter à la fin de la collection. |

**Valeur de retour :**
int - L'index auquel le SensitivityLabel a été ajouté.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Supprime l'étiquette de sensibilité à l'indice spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Indice de l'étiquette de sensibilité à supprimer. |

### clear() {#clear--}
```
public abstract void clear()
```

Supprime tous les éléments de la collection.

### getCount() {#getCount--}
```
public abstract int getCount()
```

Obtient le nombre de tous les éléments de la collection. Lecture seule int .

**Valeur de retour :**
int