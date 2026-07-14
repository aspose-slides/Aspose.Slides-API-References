---
title: IChartCellCollection
second_title: Aspose.Slides لأندرويد عبر مرجع API جافا
description: يمثل مجموعة من الخلايا التي تحتوي على بيانات.
type: docs
url: /ar/com.aspose.slides/ichartcellcollection/
---
**جميع الواجهات المنفذة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IChartCellCollection extends System.Collections.Generic.IGenericEnumerable<IChartDataCell>
```

يمثل مجموعة من الخلايا التي تحتوي على بيانات.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | يعيد عنوان مجموعة الخلايا في المصنف. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | سلسلة الجمع من جميع قيم الخلايا النصية. |
| [get_Item(int index)](#get-Item-int-) | يعيد خلية (IChartDataCell) حسب الفهرس. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | إضافة خلية جديدة إلى المجموعة. |
| [add(Object value)](#add-java.lang.Object-) | ينشئ [IChartDataCell](../../com.aspose.slides/ichartdatacell) من القيمة المحددة ويضيفه إلى المجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل خلية من المجموعة حسب الفهرس. |
| [getCount()](#getCount--) | يحصل على عدد الخلايا في المجموعة. |
### getCellsAddress() {#getCellsAddress--}
```
public abstract String getCellsAddress()
```


يعيد عنوان مجموعة الخلايا في المصنف.

**القيمة المرجعة:**
java.lang.String - عنوان مجموعة الخلايا في المصنف String
### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public abstract String getConcatenatedValuesFromCells()
```


سلسلة الجمع من جميع قيم الخلايا النصية.

**القيمة المرجعة:**
java.lang.String - السلسلة الناتجة String
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int index)
```


يعيد خلية (IChartDataCell) حسب الفهرس.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الخلية. |

**القيمة المرجعة:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - خلية تحتوي على بيانات.
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract void add(IChartDataCell chartDataCell)
```


إضافة خلية جديدة إلى المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | الخلية الجديدة للإضافة. |

### add(Object value) {#add-java.lang.Object-}
```
public abstract void add(Object value)
```


ينشئ [IChartDataCell](../../com.aspose.slides/ichartdatacell) من القيمة المحددة ويضيفه إلى المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.Object | القيمة.

--------------------

هذه الطريقة تضيف ورقة عمل باسم AUTO_DATA وتضيف جميع القيم هناك. إذا كنت تستخدم [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) لإضافة أو تعديل قيم الخلايا، تأكد من عدم استخدام هذه الورقة. الحد الأقصى لعدد القيم المضافة باستخدام هذه الطريقة لا يجب أن يتجاوز 16711680 |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


يزيل خلية من المجموعة حسب الفهرس.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الخلية المراد إزالتها. |

### getCount() {#getCount--}
```
public abstract int getCount()
```


يحصل على عدد الخلايا في المجموعة. int للقراءة فقط.

**القيمة المرجعة:**
int