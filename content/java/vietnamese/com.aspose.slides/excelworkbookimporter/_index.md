---
title: ExcelWorkbookImporter
second_title: Tham chiếu API Aspose.Slides cho Java
description: Cung cấp chức năng nhập nội dung từ một sổ làm việc Excel vào bản trình bày.
type: docs
url: /vi/com.aspose.slides/excelworkbookimporter/
---
**Kế thừa:**
java.lang.Object
```
public class ExcelWorkbookImporter
```

Cung cấp chức năng nhập nội dung từ một sổ làm việc Excel vào bản trình bày.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-) | Lấy một biểu đồ từ sổ làm việc Excel được chỉ định và thêm nó vào cuối bộ sưu tập hình đã cho tại tọa độ được chỉ định. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-) | Lấy một biểu đồ từ sổ làm việc Excel được chỉ định và thêm nó vào cuối bộ sưu tập hình đã cho tại tọa độ được chỉ định. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-) | Lấy một biểu đồ từ sổ làm việc Excel được chỉ định và thêm nó vào cuối bộ sưu tập hình đã cho tại tọa độ được chỉ định. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-) | Lấy một biểu đồ từ sổ làm việc Excel được chỉ định và thêm nó vào cuối bộ sưu tập hình đã cho tại tọa độ được chỉ định. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-) | Lấy một bảng từ sổ làm việc Excel được chỉ định và thêm nó vào cuối bộ sưu tập hình đã cho tại tọa độ được chỉ định. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-) | Lấy một bảng từ tệp sổ làm việc Excel được chỉ định và thêm nó vào cuối bộ sưu tập hình đã cho tại tọa độ được chỉ định. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-) | Lấy một bảng từ tệp sổ làm việc Excel được chỉ định và thêm nó vào cuối bộ sưu tập hình đã cho tại tọa độ được chỉ định. |
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)
```


Lấy một biểu đồ từ sổ làm việc Excel được chỉ định và thêm nó vào cuối bộ sưu tập hình đã cho tại tọa độ được chỉ định.

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addChartFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, wb, worksheetName, chartName, false);
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Bộ sưu tập hình mà biểu đồ sẽ được thêm vào. |
| x | float | Tọa độ X để định vị biểu đồ. |
| y | float | Tọa độ Y để định vị biểu đồ. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Sổ làm việc Excel. |
| worksheetName | java.lang.String | Tên của trang tính chứa biểu đồ. |
| chartIndex | int | Chỉ mục bắt đầu từ 0 của hình biểu đồ cần chèn. Chỉ mục này có thể lấy bằng phương thức [IExcelDataWorkbook.getChartsFromWorksheet(String)](../../com.aspose.slides/iexceldataworkbook\#getChartsFromWorksheet-String-). |
| embedAllWorkbook | boolean | Nếu true, toàn bộ sổ làm việc sẽ được nhúng vào biểu đồ; nếu false, chỉ dữ liệu biểu đồ sẽ được nhúng. |

**Giá trị trả về:**
[IChart](../../com.aspose.slides/ichart) - Biểu đồ đã được thêm vào bộ sưu tập hình.
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)
```


Lấy một biểu đồ từ sổ làm việc Excel được chỉ định và thêm nó vào cuối bộ sưu tập hình đã cho tại tọa độ được chỉ định.

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  Presentation pres = new Presentation();
>  try {
>      String worksheetName = "worksheet name";
>      Dictionary.Enumerator<Integer, String> worksheetCharts = wb.getChartsFromWorksheet(worksheetName).iterator();
>      while (worksheetCharts.hasNext())
>      {
>          KeyValuePair<Integer, String> chart = worksheetCharts.next();
>          ISlide slide = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>          ExcelWorkbookImporter.addChartFromWorkbook(slide.getShapes(), 10, 10, wb, worksheetName, chart.getKey(), false);
>      }
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Bộ sưu tập hình mà biểu đồ sẽ được thêm vào. |
| x | float | Tọa độ X để định vị biểu đồ. |
| y | float | Tọa độ Y để định vị biểu đồ. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Sổ làm việc Excel. |
| worksheetName | java.lang.String | Tên của trang tính chứa biểu đồ. |
| chartName | java.lang.String | Tên của biểu đồ cần thêm. |
| embedAllWorkbook | boolean | Nếu true, toàn bộ sổ làm việc sẽ được nhúng vào biểu đồ; nếu false, chỉ dữ liệu biểu đồ sẽ được nhúng. |

**Giá trị trả về:**
[IChart](../../com.aspose.slides/ichart) - Biểu đồ đã được thêm vào bộ sưu tập hình.
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)
```


Lấy một biểu đồ từ sổ làm việc Excel được chỉ định và thêm nó vào cuối bộ sưu tập hình đã cho tại tọa độ được chỉ định.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fStream = new FileInputStream(workbookPath);
>      ExcelWorkbookImporter.addChartFromWorkbook(pres.getLayoutSlides().get_Item(0).getShapes(), 10, 10, fStream, worksheetName, chartName, true);
>      fStream.close();
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Bộ sưu tập hình mà biểu đồ sẽ được thêm vào. |
| x | float | Tọa độ X để định vị biểu đồ. |
| y | float | Tọa độ Y để định vị biểu đồ. |
| workbookStream | java.io.InputStream | Luồng chứa dữ liệu sổ làm việc. |
| worksheetName | java.lang.String | Tên của trang tính chứa biểu đồ. |
| chartName | java.lang.String | Tên của biểu đồ cần thêm. |
| embedAllWorkbook | boolean | Nếu true, toàn bộ sổ làm việc sẽ được nhúng vào biểu đồ; nếu false, chỉ dữ liệu biểu đồ sẽ được nhúng. |

**Giá trị trả về:**
[IChart](../../com.aspose.slides/ichart) - Biểu đồ đã được thêm vào bộ sưu tập hình.
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)
```


