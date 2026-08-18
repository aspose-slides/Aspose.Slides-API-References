---
title: TextFrameFormat
second_title: Aspose.Slides für Java API-Referenz
description: Enthält die formatTextFrameFormatting-Eigenschaften von TextFrames.
type: docs
url: /de/com.aspose.slides/textframeformat/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ITextFrameFormat](../../com.aspose.slides/itextframeformat), [com.aspose.slides.IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
```
public final class TextFrameFormat extends PVIObject implements ITextFrameFormat, IChartTextBlockFormat
```

Enthält die formatTextFrameFormatting-Eigenschaften des TextFrames.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TextFrameFormat()](#TextFrameFormat--) | Initialisiert eine neue Instanz der Klasse [TextFrameFormat](../../com.aspose.slides/textframeformat). |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getTextStyle()](#getTextStyle--) | Gibt den Stil des Textes zurück. |
| [getThreeDFormat()](#getThreeDFormat--) | Gibt das ThreeDFormat-Objekt zurück, das die 3D-Effekt-Eigenschaften für einen Text darstellt. |
| [getMarginLeft()](#getMarginLeft--) | Ermittelt oder legt den linken Rand (Punkte) in einem TextFrame fest. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Ermittelt oder legt den linken Rand (Punkte) in einem TextFrame fest. |
| [getMarginRight()](#getMarginRight--) | Ermittelt oder legt den rechten Rand (Punkte) in einem TextFrame fest. |
| [setMarginRight(double value)](#setMarginRight-double-) | Ermittelt oder legt den rechten Rand (Punkte) in einem TextFrame fest. |
| [getMarginTop()](#getMarginTop--) | Ermittelt oder legt den oberen Rand (Punkte) in einem TextFrame fest. |
| [setMarginTop(double value)](#setMarginTop-double-) | Ermittelt oder legt den oberen Rand (Punkte) in einem TextFrame fest. |
| [getMarginBottom()](#getMarginBottom--) | Ermittelt oder legt den unteren Rand (Punkte) in einem TextFrame fest. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Ermittelt oder legt den unteren Rand (Punkte) in einem TextFrame fest. |
| [getWrapText()](#getWrapText--) | Wahr, wenn Text an den Rändern des TextFrames umgebrochen wird. |
| [setWrapText(byte value)](#setWrapText-byte-) | Wahr, wenn Text an den Rändern des TextFrames umgebrochen wird. |
| [getAnchoringType()](#getAnchoringType--) | Ermittelt oder legt den vertikalen Ankertext in einem TextFrame fest. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Ermittelt oder legt den vertikalen Ankertext in einem TextFrame fest. |
| [getCenterText()](#getCenterText--) | Wenn NullableBool.True, dann sollte der Text horizontal im Feld zentriert werden. |
| [setCenterText(byte value)](#setCenterText-byte-) | Wenn NullableBool.True, dann sollte der Text horizontal im Feld zentriert werden. |
| [getTextVerticalType()](#getTextVerticalType--) | Bestimmt die Textorientierung. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Bestimmt die Textorientierung. |
| [getAutofitType()](#getAutofitType--) | Ermittelt oder legt den Autofit-Modus des Textes fest. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Ermittelt oder legt den Autofit-Modus des Textes fest. |
| [getColumnCount()](#getColumnCount--) | Ermittelt oder legt die Anzahl der Spalten im Textbereich fest. |
| [setColumnCount(int value)](#setColumnCount-int-) | Ermittelt oder legt die Anzahl der Spalten im Textbereich fest. |
| [getColumnSpacing()](#getColumnSpacing--) | Ermittelt oder legt den Abstand zwischen Textspalten im Textbereich (in Punkten) fest. |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | Ermittelt oder legt den Abstand zwischen Textspalten im Textbereich (in Punkten) fest. |
| [getRotationAngle()](#getRotationAngle--) | Gibt die benutzerdefinierte Drehung an, die auf den Text innerhalb des Begrenzungsrahmens angewendet wird. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Gibt die benutzerdefinierte Drehung an, die auf den Text innerhalb des Begrenzungsrahmens angewendet wird. |
| [getTransform()](#getTransform--) | Ermittelt oder legt die Textumbruchform fest. |
| [setTransform(byte value)](#setTransform-byte-) | Ermittelt oder legt die Textumbruchform fest. |
| [getKeepTextFlat()](#getKeepTextFlat--) | Ermittelt oder legt fest, dass der Text flach bleibt, selbst wenn ein 3-D-Rotations-Effekt angewendet wurde. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | Ermittelt oder legt fest, dass der Text flach bleibt, selbst wenn ein 3-D-Rotations-Effekt angewendet wurde. |
| [getEffective()](#getEffective--) | Ermittelt wirksame Textframe-Formatierungsdaten mit angewandter Vererbung. |
### TextFrameFormat() {#TextFrameFormat--}
```
public TextFrameFormat()
```

Initialisiert eine neue Instanz der Klasse [TextFrameFormat](../../com.aspose.slides/textframeformat).

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Nur-Lesen long.

**Rückgabe:**
long
### getTextStyle() {#getTextStyle--}
```
public final ITextStyle getTextStyle()
```

Gibt den Stil des Textes zurück. Nur-Lesen [ITextStyle](../../com.aspose.slides/itextstyle).

**Rückgabe:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getThreeDFormat() {#getThreeDFormat--}
```
public final IThreeDFormat getThreeDFormat()
```

Gibt das ThreeDFormat-Objekt zurück, das die 3D-Effekteigenschaften für einen Text darstellt. Nur-Lesen [IThreeDFormat](../../com.aspose.slides/ithreedformat).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // Setze Texttransformation
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // Setze Extrusion
>      textFrame.getTextFrameFormat().getThreeDFormat().getExtrusionColor().setColor(Color.ORANGE);
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(6);
>      // Setze Kontur
>      textFrame.getTextFrameFormat().getThreeDFormat().getContourColor().setColor(Color.DARK_GRAY);
>      textFrame.getTextFrameFormat().getThreeDFormat().setContourWidth(1.5);
>      // Setze Tiefe
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      // Setze Material
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      // Setze Beleuchtung
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      // Setze Kameratyp
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabe:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)
### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```

Ermittelt oder legt den linken Rand (Punkte) in einem TextFrame fest. Lese/Schreib double.

**Rückgabe:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

Ermittelt oder legt den linken Rand (Punkte) in einem TextFrame fest. Lese/Schreib double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

Ermittelt oder legt den rechten Rand (Punkte) in einem TextFrame fest. Lese/Schreib double.

**Rückgabe:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

Ermittelt oder legt den rechten Rand (Punkte) in einem TextFrame fest. Lese/Schreib double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

Ermittelt oder legt den oberen Rand (Punkte) in einem TextFrame fest. Lese/Schreib double.

**Rückgabe:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

Ermittelt oder legt den oberen Rand (Punkte) in einem TextFrame fest. Lese/Schreib double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

Ermittelt oder legt den unteren Rand (Punkte) in einem TextFrame fest. Lese/Schreib double.

**Rückgabe:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

Ermittelt oder legt den unteren Rand (Punkte) in einem TextFrame fest. Lese/Schreib double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getWrapText() {#getWrapText--}
```
public final byte getWrapText()
```

Wahr, wenn Text an den Rändern des TextFrames umgebrochen wird. Lese/Schreib [NullableBool](../../com.aspose.slides/nullablebool).

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

**Rückgabe:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public final void setWrapText(byte value)
```

Wahr, wenn Text an den Rändern des TextFrames umgebrochen wird. Lese/Schreib [NullableBool](../../com.aspose.slides/nullablebool).

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getAnchoringType() {#getAnchoringType--}
```
public final byte getAnchoringType()
```

Ermittelt oder legt den vertikalen Ankertext in einem TextFrame fest. Lese/Schreib [TextAnchorType](../../com.aspose.slides/textanchortype).

**Rückgabe:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public final void setAnchoringType(byte value)
```

Ermittelt oder legt den vertikalen Ankertext in einem TextFrame fest. Lese/Schreib [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getCenterText() {#getCenterText--}
```
public final byte getCenterText()
```

Wenn NullableBool.True, dann sollte der Text horizontal im Feld zentriert werden. Lese/Schreib [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public final void setCenterText(byte value)
```

Wenn NullableBool.True, dann sollte der Text horizontal im Feld zentriert werden. Lese/Schreib [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

Bestimmt die Textorientierung. Der resultierende Wert der visuellen Textrotation ergibt sich aus dieser Eigenschaft und dem benutzerdefinierten Winkel in RotationAngle. Lese/Schreib [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Rückgabe:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

Bestimmt die Textorientierung. Der resultierende Wert der visuellen Textrotation ergibt sich aus dieser Eigenschaft und dem benutzerdefinierten Winkel in RotationAngle. Lese/Schreib [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getAutofitType() {#getAutofitType--}
```
public final byte getAutofitType()
```

Ermittelt oder legt den Autofit-Modus des Textes fest. Lese/Schreib [TextAutofitType](../../com.aspose.slides/textautofittype).

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

**Rückgabe:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public final void setAutofitType(byte value)
```

Ermittelt oder legt den Autofit-Modus des Textes fest. Lese/Schreib [TextAutofitType](../../com.aspose.slides/textautofittype).

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getColumnCount() {#getColumnCount--}
```
public final int getColumnCount()
```

Ermittelt oder legt die Anzahl der Spalten im Textbereich fest. Dieser Wert muss positiv sein; andernfalls wird er auf Null gesetzt. Wert 0 bedeutet undefiniert. Lese/Schreib int.

--------------------

> ```
> Der folgende Beispielcode zeigt, wie man in einem TextFrame einer PowerPoint-Präsentation Spalten hinzufügt.
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


**Rückgabe:**
int
### setColumnCount(int value) {#setColumnCount-int-}
```
public final void setColumnCount(int value)
```

Ermittelt oder legt die Anzahl der Spalten im Textbereich fest. Dieser Wert muss positiv sein; andernfalls wird er auf Null gesetzt. Wert 0 bedeutet undefiniert. Lese/Schreib int.

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getColumnSpacing() {#getColumnSpacing--}
```
public final double getColumnSpacing()
```

Ermittelt oder legt den Abstand zwischen Textspalten im Textbereich (in Punkten) fest. Dies gilt nur, wenn mehr als eine Spalte vorhanden ist. Der Wert muss positiv sein; andernfalls wird er auf Null gesetzt. Lese/Schreib double.

**Rückgabe:**
double
### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public final void setColumnSpacing(double value)
```

Ermittelt oder legt den Abstand zwischen Textspalten im Textbereich (in Punkten) fest. Dies gilt nur, wenn mehr als eine Spalte vorhanden ist. Der Wert muss positiv sein; andernfalls wird er auf Null gesetzt. Lese/Schreib double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getRotationAngle() {#getRotationAngle--}
```
public final float getRotationAngle()
```

Gibt die benutzerdefinierte Drehung an, die auf den Text innerhalb des Begrenzungsrahmens angewendet wird. Wenn nicht angegeben, wird die Drehung der zugehörigen Form verwendet. Ist sie angegeben, wird sie unabhängig von der Form angewendet. Das Ergebnis der visuellen Textrotation ergibt sich aus dieser Eigenschaft und dem vordefinierten vertikalen Typ in TextVerticalType. Lese/Schreib float.

--------------------

> ```
> Betrachten Sie den Fall, dass einer Form eine Drehung von 90 Grad im Uhrzeigersinn angewendet wird. 
>  Zusätzlich dazu hat der Textkörper selbst eine Drehung von -90 Grad gegen den Uhrzeigersinn angewendet. 
>  Dann würde die resultierende Form scheinbar gedreht erscheinen, aber der darin enthaltene Text würde so aussehen, als wäre er überhaupt nicht gedreht worden.
```

**Rückgabe:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public final void setRotationAngle(float value)
```

Gibt die benutzerdefinierte Drehung an, die auf den Text innerhalb des Begrenzungsrahmens angewendet wird. Wenn nicht angegeben, wird die Drehung der zugehörigen Form verwendet. Ist sie angegeben, wird sie unabhängig von der Form angewendet. Das Ergebnis der visuellen Textrotation ergibt sich aus dieser Eigenschaft und dem vordefinierten vertikalen Typ in TextVerticalType. Lese/Schreib float.

--------------------

> ```
> Betrachten Sie den Fall, dass einer Form eine Drehung von 90 Grad im Uhrzeigersinn angewendet wird. 
>  Zusätzlich dazu hat der Textkörper selbst eine Drehung von -90 Grad 
>  gegen den Uhrzeigersinn erhalten. Dann würde die resultierende Form scheinen zu
>  drehen, aber der darin befindliche Text würde so aussehen, als wäre er überhaupt nicht gedreht worden.
```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### getTransform() {#getTransform--}
```
public final byte getTransform()
```

Ermittelt oder legt die Textumbruchform fest. Lese/Schreib [TextShapeType](../../com.aspose.slides/textshapetype).

**Rückgabe:**
byte
### setTransform(byte value) {#setTransform-byte-}
```
public final void setTransform(byte value)
```

Ermittelt oder legt die Textumbruchform fest. Lese/Schreib [TextShapeType](../../com.aspose.slides/textshapetype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getKeepTextFlat() {#getKeepTextFlat--}
```
public final boolean getKeepTextFlat()
```

Ermittelt oder legt fest, dass der Text flach bleibt, selbst wenn ein 3-D-Rotations-Effekt angewendet wurde. Lese/Schreib boolean.

**Rückgabe:**
boolean
### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public final void setKeepTextFlat(boolean value)
```

Ermittelt oder legt fest, dass der Text flach bleibt, selbst wenn ein 3-D-Rotations-Effekt angewendet wurde. Lese/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getEffective() {#getEffective--}
```
public final ITextFrameFormatEffectiveData getEffective()
```

Ermittelt wirksame Textframe-Formatierungsdaten mit angewandter Vererbung.

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

**Rückgabe:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).