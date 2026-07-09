---
title: IPatternFormat
second_title: Aspose.Slides for Android via Java API Reference
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
| [getForeColor()](#getForeColor--) | Renvoie la couleur du premier plan du motif. |
| [getBackColor()](#getBackColor--) | Renvoie la couleur d'arrière-plan du motif. |
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | Crée une image en mosaïque pour le remplissage du motif avec des couleurs spécifiées. |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | Crée une image en mosaïque pour le remplissage du motif. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

Renvoie ou définit le style du motif. Lecture/écriture [PatternStyle](../../com.aspose.slides/patternstyle).

**Renvoie :**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public abstract void setPatternStyle(byte value)
```

Renvoie ou définit le style du motif. Lecture/écriture [PatternStyle](../../com.aspose.slides/patternstyle).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getForeColor() {#getForeColor--}
```
public abstract IColorFormat getForeColor()
```

Renvoie la couleur du premier plan du motif. Lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Renvoie :**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public abstract IColorFormat getBackColor()
```

Renvoie la couleur d'arrière-plan du motif. Lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Renvoie :**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTile(Integer background, Integer foreground)
```

Crée une image en mosaïque pour le remplissage du motif avec des couleurs spécifiées.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| background | java.lang.Integer | Le java.lang.Integer d'arrière-plan pour le motif. |
| foreground | java.lang.Integer | Le java.lang.Integer de premier plan pour le motif. |

**Renvoie :**
[IImage](../../com.aspose.slides/iimage) - Tuile android.graphics.Bitmap.
### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public abstract IImage getTile(Integer styleColor)
```

Crée une image en mosaïque pour le remplissage du motif.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| styleColor | java.lang.Integer | Le java.lang.Integer par défaut, défini dans l'objet StyleEx de ShapeEx. Les couleurs du remplissage peuvent dépendre de cela. |

**Renvoie :**
[IImage](../../com.aspose.slides/iimage) - Tuile android.graphics.Bitmap.