Lấy một biểu đồ từ sổ làm việc Excel được chỉ định và thêm nó vào cuối bộ sưu tập hình đã cho tại tọa độ được chỉ định.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addChartFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, workbookPath, worksheetName, chartName, false);
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Bộ sưu tập hình mà biểu đồ sẽ được thêm vào. |
| x | float | Tọa độ X để định vị biểu đồ. |
| y | float | Tọa độ Y để định vị biểu đồ. |
| workbookPath | java.lang.String | Đường dẫn tới tệp sổ làm việc chứa biểu đồ. |
| worksheetName | java.lang.String | Tên của trang tính chứa biểu đồ. |
| chartName | java.lang.String | Tên của biểu đồ cần thêm. |
| embedWorkbook | boolean | Nếu true, sổ làm việc sẽ được nhúng vào biểu đồ; nếu false, biểu đồ sẽ liên kết tới sổ làm việc bên ngoài. |

**Giá trị trả về:**
[IChart](../../com.aspose.slides/ichart) - Biểu đồ đã được thêm vào bộ sưu tập hình.
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)
```


Lấy một bảng từ sổ làm việc Excel được chỉ định và thêm nó vào cuối bộ sưu tập hình đã cho tại tọa độ được chỉ định.

--------------------

> ```
> IExcelDataWorkbook workbook = new ExcelDataWorkbook(testFile);
>  Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addTableFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, workbook, worksheetName, "A1:D10");
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Bộ sưu tập hình mà bảng sẽ được thêm vào. |
| x | float | Tọa độ X để định vị bảng. |
| y | float | Tọa độ Y để định vị bảng. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Sổ làm việc Excel. |
| worksheetName | java.lang.String | Tên của trang tính chứa bảng. |
| cellRange | java.lang.String | Phạm vi ô xác định bảng (ví dụ, "A1:D10"). |

**Giá trị trả về:**
[ITable](../../com.aspose.slides/itable) - Bảng đã được thêm vào bộ sưu tập hình.
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)
```


Lấy một bảng từ tệp sổ làm việc Excel được chỉ định và thêm nó vào cuối bộ sưu tập hình đã cho tại tọa độ được chỉ định.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addTableFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, workbookPath, worksheetName, "A1:D10");
>      pres.save("result.pptx", SaveFormat.Pptx);
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Bộ sưu tập hình mà bảng sẽ được thêm vào. |
| x | float | Tọa độ X để định vị bảng. |
| y | float | Tọa độ Y để định vị bảng. |
| workbookPath | java.lang.String | Đường dẫn tới tệp sổ làm việc Excel. |
| worksheetName | java.lang.String | Tên của trang tính chứa bảng. |
| cellRange | java.lang.String | Phạm vi ô xác định bảng (ví dụ, "A1:D10"). |

**Giá trị trả về:**
[ITable](../../com.aspose.slides/itable) - Bảng đã được thêm vào bộ sưu tập hình.
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)
```


Lấy một bảng từ tệp sổ làm việc Excel được chỉ định và thêm nó vào cuối bộ sưu tập hình đã cho tại tọa độ được chỉ định.

--------------------

> ```
> FileInputStream fStream = new FileInputStream(workbookPath);
>  Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addTableFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, fStream, worksheetName, "A1:D10");
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Bộ sưu tập hình mà bảng sẽ được thêm vào. |
| x | float | Tọa độ X để định vị bảng. |
| y | float | Tọa độ Y để định vị bảng. |
| workbookStream | java.io.InputStream | Luồng chứa dữ liệu sổ làm việc. |
| worksheetName | java.lang.String | Tên của trang tính chứa bảng. |
| cellRange | java.lang.String | Phạm vi ô xác định bảng (ví dụ, "A1:D10"). |

**Giá trị trả về:**
[ITable](../../com.aspose.slides/itable) - Bảng đã được thêm vào bộ sưu tập hình.