---
title: IChartDataWorkbook
second_title: Aspose.Slides for Java API Reference
description: Cung cấp quyền truy cập vào sổ làm việc Excel được nhúng
type: docs
url: /vi/com.aspose.slides/ichartdataworkbook/
---```
public interface IChartDataWorkbook
```

Cung cấp quyền truy cập vào sổ làm việc Excel được nhúng
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [calculateFormulas()](#calculateFormulas--) | Tính toán tất cả công thức trong sổ làm việc và cập nhật giá trị các ô tương ứng. |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | Lấy tập hợp các ô. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Lấy ô có thể được dùng cho chuỗi biểu đồ hoặc danh mục |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Lấy ô có thể được dùng cho chuỗi biểu đồ hoặc danh mục |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Lại ô có thể được dùng cho chuỗi biểu đồ hoặc danh mục |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | Lấy ô có thể được dùng cho chuỗi biểu đồ hoặc danh mục |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | Lấy ô có thể được dùng cho chuỗi biểu đồ hoặc danh mục |
| [clear(int sheetIndex)](#clear-int-) | Xóa tất cả giá trị ô trên bảng |
| [getWorksheets()](#getWorksheets--) | Lấy một tập hợp các bảng tính. |
### calculateFormulas() {#calculateFormulas--}
```
public abstract void calculateFormulas()
```


Tính toán tất cả công thức trong sổ làm việc và cập nhật giá trị các ô tương ứng.

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

### getCellCollection(String formula, boolean skipHiddenCells) {#getCellCollection-java.lang.String-boolean-}
```
public abstract IChartCellCollection getCellCollection(String formula, boolean skipHiddenCells)
```


Lấy tập hợp các ô.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| formula | java.lang.String | Công thức Excel như "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | Nếu true thì phương thức trả về tập hợp mà không có các ô ẩn. |

**Trả về:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection) - Set of cells [IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IChartDataCell getCell(String worksheetName, int row, int column)
```


Lấy ô có thể được dùng cho chuỗi biểu đồ hoặc danh mục

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| worksheetName | java.lang.String | Tên của bảng tính. |
| row | int | Hàng. |
| column | int | Cột. |

**Trả về:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column)
```


Lấy ô có thể được dùng cho chuỗi biểu đồ hoặc danh mục

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| worksheetIndex | int | Chỉ mục của bảng tính. |
| row | int | Hàng. |
| column | int | Cột. |

**Trả về:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IChartDataCell getCell(int worksheetIndex, String cellName)
```


Lấy ô có thể được dùng cho chuỗi biểu đồ hoặc danh mục

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| worksheetIndex | int | Chỉ mục của bảng tính. |
| cellName | java.lang.String | Tên của ô. |

**Trả về:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public abstract IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```


Lấy ô có thể được dùng cho chuỗi biểu đồ hoặc danh mục

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| worksheetIndex | int | Chỉ mục của bảng tính. |
| cellName | java.lang.String | Tên của ô. |
| value | java.lang.Object | Giá trị. |

**Trả về:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```


Lấy ô có thể được dùng cho chuỗi biểu đồ hoặc danh mục

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| worksheetIndex | int | Chỉ mục của bảng tính. |
| row | int | Hàng. |
| column | int | Cột. |
| value | java.lang.Object | Giá trị. |

**Trả về:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### clear(int sheetIndex) {#clear-int-}
```
public abstract void clear(int sheetIndex)
```


Xóa tất cả giá trị ô trên bảng

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sheetIndex | int | Chỉ mục của bảng |

### getWorksheets() {#getWorksheets--}
```
public abstract IChartDataWorksheetCollection getWorksheets()
```


Lấy một tập hợp các bảng tính.

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