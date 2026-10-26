---
title: TextFrameFormat
second_title: Aspose.Slides für Android über die Java-API-Referenz
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
| [getMarginLeft()](#getMarginLeft--) | Gibt den linken Rand (Punkte) in einem TextFrame zurück oder legt ihn fest. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Gibt den linken Rand (Punkte) in einem TextFrame zurück oder legt ihn fest. |
| [getMarginRight()](#getMarginRight--) | Gibt den rechten Rand (Punkte) in einem TextFrame zurück oder legt ihn fest. |
| [setMarginRight(double value)](#setMarginRight-double-) | Gibt den rechten Rand (Punkte) in einem TextFrame zurück oder legt ihn fest. |
| [getMarginTop()](#getMarginTop--) | Gibt den oberen Rand (Punkte) in einem TextFrame zurück oder legt ihn fest. |
| [setMarginTop(double value)](#setMarginTop-double-) | Gibt den oberen Rand (Punkte) in einem TextFrame zurück oder legt ihn fest. |
| [getMarginBottom()](#getMarginBottom--) | Gibt den unteren Rand (Punkte) in einem TextFrame zurück oder legt ihn fest. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Gibt den unteren Rand (Punkte) in einem TextFrame zurück oder legt ihn fest. |
| [getWrapText()](#getWrapText--) | Wahr, wenn der Text an den Rändern des TextFrames umbrochen wird. |
| [setWrapText(byte value)](#setWrapText-byte-) | Wahr, wenn der Text an den Rändern des TextFrames umbrochen wird. |
| [getAnchoringType()](#getAnchoringType--) | Gibt den vertikalen Ankertext in einem TextFrame zurück oder legt ihn fest. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Gibt den vertikalen Ankertext in einem TextFrame zurück oder legt ihn fest. |
| [getCenterText()](#getCenterText--) | Falls NullableBool.True, wird der Text horizontal in der Box zentriert. |
| [setCenterText(byte value)](#setCenterText-byte-) | Falls NullableBool.True, wird der Text horizontal in der Box zentriert. |
| [getTextVerticalType()](#getTextVerticalType--) | Bestimmt die Textausrichtung. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Bestimmt die Textausrichtung. |
| [getAutofitType()](#getAutofitType--) | Gibt den Autofit-Modus des Textes zurück oder legt ihn fest. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Gibt den Autofit-Modus des Textes zurück oder legt ihn fest. |
| [getColumnCount()](#getColumnCount--) | Gibt die Anzahl der Spalten im Textbereich zurück oder legt sie fest. |
| [setColumnCount(int value)](#setColumnCount-int-) | Gibt die Anzahl der Spalten im Textbereich zurück oder legt sie fest. |
| [getColumnSpacing()](#getColumnSpacing--) | Gibt den Abstand zwischen Textspalten im Textbereich zurück oder legt ihn fest (in Punkten). |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | Gibt den Abstand zwischen Textspalten im Textbereich zurück oder legt ihn fest (in Punkten). |
| [getRotationAngle()](#getRotationAngle--) | Gibt die benutzerdefinierte Drehung an, die auf den Text innerhalb des Begrenzungsrahmens angewendet wird. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Gibt die benutzerdefinierte Drehung an, die auf den Text innerhalb des Begrenzungsrahmens angewendet wird. |
| [getTransform()](#getTransform--) | Gibt die Form des Textumbruchs zurück oder legt sie fest. |
| [setTransform(byte value)](#setTransform-byte-) | Gibt die Form des Textumbruchs zurück oder legt sie fest. |
| [getKeepTextFlat()](#getKeepTextFlat--) | Gibt an, ob der Text flach gehalten wird, selbst wenn ein 3-D-Drehungseffekt angewendet wurde, oder legt dies fest. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | Gibt an, ob der Text flach gehalten wird, selbst wenn ein 3-D-Drehungseffekt angewendet wurde, oder legt dies fest. |
| [getEffective()](#getEffective--) | Gibt die wirksamen TextFrame-Formatierungsdaten mit angewandter Vererbung zurück. |
### TextFrameFormat() {#TextFrameFormat--}
```
public TextFrameFormat()
```

Initialisiert eine neue Instanz der Klasse [TextFrameFormat](../../com.aspose.slides/textframeformat).

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Nur-Lese long.

**Rückgabe:**
long
### getTextStyle() {#getTextStyle--}
```
public final ITextStyle getTextStyle()
```

Gibt den Stil des Textes zurück. Nur-Lese [ITextStyle](../../com.aspose.slides/itextstyle).

**Rückgabe:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getThreeDFormat() {#getThreeDFormat--}
```
public final IThreeDFormat getThreeDFormat()
```

Gibt das ThreeDFormat-Objekt zurück, das die 3D-Effekt-Eigenschaften für einen Text darstellt. Nur-Lese [IThreeDFormat](../../com.aspose.slides/ithreedformat).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // Texttransformation festlegen
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // Extrusion festlegen
>      textFrame.getTextFrameFormat().getThreeDFormat().getExtrusionColor().setColor(Color.ORANGE);
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(6);
>      // Kontur festlegen
>      textFrame.getTextFrameFormat().getThreeDFormat().getContourColor().setColor(Color.DARK_GRAY);
>      textFrame.getTextFrameFormat().getThreeDFormat().setContourWidth(1.5);
>      // Tiefe festlegen
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      // Material festlegen
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      // Beleuchtung festlegen
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      // Kameratyp festlegen
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

Gibt den linken Rand (Punkte) in einem TextFrame zurück oder legt ihn fest. Lese-/Schreib double.

**Rückgabe:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

Gibt den linken Rand (Punkte) in einem TextFrame zurück oder legt ihn fest. Lese-/Schreib double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

Gibt den rechten Rand (Punkte) in einem TextFrame zurück oder legt ihn fest. Lese-/Schreib double.

**Rückgabe:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

Gibt den rechten Rand (Punkte) in einem TextFrame zurück oder legt ihn fest. Lese-/Schreib double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

Gibt den oberen Rand (Punkte) in einem TextFrame zurück oder legt ihn fest. Lese-/Schreib double.

**Rückgabe:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

Gibt den oberen Rand (Punkte) in einem TextFrame zurück oder legt ihn fest. Lese-/Schreib double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

Gibt den unteren Rand (Punkte) in einem TextFrame zurück oder legt ihn fest. Lese-/Schreib double.

**Rückgabe:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

Gibt den unteren Rand (Punkte) in einem TextFrame zurück oder legt ihn fest. Lese-/Schreib double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public final byte getWrapText()
```

Wahr, wenn der Text an den Rändern des TextFrames umbrochen wird. Lese-/Schreib [NullableBool](../../com.aspose.slides/nullablebool).

--------------------

> ```
> Der folgende Beispielcode zeigt, wie man Text in einer Präsentation umbricht.
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

Wahr, wenn der Text an den Rändern des TextFrames umbrochen wird. Lese-/Schreib [NullableBool](../../com.aspose.slides/nullablebool).

--------------------

> ```
> Der folgende Beispielcode zeigt, wie man Text in einer Präsentation umbricht.
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

Gibt den vertikalen Ankertext in einem TextFrame zurück oder legt ihn fest. Lese-/Schreib [TextAnchorType](../../com.aspose.slides/textanchortype).

**Rückgabe:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public final void setAnchoringType(byte value)
```

Gibt den vertikalen Ankertext in einem TextFrame zurück oder legt ihn fest. Lese-/Schreib [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public final byte getCenterText()
```

Falls NullableBool.True, wird der Text horizontal in der Box zentriert. Lese-/Schreib [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public final void setCenterText(byte value)
```

Falls NullableBool.True, wird der Text horizontal in der Box zentriert. Lese-/Schreib [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

Bestimmt die Textausrichtung. Der resultierende Wert der visuellen Textrotation ergibt sich aus dieser Eigenschaft und dem benutzerdefinierten Winkel in der Eigenschaft RotationAngle. Lese-/Schreib [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Rückgabe:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

Bestimmt die Textausrichtung. Der resultierende Wert der visuellen Textrotation ergibt sich aus dieser Eigenschaft und dem benutzerdefinierten Winkel in der Eigenschaft RotationAngle. Lese-/Schreib [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public final byte getAutofitType()
```

Gibt den Autofit-Modus des Textes zurück oder legt ihn fest. Lese-/Schreib [TextAutofitType](../../com.aspose.slides/textautofittype).

--------------------

> ```
> Der folgende Beispielcode zeigt, wie man die Form auf „Fit Text“ in einer PowerPoint-Präsentation anpasst.
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
>  Der folgende Beispielcode zeigt, wie man Text bei Überlauf verkleinert.
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

Gibt den Autofit-Modus des Textes zurück oder legt ihn fest. Lese-/Schreib [TextAutofitType](../../com.aspose.slides/textautofittype).

--------------------

> ```
> Der folgende Beispielcode zeigt, wie man die Form auf Fit Text in einer PowerPoint-Präsentation anpasst.
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
>  Der folgende Beispielcode zeigt, wie man Text bei Überlauf verkleinert.
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

Gibt die Anzahl der Spalten im Textbereich zurück oder legt sie fest. Dieser Wert muss positiv sein; andernfalls wird er auf 0 gesetzt. Wert 0 bedeutet undefiniert. Lese-/Schreib int.

--------------------

> ```
> Der folgende Beispielcode zeigt, wie man eine Spalte im Textframe innerhalb einer PowerPoint-Präsentation hinzufügt.
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

Gibt die Anzahl der Spalten im Textbereich zurück oder legt sie fest. Dieser Wert muss positiv sein; andernfalls wird er auf 0 gesetzt. Wert 0 bedeutet undefiniert. Lese-/Schreib int.

--------------------

> ```
> Der folgende Beispielcode zeigt, wie man eine Spalte im Textframe innerhalb einer PowerPoint-Präsentation hinzufügt.
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
>  
>  Der folgende Beispielcode zeigt, wie man Text bei Überlauf verkleinert.
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
| value | int |  |

### getColumnSpacing() {#getColumnSpacing--}
```
public final double getColumnSpacing()
```

Gibt den Abstand zwischen Textspalten im Textbereich zurück oder legt ihn fest (in Punkten). Dies gilt nur, wenn mehr als eine Spalte vorhanden ist. Der Wert muss positiv sein; andernfalls wird er auf 0 gesetzt. Lese-/Schreib double.

**Rückgabe:**
double
### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public final void setColumnSpacing(double value)
```

Gibt den Abstand zwischen Textspalten im Textbereich zurück oder legt ihn fest (in Punkten). Dies gilt nur, wenn mehr als eine Spalte vorhanden ist. Der Wert muss positiv sein; andernfalls wird er auf 0 gesetzt. Lese-/Schreib double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getRotationAngle() {#getRotationAngle--}
```
public final float getRotationAngle()
```

Gibt die benutzerdefinierte Drehung an, die auf den Text innerhalb des Begrenzungsrahmens angewendet wird. Ist sie nicht angegeben, wird die Drehung der zugehörigen Form verwendet. Ist sie angegeben, wird sie unabhängig von der Form angewendet. Das Ergebnis der visuellen Textrotation ergibt sich aus dieser Eigenschaft und dem vordefinierten vertikalen Typ in der Eigenschaft TextVerticalType. Lese-/Schreib float.

--------------------

> ```
> Betrachten Sie den Fall, dass einer Form eine Drehung von 90 Grad im Uhrzeigersinn zugewiesen wird. 
>  Zusätzlich dazu hat der Textkörper selbst eine Drehung von -90 Grad 
>  gegen den Uhrzeigersinn erhalten. Dann würde die resultierende Form gedreht erscheinen, 
>  aber der Text darin würde so aussehen, als wäre er überhaupt nicht gedreht worden.
```

**Rückgabe:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public final void setRotationAngle(float value)
```

Gibt die benutzerdefinierte Drehung an, die auf den Text innerhalb des Begrenzungsrahmens angewendet wird. Ist sie nicht angegeben, wird die Drehung der zugehörigen Form verwendet. Ist sie angegeben, wird sie unabhängig von der Form angewendet. Das Ergebnis der visuellen Textrotation ergibt sich aus dieser Eigenschaft und dem vordefinierten vertikalen Typ in der Eigenschaft TextVerticalType. Lese-/Schreib float.

--------------------

> ```
> Betrachten Sie den Fall, dass einer Form eine Drehung von 90 Grad im Uhrzeigersinn zugewiesen wird. 
>  Zusätzlich dazu hat der Textkörper selbst eine Drehung von -90 Grad 
>  gegen den Uhrzeigersinn erhalten. Dann würde die resultierende Form erscheinen, 
>  gedreht, aber der Text darin würde so aussehen, als wäre er überhaupt nicht gedreht worden.
```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getTransform() {#getTransform--}
```
public final byte getTransform()
```

Gibt die Form des Textumbruchs zurück oder legt sie fest. Lese-/Schreib [TextShapeType](../../com.aspose.slides/textshapetype).

**Rückgabe:**
byte
### setTransform(byte value) {#setTransform-byte-}
```
public final void setTransform(byte value)
```

Gibt die Form des Textumbruchs zurück oder legt sie fest. Lese-/Schreib [TextShapeType](../../com.aspose.slides/textshapetype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getKeepTextFlat() {#getKeepTextFlat--}
```
public final boolean getKeepTextFlat()
```

Gibt an, ob der Text flach gehalten wird, selbst wenn ein 3-D-Drehungseffekt angewendet wurde, oder legt dies fest. Lese-/Schreib boolean.

**Rückgabe:**
boolean
### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public  {  ?  }
```

Gibt an, ob der Text flach gehalten wird, selbst wenn ein 3-D-Drehungseffekt angewendet wurde, oder legt dies fest. Lese-/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public final ITextFrameFormatEffectiveData getEffective()
```

Gibt die wirksamen TextFrame-Formatierungsdaten mit angewandter Vererbung zurück.

--------------------

> ```
> Dieses Beispiel zeigt das Abrufen einiger effektiver Textframe-Formatierungseigenschaften.
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