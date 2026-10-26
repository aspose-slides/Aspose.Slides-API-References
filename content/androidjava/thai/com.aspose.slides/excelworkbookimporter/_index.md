---
title: ExcelWorkbookImporter
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: ให้ความสามารถในการนำเข้าข้อมูลจาก workbook ของ Excel ไปยังงานนำเสนอ.
type: docs
url: /th/com.aspose.slides/excelworkbookimporter/
---
**Inheritance:**  
java.lang.Object  
```
public class ExcelWorkbookImporter
```

ให้ความสามารถในการนำเข้าข้อมูลจาก workbook ของ Excel ไปยังงานนำเสนอ.

## เมธอด

| Method | Description |
| --- | --- |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-) | ดึงแผนภูมิจาก workbook ของ Excel ที่ระบุและเพิ่มลงในตำแหน่งสุดท้ายของชุดรูปทรงที่กำหนดที่พิกัดที่ระบุ. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-) | ดึงแผนภูมิจาก workbook ของ Excel ที่ระบุและเพิ่มลงในตำแหน่งสุดท้ายของชุดรูปทรงที่กำหนดที่พิกัดที่ระบุ. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-) | ดึงแผนภูมิจาก workbook ของ Excel ที่ระบุและเพิ่มลงในตำแหน่งสุดท้ายของชุดรูปทรงที่กำหนดที่พิกัดที่ระบุ. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-) | ดึงแผนภูมิจาก workbook ของ Excel ที่ระบุและเพิ่มลงในตำแหน่งสุดท้ายของชุดรูปทรงที่กำหนดที่พิกัดที่ระบุ. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-) | ดึงตารางจาก workbook ของ Excel ที่ระบุและเพิ่มลงในตำแหน่งสุดท้ายของชุดรูปทรงที่กำหนดที่พิกัดที่ระบุ. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-) | ดึงตารางจากไฟล์ workbook ของ Excel ที่ระบุและเพิ่มลงในตำแหน่งสุดท้ายของชุดรูปทรงที่กำหนดที่พิกัดที่ระบุ. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-) | ดึงตารางจากไฟล์ workbook ของ Excel ที่ระบุและเพิ่มลงในตำแหน่งสุดท้ายของชุดรูปทรงที่กำหนดที่พิกัดที่ระบุ. |

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)
```

ดึงแผนภูมิจาก workbook ของ Excel ที่ระบุและเพิ่มลงในตำแหน่งสุดท้ายของชุดรูปทรงที่กำหนดที่พิกัดที่ระบุ.

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


**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | ชุดรูปทรงที่แผนภูมิจะถูกเพิ่มเข้าไป. |
| x | float | พิกัด X สำหรับกำหนดตำแหน่งของแผนภูมิ. |
| y | float | พิกัด Y สำหรับกำหนดตำแหน่งของแผนภูมิ. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Workbook ของ Excel. |
| worksheetName | java.lang.String | ชื่อของแผ่นงานที่มีแผนภูมิอยู่. |
| chartIndex | int | ดัชนีเริ่มจากศูนย์ของรูปแผนภูมิที่ต้องการแทรก ดัชนีนี้สามารถได้รับโดยใช้เมธอด [IExcelDataWorkbook.getChartsFromWorksheet(String)](../../com.aspose.slides/iexceldataworkbook\#getChartsFromWorksheet-String-). |
| embedAllWorkbook | boolean | หากเป็นจริง (true) จะฝัง workbook ทั้งหมดในแผนภูมิ; หากเป็นเท็จ (false) จะฝังเฉพาะข้อมูลแผนภูมิเท่านั้น. |

**Returns:**  
[IChart](../../com.aspose.slides/ichart) - แผนภูมิที่ถูกเพิ่มเข้าไปในชุดรูปทรง.

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)
```

ดึงแผนภูมิจาก workbook ของ Excel ที่ระบุและเพิ่มลงในตำแหน่งสุดท้ายของชุดรูปทรงที่กำหนดที่พิกัดที่ระบุ.

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


**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | ชุดรูปทรงที่แผนภูมิจะถูกเพิ่มเข้าไป. |
| x | float | พิกัด X สำหรับกำหนดตำแหน่งของแผนภูมิ. |
| y | float | พิกัด Y สำหรับกำหนดตำแหน่งของแผนภูมิ. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Workbook ของ Excel. |
| worksheetName | java.lang.String | ชื่อของแผ่นงานที่มีแผนภูมิอยู่. |
| chartName | java.lang.String | ชื่อของแผนภูมิที่จะเพิ่ม. |
| embedAllWorkbook | boolean | หากเป็นจริง (true) จะฝัง workbook ทั้งหมดในแผนภูมิ; หากเป็นเท็จ (false) จะฝังเฉพาะข้อมูลแผนภูมิเท่านั้น. |

