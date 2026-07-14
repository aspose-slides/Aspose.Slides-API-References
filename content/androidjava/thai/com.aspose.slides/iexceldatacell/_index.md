---
title: IExcelDataCell
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: เป็นตัวแทนของเซลล์เดียวในเวิร์กบุ๊กของ Excel.
type: docs
url: /th/com.aspose.slides/iexceldatacell/
---```
public interface IExcelDataCell
```

เป็นตัวแทนของเซลล์เดียวในเวิร์กบุ๊กของ Excel.
## วิธีการ

| วิธีการ | คำอธิบาย |
| --- | --- |
| [getValue()](#getValue--) | รับค่าที่อยู่ในเซลล์ Excel |
| [getName()](#getName--) | รับชื่อของเซลล์ข้อมูลแผนภูมิ |
| [getRow()](#getRow--) | รับดัชนีเริ่มศูนย์ของแถวในแผ่นงานที่เซลล์ตั้งอยู่ |
| [getColumn()](#getColumn--) | รับดัชนีเริ่มศูนย์ของคอลัมน์ในแผ่นงานที่เซลล์ตั้งอยู่ |
### getValue() {#getValue--}
```
public abstract Object getValue()
```

รับค่าที่อยู่ในเซลล์ Excel. อ่านอย่างเดียว  Object .

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```


**ผลลัพธ์:**
java.lang.Object
### getName() {#getName--}
```
public abstract String getName()
```

รับชื่อของเซลล์ข้อมูลแผนภูมิ. อ่านอย่างเดียว String.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //ผลลัพธ์: "B2"
> ```

**ผลลัพธ์:**
java.lang.String
### getRow() {#getRow--}
```
public abstract int getRow()
```

รับดัชนีเริ่มศูนย์ของแถวในแผ่นงานที่เซลล์ตั้งอยู่. อ่านอย่างเดียว int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getRow()); //ผลลัพธ์: 1
> ```


**ผลลัพธ์:**
int
### getColumn() {#getColumn--}
```
public abstract int getColumn()
```

รับดัชนีเริ่มศูนย์ของคอลัมน์ในแผ่นงานที่เซลล์ตั้งอยู่. อ่านอย่างเดียว int.

--------------------

> ```
> Example:
>  
> v
> ```

**ผลลัพธ์:**
int