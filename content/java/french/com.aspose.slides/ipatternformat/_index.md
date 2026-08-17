---
title: IPatternFormat
second_title: Aspose.Slides for Java API Reference
description: Represents a pattern to fill a shape.
type: docs
url: /fr/com.aspose.slides/ipatternformat/
---```
public interface IPatternFormat
```

Représente un motif pour remplir une forme.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Renvoie ou définit le style du motif. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Renvoie ou définit le style du motif. |
| [getForeColor()](#getForeColor--) | Renvoie la couleur du motif d'avant-plan. |
| [getBackColor()](#getBackColor--) | Renvoie la couleur du motif d'arrière-plan. |
| [getTile(Color background, Color foreground)](#getTile-java.awt.Color-java.awt.Color-) | Crée une image de tuile pour le remplissage du motif avec des couleurs spécifiées. |
| [getTile(Color styleColor)](#getTile-java.awt.Color-) | Crée une image de tuile pour le remplissage du motif. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```


Renvoie ou définit le style du motif. Lecture/écriture [PatternStyle](../../com.aspose.slides/patternstyle).

**Renvoie:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public abstract void setPatternStyle(byte value)
```


Renvoie ou définit le style du motif. Lecture/écriture [PatternStyle](../../com.aspose.slides/patternstyle).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public abstract IColorFormat getForeColor()
```


Renvoie la couleur du motif d'avant-plan. Lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Renvoie:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public abstract IColorFormat getBackColor()
```


Renvoie la couleur du motif d'arrière-plan. Lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Renvoie:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Color background, Color foreground) {#getTile-java.awt.Color-java.awt.Color-}
```
public abstract IImage getTile(Color background, Color foreground)
```


Crée une image de tuile pour le remplissage du motif avec des couleurs spécifiées.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| background | java.awt.Color | Le java.awt.Color de fond pour le motif. |
| foreground | java.awt.Color | Le java.awt.Color d'avant-plan pour le motif. |

**Renvoie:**
[IImage](../../com.aspose.slides/iimage) - Tuile java.awt.image.BufferedImage.
### getTile(Color styleColor) {#getTile-java.awt.Color-}
```
public abstract IImage getTile(Color styleColor)
```


Crée une image de tuile pour le remplissage du motif.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| styleColor | java.awt.Color | Le java.awt.Color par défaut, défini dans l'objet StyleEx de ShapeEx. Les couleurs du remplissage peuvent dépendre de cela. |

**Renvoie:**
[IImage](../../com.aspose.slides/iimage) - Tuile java.awt.image.BufferedImage.