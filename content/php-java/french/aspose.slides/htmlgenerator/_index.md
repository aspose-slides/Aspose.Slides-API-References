---
title: HtmlGenerator
second_title: Aspose.Sildes pour PHP via la Référence de l'API Java
description: 
type: docs

url: /fr/aspose.slides/htmlgenerator/
---
## classe HtmlGenerator

 Générateur HTML.
 
### addAttributeValue {#addAttributeValue}

| Nom | Description |
| --- | --- |
| addAttributeValue (String) | Entoure la valeur de l'attribut de guillemets et l'ajoute au fichier html. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| value | String | Chaîne de valeur d'attribut. |

 **Renvoie :**
void


---


### addAttributeValue {#addAttributeValue}

| Nom | Description |
| --- | --- |
| addAttributeValue (char[]) | Entoure la valeur de l'attribut de guillemets et l'ajoute au fichier html. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| value | char[] | Chaîne de valeur d'attribut. |

 **Renvoie :**
void


---


### addAttributeValue {#addAttributeValue}

| Nom | Description |
| --- | --- |
| addAttributeValue (char[], int, int) | Entoure la valeur de l'attribut de guillemets et l'ajoute au fichier html. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| value | char[] | Chaîne de valeur d'attribut. |
| startIndex | int | Indice de départ de la portion à ajouter. |
| length | int | Longueur de la portion à ajouter. |

 **Renvoie :**
void


---


### addHtml {#addHtml}

| Nom | Description |
| --- | --- |
| addHtml (String) | Ajoute du texte HTML formaté. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| html | String | Texte à ajouter. |

 **Renvoie :**
void


---


### addHtml {#addHtml}

| Nom | Description |
| --- | --- |
| addHtml (char[]) | Ajoute du texte HTML formaté. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| html | char[] | Texte à ajouter. |

 **Renvoie :**
void


---


### addHtml {#addHtml}

| Nom | Description |
| --- | --- |
| addHtml (char[], int, int) | Ajoute du texte HTML formaté. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| html | char[] | Texte à ajouter. |
| startIndex | int | Indice de départ de la portion à ajouter. |
| length | int | Longueur de la portion à ajouter. |

 **Renvoie :**
void


---


### addText {#addText}

| Nom | Description |
| --- | --- |
| addText (String) | Ajoute du texte brut aux fichiers html, en remplaçant les caractères spéciaux par des entités html. Les sauts de ligne et les espaces blancs ne sont pas remplacés. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| text | String | Texte à ajouter. |

 **Renvoie :**
void


---


### addText {#addText}

| Nom | Description |
| --- | --- |
| addText (char[]) | Ajoute du texte brut aux fichiers html, en remplaçant les caractères spéciaux par des entités html. Les sauts de ligne et les espaces blancs ne sont pas remplacés. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| text | char[] | Texte à ajouter. |

 **Renvoie :**
void


---


### addText {#addText}

| Nom | Description |
| --- | --- |
| addText (char[], int, int) | Ajoute du texte brut aux fichiers html, en remplaçant les caractères spéciaux par des entités html. Les sauts de ligne et les espaces blancs ne sont pas remplacés. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| text | char[] | Texte à ajouter. |
| startIndex | int | Indice de départ de la portion à ajouter. |
| length | int | Longueur de la portion à ajouter. |

 **Renvoie :**
void


---


### getNextSlideIndex {#getNextSlideIndex}

| Nom | Description |
| --- | --- |
| getNextSlideIndex () | Renvoie l'indice d'une diapositive qui sera rendue après la diapositive actuelle ou -1 si la dernière diapositive est en cours de rendu. Lecture seule int. |

 **Renvoie :**
int


---


### getPreviousSlideIndex {#getPreviousSlideIndex}

| Nom | Description |
| --- | --- |
| getPreviousSlideIndex () | Renvoie l'indice de la diapositive précédemment rendue ou -1 si la première diapositive est en cours de rendu. Lecture seule int. |

 **Renvoie :**
int


---


### getSlideImageSize {#getSlideImageSize}

| Nom | Description |
| --- | --- |
| getSlideImageSize () | Renvoie la taille de l'image de la diapositive. Lecture seule java.awt.geom.Dimension2D. |

 **Renvoie :**
Dimension2D


---


### getSlideImageSizeUnit {#getSlideImageSizeUnit}

| Nom | Description |
| --- | --- |
| getSlideImageSizeUnit () | Renvoie l'unité dans laquelle la taille de l'image de la diapositive est spécifiée. Lecture seule SvgCoordinateUnit. |

 **Renvoie :**
int


---


### getSlideImageSizeUnitCode {#getSlideImageSizeUnitCode}

| Nom | Description |
| --- | --- |
| getSlideImageSizeUnitCode () | Renvoie un code CSS de l'unité dans laquelle la taille de l'image de la diapositive est spécifiée. Lecture seule String. |

 **Renvoie :**
String


---


### getSlideIndex {#getSlideIndex}

| Nom | Description |
| --- | --- |
| getSlideIndex () | Renvoie l'indice de la diapositive en cours de rendu. Lecture seule int. |

 **Renvoie :**
int


---