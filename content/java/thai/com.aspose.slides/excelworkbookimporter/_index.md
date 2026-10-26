---
title: ExcelWorkbookImporter
second_title: Aspose.Slides สำหรับ Java อ้างอิง API
description: ให้ฟังก์ชันสำหรับการนำเข้าข้อมูลจากเวิร์กบุ๊ก Excel ไปสู่การนำเสนอ
type: docs
url: /th/com.aspose.slides/excelworkbookimporter/
---
**การสืบทอด:**  
java.lang.Object  
```
public class ExcelWorkbookImporter
```

ให้ฟังก์ชันสำหรับการนำเข้าข้อมูลจากไฟล์เวิร์กบุ๊ก Excel ไปยังการนำเสนอ

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-) | ดึงแผนภูมิจากไฟล์เวิร์กบุ๊ก Excel ที่ระบุและเพิ่มเข้าไปในส่วนท้ายของคอลเลกชันรูปทรงที่กำหนดที่พิกัดที่ระบุ |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-) | ดึงแผนภูมิจากไฟล์เวิร์กบุ๊ก Excel ที่ระบุและเพิ่มเข้าไปในส่วนท้ายของคอลเลกชันรูปทรงที่กำหนดที่พิกัดที่ระบุ |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-) | ดึงแผนภูมิจากไฟล์เวิร์กบุ๊ก Excel ที่ระบุและเพิ่มเข้าไปในส่วนท้ายของคอลเลกชันรูปทรงที่กำหนดที่พิกัดที่ระบุ |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-) | ดึงแผนภูมิจากไฟล์เวิร์กบุ๊ก Excel ที่ระบุและเพิ่มเข้าไปในส่วนท้ายของคอลเลกชันรูปทรงที่กำหนดที่พิกัดที่ระบุ |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-) | ดึงตารางจากไฟล์เวิร์กบุ๊ก Excel ที่ระบุและเพิ่มเข้าไปในส่วนท้ายของคอลเลกชันรูปทรงที่กำหนดที่พิกัดที่ระบุ |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-) | ดึงตารางจากไฟล์เวิร์กบุ๊ก Excel ที่ระบุและเพิ่มเข้าไปในส่วนท้ายของคอลเลกชันรูปทรงที่กำหนดที่พิกัดที่ระบุ |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-) | ดึงตารางจากไฟล์เวิร์กบุ๊ก Excel ที่ระบุและเพิ่มเข้าไปในส่วนท้ายของคอลเลกชันรูปทรงที่กำหนดที่พิกัดที่ระบุ |

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)
```

ดึงแผนภูมิจากไฟล์เวิร์กบุ๊ก Excel ที่ระบุและเพิ่มเข้าไปในส่วนท้ายของคอลเลกชันรูปทรงที่กำหนดที่พิกัดที่ระบุ

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

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | คอลเลกชันรูปทรงที่จะแผนภูมิจะถูกเพิ่มเข้าไป |
| x | float | พิกัด X สำหรับกำหนดตำแหน่งของแผนภูมิ |
| y | float | พิกัด Y สำหรับกำหนดตำแหน่งของแผนภูมิ |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | เวิร์กบุ๊ก Excel |
| worksheetName | java.lang.String | ชื่อแผ่นงานที่มีแผนภูมิ |
| chartIndex | int | ดัชนีเริ่มจากศูนย์ของรูปแผนภูมิที่จะใส่ การดึงค่าดัชนีนี้ทำได้โดยใช้เมธอด [IExcelDataWorkbook.getChartsFromWorksheet(String)](../../com.aspose.slides/iexceldataworkbook\#getChartsFromWorksheet-String-) |
| embedAllWorkbook | boolean | หากเป็น true เวิร์กบุ๊กทั้งหมดจะฝังอยู่ในแผนภูมิ; หากเป็น false จะฝังเฉพาะข้อมูลแผนภูมิเท่านั้น |

**คืนค่า:**  
[IChart](../../com.aspose.slides/ichart) - แผนภูมิที่ถูกเพิ่มเข้าไปในคอลเลกชันรูปทรง

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)
```

ดึงแผนภูมิจากไฟล์เวิร์กบุ๊ก Excel ที่ระบุและเพิ่มเข้าไปในส่วนท้ายของคอลเลกชันรูปทรงที่กำหนดที่พิกัดที่ระบุ

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

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | คอลเลกชันรูปทรงที่จะแผนภูมิจะถูกเพิ่มเข้าไป |
| x | float | พิกัด X สำหรับกำหนดตำแหน่งของแผนภูมิ |
| y | float | พิกัด Y สำหรับกำหนดตำแหน่งของแผนภูมิ |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | เวิร์กบุ๊ก Excel |
| worksheetName | java.lang.String | ชื่อแผ่นงานที่มีแผนภูมิ |
| chartName | java.lang.String | ชื่อของแผนภูมิที่จะเพิ่ม |
| embedAllWorkbook | boolean | หากเป็น true เวิร์กบุ๊กทั้งหมดจะฝังอยู่ในแผนภูมิ; หากเป็น false จะฝังเฉพาะข้อมูลแผนภูมิเท่านั้น |

