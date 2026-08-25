---
title: MathParagraph
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/mathparagraph/
---
## MathParagraph classe

Paragraphe mathématique qui est un conteneur pour les blocs mathématiques (IMathBlock)
 
### MathParagraph {#MathParagraph}

| Nom | Description |
| --- | --- |
| MathParagraph() | Initialise une nouvelle instance de la classe MathParagraph. |

 **Retour :**
MathParagraph


---


### MathParagraph {#MathParagraph}

| Nom | Description |
| --- | --- |
| MathParagraph([MathBlock](../mathblock)) | Initialise une nouvelle instance de la classe MathParagraph. |

 **Retour :**
MathParagraph


---


### add {#add}

| Nom | Description |
| --- | --- |
| add ([MathBlock](../mathblock)) | Ajoute IMathBlock à la fin de la collection. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| mathBlock | [MathBlock](../mathblock) | Un bloc mathématique qui sera ajouté à la fin de la collection |

 **Retour :**
void


---


### clear {#clear}

| Nom | Description |
| --- | --- |
| clear () | Supprime tous les éléments de la collection. |

 **Retour :**
void


---


### contains {#contains}

| Nom | Description |
| --- | --- |
| contains ([MathBlock](../mathblock)) | Détermine si la collection contient une valeur spécifique. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| mathBlock | [MathBlock](../mathblock) | L'objet à localiser dans la collection. |

 **Retour :**
boolean


---


### getCount {#getCount}

| Nom | Description |
| --- | --- |
| getCount () | Obtient le nombre d'éléments réellement contenus dans la collection. Lecture seule int. |

 **Retour :**
int


---


### getJustification {#getJustification}

| Nom | Description |
| --- | --- |
| getJustification () | Justification du paragraphe Valeur par défaut : CenteredAsGroup |

 **Retour :**
int


---


### get_Item {#get_Item}

| Nom | Description |
| --- | --- |
| get_Item (int) | Obtient l'élément à l'index spécifié. Lecture seule IMathBlock. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro de l'élément à obtenir |

 **Retour :**
[MathBlock](../mathblock)


---


### indexOf {#indexOf}

| Nom | Description |
| --- | --- |
| indexOf ([MathBlock](../mathblock)) | Détermine l'index d'un IMathBlock spécifique dans la collection. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| mathBlock | [MathBlock](../mathblock) | L'élément à localiser dans la collection. |

 **Retour :**
int


---


### insert {#insert}

| Nom | Description |
| --- | --- |
| insert (int, [MathBlock](../mathblock)) | Insère IMathBlock dans la collection à l'index spécifié. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro auquel l'élément doit être inséré. |
| mathBlock | [MathBlock](../mathblock) | L'IMathBlock à insérer. |

 **Retour :**
void


---


### iterator {#iterator}

| Nom | Description |
| --- | --- |
| iterator () |  |

 **Retour :**



---


### iteratorJava {#iteratorJava}

| Nom | Description |
| --- | --- |
| iteratorJava () |  |

 **Retour :**



---


### remove {#remove}

| Nom | Description |
| --- | --- |
| remove ([MathBlock](../mathblock)) | Supprime la première occurrence d'un objet spécifique de la collection. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| mathBlock | [MathBlock](../mathblock) | L'objet à supprimer de la collection. |

 **Retour :**
boolean


---


### removeAt {#removeAt}

| Nom | Description |
| --- | --- |
| removeAt (int) | Supprime un élément à l'index spécifié de la collection. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro de l'élément à supprimer. |

 **Retour :**
void


---


### setJustification {#setJustification}

| Nom | Description |
| --- | --- |
| setJustification (int) | Justification du paragraphe Valeur par défaut : CenteredAsGroup |

 **Retour :**
void


---


### set_Item {#set_Item}

| Nom | Description |
| --- | --- |
| set_Item (int, [MathBlock](../mathblock)) | Obtient l'élément à l'index spécifié. Lecture seule IMathBlock. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| value | int | Le bloc d'un texte mathématique. |
| index | [MathBlock](../mathblock) | L'index basé sur zéro de l'élément à obtenir |

 **Retour :**
void


---


### toLatex {#toLatex}

| Nom | Description |
| --- | --- |
| toLatex () | Obtient l'équation mathématique au format LaTeX |

 **Retour :**
String


---


### writeAsMathMl {#writeAsMathMl}

| Nom | Description |
| --- | --- |
| writeAsMathMl (OutputStream) | Enregistre le contenu de ce MathParagraph au format MathML |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| stream | OutputStream | Flux cible |

 **Retour :**
void


---