---
title: ICellFormat
second_title: Aspose.Slides for Java API Reference
description: Rappresenta il formato di una cella di tabella.
type: docs
url: /it/com.aspose.slides/icellformat/
---```
public interface ICellFormat
```

Rappresenta il formato di una cella di tabella.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Restituisce un oggetto delle proprietà di riempimento della cella. |
| [getBorderLeft()](#getBorderLeft--) | Restituisce un oggetto delle proprietà della linea del bordo sinistro. |
| [getBorderTop()](#getBorderTop--) | Restituisce un oggetto delle proprietà della linea del bordo superiore. |
| [getBorderRight()](#getBorderRight--) | Restituisce un oggetto delle proprietà della linea del bordo destro. |
| [getBorderBottom()](#getBorderBottom--) | Restituisce un oggetto delle proprietà della linea del bordo inferiore. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Restituisce un oggetto delle proprietà della linea diagonale dall’angolo in alto a sinistra a quello in basso a destra. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Restituisce un oggetto delle proprietà della linea diagonale dall’angolo in basso a sinistra a quello in alto a destra. |
| [getTransparency()](#getTransparency--) | Ottiene o imposta la trasparenza del colore di riempimento. |
| [setTransparency(float value)](#setTransparency-float-) | Ottiene o imposta la trasparenza del colore di riempimento. |
| [getEffective()](#getEffective--) | Ottiene le proprietà di formattazione effettive della cella della tabella con ereditarietà e stili di tabella applicati. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Restituisce un oggetto delle proprietà di riempimento della cella. Solo lettura [IFillFormat](../../com.aspose.slides/ifillformat).

**Restituisce:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public abstract ILineFormat getBorderLeft()
```

Restituisce un oggetto delle proprietà della linea del bordo sinistro. Solo lettura [ILineFormat](../../com.aspose.slides/ilineformat).

**Restituisce:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public abstract ILineFormat getBorderTop()
```

Restituisce un oggetto delle proprietà della linea del bordo superiore. Solo lettura [ILineFormat](../../com.aspose.slides/ilineformat).

**Restituisce:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public abstract ILineFormat getBorderRight()
```

Restituisce un oggetto delle proprietà della linea del bordo destro. Solo lettura [ILineFormat](../../com.aspose.slides/ilineformat).

**Restituisce:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public abstract ILineFormat getBorderBottom()
```

Restituisce un oggetto delle proprietà della linea del bordo inferiore. Solo lettura [ILineFormat](../../com.aspose.slides/ilineformat).

**Restituisce:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public abstract ILineFormat getBorderDiagonalDown()
```

Restituisce un oggetto delle proprietà della linea diagonale dall’angolo in alto a sinistra a quello in basso a destra. Solo lettura [ILineFormat](../../com.aspose.slides/ilineformat).

**Restituisce:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public abstract ILineFormat getBorderDiagonalUp()
```

Restituisce un oggetto delle proprietà della linea diagonale dall’angolo in basso a sinistra a quello in alto a destra. Solo lettura [ILineFormat](../../com.aspose.slides/ilineformat).

**Restituisce:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```

Ottiene o imposta la trasparenza del colore di riempimento. Lettura/scrittura  float .

**Restituisce:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```

Ottiene o imposta la trasparenza del colore di riempimento. Lettura/scrittura  float .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public abstract ICellFormatEffectiveData getEffective()
```

Ottiene le proprietà di formattazione effettive della cella della tabella con ereditarietà e stili di tabella applicati.

**Restituisce:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - Un [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).