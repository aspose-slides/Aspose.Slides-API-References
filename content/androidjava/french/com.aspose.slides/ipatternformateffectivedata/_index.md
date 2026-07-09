---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective pattern filling properties.
type: docs
url: /fr/com.aspose.slides/ipatternformateffectivedata/
---```
public interface IPatternFormatEffectiveData
```

Objet immuable qui contient les propriétés de remplissage de motif effectives.

--------------------

Cette interface est utilisée comme partie de [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) et [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Renvoie le style du motif. |
| [getForeColor()](#getForeColor--) | Renvoie la couleur de premier plan du motif. |
| [getBackColor()](#getBackColor--) | Renvoie la couleur d'arrière-plan du motif. |
| [getTileIImage(Integer background, Integer foreground)](#getTileIImage-java.lang.Integer-java.lang.Integer-) | Crée une image en mosaïque pour le remplissage du motif avec des couleurs spécifiées. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```


Renvoie le style du motif. Lecture seule [PatternStyle](../../com.aspose.slides/patternstyle).

**Renvoie :**
byte
### getForeColor() {#getForeColor--}
```
public abstract Integer getForeColor()
```


Renvoie la couleur de premier plan du motif. Lecture seule java.lang.Integer.

**Renvoie :**
java.lang.Integer
### getBackColor() {#getBackColor--}
```
public abstract Integer getBackColor()
```


Renvoie la couleur d'arrière-plan du motif. Lecture seule java.lang.Integer.

**Renvoie :**
java.lang.Integer
### getTileIImage(Integer background, Integer foreground) {#getTileIImage-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTileIImage(Integer background, Integer foreground)
```


Crée une image en mosaïque pour le remplissage du motif avec des couleurs spécifiées.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| background | java.lang.Integer | Le java.lang.Integer d'arrière-plan pour le motif. |
| foreground | java.lang.Integer | Le java.lang.Integer de premier plan pour le motif. |

**Renvoie :**
[IImage](../../com.aspose.slides/iimage) - Tile [IImage](../../com.aspose.slides/iimage).