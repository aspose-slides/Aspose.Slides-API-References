---
title: SensitivityLabelCollection
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Représente une collection de labels de sensibilité appliqués au document.
type: docs
url: /fr/com.aspose.slides/sensitivitylabelcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)
```
public final class SensitivityLabelCollection extends DomObject<Presentation> implements ISensitivityLabelCollection
```

Représente une collection de labels de sensibilité appliqués au document.
## Méthodes

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retourne le label de sensibilité par index. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | Ajoute le label de sensibilité à la fin de la collection. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | Ajoute un SensitivityLabel à la collection. |
| [removeAt(int index)](#removeAt-int-) | Supprime le label de sensibilité à l'index spécifié. |
| [clear()](#clear--) | Supprime tous les éléments de la collection. |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [getCount()](#getCount--) | Renvoie le nombre d'éléments dans la collection. |
| [copyTo(ISensitivityLabel[] array, int index)](#copyTo-com.aspose.slides.ISensitivityLabel---int-) | Copie tous les éléments de la collection dans le tableau spécifié. |
### get_Item(int index) {#get-Item-int-}
```
public final ISensitivityLabel get_Item(int index)
```


Retourne le label de sensibilité par index.

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Renvoie :**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public final ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```


Ajoute le label de sensibilité à la fin de la collection.

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| id | java.lang.String | L'identifiant du label de sensibilité. |
| siteId | java.util.UUID | L'identifiant du site Azure Active Directory (Azure AD). |
| isEnabled | boolean | Indique si le label de sensibilité est activé. |
| methodType | int | La méthode d'affectation du label de sensibilité. |

**Renvoie :**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public final int add(ISensitivityLabel label)
```


Ajoute un SensitivityLabel à la collection.

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | L'objet SensitivityLabel à ajouter à la fin de la collection. |

**Renvoie :**
int - L'indice auquel le SensitivityLabel a été ajouté.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Supprime le label de sensibilité à l'index spécifié.

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indice du label de sensibilité à supprimer. |

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

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISensitivityLabel> - Un System.Collections.Generic.IEnumerator1 qui peut être utilisé pour parcourir la collection.
### getCount() {#getCount--}
```
public final int getCount()
```


Renvoie le nombre d'éléments dans la collection. Lecture seule int .

**Renvoie :**
int
### copyTo(ISensitivityLabel[] array, int index) {#copyTo-com.aspose.slides.ISensitivityLabel---int-}
```
public final void copyTo(ISensitivityLabel[] array, int index)
```


Copie tous les éléments de la collection dans le tableau spécifié.

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [ISensitivityLabel\[\]](../../com.aspose.slides/isensitivitylabel) | Tableau cible. |
| index | int | Indice de départ dans le tableau cible. |