**คืนค่า:**  
[IChart](../../com.aspose.slides/ichart) - แผนภูมิที่ถูกเพิ่มเข้าไปในคอลเลกชันรูปทรง

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)
```

ดึงแผนภูมิจากไฟล์เวิร์กบุ๊ก Excel ที่ระบุและเพิ่มเข้าไปในส่วนท้ายของคอลเลกชันรูปทรงที่กำหนดที่พิกัดที่ระบุ

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

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | คอลเลกชันรูปทรงที่จะแผนภูมิจะถูกเพิ่มเข้าไป |
| x | float | พิกัด X สำหรับกำหนดตำแหน่งของแผนภูมิ |
| y | float | พิกัด Y สำหรับกำหนดตำแหน่งของแผนภูมิ |
| workbookStream | java.io.InputStream | สตรีมที่มีข้อมูลของเวิร์กบุ๊ก |
| worksheetName | java.lang.String | ชื่อแผ่นงานที่มีแผนภูมิ |
| chartName | java.lang.String | ชื่อของแผนภูมิที่จะเพิ่ม |
| embedAllWorkbook | boolean | หากเป็น true เวิร์กบุ๊กทั้งหมดจะฝังอยู่ในแผนภูมิ; หากเป็น false จะฝังเฉพาะข้อมูลแผนภูมิเท่านั้น |

**คืนค่า:**  
[IChart](../../com.aspose.slides/ichart) - แผนภูมิที่ถูกเพิ่มเข้าไปในคอลเลกชันรูปทรง

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)
```

ดึงแผนภูมิจากไฟล์เวิร์กบุ๊ก Excel ที่ระบุและเพิ่มเข้าไปในส่วนท้ายของคอลเลกชันรูปทรงที่กำหนดที่พิกัดที่ระบุ

--------------------

> ```
> ตัวอย่าง:
>  
>  Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addChartFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, workbookPath, worksheetName, chartName, false);
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | คอลเลกชันรูปทรงที่จะแผนภูมิจะถูกเพิ่มเข้าไป |
| x | float | พิกัด X สำหรับกำหนดตำแหน่งของแผนภูมิ |
| y | float | พิกัด Y สำหรับกำหนดตำแหน่งของแผนภูมิ |
| workbookPath | java.lang.String | เส้นทางไฟล์ของเวิร์กบุ๊กที่มีแผนภูมิ |
| worksheetName | java.lang.String | ชื่อแผ่นงานที่มีแผนภูมิ |
| chartName | java.lang.String | ชื่อของแผนภูมิที่จะเพิ่ม |
| embedWorkbook | boolean | หากเป็น true เวิร์กบุ๊กจะฝังอยู่ในแผนภูมิ; หากเป็น false แผนภูมิจะลิงก์ไปยังเวิร์กบุ๊กภายนอก |

**คืนค่า:**  
[IChart](../../com.aspose.slides/ichart) - แผนภูมิที่ถูกเพิ่มเข้าไปในคอลเลกชันรูปทรง

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)
```

ดึงตารางจากไฟล์เวิร์กบุ๊ก Excel ที่ระบุและเพิ่มเข้าไปในส่วนท้ายของคอลเลกชันรูปทรงที่กำหนดที่พิกัดที่ระบุ

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

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | คอลเลกชันรูปทรงที่ตารางจะถูกเพิ่มเข้าไป |
| x | float | พิกัด X สำหรับกำหนดตำแหน่งของตาราง |
| y | float | พิกัด Y สำหรับกำหนดตำแหน่งของตาราง |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | เวิร์กบุ๊ก Excel |
| worksheetName | java.lang.String | ชื่อแผ่นงานที่มีตาราง |
| cellRange | java.lang.String | ช่วงเซลล์ที่กำหนดตาราง (เช่น “A1:D10”) |

**คืนค่า:**  
[ITable](../../com.aspose.slides/itable) - ตารางที่ถูกเพิ่มเข้าไปในคอลเลกชันรูปทรง

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)
```

ดึงตารางจากไฟล์เวิร์กบุ๊ก Excel ที่ระบุและเพิ่มเข้าไปในส่วนท้ายของคอลเลกชันรูปทรงที่กำหนดที่พิกัดที่ระบุ

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

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | คอลเลกชันรูปทรงที่ตารางจะถูกเพิ่มเข้าไป |
| x | float | พิกัด X สำหรับกำหนดตำแหน่งของตาราง |
| y | float | พิกัด Y สำหรับกำหนดตำแหน่งของตาราง |
| workbookPath | java.lang.String | เส้นทางไฟล์ของเวิร์กบุ๊ก Excel |
| worksheetName | java.lang.String | ชื่อแผ่นงานที่มีตาราง |
| cellRange | java.lang.String | ช่วงเซลล์ที่กำหนดตาราง (เช่น “A1:D10”) |

**คืนค่า:**  
[ITable](../../com.aspose.slides/itable) - ตารางที่ถูกเพิ่มเข้าไปในคอลเลกชันรูปทรง

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)
```

ดึงตารางจากไฟล์เวิร์กบุ๊ก Excel ที่ระบุและเพิ่มเข้าไปในส่วนท้ายของคอลเลกชันรูปทรงที่กำหนดที่พิกัดที่ระบุ

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

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | คอลเลกชันรูปทรงที่ตารางจะถูกเพิ่มเข้าไป |
| x | float | พิกัด X สำหรับกำหนดตำแหน่งของตาราง |
| y | float | พิกัด Y สำหรับกำหนดตำแหน่งของตาราง |
| workbookStream | java.io.InputStream | สตรีมที่มีข้อมูลของเวิร์กบุ๊ก |
| worksheetName | java.lang.String | ชื่อแผ่นงานที่มีตาราง |
| cellRange | java.lang.String | ช่วงเซลล์ที่กำหนดตาราง (เช่น “A1:D10”) |

**คืนค่า:**  
[ITable](../../com.aspose.slides/itable) - ตารางที่ถูกเพิ่มเข้าไปในคอลเลกชันรูปทรง