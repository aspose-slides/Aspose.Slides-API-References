---
title: ExcelWorkbookImporter
second_title: Aspose.Slides для Android через справочник Java API
description: Обеспечивает возможность импорта содержимого из рабочей книги Excel в презентацию.
type: docs
url: /ru/com.aspose.slides/excelworkbookimporter/
---
**Наследование:**
java.lang.Object
```
public class ExcelWorkbookImporter
```

Предоставляет функциональность для импорта содержимого из рабочей книги Excel в презентацию.
## Methods

| Метод | Описание |
| --- | --- |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-) | Извлекает диаграмму из указанной рабочей книги Excel и добавляет её в конец заданной коллекции фигур по указанным координатам. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-) | Извлекает диаграмму из указанной рабочей книги Excel и добавляет её в конец заданной коллекции фигур по указанным координатам. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-) | Извлекает диаграмму из указанной рабочей книги Excel и добавляет её в конец заданной коллекции фигур по указанным координатам. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-) | Извлекает диаграмму из указанной рабочей книги Excel и добавляет её в конец заданной коллекции фигур по указанным координатам. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-) | Извлекает таблицу из указанной рабочей книги Excel и добавляет её в конец заданной коллекции фигур по указанным координатам. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-) | Извлекает таблицу из указанной рабочей книги Excel и добавляет её в конец заданной коллекции фигур по указанным координатам. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-) | Извлекает таблицу из указанной рабочей книги Excel и добавляет её в конец заданной коллекции фигур по указанным координатам. |
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)
```

Извлекает диаграмму из указанной рабочей книги Excel и добавляет её в конец заданной коллекции фигур по указанным координатам.

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addChartFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, wb, worksheetName, chartName, false);
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Коллекция фигур, в которую будет добавлена диаграмма. |
| x | float | Координата X для размещения диаграммы. |
| y | float | Координата Y для размещения диаграммы. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Рабочая книга Excel. |
| worksheetName | java.lang.String | Имя листа, содержащего диаграмму. |
| chartIndex | int | Нулевой (начинающий с нуля) индекс формы диаграммы для вставки. Этот индекс можно получить с помощью метода [IExcelDataWorkbook.getChartsFromWorksheet(String)](../../com.aspose.slides/iexceldataworkbook\#getChartsFromWorksheet-String-). |
| embedAllWorkbook | boolean | Если true, в диаграмму будет встроена вся рабочая книга; если false, будет встроены только данные диаграммы. |

**Возвращаемое значение:**
[IChart](../../com.aspose.slides/ichart) - Диаграмма, добавленная в коллекцию фигур.
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)
```

Извлекает диаграмму из указанной рабочей книги Excel и добавляет её в конец заданной коллекции фигур по указанным координатам.

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  Presentation pres = new Presentation();
>  try {
>      String worksheetName = "worksheet name";
>      Dictionary.Enumerator<Integer, String> worksheetCharts = wb.getChartsFromWorksheet(worksheetName).iterator();
>      while (worksheetCharts.hasNext())
>      {
>          KeyValuePair<Integer, String> chart = worksheetCharts.next();
>          ISlide slide = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>          ExcelWorkbookImporter.addChartFromWorkbook(slide.getShapes(), 10, 10, wb, worksheetName, chart.getKey(), false);
>      }
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Коллекция фигур, в которую будет добавлена диаграмма. |
| x | float | Координата X для размещения диаграммы. |
| y | float | Координата Y для размещения диаграммы. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Рабочая книга Excel. |
| worksheetName | java.lang.String | Имя листа, содержащего диаграмму. |
| chartName | java.lang.String | Имя диаграммы, которую следует добавить. |
| embedAllWorkbook | boolean | Если true, в диаграмму будет встроена вся рабочая книга; если false, будет встроены только данные диаграммы. |

**Возвращаемое значение:**
[IChart](../../com.aspose.slides/ichart) - Диаграмма, добавленная в коллекцию фигур.
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)
```

Извлекает диаграмму из указанной рабочей книги Excel и добавляет её в конец заданной коллекции фигур по указанным координатам.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fStream = new FileInputStream(workbookPath);
>      ExcelWorkbookImporter.addChartFromWorkbook(pres.getLayoutSlides().get_Item(0).getShapes(), 10, 10, fStream, worksheetName, chartName, true);
>      fStream.close();
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Коллекция фигур, в которую будет добавлена диаграмма. |
| x | float | Координата X для размещения диаграммы. |
| y | float | Координата Y для размещения диаграммы. |
| workbookStream | java.io.InputStream | Поток, содержащий данные рабочей книги. |
| worksheetName | java.lang.String | Имя листа, содержащего диаграмму. |
| chartName | java.lang.String | Имя диаграммы, которую следует добавить. |
| embedAllWorkbook | boolean | Если true, в диаграмму будет встроена вся рабочая книга; если false, будет встроены только данные диаграммы. |

**Возвращаемое значение:**
[IChart](../../com.aspose.slides/ichart) - Диаграмма, добавленная в коллекцию фигур.
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)
```

