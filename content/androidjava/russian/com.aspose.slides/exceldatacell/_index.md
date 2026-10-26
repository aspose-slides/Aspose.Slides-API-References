---
title: ExcelDataCell
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет одну ячейку в книге Excel.
type: docs
url: /ru/com.aspose.slides/exceldatacell/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IExcelDataCell](../../com.aspose.slides/iexceldatacell)
```
public class ExcelDataCell implements IExcelDataCell
```

Представляет одну ячейку в книге Excel.
## Методы

| Метод | Описание |
| --- | --- |
| [getValue()](#getValue--) | Получает значение, содержащееся в ячейке Excel. |
| [getName()](#getName--) | Получает имя ячейки данных диаграммы. |
| [getRow()](#getRow--) | Получает нулевой индекс строки в листе, где расположена ячейка. |
| [getColumn()](#getColumn--) | Получает нулевой индекс столбца в листе, где расположена ячейка. |
### getValue() {#getValue--}
```
public final Object getValue()
```

Получает значение, содержащееся в ячейке Excel.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Возвращаемое значение:**
java.lang.Object
### getName() {#getName--}
```
public final String getName()
```

Получает имя ячейки данных диаграммы.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //Вывод: "B2"
> ```

**Возвращаемое значение:**
java.lang.String
### getRow() {#getRow--}
```
public final int getRow()
```

Получает нулевой индекс строки в листе, где расположена ячейка. Только для чтения int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getRow()); //Вывод: 1
> ```

**Возвращаемое значение:**
int
### getColumn() {#getColumn--}
```
public final int getColumn()
```

Получает нулевой индекс столбца в листе, где расположена ячейка. Только для чтения int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getColumn()); //Вывод: 1
> ```

**Возвращаемое значение:**
int