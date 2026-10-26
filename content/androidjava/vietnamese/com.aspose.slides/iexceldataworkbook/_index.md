---
title: IExcelDataWorkbook
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho một workbook cung cấp quyền truy cập vào dữ liệu Excel cho việc sử dụng chung.
type: docs
url: /vi/com.aspose.slides/iexceldataworkbook/
---```
public interface IExcelDataWorkbook
```

Đại diện cho một workbook cung cấp quyền truy cập vào dữ liệu Excel cho việc sử dụng chung.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | Lấy một tập hợp các ô từ workbook khớp với công thức đã chỉ định. |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Lấy một ô từ worksheet đã chỉ định bằng chỉ số và tọa độ ô. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Lấy một ô từ worksheet đã chỉ định bằng tên và tọa độ ô. |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Lấy một ô từ worksheet đã chỉ định bằng chỉ số và tên ô theo kiểu Excel (e.g., "B2"). |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | Lấy một ô từ worksheet đã chỉ định bằng tên ô theo kiểu Excel (e.g., "B2"). |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | Lấy một từ điển chứa các chỉ mục và tên của tất cả biểu đồ trong worksheet đã chỉ định của một workbook Excel. |
| [getWorksheetNames()](#getWorksheetNames--) | Lấy tên của tất cả worksheet có trong workbook Excel. |
### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public abstract System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```


Lấy một tập hợp các ô từ workbook khớp với công thức đã chỉ định.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //Kết quả: 5
> ```

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| formula | java.lang.String | Một công thức hoặc biểu thức phạm vi (e.g., "Sheet1!A1:B3") được sử dụng để xác định các ô mục tiêu. |
| skipHiddenCells | boolean | Nếu true, các ô ẩn (e.g., trong các hàng hoặc cột ẩn) sẽ bị loại khỏi kết quả. |

**Giá trị trả về:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - Một danh sách chỉ đọc các ô khớp với công thức đã chỉ định.
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, int row, int column)
```


Lấy một ô từ worksheet đã chỉ định bằng chỉ số và tọa độ ô.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | Chỉ mục worksheet tính từ 0. |
| row | int | Chỉ mục hàng của ô tính từ 0. |
| column | int | Chỉ mục cột của ô tính từ 0. |

**Giá trị trả về:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Ô tại vị trí đã chỉ định.
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IExcelDataCell getCell(String worksheetName, int row, int column)
```


Lấy một ô từ worksheet đã chỉ định bằng tên và tọa độ ô.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | java.lang.String | Tên của worksheet. |
| row | int | Chỉ mục hàng của ô tính từ 0. |
| column | int | Chỉ mục cột của ô tính từ 0. |

**Giá trị trả về:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Ô tại vị trí đã chỉ định.
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, String cellName)
```


Lấy một ô từ worksheet đã chỉ định bằng chỉ số và tên ô theo kiểu Excel (e.g., "B2").

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, "B2");
>  System.out.println(cell.getValue().toString());
> ```

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | Chỉ mục worksheet tính từ 0. |
| cellName | java.lang.String | Tham chiếu ô theo kiểu Excel (e.g., "A1", "C5"). |

**Giá trị trả về:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Ô tại vị trí đã chỉ định.
### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public abstract IExcelDataCell getCell(String worksheetName, String cellName)
```


Lấy một ô từ worksheet đã chỉ định bằng tên ô theo kiểu Excel (e.g., "B2").

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", "B2");
>  System.out.println(cell.getValue().toString());
> ```

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | java.lang.String | Tên của worksheet. |
| cellName | java.lang.String | Tham chiếu ô theo kiểu Excel (e.g., "A1", "C5"). |

**Giá trị trả về:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Ô tại vị trí đã chỉ định.
### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public abstract System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```


Lấy một từ điển chứa các chỉ mục và tên của tất cả biểu đồ trong worksheet đã chỉ định của một workbook Excel.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  Dictionary.Enumerator<Integer, String> sheetCharts = wb.getChartsFromWorksheet("worksheetName").iterator();
>  while (sheetCharts.hasNext())
>  {
>      KeyValuePair<Integer, String> chart = sheetCharts.next();
>      System.out.println(chart.getKey() + " : " + chart.getValue());
>  }
> ```

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | java.lang.String | Tên của worksheet để tìm biểu đồ. |

**Giá trị trả về:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - Một từ điển trong đó khóa là chỉ mục biểu đồ và giá trị là tên biểu đồ.
### getWorksheetNames() {#getWorksheetNames--}
```
public abstract System.Collections.Generic.List<String> getWorksheetNames()
```


Lấy tên của tất cả worksheet có trong workbook Excel.

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<String> sheetNames = wb.getWorksheetNames();
>  for (String name : sheetNames)
>      System.out.println(name);
> ```

**Giá trị trả về:**
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - Một danh sách các tên worksheet