Извлекает диаграмму из указанной рабочей книги Excel и добавляет её в конец заданной коллекции фигур по указанным координатам.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addChartFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, workbookPath, worksheetName, chartName, false);
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Коллекция фигур, в которую будет добавлена диаграмма. |
| x | float | Координата X для размещения диаграммы. |
| y | float | Координата Y для размещения диаграммы. |
| workbookPath | java.lang.String | Путь к файлу рабочей книги, содержащей диаграмму. |
| worksheetName | java.lang.String | Имя листа, содержащего диаграмму. |
| chartName | java.lang.String | Имя диаграммы, которую следует добавить. |
| embedWorkbook | boolean | Если true, рабочая книга будет встроена в диаграмму; если false, диаграмма будет ссылаться на внешнюю рабочую книгу. |

**Возвращаемое значение:**
[IChart](../../com.aspose.slides/ichart) - Диаграмма, добавленная в коллекцию фигур.
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)
```

Извлекает таблицу из указанной рабочей книги Excel и добавляет её в конец заданной коллекции фигур по указанным координатам.

--------------------

> ```
> IExcelDataWorkbook workbook = new ExcelDataWorkbook(testFile);
>  Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addTableFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, workbook, worksheetName, "A1:D10");
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Коллекция фигур, в которую будет добавлена таблица. |
| x | float | Координата X для размещения таблицы. |
| y | float | Координата Y для размещения таблицы. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Рабочая книга Excel. |
| worksheetName | java.lang.String | Имя листа, содержащего таблицу. |
| cellRange | java.lang.String | Диапазон ячеек, определяющий таблицу (например, "A1:D10"). |

**Возвращаемое значение:**
[ITable](../../com.aspose.slides/itable) - Таблица, добавленная в коллекцию фигур.
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)
```

Извлекает таблицу из указанной рабочей книги Excel и добавляет её в конец заданной коллекции фигур по указанным координатам.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addTableFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, workbookPath, worksheetName, "A1:D10");
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Коллекция фигур, в которую будет добавлена таблица. |
| x | float | Координата X для размещения таблицы. |
| y | float | Координата Y для размещения таблицы. |
| workbookPath | java.lang.String | Путь к файлу рабочей книги Excel. |
| worksheetName | java.lang.String | Имя листа, содержащего таблицу. |
| cellRange | java.lang.String | Диапазон ячеек, определяющий таблицу (например, "A1:D10"). |

**Возвращаемое значение:**
[ITable](../../com.aspose.slides/itable) - Таблица, добавленная в коллекцию фигур.
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)
```

Извлекает таблицу из указанной рабочей книги Excel и добавляет её в конец заданной коллекции фигур по указанным координатам.

--------------------

> ```
> FileInputStream fStream = new FileInputStream(workbookPath);
>  Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addTableFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, fStream, worksheetName, "A1:D10");
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Коллекция фигур, в которую будет добавлена таблица. |
| x | float | Координата X для размещения таблицы. |
| y | float | Координата Y для размещения таблицы. |
| workbookStream | java.io.InputStream | Поток, содержащий данные рабочей книги. |
| worksheetName | java.lang.String | Имя листа, содержащего таблицу. |
| cellRange | java.lang.String | Диапазон ячеек, определяющий таблицу (например, "A1:D10"). |

**Возвращаемое значение:**
[ITable](../../com.aspose.slides/itable) - Таблица, добавленная в коллекцию фигур.