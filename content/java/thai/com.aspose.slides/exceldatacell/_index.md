---
title: ExcelDataCell
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงถึงเซลล์เดียวในเวิร์กบุ๊ก Excel.
type: docs
url: /th/com.aspose.slides/exceldatacell/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.IExcelDataCell](../../com.aspose.slides/iexceldatacell)
```
public class ExcelDataCell implements IExcelDataCell
```

แสดงถึงเซลล์เดียวในเวิร์กบุ๊ก Excel.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getValue()](#getValue--) | ดึงค่าที่อยู่ในเซลล์ Excel. |
| [getName()](#getName--) | ดึงชื่อของเซลล์ข้อมูลแผนภูมิ. |
| [getRow()](#getRow--) | ดึงดัชนีอ้างอิงศูนย์ของแถวในเวิร์กชีตที่เซลล์ตั้งอยู่. |
| [getColumn()](#getColumn--) | ดึงดัชนีอ้างอิงศูนย์ของคอลัมน์ในเวิร์กชีตที่เซลล์ตั้งอยู่. |
### getValue() {#getValue--}
```
public final Object getValue()
```


ดึงค่าที่อยู่ในเซลล์ Excel.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**คืนค่า:**
java.lang.Object
### getName() {#getName--}
```
public final String getName()
```


ดึงชื่อของเซลล์ข้อมูลแผนภูมิ.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //ผลลัพธ์: "B2"
> ```

**คืนค่า:**
java.lang.String
### getRow() {#getRow--}
```
public final int getRow()
```


ดึงดัชนีอ้างอิงศูนย์ของแถวในเวิร์กชีตที่เซลล์ตั้งอยู่. อ่านอย่างเดียว int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getRow()); //ผลลัพธ์: 1
> ```

**คืนค่า:**
int
### getColumn() {#getColumn--}
```
public final int getColumn()
```


ดึงดัชนีอ้างอิงศูนย์ของคอลัมน์ในเวิร์กชีตที่เซลล์ตั้งอยู่. อ่านอย่างเดียว int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getColumn()); //ผลลัพธ์: 1
> ```


**คืนค่า:**
int