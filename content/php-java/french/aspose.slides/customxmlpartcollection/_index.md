---
title: CustomXmlPartCollection
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/customxmlpartcollection/
---
## CustomXmlPartCollection classe

Représente une collection de parties XML personnalisées.

### add {#add}

| Nom | Description |
| --- | --- |
| add (String) | Ajoute une nouvelle partie XML personnalisée. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| xmlString | String | La chaîne XML de la nouvelle partie à ajouter. |

**Retour:**
[CustomXmlPart](../customxmlpart)

**Exception**

| Erreur | Condition |
| --- | --- |
| com.aspose.ms.System.ArgumentException | xmlString est vide ou les données XML sont invalides. |

---

### add {#add}

| Nom | Description |
| --- | --- |
| add (byte[]) | Ajoute une nouvelle partie XML personnalisée. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| xmlData | byte[] | Les données XML de la nouvelle partie à ajouter. |

**Retour:**
[CustomXmlPart](../customxmlpart)

**Exception**

| Erreur | Condition |
| --- | --- |
| com.aspose.ms.System.ArgumentException | xmlData est vide ou invalide. |

---

### add {#add}

| Nom | Description |
| --- | --- |
| add (InputStream) | Ajoute une nouvelle partie XML personnalisée. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| inputStream | InputStream | Le flux d'entrée contenant les données XML de la nouvelle partie à ajouter. |

**Retour:**
[CustomXmlPart](../customxmlpart)

**Exception**

| Erreur | Condition |
| --- | --- |
| com.aspose.ms.System.ArgumentException | Les données dans inputStream sont vides ou invalides. |

---

### clear {#clear}

| Nom | Description |
| --- | --- |
| clear () | Supprime tous les éléments de la collection. |

**Retour:**
void

---

### getSyncRoot {#getSyncRoot}

| Nom | Description |
| --- | --- |
| getSyncRoot () | Retourne une racine de synchronisation. Objet en lecture seule. |

**Retour:**
Object

---

### get_Item {#get_Item}

| Nom | Description |
| --- | --- |
| get_Item (int) | Retourne l'élément à l'index spécifié. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro de l'élément à obtenir. |

**Retour:**
[CustomXmlPart](../customxmlpart)

**Exception**

| Erreur | Condition |
| --- | --- |
| com.aspose.ms.System.ArgumentOutOfRangeException | index est inférieur à 0 ou égal/plus grand que Count. |

---

### isSynchronized {#isSynchronized}

| Nom | Description |
| --- | --- |
| isSynchronized () | Retourne une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). Booléen en lecture seule. |

**Retour:**
boolean

---

### iterator {#iterator}

| Nom | Description |
| --- | --- |
| iterator () | Retourne un itérateur qui parcourt la collection. |

**Retour:**

---

### iteratorJava {#iteratorJava}

| Nom | Description |
| --- | --- |
| iteratorJava () | Retourne un itérateur Java pour l'ensemble de la collection. |

**Retour:**

---

### remove {#remove}

| Nom | Description |
| --- | --- |
| remove ([CustomXmlPart](../customxmlpart)) | Supprime la première occurrence d'un objet spécifique de la collection. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| item | [CustomXmlPart](../customxmlpart) | La partie XML personnalisée à supprimer. |

**Retour:**
boolean

**Exception**

| Erreur | Condition |
| --- | --- |
| com.aspose.ms.System.ArgumentNullException | item est nul. |

---

### removeAt {#removeAt}

| Nom | Description |
| --- | --- |
| removeAt (int) | Supprime la partie XML personnalisée à l'index spécifié. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro de l'élément à supprimer. |

**Retour:**
void

**Exception**

| Erreur | Condition |
| --- | --- |
| com.aspose.ms.System.ArgumentOutOfRangeException | index est inférieur à 0 ou égal/plus grand que Count. |

---

### size {#size}

| Nom | Description |
| --- | --- |
| size () | Retourne le nombre de parties XML personnalisées dans la collection. int en lecture seule. |

**Retour:**
int