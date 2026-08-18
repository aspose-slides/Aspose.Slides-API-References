---
title: TextFrameFormat
second_title: Referencia de API de Aspose.Slides para Java
description: Contiene las propiedades formatTextFrameFormatting de los TextFrames.
type: docs
url: /es/com.aspose.slides/textframeformat/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Todas las interfaces implementadas:**
[com.aspose.slides.ITextFrameFormat](../../com.aspose.slides/itextframeformat), [com.aspose.slides.IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
```
public final class TextFrameFormat extends PVIObject implements ITextFrameFormat, IChartTextBlockFormat
```

Contiene las propiedades **formatTextFrameFormatting** del TextFrame.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [TextFrameFormat()](#TextFrameFormat--) | Inicializa una nueva instancia de la clase [TextFrameFormat](../../com.aspose.slides/textframeformat). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getTextStyle()](#getTextStyle--) | Devuelve el estilo del texto. |
| [getThreeDFormat()](#getThreeDFormat--) | Devuelve el objeto ThreeDFormat que representa las propiedades del efecto 3D para un texto. |
| [getMarginLeft()](#getMarginLeft--) | Devuelve o establece el margen izquierdo (puntos) en un TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Devuelve o establece el margen izquierdo (puntos) en un TextFrame. |
| [getMarginRight()](#getMarginRight--) | Devuelve o establece el margen derecho (puntos) en un TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Devuelve o establece el margen derecho (puntos) en un TextFrame. |
| [getMarginTop()](#getMarginTop--) | Devuelve o establece el margen superior (puntos) en un TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Devuelve o establece el margen superior (puntos) en un TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Devuelve o establece el margen inferior (puntos) en un TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Devuelve o establece el margen inferior (puntos) en un TextFrame. |
| [getWrapText()](#getWrapText--) | True si el texto se envuelve en los márgenes del TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | True si el texto se envuelve en los márgenes del TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | Devuelve o establece el anclaje vertical del texto en un TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Devuelve o establece el anclaje vertical del texto en un TextFrame. |
| [getCenterText()](#getCenterText--) | Si NullableBool.True entonces el texto debe centrarse horizontalmente en el recuadro. |
| [setCenterText(byte value)](#setCenterText-byte-) | Si NullableBool.True entonces el texto debe centrarse horizontalmente en el recuadro. |
| [getTextVerticalType()](#getTextVerticalType--) | Determina la orientación del texto. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Determina la orientación del texto. |
| [getAutofitType()](#getAutofitType--) | Devuelve o establece el modo de ajuste automático del texto. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Devuelve o establece el modo de ajuste automático del texto. |
| [getColumnCount()](#getColumnCount--) | Devuelve o establece el número de columnas en el área de texto. |
| [setColumnCount(int value)](#setColumnCount-int-) | Devuelve o establece el número de columnas en el área de texto. |
| [getColumnSpacing()](#getColumnSpacing--) | Devuelve o establece el espacio entre columnas de texto en el área de texto (en puntos). |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | Devuelve o establece el espacio entre columnas de texto en el área de texto (en puntos). |
| [getRotationAngle()](#getRotationAngle--) | Especifica la rotación personalizada que se aplica al texto dentro del cuadro delimitador. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Especifica la rotación personalizada que se aplica al texto dentro del cuadro delimitador. |
| [getTransform()](#getTransform--) | Obtiene o establece la forma de ajuste de texto. |
| [setTransform(byte value)](#setTransform-byte-) | Obtiene o establece la forma de ajuste de texto. |
| [getKeepTextFlat()](#getKeepTextFlat--) | Obtiene o establece la conservación del texto plano incluso si se aplicó un efecto de rotación 3-D. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | Obtiene o establece la conservación del texto plano incluso si se aplicó un efecto de rotación 3-D. |
| [getEffective()](#getEffective--) | Obtiene datos de formato de cuadro de texto efectivos con la herencia aplicada. |
### TextFrameFormat() {#TextFrameFormat--}
```
public TextFrameFormat()
```

Inicializa una nueva instancia de la clase [TextFrameFormat](../../com.aspose.slides/textframeformat).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versión. Sólo lectura long.

**Devuelve:**
long
### getTextStyle() {#getTextStyle--}
```
public final ITextStyle getTextStyle()
```

Devuelve el estilo del texto. Sólo lectura [ITextStyle](../../com.aspose.slides/itextstyle).

**Devuelve:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getThreeDFormat() {#getThreeDFormat--}
```
public final IThreeDFormat getThreeDFormat()
```

Devuelve el objeto ThreeDFormat que representa las propiedades del efecto 3D para un texto. Sólo lectura [IThreeDFormat](../../com.aspose.slides/ithreedformat).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // Establecer transformación de texto
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // Establecer extrusión
>      textFrame.getTextFrameFormat().getThreeDFormat().getExtrusionColor().setColor(Color.ORANGE);
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(6);
>      // Establecer contorno
>      textFrame.getTextFrameFormat().getThreeDFormat().getContourColor().setColor(Color.DARK_GRAY);
>      textFrame.getTextFrameFormat().getThreeDFormat().setContourWidth(1.5);
>      // Establecer profundidad
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      // Establecer material
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      // Establecer iluminación
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      // Establecer tipo de cámara
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)
### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```

Devuelve o establece el margen izquierdo (puntos) en un TextFrame. Lectura/escritura double.

**Devuelve:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

Devuelve o establece el margen izquierdo (puntos) en un TextFrame. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

Devuelve o establece el margen derecho (puntos) en un TextFrame. Lectura/escritura double.

**Devuelve:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

Devuelve o establece el margen derecho (puntos) en un TextFrame. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

Devuelve o establece el margen superior (puntos) en un TextFrame. Lectura/escritura double.

**Devuelve:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

Devuelve o establece el margen superior (puntos) en un TextFrame. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

Devuelve o establece el margen inferior (puntos) en un TextFrame. Lectura/escritura double.

**Devuelve:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

Devuelve o establece el margen inferior (puntos) en un TextFrame. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |
### getWrapText() {#getWrapText--}
```
public final byte getWrapText()
```

True si el texto se envuelve en los márgenes del TextFrame. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

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

**Devuelve:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public final void setWrapText(byte value)
```

True si el texto se envuelve en los márgenes del TextFrame. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |
### getAnchoringType() {#getAnchoringType--}
```
public final byte getAnchoringType()
```

Devuelve o establece el anclaje vertical del texto en un TextFrame. Lectura/escritura [TextAnchorType](../../com.aspose.slides/textanchortype).

**Devuelve:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public final void setAnchoringType(byte value)
```

Devuelve o establece el anclaje vertical del texto en un TextFrame. Lectura/escritura [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |
### getCenterText() {#getCenterText--}
```
public final byte getCenterText()
```

Si NullableBool.True entonces el texto debe centrarse horizontalmente en el recuadro. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public final void setCenterText(byte value)
```

Si NullableBool.True entonces el texto debe centrarse horizontalmente en el recuadro. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

Determina la orientación del texto. El valor resultante de la rotación visual del texto se resume de esta propiedad y el ángulo personalizado en la propiedad RotationAngle. Lectura/escritura [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Devuelve:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

Determina la orientación del texto. El valor resultante de la rotación visual del texto se resume de esta propiedad y el ángulo personalizado en la propiedad RotationAngle. Lectura/escritura [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |
### getAutofitType() {#getAutofitType--}
```
public final byte getAutofitType()
```

Devuelve o establece el modo de ajuste automático del texto. Lectura/escritura [TextAutofitType](../../com.aspose.slides/textautofittype).

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

**Devuelve:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public final void setAutofitType(byte value)
```

Devuelve o establece el modo de ajuste automático del texto. Lectura/escritura [TextAutofitType](../../com.aspose.slides/textautofittype).

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |
### getColumnCount() {#getColumnCount--}
```
public final int getColumnCount()
```

Devuelve o establece el número de columnas en el área de texto. Este valor debe ser un número positivo. De lo contrario, se establecerá a cero. El valor 0 significa valor indefinido. Lectura/escritura int.

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

**Devuelve:**
int
### setColumnCount(int value) {#setColumnCount-int-}
```
public final void setColumnCount(int value)
```

Devuelve o establece el número de columnas en el área de texto. Este valor debe ser un número positivo. De lo contrario, se establecerá a cero. El valor 0 significa valor indefinido. Lectura/escritura int.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |
### getColumnSpacing() {#getColumnSpacing--}
```
public final double getColumnSpacing()
```

Devuelve o establece el espacio entre columnas de texto en el área de texto (en puntos). Esto solo debe aplicarse cuando hay más de una columna presente. Este valor debe ser un número positivo. De lo contrario, se establecerá a cero. Lectura/escritura double.

**Devuelve:**
double
### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public final void setColumnSpacing(double value)
```

Devuelve o establece el espacio entre columnas de texto en el área de texto (en puntos). Esto solo debe aplicarse cuando hay más de una columna presente. Este valor debe ser un número positivo. De lo contrario, se establecerá a cero. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |
### getRotationAngle() {#getRotationAngle--}
```
public final float getRotationAngle()
```

Especifica la rotación personalizada que se aplica al texto dentro del cuadro delimitador. Si no se especifica, se usa la rotación de la forma acompañante. Si se especifica, se aplica independientemente de la forma. Es decir, la forma puede tener una rotación aplicada además de la rotación del texto. El valor resultante de la rotación visual del texto se resume de esta propiedad y el tipo vertical predefinido en la propiedad TextVerticalType. Lectura/escritura float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**Devuelve:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public final void setRotationAngle(float value)
```

Especifica la rotación personalizada que se aplica al texto dentro del cuadro delimitador. Si no se especifica, se usa la rotación de la forma acompañante. Si se especifica, se aplica independientemente de la forma. Es decir, la forma puede tener una rotación aplicada además de la rotación del texto. El valor resultante de la rotación visual del texto se resume de esta propiedad y el tipo vertical predefinido en la propiedad TextVerticalType. Lectura/escritura float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |
### getTransform() {#getTransform--}
```
public final byte getTransform()
```

Obtiene o establece la forma de ajuste de texto. Lectura/escritura [TextShapeType](../../com.aspose.slides/textshapetype).

**Devuelve:**
byte
### setTransform(byte value) {#setTransform-byte-}
```
public final void setTransform(byte value)
```

Obtiene o establece la forma de ajuste de texto. Lectura/escritura [TextShapeType](../../com.aspose.slides/textshapetype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |
### getKeepTextFlat() {#getKeepTextFlat--}
```
public final boolean getKeepTextFlat()
```

Obtiene o establece la conservación del texto plano incluso si se aplicó un efecto de rotación 3-D. Lectura/escritura boolean.

**Devuelve:**
boolean
### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public final void setKeepTextFlat(boolean value)
```

Obtiene o establece la conservación del texto plano incluso si se aplicó un efecto de rotación 3-D. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getEffective() {#getEffective--}
```
public final ITextFrameFormatEffectiveData getEffective()
```

Obtiene datos de formato de cuadro de texto efectivos con la herencia aplicada.

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

**Devuelve:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - Un [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).