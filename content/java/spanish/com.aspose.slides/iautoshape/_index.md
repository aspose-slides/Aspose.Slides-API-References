---
title: IAutoShape
second_title: Referencia de la API de Aspose.Slides para Java
description: Representa una AutoShape.
type: docs
url: /es/com.aspose.slides/iautoshape/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IAutoShape extends IGeometryShape
```

Representa una AutoShape.
## Métodos

| Method | Description |
| --- | --- |
| [getAutoShapeLock()](#getAutoShapeLock--) | Returns AutoShape's locks. |
| [getTextFrame()](#getTextFrame--) | Returns TextFrame object for the AutoShape. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Determines whether this autoshape should be filled with slide's background fill instead of specified by style or fill format. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Determines whether this autoshape should be filled with slide's background fill instead of specified by style or fill format. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Adds a new TextFrame to a shape. |
| [isTextBox()](#isTextBox--) | Specifies if the shape is a text box. |
### getAutoShapeLock() {#getAutoShapeLock--}
```
public abstract IAutoShapeLock getAutoShapeLock()
```

Devuelve los bloqueos de AutoShape. Solo lectura [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Devuelve:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

Devuelve el objeto TextFrame para la AutoShape. Solo lectura [ITextFrame](../../com.aspose.slides/itextframe).

**Devuelve:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public abstract boolean getUseBackgroundFill()
```

Determina si este autoshape debe rellenarse con el fondo de la diapositiva en lugar de lo especificado por estilo o formato de relleno. Booleano de lectura/escritura.

**Devuelve:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public abstract void setUseBackgroundFill(boolean value)
```

Determina si este autoshape debe rellenarse con el fondo de la diapositiva en lugar de lo especificado por estilo o formato de relleno. Booleano de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public abstract ITextFrame addTextFrame(String text)
```

Añade un nuevo TextFrame a una forma. Si la forma ya tiene un TextFrame, simplemente cambia su texto.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | java.lang.String | Texto predeterminado para un nuevo TextFrame. |

**Devuelve:**
[ITextFrame](../../com.aspose.slides/itextframe) - Nuevo objeto [ITextFrame](../../com.aspose.slides/itextframe).
### isTextBox() {#isTextBox--}
```
public abstract boolean isTextBox()
```

Especifica si la forma es un cuadro de texto.

--------------------

Si la forma no está especificada como un cuadro de texto no significa que no pueda tener texto adjunto. Un cuadro de texto es simplemente una forma especializada con propiedades específicas.

**Devuelve:**
boolean