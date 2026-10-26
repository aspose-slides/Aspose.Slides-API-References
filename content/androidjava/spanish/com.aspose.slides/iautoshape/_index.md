---
title: IAutoShape
second_title: Aspose.Slides para Android a través de la referencia de API Java
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

| Método | Descripción |
| --- | --- |
| [getAutoShapeLock()](#getAutoShapeLock--) | Devuelve los bloqueos de AutoShape. |
| [getTextFrame()](#getTextFrame--) | Devuelve el objeto TextFrame para la AutoShape. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Determina si este autoshape debe rellenarse con el fondo de la diapositiva en lugar de lo especificado por el estilo o formato de relleno. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Determina si este autoshape debe rellenarse con el fondo de la diapositiva en lugar de lo especificado por el estilo o formato de relleno. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Añade un nuevo TextFrame a una forma. |
| [isTextBox()](#isTextBox--) | Especifica si la forma es un cuadro de texto. |
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


Determina si este autoshape debe rellenarse con el fondo de la diapositiva en lugar de lo especificado por el estilo o formato de relleno. Booleano de lectura/escritura.

**Devuelve:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public abstract void setUseBackgroundFill(boolean value)
```


Determina si este autoshape debe rellenarse con el fondo de la diapositiva en lugar de lo especificado por el estilo o formato de relleno. Booleano de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public abstract ITextFrame addTextFrame(String text)
```


Añade un nuevo TextFrame a una forma. Si la forma ya tiene TextFrame, simplemente cambia su texto.

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