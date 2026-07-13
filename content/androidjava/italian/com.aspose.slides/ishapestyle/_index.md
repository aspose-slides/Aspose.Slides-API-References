---
title: IShapeStyle
second_title: Aspose.Slides per Android tramite Java API Reference
description: Rappresenta il riferimento allo stile delle forme.
type: docs
url: /it/com.aspose.slides/ishapestyle/
---```
public interface IShapeStyle
```

Rappresenta il riferimento allo stile della forma.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getLineColor()](#getLineColor--) | Restituisce il colore del contorno di una forma. |
| [getLineStyleIndex()](#getLineStyleIndex--) | Restituisce o imposta l'indice di colonna della linea in una matrice di stile. |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | Restituisce o imposta l'indice di colonna della linea in una matrice di stile. |
| [getFillColor()](#getFillColor--) | Restituisce il colore di riempimento di una forma. |
| [getFillStyleIndex()](#getFillStyleIndex--) | Restituisce o imposta l'indice di colonna di riempimento della forma nelle matrici di stile. |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | Restituisce o imposta l'indice di colonna di riempimento della forma nelle matrici di stile. |
| [getEffectColor()](#getEffectColor--) | Restituisce il colore dell'effetto della forma. |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | Restituisce o imposta l'indice di colonna dell'effetto della forma in una matrice di stile. |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | Restituisce o imposta l'indice di colonna dell'effetto della forma in una matrice di stile. |
| [getFontColor()](#getFontColor--) | Restituisce il colore del carattere della forma. |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | Restituisce o imposta l'indice del carattere della forma in una raccolta di caratteri. |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | Restituisce o imposta l'indice del carattere della forma in una raccolta di caratteri. |
### getLineColor() {#getLineColor--}
```
public abstract IColorFormat getLineColor()
```

Restituisce il colore del contorno di una forma. Solo lettura [IColorFormat](../../com.aspose.slides/icolorformat).

**Restituisce:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getLineStyleIndex() {#getLineStyleIndex--}
```
public abstract int getLineStyleIndex()
```

Restituisce o imposta l'indice di colonna della linea in una matrice di stile. Lettura/scrittura int.

**Restituisce:**  
int
### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public abstract void setLineStyleIndex(int value)
```

Restituisce o imposta l'indice di colonna della linea in una matrice di stile. Lettura/scrittura int.

**Parametri:**  
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getFillColor() {#getFillColor--}
```
public abstract IColorFormat getFillColor()
```

Restituisce il colore di riempimento di una forma. Solo lettura [IColorFormat](../../com.aspose.slides/icolorformat).

**Restituisce:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFillStyleIndex() {#getFillStyleIndex--}
```
public abstract short getFillStyleIndex()
```

Restituisce o imposta l'indice di colonna di riempimento della forma nelle matrici di stile. 0 significa nessun riempimento, valore positivo - indice negli stili di riempimento del tema, valore negativo - indice negli stili di sfondo del tema. Lettura/scrittura short.

**Restituisce:**  
short
### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public abstract void setFillStyleIndex(short value)
```

Restituisce o imposta l'indice di colonna di riempimento della forma nelle matrici di stile. 0 significa nessun riempimento, valore positivo - indice negli stili di riempimento del tema, valore negativo - indice negli stili di sfondo del tema. Lettura/scrittura short.

**Parametri:**  
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | short |  |
### getEffectColor() {#getEffectColor--}
```
public abstract IColorFormat getEffectColor()
```

Restituisce il colore dell'effetto della forma. Solo lettura [IColorFormat](../../com.aspose.slides/icolorformat).

**Restituisce:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public abstract long getEffectStyleIndex()
```

Restituisce o imposta l'indice di colonna dell'effetto della forma in una matrice di stile. Lettura/scrittura long.

**Restituisce:**  
long
### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public abstract void setEffectStyleIndex(long value)
```

Restituisce o imposta l'indice di colonna dell'effetto della forma in una matrice di stile. Lettura/scrittura long.

**Parametri:**  
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | long |  |
### getFontColor() {#getFontColor--}
```
public abstract IColorFormat getFontColor()
```

Restituisce il colore del carattere della forma. Solo lettura [IColorFormat](../../com.aspose.slides/icolorformat).

**Restituisce:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public abstract byte getFontCollectionIndex()
```

Restituisce o imposta l'indice del carattere della forma in una raccolta di caratteri. Lettura/scrittura [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Restituisce:**  
byte
### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public abstract void setFontCollectionIndex(byte value)
```

Restituisce o imposta l'indice del carattere della forma in una raccolta di caratteri. Lettura/scrittura [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Parametri:**  
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |