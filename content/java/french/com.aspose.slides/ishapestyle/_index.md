---
title: IShapeStyle
second_title: Aspose.Slides for Java API Reference
description: Represent shapes style reference.
type: docs
url: /fr/com.aspose.slides/ishapestyle/
---```
public interface IShapeStyle
```

Représente la référence du style d'une forme.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getLineColor()](#getLineColor--) | Renvoie la couleur du contour d'une forme. |
| [getLineStyleIndex()](#getLineStyleIndex--) | Renvoie ou définit l'indice de colonne de la ligne dans une matrice de style. |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | Renvoie ou définit l'indice de colonne de la ligne dans une matrice de style. |
| [getFillColor()](#getFillColor--) | Renvoie la couleur de remplissage d'une forme. |
| [getFillStyleIndex()](#getFillStyleIndex--) | Renvoie ou définit l'indice de colonne de remplissage de la forme dans les matrices de style. |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | Renvoie ou définit l'indice de colonne de remplissage de la forme dans les matrices de style. |
| [getEffectColor()](#getEffectColor--) | Renvoie la couleur d'effet d'une forme. |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | Renvoie ou définit l'indice de colonne d'effet de la forme dans une matrice de style. |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | Renvoie ou définit l'indice de colonne d'effet de la forme dans une matrice de style. |
| [getFontColor()](#getFontColor--) | Renvoie la couleur de police d'une forme. |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | Renvoie ou définit l'indice de police de la forme dans une collection de polices. |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | Renvoie ou définit l'indice de police de la forme dans une collection de polices. |
### getLineColor() {#getLineColor--}
```
public abstract IColorFormat getLineColor()
```


Renvoie la couleur du contour d'une forme. Lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Renvoie :**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getLineStyleIndex() {#getLineStyleIndex--}
```
public abstract int getLineStyleIndex()
```


Renvoie ou définit l'indice de colonne de la ligne dans une matrice de style. Lecture/écriture int.

**Renvoie :**
int
### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public abstract void setLineStyleIndex(int value)
```


Renvoie ou définit l'indice de colonne de la ligne dans une matrice de style. Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFillColor() {#getFillColor--}
```
public abstract IColorFormat getFillColor()
```


Renvoie la couleur de remplissage d'une forme. Lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Renvoie :**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFillStyleIndex() {#getFillStyleIndex--}
```
public abstract short getFillStyleIndex()
```


Renvoie ou définit l'indice de colonne de remplissage de la forme dans les matrices de style. 0 signifie aucun remplissage, une valeur positive - indice dans les styles de remplissage du thème, une valeur négative - indice dans les styles d'arrière-plan du thème. Lecture/écriture short.

**Renvoie :**
short
### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public abstract void setFillStyleIndex(short value)
```


Renvoie ou définit l'indice de colonne de remplissage de la forme dans les matrices de style. 0 signifie aucun remplissage, une valeur positive - indice dans les styles de remplissage du thème, une valeur négative - indice dans les styles d'arrière-plan du thème. Lecture/écriture short.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | short |  |

### getEffectColor() {#getEffectColor--}
```
public abstract IColorFormat getEffectColor()
```


Renvoie la couleur d'effet d'une forme. Lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Renvoie :**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public abstract long getEffectStyleIndex()
```


Renvoie ou définit l'indice de colonne d'effet de la forme dans une matrice de style. Lecture/écriture long.

**Renvoie :**
long
### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public abstract void setEffectStyleIndex(long value)
```


Renvoie ou définit l'indice de colonne d'effet de la forme dans une matrice de style. Lecture/écriture long.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | long |  |

### getFontColor() {#getFontColor--}
```
public abstract IColorFormat getFontColor()
```


Renvoie la couleur de police d'une forme. Lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Renvoie :**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public abstract byte getFontCollectionIndex()
```


Renvoie ou définit l'indice de police de la forme dans une collection de polices. Lecture/écriture [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Renvoie :**
byte
### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public abstract void setFontCollectionIndex(byte value)
```


Renvoie ou définit l'indice de police de la forme dans une collection de polices. Lecture/écriture [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |