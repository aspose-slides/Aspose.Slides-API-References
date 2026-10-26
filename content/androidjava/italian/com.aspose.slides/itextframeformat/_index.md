---
title: ITextFrameFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Contiene le proprietà di formattazione dei TextFrames.
type: docs
url: /it/com.aspose.slides/itextframeformat/
---```
public interface ITextFrameFormat
```

Contiene le proprietà di formattazione del TextFrame.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | Restituisce lo stile del testo. |
| [getMarginLeft()](#getMarginLeft--) | Restituisce o imposta il margine sinistro (punti) in un TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Restituisce o imposta il margine sinistro (punti) in un TextFrame. |
| [getMarginRight()](#getMarginRight--) | Restituisce o imposta il margine destro (punti) in un TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Restituisce o imposta il margine destro (punti) in un TextFrame. |
| [getMarginTop()](#getMarginTop--) | Restituisce o imposta il margine superiore (punti) in un TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Restituisce o imposta il margine superiore (punti) in un TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Restituisce o imposta il margine inferiore (punti) in un TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Restituisce o imposta il margine inferiore (punti) in un TextFrame. |
| [getWrapText()](#getWrapText--) | True se il testo è avvolto ai margini del TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | True se il testo è avvolto ai margini del TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | Restituisce o imposta l'ancoraggio verticale del testo in un TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Restituisce o imposta l'ancoraggio verticale del testo in un TextFrame. |
| [getCenterText()](#getCenterText--) | Se NullableBool.True, il testo dovrebbe essere centrato orizzontalmente nella casella. |
| [setCenterText(byte value)](#setCenterText-byte-) | Se NullableBool.True, il testo dovrebbe essere centrato orizzontalmente nella casella. |
| [getTextVerticalType()](#getTextVerticalType--) | Determina l'orientamento del testo. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Determina l'orientamento del testo. |
| [getAutofitType()](#getAutofitType--) | Restituisce o imposta la modalità autofit del testo. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Restituisce o imposta la modalità autofit del testo. |
| [getColumnCount()](#getColumnCount--) | Restituisce o imposta il numero di colonne nell'area di testo. |
| [setColumnCount(int value)](#setColumnCount-int-) | Restituisce o imposta il numero di colonne nell'area di testo. |
| [getColumnSpacing()](#getColumnSpacing--) | Restituisce o imposta lo spazio tra le colonne di testo nell'area di testo (in punti). |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | Restituisce o imposta lo spazio tra le colonne di testo nell'area di testo (in punti). |
| [getThreeDFormat()](#getThreeDFormat--) | Restituisce l'oggetto ThreeDFormat che rappresenta le proprietà dell'effetto 3d per un testo. |
| [getKeepTextFlat()](#getKeepTextFlat--) | Restituisce o imposta il mantenimento del testo completamente fuori dalla scena 3D. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | Restituisce o imposta il mantenimento del testo completamente fuori dalla scena 3D. |
| [getRotationAngle()](#getRotationAngle--) | Specifica la rotazione personalizzata applicata al testo all'interno della casella di delimitazione. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Specifica la rotazione personalizzata applicata al testo all'interno della casella di delimitazione. |
| [getTransform()](#getTransform--) | Ottiene o imposta la forma di avvolgimento del testo. |
| [setTransform(byte value)](#setTransform-byte-) | Ottiene o imposta la forma di avvolgimento del testo. |
| [getEffective()](#getEffective--) | Ottiene i dati di formattazione effettivi del text frame con l'ereditarietà applicata. |

### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyle getTextStyle()
```

Restituisce lo stile del testo. Solo lettura [ITextStyle](../../com.aspose.slides/itextstyle).

**Restituisce:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Restituisce o imposta il margine sinistro (punti) in un TextFrame. Lettura/scrittura double.

**Restituisce:**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Restituisce o imposta il margine sinistro (punti) in un TextFrame. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Restituisce o imposta il margine destro (punti) in un TextFrame. Lettura/scrittura double.

**Restituisce:**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Restituisce o imposta il margine destro (punti) in un TextFrame. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Restituisce o imposta il margine superiore (punti) in un TextFrame. Lettura/scrittura double.

**Restituisce:**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Restituisce o imposta il margine superiore (punti) in un TextFrame. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Restituisce o imposta il margine inferiore (punti) in un TextFrame. Lettura/scrittura double.

**Restituisce:**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Restituisce o imposta il margine inferiore (punti) in un TextFrame. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

True se il testo è avvolto ai margini del TextFrame. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**
byte

### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

True se il testo è avvolto ai margini del TextFrame. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Restituisce o imposta l'ancoraggio verticale del testo in un TextFrame. Lettura/scrittura [TextAnchorType](../../com.aspose.slides/textanchortype).

**Restituisce:**
byte

### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

Restituisce o imposta l'ancoraggio verticale del testo in un TextFrame. Lettura/scrittura [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

Se NullableBool.True, il testo dovrebbe essere centrato orizzontalmente nella casella. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**
byte

### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

Se NullableBool.True, il testo dovrebbe essere centrato orizzontalmente nella casella. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Determina l'orientamento del testo. Il valore risultante della rotazione visuale del testo è riassunto da questa proprietà e dall'angolo personalizzato nella proprietà RotationAngle. Lettura/scrittura [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Restituisce:**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Determina l'orientamento del testo. Il valore risultante della rotazione visuale del testo è riassunto da questa proprietà e dall'angolo personalizzato nella proprietà RotationAngle. Lettura/scrittura [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

Restituisce o imposta la modalità autofit del testo. Lettura/scrittura [TextAutofitType](../../com.aspose.slides/textautofittype).

**Restituisce:**
byte

### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

Restituisce o imposta la modalità autofit del testo. Lettura/scrittura [TextAutofitType](../../com.aspose.slides/textautofittype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

Restituisce o imposta il numero di colonne nell'area di testo. Questo valore deve essere positivo; altrimenti verrà impostato a zero. Il valore 0 indica valore non definito. Lettura/scrittura int.

**Restituisce:**
int

### setColumnCount(int value) {#setColumnCount-int-}
```
public abstract void setColumnCount(int value)
```

Restituisce o imposta il numero di colonne nell'area di testo. Questo valore deve essere positivo; altrimenti verrà impostato a zero. Il valore 0 indica valore non definito. Lettura/scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getColumnSpacing() {#getColumnSpacing--}
```
public abstract double getColumnSpacing()
```

Restituisce o imposta lo spazio tra le colonne di testo nell'area di testo (in punti). Questo si applica solo quando è presente più di una colonna. Il valore deve essere positivo; altrimenti verrà impostato a zero. Lettura/scrittura double.

**Restituisce:**
double

### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public abstract void setColumnSpacing(double value)
```

Restituisce o imposta lo spazio tra le colonne di testo nell'area di testo (in punti). Questo si applica solo quando è presente più di una colonna. Il valore deve essere positivo; altrimenti verrà impostato a zero. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |

### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

Restituisce l'oggetto ThreeDFormat che rappresenta le proprietà dell'effetto 3d per un testo. Solo lettura [IThreeDFormat](../../com.aspose.slides/ithreedformat).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // Imposta la trasformazione del testo
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // Imposta l'estrusione
>      textFrame.getTextFrameFormat().getThreeDFormat().getExtrusionColor().setColor(Color.ORANGE);
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(6);
>      // Imposta il contorno
>      textFrame.getTextFrameFormat().getThreeDFormat().getContourColor().setColor(Color.DARK_GRAY);
>      textFrame.getTextFrameFormat().getThreeDFormat().setContourWidth(1.5);
>      // Imposta la profondità
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      // Imposta il materiale
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      // Imposta l'illuminazione
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      // Imposta il tipo di fotocamera
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Restituisce:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getKeepTextFlat() {#getKeepTextFlat--}
```
public abstract boolean getKeepTextFlat()
```

Restituisce o imposta il mantenimento del testo completamente fuori dalla scena 3D. Lettura/scrittura boolean.

**Restituisce:**
boolean

### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public abstract void setKeepTextFlat(boolean value)
```

Restituisce o imposta il mantenimento del testo completamente fuori dalla scena 3D. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

Specific

a la rotazione personalizzata applicata al testo all'interno della casella di delimitazione. Se non specificata, viene usata la rotazione della forma associata. Se specificata, viene applicata indipendentemente dalla forma. Ciò significa che la forma può avere una rotazione aggiuntiva rispetto alla rotazione del testo. Il valore risultante della rotazione visuale del testo è riassunto da questa proprietà e dal tipo verticale predefinito nella proprietà TextVerticalType. Lettura/scrittura float.

--------------------

> ```
> Considera il caso in cui una forma ha una rotazione di 90 gradi in senso orario applicata. 
>  Inoltre, il corpo del testo stesso ha una rotazione di -90 gradi in senso antiorario applicata. 
>  Allora la forma risultante apparirebbe ruotata ma il testo al suo interno sembrerebbe non essere stato ruotato affatto.
> ```


**Restituisce:**
float

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

Specific

a la rotazione personalizzata applicata al testo all'interno della casella di delimitazione. Se non specificata, viene usata la rotazione della forma associata. Se specificata, viene applicata indipendentemente dalla forma. Ciò significa che la forma può avere una rotazione aggiuntiva rispetto alla rotazione del testo. Il valore risultante della rotazione visuale del testo è riassunto da questa proprietà e dal tipo verticale predefinito nella proprietà TextVerticalType. Lettura/scrittura float.

--------------------

> ```
> Considera il caso in cui una forma ha una rotazione di 90 gradi in senso orario applicata. 
>  Inoltre, il corpo del testo stesso ha una rotazione di -90 gradi in senso antiorario applicata. 
>  Allora la forma risultante apparirebbe ruotata ma il testo al suo interno sembrerebbe non essere stato ruotato affatto.
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getTransform() {#getTransform--}
```
public abstract byte getTransform()
```

Ottiene o imposta la forma di avvolgimento del testo. Lettura/scrittura [TextShapeType](../../com.aspose.slides/textshapetype).

**Restituisce:**
byte

### setTransform(byte value) {#setTransform-byte-}
```
public abstract void setTransform(byte value)
```

Ottiene o imposta la forma di avvolgimento del testo. Lettura/scrittura [TextShapeType](../../com.aspose.slides/textshapetype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getEffective() {#getEffective--}
```
public abstract ITextFrameFormatEffectiveData getEffective()
```

Ottiene i dati di formattazione effettivi del text frame con l'ereditarietà applicata.

**Restituisce:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).