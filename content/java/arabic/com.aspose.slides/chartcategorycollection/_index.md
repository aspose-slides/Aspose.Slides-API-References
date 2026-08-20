---
title: ChartCategoryCollection
second_title: مرجع Aspose.Slides لـ Java API
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
| [getUseCells()](#getUseCells--) | إذا كانت true فإن ورقة العمل تُستخدم لتخزين الفئات (هذا الحالة تدعم فئات متعددة المستويات). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | إذا كانت true فإن ورقة العمل تُستخدم لتخزين الفئات (هذا الحالة تدعم فئات متعددة المستويات). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | يعيد عدد مستويات تجميع الفئات المستخدمة. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | إذا كانت الفئة موجودة في المجموعة، يُرجعها. |
| [add(Object value)](#add-java.lang.Object-) | ينشئ [ChartCategory](../../com.aspose.slides/chartcategory) جديد من القيمة ويضيفه إلى المجموعة. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | يبحث عن [ChartCategory](../../com.aspose.slides/chartcategory) المحدد ويُرجع الفهرس الصفري للظهور الأول ضمن المجموعة بالكامل. |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | يزيل القيمة المحددة. |
| [removeAt(int index)](#removeAt-int-) | يزيل العنصر في الفهرس المحدد. |
| [clear()](#clear--) | يزيل جميع العناصر من المجموعة. |
| [iterator()](#iterator--) | يعيد عدادًا يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يعيد مؤشر java للمجموعة بالكامل. |
| [size()](#size--) | يعيد عدد العناصر في المجموعة. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | ينسخ جميع عناصر المجموعة إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | يعيد قيمة تشير إلى ما إذا كان الوصول إلى القائمة متزامنًا (آمن للخيوط). |
| [getSyncRoot()](#getSyncRoot--) | يعيد كائنًا يمكن استخدامه لمزامنة الوصول إلى المجموعة. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartCategory get_Item(int index)
```

يحصل على العنصر في الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرتجعة:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - العنصر في الفهرس المحدد.

### getUseCells() {#getUseCells--}
```
public final boolean getUseCells()
```

إذا كانت true فإن ورقة العمل تُستخدم لتخزين الفئات (هذا الحالة تدعم فئات متعددة المستويات). إذا كانت false فإن ورقة العمل لا تُستخدم لتخزين القيم (وهذا الحالة لا تدعم فئات متعددة المستويات). منطقي قابل للقراءة والكتابة.

**القيمة المرتجعة:**
boolean

### setUseCells(boolean value) {#setUseCells-boolean-}
```
public final void setUseCells(boolean value)
```

إذاكانت true فإن ورقة العمل تُستخدم لتخزين الفئات (هذا الحالة تدعم فئات متعددة المستويات). إذاكانت false فإن ورقة العمل لا تُستخدم لتخزين القيم (وهذا الحالة لا تدعم فئات متعددة المستويات). منطقي قابل للقراءة والكتابة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public final int getGroupingLevelCount()
```

يعيد عدد مستويات تجميع الفئات المستخدمة. يكون أكثر من واحد للفئات المتعددة المستويات. int للقراءة فقط.

**القيمة المرتجعة:**
int

### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public final IChartCategory add(IChartDataCell chartDataCell)
```

إذا كانت الفئة موجودة في المجموعة، يُرجعها. وإلا ينشئ فئة مخطط جديدة من [IChartDataCell](../../com.aspose.slides/ichartdatacell) ويضيفها إلى المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | خلية تُستخدم لإنشاء فئة المخطط. |

**القيمة المرتجعة:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - الفئة المضافة أو الموجودة.

### add(Object value) {#add-java.lang.Object-}
```
public final IChartCategory add(Object value)
```

ينشئ [ChartCategory](../../com.aspose.slides/chartcategory) جديد من القيمة ويضيفه إلى المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.Object | القيمة. |

**القيمة المرتجعة:**
هذه الطريقة تضيف ورقة عمل بالاسم AUTO_DATA وتضيف جميع القيم هناك. إذا استخدمت [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) لإضافة أو تعديل قيم الخلايا، تأكد من عدم استخدام هذه الورقة. الحد الأقصى لعدد القيم التي تُضاف باستخدام هذه الطريقة لا يجب أن يتجاوز 16711680

**القيمة المرتجعة:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - تم إضافة [IChartCategory](../../com.aspose.slides/ichartcategory).

### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public final int indexOf(IChartCategory value)
```

يبحث عن [ChartCategory](../../com.aspose.slides/chartcategory) المحدد ويُرجع الفهرس الصفري للظهور الأول ضمن المجموعة بالكامل.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | فئة المخطط. |

**القيمة المرتجعة:**
int - الفهرس الصفري للظهور الأول للقيمة ضمن CollectionBase بالكامل، إذا وجدت؛ وإلا -1.

### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public final void remove(IChartCategory value)
```

يزيل القيمة المحددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | القيمة. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

يزيل العنصر في الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الفئة لإزالتها. |

### clear() {#clear--}
```
public final void clear()
```

يزيل جميع العناصر من المجموعة.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iterator()
```

يعيد عدادًا يتنقل عبر المجموعة.

**القيمة المرتجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - IGenericEnumerator يمكن استخدامه للتنقل عبر المجموعة.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iteratorJava()
```

يعيد مؤشر java للمجموعة بالكامل.

**القيمة المرتجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - java.util.Iterator للمجموعة بالكامل.

### size() {#size--}
```
public final int size()
```

يعيد عدد العناصر في المجموعة. int للقراءة فقط.

**القيمة المرتجعة:**
int

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

ينسخ جميع عناصر المجموعة إلى المصفوفة المحددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة الهدف. |
| index | int | الفهرس الابتدائي في المصفوفة. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

يعيد قيمة تشير إلى ما إذا كان الوصول إلى القائمة متزامنًا (آمن للخيوط). boolean للقراءة فقط.

**القيمة المرتجعة:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

يعيد كائنًا يمكن استخدامه لمزامنة الوصول إلى المجموعة. Object للقراءة فقط.

يعيد جذر المزامنة. Object للقراءة فقط.

**القيمة المرتجعة:**
java.lang.Object