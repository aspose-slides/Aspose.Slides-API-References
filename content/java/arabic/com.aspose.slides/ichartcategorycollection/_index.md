---
title: IChartCategoryCollection
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل مجموعة من
type: docs
url: /ar/com.aspose.slides/ichartcategorycollection/
---
**جميع الواجهات المنفذة:**
com.aspose.slides.IGenericCollection
```
public interface IChartCategoryCollection extends IGenericCollection<IChartCategory>
```

يمثل مجموعة من [IChartCategory](../../com.aspose.slides/ichartcategory)
## الأساليب

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يجلب العنصر عند الفهرس المحدد. |
| [getUseCells()](#getUseCells--) | إذا كان صحيحًا فستُستَخدم ورقة العمل لتخزين الفئات (يدعم هذا الحالة الفئات متعددة المستويات). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | إذا كان صحيحًا فستُستَخدم ورقة العمل لتخزين الفئات (يدعم هذا الحالة الفئات متعددة المستويات). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | يعيد عدد مستويات تجميع الفئات المستخدمة. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | إذا كانت الفئة موجودة في المجموعة، فارجعها. |
| [add(Object value)](#add-java.lang.Object-) | ينشئ [IChartCategory](../../com.aspose.slides/ichartcategory) جديدًا من القيمة ويضيفه إلى المجموعة. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | يبحث عن [IChartCategory](../../com.aspose.slides/ichartcategory) المحدد ويعيد الفهرس الصفري للظهور الأول داخل المجموعة الكاملة |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | يزيل القيمة المحددة. |
| [removeAt(int index)](#removeAt-int-) | يزيل العنصر عند الفهرس المحدد. |
| [clear()](#clear--) | يزيل جميع العناصر من المجموعة. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartCategory get_Item(int index)
```

يجلب العنصر عند الفهرس المحدد.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**الإرجاع:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - العنصر عند الفهرس المحدد.
### getUseCells() {#getUseCells--}
```
public abstract boolean getUseCells()
```

إذا كان صحيحًا فستُستَخدم ورقة العمل لتخزين الفئات (يدعم هذا الحالة الفئات متعددة المستويات). إذا كان خطأً فغير ذلك، ولا تُستَخدم ورقة العمل لتخزين القيم (ولا يدعم ذلك الفئات متعددة المستويات). منطقية قابلة للقراءة والكتابة.

**الإرجاع:**
boolean
### setUseCells(boolean value) {#setUseCells-boolean-}
```
public abstract void setUseCells(boolean value)
```

إذا كان صحيحًا فستُستَخدم ورقة العمل لتخزين الفئات (يدعم هذا الحالة الفئات متعددة المستويات). إذا كان خطأً فغير ذلك، ولا تُستَخدم ورقة العمل لتخزين القيم (ولا يدعم ذلك الفئات متعددة المستويات). منطقية قابلة للقراءة والكتابة.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public abstract int getGroupingLevelCount()
```

يعيد عدد مستويات تجميع الفئات المستخدمة. يكون أكثر من واحد للفئات متعددة المستويات. عدد صحيح للقراءة فقط.

**الإرجاع:**
int
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract IChartCategory add(IChartDataCell chartDataCell)
```

إذا كانت الفئة موجودة في المجموعة، فارجعها. وإلا يُنشئ فئة مخطط جديدة من [IChartDataCell](../../com.aspose.slides/ichartdatacell) ويضيفها إلى المجموعة.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cell يُستخدم لإنشاء فئة المخطط. |

**الإرجاع:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - الفئة المضافة أو الموجودة.
### add(Object value) {#add-java.lang.Object-}
```
public abstract IChartCategory add(Object value)
```

ينشئ [IChartCategory](../../com.aspose.slides/ichartcategory) جديدًا من القيمة ويضيفه إلى المجموعة.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object | القيمة.

--------------------

هذه الطريقة تُضيف ورقة عمل بالاسم AUTO_DATA وتضيف جميع القيم هناك. إذا استخدمت [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) لإضافة أو تعديل قيم الخلايا، تأكد من عدم استخدام هذه الورقة. يجب ألا يتجاوز الحد الأقصى لعدد القيم المضافة باستخدام هذه الطريقة 16711680

**الإرجاع:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - تم إضافة [IChartCategory](../../com.aspose.slides/ichartcategory).
### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public abstract int indexOf(IChartCategory value)
```

يبحث عن [IChartCategory](../../com.aspose.slides/ichartcategory) المحدد ويعيد الفهرس الصفري للظهور الأول داخل المجموعة الكاملة

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | فئة المخطط. |

**الإرجاع:**
int - الفهرس الصفري للظهور الأول للقيمة داخل CollectionBase بالكامل، إذا وجد؛ وإلا -1.
### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public abstract void remove(IChartCategory value)
```

يزيل القيمة المحددة.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | القيمة. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

يزيل العنصر عند الفهرس المحدد.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | فهرس الفئة المُزالة. |

### clear() {#clear--}
```
public abstract void clear()
```

يزيل جميع العناصر من المجموعة.