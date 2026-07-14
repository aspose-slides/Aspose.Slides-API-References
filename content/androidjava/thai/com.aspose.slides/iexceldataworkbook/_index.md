---
title: IExcelDataWorkbook
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงถึงเวิร์กบุ๊กที่ให้การเข้าถึงข้อมูล Excel สำหรับการใช้ทั่วไป.
type: docs
url: /th/com.aspose.slides/iexceldataworkbook/
---```
public interface IExcelDataWorkbook
```

แสดงถึงเวิร์กบุ๊กที่ให้การเข้าถึงข้อมูล Excel สำหรับการใช้ทั่วไป.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | ดึงคอลเลกชันของเซลล์จากเวิร์กบุ๊กที่ตรงกับสูตรที่ระบุ |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | ดึงเซลล์จากเวิร์กชีตที่ระบุโดยใช้ดัชนีและพิกัดของเซลล์ |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | ดึงเซลล์จากเวิร์กชีตที่ระบุโดยใช้ชื่อและพิกัดของเซลล์ |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | ดึงเซลล์จากเวิร์กชีตที่ระบุโดยใช้ดัชนีและชื่อเซลล์แบบ Excel (เช่น "B2") |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | ดึงเซลล์จากเวิร์กชีตที่ระบุโดยใช้ชื่อเซลล์แบบ Excel (เช่น "B2") |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | ดึงพจนานุกรมที่มีดัชนีและชื่อของแผนภูมิทั้งหมดในเวิร์กชีตที่ระบุของเวิร์กบุ๊ก Excel |
| [getWorksheetNames()](#getWorksheetNames--) | ดึงชื่อของเวิร์กชีตทั้งหมดที่อยู่ในเวิร์กบุ๊ก Excel |
### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public abstract System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```


ดึงคอลเลกชันของเซลล์จากเวิร์กบุ๊กที่ตรงกับสูตรที่ระบุ.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //ผลลัพธ์: 5
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| formula | java.lang.String | สูตรหรือการแสดงช่วง (เช่น "Sheet1!A1:B3") ที่ใช้ในการระบุเซลล์เป้าหมาย |
| skipHiddenCells | boolean | หากเป็นจริง เซลล์ที่ซ่อนอยู่ (เช่น แถวหรือคอลัมน์ที่ซ่อน) จะถูกยกเว้นจากผลลัพธ์ |

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - รายการเซลล์แบบอ่านอย่างเดียวที่ตรงกับสูตรที่ระบุ
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, int row, int column)
```


ดึงเซลล์จากเวิร์กชีตที่ระบุโดยใช้ดัชนีและพิกัดของเซลล์.

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
| worksheetIndex | int | ดัชนีของเวิร์กชีตที่เริ่มจากศูนย์ |
| row | int | ดัชนีแถวของเซลล์ที่เริ่มจากศูนย์ |
| column | int | ดัชนีคอลัมน์ของเซลล์ที่เริ่มจากศูนย์ |

**คืนค่า:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - เซลล์ที่ตำแหน่งที่ระบุ
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IExcelDataCell getCell(String worksheetName, int row, int column)
```


ดึงเซลล์จากเวิร์กชีตที่ระบุโดยใช้ชื่อและพิกัดของเซลล์.

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
| row | int | ดัชนีแถวของเซลล์ที่เริ่มจากศูนย์ |
| column | int | ดัชนีคอลัมน์ของเซลล์ที่เริ่มจากศูนย์ |

**คืนค่า:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - เซลล์ที่ตำแหน่งที่ระบุ
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, String cellName)
```


ดึงเซลล์จากเวิร์กชีตที่ระบุโดยใช้ดัชนีและชื่อเซลล์แบบ Excel (เช่น "B2").

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
| worksheetIndex | int | ดัชนีของเวิร์กชีตที่เริ่มจากศูนย์ |
| cellName | java.lang.String | อ้างอิงเซลล์แบบ Excel (เช่น "A1", "C5") |

**คืนค่า:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - เซลล์ที่ตำแหน่งที่ระบุ
### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public abstract IExcelDataCell getCell(String worksheetName, String cellName)
```


ดึงเซลล์จากเวิร์กชีตที่ระบุโดยใช้ชื่อเซลล์แบบ Excel (เช่น "B2").

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

**คืนค่า:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - เซลล์ที่ตำแหน่งที่ระบุ
### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public abstract System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```


ดึงพจนานุกรมที่มีดัชนีและชื่อของแผนภูมิทั้งหมดในเวิร์กชีตที่ระบุของเวิร์กบุ๊ก Excel.

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
| worksheetName | java.lang.String | ชื่อของเวิร์กชีตเพื่อค้นหาแผนภูมิ |

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - พจนานุกรมที่คีย์เป็นดัชนีของแผนภูมิและค่คือชื่อของแผนภูมิ
### getWorksheetNames() {#getWorksheetNames--}
```
public abstract System.Collections.Generic.List<String> getWorksheetNames()
```


ดึงชื่อของเวิร์กชีตทั้งหมดที่อยู่ในเวิร์กบุ๊ก Excel.

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<String> sheetNames = wb.getWorksheetNames();
>  for (String name : sheetNames)
>      System.out.println(name);
> ```

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - รายการชื่อเวิร์กชีต