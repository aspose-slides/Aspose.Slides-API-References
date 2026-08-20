---
title: IExcelDataCell
second_title: Aspose.Slides for Java API Reference
description: تمثل خلية واحدة في مصنف Excel.
type: docs
url: /ar/com.aspose.slides/iexceldatacell/
---```
public interface IExcelDataCell
```

تمثل خلية واحدة في مصنف Excel.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getValue()](#getValue--) | يُحصل على القيمة الموجودة في خلية Excel. |
| [getName()](#getName--) | يُحصل على اسم خلية بيانات المخطط. |
| [getRow()](#getRow--) | يُحصل على الفهرس الصفري للصف في ورقة العمل التي توجد فيها الخلية. |
| [getColumn()](#getColumn--) | يُحصل على الفهرس الصفري للعمود في ورقة العمل التي توجد فيها الخلية. |
### getValue() {#getValue--}
```
public abstract Object getValue()
```

يُحصل على القيمة الموجودة في خلية Excel. للقراءة فقط Object .

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
public abstract String getName()
```

يُحصل على اسم خلية بيانات المخطط. للقراءة فقط String.

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
public abstract int getRow()
```

يُحصل على الفهرس الصفري للصف في ورقة العمل التي توجد فيها الخلية. للقراءة فقط int.

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
public abstract int getColumn()
```

يُحصل على الفهرس الصفري للعمود في ورشة العمل التي توجد فيها الخلية. للقراءة فقط int.

--------------------

> ```
> Example:
>  
> v
> ```

**الإرجاع:**  
int