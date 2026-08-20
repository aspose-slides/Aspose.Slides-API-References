---
title: ChartDataWorkbook
second_title: Tham chiếu API Aspose.Slides cho Java
description: Cung cấp quyền truy cập vào workbook Excel được nhúng
type: docs
url: /vi/com.aspose.slides/chartdataworkbook/
---
**Kế thừa:**
java.lang.Object, com.aspose.slides.DomObject

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
```
public class ChartDataWorkbook extends DomObject<ChartData> implements IChartDataWorkbook
```

Cung cấp quyền truy cập vào workbook Excel được nhúng
## Phương thức

| Method | Description |
| --- | --- |
| [getWorksheets()](#getWorksheets--) | Lấy một bộ sưu tập các worksheets. |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | Lấy tập hợp các cells. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Lấy cell có thể được sử dụng cho chart series hoặc categories |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Lấy cell có thể được sử dụng cho chart series hoặc categories |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Lấy cell có thể được sử dụng cho chart series hoặc categories |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | Lấy cell có thể được sử dụng cho chart series hoặc categories |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | Lấy cell có thể được sử dụng cho chart series hoặc categories |
| [clear(int sheetIndex)](#clear-int-) | Xóa tất cả giá trị các cells trên sheet |
| [calculateFormulas()](#calculateFormulas--) | Tính toán tất cả formulas trong workbook và cập nhật các giá trị cells tương ứng. |
### getWorksheets() {#getWorksheets--}
```
public final IChartDataWorksheetCollection getWorksheets()
```

Lấy một bộ sưu tập các worksheets.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 500);
>      IChartDataWorkbook workbook =  chart.getChartData().getChartDataWorkbook();
>      for (IChartDataWorksheet worksheet : workbook.getWorksheets())
>      {
>          String worksheetName = worksheet.getName();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**
[IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection)
### getCellCollection(String formula, boolean skipHiddenCells) {#getCellCollection-java.lang.String-boolean-}
```
public final IChartCellCollection getCellCollection(String formula, boolean skipHiddenCells)
```

Lấy tập hợp các cells.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| formula | java.lang.String | Công thức Excel như "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | Nếu true thì phương thức trả về bộ sưu tập không có hidden cells. |

**Trả về:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IChartDataCell getCell(String worksheetName, int row, int column)
```

Lấy cell có thể được sử dụng cho chart series hoặc categories

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| worksheetName | java.lang.String | Tên của worksheet. |
| row | int | Hàng. |
| column | int | Cột. |

**Trả về:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - đối tượng Cell
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column)
```

Lấy cell có thể được sử dụng cho chart series hoặc categories

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| worksheetIndex | int | Chỉ mục của worksheet. |
| row | int | Hàng. |
| column | int | Cột. |

**Trả về:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - đối tượng Cell
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName)
```

Lấy cell có thể được sử dụng cho chart series hoặc categories

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| worksheetIndex | int | Chỉ mục của worksheet. |
| cellName | java.lang.String | Tên của cell. |

**Trả về:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - đối tượng Cell
### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```

Lấy cell có thể được sử dụng cho chart series hoặc categories

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| worksheetIndex | int | Chỉ mục của worksheet. |
| cellName | java.lang.String | Tên của cell. |
| value | java.lang.Object | Giá trị. |

**Trả về:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - đối tượng Cell
### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```

Lấy cell có thể được sử dụng cho chart series hoặc categories

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| worksheetIndex | int | Chỉ mục của worksheet. |
| row | int | Hàng. |
| column | int | Cột. |
| value | java.lang.Object | Giá trị. |

**Trả về:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - đối tượng Cell
### clear(int sheetIndex) {#clear-int-}
```
public final void clear(int sheetIndex)
```

Xóa tất cả giá trị các cells trên sheet

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sheetIndex | int | Chỉ mục của sheet |
### calculateFormulas() {#calculateFormulas--}
```
public final void calculateFormulas()
```

Tính toán tất cả formulas trong workbook và cập nhật các giá trị cells tương ứng.

--------------------

> ```
> Example shows how to assign a formula to the cell and to calculate a value. The value of the "B4" cell is getting set to 5.
>   
>   Presentation pres = new Presentation();
>   try {
>       IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 100, 100, 300, 400);
>       IChartDataWorkbook wb = chart.getChartData().getChartDataWorkbook();
>       wb.getCell(0, "B2", 2);
>       wb.getCell(0, "B3", 3);
>       wb.getCell(0, "B4").setFormula("B2+B3");
>       wb.calculateFormulas();
>       ...
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```