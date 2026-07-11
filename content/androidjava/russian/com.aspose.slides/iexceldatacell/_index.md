---
title: IExcelDataCell
second_title: Aspose.Slides for Android via Java API Reference
description: Представляет отдельную ячейку в рабочей книге Excel.
type: docs
url: /ru/com.aspose.slides/iexceldatacell/
---```
public interface IExcelDataCell
```

Представляет отдельную ячейку в рабочей книге Excel.
## Методы

| Метод | Описание |
| --- | --- |
| [getValue()](#getValue--) | Возвращает значение, содержащееся в ячейке Excel. |
| [getName()](#getName--) | Возвращает имя ячейки данных диаграммы. |
| [getRow()](#getRow--) | Возвращает нулевой индекс строки в листе, где находится ячейка. |
| [getColumn()](#getColumn--) | Возвращает нулевой индекс столбца в листе, где находится ячейка. |
### getValue() {#getValue--}
```
public abstract Object getValue()
```

Возвращает значение, содержащееся в ячейке Excel. Только для чтения  Object .

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Возвращает:**
java.lang.Object
### getName() {#getName--}
```
public abstract String getName()
```

Возвращает имя ячейки данных диаграммы. Только для чтения String.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //Вывод: "B2"
> ```

**Возвращает:**
java.lang.String
### getRow() {#getRow--}
```
public abstract int getRow()
```

Возвращает нулевой индекс строки в листе, где находится ячейка. Только для чтения int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getRow()); //Вывод: 1
> ```

**Возвращает:**
int
### getColumn() {#getColumn--}
```
public abstract int getColumn()
```

Возвращает нулевой индекс столбца в листе, где находится ячейка. Только для чтения int.

--------------------

> ```
> Example:
>  
> v
> ```

**Возвращает:**
int