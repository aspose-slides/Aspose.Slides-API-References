---
title: HtmlGenerator
second_title: Aspose.Slides pour Android via la référence API Java
description: Générateur HTML.
type: docs
url: /fr/com.aspose.slides/htmlgenerator/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator)
```
public final class HtmlGenerator implements IHtmlGenerator
```

Générateur HTML.
## Méthodes

| Méthode | Description |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | Ajoute du texte HTML formaté. |
| [addHtml(char[] html)](#addHtml-char---) | Ajoute du texte HTML formaté. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | Ajoute du texte HTML formaté. |
| [addText(String text)](#addText-java.lang.String-) | Ajoute du texte brut aux fichiers HTML, en remplaçant les caractères spéciaux par des entités HTML. |
| [addText(char[] text)](#addText-char---) | Ajoute du texte brut aux fichiers HTML, en remplaçant les caractères spéciaux par des entités HTML. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | Ajoute du texte brut aux fichiers HTML, en remplaçant les caractères spéciaux par des entités HTML. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | Entoure la valeur de l'attribut de guillemets et l'ajoute au fichier HTML. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | Entoure la valeur de l'attribut de guillemets et l'ajoute au fichier HTML. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | Entoure la valeur de l'attribut de guillemets et l'ajoute au fichier HTML. |
| [getSlideImageSize()](#getSlideImageSize--) | Renvoie la taille de l'image de la diapositive. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | Renvoie l'unité dans laquelle la taille de l'image de la diapositive est spécifiée. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | Renvoie le code CSS de l'unité dans laquelle la taille de l'image de la diapositive est spécifiée. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | Renvoie l'index de la diapositive précédemment rendue ou -1 si la première diapositive est en cours de rendu. |
| [getSlideIndex()](#getSlideIndex--) | Renvoie l'index de la diapositive actuellement en cours de rendu. |
| [getNextSlideIndex()](#getNextSlideIndex--) | Renvoie l'index d'une diapositive qui sera rendue après la diapositive actuelle ou -1 si la dernière diapositive est en cours de rendu. |
### addHtml(String html) {#addHtml-java.lang.String-}
```
public final void addHtml(String html)
```


Ajoute du texte HTML formaté.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| html | java.lang.String | Texte à ajouter. |

### addHtml(char[] html) {#addHtml-char---}
```
public final void addHtml(char[] html)
```


Ajoute du texte HTML formaté.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| html | char[] | Texte à ajouter. |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public final void addHtml(char[] html, int startIndex, int length)
```


Ajoute du texte HTML formaté.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| html | char[] | Texte à ajouter. |
| startIndex | int | Index de départ de la portion à ajouter. |
| length | int | Longueur de la portion à ajouter. |

### addText(String text) {#addText-java.lang.String-}
```
public final void addText(String text)
```


Ajoute du texte brut aux fichiers HTML, en remplaçant les caractères spéciaux par des entités HTML. Les sauts de ligne et les espaces ne sont pas remplacés.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte à ajouter. |

### addText(char[] text) {#addText-char---}
```
public final void addText(char[] text)
```


Ajoute du texte brut aux fichiers HTML, en remplaçant les caractères spéciaux par des entités HTML. Les sauts de ligne et les espaces ne sont pas remplacés.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | char[] | Texte à ajouter. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public final void addText(char[] text, int startIndex, int length)
```


Ajoute du texte brut aux fichiers HTML, en remplaçant les caractères spéciaux par des entités HTML. Les sauts de ligne et les espaces ne sont pas remplacés.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | char[] | Texte à ajouter. |
| startIndex | int | Index de départ de la portion à ajouter. |
| length | int | Longueur de la portion à ajouter. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public final void addAttributeValue(String value)
```


Entoure la valeur de l'attribut de guillemets et l'ajoute au fichier HTML.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Chaîne de valeur d'attribut. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public final void addAttributeValue(char[] value)
```


Entoure la valeur de l'attribut de guillemets et l'ajoute au fichier HTML.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | char[] | Chaîne de valeur d'attribut. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public final void addAttributeValue(char[] value, int startIndex, int length)
```


Entoure la valeur de l'attribut de guillemets et l'ajoute au fichier HTML.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | char[] | Chaîne de valeur d'attribut. |
| startIndex | int | Index de départ de la portion à ajouter. |
| length | int | Longueur de la portion à ajouter. |

### getSlideImageSize() {#getSlideImageSize--}
```
public final SizeF getSlideImageSize()
```


Renvoie la taille de l'image de la diapositive. Lecture seule [SizeF](../../com.aspose.slides.android/sizef).

**Renvoie :**
[SizeF](../../com.aspose.slides.android/sizef)
### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public final int getSlideImageSizeUnit()
```


Renvoie l'unité dans laquelle la taille de l'image de la diapositive est spécifiée. Lecture seule [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**Renvoie :**
int
### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public final String getSlideImageSizeUnitCode()
```


Renvoie le code CSS de l'unité dans laquelle la taille de l'image de la diapositive est spécifiée. Lecture seule String.

**Renvoie :**
java.lang.String
### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public final int getPreviousSlideIndex()
```


Renvoie l'index de la diapositive précédemment rendue ou -1 si la première diapositive est en cours de rendu. Lecture seule int.

**Renvoie :**
int
### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```


Renvoie l'index de la diapositive actuellement en cours de rendu. Lecture seule int.

**Renvoie :**
int
### getNextSlideIndex() {#getNextSlideIndex--}
```
public final int getNextSlideIndex()
```


Renvoie l'index d'une diapositive qui sera rendue après la diapositive actuelle ou -1 si la dernière diapositive est en cours de rendu. Lecture seule int.

**Renvoie :**
int