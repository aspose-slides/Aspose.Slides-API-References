---
title: ShapeElement
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta una parte di forma con le stesse proprietà di contorno e riempimento.
type: docs
url: /it/com.aspose.slides/shapeelement/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IShapeElement](../../com.aspose.slides/ishapeelement)
```
public class ShapeElement implements IShapeElement
```

Rappresenta una parte di una forma con le stesse proprietà di contorno e riempimento.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getParentShape()](#getParentShape--) | Restituisce un Shape_PPT per il quale l'elemento è stato creato. |
| [getPathPoints()](#getPathPoints--) | Ottiene un array di punti che definiscono la geometria del percorso dell'elemento. |
| [getPathTypes()](#getPathTypes--) | Ottiene un array di valori byte che specificano il tipo di ciascun punto nel percorso dell'elemento. |
| [getFillSource()](#getFillSource--) | Restituisce informazioni su come riempire un elemento. |
| [getStrokeSource()](#getStrokeSource--) | Restituisce informazioni su come tracciare un elemento. |
### getParentShape() {#getParentShape--}
```
public final Shape getParentShape()
```

Restituisce un Shape_PPT per il quale l'elemento è stato creato. Solo lettura [Shape](../../com.aspose.slides/shape).

**Restituisce:**
[Shape](../../com.aspose.slides/shape)
### getPathPoints() {#getPathPoints--}
```
public final PointF[] getPathPoints()
```

Ottiene un array di punti che definiscono la geometria del percorso dell'elemento.

**Restituisce:**
android.graphics.PointF[]
### getPathTypes() {#getPathTypes--}
```
public final byte[] getPathTypes()
```

Ottiene un array di valori byte che specificano il tipo di ciascun punto nel percorso dell'elemento.

**0** Indica che il punto è l'inizio di una figura.

**1** Indica che il punto è uno dei due estremi di una linea.

**3** Indica che il punto è un punto finale o di controllo di una spline cubica di Bezier.

**7** Maschera tutti i bit eccetto i tre bit di ordine inferiore, che indicano il tipo di punto.

**16** Specifica che il segmento corrispondente è tratteggiato.

**32** Specifica che il punto è un marcatore.

**128** Specifica che il punto è l'ultimo punto in un sotto-percorso chiuso (figura).

**129** Indica un punto dati che è sia l'estremità di un segmento di linea sia l'ultimo punto di un sotto-percorso chiuso.

**Restituisce:**
byte[]
### getFillSource() {#getFillSource--}
```
public final byte getFillSource()
```

Restituisce informazioni su come riempire un elemento. Solo lettura [ShapeElementFillSource](../../com.aspose.slides/shapeelementfillsource).

**Restituisce:**
byte
### getStrokeSource() {#getStrokeSource--}
```
public final byte getStrokeSource()
```

Restituisce informazioni su come tracciare un elemento. Solo lettura [ShapeElementStrokeSource](../../com.aspose.slides/shapeelementstrokesource).

**Restituisce:**
byte