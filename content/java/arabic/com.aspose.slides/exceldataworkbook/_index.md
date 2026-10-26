---
title: ExcelDataWorkbook
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثّل دفتر عمل يوفر الوصول إلى بيانات Excel للاستخدام العام.
type: docs
url: /ar/com.aspose.slides/exceldataworkbook/
---
**الوراثة:**  
java.lang.Object

**جميع الواجهات المطبقة:**  
[com.aspose.slides.IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook)  
```
public class ExcelDataWorkbook implements IExcelDataWorkbook
```

يمثل دفتر عمل يوفر الوصول إلى بيانات Excel للاستخدام العام.

## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [ExcelDataWorkbook(String filePath)](#ExcelDataWorkbook-java.lang.String-) | يهيئ نسخة جديدة باستخدام مسار الملف المحدد. |
| [ExcelDataWorkbook(InputStream stream)](#ExcelDataWorkbook-java.io.InputStream-) | يهيئ نسخة جديدة من الفئة باستخدام الدفق المقدم. |

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | يسترجع مجموعة من الخلايا من دفتر العمل التي تطابق الصيغة المحددة. |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | يسترجع خلية من ورقة العمل المحددة باستخدام الفهرس وإحداثيات الخلية. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | يسترجع خلية من ورقة العمل المحددة باستخدام الاسم وإحداثيات الخلية. |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | يسترجع خلية من ورقة العمل المحددة باستخدام الفهرس واسم الخلية على نمط Excel (مثل "B2"). |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | يسترجع خلية من ورقة العمل المحددة باستخدام اسم الخلية على نمط Excel (مثل "B2"). |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | يسترجع قاموسًا يحتوي على الفهارس والأسماء لجميع المخططات في ورقة العمل المحددة من دفتر عمل Excel. |
| [getWorksheetNames()](#getWorksheetNames--) | يسترجع أسماء جميع أوراق العمل الموجودة في دفتر عمل Excel. |

### ExcelDataWorkbook(String filePath) {#ExcelDataWorkbook-java.lang.String-}
```
public ExcelDataWorkbook(String filePath)
```

يهيئ نسخة جديدة باستخدام مسار الملف المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | المسار الكامل إلى ملف دفتر عمل Excel. |

### ExcelDataWorkbook(InputStream stream) {#ExcelDataWorkbook-java.io.InputStream-}
```
public ExcelDataWorkbook(InputStream stream)
```

يهيئ نسخة جديدة من الفئة باستخدام الدفق المقدم.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | دفق يحتوي على بيانات دفتر عمل Excel. |

### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public final System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```

يسترجع مجموعة من الخلايا من دفتر العمل التي تطابق الصيغة المحددة.

--------------------

> ```
> ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //الإخراج: 5
> ```


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| formula | java.lang.String | صيغة أو تعبير نطاق (مثل "Sheet1!A1:B3") يُستخدم لتحديد الخلايا المستهدفة. |
| skipHiddenCells | boolean | إذا كان true، سيتم استبعاد الخلايا المخفية (مثلاً في الصفوف أو الأعمدة المخفية) من النتيجة. |

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - قائمة للقراءة فقط من الخلايا التي تطابق الصيغة المحددة.

### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IExcelDataCell getCell(int worksheetIndex, int row, int column)
```

يسترجع خلية من ورقة العمل المحددة باستخدام الفهرس وإحداثيات الخلية.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| worksheetIndex | int | الفهرس الصفري لورقة العمل. |
| row | int | فهرس الصف الصفري للخلية. |
| column | int | فهرس العمود الصفري للخلية. |

**القيمة المرجعة:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - الخلية في الموقع المحدد.

### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IExcelDataCell getCell(String worksheetName, int row, int column)
```

يسترجع خلية من ورقة العمل المحددة باستخدام الاسم وإحداثيات الخلية.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| worksheetName | java.lang.String | اسم ورقة العمل. |
| row | int | فهرس الصف الصفري للخلية. |
| column | int | فهرس العمود الصفري للخلية. |

**القيمة المرجعة:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - الخلية في الموقع المحدد.

### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IExcelDataCell getCell(int worksheetIndex, String cellName)
```

يسترجع خلية من ورقة العمل المحددة باستخدام الفهرس واسم الخلية على نمط Excel (مثل "B2").

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, "B2");
>  System.out.println(cell.getValue().toString());
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| worksheetIndex | int | الفهرس الصفري لورقة العمل. |
| cellName | java.lang.String | مرجع الخلية على نمط Excel (مثل "A1"، "C5"). |

**القيمة المرجعة:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - الخلية في الموقع المحدد.

### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public final IExcelDataCell getCell(String worksheetName, String cellName)
```

يسترجع خلية من ورقة العمل المحددة باستخدام اسم الخلية على نمط Excel (مثل "B2").

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", "B2");
>  System.out.println(cell.getValue().toString());
> ```


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| worksheetName | java.lang.String | اسم ورقة العمل. |
| cellName | java.lang.String | مرجع الخلية على نمط Excel (مثل "A1"، "C5"). |

**القيمة المرجعة:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - الخلية في الموقع المحدد.

### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public final System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```

يسترجع قاموسًا يحتوي على الفهارس والأسماء لجميع المخططات في ورقة العمل المحددة من دفتر عمل Excel.

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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| worksheetName | java.lang.String | اسم ورقة العمل التي يتم البحث فيها عن المخططات. |

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - قاموس حيث المفتاح هو فهرس المخطط والقيمة هي اسم المخطط.

### getWorksheetNames() {#getWorksheetNames--}
```
public final System.Collections.Generic.List<String> getWorksheetNames()
```

يسترجع أسماء جميع أوراق العمل الموجودة في دفتر عمل Excel.

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<String> sheetNames = wb.getWorksheetNames();
>  for (String name : sheetNames)
>      System.out.println(name);
> ```

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - قائمة بأسماء أوراق العمل.