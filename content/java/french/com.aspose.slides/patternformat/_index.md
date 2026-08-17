---
title: PatternFormat
second_title: Référence API Aspose.Slides pour Java
description: Représente un motif pour remplir une forme.
type: docs
url: /fr/com.aspose.slides/patternformat/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IPatternFormat](../../com.aspose.slides/ipatternformat)
```
public final class PatternFormat extends PVIObject implements IPatternFormat
```

Représente un motif pour remplir une forme.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPatternStyle()](#getPatternStyle--) | Renvoie ou définit le style de motif. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Renvoie ou définit le style de motif. |
| [getForeColor()](#getForeColor--) | Renvoie la couleur de motif en avant-plan. |
| [getBackColor()](#getBackColor--) | Renvoie la couleur de motif en arrière-plan. |
| [getTile(Color background, Color foreground)](#getTile-java.awt.Color-java.awt.Color-) | Crée une image en mosaïque pour le remplissage de motif avec des couleurs spécifiées. |
| [getTile(Color styleColor)](#getTile-java.awt.Color-) | Crée une image en mosaïque pour le remplissage de motif. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Lecture seule long.

**Renvoie :**
long
### getPatternStyle() {#getPatternStyle--}
```
public final byte getPatternStyle()
```

Renvoie ou définit le style de motif. Lecture/écriture [PatternStyle](../../com.aspose.slides/patternstyle).

**Renvoie :**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public final void setPatternStyle(byte value)
```

Renvoie ou définit le style de motif. Lecture/écriture [PatternStyle](../../com.aspose.slides/patternstyle).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getForeColor() {#getForeColor--}
```
public final IColorFormat getForeColor()
```

Renvoie la couleur de motif en avant-plan. Lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Renvoie :**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public final IColorFormat getBackColor()
```

Renvoie la couleur de motif en arrière-plan. Lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Renvoie :**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Color background, Color foreground) {#getTile-java.awt.Color-java.awt.Color-}
```
public final IImage getTile(Color background, Color foreground)
```

Crée une image en mosaïque pour le remplissage de motif avec des couleurs spécifiées.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| background | java.awt.Color | La couleur java.awt.Color d’arrière-plan pour le motif. |
| foreground | java.awt.Color | La couleur java.awt.Color d’avant-plan pour le motif. |

**Renvoie :**
[IImage](../../com.aspose.slides/iimage) - Mosaïque [IImage](../../com.aspose.slides/iimage).
### getTile(Color styleColor) {#getTile-java.awt.Color-}
```
public final IImage getTile(Color styleColor)
```

Crée une image en mosaïque pour le remplissage de motif.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| styleColor | java.awt.Color | La couleur java.awt.Color par défaut |

**Renvoie :**
[IImage](../../com.aspose.slides/iimage) - Mosaïque [IImage](../../com.aspose.slides/iimage).