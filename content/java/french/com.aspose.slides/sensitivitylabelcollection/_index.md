---
title: SensitivityLabelCollection
second_title: Référence API Aspose.Slides pour Java
description: Représente une collection d'étiquettes de sensibilité appliquées au document.
type: docs
url: /fr/com.aspose.slides/sensitivitylabelcollection/
---
**Héritage :**
java.lang.Object, com.aspose.slides.DomObject

**Toutes les interfaces implémentées :**
[com.aspose.slides.ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)
```
public final class SensitivityLabelCollection extends DomObject<Presentation> implements ISensitivityLabelCollection
```

Représente une collection d'étiquettes de sensibilité appliquées au document.
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Renvoie l'étiquette de sensibilité par index. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | Ajoute l'étiquette de sensibilité à la fin de la collection. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | Ajoute un SensitivityLabel à la collection. |
| [removeAt(int index)](#removeAt-int-) | Supprime l'étiquette de sensibilité à l'index spécifié. |
| [clear()](#clear--) | Supprime tous les éléments de la collection. |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [getCount()](#getCount--) | Renvoie le nombre d'éléments dans la collection. |
| [copyTo(ISensitivityLabel[] array, int index)](#copyTo-com.aspose.slides.ISensitivityLabel---int-) | Copie tous les éléments de la collection dans le tableau spécifié. |
### get_Item(int index) {#get-Item-int-}
```
public final ISensitivityLabel get_Item(int index)
```


Renvoie l'étiquette de sensibilité par index.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Retour :**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public final ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```


Ajoute l'étiquette de sensibilité à la fin de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| id | java.lang.String | L'identifiant de l'étiquette de sensibilité. |
| siteId | java.util.UUID | L'identifiant du site Azure Active Directory (Azure AD). |
| isEnabled | boolean | Indicateur indiquant si l'étiquette de sensibilité est activée. |
| methodType | int | La méthode d'affectation de l'étiquette de sensibilité. |

**Retour :**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public final int add(ISensitivityLabel label)
```


Ajoute un SensitivityLabel à la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | L'objet SensitivityLabel à ajouter à la fin de la collection. |

**Retour :**
int - L'index auquel le SensitivityLabel a été ajouté.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Supprime l'étiquette de sensibilité à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index de l'étiquette de sensibilité à supprimer. |

### clear() {#clear--}
```
public final void clear()
```


Supprime tous les éléments de la collection.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISensitivityLabel> iterator()
```


Renvoie un énumérateur qui parcourt la collection.

**Retour :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISensitivityLabel> - A  System.Collections.Generic.IEnumerator1  that can be used to iterate through the collection.
### getCount() {#getCount--}
```
public final int getCount()
```


Renvoie le nombre d'éléments dans la collection. Lecture seule  int .

**Retour :**
int
### copyTo(ISensitivityLabel[] array, int index) {#copyTo-com.aspose.slides.ISensitivityLabel---int-}
```
public final void copyTo(ISensitivityLabel[] array, int index)
```


Copie tous les éléments de la collection dans le tableau spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| array | [ISensitivityLabel\[\]](../../com.aspose.slides/isensitivitylabel) | Tableau cible. |
| index | int | Index de départ dans le tableau cible. |