---
title: ExcelDataWorkbook
second_title: Aspose.Slides สำหรับ Java เอกสารอ้างอิง API
description: เป็นตัวแทนของ workbook ที่ให้การเข้าถึงข้อมูล Excel เพื่อการใช้ทั่วไป.
type: docs
url: /th/com.aspose.slides/exceldataworkbook/
---
**การสืบทอด:**  
java.lang.Object

**ส่วนต่อประสานที่ทำทั้งหมด:**  
[com.aspose.slides.IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook)  
```
public class ExcelDataWorkbook implements IExcelDataWorkbook
```

แสดงถึง workbook ที่ให้การเข้าถึงข้อมูล Excel เพื่อการใช้ทั่วไป.

## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [ExcelDataWorkbook(String filePath)](#ExcelDataWorkbook-java.lang.String-) | สร้างอินสแตนซ์ใหม่โดยใช้เส้นทางไฟล์ที่ระบุ. |
| [ExcelDataWorkbook(InputStream stream)](#ExcelDataWorkbook-java.io.InputStream-) | สร้างอินสแตนซ์ใหม่ของคลาสโดยใช้สตรีมที่ให้มา. |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | ดึงคอลเลกชันของเซลล์จาก workbook ที่ตรงกับสูตรที่ระบุ. |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | ดึงเซลล์จากแผ่นงานที่ระบุโดยใช้ดัชนีและพิกัดของเซลล์. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | ดึงเซลล์จากแผ่นงานที่ระบุโดยใช้ชื่อและพิกัดของเซลล์. |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | ดึงเซลล์จากแผ่นงานที่ระบุโดยใช้ดัชนีและชื่อเซลล์แบบ Excel (เช่น "B2"). |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | ดึงเซลล์จากแผ่นงานที่ระบุโดยใช้ชื่อเซลล์แบบ Excel (เช่น "B2"). |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | ดึงพจนานุกรมที่บรรจุดัชนีและชื่อของแผนภูมิทั้งหมดในแผ่นงานที่ระบุของ Excel workbook. |
| [getWorksheetNames()](#getWorksheetNames--) | ดึงชื่อของแผ่นงานทั้งหมดที่อยู่ใน Excel workbook. |

### ExcelDataWorkbook(String filePath) {#ExcelDataWorkbook-java.lang.String-}
```
public ExcelDataWorkbook(String filePath)
```

สร้างอินสแตนซ์ใหม่โดยใช้เส้นทางไฟล์ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| filePath | java.lang.String | เส้นทางเต็มไปยังไฟล์ Excel workbook. |

### ExcelDataWorkbook(InputStream stream) {#ExcelDataWorkbook-java.io.InputStream-}
```
public ExcelDataWorkbook(InputStream stream)
```

สร้างอินสแตนซ์ใหม่ของคลาสโดยใช้สตรีมที่ให้มา.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.InputStream | สตรีมที่บรรจุข้อมูลของ Excel workbook. |

### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public final System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```

ดึงคอลเลกชันของเซลล์จาก workbook ที่ตรงกับสูตรที่ระบุ.

--------------------

> ```
> ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //ผลลัพธ์: 5
>  ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| formula | java.lang.String | สูตรหรือการแสดงช่วง (เช่น "Sheet1!A1:B3") ที่ใช้ระบุเซลล์เป้าหมาย. |
| skipHiddenCells | boolean | ถ้าเป็นจริง เซลล์ที่ซ่อนอยู่ (เช่น ในแถวหรือคอลัมน์ที่ซ่อน) จะถูกตัดออกจากผลลัพธ์. |

**ผลลัพธ์:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - รายการเซลล์แบบอ่านอย่างเดียวที่ตรงกับสูตรที่ระบุ.

### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IExcelDataCell getCell(int worksheetIndex, int row, int column)
```

ดึงเซลล์จากแผ่นงานที่ระบุโดยใช้ดัชนีและพิกัดของเซลล์.

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
| worksheetIndex | int | ดัชนีเริ่มจากศูนย์ของแผ่นงาน. |
| row | int | ดัชนีแถวเริ่มจากศูนย์ของเซลล์. |
| column | int | ดัชนีคอลัมน์เริ่มจากศูนย์ของเซลล์. |

**ผลลัพธ์:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - เซลล์ที่ตำแหน่งที่ระบุ.

### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IExcelDataCell getCell(String worksheetName, int row, int column)
```

ดึงเซลล์จากแผ่นงานที่ระบุโดยใช้ชื่อและพิกัดของเซลล์.

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
| worksheetName | java.lang.String | ชื่อของแผ่นงาน. |
| row | int | ดัชนีแถวเริ่มจากศูนย์ของเซลล์. |
| column | int | ดัชนีคอลัมน์เริ่มจากศูนย์ของเซลล์. |

**ผลลัพธ์:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - เซลล์ที่ตำแหน่งที่ระบุ.

### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IExcelDataCell getCell(int worksheetIndex, String cellName)
```

ดึงเซลล์จากแผ่นงานที่ระบุโดยใช้ดัชนีและชื่อเซลล์แบบ Excel (เช่น "B2").

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
| worksheetIndex | int | ดัชนีเริ่มจากศูนย์ของแผ่นงาน. |
| cellName | java.lang.String | อ้างอิงเซลล์แบบ Excel (เช่น "A1", "C5"). |

**ผลลัพธ์:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - เซลล์ที่ตำแหน่งที่ระบุ.

### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public final IExcelDataCell getCell(String worksheetName, String cellName)
```

ดึงเซลล์จากแผ่นงานที่ระบุโดยใช้ชื่อเซลล์แบบ Excel (เช่น "B2").

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
| worksheetName | java.lang.String | ชื่อของแผ่นงาน. |
| cellName | java.lang.String | อ้างอิงเซลล์แบบ Excel (เช่น "A1", "C5"). |

**ผลลัพธ์:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - เซลล์ที่ตำแหน่งที่ระบุ.

### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public final System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```

ดึงพจนานุกรมที่บรรจุดัชนีและชื่อของแผนภูมิทั้งหมดในแผ่นงานที่ระบุของ Excel workbook.

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
| worksheetName | java.lang.String | ชื่อของแผ่นงานที่ต้องการค้นหาแผนภูมิ. |

**ผลลัพธ์:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - พจนานุกรมที่มีคีย์เป็นดัชนีแผนภูมิและค่เป็นชื่อแผนภูมิ.

### getWorksheetNames() {#getWorksheetNames--}
```
public final System.Collections.Generic.List<String> getWorksheetNames()
```

ดึงชื่อของแผ่นงานทั้งหมดที่อยู่ใน Excel workbook.

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
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - รายการชื่อแผ่นงาน