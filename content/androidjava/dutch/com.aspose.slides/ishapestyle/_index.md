---
title: IShapeStyle
second_title: Aspose.Slides voor Android via Java API-referentie
description: Verwijzing naar de stijl van vormen.
type: docs
url: /nl/com.aspose.slides/ishapestyle/
---```
public interface IShapeStyle
```

Verwijzing naar de stijl van een vorm.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getLineColor()](#getLineColor--) | Retourneert de contourkleur van een vorm. |
| [getLineStyleIndex()](#getLineStyleIndex--) | Retourneert of stelt de kolomindex van de lijn in een stijlmatrix in. |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | Retourneert of stelt de kolomindex van de lijn in een stijlmatrix in. |
| [getFillColor()](#getFillColor--) | Retourneert de opvulkleur van een vorm. |
| [getFillStyleIndex()](#getFillStyleIndex--) | Retourneert of stelt de kolomindex van de vormvulling in stijlmatrices in. |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | Retourneert of stelt de kolomindex van de vormvulling in stijlmatrices in. |
| [getEffectColor()](#getEffectColor--) | Retourneert de effectkleur van een vorm. |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | Retourneert of stelt de kolomindex van het effect in een stijlmatrix in. |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | Retourneert of stelt de kolomindex van het effect in een stijlmatrix in. |
| [getFontColor()](#getFontColor--) | Retourneert de lettertypekleur van een vorm. |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | Retourneert of stelt de lettertype-index van een vorm in een lettertypecollectie in. |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | Retourneert of stelt de lettertype-index van een vorm in een lettertypecollectie in. |
### getLineColor() {#getLineColor--}
```
public abstract IColorFormat getLineColor()
```

Retourneert de contourkleur van een vorm. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getLineStyleIndex() {#getLineStyleIndex--}
```
public abstract int getLineStyleIndex()
```

Retourneert of stelt de kolomindex van de lijn in een stijlmatrix in. Lezen/schrijven int.

**Retour:**
int
### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public abstract void setLineStyleIndex(int value)
```

Retourneert of stelt de kolomindex van de lijn in een stijlmatrix in. Lezen/schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getFillColor() {#getFillColor--}
```
public abstract IColorFormat getFillColor()
```

Retourneert de opvulkleur van een vorm. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFillStyleIndex() {#getFillStyleIndex--}
```
public abstract short getFillStyleIndex()
```

Retourneert of stelt de kolomindex van de vormvulling in stijlmatrices in. 0 betekent geen vulling, positief getal - index in de vulstijlen van het thema, negatief getal - index in de achtergrondstijlen van het thema. Lezen/schrijven short.

**Retour:**
short
### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public abstract void setFillStyleIndex(short value)
```

Retourneert of stelt de kolomindex van de vormvulling in stijlmatrices in. 0 betekent geen vulling, positief getal - index in de vulstijlen van het thema, negatief getal - index in de achtergrondstijlen van het thema. Lezen/schrijven short.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | short |  |
### getEffectColor() {#getEffectColor--}
```
public abstract IColorFormat getEffectColor()
```

Retourneert de effectkleur van een vorm. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public abstract long getEffectStyleIndex()
```

Retourneert of stelt de kolomindex van het effect in een stijlmatrix in. Lezen/schrijven long.

**Retour:**
long
### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public abstract void setEffectStyleIndex(long value)
```

Retourneert of stelt de kolomindex van het effect in een stijlmatrix in. Lezen/schrijven long.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | long |  |
### getFontColor() {#getFontColor--}
```
public abstract IColorFormat getFontColor()
```

Retourneert de lettertypekleur van een vorm. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public abstract byte getFontCollectionIndex()
```

Retourneert of stelt de lettertype-index van een vorm in een lettertypecollectie in. Lezen/schrijven [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Retour:**
byte
### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public abstract void setFontCollectionIndex(byte value)
```

Retourneert of stelt de lettertype-index van een vorm in een lettertypecollectie in. Lezen/schrijven [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |