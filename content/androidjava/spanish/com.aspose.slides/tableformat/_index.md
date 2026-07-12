---
title: TableFormat
second_title: Referencia de API de Aspose.Slides para Android vía Java
description: Representa el formato de una tabla.
type: docs
url: /es/com.aspose.slides/tableformat/
---
**Herencia:**
java.lang.Object, com.aspose.slides.DomObject

**Todas las interfaces implementadas:**
[com.aspose.slides.ITableFormat](../../com.aspose.slides/itableformat), com.aspose.slides.IPVIObject
```
public final class TableFormat extends DomObject<Table> implements ITableFormat, IPVIObject
```

Representa el formato de una tabla.
## Métodos

| Método | Descripción |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Devuelve un objeto de propiedades de relleno de tabla. |
| [getTransparency()](#getTransparency--) | Obtiene o establece la transparencia del color de relleno. |
| [setTransparency(float value)](#setTransparency-float-) | Obtiene o establece la transparencia del color de relleno. |
| [getEffective()](#getEffective--) | Obtiene las propiedades de formato de tabla efectivas con herencia y estilos de tabla aplicados. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Devuelve un objeto de propiedades de relleno de tabla. Solo lectura [IFillFormat](../../com.aspose.slides/ifillformat).

**Devuelve:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```

Obtiene o establece la transparencia del color de relleno. Lectura/escritura  float .

**Devuelve:**
float

### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```

Obtiene o establece la transparencia del color de relleno. Lectura/escritura  float .

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final ITableFormatEffectiveData getEffective()
```

Obtiene las propiedades de formato de tabla efectivas con herencia y estilos de tabla aplicados.

--------------------

> ```
> This example demonstrates getting effective fill format for different table logic parts.
>  Please note that cell formatting always has higher priority than row formatting, row - higher than column, column - higher that whole table.
>  So finally CellFormatEffectiveData properties always used to draw the table. The following code is just an example of API.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      ITable tbl = (Table)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IFillFormatEffectiveData tableFillFormatEffective = tbl.getTableFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData rowFillFormatEffective = tbl.getRows().get_Item(0).getRowFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData columnFillFormatEffective = tbl.getColumns().get_Item(0).getColumnFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData cellFillFormatEffective = tbl.get_Item(0, 0).getCellFormat().getEffective().getFillFormat();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Devuelve:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - Un [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).

### getVersion() {#getVersion--}
```
public final long getVersion()
```

Versión. Solo lectura long.

**Devuelve:**
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Devuelve el IPresentationComponent padre. Solo lectura [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Devuelve:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)