---
title: IExcelDataCell
second_title: Aspose.Slides for Java API Reference
description: Представляет одну ячейку в рабочей книге Excel.
type: docs
url: /ru/com.aspose.slides/iexceldatacell/
---```
public interface IExcelDataCell
```

Представляет одну ячейку в рабочей книге Excel.
## Методы

| Метод | Описание |
| --- | --- |
| [getValue()](#getValue--) | Получает значение, содержащееся в ячейке Excel. |
| [getName()](#getName--) | Получает имя ячейки данных диаграммы. |
| [getRow()](#getRow--) | Получает нулевой индекс строки в листе, где расположена ячейка. |
| [getColumn()](#getColumn--) | Получает нулевой индекс столбца в листе, где расположена ячейка. |
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Получает значение, содержащееся в ячейке Excel. **Только для чтения**  Object .

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


Получает имя ячейки данных диаграммы. **Только для чтения** String.

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


Получает нулевой индекс строки в листе, где расположена ячейка. **Только для чтения** int.

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


Получает нулевой индекс столбца в листе, где расположена ячейка. **Только для чтения** int.

--------------------

> ```
> Example:
>  
> v
> ```

**Возвращает:**
int