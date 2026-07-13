---
title: SmartArtShape
second_title: Riferimento API Java per Aspose.Slides per Android
description: Rappresenta la forma SmartArt
type: docs
url: /it/com.aspose.slides/smartartshape/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Tutte le interfacce implementate:**
[com.aspose.slides.ISmartArtShape](../../com.aspose.slides/ismartartshape)
```
public class SmartArtShape extends GeometryShape implements ISmartArtShape
```

Rappresenta la forma SmartArt
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getShapeType()](#getShapeType--) | Restituisce o imposta il tipo predefinito di geometria. |
| [setShapeType(int value)](#setShapeType-int-) | Restituisce o imposta il tipo predefinito di geometria. |
| [getTextFrame()](#getTextFrame--) | Restituisce il testo della forma SmartArt. |
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```


Restituisce o imposta il tipo predefinito di geometria. Nota: al cambio del valore tutti i valori di regolazione verranno ripristinati ai valori predefiniti. Lettura/scrittura [ShapeType](../../com.aspose.slides/shapetype).

**Restituisce:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```


Restituisce o imposta il tipo predefinito di geometria. Nota: al cambio del valore tutti i valori di regolazione verranno ripristinati ai valori predefiniti. Lettura/scrittura [ShapeType](../../com.aspose.slides/shapetype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```


Restituisce il testo della forma SmartArt. Sola lettura [ITextFrame](../../com.aspose.slides/itextframe).

**Restituisce:**
[ITextFrame](../../com.aspose.slides/itextframe)