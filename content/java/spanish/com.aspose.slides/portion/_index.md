---
title: Portion
second_title: Referencia de la API de Aspose.Slides para Java
description: Representa una porción de texto dentro de un párrafo de texto.
type: docs
url: /es/com.aspose.slides/portion/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IPortion](../../com.aspose.slides/iportion), com.aspose.slides.IDOMObject
```
public class Portion implements IPortion, IDOMObject
```

Representa una porción de texto dentro de un párrafo de texto.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Portion()](#Portion--) | Inicializa una nueva instancia de la clase Portion. |
| [Portion(String str)](#Portion-java.lang.String-) | Inicializa una nueva instancia de la clase Portion. |
| [Portion(Portion portion)](#Portion-com.aspose.slides.Portion-) | Inicializa una nueva instancia de la clase Portion. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | Devuelve un objeto de formato que contiene las propiedades de formato establecidas explícitamente de la porción de texto sin aplicar herencia. |
| [getText()](#getText--) | Obtiene o establece el texto sin formato de una porción. |
| [setText(String value)](#setText-java.lang.String-) | Obtiene o establece el texto sin formato de una porción. |
| [getField()](#getField--) | Devuelve un campo de esta porción. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | Convierte esta porción en el campo actualizado automáticamente. |
| [addField(String internalString)](#addField-java.lang.String-) | Convierte esta porción en el campo actualizado automáticamente. |
| [removeField()](#removeField--) | Convierte esta porción de campo en una porción simple. |
| [getRect()](#getRect--) | Obtiene las coordenadas del rectángulo que delimita la porción. |
| [getCoordinates()](#getCoordinates--) | Obtiene las coordenadas del inicio de la porción. |
| [getSlide()](#getSlide--) | Devuelve la diapositiva padre del texto. |
| [getPresentation()](#getPresentation--) | Devuelve la presentación padre del texto. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Portion() {#Portion--}
```
public Portion()
```

Inicializa una nueva instancia de la clase Portion.

### Portion(String str) {#Portion-java.lang.String-}
```
public Portion(String str)
```

Inicializa una nueva instancia de la clase Portion.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | java.lang.String |  |

### Portion(Portion portion) {#Portion-com.aspose.slides.Portion-}
```
public Portion(Portion portion)
```

Inicializa una nueva instancia de la clase Portion.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) |  |

### getPortionFormat() {#getPortionFormat--}
```
public final IPortionFormat getPortionFormat()
```

Devuelve un objeto de formato que contiene las propiedades de formato establecidas explícitamente de la porción de texto sin aplicar herencia. Solo lectura [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

El objeto de formato contiene los parámetros de formato definidos solo para la porción actual; los datos heredados no se aplican.

Para obtener los valores efectivos, incluidos los heredados, utilice el método [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective).

**Devuelve:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public final String getText()
```

Obtiene o establece el texto sin formato de una porción. Lectura/escritura String.

Valor: El texto.

**Devuelve:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Obtiene o establece el texto sin formato de una porción. Lectura/escritura String.

Valor: El texto.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public final IField getField()
```

Devuelve un campo de esta porción. Solo lectura [IField](../../com.aspose.slides/ifield).

**Devuelve:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public final void addField(IFieldType fieldType)
```

Convierte esta porción en el campo actualizado automáticamente.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) |  |

### addField(String internalString) {#addField-java.lang.String-}
```
public final void addField(String internalString)
```

Convierte esta porción en el campo actualizado automáticamente.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| internalString | java.lang.String | Nombre interno de FieldType. |

### removeField() {#removeField--}
```
public final void removeField()
```

Convierte esta porción de campo en una porción simple.

### getRect() {#getRect--}
```
public final Rectangle2D.Float getRect()
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
java.awt.geom.Rectangle2D.Float
### getCoordinates() {#getCoordinates--}
```
public final Point2D.Float getCoordinates()
```

Obtiene las coordenadas del inicio de la porción. La coordenada X del punto representa el comienzo de la porción desde el primer carácter, incluyendo el margen izquierdo. La coordenada Y incluye el margen superior.

**Devuelve:**
java.awt.geom.Point2D.Float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Devuelve la diapositiva padre del texto. Solo lectura [BaseSlide](../../com.aspose.slides/baseslide).

**Devuelve:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Devuelve la presentación padre del texto. Solo lectura [IPresentation](../../com.aspose.slides/ipresentation).

**Devuelve:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Devuelve el objeto Parent_Immediate. Solo lectura IDOMObject.

**Devuelve:**
com.aspose.slides.IDOMObject