---
title: IExcelDataCell
second_title: Aspose.Slides สำหรับ Java เอกสารอ้างอิง API
description: แสดงเซลล์เดียวในเวิร์กบุ๊กของ Excel.
type: docs
url: /th/com.aspose.slides/iexceldatacell/
---```
public interface IExcelDataCell
```

แสดงเซลล์เดียวในเวิร์กบุ๊กของ Excel.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getValue()](#getValue--) | รับค่าที่อยู่ในเซลล์ Excel. |
| [getName()](#getName--) | รับชื่อของเซลล์ข้อมูลแผนภูมิ. |
| [getRow()](#getRow--) | รับดัชนีที่เริ่มจากศูนย์ของแถวในเวิร์กชีตที่เซลล์ตั้งอยู่. |
| [getColumn()](#getColumn--) | รับดัชนีที่เริ่มจากศูนย์ของคอลัมน์ในเวิร์กชีตที่เซลล์ตั้งอยู่. |
### getValue() {#getValue--}
```
public abstract Object getValue()
```


รับค่าที่อยู่ในเซลล์ Excel. Read-only  Object .

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Returns:**
java.lang.Object
### getName() {#getName--}
```
public abstract String getName()
```


รับชื่อของเซลล์ข้อมูลแผนภูมิ. Read-only String.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //ผลลัพธ์: "B2"
> ```

**Returns:**
java.lang.String
### getRow() {#getRow--}
```
public abstract int getRow()
```


รับดัชนีที่เริ่มจากศูนย์ของแถวในเวิร์กชีตที่เซลล์ตั้งอยู่. Read-only int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getRow()); //ผลลัพธ์: 1
> ```

**Returns:**
int
### getColumn() {#getColumn--}
```
public abstract int getColumn()
```


รับดัชนีที่เริ่มจากศูนย์ของคอลัมน์ในเวิร์กชีตที่เซลล์ตั้งอยู่. Read-only int.

--------------------

> ```
> Example:
>  
> v
> ```

**Returns:**
int