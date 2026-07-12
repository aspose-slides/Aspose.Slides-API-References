---
title: IParagraph
second_title: Aspose.Slides para Android mediante la referencia de API de Java
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
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Especifica las propiedades de la porción que se deben usar si se inserta otra porción después de la última. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Especifica las propiedades de la porción que se deben usar si se inserta otra porción después de la última. |
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
public abstract RectF getRect()
```


Obtiene las coordenadas del rectángulo que delimita el párrafo. El rectángulo incluye todas las líneas de texto en el párrafo, incluidas las vacías.

**Devuelve:**
android.graphics.RectF - Rectángulo que delimita el párrafo android.graphics.RectF
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
int - Conteo de líneas en un párrafo
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public abstract IPortionFormat getEndParagraphPortionFormat()
```


Especifica las propiedades de la porción que se deben usar si se inserta otra porción después de la última.

**Devuelve:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setEndParagraphPortionFormat(IPortionFormat value)
```


Especifica las propiedades de la porción que se deben usar si se inserta otra porción después de la última.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |