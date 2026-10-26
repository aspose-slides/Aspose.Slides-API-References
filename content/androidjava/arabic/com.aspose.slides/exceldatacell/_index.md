---
title: ExcelDataCell
second_title: Aspose.Slides لنظام Android عبر مرجع API Java
description: يمثل خلية واحدة في مصنف Excel.
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

يمثل خلية واحدة في مصنف Excel.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getValue()](#getValue--) | يحصل على القيمة الموجودة في خلية Excel. |
| [getName()](#getName--) | يحصل على اسم خلية بيانات المخطط. |
| [getRow()](#getRow--) | يحصل على الفهرس الصفري للصف في ورقة العمل حيث تقع الخلية. |
| [getColumn()](#getColumn--) | يحصل على الفهرس الصفري للعمود في ورقة العمل حيث توجد الخلية. |
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

**القيمة المرجعة:**
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

**القيمة المرجعة:**
java.lang.String
### getRow() {#getRow--}
```
public final int getRow()
```

يحصل على الفهرس الصفري للصف في ورقة العمل حيث تقع الخلية. قابل للقراءة فقط int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getRow()); //الإخراج: 1
> ```

**القيمة المرجعة:**
int
### getColumn() {#getColumn--}
```
public final int getColumn()
```

يحصل على الفهرس الصفري للعمود في ورقة العمل حيث توجد الخلية. قابل للقراءة فقط int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getColumn()); //الإخراج: 1
> ```

**القيمة المرجعة:**
int