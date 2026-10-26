---
title: TextFrameFormat
second_title: Riferimento API Java di Aspose.Slides per Android
description: Contiene le proprietà formatTextFrameFormatting dei TextFrames.
type: docs
url: /it/com.aspose.slides/textframeformat/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tutte le interfacce implementate:**
[com.aspose.slides.ITextFrameFormat](../../com.aspose.slides/itextframeformat), [com.aspose.slides.IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
```
public final class TextFrameFormat extends PVIObject implements ITextFrameFormat, IChartTextBlockFormat
```

Contiene le proprietà formatTextFrameFormatting del TextFrame.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TextFrameFormat()](#TextFrameFormat--) | Inizializza una nuova istanza della classe [TextFrameFormat](../../com.aspose.slides/textframeformat). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getTextStyle()](#getTextStyle--) | Restituisce lo stile del testo. |
| [getThreeDFormat()](#getThreeDFormat--) | Restituisce l'oggetto ThreeDFormat che rappresenta le proprietà dell'effetto 3D per un testo. |
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
| [getAnchoringType()](#getAnchoringType--) | Restituisce o imposta l'ancoraggio verticale del testo in un TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Restituisce o imposta l'ancoraggio verticale del testo in un TextFrame. |
| [getCenterText()](#getCenterText--) | Se NullableBool.True, il testo dovrebbe essere centrato orizzontalmente nella casella. |
| [setCenterText(byte value)](#setCenterText-byte-) | Se NullableBool.True, il testo dovrebbe essere centrato orizzontalmente nella casella. |
| [getTextVerticalType()](#getTextVerticalType--) | Determina l'orientamento del testo. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Determina l'orientamento del testo. |
| [getAutofitType()](#getAutofitType--) | Restituisce o imposta la modalità di adattamento automatico del testo. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Restituisce o imposta la modalità di adattamento automatico del testo. |
| [getColumnCount()](#getColumnCount--) | Restituisce o imposta il numero di colonne nell'area del testo. |
| [setColumnCount(int value)](#setColumnCount-int-) | Restituisce o imposta il numero di colonne nell'area del testo. |
| [getColumnSpacing()](#getColumnSpacing--) | Restituisce o imposta lo spazio tra le colonne di testo nell'area del testo (in punti). |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | Restituisce o imposta lo spazio tra le colonne di testo nell'area del testo (in punti). |
| [getRotationAngle()](#getRotationAngle--) | Specifica la rotazione personalizzata applicata al testo all'interno della casella di delimitazione. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Specifica la rotazione personalizzata applicata al testo all'interno della casella di delimitazione. |
| [getTransform()](#getTransform--) | Ottiene o imposta la forma di avvolgimento del testo. |
| [setTransform(byte value)](#setTransform-byte-) | Ottiene o imposta la forma di avvolgimento del testo. |
| [getKeepTextFlat()](#getKeepTextFlat--) | Ottiene o imposta il mantenimento del testo piatto anche se è stato applicato un effetto di rotazione 3D. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | Ottiene o imposta il mantenimento del testo piatto anche se è stato applicato un effetto di rotazione 3D. |
| [getEffective()](#getEffective--) | Ottiene i dati effettivi di formattazione del frame di testo con l'ereditarietà applicata. |
### TextFrameFormat() {#TextFrameFormat--}
```
public TextFrameFormat()
```


Inizializza una nuova istanza della classe [TextFrameFormat](../../com.aspose.slides/textframeformat).

### getVersion() {#getVersion--}
```
public long getVersion()
```


Versione. Solo lettura long.

**Restituisce:**
long
### getTextStyle() {#getTextStyle--}
```
public final ITextStyle getTextStyle()
```


Restituisce lo stile del testo. Solo lettura [ITextStyle](../../com.aspose.slides/itextstyle).

**Restituisce:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getThreeDFormat() {#getThreeDFormat--}
```
public final IThreeDFormat getThreeDFormat()
```


Restituisce l'oggetto ThreeDFormat che rappresenta le proprietà dell'effetto 3D per un testo. Solo lettura [IThreeDFormat](../../com.aspose.slides/ithreedformat).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // Imposta trasformazione del testo
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // Imposta estrusione
>      textFrame.getTextFrameFormat().getThreeDFormat().getExtrusionColor().setColor(Color.ORANGE);
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(6);
>      // Imposta contorno
>      textFrame.getTextFrameFormat().getThreeDFormat().getContourColor().setColor(Color.DARK_GRAY);
>      textFrame.getTextFrameFormat().getThreeDFormat().setContourWidth(1.5);
>      // Imposta profondità
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      // Imposta materiale
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      // Imposta illuminazione
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      // Imposta tipo di telecamera
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Restituisce:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)
### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```


Restituisce o imposta il margine sinistro (punti) in un TextFrame. Lettura/scrittura double.

**Restituisce:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```


Restituisce o imposta il margine sinistro (punti) in un TextFrame. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```


Restituisce o imposta il margine destro (punti) in un TextFrame. Lettura/scrittura double.

**Restituisce:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```


Restituisce o imposta il margine destro (punti) in un TextFrame. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```


Restituisce o imposta il margine superiore (punti) in un TextFrame. Lettura/scrittura double.

**Restituisce:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```


Restituisce o imposta il margine superiore (punti) in un TextFrame. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```


Restituisce o imposta il margine inferiore (punti) in un TextFrame. Lettura/scrittura double.

**Restituisce:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```


Restituisce o imposta il margine inferiore (punti) in un TextFrame. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |
### getWrapText() {#getWrapText--}
```
public final byte getWrapText()
```


Vero se il testo è a capo ai margini del TextFrame. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

--------------------

> ```
> The following sample code shows how to wrap text in Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setWrapText(NullableBool.True);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Restituisce:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public final void setWrapText(byte value)
```


Vero se il testo è a capo ai margini del TextFrame. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

--------------------

> ```
> The following sample code shows how to wrap text in Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setWrapText(NullableBool.True);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |
### getAnchoringType() {#getAnchoringType--}
```
public final byte getAnchoringType()
```


Restituisce o imposta l'ancoraggio verticale del testo in un TextFrame. Lettura/scrittura [TextAnchorType](../../com.aspose.slides/textanchortype).

**Restituisce:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public final void setAnchoringType(byte value)
```


Restituisce o imposta l'ancoraggio verticale del testo in un TextFrame. Lettura/scrittura [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |
### getCenterText() {#getCenterText--}
```
public final byte getCenterText()
```


Se NullableBool.True, il testo dovrebbe essere centrato orizzontalmente nella casella. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public final void setCenterText(byte value)
```


Se NullableBool.True, il testo dovrebbe essere centrato orizzontalmente nella casella. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```


Determina l'orientamento del testo. Il valore risultante della rotazione visiva del testo è sintetizzato da questa proprietà e dall'angolo personalizzato nella proprietà RotationAngle. Lettura/scrittura [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Restituisce:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```


Determina l'orientamento del testo. Il valore risultante della rotazione visiva del testo è sintetizzato da questa proprietà e dall'angolo personalizzato nella proprietà RotationAngle. Lettura/scrittura [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |
### getAutofitType() {#getAutofitType--}
```
public final byte getAutofitType()
```


Restituisce o imposta la modalità di adattamento automatico del testo. Lettura/scrittura [TextAutofitType](../../com.aspose.slides/textautofittype).

--------------------

> ```
> The following sample code shows how to resize shape to Fit Text in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Shape);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code shows how to shrink text on overflow.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Normal);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Restituisce:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public final void setAutofitType(byte value)
```


Restituisce o imposta la modalità di adattamento automatico del testo. Lettura/scrittura [TextAutofitType](../../com.aspose.slides/textautofittype).

--------------------

> ```
> The following sample code shows how to resize shape to Fit Text in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Shape);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code shows how to shrink text on overflow.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Normal);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |
### getColumnCount() {#getColumnCount--}
```
public final int getColumnCount()
```


Restituisce o imposta il numero di colonne nell'area del testo. Questo valore deve essere un numero positivo. Altrimenti, il valore sarà impostato a zero. Il valore 0 indica un valore indefinito. Lettura/scrittura int.

--------------------

> ```
> The following sample code shows how to add column in Text frame inside a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape1 = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      TextFrameFormat format = (TextFrameFormat)shape1.getTextFrame().getTextFrameFormat();
>      format.setColumnCount(2);
>      format.setColumnSpacing(20);
>      shape1.getTextFrame().setText("All these columns are forced to stay within a single text container -- " +
>      "you can add or delete text - and the new or remaining text automatically adjusts " +
>      "itself to stay within the container. You cannot have text spill over from one container " +
>      "to other, though -- because PowerPoint's column options for text are limited!");
>      pres.save("Columns_output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Restituisce:**
int
### setColumnCount(int value) {#setColumnCount-int-}
```
public final void setColumnCount(int value)
```


Restituisce o imposta il numero di colonne nell'area del testo. Questo valore deve essere un numero positivo. Altrimenti, il valore sarà impostato a zero. Il valore 0 indica un valore indefinito. Lettura/scrittura int.

--------------------

> ```
> Il seguente codice di esempio mostra come aggiungere colonne in un frame di testo all'interno di una presentazione PowerPoint.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape1 = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      TextFrameFormat format = (TextFrameFormat)shape1.getTextFrame().getTextFrameFormat();
>      format.setColumnCount(2);
>      format.setColumnSpacing(20);
>      shape1.getTextFrame().setText("All these columns are forced to stay within a single text container -- " +
>      "you can add or delete text - and the new or remaining text automatically adjusts " +
>      "itself to stay within the container. You cannot have text spill over from one container " +
>      "to other, though -- because PowerPoint's column options for text are limited!");
>      pres.save("Columns_output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getColumnSpacing() {#getColumnSpacing--}
```
public final double getColumnSpacing()
```


Restituisce o imposta lo spazio tra le colonne di testo nell'area del testo (in punti). Questo dovrebbe applicarsi solo quando è presente più di 1 colonna. Questo valore deve essere un numero positivo. Altrimenti, il valore sarà impostato a zero. Lettura/scrittura double.

**Restituisce:**
double
### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public final void setColumnSpacing(double value)
```


Restituisce o imposta lo spazio tra le colonne di testo nell'area del testo (in punti). Questo dovrebbe applicarsi solo quando è presente più di 1 colonna. Questo valore deve essere un numero positivo. Altrimenti, il valore sarà impostato a zero. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |
### getRotationAngle() {#getRotationAngle--}
```
public final float getRotationAngle()
```


Specifica la rotazione personalizzata applicata al testo all'interno della casella di delimitazione. Se non specificata, viene utilizzata la rotazione della forma associata. Se specificata, viene applicata indipendentemente dalla forma. Cioè la forma può avere una rotazione applicata oltre a quella del testo stesso. Il valore risultante della rotazione visiva del testo è sintetizzato da questa proprietà e dal tipo verticale predefinito nella proprietà TextVerticalType. Lettura/scrittura float.

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
public final void setRotationAngle(float value)
```


Specifica la rotazione personalizzata applicata al testo all'interno della casella di delimitazione. Se non specificata, viene utilizzata la rotazione della forma associata. Se specificata, viene applicata indipendentemente dalla forma. Cioè la forma può avere una rotazione applicata oltre a quella del testo stesso. Il valore risultante della rotazione visiva del testo è sintetizzato da questa proprietà e dal tipo verticale predefinito nella proprietà TextVerticalType. Lettura/scrittura float.

--------------------

> ```
> Considera il caso in cui una forma ha una rotazione di 90 gradi in senso orario applicata. 
>  In aggiunta a ciò, il corpo del testo stesso ha una rotazione di -90 gradi 
>  in senso antiorario applicata. Allora la forma risultante sembrerebbe
>  essere ruotata, ma il testo al suo interno sembrerebbe non essere stato ruotato affatto.
```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |
### getTransform() {#getTransform--}
```
public final byte getTransform()
```


Ottiene o imposta la forma di avvolgimento del testo. Lettura/scrittura [TextShapeType](../../com.aspose.slides/textshapetype).

**Restituisce:**
byte
### setTransform(byte value) {#setTransform-byte-}
```
public  



```


Ottiene o imposta la forma di avvolgimento del testo. Lettura/scrittura [TextShapeType](../../com.aspose.slides/textshapetype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |
### getKeepTextFlat() {#getKeepTextFlat--}
```
public final boolean getKeepTextFlat()
```


Ottiene o imposta il mantenimento del testo piatto anche se è stato applicato un effetto di rotazione 3D. Lettura/scrittura boolean.

**Restituisce:**
boolean
### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public final void setKeepTextFlat(boolean value)
```


Ottiene o imposta il mantenimento del testo piatto anche se è stato applicato un effetto di rotazione 3D. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getEffective() {#getEffective--}
```
public final ITextFrameFormatEffectiveData getEffective()
```


Ottiene i dati effettivi di formattazione del frame di testo con l'ereditarietà applicata.

--------------------

> ```
> This example demonstrates getting some of effective text frame formatting properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      ITextFrameFormatEffectiveData effectiveTextFrameFormat = shape.getTextFrame().getTextFrameFormat().getEffective();
>     
>      System.out.println("Anchoring type: " + effectiveTextFrameFormat.getAnchoringType());
>      System.out.println("Autofit type: " + effectiveTextFrameFormat.getAutofitType());
>      System.out.println("Text vertical type: " + effectiveTextFrameFormat.getTextVerticalType());
>      System.out.println("Margins");
>      System.out.println("   Left: " + effectiveTextFrameFormat.getMarginLeft());
>      System.out.println("   Top: " + effectiveTextFrameFormat.getMarginTop());
>      System.out.println("   Right: " + effectiveTextFrameFormat.getMarginRight());
>      System.out.println("   Bottom: " + effectiveTextFrameFormat.getMarginBottom());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Restituisce:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).