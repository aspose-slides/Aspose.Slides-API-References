---
title: IChartCategoryCollection
second_title: Aspose.Slides لأندرويد عبر مرجع API لجافا
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

| طريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر عند الـ index المحدد. |
| [getUseCells()](#getUseCells--) | إذا كان true فإن ورقة العمل تُستخدم لتخزين الفئات (هذا الحال يدعم فئات متعددة المستويات). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | إذا كان true فإن ورقة العمل تُستخدم لتخزين الفئات (هذا الحال يدعم فئات متعددة المستويات). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | يُرجع عدد مستويات تجميع الفئات المستخدمة. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | إذا كانت الفئة موجودة في المجموعة، تُرجِعها. |
| [add(Object value)](#add-java.lang.Object-) | ينشئ [IChartCategory](../../com.aspose.slides/ichartcategory) جديدًا من القيمة ويضيفه إلى المجموعة. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | يبحث عن [IChartCategory](../../com.aspose.slides/ichartcategory) المحدد ويُرجع الفهرس الصفري للظهور الأول داخل Collection |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | يزيل القيمة المحددة. |
| [removeAt(int index)](#removeAt-int-) | يزيل العنصر عند الـ index المحدد. |
| [clear()](#clear--) | يزيل جميع العناصر من المجموعة. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartCategory get_Item(int index)
```


يحصل على العنصر عند الـ index المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**الإرجاع:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - العنصر عند الـ index المحدد.
### getUseCells() {#getUseCells--}
```
public abstract boolean getUseCells()
```


إذا كان true فإن ورقة العمل تُستخدم لتخزين الفئات (هذا الحال يدعم فئات متعددة المستويات). إذا كان false فإن ورقة العمل لا تُستخدم لتخزين القيم (وهذا الحال لا يدعم فئات متعددة المستويات). قابل للقراءة/الكتابة من النوع boolean.

**الإرجاع:**
boolean
### setUseCells(boolean value) {#setUseCells-boolean-}
```
public abstract void setUseCells(boolean value)
```


إذا كان true فإن ورقة العمل تُستخدم لتخزين الفئات (هذا الحال يدعم فئات متعددة المستويات). إذا كان false فإن ورقة العمل لا تُستخدم لتخزين القيم (وهذا الحال لا يدعم فئات متعددة المستويات). قابل للقراءة/الكتابة من النوع boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public abstract int getGroupingLevelCount()
```


يُرجع عدد مستويات تجميع الفئات المستخدمة. يكون أكبر من واحد للفئات متعددة المستويات. للقراءة فقط int.

**الإرجاع:**
int
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract IChartCategory add(IChartDataCell chartDataCell)
```


إذا كانت الفئة موجودة في المجموعة، تُرجِعها. وإلا ينشئ فئة مخطط جديدة من [IChartDataCell](../../com.aspose.slides/ichartdatacell) ويضيفها إلى المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | الخلية المستخدمة لإنشاء فئة المخطط. |

**الإرجاع:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - الفئة المضافة أو الموجودة.
### add(Object value) {#add-java.lang.Object-}
```
public abstract IChartCategory add(Object value)
```


ينشئ [IChartCategory](../../com.aspose.slides/ichartcategory) جديدًا من القيمة ويضيفه إلى المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.Object | القيمة.

--------------------

تضيف هذه الطريقة ورقة عمل بالاسم AUTO_DATA وتضيف جميع القيم هناك. إذا كنت تستخدم [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) لإضافة أو تعديل قيم الخلايا، تأكد من عدم استخدام هذه الورقة. الحد الأقصى لعدد القيم التي تُضاف باستخدام هذه الطريقة يجب ألا يتجاوز 16711680

**الإرجاع:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - [IChartCategory](../../com.aspose.slides/ichartcategory) المضاف.
### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public abstract int indexOf(IChartCategory value)
```


يبحث عن [IChartCategory](../../com.aspose.slides/ichartcategory) المحدد ويُرجع الفهرس الصفري للظهور الأول داخل Collection

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | فئة المخطط. |

**الإرجاع:**
int - الفهرس الصفري للظهور الأول للقيمة داخل CollectionBase، إذا تم العثور عليها؛ وإلا -1.
### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public abstract void remove(IChartCategory value)
```


يزيل القيمة المحددة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | القيمة. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


يزيل العنصر عند الـ index المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الفئة المراد إزالتها. |

### clear() {#clear--}
```
public abstract void clear()
```


يزيل جميع العناصر من المجموعة.