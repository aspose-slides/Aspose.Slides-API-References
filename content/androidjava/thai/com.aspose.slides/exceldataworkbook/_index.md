---
title: ExcelDataWorkbook
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: เป็นเวิร์กบุ๊กที่ให้การเข้าถึงข้อมูล Excel เพื่อการใช้งานทั่วไป
type: docs
url: /th/com.aspose.slides/exceldataworkbook/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook)
```
public class ExcelDataWorkbook implements IExcelDataWorkbook
```

เป็นเวิร์กบุ๊กที่ให้การเข้าถึงข้อมูล Excel เพื่อการใช้งานทั่วไป.
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [ExcelDataWorkbook(String filePath)](#ExcelDataWorkbook-java.lang.String-) | สร้างอินสแตนซ์ใหม่โดยใช้เส้นทางไฟล์ที่ระบุ |
| [ExcelDataWorkbook(InputStream stream)](#ExcelDataWorkbook-java.io.InputStream-) | สร้างอินสแตนซ์ใหม่ของคลาสโดยใช้สตรีมที่ให้มา |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | ดึงชุดของเซลล์จากเวิร์กบุ๊กที่ตรงกับสูตรที่ระบุ |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | ดึงเซลล์จากเวิร์กชีตที่ระบุโดยใช้ดัชนีและพิกัดของเซลล์ |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | ดึงเซลล์จากเวิร์กชีตที่ระบุโดยใช้ชื่อและพิกัดของเซลล์ |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | ดึงเซลล์จากเวิร์กชีตที่ระบุโดยใช้ดัชนีและชื่อเซลล์แบบ Excel (เช่น "B2") |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | ดึงเซลล์จากเวิร์กชีตที่ระบุโดยใช้ชื่อเซลล์แบบ Excel (เช่น "B2") |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | ดึงพจนานุกรมที่มีดัชนีและชื่อของแผนภูมิทั้งหมดในเวิร์กชีตที่ระบุของเวิร์กบุ๊ก Excel |
| [getWorksheetNames()](#getWorksheetNames--) | ดึงชื่อของเวิร์กชีตทั้งหมดที่อยู่ในเวิร์กบุ๊ก Excel |
### ExcelDataWorkbook(String filePath) {#ExcelDataWorkbook-java.lang.String-}
```
public ExcelDataWorkbook(String filePath)
```


สร้างอินสแตนซ์ใหม่โดยใช้เส้นทางไฟล์ที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| filePath | java.lang.String | เส้นทางเต็มไปยังไฟล์เวิร์กบุ๊ก Excel |
### ExcelDataWorkbook(InputStream stream) {#ExcelDataWorkbook-java.io.InputStream-}
```
public ExcelDataWorkbook(InputStream stream)
```


สร้างอินสแตนซ์ใหม่ของคลาสโดยใช้สตรีมที่ให้มา

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.InputStream | สตรีมที่มีข้อมูลของเวิร์กบุ๊ก Excel |
### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public final System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```


ดึงชุดของเซลล์จากเวิร์กบุ๊กที่ตรงกับสูตรที่ระบุ

--------------------

> ```
> ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //Output: 5
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| formula | java.lang.String | สูตรหรือการแสดงช่วง (เช่น "Sheet1!A1:B3") ที่ใช้ระบุเซลล์เป้าหมาย |
| skipHiddenCells | boolean | หากเป็น true เซลล์ที่ซ่อนอยู่ (เช่น แถวหรือคอลัมน์ที่ซ่อน) จะถูกตัดออกจากผลลัพธ์ |

**ผลลัพธ์:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - รายการเซลล์แบบอ่านอย่างเดียวที่ตรงกับสูตรที่ระบุ
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IExcelDataCell getCell(int worksheetIndex, int row, int column)
```


ดึงเซลล์จากเวิร์กชีตที่ระบุโดยใช้ดัชนีและพิกัดของเซลล์

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| worksheetIndex | int | ดัชนีของเวิร์กชีตโดยเริ่มจากศูนย์ |
| row | int | ดัชนีแถวของเซลล์โดยเริ่มจากศูนย์ |
| column | int | ดัชนีคอลัมน์ของเซลล์โดยเริ่มจากศูนย์ |

**ผลลัพธ์:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - เซลล์ที่ตำแหน่งที่ระบุ
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IExcelDataCell getCell(String worksheetName, int row, int column)
```


ดึงเซลล์จากเวิร์กชีตที่ระบุโดยใช้ชื่อและพิกัดของเซลล์

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| worksheetName | java.lang.String | ชื่อของเวิร์กชีต |
| row | int | ดัชนีแถวของเซลล์โดยเริ่มจากศูนย์ |
| column | int | ดัชนีคอลัมน์ของเซลล์โดยเริ่มจากศูนย์ |

**ผลลัพธ์:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - เซลล์ที่ตำแหน่งที่ระบุ
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IExcelDataCell getCell(int worksheetIndex, String cellName)
```


ดึงเซลล์จากเวิร์กชีตที่ระบุโดยใช้ดัชนีและชื่อเซลล์แบบ Excel (เช่น "B2")

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, "B2");
>  System.out.println(cell.getValue().toString());
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| worksheetIndex | int | ดัชนีของเวิร์กชีตโดยเริ่มจากศูนย์ |
| cellName | java.lang.String | อ้างอิงเซลล์แบบ Excel (เช่น "A1", "C5") |

**ผลลัพธ์:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - เซลล์ที่ตำแหน่งที่ระบุ
### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public final IExcelDataCell getCell(String worksheetName, String cellName)
```


ดึงเซลล์จากเวิร์กชีตที่ระบุโดยใช้ชื่อเซลล์แบบ Excel (เช่น "B2")

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", "B2");
>  System.out.println(cell.getValue().toString());
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| worksheetName | java.lang.String | ชื่อของเวิร์กชีต |
| cellName | java.lang.String | อ้างอิงเซลล์แบบ Excel (เช่น "A1", "C5") |

**ผลลัพธ์:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - เซลล์ที่ตำแหน่งที่ระบุ
### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public final System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```


ดึงพจนานุกรมที่มีดัชนีและชื่อของแผนภูมิทั้งหมดในเวิร์กชีตที่ระบุของเวิร์กบุ๊ก Excel

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

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| worksheetName | java.lang.String | ชื่อของเวิร์กชีตที่ค้นหาแผนภูมิ |

**ผลลัพธ์:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - พจนานุกรมที่มีคีย์เป็นดัชนีของแผนภูมิและค่าเป็นชื่อของแผนภูมิ
### getWorksheetNames() {#getWorksheetNames--}
```
public final System.Collections.Generic.List<String> getWorksheetNames()
```


ดึงชื่อของเวิร์กชีตทั้งหมดที่อยู่ในเวิร์กบุ๊ก Excel

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<String> sheetNames = wb.getWorksheetNames();
>  for (String name : sheetNames)
>      System.out.println(name);
> ```

**ผลลัพธ์:**
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - รายการชื่อเวิร์กชีต