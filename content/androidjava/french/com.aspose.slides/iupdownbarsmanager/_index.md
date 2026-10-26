---
title: IUpDownBarsManager
second_title: Aspose.Slides for Android via Java API Reference
description: Fournit l'accès aux barres haut/bas des graphiques en ligne ou boursiers.
type: docs
url: /fr/com.aspose.slides/iupdownbarsmanager/
---```
public interface IUpDownBarsManager
```

Fournit l'accès aux barres haut/bas des graphiques en ligne ou boursiers.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getUpBarsFormat()](#getUpBarsFormat--) | Renvoie le format des barres supérieures. |
| [getDownBarsFormat()](#getDownBarsFormat--) | Renvoie le format des barres inférieures. |
| [hasUpDownBars()](#hasUpDownBars--) | Détermine si le graphique possède des barres haut/bas. |
| [setUpDownBars(boolean value)](#setUpDownBars-boolean-) | Détermine si le graphique possède des barres haut/bas. |
| [getGapWidth()](#getGapWidth--) | Renvoie ou définit la largeur de l'écart. |
| [setGapWidth(int value)](#setGapWidth-int-) | Renvoie ou définit la largeur de l'écart. |
### getUpBarsFormat() {#getUpBarsFormat--}
```
public abstract IFormat getUpBarsFormat()
```

Renvoie le format des barres supérieures. Lecture seule [IFormat](../../com.aspose.slides/iformat).

**Renvoie :**
[IFormat](../../com.aspose.slides/iformat)
### getDownBarsFormat() {#getDownBarsFormat--}
```
public abstract IFormat getDownBarsFormat()
```

Renvoie le format des barres inférieures. Lecture seule [IFormat](../../com.aspose.slides/iformat).

**Renvoie :**
[IFormat](../../com.aspose.slides/iformat)
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

Détermine si le graphique possède des barres haut/bas. Lecture/écriture booléen.

**Renvoie :**
boolean
### setUpDownBars(boolean value) {#setUpDownBars-boolean-}
```
public abstract void setUpDownBars(boolean value)
```

Détermine si le graphique possède des barres haut/bas. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Renvoie ou définit la largeur de l'écart. Lecture/écriture int.

**Renvoie :**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

Renvoie ou définit la largeur de l'écart. Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |