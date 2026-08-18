---
title: IPortion
second_title: Referencia de la API de Aspose.Slides para Java
description: Representa una porción de texto dentro de un párrafo de texto.
type: docs
url: /es/com.aspose.slides/iportion/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IPortion extends ISlideComponent
```

Representa una porción de texto dentro de un párrafo de texto.
## Métodos

| Método | Descripción |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | Devuelve un objeto de formato que contiene las propiedades de formato establecidas explícitamente de la porción de texto sin aplicar herencia. |
| [getText()](#getText--) | Obtiene o establece el texto plano de una porción. |
| [setText(String value)](#setText-java.lang.String-) | Obtiene o establece el texto plano de una porción. |
| [getField()](#getField--) | Devuelve un campo de esta porción. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | Convierte esta porción en un campo actualizado automáticamente. |
| [addField(String internalString)](#addField-java.lang.String-) | Convierte esta porción en un campo actualizado automáticamente. |
| [removeField()](#removeField--) | Convierte esta porción de campo en una porción simple. |
| [getRect()](#getRect--) | Obtiene las coordenadas del rectángulo que delimita la porción. |
| [getCoordinates()](#getCoordinates--) | Obtiene las coordenadas del inicio de la porción. |
### getPortionFormat() {#getPortionFormat--}
```
public abstract IPortionFormat getPortionFormat()
```

Devuelve un objeto de formato que contiene las propiedades de formato establecidas explícitamente de la porción de texto sin aplicar herencia. Solo lectura [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

El objeto de formato contiene los parámetros de formato definidos solo para la porción actual, no se aplican los datos heredados.

Para obtener los valores efectivos, incluidos los heredados, use el método [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective).

**Devuelve:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public abstract String getText()
```

Obtiene o establece el texto plano de una porción. Lectura/escritura String.

Valor: El texto.

**Devuelve:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Obtiene o establece el texto plano de una porción. Lectura/escritura String.

Valor: El texto.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public abstract IField getField()
```

Devuelve un campo de esta porción. Solo lectura [IField](../../com.aspose.slides/ifield).

**Devuelve:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public abstract void addField(IFieldType fieldType)
```

Convierte esta porción en un campo actualizado automáticamente.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) | Tipo de campo [IFieldType](../../com.aspose.slides/ifieldtype) |

### addField(String internalString) {#addField-java.lang.String-}
```
public abstract void addField(String internalString)
```

Convierte esta porción en un campo actualizado automáticamente.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| internalString | java.lang.String | Nombre interno de FieldTypeEx String |

### removeField() {#removeField--}
```
public abstract void removeField()
```

Convierte esta porción de campo en una porción simple.

### getRect() {#getRect--}
```
public abstract Rectangle2D.Float getRect()
```

Obtiene las coordenadas del rectángulo que delimita la porción. El rectángulo incluye todas las líneas de texto en la porción, incluidas las vacías.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try
>  {
>  	ISlide slide = pres.getSlides().get_Item(0);
>  	IAutoShape shape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 200, 50);
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().clear();
>  	Portion portion0 = new Portion("Some text");
>  	Portion portion1 = new Portion("GetRect text");
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion0);
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion1);
>  	Rectangle2D.Float rect = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(1).getRect();
>  	...
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:**
java.awt.geom.Rectangle2D.Float - Rectángulo que delimita la porción java.awt.geom.Rectangle2D.Float
### getCoordinates() {#getCoordinates--}
```
public abstract Point2D.Float getCoordinates()
```

Obtiene las coordenadas del inicio de la porción. La coordenada X del punto representa el comienzo de la porción desde el primer carácter, incluyendo el margen izquierdo. La coordenada Y incluye el margen superior.

**Devuelve:**
java.awt.geom.Point2D.Float - Coordenadas del inicio de la porción java.awt.geom.Point2D.Float