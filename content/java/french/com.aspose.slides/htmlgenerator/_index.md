---
title: HtmlGenerator
second_title: Référence de l'API Aspose.Slides pour Java
description: Générateur HTML.
type: docs
url: /fr/com.aspose.slides/htmlgenerator/
---
**Héritage:**  
java.lang.Object  

**Toutes les interfaces implémentées:**  
[com.aspose.slides.IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator)  
```
public final class HtmlGenerator implements IHtmlGenerator
```  

Générateur Html.  
## Méthodes  

| Méthode | Description |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | Ajoute du texte HTML formaté. |
| [addHtml(char[] html)](#addHtml-char---) | Ajoute du texte HTML formaté. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | Ajoute du texte HTML formaté. |
| [addText(String text)](#addText-java.lang.String-) | Ajoute du texte brut aux fichiers html, en remplaçant les caractères spéciaux par des entités html. |
| [addText(char[] text)](#addText-char---) | Ajoute du texte brut aux fichiers html, en remplaçant les caractères spéciaux par des entités html. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | Ajoute du texte brut aux fichiers html, en remplaçant les caractères spéciaux par des entités html. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | Entoure la valeur de l’attribut de guillemets et l’ajoute au fichier html. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | Entoure la valeur de l’attribut de guillemets et l’ajoute au fichier html. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | Entoure la valeur de l’attribut de guillemets et l’ajoute au fichier html. |
| [getSlideImageSize()](#getSlideImageSize--) | Renvoie la taille de l’image de diapositive. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | Renvoie l’unité dans laquelle la taille de l’image de diapositive est spécifiée. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | Renvoie le code CSS de l’unité dans laquelle la taille de l’image de diapositive est spécifiée. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | Renvoie l’indice de la diapositive précédemment rendue ou -1 si la première diapositive est en cours de rendu. |
| [getSlideIndex()](#getSlideIndex--) | Renvoie l’indice de la diapositive actuellement rendue. |
| [getNextSlideIndex()](#getNextSlideIndex--) | Renvoie l’indice d’une diapositive qui sera rendue après la diapositive actuelle ou -1 si la dernière diapositive est en cours de rendu. |

### addHtml(String html) {#addHtml-java.lang.String-}
```
public final void addHtml(String html)
```

Ajoute du texte HTML formaté.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| html | java.lang.String | Texte à ajouter. |

### addHtml(char[] html) {#addHtml-char---}
```
public final void addHtml(char[] html)
```

Ajoute du texte HTML formaté.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| html | char[] | Texte à ajouter. |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public final void addHtml(char[] html, int startIndex, int length)
```

Ajoute du texte HTML formaté.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| html | char[] | Texte à ajouter. |
| startIndex | int | Index de départ de la portion à ajouter. |
| length | int | Longueur de la portion à ajouter. |

### addText(String text) {#addText-java.lang.String-}
```
public final void addText(String text)
```

Ajoute du texte brut aux fichiers html, en remplaçant les caractères spéciaux par des entités html. Les sauts de ligne et les espaces blancs ne sont pas remplacés.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte à ajouter. |

### addText(char[] text) {#addText-char---}
```
public final void addText(char[] text)
```

Ajoute du texte brut aux fichiers html, en remplaçant les caractères spéciaux par des entités html. Les sauts de ligne et les espaces blancs ne sont pas remplacés.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| text | char[] | Texte à ajouter. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public final void addText(char[] text, int startIndex, int length)
```

Ajoute du texte brut aux fichiers html, en remplaçant les caractères spéciaux par des entités html. Les sauts de ligne et les espaces blancs ne sont pas remplacés.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| text | char[] | Texte à ajouter. |
| startIndex | int | Index de départ de la portion à ajouter. |
| length | int | Longueur de la portion à ajouter. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public final void addAttributeValue(String value)
```

Entoure la valeur de l’attribut de guillemets et l’ajoute au fichier html.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Chaîne de valeur d’attribut. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public final void addAttributeValue(char[] value)
```

Entoure la valeur de l’attribut de guillemets et l’ajoute au fichier html.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | char[] | Chaîne de valeur d’attribut. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public final void addAttributeValue(char[] value, int startIndex, int length)
```

Entoure la valeur de l’attribut de guillemets et l’ajoute au fichier html.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | char[] | Chaîne de valeur d’attribut. |
| startIndex | int | Index de départ de la portion à ajouter. |
| length | int | Longueur de la portion à ajouter. |

### getSlideImageSize() {#getSlideImageSize--}
```
public final Dimension2D getSlideImageSize()
```

Renvoie la taille de l’image de diapositive. Lecture seule java.awt.geom.Dimension2D.

**Retour:**  
java.awt.geom.Dimension2D

### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public final int getSlideImageSizeUnit()
```

Renvoie l’unité dans laquelle la taille de l’image de diapositive est spécifiée. Lecture seule [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**Retour:**  
int

### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public final String getSlideImageSizeUnitCode()
```

Renvoie le code CSS de l’unité dans laquelle la taille de l’image de diapositive est spécifiée. Lecture seule String.

**Retour:**  
java.lang.String

### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public final int getPreviousSlideIndex()
```

Renvoie l’indice de la diapositive précédemment rendue ou -1 si la première diapositive est en cours de rendu. Lecture seule int.

**Retour:**  
int

### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```

Renvoie l’indice de la diapositive actuellement rendue. Lecture seule int.

**Retour:**  
int

### getNextSlideIndex() {#getNextSlideIndex--}
```
public final int getNextSlideIndex()
```

Renvoie l’indice d’une diapositive qui sera rendue après la diapositive actuelle ou -1 si la dernière diapositive est en cours de rendu. Lecture seule int.

**Retour:**  
int