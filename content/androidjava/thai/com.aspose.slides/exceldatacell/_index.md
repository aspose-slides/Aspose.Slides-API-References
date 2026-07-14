---
title: ExcelDataCell
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงถึงเซลล์เดียวในเวิร์กบุ๊กของ Excel.
type: docs
url: /th/com.aspose.slides/exceldatacell/
---
**การสืบทอด:**  
java.lang.Object

**อินเทอร์เฟซที่ใช้งานทั้งหมด:**  
[com.aspose.slides.IExcelDataCell](../../com.aspose.slides/iexceldatacell)  
```
public class ExcelDataCell implements IExcelDataCell
```

แสดงถึงเซลล์เดียวในเวิร์กบุ๊กของ Excel.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getValue()](#getValue--) | รับค่าที่บรรจุอยู่ในเซลล์ Excel. |
| [getName()](#getName--) | รับชื่อของเซลล์ข้อมูลแผนภูมิ. |
| [getRow()](#getRow--) | รับดัชนีแถวที่เริ่มจากศูนย์ในแผ่นงานที่เซลล์ตั้งอยู่. |
| [getColumn()](#getColumn--) | รับดัชนีคอลัมน์ที่เริ่มจากศูนย์ในแผ่นงานที่เซลล์ตั้งอยู่. |

### getValue() {#getValue--}
```
public final Object getValue()
```

รับค่าที่บรรจุอยู่ในเซลล์ Excel.

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

รับชื่อของเซลล์ข้อมูลแผนภูมิ.

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

รับดัชนีแถวที่เริ่มจากศูนย์ในแผ่นงานที่เซลล์ตั้งอยู่. int อ่านอย่างเดียว.

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

รับดัชนีคอลัมน์ที่เริ่มจากศูนย์ในแผ่นงานที่เซลล์ตั้งอยู่. int อ่านอย่างเดียว.

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