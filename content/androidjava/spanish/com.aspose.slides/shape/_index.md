---
title: Shape
second_title: Referencia de API Java de Aspose.Slides para Android
description: Representa una forma en una diapositiva.
type: docs
url: /es/com.aspose.slides/shape/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IShape](../../com.aspose.slides/ishape), com.aspose.slides.IDOMObject
```
public class Shape implements IShape, IDOMObject
```

Representa una forma en una diapositiva.
## Métodos

| Método | Descripción |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | Determina si la forma es TextHolder\_PPT. |
| [getPlaceholder()](#getPlaceholder--) | Devuelve el marcador de posición para una forma. |
| [removePlaceholder()](#removePlaceholder--) | Define que esta forma no es un marcador de posición. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | Añade un nuevo marcador de posición si no existe y establece las propiedades del marcador de posición a una especificada. |
| [getBasePlaceholder()](#getBasePlaceholder--) | Devuelve una forma de marcador de posición básica (forma del diseño y/o diapositiva maestra de la cual la forma actual hereda). |
| [getCustomData()](#getCustomData--) | Devuelve los datos personalizados de la forma. |
| [getRawFrame()](#getRawFrame--) | Devuelve o establece las propiedades del marco sin procesar de la forma. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | Devuelve o establece las propiedades del marco sin procesar de la forma. |
| [getFrame()](#getFrame--) | Devuelve o establece las propiedades del marco sin procesar de la forma. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Devuelve o establece las propiedades del marco sin procesar de la forma. |
| [getLineFormat()](#getLineFormat--) | Devuelve el objeto LineFormat que contiene las propiedades de formato de línea para una forma. |
| [getThreeDFormat()](#getThreeDFormat--) | Devuelve el objeto ThreeDFormat que contiene las propiedades de efecto 3D para una forma. |
| [getEffectFormat()](#getEffectFormat--) | Devuelve el objeto EffectFormat que contiene los efectos de píxel aplicados a una forma. |
| [getFillFormat()](#getFillFormat--) | Devuelve el objeto FillFormat que contiene las propiedades de formato de relleno para una forma. |
| [getImage()](#getImage--) | Devuelve la miniatura de la forma. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | Devuelve la miniatura de la forma. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Guarda el contenido de Shape como archivo SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Guarda el contenido de Shape como archivo SVG. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Devuelve o establece el hipervínculo definido para el clic del ratón. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | Devuelve o establece el hipervínculo definido para el clic del ratón. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Devuelve o establece el hipervínculo definido para pasar el ratón por encima. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | Devuelve o establece el hipervínculo definido para pasar el ratón por encima. |
| [getHyperlinkManager()](#getHyperlinkManager--) | Devuelve el gestor de hipervínculos. |
| [getHidden()](#getHidden--) | Determina si la forma está oculta. |
| [setHidden(boolean value)](#setHidden-boolean-) | Determina si la forma está oculta. |
| [getZOrderPosition()](#getZOrderPosition--) | Devuelve la posición de una forma en el orden Z. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | Devuelve el número de puntos de conexión en la forma. |
| [getRotation()](#getRotation--) | Devuelve o establece el número de grados que la forma especificada está rotada alrededor del eje Z. |
| [setRotation(float value)](#setRotation-float-) | Devuelve o establece el número de grados que la forma especificada está rotada alrededor del eje Z. |
| [getX()](#getX--) | Obtiene o establece la coordenada x de la esquina superior izquierda de la forma, medida en puntos. |
| [setX(float value)](#setX-float-) | Obtiene o establece la coordenada x de la esquina superior izquierda de la forma, medida en puntos. |
| [getY()](#getY--) | Obtiene o establece la coordenada y de la esquina superior izquierda de la forma, medida en puntos. |
| [setY(float value)](#setY-float-) | Obtiene o establece la coordenada y de la esquina superior izquierda de la forma, medida en puntos. |
| [getWidth()](#getWidth--) | Obtiene o establece el ancho de la forma, medido en puntos. |
| [setWidth(float value)](#setWidth-float-) | Obtiene o establece el ancho de la forma, medido en puntos. |
| [getHeight()](#getHeight--) | Obtiene o establece la altura de la forma, medida en puntos. |
| [setHeight(float value)](#setHeight-float-) | Obtiene o establece la altura de la forma, medida en puntos. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | La propiedad especifica cómo se renderizará una forma en modo de visualización en blanco y negro. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | La propiedad especifica cómo se renderizará una forma en modo de visualización en blanco y negro. |
| [getUniqueId()](#getUniqueId--) | Devuelve un identificador interno, con alcance de presentación, destinado a ser usado por complementos u otro código. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | Devuelve un identificador único con alcance de diapositiva que permanece constante durante la vida útil de la forma y permite que PowerPoint o código de interoperabilidad referencien la forma de manera fiable desde cualquier parte del documento. |
| [getAlternativeText()](#getAlternativeText--) | Devuelve o establece el texto alternativo asociado a una forma. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Devuelve o establece el texto alternativo asociado a una forma. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | Devuelve o establece el título del texto alternativo asociado a una forma. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | Devuelve o establece el título del texto alternativo asociado a una forma. |
| [getName()](#getName--) | Devuelve o establece el nombre de una forma. |
| [setName(String value)](#setName-java.lang.String-) | Devuelve o establece el nombre de una forma. |
| [isDecorative()](#isDecorative--) | Obtiene o establece la opción 'Marcar como decorativa' Lectura/escritura boolean. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | Obtiene o establece la opción 'Marcar como decorativa' Lectura/escritura boolean. |
| [getShapeLock()](#getShapeLock--) | Devuelve los bloqueos de la forma. |
| [isGrouped()](#isGrouped--) | Determina si la forma está agrupada. |
| [getParentGroup()](#getParentGroup--) | Devuelve el objeto GroupShape padre si la forma está agrupada. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVisualBounds()](#getVisualBounds--) | Obtiene los límites visuales de la forma calculados a partir de su contenido renderizado. |
| [getSlide()](#getSlide--) | Devuelve la diapositiva padre de una forma. |
| [getPresentation()](#getPresentation--) | Devuelve la presentación padre de una diapositiva. |

### isTextHolder() {#isTextHolder--}
```
public final boolean isTextHolder()
```

Determina si la forma es TextHolder\_PPT. **Solo lectura** boolean.

**Devuelve:**
boolean

### getPlaceholder() {#getPlaceholder--}
```
public final IPlaceholder getPlaceholder()
```

Devuelve el marcador de posición para una forma. Devuelve null si la forma no tiene marcador de posición. **Solo lectura** [IPlaceholder](../../com.aspose.slides/iplaceholder).

--------------------

> ```
> The following example shows how to change Text in Placeholder.
>  
>  // Instancia una clase Presentation
>  Presentation pres = new Presentation("ReplacingText.pptx");
>  try {
>      // Accede a la primera diapositiva
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Recorre las formas para encontrar el marcador de posición
>      for (IShape shp : sld.getShapes())
>          if (shp.getPlaceholder() != null)
>          {
>              // Cambia el texto en cada marcador de posición
>              ((IAutoShape)shp).getTextFrame().setText("This is a Placeholder");
>          }
>      // Guarda la presentación en disco
>      pres.save("output_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set Prompt Text in Placeholder.
>  
>  Presentation pres = new Presentation("Presentation2.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      for (IShape shape : slide.getSlide().getShapes()) // Recorre la diapositiva
>      {
>          if (shape.getPlaceholder() != null && shape instanceof AutoShape)
>          {
>              String text = "";
>              if (shape.getPlaceholder().getType() == PlaceholderType.CenteredTitle) // PowerPoint muestra "Click to add title"
>              {
>                  text = "Add Title";
>              }
>              else if (shape.getPlaceholder().getType() == PlaceholderType.Subtitle) // Añade subtítulo
>              {
>                  text = "Add Subtitle";
>              }
>              ((IAutoShape)shape).getTextFrame().setText(text);
>              System.out.println("Placeholder with text: " + text);
>          }
>      }
>      pres.save("Placeholders_PromptText.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Devuelve:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### removePlaceholder() {#removePlaceholder--}
```
public final void removePlaceholder()
```

Define que esta forma no es un marcador de posición.

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public final IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

Añade un nuevo marcador de posición si no existe y establece las propiedades del marcador de posición a uno especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | Marcador de posición del cual copiar el contenido. |

**Devuelve:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - Nuevo #getPlaceholder.getPlaceholder.

### getBasePlaceholder() {#getBasePlaceholder--}
```
public final IShape getBasePlaceholder()
```

Devuelve una forma de marcador de posición básica (forma del diseño y/o diapositiva maestra de la cual la forma actual hereda).

--------------------

> ```
> // obtener todos los efectos animados (master/layout/slide) del shape placeholder
>  Presentation pres = new Presentation("sample.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IShape shape = slide.getShapes().get_Item(0);
>      IEffect[] shapeEffects = slide.getTimeline().getMainSequence().getEffectsByShape(shape);
>      IShape layoutShape = shape.getBasePlaceholder();
>      IEffect[] layoutShapeEffects = slide.getLayoutSlide().getTimeline().getMainSequence().getEffectsByShape(layoutShape);
>      IShape masterShape = layoutShape.getBasePlaceholder();
>      IEffect[] masterShapeEffects = slide.getLayoutSlide().getMasterSlide().getTimeline().getMainSequence().getEffectsByShape(masterShape);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Se devuelve null si la forma actual no hereda.

**Devuelve:**
[IShape](../../com.aspose.slides/ishape)

### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

Devuelve los datos personalizados de la forma. **Solo lectura** [ICustomData](../../com.aspose.slides/icustomdata).

**Devuelve:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public final IShapeFrame getRawFrame()
```

Devuelve o establece las propiedades del marco sin procesar de la forma. **Lectura/escritura** [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //o
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Ese código puede conducir a situaciones poco claras. Por lo tanto, se añadieron restricciones para usar valores indefinidos en IShape.getFrame(). Los valores de x, y, width, height, flipH, flipV y rotationAngle deben estar definidos (no Float.NaN ni NullableBool.NotDefined). El código de ejemplo anterior ahora lanza una excepción ArgumentException.
>  //Esto se aplica a estos casos de uso:
>  IShape shape = ...;
>  shape.setFrame(...); // no puede ser indefinido
>  IShapeCollection shapes = ...;
>  // Los parámetros x, y, width, height no pueden ser Float.NaN:
>  {
>      shapes.addAudioFrameCD(...);
>      shapes.addAudioFrameEmbedded(...);
>      shapes.addAudioFrameLinked(...);
>      shapes.addAutoShape(...);
>      shapes.addChart(...);
>      shapes.addConnector(...);
>      shapes.addOleObjectFrame(...);
>      shapes.addPictureFrame(...);
>      shapes.addSmartArt(...);
>      shapes.addTable(...);
>      shapes.addVideoFrame(...);
>      shapes.insertAudioFrameEmbedded(...);
>      shapes.insertAudioFrameLinked(...);
>      shapes.insertAutoShape(...);
>      shapes.insertChart(...);
>      shapes.insertConnector(...);
>      shapes.insertOleObjectFrame(...);
>      shapes.insertPictureFrame(...);
>      shapes.insertTable(...);
>      shapes.insertVideoFrame(...);
>  }
>  // Pero las propiedades del marco IShape.RawFrame pueden ser indefinidas. Esto tiene sentido cuando la forma está vinculada a un marcador de posición. Entonces los valores indefinidos del marco de la forma se sobrescriben con los del marcador de posición padre. Si no hay una forma de marcador de posición padre para esa forma, entonces esa forma usa valores predeterminados al evaluar el marco efectivo basado en su IShape.RawFrame. Los valores predeterminados son 0 y NullableBool.False para x, y, width, height, flipH, flipV y rotationAngle. Por ejemplo:
>  IShape shape = ...; // la forma está vinculada al marcador de posición
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // ahora la forma hereda los valores x, y, height, flipH, flipV del marcador de posición y sobrescribe width=100 y rotationAngle=0.{code}
> ```


**Devuelve:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public final void setRawFrame(IShapeFrame value)
```

Devuelve o establece las propiedades del marco sin procesar de la forma. **Lectura/escritura** [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //o
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Ese código puede conducir a situaciones poco claras. Por lo tanto, se añadieron restricciones para usar valores indefinidos en IShape.getFrame(). Los valores de x, y, width, height, flipH, flipV y rotationAngle deben estar definidos (no Float.NaN ni NullableBool.NotDefined). El código de ejemplo anterior ahora lanza una excepción ArgumentException.
>  //Esto se aplica a estos casos de uso:
>  IShape shape = ...;
>  shape.setFrame(...); // no puede ser indefinido
>  IShapeCollection shapes = ...;
>  // Los parámetros x, y, width, height no pueden ser Float.NaN:
>  {
>      shapes.addAudioFrameCD(...);
>      shapes.addAudioFrameEmbedded(...);
>      shapes.addAudioFrameLinked(...);
>      shapes.addAutoShape(...);
>      shapes.addChart(...);
>      shapes.addConnector(...);
>      shapes.addOleObjectFrame(...);
>      shapes.addPictureFrame(...);
>      shapes.addSmartArt(...);
>      shapes.addTable(...);
>      shapes.addVideoFrame(...);
>      shapes.insertAudioFrameEmbedded(...);
>      shapes.insertAudioFrameLinked(...);
>      shapes.insertAutoShape(...);
>      shapes.insertChart(...);
>      shapes.insertConnector(...);
>      shapes.insertOleObjectFrame(...);
>      shapes.insertPictureFrame(...);
>      shapes.insertTable(...);
>      shapes.insertVideoFrame(...);
>  }
>  //Pero las propiedades del marco IShape.RawFrame pueden ser indefinidas. Esto tiene sentido cuando la forma está vinculada a un marcador de posición. Entonces los valores indefinidos del marco de la forma se sobrescriben con los del marcador de posición padre. Si no existe un marcador de posición padre para esa forma, entonces esa forma usa valores predeterminados al evaluar el marco efectivo basado en su IShape.RawFrame. Los valores predeterminados son 0 y NullableBool.False para x, y, width, height, flipH, flipV y rotationAngle. Por ejemplo:
>  IShape shape = ...; // la forma está vinculada a un marcador de posición
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // ahora la forma hereda los valores x, y, height, flipH, flipV del marcador de posición y sobrescribe width=100 y rotationAngle=0.{code}
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

Devuelve o establece las propiedades del marco de la forma. **Lectura/escritura** [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

El valor de cada propiedad de la instancia IShapeFrame devuelta no es undefined (no es NaN ni NotDefined). El valor de cada propiedad de la instancia IShapeFrame asignada debe no ser undefined (no debe ser NaN ni NotDefined). Puede establecer valores undefined para las propiedades de la instancia RawFrame.

**Devuelve:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

Devuelve o establece las propiedades del marco de la forma. **Lectura/escritura** [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

El valor de cada propiedad de la instancia IShapeFrame devuelta no es undefined (no es NaN ni NotDefined). El valor de cada propiedad de la instancia IShapeFrame asignada debe no ser undefined (no debe ser NaN ni NotDefined). Puede establecer valores undefined para las propiedades de la instancia RawFrame.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

Devuelve el objeto LineFormat que contiene las propiedades de formato de línea para una forma. Nota: puede devolver null para ciertos tipos de formas que no tienen propiedades de línea. **Solo lectura** [ILineFormat](../../com.aspose.slides/ilineformat).

**Devuelve:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public IThreeDFormat getThreeDFormat()
```

Devuelve el objeto ThreeDFormat que contiene las propiedades de efecto 3D para una forma. Nota: puede devolver null para ciertos tipos de formas que no tienen propiedades 3D. **Solo lectura** [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Devuelve:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public IEffectFormat getEffectFormat()
```

Devuelve el objeto EffectFormat que contiene los efectos de píxel aplicados a una forma. Nota: puede devolver null para ciertos tipos de formas que no tienen propiedades de efecto. **Solo lectura** [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Devuelve:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

Devuelve el objeto FillFormat que contiene las propiedades de formato de relleno para una forma. Nota: puede devolver null para ciertos tipos de formas que no tienen propiedades de relleno. **Solo lectura** [IFillFormat](../../com.aspose.slides/ifillformat).

--------------------

> ```
> The following example shows how to change the accent color for a theme of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
>      shape.getFillFormat().setFillType(FillType.Solid);
>      shape.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example demonstrates how to obtain palette colors from the main theme color and then used in shapes.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Accent 4
>      IShape shape1 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 50, 50);
>      shape1.getFillFormat().setFillType(FillType.Solid);
>      shape1.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      // Accent 4, Lighter 80%
>      IShape shape2 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 70, 50, 50);
>      shape2.getFillFormat().setFillType(FillType.Solid);
>      shape2.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.2f);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.8f);
>      // Accent 4, Lighter 60%
>      IShape shape3 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 130, 50, 50);
>      shape3.getFillFormat().setFillType(FillType.Solid);
>      shape3.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.4f);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.6f);
>      // Accent 4, Lighter 40%
>      IShape shape4 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 190, 50, 50);
>      shape4.getFillFormat().setFillType(FillType.Solid);
>      shape4.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.6f);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.4f);
>      // Accent 4, Darker 25%
>      IShape shape5 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 250, 50, 50);
>      shape5.getFillFormat().setFillType(FillType.Solid);
>      shape5.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape5.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.75f);
>      // Accent 4, Darker 50%
>      IShape shape6 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 310, 50, 50);
>      shape6.getFillFormat().setFillType(FillType.Solid);
>      shape6.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape6.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.5f);
>      pres.save("example_accent4.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public final IImage getImage()
```

Devuelve la miniatura de la forma. ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default.

**Devuelve:**
[IImage](../../com.aspose.slides/iimage) - Miniatura de la forma.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public final IImage getImage(int bounds, float scaleX, float scaleY)
```

Devuelve la miniatura de la forma.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bounds | int | Tipo de límites de la miniatura de la forma. |
| scaleX | float | Escala X |
| scaleY | float | Escala Y |

**Devuelve:**
[IImage](../../com.aspose.slides/iimage) - Miniatura de la forma o null en caso de que se use ShapeThumbnailBounds.Appearance y la forma no tenga elementos visibles.

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

Guarda el contenido de Shape como archivo SVG.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.OutputStream | Flujo de destino |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Guarda el contenido de Shape como archivo SVG.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.OutputStream | Flujo de destino |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Opciones de generación SVG |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

Devuelve o establece el hipervínculo definido para el clic del ratón. **Lectura/escritura** [IHyperlink](../../com.aspose.slides/ihyperlink).

**Devuelve:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

Devuelve o establece el hipervínculo definido para el clic del ratón. **Lectura/escritura** [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

Devuelve o establece el hipervínculo definido para pasar el ratón por encima. **Lectura/escritura** [IHyperlink](../../com.aspose.slides/ihyperlink).

**Devuelve:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

Devuelve o establece el hipervínculo definido para pasar el ratón por encima. **Lectura/escritura** [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

Devuelve el gestor de hipervínculos. **Solo lectura** [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**Devuelve:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

Determina si la forma está oculta. **Lectura/escritura** boolean.

**Devuelve:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

Determina si la forma está oculta. **Lectura/escritura** boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public int getZOrderPosition()
```

Devuelve la posición de una forma en el orden Z. Shapes[0] devuelve la forma más atrás del orden Z, y Shapes[Shapes.Count - 1] devuelve la forma más al frente del orden Z. **Solo lectura** int.

**Devuelve:**
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public final int getConnectionSiteCount()
```

Devuelve el número de puntos de conexión en la forma. **Solo lectura** int.

**Devuelve:**
int

### getRotation() {#getRotation--}
```
public final float getRotation()
```

Devuelve o establece el número de grados que la forma especificada está rotada alrededor del eje Z. Un valor positivo indica rotación en sentido horario; un valor negativo indica rotación en sentido antihorario. **Lectura/escritura** float.

--------------------

El valor devuelto siempre está definido (no es Float.NaN). El valor asignado debe estar definido (no Float.NaN). Puede establecer valores undefined para las propiedades de la instancia RawFrame.

**Devuelve:**
float

### setRotation(float value) {#setRotation-float-}
```
public final void setRotation(float value)
```

Devuelve o establece el número de grados que la forma especificada está rotada alrededor del eje Z. Un valor positivo indica rotación en sentido horario; un valor negativo indica rotación en sentido antihorario. **Lectura/escritura** float.

--------------------

El valor devuelto siempre está definido (no es Float.NaN). El valor asignado debe estar definido (no Float.NaN). Puede establecer valores undefined para las propiedades de la instancia RawFrame.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public final float getX()
```

Obtiene o establece la coordenada x de la esquina superior izquierda de la forma, medida en puntos. **Lectura/escritura** float.

--------------------

El valor devuelto siempre está definido y nunca es Float.NaN. El valor asignado también debe estar definido; asigne Float.NaN solo a propiedades de una instancia RawFrame.

**Devuelve:**
float

### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Obtiene o establece la coordenada x de la esquina superior izquierda de la forma, medida en puntos. **Lectura/escritura** float.

--------------------

El valor devuelto siempre está definido y nunca es Float.NaN. El valor asignado también debe estar definido; asigne Float.NaN solo a propiedades de una instancia RawFrame.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

Obtiene o establece la coordenada y de la esquina superior izquierda de la forma, medida en puntos. **Lectura/escritura** float.

--------------------

El valor devuelto siempre está definido y nunca es Float.NaN. El valor asignado también debe estar definido; asigne Float.NaN solo a propiedades de una instancia RawFrame.

**Devuelve:**
float

### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Obtiene o establece la coordenada y de la esquina superior izquierda de la forma, medida en puntos. **Lectura/escritura** float.

--------------------

El valor devuelto siempre está definido y nunca es Float.NaN. El valor asignado también debe estar definido; asigne Float.NaN solo a propiedades de una instancia RawFrame.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

Obtiene o establece el ancho de la forma, medido en puntos. **Lectura/escritura** float.

--------------------

El valor devuelto siempre está definido y nunca es Float.NaN. El valor asignado también debe estar definido; asigne Float.NaN solo a propiedades de una instancia RawFrame.

**Devuelve:**
float

### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Obtiene o establece el ancho de la forma, medido en puntos. **Lectura/escritura** float.

--------------------

El valor devuelto siempre está definido y nunca es Float.NaN. El valor asignado también debe estar definido; asigne Float.NaN solo a propiedades de una instancia RawFrame.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

Obtiene o establece la altura de la forma, medida en puntos. **Lectura/escritura** float.

--------------------

El valor devuelto siempre está definido y nunca es Float.NaN. El valor asignado también debe estar definido; asigne Float.NaN solo a propiedades de una instancia RawFrame.

**Devuelve:**
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Obtiene o establece la altura de la forma, medida en puntos. **Lectura/escritura** float.

--------------------

El valor devuelto siempre está definido y nunca es Float.NaN. El valor asignado también debe estar definido; asigne Float.NaN solo a propiedades de una instancia RawFrame.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public final byte getBlackWhiteMode()
```

La propiedad especifica cómo se renderizará una forma en modo de visualización en blanco y negro. **Lectura/escritura** [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Devuelve:**
byte

### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public final void setBlackWhiteMode(byte value)
```

La propiedad especifica cómo se renderizará una forma en modo de visualización en blanco y negro. **Lectura/escritura** [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getUniqueId() {#getUniqueId--}
```
public final long getUniqueId()
```

Devuelve un identificador interno, con alcance de presentación, destinado a ser usado por complementos u otro código. Debido a que este valor puede ser reasignado por el usuario o programáticamente, no debe ser tratado como una clave única persistente. **Solo lectura** long. Véase también #getOfficeInteropShapeId.getOfficeInteropShapeId.

**Devuelve:**
long

### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public final long getOfficeInteropShapeId()
```

Devuelve un identificador único con alcance de diapositiva que permanece constante durante la vida útil de la forma y permite que PowerPoint o código de interoperabilidad referencien la forma de manera fiable desde cualquier parte del documento. **Solo lectura** long. Véase también #getUniqueId.getUniqueId.

**Devuelve:**
long

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```

Devuelve o establece el texto alternativo asociado a una forma. **Lectura/escritura** String.

**Devuelve:**
java.lang.String

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```

Devuelve o establece el texto alternativo asociado a una forma. **Lectura/escritura** String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public final String getAlternativeTextTitle()
```

Devuelve o establece el título del texto alternativo asociado a una forma. **Lectura/escritura** String.

**Devuelve:**
java.lang.String

### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public final void setAlternativeTextTitle(String value)
```

Devuelve o establece el título del texto alternativo asociado a una forma. **Lectura/escritura** String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public final String getName()
```

Devuelve o establece el nombre de una forma. No debe ser nulo. Use una cadena vacía si es necesario. **Lectura/escritura** String.

**Devuelve:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Devuelve o establece el nombre de una forma. No debe ser nulo. Use una cadena vacía si es necesario. **Lectura/escritura** String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public final boolean isDecorative()
```

Obtiene o establece la opción 'Marcar como decorativa' Lectura/escritura boolean.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:**
boolean

### setDecorative(boolean value) {#setDecorative-boolean-}
```
public final void setDecorative(boolean value)
```

Obtiene o establece la opción 'Marcar como decorativa' Lectura/escritura boolean.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getShapeLock() {#getShapeLock--}
```
public IBaseShapeLock getShapeLock()
```

Devuelve los bloqueos de la forma. **Solo lectura** [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**Devuelve:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)

### isGrouped() {#isGrouped--}
```
public final boolean isGrouped()
```

Determina si la forma está agrupada. **Solo lectura** boolean.

--------------------

La propiedad #getParentGroup.getParentGroup devuelve el objeto GroupShape padre si la forma está agrupada.

**Devuelve:**
boolean

### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

Devuelve el objeto GroupShape padre si la forma está agrupada. De lo contrario devuelve null. **Solo lectura** [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

La propiedad #isGrouped.isGrouped determina si la forma está agrupada.

**Devuelve:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Devuelve el objeto Parent_Immediate. **Solo lectura** IDOMObject.

**Devuelve:**
com.aspose.slides.IDOMObject

### getVisualBounds() {#getVisualBounds--}
```
public final RectF getVisualBounds()
```

Obtiene los límites visuales de la forma calculados a partir de su contenido renderizado.

**Devuelve:**
android.graphics.RectF - Un android.graphics.RectF que representa los límites visuales de la forma en coordenadas de diapositiva.

--------------------

El rectángulo devuelto representa los límites alineados al eje de todo el contenido producido por la forma durante la renderización en el espacio de coordenadas de la diapositiva. Estos límites pueden diferir de los límites del modelo de la forma #getX.getX/#setX(float).setX(float), #getY.getY/#setY(float).setY(float), #getWidth.getWidth/#setWidth(float).setWidth(float), #getHeight.getHeight/#setHeight(float).setHeight(float) y pueden contener coordenadas negativas si el contenido renderizado se extiende más allá del origen de la diapositiva. Los límites visuales tienen en cuenta aspectos relacionados con la renderización como transformaciones (por ejemplo, rotación), ancho y uniones de trazo, disposición y desbordamiento de texto, geometría de SmartArt y otros efectos de diseño que influyen en la apariencia final renderizada de la forma. Los límites devueltos no están recortados al rectángulo de la diapositiva.

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Devuelve la diapositiva padre de una forma. **Solo lectura** [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Devuelve:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Devuelve la presentación padre de una diapositiva. **Solo lectura** [IPresentation](../../com.aspose.slides/ipresentation).

**Devuelve:**
[IPresentation](../../com.aspose.slides/ipresentation)