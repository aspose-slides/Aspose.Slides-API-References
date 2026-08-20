---
title: IExcelDataWorkbook
second_title: Aspose.Slides for Java API Reference
description: Represents a workbook that provides access to Excel data for general use.
type: docs
url: /th/com.aspose.slides/iexceldataworkbook/
---```
public interface IExcelDataWorkbook
```

เป็นเวิร์กบุ๊กที่ให้การเข้าถึงข้อมูล Excel สำหรับการใช้งานทั่วไป.
## เมธอด

| Method | Description |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | ดึงคอลเล็กชันของเซลล์จากเวิร์กบุ๊กที่ตรงกับสูตรที่ระบุ |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | ดึงเซลล์จากเวิร์กชีตที่ระบุโดยใช้ดัชนีและพิกัดของเซลล์ |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | ดึงเซลล์จากเวิร์กชีตที่ระบุโดยใช้ชื่อและพิกัดของเซลล์ |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | ดึงเซลล์จากเวิร์กชีตที่ระบุโดยใช้ดัชนีและชื่อเซลล์แบบ Excel (เช่น "B2") |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | ดึงเซลล์จากเวิร์กชีตที่ระบุโดยใช้ชื่อเซลล์แบบ Excel (เช่น "B2") |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | ดึงพจนานุกรมที่ประกอบด้วยดัชนีและชื่อของแผนภูมิทั้งหมดในเวิร์กชีตที่ระบุของเวิร์กบุ๊ก Excel |
| [getWorksheetNames()](#getWorksheetNames--) | ดึงชื่อของเวิร์กชีตทั้งหมดที่อยู่ในเวิร์กบุ๊ก Excel |

### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public abstract System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```

ดึงคอลเล็กชันของเซลล์จากเวิร์กบุ๊กที่ตรงกับสูตรที่ระบุ

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //ผลลัพธ์: 5
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| formula | java.lang.String | สูตรหรือช่วง (เช่น "Sheet1!A1:B3") ที่ใช้ระบุเซลล์เป้าหมาย |
| skipHiddenCells | boolean | หากเป็น true เซลล์ที่ซ่อนอยู่ (เช่น ในแถวหรือคอลัมน์ที่ซ่อน) จะไม่รวมในผลลัพธ์ |

**ค่าที่คืน:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - รายการอ่านอย่างเดียวของเซลล์ที่ตรงกับสูตรที่ระบุ

### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, int row, int column)
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
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | ดัชนีของเวิร์กชีต (เริ่มจาก 0) |
| row | int | ดัชนีแถวของเซลล์ (เริ่มจาก 0) |
| column | int | ดัชนีคอลัมน์ของเซลล์ (เริ่มจาก 0) |

**ค่าที่คืน:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - เซลล์ที่ตำแหน่งที่ระบุ

### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IExcelDataCell getCell(String worksheetName, int row, int column)
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
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | java.lang.String | ชื่อของเวิร์กชีต |
| row | int | ดัชนีแถวของเซลล์ (เริ่มจาก 0) |
| column | int | ดัชนีคอลัมน์ของเซลล์ (เริ่มจาก 0) |

**ค่าที่คืน:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - เซลล์ที่ตำแหน่งที่ระบุ

### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, String cellName)
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
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | ดัชนีของเวิร์กชีต (เริ่มจาก 0) |
| cellName | java.lang.String | การอ้างอิงเซลล์แบบ Excel (เช่น "A1", "C5") |

**ค่าที่คืน:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - เซลล์ที่ตำแหน่งที่ระบุ

### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public abstract IExcelDataCell getCell(String worksheetName, String cellName)
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
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | java.lang.String | ชื่อของเวิร์กชีต |
| cellName | java.lang.String | การอ้างอิงเซลล์แบบ Excel (เช่น "A1", "C5") |

**ค่าที่คืน:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - เซลล์ที่ตำแหน่งที่ระบุ

### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public abstract System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```

ดึงพจนานุกรมที่ประกอบด้วยดัชนีและชื่อของแผนภูมิทั้งหมดในเวิร์กชีตที่ระบุของเวิร์กบุ๊ก Excel

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
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | java.lang.String | ชื่อของเวิร์กชีตที่ต้องการค้นหาแผนภูมิ |

**ค่าที่คืน:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - พจนานุกรมที่คีย์เป็นดัชนีของแผนภูมิและค่าคือชื่อแผนภูมิ

### getWorksheetNames() {#getWorksheetNames--}
```
public abstract System.Collections.Generic.List<String> getWorksheetNames()
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

**ค่าที่คืน:**
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - รายการของชื่อเวิร์กชีต