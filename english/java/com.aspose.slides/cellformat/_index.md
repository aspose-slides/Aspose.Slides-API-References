---
title: CellFormat
second_title: Aspose.Sildes for Java API Reference
description: p
 Represents format of a table cell.
type: docs
weight: 73
url: /java/com.aspose.slides/cellformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.ICellFormat](../../com.aspose.slides/icellformat)
```
public class CellFormat extends PVIObject implements ICellFormat
```

Represents format of a table cell.
## Methods

| Method | Description |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Returns a cell fill properties object. |
| [getBorderLeft()](#getBorderLeft--) | Returns a left border line properties object. |
| [getBorderTop()](#getBorderTop--) | Returns a top border line properties object. |
| [getBorderRight()](#getBorderRight--) | Returns a right border line properties object. |
| [getBorderBottom()](#getBorderBottom--) | Returns a bottom border line properties object. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Returns a top-left to bottom-right diagonal line properties object. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Returns a bottom-left to top-right diagonal line properties object. |
| [getEffective()](#getEffective--) | Gets effective table cell formatting properties with inheritance and table styles applied. |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


Returns a cell fill properties object. Read-only [IFillFormat](../../com.aspose.slides/ifillformat).

**Returns:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public final ILineFormat getBorderLeft()
```


Returns a left border line properties object. Read-only [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public final ILineFormat getBorderTop()
```


Returns a top border line properties object. Read-only [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public final ILineFormat getBorderRight()
```


Returns a right border line properties object. Read-only [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public final ILineFormat getBorderBottom()
```


Returns a bottom border line properties object. Read-only [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public final ILineFormat getBorderDiagonalDown()
```


Returns a top-left to bottom-right diagonal line properties object. Read-only [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public final ILineFormat getBorderDiagonalUp()
```


Returns a bottom-left to top-right diagonal line properties object. Read-only [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getEffective() {#getEffective--}
```
public final ICellFormatEffectiveData getEffective()
```


Gets effective table cell formatting properties with inheritance and table styles applied.

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

**Returns:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - A [ICellFormatEffectiveData](../com.aspose.slides/icellformateffectivedata).
