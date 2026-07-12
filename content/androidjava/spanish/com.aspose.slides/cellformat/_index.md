---
title: CellFormat
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Representa el formato de una celda de tabla.
type: docs
url: /es/com.aspose.slides/cellformat/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Todas las interfaces implementadas:**
[com.aspose.slides.ICellFormat](../../com.aspose.slides/icellformat)
```
public final class CellFormat extends PVIObject implements ICellFormat
```

Representa el formato de una celda de tabla.
## Métodos

| Método | Descripción |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillFormat()](#getFillFormat--) | Devuelve un objeto de propiedades de relleno de celda. |
| [getBorderLeft()](#getBorderLeft--) | Devuelve un objeto de propiedades de línea del borde izquierdo. |
| [getBorderTop()](#getBorderTop--) | Devuelve un objeto de propiedades de línea del borde superior. |
| [getBorderRight()](#getBorderRight--) | Devuelve un objeto de propiedades de línea del borde derecho. |
| [getBorderBottom()](#getBorderBottom--) | Devuelve un objeto de propiedades de línea del borde inferior. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Devuelve un objeto de propiedades de línea diagonal de arriba a la izquierda a abajo a la derecha. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Devuelve un objeto de propiedades de línea diagonal de abajo a la izquierda a arriba a la derecha. |
| [getEffective()](#getEffective--) | Obtiene las propiedades de formato de celda de tabla efectivas con herencia y estilos de tabla aplicados. |
| [getTransparency()](#getTransparency--) | Obtiene o establece la transparencia del color de relleno. |
| [setTransparency(float value)](#setTransparency-float-) | Obtiene o establece la transparencia del color de relleno. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Versión. Solo lectura long.

**Devuelve:**
long
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


Devuelve un objeto de propiedades de relleno de celda. Solo lectura [IFillFormat](../../com.aspose.slides/ifillformat).

**Devuelve:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public final ILineFormat getBorderLeft()
```


Devuelve un objeto de propiedades de línea del borde izquierdo. Solo lectura [ILineFormat](../../com.aspose.slides/ilineformat).

**Devuelve:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public final ILineFormat getBorderTop()
```


Devuelve un objeto de propiedades de línea del borde superior. Solo lectura [ILineFormat](../../com.aspose.slides/ilineformat).

**Devuelve:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public final ILineFormat getBorderRight()
```


Devuelve un objeto de propiedades de línea del borde derecho. Solo lectura [ILineFormat](../../com.aspose.slides/ilineformat).

**Devuelve:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public final ILineFormat getBorderBottom()
```


Devuelve un objeto de propiedades de línea del borde inferior. Solo lectura [ILineFormat](../../com.aspose.slides/ilineformat).

**Devuelve:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public final ILineFormat getBorderDiagonalDown()
```


Devuelve un objeto de propiedades de línea diagonal de arriba a la izquierda a abajo a la derecha. Solo lectura [ILineFormat](../../com.aspose.slides/ilineformat).

**Devuelve:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public final ILineFormat getBorderDiagonalUp()
```


Devuelve un objeto de propiedades de línea diagonal de abajo a la izquierda a arriba a la derecha. Solo lectura [ILineFormat](../../com.aspose.slides/ilineformat).

**Devuelve:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getEffective() {#getEffective--}
```
public final ICellFormatEffectiveData getEffective()
```


Obtiene las propiedades de formato de celda de tabla efectivas con herencia y estilos de tabla aplicados.

--------------------

> ```
> This example demonstrates getting effective fill format for different table logic parts.
>  Please note that cell formatting always has higher priority than row formatting, row - higher than column, column - higher that whole table.
>  So finally CellFormatEffectiveData properties always used to draw the table. The following code is just an example of API.
>  
>  Presentation pres = new Presentation(@"MyPresentation.pptx");
>  try
>  {
>      ITable tbl = (ITable) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IFillFormatEffectiveData tableFillFormatEffective = tbl.getTableFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData rowFillFormatEffective = tbl.getRows().get_Item(0).RowFormat.GetEffective().getFillFormat();
>      IFillFormatEffectiveData columnFillFormatEffective = tbl.getColumns().get_Item(0).getColumnFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData cellFillFormatEffective = tbl.get_Item(0, 0).getCellFormat().getEffective().getFillFormat();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - Un [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).
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