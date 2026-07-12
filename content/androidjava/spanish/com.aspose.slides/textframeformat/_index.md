---
title: TextFrameFormat
second_title: Referencia de API Java de Aspose.Slides para Android
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

Contiene las propiedades formatTextFrameFormatting del TextFrame.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [TextFrameFormat()](#TextFrameFormat--) | Inicializa una nueva instancia de la clase [TextFrameFormat](../../com.aspose.slides/textframeformat). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getTextStyle()](#getTextStyle--) | Devuelve el estilo del texto. |
| [getThreeDFormat()](#getThreeDFormat--) | Devuelve el objeto ThreeDFormat que representa las propiedades de efecto 3d para un texto. |
| [getMarginLeft()](#getMarginLeft--) | Obtiene o establece el margen izquierdo (puntos) en un TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Obtiene o establece el margen izquierdo (puntos) en un TextFrame. |
| [getMarginRight()](#getMarginRight--) | Obtiene o establece el margen derecho (puntos) en un TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Obtiene o establece el margen derecho (puntos) en un TextFrame. |
| [getMarginTop()](#getMarginTop--) | Obtiene o establece el margen superior (puntos) en un TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Obtiene o establece el margen superior (puntos) en un TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Obtiene o establece el margen inferior (puntos) en un TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Obtiene o establece el margen inferior (puntos) en un TextFrame. |
| [getWrapText()](#getWrapText--) | Verdadero si el texto se ajusta en los márgenes del TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | Verdadero si el texto se ajusta en los márgenes del TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | Obtiene o establece la ancla vertical del texto en un TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Obtiene o establece la ancla vertical del texto en un TextFrame. |
| [getCenterText()](#getCenterText--) | Si NullableBool.True entonces el texto debe centrarse horizontalmente en el cuadro. |
| [setCenterText(byte value)](#setCenterText-byte-) | Si NullableBool.True entonces el texto debe centrarse horizontalmente en el cuadro. |
| [getTextVerticalType()](#getTextVerticalType--) | Determina la orientación del texto. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Determina la orientación del texto. |
| [getAutofitType()](#getAutofitType--) | Obtiene o establece el modo de ajuste automático del texto. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Obtiene o establece el modo de ajuste automático del texto. |
| [getColumnCount()](#getColumnCount--) | Obtiene o establece el número de columnas en el área de texto. |
| [setColumnCount(int value)](#setColumnCount-int-) | Obtiene o establece el número de columnas en el área de texto. |
| [getColumnSpacing()](#getColumnSpacing--) | Obtiene o establece el espacio entre columnas de texto en el área de texto (en puntos). |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | Obtiene o establece el espacio entre columnas de texto en el área de texto (en puntos). |
| [getRotationAngle()](#getRotationAngle--) | Especifica la rotación personalizada que se aplica al texto dentro del cuadro delimitador. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Especifica la rotación personalizada que se aplica al texto dentro del cuadro delimitador. |
| [getTransform()](#getTransform--) | Obtiene o establece la forma de ajuste de texto. |
| [setTransform(byte value)](#setTransform-byte-) | Obtiene o establece la forma de ajuste de texto. |
| [getKeepTextFlat()](#getKeepTextFlat--) | Obtiene o establece mantener el texto plano incluso si se aplicó un efecto de Rotación 3-D. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | Obtiene o establece mantener el texto plano incluso si se aplicó un efecto de Rotación 3-D. |
| [getEffective()](#getEffective--) | Obtiene los datos efectivos de formato del marco de texto con la herencia aplicada. |
### TextFrameFormat() {#TextFrameFormat--}
```
public TextFrameFormat()
```


Inicializa una nueva instancia de la clase [TextFrameFormat](../../com.aspose.slides/textframeformat).

### getVersion() {#getVersion--}
```
public long getVersion()
```


Versión. Solo lectura long.

**Devuelve:**
long
### getTextStyle() {#getTextStyle--}
```
public final ITextStyle getTextStyle()
```


Devuelve el estilo del texto. Solo lectura [ITextStyle](../../com.aspose.slides/itextstyle).

**Devuelve:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getThreeDFormat() {#getThreeDFormat--}
```
public final IThreeDFormat getThreeDFormat()
```


Devuelve el objeto ThreeDFormat que representa las propiedades de efecto 3d para un texto. Solo lectura [IThreeDFormat](../../com.aspose.slides/ithreedformat).

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


Obtiene o establece el margen izquierdo (puntos) en un TextFrame. Lectura/escritura double.

**Devuelve:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```


Obtiene o establece el margen izquierdo (puntos) en un TextFrame. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```


Obtiene o establece el margen derecho (puntos) en un TextFrame. Lectura/escritura double.

**Devuelve:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```


Obtiene o establece el margen derecho (puntos) en un TextFrame. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```


Obtiene o establece el margen superior (puntos) en un TextFrame. Lectura/escritura double.

**Devuelve:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```


Obtiene o establece el margen superior (puntos) en un TextFrame. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```


Obtiene o establece el margen inferior (puntos) en un TextFrame. Lectura/escritura double.

**Devuelve:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```


Obtiene o establece el margen inferior (puntos) en un TextFrame. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public final byte getWrapText()
```


Verdadero si el texto se ajusta en los márgenes del TextFrame. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

--------------------

> ```
> El siguiente código de ejemplo muestra cómo ajustar texto en Presentation.
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


Verdadero si el texto se ajusta en los márgenes del TextFrame. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

--------------------

> ```
> El siguiente código de ejemplo muestra cómo ajustar texto en Presentation.
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


Obtiene o establece la ancla vertical del texto en un TextFrame. Lectura/escritura [TextAnchorType](../../com.aspose.slides/textanchortype).

**Devuelve:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public final void setAnchoringType(byte value)
```


Obtiene o establece la ancla vertical del texto en un TextFrame. Lectura/escritura [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public final byte getCenterText()
```


Si NullableBool.True entonces el texto debe centrarse horizontalmente en el cuadro. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public final void setCenterText(byte value)
```


Si NullableBool.True entonces el texto debe centrarse horizontalmente en el cuadro. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```


Determina la orientación del texto. El valor resultante de la rotación visual del texto se resume a partir de esta propiedad y del ángulo personalizado en la propiedad RotationAngle. Lectura/escritura [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Devuelve:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```


Determina la orientación del texto. El valor resultante de la rotación visual del texto se resume a partir de esta propiedad y del ángulo personalizado en la propiedad RotationAngle. Lectura/escritura [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public final byte getAutofitType()
```


Obtiene o establece el modo de ajuste automático del texto. Lectura/escritura [TextAutofitType](../../com.aspose.slides/textautofittype).

--------------------

> ```
> El siguiente código de muestra muestra cómo redimensionar la forma para Ajustar Texto en una presentación de PowerPoint.
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
>  El siguiente código de muestra muestra cómo reducir el texto cuando se desborda.
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


Obtiene o establece el modo de ajuste automático del texto. Lectura/escritura [TextAutofitType](../../com.aspose.slides/textautofittype).

--------------------

> ```
> El siguiente código de muestra muestra cómo redimensionar la forma para Ajustar Texto en una presentación de PowerPoint.
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
>  El siguiente código de muestra muestra cómo reducir el texto cuando se desborda.
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


Obtiene o establece el número de columnas en el área de texto. Este valor debe ser un número positivo. De lo contrario, el valor se establecerá en cero. El valor 0 significa valor indefinido. Lectura/escritura int.

--------------------

> ```
> El siguiente código de muestra muestra cómo agregar columna en el marco de texto dentro de una presentación de PowerPoint.
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
>  El siguiente código de muestra muestra cómo reducir el texto cuando se desborda.
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
int
### setColumnCount(int value) {#setColumnCount-int-}
```
public final void setColumnCount(int value)
```


Obtiene o establece el número de columnas en el área de texto. Este valor debe ser un número positivo. De lo contrario, el valor se establecerá en cero. El valor 0 significa valor indefinido. Lectura/escritura int.

--------------------

> ```
> El siguiente código de muestra muestra cómo agregar columna en el marco de texto dentro de una presentación de PowerPoint.
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


Obtiene o establece el espacio entre columnas de texto en el área de texto (en puntos). Esto solo se aplica cuando hay más de una columna presente. Este valor debe ser un número positivo. De lo contrario, el valor se establecerá en cero. Lectura/escritura double.

**Devuelve:**
double
### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public final void setColumnSpacing(double value)
```


Obtiene o establece el espacio entre columnas de texto en el área de texto (en puntos). Esto solo se aplica cuando hay más de una columna presente. Este valor debe ser un número positivo. De lo contrario, el valor se establecerá en cero. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### getRotationAngle() {#getRotationAngle--}
```
public final float getRotationAngle()
```


Especifica la rotación personalizada que se aplica al texto dentro del cuadro delimitador. Si no se especifica, se usa la rotación de la forma acompañante. Si se especifica, se aplica independientemente de la forma. Es decir, la forma puede tener una rotación aplicada además de la rotación del texto. El valor resultante de la rotación visual del texto se resume a partir de esta propiedad y del tipo vertical predefinido en la propiedad TextVerticalType. Lectura/escritura float.

--------------------

> ```
> Considere el caso en que una forma tiene una rotación de 90 grados en sentido horario aplicada. 
>  Además de esto, el propio cuerpo del texto tiene una rotación de -90 grados 
>  en sentido antihorario aplicada a ella. Entonces, la forma resultante parecería
>  estar rotada, pero el texto dentro de ella parecería como si no se hubiera rotado en absoluto.
```

**Devuelve:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public final void setRotationAngle(float value)
```


Especifica la rotación personalizada que se aplica al texto dentro del cuadro delimitador. Si no se especifica, se usa la rotación de la forma acompañante. Si se especifica, se aplica independientemente de la forma. Es decir, la forma puede tener una rotación aplicada además de la rotación del texto. El valor resultante de la rotación visual del texto se resume a partir de esta propiedad y del tipo vertical predefinido en la propiedad TextVerticalType. Lectura/escritura float.

--------------------

> ```
> Considere el caso en que una forma tiene una rotación de 90 grados en sentido horario aplicada. 
>  Además de esto, el propio cuerpo del texto tiene una rotación de -90 grados 
>  en sentido antihorario aplicada a él. Entonces, la forma resultante parecería
>  estar rotada, pero el texto dentro de ella parecería como si no se hubiera rotado en absoluto.
```

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


Obtiene o establece mantener el texto plano incluso si se aplicó un efecto de Rotación 3-D. Lectura/escritura boolean.

**Devuelve:**
boolean
### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public final void setKeepTextFlat(boolean value)
```


Obtiene o establece mantener el texto plano incluso si se aplicó un efecto de Rotación 3-D. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public final ITextFrameFormatEffectiveData getEffective()
```


Obtiene los datos efectivos de formato del marco de texto con la herencia aplicada.

--------------------

> ```
> Este ejemplo muestra cómo obtener algunas de las propiedades efectivas de formato del marco de texto.
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