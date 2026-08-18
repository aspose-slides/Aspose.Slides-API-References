---
title: IParagraph
second_title: Referencia de API de Aspose.Slides para Java
description: Representa un párrafo de texto.
type: docs
url: /es/com.aspose.slides/iparagraph/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraph extends ISlideComponent
```

Representa un párrafo de texto.
## Métodos

| Método | Descripción |
| --- | --- |
| [getPortions()](#getPortions--) | Devuelve la colección de porciones de texto. |
| [getParagraphFormat()](#getParagraphFormat--) | Devuelve el objeto de formato para este párrafo. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Une ejecuciones con el mismo formato. |
| [getText()](#getText--) | Obtiene o establece el texto sin formato de un párrafo. |
| [setText(String value)](#setText-java.lang.String-) | Obtiene o establece el texto sin formato de un párrafo. |
| [getRect()](#getRect--) | Obtiene las coordenadas del rectángulo que delimita el párrafo. |
| [getLinesCount()](#getLinesCount--) | Obtiene el número de líneas en un párrafo. |
| [getImage()](#getImage--) | Devuelve una imagen del párrafo. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Devuelve una imagen del párrafo con la escala especificada. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Especifica las propiedades de la porción que se usarán si se inserta otra porción después de la última. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Especifica las propiedades de la porción que se usarán si se inserta otra porción después de la última. |
### getPortions() {#getPortions--}
```
public abstract IPortionCollection getPortions()
```

Devuelve la colección de porciones de texto. Solo lectura [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Devuelve:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IParagraphFormat getParagraphFormat()
```

Devuelve el objeto de formato para este párrafo. Solo lectura [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Devuelve:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Une ejecuciones con el mismo formato.

### getText() {#getText--}
```
public abstract String getText()
```

Obtiene o establece el texto sin formato de un párrafo. Lectura/escritura String.

Valor: El texto.

**Devuelve:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Obtiene o establece el texto sin formato de un párrafo. Lectura/escritura String.

Valor: El texto.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |
### getRect() {#getRect--}
```
public abstract Rectangle2D.Float getRect()
```

Obtiene las coordenadas del rectángulo que delimita el párrafo. El rectángulo incluye todas las líneas de texto del párrafo, incluidas las vacías.

**Devuelve:**
java.awt.geom.Rectangle2D.Float - Rectángulo que delimita el párrafo java.awt.geom.Rectangle2D.Float
### getLinesCount() {#getLinesCount--}
```
public abstract int getLinesCount()
```

Obtiene el número de líneas en un párrafo.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide sld = pres.getSlides().get_Item(0);
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      IParagraph para = ashp.getTextFrame().getParagraphs().get_Item(0);
>      IPortion portion = para.getPortions().get_Item(0);
>      portion.setText("Aspose Paragraph GetLinesCount() Example");
>      System.out.println("Lines Count = " + para.getLinesCount());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:**
int - Recuento de líneas en un párrafo
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Devuelve una imagen del párrafo.

--------------------

> ```
> El siguiente ejemplo muestra cómo renderizar un párrafo como una imagen:
>   
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(
>          ShapeType.Rectangle, 50, 50, 150, 50);
>      IParagraph paragraph = shape.getTextFrame().getParagraphs().get_Item(0);
>      paragraph.setText("Aspose Paragraph GetImage() Example");
>      IImage paragraphImage = paragraph.getImage();
>      try {
>          paragraphImage.save("paragraph.png");
>      } finally {
>          if (paragraphImage != null) paragraphImage.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:**
[IImage](../../com.aspose.slides/iimage) - Una imagen que contiene el párrafo renderizado, o null si el párrafo no se encuentra en su colección principal, no tiene límites de renderizado válidos, o ocurre un error al renderizar la imagen.
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```

Devuelve una imagen del párrafo con la escala especificada.

--------------------

> ```
> The following example shows how to render each text box paragraph on a slide as an image with custom scaling:
>   
>  Presentation pres = new Presentation("sample.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      int shapeIndex = 0;
>      for (IShape shape : slide.getShapes())
>      {
>          shapeIndex++;
>          if (shape instanceof IAutoShape) {
>              IAutoShape autoShape = (IAutoShape)shape;
>              int paragraphIndex = 0;
>              for (IParagraph paragraph : autoShape.getTextFrame().getParagraphs())
>              {
>                  paragraphIndex++;
>                  IImage paragraphImage = paragraph.getImage(2f, 2f);
>                  try {
>                      if (paragraphImage != null)
>                          paragraphImage.save("shape"+shapeIndex+"_paragraph"+paragraphIndex+".png");
> 
>                  } finally {
>                      if (paragraphImage != null) paragraphImage.dispose();
>                  }
>              }
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| scaleX | float | El factor de escala horizontal aplicado a la imagen del párrafo. |
| scaleY | float | El factor de escala vertical aplicado a la imagen del párrafo. |

**Devuelve:**
[IImage](../../com.aspose.slides/iimage) - Una imagen que contiene el párrafo renderizado, o null si el párrafo no se encuentra en su colección principal, no tiene límites de renderizado válidos, o ocurre un error al renderizar la imagen.
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public abstract IPortionFormat getEndParagraphPortionFormat()
```

Especifica las propiedades de la porción que se usarán si se inserta otra porción después de la última.

**Devuelve:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setEndParagraphPortionFormat(IPortionFormat value)
```

Especifica las propiedades de la porción que se usarán si se inserta otra porción después de la última.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |