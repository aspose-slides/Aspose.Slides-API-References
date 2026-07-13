---
title: IChartTextBlockFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Represents formatting properties for chart text elements.
type: docs
url: /it/com.aspose.slides/icharttextblockformat/
---```
public interface IChartTextBlockFormat
```

Rappresenta le proprietà di formattazione per gli elementi di testo del grafico.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getAnchoringType()](#getAnchoringType--) | Restituisce o imposta il testo di ancoraggio verticale in un TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Restituisce o imposta il testo di ancoraggio verticale in un TextFrame. |
| [getCenterText()](#getCenterText--) | Se NullableBool.True allora il testo dovrebbe essere centrato orizzontalmente nella casella. |
| [setCenterText(byte value)](#setCenterText-byte-) | Se NullableBool.True allora il testo dovrebbe essere centrato orizzontalmente nella casella. |
| [getTextVerticalType()](#getTextVerticalType--) | Determina l'orientamento del testo. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Determina l'orientamento del testo. |
| [getMarginLeft()](#getMarginLeft--) | Restituisce o imposta il margine sinistro (punti) in un TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Restituisce o imposta il margine sinistro (punti) in un TextFrame. |
| [getMarginRight()](#getMarginRight--) | Restituisce o imposta il margine destro (punti) in un TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Restituisce o imposta il margine destro (punti) in un TextFrame. |
| [getMarginTop()](#getMarginTop--) | Restituisce o imposta il margine superiore (punti) in un TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Restituisce o imposta il margine superiore (punti) in un TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Restituisce o imposta il margine inferiore (punti) in un TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Restituisce o imposta il margine inferiore (punti) in un TextFrame. |
| [getWrapText()](#getWrapText--) | Vero se il testo è a capo ai margini del TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | Vero se il testo è a capo ai margini del TextFrame. |
| [getAutofitType()](#getAutofitType--) | Restituisce o imposta la modalità di adattamento automatico del testo. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Restituisce o imposta la modalità di adattamento automatico del testo. |
| [getRotationAngle()](#getRotationAngle--) | Specifica la rotazione personalizzata applicata al testo all'interno del riquadro di delimitazione. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Specifica la rotazione personalizzata applicata al testo all'interno del riquadro di delimitazione. |

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Restituisce o imposta il testo di ancoraggio verticale in un TextFrame. Lettura/scrittura [TextAnchorType](../../com.aspose.slides/textanchortype).

**Restituisce:**
byte

### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

Restituisce o imposta il testo di ancoraggio verticale in un TextFrame. Lettura/scrittura [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

Se NullableBool.True allora il testo dovrebbe essere centrato orizzontalmente nella casella. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**
byte

### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

Se NullableBool.True allora il testo dovrebbe essere centrato orizzontalmente nella casella. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Determina l'orientamento del testo. Il valore risultante della rotazione visiva del testo, riassunto da questa proprietà e dall'angolo personalizzato nella proprietà RotationAngle. Lettura/scrittura [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Restituisce:**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Determina l'orientamento del testo. Il valore risultante della rotazione visiva del testo, riassunto da questa proprietà e dall'angolo personalizzato nella proprietà RotationAngle. Lettura/scrittura [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Restituisce o imposta il margine sinistro (punti) in un TextFrame. La modifica di questa proprietà può influenzare solo le seguenti parti del grafico: DataLabel e DataLabelFormat (supporto completo in PowerPoint 2013; in PowerPoint 2007 non ha effetto sul rendering). Lettura/scrittura double.

**Restituisce:**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Restituisce o imposta il margine sinistro (punti) in un TextFrame. La modifica di questa proprietà può influenzare solo le seguenti parti del grafico: DataLabel e DataLabelFormat (supporto completo in PowerPoint 2013; in PowerPoint 2007 non ha effetto sul rendering). Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Restituisce o imposta il margine destro (punti) in un TextFrame. La modifica di questa proprietà può influenzare solo le seguenti parti del grafico: DataLabel e DataLabelFormat (supporto completo in PowerPoint 2013; in PowerPoint 2007 non ha effetto sul rendering). Lettura/scrittura double.

**Restituisce:**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Restituisce o imposta il margine destro (punti) in un TextFrame. La modifica di questa proprietà può influenzare solo le seguenti parti del grafico: DataLabel e DataLabelFormat (supporto completo in PowerPoint 2013; in PowerPoint 2007 non ha effetto sul rendering). Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Restituisce o imposta il margine superiore (punti) in un TextFrame. La modifica di questa proprietà può influenzare solo le seguenti parti del grafico: DataLabel e DataLabelFormat (supporto completo in PowerPoint 2013; in PowerPoint 2007 non ha effetto sul rendering). Lettura/scrittura double.

**Restituisce:**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Restituisce o imposta il margine superiore (punti) in un TextFrame. La modifica di questa proprietà può influenzare solo le seguenti parti del grafico: DataLabel e DataLabelFormat (supporto completo in PowerPoint 2013; in PowerPoint 2007 non ha effetto sul rendering). Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Restituisce o imposta il margine inferiore (punti) in un TextFrame. La modifica di questa proprietà può influenzare solo le seguenti parti del grafico: DataLabel e DataLabelFormat (supporto completo in PowerPoint 2013; in PowerPoint 2007 non ha effetto sul rendering). Lettura/scrittura double.

**Restituisce:**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Restituisce o imposta il margine inferiore (punti) in un TextFrame. La modifica di questa proprietà può influenzare solo le seguenti parti del grafico: DataLabel e DataLabelFormat (supporto completo in PowerPoint 2013; in PowerPoint 2007 non ha effetto sul rendering). Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

Vero se il testo è a capo ai margini del TextFrame. La modifica di questa proprietà può influenzare solo le seguenti parti del grafico: DataLabel e DataLabelFormat (supporto completo in PowerPoint 2007/2013). Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**
byte

### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

Vero se il testo è a capo ai margini del TextFrame. La modifica di questa proprietà può influenzare solo le seguenti parti del grafico: DataLabel e DataLabelFormat (supporto completo in PowerPoint 2007/2013). Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

Restituisce o imposta la modalità di adattamento automatico del testo. La modifica di questa proprietà può influenzare solo le seguenti parti del grafico: DataLabel e DataLabelFormat (supporto completo in PowerPoint 2013; in PowerPoint 2007 non ha effetto sul rendering). Lettura/scrittura [TextAutofitType](../../com.aspose.slides/textautofittype).

**Restituisce:**
byte

### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

Restituisce o imposta la modalità di adattamento automatico del testo. La modifica di questa proprietà può influenzare solo le seguenti parti del grafico: DataLabel e DataLabelFormat (supporto completo in PowerPoint 2013; in PowerPoint 2007 non ha effetto sul rendering). Lettura/scrittura [TextAutofitType](../../com.aspose.slides/textautofittype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

Specifică la rotazione personalizzata applicata al testo all'interno del riquadro di delimitazione. Se non specificata, viene utilizzata la rotazione della forma associata. Se è specificata, viene applicata in modo indipendente dalla forma. Ciò significa che la forma può avere una rotazione applicata oltre a quella del testo stesso. Il valore risultante della rotazione visiva del testo, riassunto da questa proprietà e dal tipo verticale predefinito nella proprietà TextVerticalType. Lettura/scrittura float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**Restituisce:**
float

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

Specifică la rotazione personalizzata applicata al testo all'interno del riquadro di delimitazione. Se non specificata, viene utilizzata la rotazione della forma associata. Se è specificata, viene applicata in modo indipendente dalla forma. Ciò significa che la forma può avere una rotazione applicata oltre a quella del testo stesso. Il valore risultante della rotazione visiva del testo, riassunto da questa proprietà e dal tipo verticale predefinito nella proprietà TextVerticalType. Lettura/scrittura float.

--------------------

> ```
> Considera il caso in cui una forma abbia una rotazione di 90 gradi in senso orario applicata a essa. 
>  In aggiunta a ciò, il corpo del testo stesso ha una rotazione di -90 gradi 
>  in senso antiorario applicata. Allora la forma risultante apparirebbe a
>  essere ruotata, ma il testo al suo interno apparirebbe come se non fosse stato ruotato affatto.
```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |