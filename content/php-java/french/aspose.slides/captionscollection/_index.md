---
title: CaptionsCollection
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs
url: /fr/aspose.slides/captionscollection/
---
## CaptionsCollection classe

 Représente une collection des sous-titres fermés.
 
### add {#add}

| Nom | Description |
| --- | --- |
| add (String, String) | Ajoute des sous-titres fermés WebVTT à la fin de la collection. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| label | String | Le libellé des sous-titres fermés. |
| filePath | String | Le chemin vers le fichier WebVTT. |

 **Valeur de retour :**
[Captions](../captions)

 **Exception**

| Erreur | Condition |
| --- | --- |
 | ArgumentException | Lancé si filePath est vide. |


---

### add {#add}

| Nom | Description |
| --- | --- |
| add (String, InputStream) | Ajoute des sous-titres fermés WebVTT à la fin de la collection à partir d'un flux. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| label | String | Le libellé des sous-titres fermés. |
| stream | InputStream | Le flux d'entrée contenant des données au format WebVTT. |

 **Valeur de retour :**
[Captions](../captions)

 **Exception**

| Erreur | Condition |
| --- | --- |
 | ArgumentException | Lancé si les données d'entrée ne sont pas au format WebVTT. |


---

### clear {#clear}

| Nom | Description |
| --- | --- |
| clear () | Supprime tous les sous-titres fermés de la collection. |

 **Valeur de retour :**
void


---

### getCount {#getCount}

| Nom | Description |
| --- | --- |
| getCount () | Renvoie le nombre d'éléments dans la collection. int en lecture seule. |

 **Valeur de retour :**
int


---

### get_Item {#get_Item}

| Nom | Description |
| --- | --- |
| get_Item (int) | Renvoie les sous-titres fermés à l'index spécifié. ICaptions en lecture seule. |

 **Valeur de retour :**
[Captions](../captions)


---

### iterator {#iterator}

| Nom | Description |
| --- | --- |
| iterator () | Renvoie un itérateur qui parcourt la collection. |

 **Valeur de retour :**



---

### remove {#remove}

| Nom | Description |
| --- | --- |
| remove ([Captions](../captions)) | Supprime les sous-titres fermés spécifiés de la collection. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| captions | [Captions](../captions) | Les sous-titres fermés à supprimer. |

 **Valeur de retour :**
void


---

### removeAt {#removeAt}

| Nom | Description |
| --- | --- |
| removeAt (int) | Supprime les sous-titres fermés à l'index spécifié. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index des sous-titres fermés à supprimer. |

 **Valeur de retour :**
void


---