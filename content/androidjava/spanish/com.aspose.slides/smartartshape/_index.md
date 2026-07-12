---
title: SmartArtShape
second_title: Aspose.Slides para Android a través de la referencia de la API Java
description: Representa la forma SmartArt
type: docs
url: /es/com.aspose.slides/smartartshape/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Todas las interfaces implementadas:**
[com.aspose.slides.ISmartArtShape](../../com.aspose.slides/ismartartshape)
```
public class SmartArtShape extends GeometryShape implements ISmartArtShape
```

Representa la forma SmartArt
## Métodos

| Método | Descripción |
| --- | --- |
| [getShapeType()](#getShapeType--) | Devuelve o establece el tipo predefinido de geometría. |
| [setShapeType(int value)](#setShapeType-int-) | Devuelve o establece el tipo predefinido de geometría. |
| [getTextFrame()](#getTextFrame--) | Devuelve el texto de la forma SmartArt. |
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```


Devuelve o establece el tipo predefinido de geometría. Nota: al cambiar el valor, todos los valores de ajuste se restablecerán a sus valores predeterminados. Lectura/escritura [ShapeType](../../com.aspose.slides/shapetype).

**Devuelve:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```


Devuelve o establece el tipo predefinido de geometría. Nota: al cambiar el valor, todos los valores de ajuste se restablecerán a sus valores predeterminados. Lectura/escritura [ShapeType](../../com.aspose.slides/shapetype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```


Devuelve el texto de la forma SmartArt. Solo lectura [ITextFrame](../../com.aspose.slides/itextframe).

**Devuelve:**
[ITextFrame](../../com.aspose.slides/itextframe)