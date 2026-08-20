---
title: IExcelDataWorkbook
second_title: Aspose.Slides for Java API Reference
description: Đại diện cho một workbook cung cấp quyền truy cập vào dữ liệu Excel cho mục đích sử dụng chung.
type: docs
url: /vi/com.aspose.slides/iexceldataworkbook/
---```
public interface IExcelDataWorkbook
```

Đại diện cho một workbook cung cấp quyền truy cập vào dữ liệu Excel cho mục đích sử dụng chung.
## Các phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | Lấy một tập hợp các ô từ workbook khớp với công thức đã chỉ định. |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Lấy một ô từ worksheet đã chỉ định bằng chỉ số và tọa độ ô. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Lấy một ô từ worksheet đã chỉ định bằng tên và tọa độ ô. |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Lấy một ô từ worksheet đã chỉ định bằng chỉ số và tên ô theo kiểu Excel (ví dụ: "B2"). |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | Lấy một ô từ worksheet đã chỉ định bằng tên ô theo kiểu Excel (ví dụ: "B2"). |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | Lấy một từ điển chứa các chỉ số và tên của tất cả các biểu đồ trong worksheet đã chỉ định của một workbook Excel. |
| [getWorksheetNames()](#getWorksheetNames--) | Lấy tên của tất cả các worksheet có trong workbook Excel. |
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
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| formula | java.lang.String | Một công thức hoặc biểu thức phạm vi (ví dụ: "Sheet1!A1:B3") dùng để xác định các ô mục tiêu. |
| skipHiddenCells | boolean | Nếu true, các ô ẩn (ví dụ: trong các hàng hoặc cột ẩn) sẽ bị loại bỏ khỏi kết quả. |

**Trả về:**
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
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| worksheetIndex | int | Chỉ số worksheet tính từ 0. |
| row | int | Chỉ số hàng của ô tính từ 0. |
| column | int | Chỉ số cột của ô tính từ 0. |

**Trả về:**
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
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| worksheetName | java.lang.String | Tên của worksheet. |
| row | int | Chỉ số hàng của ô tính từ 0. |
| column | int | Chỉ số cột của ô tính từ 0. |

**Trả về:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Ô tại vị trí đã chỉ định.
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, String cellName)
```

Lấy một ô từ worksheet đã chỉ định bằng chỉ số và tên ô theo kiểu Excel (ví dụ: "B2").

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, "B2");
>  System.out.println(cell.getValue().toString());
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| worksheetIndex | int | Chỉ số worksheet tính từ 0. |
| cellName | java.lang.String | Tham chiếu ô theo kiểu Excel (ví dụ: "A1", "C5"). |

**Trả về:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Ô tại vị trí đã chỉ định.
### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public abstract IExcelDataCell getCell(String worksheetName, String cellName)
```

Lấy một ô từ worksheet đã chỉ định bằng tên ô theo kiểu Excel (ví dụ: "B2").

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", "B2");
>  System.out.println(cell.getValue().toString());
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| worksheetName | java.lang.String | Tên của worksheet. |
| cellName | java.lang.String | Tham chiếu ô theo kiểu Excel (ví dụ: "A1", "C5"). |

**Trả về:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Ô tại vị trí đã chỉ định.
### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public abstract System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```

Lấy một từ điển chứa các chỉ số và tên của tất cả các biểu đồ trong worksheet đã chỉ định của một workbook Excel.

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
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| worksheetName | java.lang.String | Tên của worksheet để tìm kiếm các biểu đồ. |

**Trả về:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - Một từ điển trong đó khóa là chỉ số biểu đồ và giá trị là tên biểu đồ.
### getWorksheetNames() {#getWorksheetNames--}
```
public abstract System.Collections.Generic.List<String> getWorksheetNames()
```

Lấy tên của tất cả các worksheet có trong workbook Excel.

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<String> sheetNames = wb.getWorksheetNames();
>  for (String name : sheetNames)
>      System.out.println(name);
> ```

**Trả về:**
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - Một danh sách các tên worksheet