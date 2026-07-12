---
title: IShape
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Representa una forma en una diapositiva.
type: docs
url: /es/com.aspose.slides/ishape/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IShape extends ISlideComponent, IHyperlinkContainer
```

Representa una forma en una diapositiva.
## Métodos

| Método | Descripción |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | Determina si la forma es TextHolder. |
| [getPlaceholder()](#getPlaceholder--) | Devuelve el marcador de posición para una forma. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | Agrega un nuevo marcador de posición si no existe y establece las propiedades del marcador de posición a una especificada. |
| [removePlaceholder()](#removePlaceholder--) | Define que esta forma no es un marcador de posición. |
| [getCustomData()](#getCustomData--) | Devuelve los datos personalizados de la forma. |
| [getRawFrame()](#getRawFrame--) | Obtiene o establece las propiedades del marco de forma sin procesar. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | Obtiene o establece las propiedades del marco de forma sin procesar. |
| [getFrame()](#getFrame--) | Obtiene o establece las propiedades del marco de forma. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Obtiene o establece las propiedades del marco de forma. |
| [getLineFormat()](#getLineFormat--) | Devuelve el objeto LineFormat que contiene las propiedades de formato de línea para una forma. |
| [getThreeDFormat()](#getThreeDFormat--) | Devuelve el objeto ThreeDFormat que contiene las propiedades de formato de línea para una forma. |
| [getEffectFormat()](#getEffectFormat--) | Devuelve el objeto EffectFormat que contiene los efectos de píxel aplicados a una forma. |
| [getFillFormat()](#getFillFormat--) | Devuelve el objeto FillFormat que contiene las propiedades de formato de relleno para una forma. |
| [getImage()](#getImage--) | Devuelve la miniatura de la forma. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | Devuelve la miniatura de la forma. |
| [getHidden()](#getHidden--) | Determina si la forma está oculta. |
| [setHidden(boolean value)](#setHidden-boolean-) | Determina si la forma está oculta. |
| [getZOrderPosition()](#getZOrderPosition--) | Devuelve la posición de una forma en el orden Z. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | Devuelve el número de puntos de conexión en la forma. |
| [getRotation()](#getRotation--) | Obtiene o establece el número de grados que la forma especificada está rotada alrededor del eje Z. |
| [setRotation(float value)](#setRotation-float-) | Obtiene o establece el número de grados que la forma especificada está rotada alrededor del eje Z. |
| [getX()](#getX--) | Obtiene o establece la coordenada x de la esquina superior izquierda de la forma, medida en puntos. |
| [setX(float value)](#setX-float-) | Obtiene o establece la coordenada x de la esquina superior izquierda de la forma, medida en puntos. |
| [getY()](#getY--) | Obtiene o establece la coordenada y de la esquina superior izquierda de la forma, medida en puntos. |
| [setY(float value)](#setY-float-) | Obtiene o establece la coordenada y de la esquina superior izquierda de la forma, medida en puntos. |
| [getWidth()](#getWidth--) | Obtiene o establece el ancho de la forma, medido en puntos. |
| [setWidth(float value)](#setWidth-float-) | Obtiene o establece el ancho de la forma, medido en puntos. |
| [getHeight()](#getHeight--) | Obtiene o establece la altura de la forma, medida en puntos. |
| [setHeight(float value)](#setHeight-float-) | Obtiene o establece la altura de la forma, medida en puntos. |
| [getAlternativeText()](#getAlternativeText--) | Obtiene o establece el texto alternativo asociado a una forma. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Obtiene o establece el texto alternativo asociado a una forma. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | Obtiene o establece el título del texto alternativo asociado a una forma. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | Obtiene o establece el título del texto alternativo asociado a una forma. |
| [getName()](#getName--) | Obtiene o establece el nombre de una forma. |
| [setName(String value)](#setName-java.lang.String-) | Obtiene o establece el nombre de una forma. |
| [isDecorative()](#isDecorative--) | Obtiene o establece la opción “Marcar como decorativo”. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | Obtiene o establece la opción “Marcar como decorativo”. |
| [getShapeLock()](#getShapeLock--) | Devuelve los bloqueos de la forma. |
| [getUniqueId()](#getUniqueId--) | Devuelve un identificador interno, con alcance de presentación, destinado al uso por complementos u otro código. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | Devuelve un identificador único con alcance de diapositiva que permanece constante durante la vida de la forma y permite que PowerPoint o código interop lo referencie de forma fiable desde cualquier parte del documento. |
| [isGrouped()](#isGrouped--) | Determina si la forma está agrupada. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | La propiedad especifica cómo se mostrará una forma en modo de visualización en blanco y negro. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | La propiedad especifica cómo se mostrará una forma en modo de visualización en blanco y negro. |
| [getParentGroup()](#getParentGroup--) | Devuelve el objeto GroupShape padre si la forma está agrupada. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Guarda el contenido de Shape como archivo SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Guarda el contenido de Shape como archivo SVG. |
| [getBasePlaceholder()](#getBasePlaceholder--) | Devuelve una forma de marcador de posición básica (forma del diseño y/o diapositiva maestra de la cual la forma actual hereda). |

### isTextHolder() {#isTextHolder--}
```
public abstract boolean isTextHolder()
```

Determina si la forma es TextHolder. Solo lectura boolean.

**Devuelve:**
boolean

### getPlaceholder() {#getPlaceholder--}
```
public abstract IPlaceholder getPlaceholder()
```

Devuelve el marcador de posición para una forma. Solo lectura [IPlaceholder](../../com.aspose.slides/iplaceholder).

**Devuelve:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public abstract IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

Agrega un nuevo marcador de posición si no existe y establece las propiedades del marcador de posición a una especificada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | Marcador de posición del que copiar el contenido. |

**Devuelve:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - Nuevo [IPlaceholder](../../com.aspose.slides/iplaceholder).

### removePlaceholder() {#removePlaceholder--}
```
public abstract void removePlaceholder()
```

Define que esta forma no es un marcador de posición.

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Devuelve los datos personalizados de la forma. Solo lectura [ICustomData](../../com.aspose.slides/icustomdata).

**Devuelve:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public abstract IShapeFrame getRawFrame()
```

