---
title: IShapeStyle
second_title: Aspose.Slides for Android via Java API Reference
description: Représente la référence du style d'une forme.
type: docs
url: /fr/com.aspose.slides/ishapestyle/
---```
public interface IShapeStyle
```

Représente la référence du style d’une forme.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getLineColor()](#getLineColor--) | Retourne la couleur du contour d’une forme. |
| [getLineStyleIndex()](#getLineStyleIndex--) | Retourne ou définit l’index de colonne de la ligne dans une matrice de style. |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | Retourne ou définit l’index de colonne de la ligne dans une matrice de style. |
| [getFillColor()](#getFillColor--) | Retourne la couleur de remplissage d’une forme. |
| [getFillStyleIndex()](#getFillStyleIndex--) | Retourne ou définit l’index de colonne de remplissage de la forme dans les matrices de style. |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | Retourne ou définit l’index de colonne de remplissage de la forme dans les matrices de style. |
| [getEffectColor()](#getEffectColor--) | Retourne la couleur d’effet d’une forme. |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | Retourne ou définit l’index de colonne d’effet de la forme dans une matrice de style. |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | Retourne ou définit l’index de colonne d’effet de la forme dans une matrice de style. |
| [getFontColor()](#getFontColor--) | Retourne la couleur de police d’une forme. |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | Retourne ou définit l’index de police de la forme dans une collection de polices. |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | Retourne ou définit l’index de police de la forme dans une collection de polices. |
### getLineColor() {#getLineColor--}
```
public abstract IColorFormat getLineColor()
```


Retourne la couleur du contour d’une forme. Lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Retourne :**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getLineStyleIndex() {#getLineStyleIndex--}
```
public abstract int getLineStyleIndex()
```


Retourne ou définit l’index de colonne de la ligne dans une matrice de style. Lecture/écriture int.

**Retourne :**
int
### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public abstract void setLineStyleIndex(int value)
```


Retourne ou définit l’index de colonne de la ligne dans une matrice de style. Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFillColor() {#getFillColor--}
```
public abstract IColorFormat getFillColor()
```


Retourne la couleur de remplissage d’une forme. Lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Retourne :**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFillStyleIndex() {#getFillStyleIndex--}
```
public abstract short getFillStyleIndex()
```


Retourne ou définit l’index de colonne de remplissage de la forme dans les matrices de style. 0 signifie aucun remplissage, valeur positive – index dans les styles de remplissage du thème, valeur négative – index dans les styles d’arrière-plan du thème. Lecture/écriture short.

**Retourne :**
short
### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public abstract void setFillStyleIndex(short value)
```


Retourne ou définit l’index de colonne de remplissage de la forme dans les matrices de style. 0 signifie aucun remplissage, valeur positive – index dans les styles de remplissage du thème, valeur négative – index dans les styles d’arrière-plan du thème. Lecture/écriture short.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | short |  |

### getEffectColor() {#getEffectColor--}
```
public abstract IColorFormat getEffectColor()
```


Retourne la couleur d’effet d’une forme. Lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Retourne :**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public abstract long getEffectStyleIndex()
```


Retourne ou définit l’index de colonne d’effet de la forme dans une matrice de style. Lecture/écriture long.

**Retourne :**
long
### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public abstract void setEffectStyleIndex(long value)
```


Retourne ou définit l’index de colonne d’effet de la forme dans une matrice de style. Lecture/écriture long.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | long |  |

### getFontColor() {#getFontColor--}
```
public abstract IColorFormat getFontColor()
```


Retourne la couleur de police d’une forme. Lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Retourne :**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public abstract byte getFontCollectionIndex()
```


Retourne ou définit l’index de police de la forme dans une collection de polices. Lecture/écriture [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Retourne :**
byte
### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public abstract void setFontCollectionIndex(byte value)
```


Retourne ou définit l’index de police de la forme dans une collection de polices. Lecture/écriture [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |