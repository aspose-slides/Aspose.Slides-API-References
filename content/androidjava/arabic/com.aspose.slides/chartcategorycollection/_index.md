---
title: ChartCategoryCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل مجموعة من
type: docs
url: /ar/com.aspose.slides/chartcategorycollection/
---
**الوراثة:**
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المنفذة:**
[com.aspose.slides.IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
```
public class ChartCategoryCollection extends DomObject<ChartData> implements IChartCategoryCollection
```

يمثل مجموعة من [ChartCategory](../../com.aspose.slides/chartcategory)
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر في الفهرس المحدد. |
| [getUseCells()](#getUseCells--) | إذا كانت true فإن ورقة العمل تُستخدم لتخزين الفئات (هذه الحالة تدعم فئات متعددة المستويات). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | إذا كانت true فإن ورقة العمل تُستخدم لتخزين الفئات (هذه الحالة تدعم فئات متعددة المستويات). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | يُعيد عدد مستويات تجميع الفئات المستخدمة. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | إذا كانت الفئة موجودة في المجموعة، يتم إرجاعها. |
| [add(Object value)](#add-java.lang.Object-) | ينشئ [ChartCategory](../../com.aspose.slides/chartcategory) جديدًا من القيمة ويضيفه إلى المجموعة. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | يبحث عن [ChartCategory](../../com.aspose.slides/chartcategory) المحدد ويُعيد الفهرس الصفري للظهور الأول في المجموعة بأكملها. |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | يزيل القيمة المحددة. |
| [removeAt(int index)](#removeAt-int-) | يزيل العنصر عند الفهرس المعطى. |
| [clear()](#clear--) | يزيل جميع العناصر من المجموعة. |
| [iterator()](#iterator--) | يُعيد عددًا يتيح التكرار عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يُعيد مكرّر جافا للمجموعة بأكملها. |
| [size()](#size--) | يُعيد عدد العناصر في المجموعة. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | ينسخ جميع عناصر المجموعة إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | يُعيد قيمة تُشير إلى ما إذا كان الوصول إلى القائمة مُزامنًا (آمن للخيوط). |
| [getSyncRoot()](#getSyncRoot--) | يُعيد كائنًا يمكن استخدامه لمزامنة الوصول إلى المجموعة. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartCategory get_Item(int index)
```

يحصل على العنصر في الفهرس المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرتجعة:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - العنصر في الفهرس المحدد.

### getUseCells() {#getUseCells--}
```
public final boolean getUseCells()
```

إذا كانت true فإن ورقة العمل تُستخدم لتخزين الفئات (هذه الحالة تدعم فئات متعددة المستويات). إذا كانت false فإن ورقة العمل **ليس** تُستخدم لتخزين القيم (وهذه الحالة لا تدعم فئات متعددة المستويات). منطق قابل للقراءة والكتابة.

**القيمة المرتجعة:**
boolean

### setUseCells(boolean value) {#setUseCells-boolean-}
```
public final void setUseCells(boolean value)
```

إذا كانت true فإن ورقة العمل تُستخدم لتخزين الفئات (هذه الحالة تدعم فئات متعددة المستويات). إذا كانت false فإن ورقة العمل **ليس** تُستخدم لتخزين القيم (وهذه الحالة لا تدعم فئات متعددة المستويات). منطق قابل للقراءة والكتابة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public final int getGroupingLevelCount()
```

يُعيد عدد مستويات تجميع الفئات المستخدمة. يكون أكثر من واحد للفئات متعددة المستويات. عدد صحيح للقراءة فقط.

**القيمة المرتجعة:**
int

### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public final IChartCategory add(IChartDataCell chartDataCell)
```

إذا كانت الفئة موجودة في المجموعة، يتم إرجاعها. وإلا يتم إنشاء فئة مخطط جديدة من [IChartDataCell](../../com.aspose.slides/ichartdatacell) وإضافتها إلى المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | الخلية المستخدمة لإنشاء فئة المخطط. |

**القيمة المرتجعة:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - الفئة المضافة أو الموجودة.

### add(Object value) {#add-java.lang.Object-}
```
public final IChartCategory add(Object value)
```

ينشئ [ChartCategory](../../com.aspose.slides/chartcategory) جديدًا من القيمة ويضيفه إلى المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.Object | القيمة.

--------------------

هذه الطريقة تُضيف ورقة عمل باسم AUTO_DATA وتضيف جميع القيم هناك. إذا استخدمت [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) لإضافة أو تعديل قيم الخلايا، تأكد من عدم استخدام هذه الورقة. يجب ألا يتجاوز العدد الأقصى للقيم المضافة باستخدام هذه الطريقة 16711680 |

**القيمة المرتجعة:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - [IChartCategory](../../com.aspose.slides/ichartcategory) المضافة.

### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public final int indexOf(IChartCategory value)
```

يبحث عن [ChartCategory](../../com.aspose.slides/chartcategory) المحدد ويُعيد الفهرس الصفري للظهور الأول داخل المجموعة بأكملها.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | فئة المخطط.

**القيمة المرتجعة:**
int - الفهرس الصفري للظهور الأول للقيمة داخل CollectionBase بأكملها، إذا وُجد؛ وإلا -1.

### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public final void remove(IChartCategory value)
```

يزيل القيمة المحددة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | القيمة.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

يزيل العنصر عند الفهرس المعطى.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الفئة التي يجب إزالتها.

### clear() {#clear--}
```
public final void clear()
```

يزيل جميع العناصر من المجموعة.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iterator()
```

يُعيد عددًا يتيح التكرار عبر المجموعة.

**القيمة المرتجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - IGenericEnumerator يمكن استخدامه للتكرار عبر المجموعة.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iteratorJava()
```

يُعيد مكرّر جافا للمجموعة بأكملها.

**القيمة المرتجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - java.util.Iterator للمجموعة بأكملها.

### size() {#size--}
```
public final int size()
```

يُعيد عدد العناصر في المجموعة. عدد صحيح للقراءة فقط.

**القيمة المرتجعة:**
int

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

ينسخ جميع عناصر المجموعة إلى المصفوفة المحددة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة الهدف. |
| index | int | الفهرس الابتدائي في المصفوفة.

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

يُعيد قيمة تُشير إلى ما إذا كان الوصول إلى القائمة مُزامنًا (آمن للخيوط). منطقي للقراءة فقط.

**القيمة المرتجعة:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

يُعيد كائنًا يمكن استخدامه لمزامنة الوصول إلى المجموعة. كائن للقراءة فقط.

يُعيد جذر المزامنة. كائن للقراءة فقط.

**القيمة المرتجعة:**
java.lang.Object