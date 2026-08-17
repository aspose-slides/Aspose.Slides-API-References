---
title: IHtmlGenerator
second_title: Aspose.Slides pour Java Référence de l'API
description: Générateur HTML.
type: docs
url: /fr/com.aspose.slides/ihtmlgenerator/
---```
public interface IHtmlGenerator
```

Générateur HTML.
## Méthodes

| Méthode | Description |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | Ajoute du texte HTML formaté. |
| [addHtml(char[] html)](#addHtml-char---) | Ajoute du texte HTML formaté. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | Ajoute du texte HTML formaté. |
| [addText(String text)](#addText-java.lang.String-) | Ajoute du texte brut aux fichiers html, en remplaçant les caractères spéciaux par des entités html. |
| [addText(char[] text)](#addText-char---) | Ajoute du texte brut aux fichiers html, en remplaçant les caractères spéciaux par des entités html. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | Ajoute du texte brut aux fichiers html, en remplaçant les caractères spéciaux par des entités html. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | Cite la valeur d'attribut et l'ajoute au fichier html. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | Cite la valeur d'attribut et l'ajoute au fichier html. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | Cite la valeur d'attribut et l'ajoute au fichier html. |
| [getSlideImageSize()](#getSlideImageSize--) | Renvoie la taille de l'image de la diapositive. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | Renvoie l'unité dans laquelle la taille de l'image de la diapositive est spécifiée. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | Renvoie le code CSS de l'unité dans laquelle la taille de l'image de la diapositive est spécifiée. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | Renvoie l'index de la diapositive précédemment rendue ou -1 si la première diapositive est rendue. |
| [getSlideIndex()](#getSlideIndex--) | Renvoie l'index de la diapositive en cours de rendu. |
| [getNextSlideIndex()](#getNextSlideIndex--) | Renvoie l'index d'une diapositive qui sera rendue après la diapositive actuelle ou -1 si la dernière diapositive est en cours de rendu. |

### addHtml(String html) {#addHtml-java.lang.String-}
```
public abstract void addHtml(String html)
```

Ajoute du texte HTML formaté.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| html | java.lang.String | Texte à ajouter. |

### addHtml(char[] html) {#addHtml-char---}
```
public abstract void addHtml(char[] html)
```

Ajoute du texte HTML formaté.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| html | char[] | Texte à ajouter. |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public abstract void addHtml(char[] html, int startIndex, int length)
```

Ajoute du texte HTML formaté.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| html | char[] | Texte à ajouter. |
| startIndex | int | Index de début de la portion à ajouter. |
| length | int | Longueur de la portion à ajouter. |

### addText(String text) {#addText-java.lang.String-}
```
public abstract void addText(String text)
```

Ajoute du texte brut aux fichiers html, en remplaçant les caractères spéciaux par des entités html. Les sauts de ligne et les espaces blancs ne sont pas remplacés.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte à ajouter. |

### addText(char[] text) {#addText-char---}
```
public abstract void addText(char[] text)
```

Ajoute du texte brut aux fichiers html, en remplaçant les caractères spéciaux par des entités html. Les sauts de ligne et les espaces blancs ne sont pas remplacés.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | char[] | Texte à ajouter. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public abstract void addText(char[] text, int startIndex, int length)
```

Ajoute du texte brut aux fichiers html, en remplaçant les caractères spéciaux par des entités html. Les sauts de ligne et les espaces blancs ne sont pas remplacés.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | char[] | Texte à ajouter. |
| startIndex | int | Index de début de la portion à ajouter. |
| length | int | Longueur de la portion à ajouter. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public abstract void addAttributeValue(String value)
```

Cite la valeur d'attribut et l'ajoute au fichier html.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Chaîne de valeur d'attribut. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public abstract void addAttributeValue(char[] value)
```

Cite la valeur d'attribut et l'ajoute au fichier html.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | char[] | Chaîne de valeur d'attribut. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public abstract void addAttributeValue(char[] value, int startIndex, int length)
```

Cite la valeur d'attribut et l'ajoute au fichier html.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | char[] | Chaîne de valeur d'attribut. |
| startIndex | int | Index de début de la portion à ajouter. |
| length | int | Longueur de la portion à ajouter. |

### getSlideImageSize() {#getSlideImageSize--}
```
public abstract Dimension2D getSlideImageSize()
```

Renvoie la taille de l'image de la diapositive. Lecture seule java.awt.geom.Dimension2D.

**Renvoie :**
java.awt.geom.Dimension2D

### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public abstract int getSlideImageSizeUnit()
```

Renvoie l'unité dans laquelle la taille de l'image de la diapositive est spécifiée. Lecture seule [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**Renvoie :**
int

### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public abstract String getSlideImageSizeUnitCode()
```

Renvoie le code CSS de l'unité dans laquelle la taille de l'image de la diapositive est spécifiée. Lecture seule String.

**Renvoie :**
java.lang.String

### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public abstract int getPreviousSlideIndex()
```

Renvoie l'index de la diapositive précédemment rendue ou -1 si la première diapositive est rendue. Lecture seule int.

**Renvoie :**
int

### getSlideIndex() {#getSlideIndex--}
```
public abstract int getSlideIndex()
```

Renvoie l'index de la diapositive en cours de rendu. Lecture seule int.

**Renvoie :**
int

### getNextSlideIndex() {#getNextSlideIndex--}
```
public abstract int getNextSlideIndex()
```

Renvoie l'index d'une diapositive qui sera rendue après la diapositive actuelle ou -1 si la dernière diapositive est en cours de rendu. Lecture seule int.

**Renvoie :**
int