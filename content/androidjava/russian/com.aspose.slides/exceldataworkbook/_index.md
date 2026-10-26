---
title: ExcelDataWorkbook
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет рабочую книгу, предоставляющую доступ к данным Excel для общего использования.
type: docs
url: /ru/com.aspose.slides/exceldataworkbook/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook)
```
public class ExcelDataWorkbook implements IExcelDataWorkbook
```

Представляет рабочую книгу, предоставляющую доступ к данным Excel для общего использования.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ExcelDataWorkbook(String filePath)](#ExcelDataWorkbook-java.lang.String-) | Инициализирует новый экземпляр, используя указанный путь к файлу. |
| [ExcelDataWorkbook(InputStream stream)](#ExcelDataWorkbook-java.io.InputStream-) | Инициализирует новый экземпляр класса, используя предоставленный поток. |
## Методы

| Метод | Описание |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | Получает коллекцию ячеек из рабочей книги, соответствующих указанной формуле. |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Получает ячейку из указанного листа по её индексу и координатам ячейки. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Получает ячейку из указанного листа по её имени и координатам ячейки. |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Получает ячейку из указанного листа по её индексу и имени ячейки в стиле Excel (например, "B2"). |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | Получает ячейку из указанного листа по имени ячейки в стиле Excel (например, "B2"). |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | Получает словарь, содержащий индексы и имена всех диаграмм в указанном листе рабочей книги Excel. |
| [getWorksheetNames()](#getWorksheetNames--) | Получает имена всех листов, содержащихся в рабочей книге Excel. |
### ExcelDataWorkbook(String filePath) {#ExcelDataWorkbook-java.lang.String-}
```
public ExcelDataWorkbook(String filePath)
```

Инициализирует новый экземпляр, используя указанный путь к файлу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Полный путь к файлу рабочей книги Excel. |

### ExcelDataWorkbook(InputStream stream) {#ExcelDataWorkbook-java.io.InputStream-}
```
public ExcelDataWorkbook(InputStream stream)
```

Инициализирует новый экземпляр класса, используя предоставленный поток.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, содержащий данные рабочей книги Excel. |

### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public final System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```

Получает коллекцию ячеек из рабочей книги, соответствующих указанной формуле.

--------------------

> ```
> ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //Вывод: 5
>  ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| formula | java.lang.String | Формула или выражение диапазона (например, "Sheet1!A1:B3"), используемое для идентификации целевых ячеек. |
| skipHiddenCells | boolean | Если true, скрытые ячейки (например, в скрытых строках или столбцах) будут исключены из результата. |

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - Список только для чтения ячеек, соответствующих указанной формуле.
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IExcelDataCell getCell(int worksheetIndex, int row, int column)
```

Получает ячейку из указанного листа по её индексу и координатам ячейки.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheetIndex | int | Индекс листа, начинающийся с нуля. |
| row | int | Индекс строки ячейки, начинающийся с нуля. |
| column | int | Индекс столбца ячейки, начинающийся с нуля. |

**Возвращаемое значение:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Ячейка в указанном месте.
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IExcelDataCell getCell(String worksheetName, int row, int column)
```

Получает ячейку из указанного листа по её имени и координатам ячейки.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheetName | java.lang.String | Имя листа. |
| row | int | Индекс строки ячейки, начинающийся с нуля. |
| column | int | Индекс столбца ячейки, начинающийся с нуля. |

**Возвращаемое значение:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Ячейка в указанном месте.
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IExcelDataCell getCell(int worksheetIndex, String cellName)
```

Получает ячейку из указанного листа по её индексу и имени ячейки в стиле Excel (например, "B2").

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, "B2");
>  System.out.println(cell.getValue().toString());
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheetIndex | int | Индекс листа, начинающийся с нуля. |
| cellName | java.lang.String | Ссылка на ячейку в стиле Excel (например, "A1", "C5"). |

**Возвращаемое значение:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Ячейка в указанном месте.
### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public final IExcelDataCell getCell(String worksheetName, String cellName)
```

Получает ячейку из указанного листа по имени ячейки в стиле Excel (например, "B2").

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", "B2");
>  System.out.println(cell.getValue().toString());
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheetName | java.lang.String | Имя листа. |
| cellName | java.lang.String | Ссылка на ячейку в стиле Excel (например, "A1", "C5"). |

**Возвращаемое значение:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Ячейка в указанном месте.
### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public final System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```

Получает словарь, содержащий индексы и имена всех диаграмм в указанном листе рабочей книги Excel.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  Dictionary.Enumerator<Integer, String> sheetCharts = wb.getChartsFromWorksheet("worksheetName").iterator();
>  while (sheetCharts.hasNext())
>  {
>      KeyValuePair<Integer, String> chart = sheetCharts.next();
>      System.out.println(chart.getKey() + " : " + chart.getValue());
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheetName | java.lang.String | Имя листа, в котором искать диаграммы. |

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - Словарь, где ключ — индекс диаграммы, а значение — имя диаграммы.
### getWorksheetNames() {#getWorksheetNames--}
```
public final System.Collections.Generic.List<String> getWorksheetNames()
```

Получает имена всех листов, содержащихся в рабочей книге Excel.

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<String> sheetNames = wb.getWorksheetNames();
>  for (String name : sheetNames)
>      System.out.println(name);
> ```


**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - Список имён листов