Obtiene o establece las propiedades del marco de forma sin procesar. Lectura/escritura [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //o
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Ese código puede generar situaciones poco claras. Por lo tanto, se añadieron restricciones para usar valores indefinidos en IShape.getFrame(). Los valores de x, y, width, height, flipH, flipV y rotationAngle deben estar definidos (no Float.NaN ni NullableBool.NotDefined). El código de ejemplo anterior ahora lanza una excepción ArgumentException.
>  //Esto se aplica a estos casos de uso:
>  IShape shape = ...;
>  shape.setFrame(...); // no puede ser indefinido
>  IShapeCollection shapes = ...;
>  // los parámetros x, y, width, height no pueden ser Float.NaN:
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
>  But IShape.RawFrame frame properties can be undefined. This make sense when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // la forma está vinculada al marcador de posición
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // ahora la forma hereda los valores x, y, height, flipH, flipV del marcador de posición y sobrescribe width=100 y rotationAngle=0.
```

**Devuelve:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setRawFrame(IShapeFrame value)
```

Obtiene o establece las propiedades del marco de forma sin procesar. Lectura/escritura [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //o
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Ese código puede generar situaciones poco claras. Por lo tanto, se añadieron restricciones para usar valores indefinidos en IShape.getFrame(). Los valores de x, y, width, height, flipH, flipV y rotationAngle deben estar definidos (no Float.NaN ni NullableBool.NotDefined). El código de ejemplo anterior ahora lanza una excepción ArgumentException.
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
>  But IShape.RawFrame frame properties can be undefined. This make sense when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // la forma está vinculada al marcador de posición
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // ahora la forma hereda los valores x, y, height, flipH, flipV del marcador de posición y sobrescribe width=100 y rotationAngle=0.
```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

Obtiene o establece las propiedades del marco de forma. Lectura/escritura [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

El valor de cada propiedad de la instancia IShapeFrame devuelta no es undefined (no es NaN ni NotDefined). El valor de cada propiedad de la instancia IShapeFrame asignada debe no ser undefined (debe no ser NaN ni NotDefined). Puedes establecer valores undefined para las propiedades de la instancia RawFrame.

**Devuelve:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

Obtiene o establece las propiedades del marco de forma. Lectura/escritura [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

El valor de cada propiedad de la instancia IShapeFrame devuelta no es undefined (no es NaN ni NotDefined). El valor de cada propiedad de la instancia IShapeFrame asignada debe no ser undefined (debe no ser NaN ni NotDefined). Puedes establecer valores undefined para las propiedades de la instancia RawFrame.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

Devuelve el objeto LineFormat que contiene las propiedades de formato de línea para una forma. Solo lectura [ILineFormat](../../com.aspose.slides/ilineformat).

**Devuelve:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

Devuelve el objeto ThreeDFormat que contiene las propiedades de formato de línea para una forma. Solo lectura [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Devuelve:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Devuelve el objeto EffectFormat que contiene los efectos de píxel aplicados a una forma. Solo lectura [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Devuelve:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Devuelve el objeto FillFormat que contiene las propiedades de formato de relleno para una forma. Solo lectura [IFillFormat](../../com.aspose.slides/ifillformat).

**Devuelve:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Devuelve la miniatura de la forma. Se utiliza por defecto el tipo ShapeThumbnailBounds.Shape para los límites de la miniatura de la forma.

**Devuelve:**
[IImage](../../com.aspose.slides/iimage) - Miniatura de la forma.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public abstract IImage getImage(int bounds, float scaleX, float scaleY)
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

### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

Determina si la forma está oculta. Lectura/escritura boolean.

**Devuelve:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

Determina si la forma está oculta. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public abstract int getZOrderPosition()
```

Devuelve la posición de una forma en el orden Z. Shapes[0] devuelve la forma al fondo del orden Z, y Shapes[Shapes.Count - 1] devuelve la forma al frente del orden Z. Solo lectura int.

**Devuelve:**
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public abstract int getConnectionSiteCount()
```

Devuelve el número de puntos de conexión en la forma. Solo lectura int.

**Devuelve:**
int

### getRotation() {#getRotation--}
```
public abstract float getRotation()
```

Obtiene o establece el número de grados que la forma especificada está rotada alrededor del eje Z. Un valor positivo indica rotación en sentido horario; un valor negativo indica rotación en sentido antihorario. Lectura/escritura float.

--------------------

El valor devuelto siempre está definido (no es Float.NaN). El valor asignado debe estar definido (no Float.NaN). Puedes establecer valores undefined para las propiedades de la instancia RawFrame.

**Devuelve:**
float

### setRotation(float value) {#setRotation-float-}
```
public abstract void setRotation(float value)
```

Obtiene o establece el número de grados que la forma especificada está rotada alrededor del eje Z. Un valor positivo indica rotación en sentido horario; un valor negativo indica rotación en sentido antihorario. Lectura/escritura float.

--------------------

El valor devuelto siempre está definido (no es Float.NaN). El valor asignado debe estar definido (no Float.NaN). Puedes establecer valores undefined para las propiedades de la instancia RawFrame.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public abstract float getX()
```

Obtiene o establece la coordenada x de la esquina superior izquierda de la forma, medida en puntos. Lectura/escritura float.

--------------------

El valor devuelto siempre está definido y nunca es Float.NaN. El valor asignado también debe estar definido; asigna Float.NaN solo a propiedades de una instancia RawFrame.

**Devuelve:**
float

### setX(float value) {#setX-float-}
```
public abstract void setX(float value)
```

Obtiene o establece la coordenada x de la esquina superior izquierda de la forma, medida en puntos. Lectura/escritura float.

--------------------

El valor devuelto siempre está definido y nunca es Float.NaN. El valor asignado también debe estar definido; asigna Float.NaN solo a propiedades de una instancia RawFrame.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public abstract float getY()
```

Obtiene o establece la coordenada y de la esquina superior izquierda de la forma, medida en puntos. Lectura/escritura float.

--------------------

El valor devuelto siempre está definido y nunca es Float.NaN. El valor asignado también debe estar definido; asigna Float.NaN solo a propiedades de una instancia RawFrame.

**Devuelve:**
float

### setY(float value) {#setY-float-}
```
public abstract void setY(float value)
```

Obtiene o establece la coordenada y de la esquina superior izquierda de la forma, medida en puntos. Lectura/escritura float.

--------------------

El valor devuelto siempre está definido y nunca es Float.NaN. El valor asignado también debe estar definido; asigna Float.NaN solo a propiedades de una instancia RawFrame.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

Obtiene o establece el ancho de la forma, medido en puntos. Lectura/escritura float.

--------------------

El valor devuelto siempre está definido y nunca es Float.NaN. El valor asignado también debe estar definido; asigna Float.NaN solo a propiedades de una instancia RawFrame.

**Devuelve:**
float

### setWidth(float value) {#setWidth-float-}
```
public abstract void setWidth(float value)
```

Obtiene o establece el ancho de la forma, medido en puntos. Lectura/escritura float.

--------------------

El valor devuelto siempre está definido y nunca es Float.NaN. El valor asignado también debe estar definido; asigna Float.NaN solo a propiedades de una instancia RawFrame.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Obtiene o establece la altura de la forma, medida en puntos. Lectura/escritura float.

--------------------

El valor devuelto siempre está definido y nunca es Float.NaN. El valor asignado también debe estar definido; asigna Float.NaN solo a propiedades de una instancia RawFrame.

**Devuelve:**
float

### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

Obtiene o establece la altura de la forma, medida en puntos. Lectura/escritura float.

--------------------

El valor devuelto siempre está definido y nunca es Float.NaN. El valor asignado también debe estar definido; asigna Float.NaN solo a propiedades de una instancia RawFrame.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getAlternativeText() {#getAlternativeText--}
```
public abstract String getAlternativeText()
```

Obtiene o establece el texto alternativo asociado a una forma. Lectura/escritura String.

**Devuelve:**
java.lang.String

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public abstract void setAlternativeText(String value)
```

Obtiene o establece el texto alternativo asociado a una forma. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public abstract String getAlternativeTextTitle()
```

Obtiene o establece el título del texto alternativo asociado a una forma. Lectura/escritura String.

**Devuelve:**
java.lang.String

### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public abstract void setAlternativeTextTitle(String value)
```

Obtiene o establece el título del texto alternativo asociado a una forma. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public abstract String getName()
```

Obtiene o establece el nombre de una forma. Lectura/escritura String.

**Devuelve:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Obtiene o establece el nombre de una forma. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public abstract boolean isDecorative()
```

Obtiene o establece la opción “Marcar como decorativo”. Lectura/escritura boolean.

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
public abstract void setDecorative(boolean value)
```

Obtiene o establece la opción “Marcar como decorativo”. Lectura/escritura boolean.

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
public abstract IBaseShapeLock getShapeLock()
```

Devuelve los bloqueos de la forma. Solo lectura [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**Devuelve:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)

### getUniqueId() {#getUniqueId--}
```
public abstract long getUniqueId()
```

Devuelve un identificador interno, con alcance de presentación, destinado al uso por complementos u otro código. Debido a que este valor puede ser reasignado por el usuario o programáticamente, no debe tratarse como una clave única persistente. Solo lectura long. Ver también \#getOfficeInteropShapeId.getOfficeInteropShapeId.

**Devuelve:**
long

### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public abstract long getOfficeInteropShapeId()
```

Devuelve un identificador único con alcance de diapositiva que permanece constante durante la vida de la forma y permite que PowerPoint o código interop lo referencie de forma fiable desde cualquier parte del documento. Solo lectura long. Ver también \#getUniqueId.getUniqueId.

**Devuelve:**
long

### isGrouped() {#isGrouped--}
```
public abstract boolean isGrouped()
```

Determina si la forma está agrupada. Solo lectura boolean.

--------------------

La propiedad #getParentGroup.getParentGroup devuelve el objeto GroupShape padre si la forma está agrupada.

**Devuelve:**
boolean

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public abstract byte getBlackWhiteMode()
```

La propiedad especifica cómo se mostrará una forma en modo de visualización en blanco y negro. Lectura/escritura [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Devuelve:**
byte

### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public abstract void setBlackWhiteMode(byte value)
```

La propiedad especifica cómo se mostrará una forma en modo de visualización en blanco y negro. Lectura/escritura [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

Devuelve el objeto GroupShape padre si la forma está agrupada. De lo contrario devuelve null. Solo lectura [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

La propiedad #isGrouped.isGrouped determina si la forma está agrupada.

**Devuelve:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

Guarda el contenido de Shape como archivo SVG.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.OutputStream | Flujo de destino |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Guarda el contenido de Shape como archivo SVG.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.OutputStream | Flujo de destino |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Opciones de generación SVG |

### getBasePlaceholder() {#getBasePlaceholder--}
```
public abstract IShape getBasePlaceholder()
```

Devuelve una forma de marcador de posición básica (forma del diseño y/o diapositiva maestra de la cual la forma actual hereda).

--------------------

> ```
> // obtener todos los efectos animados (master/layout/slide) de la shape del marcador de posición
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

Se devuelve null si la forma actual no es heredada.

**Devuelve:**
[IShape](../../com.aspose.slides/ishape)