---
title: IShapeStyle
second_title: Aspose.Slides for Java API Reference
description: Represent shapes style reference.
type: docs
url: /nl/com.aspose.slides/ishapestyle/
---```
public interface IShapeStyle
```

Verwijst naar de stijl van een vorm.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getLineColor()](#getLineColor--) | Retourneert de omtrekkleur van een vorm. |
| [getLineStyleIndex()](#getLineStyleIndex--) | Geeft de kolomindex van de lijn in een stijlmatrix terug of stelt deze in. |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | Geeft de kolomindex van de lijn in een stijlmatrix terug of stelt deze in. |
| [getFillColor()](#getFillColor--) | Retourneert de vulkleur van een vorm. |
| [getFillStyleIndex()](#getFillStyleIndex--) | Geeft de vulkolomindex van een vorm in stijlmatrices terug of stelt deze in. |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | Geeft de vulkolomindex van een vorm in stijlmatrices terug of stelt deze in. |
| [getEffectColor()](#getEffectColor--) | Retourneert de effectkleur van een vorm. |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | Geeft de effectkolomindex van een vorm in een stijlmatrix terug of stelt deze in. |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | Geeft de effectkolomindex van een vorm in een stijlmatrix terug of stelt deze in. |
| [getFontColor()](#getFontColor--) | Retourneert de letterkleur van een vorm. |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | Geeft de lettertype-index van een vorm in een lettertypecollectie terug of stelt deze in. |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | Geeft de lettertype-index van een vorm in een lettertypecollectie terug of stelt deze in. |
### getLineColor() {#getLineColor--}
```
public abstract IColorFormat getLineColor()
```

Retourneert de omtrekkleur van een vorm. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getLineStyleIndex() {#getLineStyleIndex--}
```
public abstract int getLineStyleIndex()
```

Geeft de kolomindex van de lijn in een stijlmatrix terug of stelt deze in. Lezen/schrijven int.

**Returns:**
int
### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public abstract void setLineStyleIndex(int value)
```

Geeft de kolomindex van de lijn in een stijlmatrix terug of stelt deze in. Lezen/schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getFillColor() {#getFillColor--}
```
public abstract IColorFormat getFillColor()
```

Retourneert de vulkleur van een vorm. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFillStyleIndex() {#getFillStyleIndex--}
```
public abstract short getFillStyleIndex()
```

Geeft de vulkolomindex van een vorm in stijlmatrices terug of stelt deze in. 0 betekent geen vulling, een positieve waarde – index in de vulstijlen van het thema, een negatieve waarde – index in de achtergrondstijlen van het thema. Lezen/schrijven short.

**Returns:**
short
### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public abstract void setFillStyleIndex(short value)
```

Geeft de vulkolomindex van een vorm in stijlmatrices terug of stelt deze in. 0 betekent geen vulling, een positieve waarde – index in de vulstijlen van het thema, een negatieve waarde – index in de achtergrondstijlen van het thema. Lezen/schrijven short.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | short |  |
### getEffectColor() {#getEffectColor--}
```
public abstract IColorFormat getEffectColor()
```

Retourneert de effectkleur van een vorm. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public abstract long getEffectStyleIndex()
```

Geeft de effectkolomindex van een vorm in een stijlmatrix terug of stelt deze in. Lezen/schrijven long.

**Returns:**
long
### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public abstract void setEffectStyleIndex(long value)
```

Geeft de effectkolomindex van een vorm in een stijlmatrix terug of stelt deze in. Lezen/schrijven long.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | long |  |
### getFontColor() {#getFontColor--}
```
public abstract IColorFormat getFontColor()
```

Retourneert de letterkleur van een vorm. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public abstract byte getFontCollectionIndex()
```

Geeft de lettertype-index van een vorm in een lettertypecollectie terug of stelt deze in. Lezen/schrijven [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Returns:**
byte
### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public abstract void setFontCollectionIndex(byte value)
```

Geeft de lettertype-index van een vorm in een lettertypecollectie terug of stelt deze in. Lezen/schrijven [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |