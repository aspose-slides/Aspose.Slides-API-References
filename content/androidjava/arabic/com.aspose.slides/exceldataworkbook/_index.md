---
title: ExcelDataWorkbook
second_title: Aspose.Slides لنظام Android عبر مرجع واجهة برمجة التطبيقات Java
description: يمثل دفتر عمل يوفّر إمكانية الوصول إلى بيانات Excel للاستخدام العام.
type: docs
url: /ar/com.aspose.slides/exceldataworkbook/
---
**الوراثة:**  
java.lang.Object

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook)  
```
public class ExcelDataWorkbook implements IExcelDataWorkbook
```

يمثل دفتر عمل يوفّر إمكانية الوصول إلى بيانات إكسل للاستخدام العام.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [ExcelDataWorkbook(String filePath)](#ExcelDataWorkbook-java.lang.String-) | يُنشئ مثيلاً جديداً باستخدام مسار الملف المحدد. |
| [ExcelDataWorkbook(InputStream stream)](#ExcelDataWorkbook-java.io.InputStream-) | يُنشئ مثيلاً جديداً للفئة باستخدام الدفق المقدم. |
## الدوال

| الدالة | الوصف |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | يسترجع مجموعة من الخلايا من دفتر العمل التي تطابق الصيغة المحددة. |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | يسترجع خلية من ورقة العمل المحددة باستخدام فهرستها وإحداثيات الخلية. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | يسترجع خلية من ورقة العمل المحددة باستخدام اسمها وإحداثيات الخلية. |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | يسترجع خلية من ورقة العمل المحددة باستخدام فهرستها واسم الخلية بنمط إكسل (مثال: "B2"). |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | يسترجع خلية من ورقة العمل المحددة باستخدام اسم الخلية بنمط إكسل (مثال: "B2"). |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | يسترجع قاموسًا يحتوي على الفهارس وأسماء جميع المخططات في ورقة العمل المحددة لدفتر إكسل. |
| [getWorksheetNames()](#getWorksheetNames--) | يسترجع أسماء جميع ورقات العمل الموجودة في دفتر إكسل. |
### ExcelDataWorkbook(String filePath) {#ExcelDataWorkbook-java.lang.String-}
```
public ExcelDataWorkbook(String filePath)
```

يُنشئ مثيلاً جديداً باستخدام مسار الملف المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | المسار الكامل إلى ملف دفتر إكسل. |
### ExcelDataWorkbook(InputStream stream) {#ExcelDataWorkbook-java.io.InputStream-}
```
public ExcelDataWorkbook(InputStream stream)
```

يُنشئ مثيلاً جديداً للفئة باستخدام الدفق المقدم.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | دفق يحتوي على بيانات دفتر إكسل. |
### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public final System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```

يسترجع مجموعة من الخلايا من دفتر العمل التي تطابق الصيغة المحددة.

--------------------

> ```
> ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //Output: 5
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| formula | java.lang.String | صيغة أو تعبير نطاق (مثال: "Sheet1!A1:B3") يحدّد الخلايا المستهدفة. |
| skipHiddenCells | boolean | إذا كان true، سيتم استبعاد الخلايا المخفية (مثلاً في الصفوف أو الأعمدة المخفية) من النتيجة. |

**القيم المرجعة:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - قائمة للقراءة فقط من الخلايا التي تطابق الصيغة المحددة.
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IExcelDataCell getCell(int worksheetIndex, int row, int column)
```

يسترجع خلية من ورقة العمل المحددة باستخدام فهرستها وإحداثيات الخلية.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
>  ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| worksheetIndex | int | فهرس الصفر للورقة. |
| row | int | فهرس الصف من الصفر للخلية. |
| column | int | فهرس العمود من الصفر للخلية. |

**القيم المرجعة:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - الخلية في الموقع المحدد.
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IExcelDataCell getCell(String worksheetName, int row, int column)
```

يسترجع خلية من ورقة العمل المحددة باستخدام اسمها وإحداثيات الخلية.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", 1, 1);
>  System.out.println(cell.getValue().toString());
>  ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| worksheetName | java.lang.String | اسم الورقة. |
| row | int | فهرس الصف من الصفر للخلية. |
| column | int | فهرس العمود من الصفر للخلية. |

**القيم المرجعة:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - الخلية في الموقع المحدد.
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IExcelDataCell getCell(int worksheetIndex, String cellName)
```

يسترجع خلية من ورقة العمل المحددة باستخدام فهرستها واسم الخلية بنمط إكسل (مثال: "B2").

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, "B2");
>  System.out.println(cell.getValue().toString());
>  ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| worksheetIndex | int | فهرس الصفر للورقة. |
| cellName | java.lang.String | مرجع الخلية بنمط إكسل (مثال: "A1", "C5"). |

**القيم المرجعة:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - الخلية في الموقع المحدد.
### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public final IExcelDataCell getCell(String worksheetName, String cellName)
```

يسترجع خلية من ورقة العمل المحددة باستخدام اسم الخلية بنمط إكسل (مثال: "B2").

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", "B2");
>  System.out.println(cell.getValue().toString());
>  ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| worksheetName | java.lang.String | اسم الورقة. |
| cellName | java.lang.String | مرجع الخلية بنمط إكسل (مثال: "A1", "C5"). |

**القيم المرجعة:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - الخلية في الموقع المحدد.
### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public final System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```

يسترجع قاموسًا يحتوي على الفهارس وأسماء جميع المخططات في ورقة العمل المحددة لدفتر إكسل.

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

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| worksheetName | java.lang.String | اسم الورقة للبحث عن المخططات. |

**القيم المرجعة:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - قاموس حيث المفتاح هو فهرس المخطط والقيمة هي اسم المخطط.
### getWorksheetNames() {#getWorksheetNames--}
```
public final System.Collections.Generic.List<String> getWorksheetNames()
```

يسترجع أسماء جميع ورقات العمل الموجودة في دفتر إكسل.

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<String> sheetNames = wb.getWorksheetNames();
>  for (String name : sheetNames)
>      System.out.println(name);
> ```

**القيم المرجعة:**
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - قائمة بأسماء أوراق العمل.