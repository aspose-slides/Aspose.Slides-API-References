---
title: IExcelDataWorkbook
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل مصنفًا يوفر الوصول إلى بيانات Excel للاستخدام العام.
type: docs
url: /ar/com.aspose.slides/iexceldataworkbook/
---```
public interface IExcelDataWorkbook
```

يمثل مصنفًا يوفر الوصول إلى بيانات Excel للاستخدام العام.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | يجلب مجموعة من الخلايا من المصنف التي تتطابق مع الصيغة المحددة. |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | يجلب خلية من ورقة العمل المحددة باستخدام فهرسها وإحداثيات الخلية. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | يجلب خلية من ورقة العمل المحددة باستخدام اسمها وإحداثيات الخلية. |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | يجلب خلية من ورقة العمل المحددة باستخدام فهرسها واسم الخلية بنمط Excel (مثال: "B2"). |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | يجلب خلية من ورقة العمل المحددة باستخدام اسم الخلية بنمط Excel (مثال: "B2"). |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | يجلب قاموسًا يحتوي على الفهارس وأسماء جميع المخططات في ورقة العمل المحددة لمصنف Excel. |
| [getWorksheetNames()](#getWorksheetNames--) | يجلب أسماء جميع أوراق العمل الموجودة في مصنف Excel. |
### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public abstract System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```

يجلب مجموعة من الخلايا من المصنف التي تتطابق مع الصيغة المحددة.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //الإخراج: 5
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| formula | java.lang.String | صيغة أو تعبير نطاق (مثال: "Sheet1!A1:B3") يُستخدم لتحديد الخلايا المستهدفة. |
| skipHiddenCells | boolean | إذا كانت true، فسيتم استبعاد الخلايا المخفية (مثال: في الصفوف أو الأعمدة المخفية) من النتيجة. |

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - قائمة للقراءة فقط من الخلايا التي تتطابق مع الصيغة المحددة.
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, int row, int column)
```

يجلب خلية من ورقة العمل المحددة باستخدام فهرسها وإحداثيات الخلية.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| worksheetIndex | int | الفهرس الصفري لورقة العمل. |
| row | int | فهرس الصف الصفري للخلية. |
| column | int | فهرس العمود الصفري للخلية. |

**القيمة المرجعة:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - الخلية في الموقع المحدد.
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IExcelDataCell getCell(String worksheetName, int row, int column)
```

يجلب خلية من ورقة العمل المحددة باستخدام اسمها وإحداثيات الخلية.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| worksheetName | java.lang.String | اسم ورقة العمل. |
| row | int | فهرس الصف الصفري للخلية. |
| column | int | فهرس العمود الصفري للخلية. |

**القيمة المرجعة:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - الخلية في الموقع المحدد.
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, String cellName)
```

يجلب خلية من ورقة العمل المحددة باستخدام فهرسها واسم الخلية بنمط Excel (مثال: "B2").

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, "B2");
>  System.out.println(cell.getValue().toString());
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| worksheetIndex | int | الفهرس الصفري لورقة العمل. |
| cellName | java.lang.String | مرجع الخلية بنمط Excel (مثال: "A1", "C5"). |

**القيمة المرجعة:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - الخلية في الموقع المحدد.
### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public abstract IExcelDataCell getCell(String worksheetName, String cellName)
```

يجلب خلية من ورقة العمل المحددة باستخدام اسم الخلية بنمط Excel (مثال: "B2").

--------------------

> ```
> مثال:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", "B2");
>  System.out.println(cell.getValue().toString());
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| worksheetName | java.lang.String | اسم ورقة العمل. |
| cellName | java.lang.String | مرجع الخلية بنمط Excel (مثال: "A1", "C5"). |

**القيمة المرجعة:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - الخلية في الموقع المحدد.
### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public abstract System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```

يجلب قاموسًا يحتوي على الفهارس وأسماء جميع المخططات في ورقة العمل المحددة لمصنف Excel.

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
| worksheetName | java.lang.String | اسم ورقة العمل للبحث عن المخططات. |

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - قاموس حيث المفتاح هو فهرس المخطط والقيمة هي اسم المخطط.
### getWorksheetNames() {#getWorksheetNames--}
```
public abstract System.Collections.Generic.List<String> getWorksheetNames()
```

يجلب أسماء جميع أوراق العمل الموجودة في مصنف Excel.

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
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - قائمة بأسماء أوراق العمل