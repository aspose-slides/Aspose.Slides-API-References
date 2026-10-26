---
title: ExcelDataWorkbook
second_title: Aspose.Slides cho Android qua Tham khảo API Java
description: Đại diện cho một workbook cung cấp quyền truy cập vào dữ liệu Excel cho mục đích chung.
type: docs
url: /vi/com.aspose.slides/exceldataworkbook/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook)
```
public class ExcelDataWorkbook implements IExcelDataWorkbook
```

Đại diện cho một workbook cho phép truy cập dữ liệu Excel cho mục đích chung.
## Các hàm tạo

| Hàm tạo | Mô tả |
| --- | --- |
| [ExcelDataWorkbook(String filePath)](#ExcelDataWorkbook-java.lang.String-) | Khởi tạo một thể hiện mới bằng cách sử dụng đường dẫn tệp được chỉ định. |
| [ExcelDataWorkbook(InputStream stream)](#ExcelDataWorkbook-java.io.InputStream-) | Khởi tạo một thể hiện mới của lớp bằng cách sử dụng luồng đã cung cấp. |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | Truy xuất một tập hợp các ô từ workbook khớp với công thức được chỉ định. |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Truy xuất một ô từ worksheet được chỉ định bằng cách sử dụng chỉ số và tọa độ ô. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Truy xuất một ô từ worksheet được chỉ định bằng cách sử dụng tên và tọa độ ô. |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Truy xuất một ô từ worksheet được chỉ định bằng cách sử dụng chỉ số và tên ô theo kiểu Excel (ví dụ, "B2"). |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | Truy xuất một ô từ worksheet được chỉ định bằng cách sử dụng tên ô theo kiểu Excel (ví dụ, "B2"). |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | Truy xuất một từ điển chứa các chỉ mục và tên của tất cả biểu đồ trong worksheet được chỉ định của một workbook Excel. |
| [getWorksheetNames()](#getWorksheetNames--) | Truy xuất tên của tất cả các worksheet có trong workbook Excel. |
### ExcelDataWorkbook(String filePath) {#ExcelDataWorkbook-java.lang.String-}
```
public ExcelDataWorkbook(String filePath)
```

Khởi tạo một thể hiện mới bằng cách sử dụng đường dẫn tệp được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| filePath | java.lang.String | Đường dẫn đầy đủ đến tệp workbook Excel. |

### ExcelDataWorkbook(InputStream stream) {#ExcelDataWorkbook-java.io.InputStream-}
```
public ExcelDataWorkbook(InputStream stream)
```

Khởi tạo một thể hiện mới của lớp bằng cách sử dụng luồng đã cung cấp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.InputStream | Một luồng chứa dữ liệu workbook Excel. |

### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public final System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```

Truy xuất một tập hợp các ô từ workbook khớp với công thức được chỉ định.

--------------------

> ```
> ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //Kết quả: 5
>  ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| formula | java.lang.String | Một công thức hoặc biểu thức phạm vi (ví dụ, "Sheet1!A1:B3") được dùng để xác định các ô mục tiêu. |
| skipHiddenCells | boolean | Nếu true, các ô ẩn (ví dụ, trong các hàng hoặc cột ẩn) sẽ bị loại khỏi kết quả. |

**Trả về:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - Một danh sách chỉ đọc các ô khớp với công thức được chỉ định.
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IExcelDataCell getCell(int worksheetIndex, int row, int column)
```

Truy xuất một ô từ worksheet được chỉ định bằng cách sử dụng chỉ số và tọa độ ô.

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
| worksheetIndex | int | Chỉ số bắt đầu từ 0 của worksheet. |
| row | int | Chỉ số dòng bắt đầu từ 0 của ô. |
| column | int | Chỉ số cột bắt đầu từ 0 của ô. |

**Trả về:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Ô tại vị trí được chỉ định.
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IExcelDataCell getCell(String worksheetName, int row, int column)
```

Truy xuất một ô từ worksheet được chỉ định bằng cách sử dụng tên và tọa độ ô.

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
| row | int | Chỉ số dòng bắt đầu từ 0 của ô. |
| column | int | Chỉ số cột bắt đầu từ 0 của ô. |

**Trả về:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Ô tại vị trí được chỉ định.
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IExcelDataCell getCell(int worksheetIndex, String cellName)
```

Truy xuất một ô từ worksheet được chỉ định bằng cách sử dụng chỉ số và tên ô theo kiểu Excel (ví dụ, "B2").

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
| worksheetIndex | int | Chỉ số bắt đầu từ 0 của worksheet. |
| cellName | java.lang.String | Tham chiếu ô theo kiểu Excel (ví dụ, "A1", "C5"). |

**Trả về:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Ô tại vị trí được chỉ định.
### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public final IExcelDataCell getCell(String worksheetName, String cellName)
```

Truy xuất một ô từ worksheet được chỉ định bằng cách sử dụng tên ô theo kiểu Excel (ví dụ, "B2").

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
| cellName | java.lang.String | Tham chiếu ô theo kiểu Excel (ví dụ, "A1", "C5"). |

**Trả về:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Ô tại vị trí được chỉ định.
### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public final System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```

Truy xuất một từ điển chứa các chỉ mục và tên của tất cả biểu đồ trong worksheet được chỉ định của một workbook Excel.

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
| worksheetName | java.lang.String | Tên của worksheet để tìm kiếm biểu đồ. |

**Trả về:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - Một từ điển trong đó khóa là chỉ số biểu đồ và giá trị là tên biểu đồ.
### getWorksheetNames() {#getWorksheetNames--}
```
public final System.Collections.Generic.List<String> getWorksheetNames()
```

Truy xuất tên của tất cả các worksheet có trong workbook Excel.

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