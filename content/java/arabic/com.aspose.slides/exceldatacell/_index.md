---
title: ExcelDataCell
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل خلية واحدة في دفتر عمل Excel.
type: docs
url: /ar/com.aspose.slides/exceldatacell/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IExcelDataCell](../../com.aspose.slides/iexceldatacell)
```
public class ExcelDataCell implements IExcelDataCell
```

يمثل خلية واحدة في دفتر عمل Excel.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getValue()](#getValue--) | يحصل على القيمة الموجودة في خلية Excel. |
| [getName()](#getName--) | يحصل على اسم خلية بيانات المخطط. |
| [getRow()](#getRow--) | يحصل على الفهرس صفر-الأساس للصف في ورقة العمل حيث توجد الخلية. |
| [getColumn()](#getColumn--) | يحصل على الفهرس صفر-الأساس للعمود في ورقة العمل حيث توجد الخلية. |
### getValue() {#getValue--}
```
public final Object getValue()
```

يحصل على القيمة الموجودة في خلية Excel.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**الإرجاع:**
java.lang.Object
### getName() {#getName--}
```
public final String getName()
```

يحصل على اسم خلية بيانات المخطط.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //الإخراج: "B2"
> ```

**الإرجاع:**
java.lang.String
### getRow() {#getRow--}
```
public final int getRow()
```

يحصل على الفهرس صفر-الأساس للصف في ورقة العمل حيث توجد الخلية. int للقراءة فقط.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getRow()); //الإخراج: 1
> ```

**الإرجاع:**
int
### getColumn() {#getColumn--}
```
public final int getColumn()
```

يحصل على الفهرس صفر-الأساس للعمود في ورقة العمل حيث توجد الخلية. int للقراءة فقط.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getColumn()); //الإخراج: 1
> ```

**الإرجاع:**
int