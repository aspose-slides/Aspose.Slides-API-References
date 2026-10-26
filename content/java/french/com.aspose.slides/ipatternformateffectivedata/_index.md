---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides pour Java Référence de l'API
description: Objet immutable qui contient les propriétés effectives de remplissage de motif.
type: docs
url: /fr/com.aspose.slides/ipatternformateffectivedata/
---```
public interface IPatternFormatEffectiveData
```

Objet immutable qui contient les propriétés effectives de remplissage de motif.

--------------------

Cette interface est utilisée comme partie de [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) et [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Renvoie le style du motif. |
| [getForeColor()](#getForeColor--) | Renvoie la couleur de premier plan du motif. |
| [getBackColor()](#getBackColor--) | Renvoie la couleur de fond du motif. |
| [getTileIImage(Color background, Color foreground)](#getTileIImage-java.awt.Color-java.awt.Color-) | Crée une image en mosaïque pour le remplissage du motif avec des couleurs spécifiées. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```


Renvoie le style du motif. Lecture seule [PatternStyle](../../com.aspose.slides/patternstyle).

**Retour :**
byte
### getForeColor() {#getForeColor--}
```
public abstract Color getForeColor()
```


Renvoie la couleur de premier plan du motif. Lecture seule java.awt.Color.

**Retour :**
java.awt.Color
### getBackColor() {#getBackColor--}
```
public abstract Color getBackColor()
```


Renvoie la couleur de fond du motif. Lecture seule java.awt.Color.

**Retour :**
java.awt.Color
### getTileIImage(Color background, Color foreground) {#getTileIImage-java.awt.Color-java.awt.Color-}
```
public abstract IImage getTileIImage(Color background, Color foreground)
```


Crée une image en mosaïque pour le remplissage du motif avec des couleurs spécifiées.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| background | java.awt.Color | La java.awt.Color de fond pour le motif. |
| foreground | java.awt.Color | La java.awt.Color de premier plan pour le motif. |

**Retour :**
[IImage](../../com.aspose.slides/iimage) - Mosaïque [IImage](../../com.aspose.slides/iimage).