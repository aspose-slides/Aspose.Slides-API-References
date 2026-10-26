---
title: RowFormat
second_title: Referencia de la API de Aspose.Slides para Java
description: Representa el formato de una fila de tabla.
type: docs
url: /es/com.aspose.slides/rowformat/
---
**Herencia:**
java.lang.Object, com.aspose.slides.DomObject

**Todas las interfaces implementadas:**
[com.aspose.slides.IRowFormat](../../com.aspose.slides/irowformat), com.aspose.slides.IPVIObject
```
public final class RowFormat extends DomObject<Row> implements IRowFormat, IPVIObject
```

Representa el formato de una fila de tabla.
## Métodos

| Método | Descripción |
| --- | --- |
| [getEffective()](#getEffective--) | Obtiene las propiedades de formato de fila de tabla efectivas con herencia y estilos de tabla aplicados. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getEffective() {#getEffective--}
```
public final IRowFormatEffectiveData getEffective()
```


Obtiene las propiedades de formato de fila de tabla efectivas con herencia y estilos de tabla aplicados.

--------------------

> ```
> Este ejemplo muestra cómo obtener el formato de relleno efectivo para diferentes partes lógicas de la tabla.
>  Tenga en cuenta que el formato de celda siempre tiene mayor prioridad que el formato de fila, la fila - mayor que la columna, la columna - mayor que toda la tabla.
>  Por lo tanto, finalmente siempre se utilizan las propiedades de CellFormatEffectiveData para dibujar la tabla. El siguiente código es solo un ejemplo de la API.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      ITable tbl = (ITable)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IFillFormatEffectiveData tableFillFormatEffective = tbl.getTableFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData rowFillFormatEffective = tbl.getRows().get_Item(0).getRowFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData columnFillFormatEffective = tbl.getColumns().get_Item(0).getColumnFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData cellFillFormatEffective = tbl.get_Item(0, 0).getCellFormat().getEffective().getFillFormat();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:**
[IRowFormatEffectiveData](../../com.aspose.slides/irowformateffectivedata) - Un [IRowFormatEffectiveData](../../com.aspose.slides/irowformateffectivedata).
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Versión. Sólo lectura long.

**Devuelve:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


Devuelve el IPresentationComponent padre. Sólo lectura [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Devuelve:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)