---
title: PatternFormat
second_title: Référence de l'API Java Aspose.Slides pour Android
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
| [getPatternStyle()](#getPatternStyle--) | Renvoie ou définit le style du motif. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Renvoie ou définit le style du motif. |
| [getForeColor()](#getForeColor--) | Renvoie la couleur de premier plan du motif. |
| [getBackColor()](#getBackColor--) | Renvoie la couleur d'arrière-plan du motif. |
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | Crée une image mosaïque pour le remplissage du motif avec des couleurs spécifiées. |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | Crée une image mosaïque pour le remplissage du motif. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Lecture-seule long.

**Renvoie :**
long
### getPatternStyle() {#getPatternStyle--}
```
public final byte getPatternStyle()
```

Renvoie ou définit le style du motif. Lecture/écriture [PatternStyle](../../com.aspose.slides/patternstyle).

**Renvoie :**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public final void setPatternStyle(byte value)
```

Renvoie ou définit le style du motif. Lecture/écriture [PatternStyle](../../com.aspose.slides/patternstyle).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getForeColor() {#getForeColor--}
```
public final IColorFormat getForeColor()
```

Renvoie la couleur de premier plan du motif. Lecture-seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Renvoie :**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public final IColorFormat getBackColor()
```

Renvoie la couleur d'arrière-plan du motif. Lecture-seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Renvoie :**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public final IImage getTile(Integer background, Integer foreground)
```

Crée une image mosaïque pour le remplissage du motif avec des couleurs spécifiées.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| background | java.lang.Integer | L’entier java.lang.Integer d’arrière-plan pour le motif. |
| foreground | java.lang.Integer | L’entier java.lang.Integer de premier plan pour le motif. |

**Renvoie :**
[IImage](../../com.aspose.slides/iimage) - Mosaïque [IImage](../../com.aspose.slides/iimage).
### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public final IImage getTile(Integer styleColor)
```

Crée une image mosaïque pour le remplissage du motif.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| styleColor | java.lang.Integer | L’entier java.lang.Integer par défaut |

**Renvoie :**
[IImage](../../com.aspose.slides/iimage) - Mosaïque [IImage](../../com.aspose.slides/iimage).