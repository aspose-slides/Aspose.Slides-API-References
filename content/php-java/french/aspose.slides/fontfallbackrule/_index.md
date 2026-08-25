---
title: FontFallBackRule
second_title: Aspose.Sildes pour PHP via la référence d'API Java
description: 
type: docs
url: /fr/aspose.slides/fontfallbackrule/
---
## classe FontFallBackRule

 Représente la règle de secours de police
 
### FontFallBackRule {#FontFallBackRule}

| Nom | Description |
| --- | --- |
| FontFallBackRule(long, long, String) | Crée une nouvelle instance. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| startIndex | long | Index de départ de la plage unicode |
| endIndex | long | Index de fin de la plage unicode |
| fontNames | String | Nom ou noms de police (délimités par une virgule) pour le secours |

 **Retour :**
FontFallBackRule


---

### FontFallBackRule {#FontFallBackRule}

| Nom | Description |
| --- | --- |
| FontFallBackRule(long, long, java.lang.String[]) | Crée une nouvelle instance. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| startIndex | long | Index de départ de la plage unicode |
| endIndex | long | Index de fin de la plage unicode |
| fontNames | java.lang.String[] | Nom ou noms de police (délimités par une virgule) pour le secours |

 **Retour :**
FontFallBackRule


---

### addFallBackFonts {#addFallBackFonts}

| Nom | Description |
| --- | --- |
| addFallBackFonts (String) | Ajoute une ou plusieurs nouvelles police(s) à la liste des polices de secours. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| fontName | String | Nom de la police ou noms (délimités par une virgule) pour le secours |

 **Retour :**
void


---

### addFallBackFonts {#addFallBackFonts}

| Nom | Description |
| --- | --- |
| addFallBackFonts (java.lang.String[]) | Ajoute de nouvelles polices à la liste des polices de secours. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| fontNames | java.lang.String[] | Nom ou noms de police (délimités par une virgule) pour le secours |

 **Retour :**
void


---

### clear {#clear}

| Nom | Description |
| --- | --- |
| clear () | Supprime toutes les polices de la liste. |

 **Retour :**
void


---

### getCount {#getCount}

| Nom | Description |
| --- | --- |
| getCount () | Obtient le nombre de polices effectivement définies pour la plage. int en lecture seule. |

 **Retour :**
int


---

### getRangeEndIndex {#getRangeEndIndex}

| Nom | Description |
| --- | --- |
| getRangeEndIndex () | Obtient l'index final de la plage unicode continue. |

 **Retour :**
long


---

### getRangeStartIndex {#getRangeStartIndex}

| Nom | Description |
| --- | --- |
| getRangeStartIndex () | Obtient l'index de départ de la plage unicode continue. |

 **Retour :**
long


---

### get_Item {#get_Item}

| Nom | Description |
| --- | --- |
| get_Item (int) | Obtient le nom de police à l'index spécifié. IFontFallBackRule en lecture seule. |

 **Retour :**
String


---

### indexOf {#indexOf}

| Nom | Description |
| --- | --- |
| indexOf (String) | Renvoie l'index de la règle spécifiée dans la collection. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| fontName | String | Nom de la police à rechercher. |

 **Retour :**
int


---

### remove {#remove}

| Nom | Description |
| --- | --- |
| remove (String) | Supprime la première occurrence d'une police de secours spécifique de la liste. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| fontName | String | Nom de la police à supprimer de la liste. |

 **Retour :**
void


---

### removeAt {#removeAt}

| Nom | Description |
| --- | --- |
| removeAt (int) | Supprime la police de secours à l'index spécifié de la liste. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro de la police à supprimer. |

 **Retour :**
void


---

### setRangeEndIndex {#setRangeEndIndex}

| Nom | Description |
| --- | --- |
| setRangeEndIndex (long) | Définit l'index final de la plage unicode continue. |

 **Retour :**
void


---

### setRangeStartIndex {#setRangeStartIndex}

| Nom | Description |
| --- | --- |
| setRangeStartIndex (long) | Définit l'index de départ de la plage unicode continue. |

 **Retour :**
void


---

### toArray {#toArray}

| Nom | Description |
| --- | --- |
| toArray () | Crée et renvoie un tableau contenant toutes les polices de secours pour cette règle. |

 **Retour :**
String


---

### toArray {#toArray}

| Nom | Description |
| --- | --- |
| toArray (int, int) | Crée et renvoie un tableau contenant toutes les polices de secours de la plage spécifiée dans la liste. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| startIndex | int | L'index de la première police à ajouter. |
| count | int | Le nombre de polices à ajouter. |

 **Retour :**
String


---