**Returns:**  
[IChart](../../com.aspose.slides/ichart) - แผนภูมิที่ถูกเพิ่มเข้าไปในชุดรูปทรง.

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)
```

ดึงแผนภูมิจาก workbook ของ Excel ที่ระบุและเพิ่มลงในตำแหน่งสุดท้ายของชุดรูปทรงที่กำหนดที่พิกัดที่ระบุ.

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


**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | ชุดรูปทรงที่แผนภูมิจะถูกเพิ่มเข้าไป. |
| x | float | พิกัด X สำหรับกำหนดตำแหน่งของแผนภูมิ. |
| y | float | พิกัด Y สำหรับกำหนดตำแหน่งของแผนภูมิ. |
| workbookStream | java.io.InputStream | สตรีมที่มีข้อมูล workbook. |
| worksheetName | java.lang.String | ชื่อของแผ่นงานที่มีแผนภูมิอยู่. |
| chartName | java.lang.String | ชื่อของแผนภูมิที่จะเพิ่ม. |
| embedAllWorkbook | boolean | หากเป็นจริง (true) จะฝัง workbook ทั้งหมดในแผนภูมิ; หากเป็นเท็จ (false) จะฝังเฉพาะข้อมูลแผนภูมิเท่านั้น. |

**Returns:**  
[IChart](../../com.aspose.slides/ichart) - แผนภูมิที่ถูกเพิ่มเข้าไปในชุดรูปทรง.

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)
```

ดึงแผนภูมิจาก workbook ของ Excel ที่ระบุและเพิ่มลงในตำแหน่งสุดท้ายของชุดรูปทรงที่กำหนดที่พิกัดที่ระบุ.

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


**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | ชุดรูปทรงที่แผนภูมิจะถูกเพิ่มเข้าไป. |
| x | float | พิกัด X สำหรับกำหนดตำแหน่งของแผนภูมิ. |
| y | float | พิกัด Y สำหรับกำหนดตำแหน่งของแผนภูมิ. |
| workbookPath | java.lang.String | เส้นทางไฟล์ของ workbook ที่มีแผนภูมิอยู่. |
| worksheetName | java.lang.String | ชื่อของแผ่นงานที่มีแผนภูมิอยู่. |
| chartName | java.lang.String | ชื่อของแผนภูมิที่จะเพิ่ม. |
| embedWorkbook | boolean | หากเป็นจริง (true) workbook จะถูกฝังในแผนภูมิ; หากเป็นเท็จ (false) แผนภูมิจะลิงก์ไปยัง workbook ภายนอก. |

**Returns:**  
[IChart](../../com.aspose.slides/ichart) - แผนภูมิที่ถูกเพิ่มเข้าไปในชุดรูปทรง.

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)
```

ดึงตารางจาก workbook ของ Excel ที่ระบุและเพิ่มลงในตำแหน่งสุดท้ายของชุดรูปทรงที่กำหนดที่พิกัดที่ระบุ.

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


**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | ชุดรูปทรงที่ตารางจะถูกเพิ่มเข้าไป. |
| x | float | พิกัด X สำหรับกำหนดตำแหน่งของตาราง. |
| y | float | พิกัด Y สำหรับกำหนดตำแหน่งของตาราง. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Workbook ของ Excel. |
| worksheetName | java.lang.String | ชื่อของแผ่นงานที่มีตารางอยู่. |
| cellRange | java.lang.String | ช่วงเซลล์ที่กำหนดตาราง (เช่น "A1:D10"). |

**Returns:**  
[ITable](../../com.aspose.slides/itable) - ตารางที่ถูกเพิ่มเข้าไปในชุดรูปทรง.

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)
```

ดึงตารางจากไฟล์ workbook ของ Excel ที่ระบุและเพิ่มลงในตำแหน่งสุดท้ายของชุดรูปทรงที่กำหนดที่พิกัดที่ระบุ.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addTableFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, workbookPath, worksheetName, "A1:D10");
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | ชุดรูปทรงที่ตารางจะถูกเพิ่มเข้าไป. |
| x | float | พิกัด X สำหรับกำหนดตำแหน่งของตาราง. |
| y | float | พิกัด Y สำหรับกำหนดตำแหน่งของตาราง. |
| workbookPath | java.lang.String | เส้นทางไปยังไฟล์ workbook ของ Excel. |
| worksheetName | java.lang.String | ชื่อของแผ่นงานที่มีตารางอยู่. |
| cellRange | java.lang.String | ช่วงเซลล์ที่กำหนดตาราง (เช่น "A1:D10"). |

**Returns:**  
[ITable](../../com.aspose.slides/itable) - ตารางที่ถูกเพิ่มเข้าไปในชุดรูปทรง.

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)
```

ดึงตารางจากไฟล์ workbook ของ Excel ที่ระบุและเพิ่มลงในตำแหน่งสุดท้ายของชุดรูปทรงที่กำหนดที่พิกัดที่ระบุ.

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


**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | ชุดรูปทรงที่ตารางจะถูกเพิ่มเข้าไป. |
| x | float | พิกัด X สำหรับกำหนดตำแหน่งของตาราง. |
| y | float | พิกัด Y สำหรับกำหนดตำแหน่งของตาราง. |
| workbookStream | java.io.InputStream | สตรีมที่มีข้อมูล workbook. |
| worksheetName | java.lang.String | ชื่อของแผ่นงานที่มีตารางอยู่. |
| cellRange | java.lang.String | ช่วงเซลล์ที่กำหนดตาราง (เช่น "A1:D10"). |

**Returns:**  
[ITable](../../com.aspose.slides/itable) - ตารางที่ถูกเพิ่มเข้าไปในชุดรูปทรง.