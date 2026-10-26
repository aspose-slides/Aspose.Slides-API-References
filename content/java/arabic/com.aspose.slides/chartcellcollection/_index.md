---
title: ChartCellCollection
second_title: مرجع API لـ Aspose.Slides for Java
description: يمثل مجموعة من الخلايا التي تحتوي على بيانات.
type: docs
url: /ar/com.aspose.slides/chartcellcollection/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IChartCellCollection](../../com.aspose.slides/ichartcellcollection), com.aspose.slides.IDOMObject
```
public class ChartCellCollection implements IChartCellCollection, IDOMObject
```

يمثل مجموعة من الخلايا التي تحتوي على بيانات.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | يرجع عنوان مجموعة الخلايا في دفتر العمل. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | سلسلة تجميع من قيم السلاسل النصية لجميع الخلايا. |
| [get_Item(int index)](#get-Item-int-) | يرجع خلية (IChartDataCell) حسب الفهرس. |
| [add(IChartDataCell cell)](#add-com.aspose.slides.IChartDataCell-) | أضف خلية جديدة إلى المجموعة. |
| [add(Object value)](#add-java.lang.Object-) | ينشئ [ChartDataCell](../../com.aspose.slides/chartdatacell) من القيمة المحددة ويضيفه إلى المجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل خلية من المجموعة حسب الفهرس. |
| [getCount()](#getCount--) | يحصل على عدد الخلايا في المجموعة. |
| [iterator()](#iterator--) | يرجع Enumerator يتجول عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يرجع مُكرّر جافا للمجموعة بأكملها. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getCellsAddress() {#getCellsAddress--}
```
public final String getCellsAddress()
```


يرجع عنوان مجموعة الخلايا في دفتر العمل.

**القيمة المرجعة:**
java.lang.String
### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public final String getConcatenatedValuesFromCells()
```


سلسلة تجميع من قيم السلاسل النصية لجميع الخلايا.

**القيمة المرجعة:**
java.lang.String
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataCell get_Item(int index)
```


يرجع خلية (IChartDataCell) حسب الفهرس.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الخلية. |

**القيمة المرجعة:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - خلية تحتوي على بيانات.
### add(IChartDataCell cell) {#add-com.aspose.slides.IChartDataCell-}
```
public final void add(IChartDataCell cell)
```


أضف خلية جديدة إلى المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | الخلية الجديدة للإضافة. |

### add(Object value) {#add-java.lang.Object-}
```
public final void add(Object value)
```


ينشئ [ChartDataCell](../../com.aspose.slides/chartdatacell) من القيمة المحددة ويضيفه إلى المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.Object | القيمة.

--------------------

هذه الطريقة تُضيف ورقة عمل بالاسم AUTO_DATA وتضيف جميع القيم هناك. إذا استخدمت [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) لإضافة أو تعديل قيم الخلية، تأكد من عدم استخدام هذه الورقة. الحد الأقصى لعدد القيم المضافة باستخدام هذه الطريقة يجب ألا يتجاوز 16711680 |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


يزيل خلية من المجموعة حسب الفهرس.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الخلية التي تريد إزالتها. |

### getCount() {#getCount--}
```
public final int getCount()
```


يحصل على عدد الخلايا في المجموعة. للقراءة فقط int.

**القيمة المرجعة:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iterator()
```


يرجع Enumerator يتجول عبر المجموعة.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - IGenericEnumerator يمكن استخدامه لتجول عبر المجموعة.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iteratorJava()
```


يرجع مُكرّر جافا للمجموعة بأكملها.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - java.util.Iterator للمجموعة بأكملها.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


يرجع كائن Parent_Immediate. للقراءة فقط IDOMObject.

**القيمة المرجعة:**
com.aspose.slides.IDOMObject