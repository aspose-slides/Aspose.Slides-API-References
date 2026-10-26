---
title: ColumnFormat
second_title: Aspose.Slides para Android vía Referencia de API Java
description: Representa el formato de una columna de tabla.
type: docs
url: /es/com.aspose.slides/columnformat/
---
**Herencia:**
java.lang.Object, com.aspose.slides.DomObject

**Todas las interfaces implementadas:**
[com.aspose.slides.IColumnFormat](../../com.aspose.slides/icolumnformat), com.aspose.slides.IPVIObject
```
public final class ColumnFormat extends DomObject<Column> implements IColumnFormat, IPVIObject
```

Representa el formato de una columna de tabla.
## Métodos

| Método | Descripción |
| --- | --- |
| [getEffective()](#getEffective--) | Obtiene las propiedades de formato de columna de tabla efectivas con herencia y estilos de tabla aplicados. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getEffective() {#getEffective--}
```
public final IColumnFormatEffectiveData getEffective()
```

Obtiene las propiedades de formato de columna de tabla efectivas con herencia y estilos de tabla aplicados.

--------------------

> ```
> Este ejemplo muestra cómo obtener el formato de relleno efectivo para diferentes partes lógicas de la tabla.
>  Tenga en cuenta que el formato de celda siempre tiene mayor prioridad que el formato de fila, la fila - mayor que la columna, la columna - mayor que toda la tabla.
>  Así que, finalmente, las propiedades de CellFormatEffectiveData siempre se utilizan para dibujar la tabla. El siguiente código es solo un ejemplo de la API.
>  
  
>  Presentation pres = new Presentation(@"MyPresentation.pptx");
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
[IColumnFormatEffectiveData](../../com.aspose.slides/icolumnformateffectivedata) - un [IColumnFormatEffectiveData](../../com.aspose.slides/icolumnformateffectivedata).
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

Devuelve el padre IPresentationComponent. Solo lectura [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Devuelve:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)