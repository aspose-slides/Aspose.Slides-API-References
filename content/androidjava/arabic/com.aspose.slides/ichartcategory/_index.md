---
title: IChartCategory
second_title: Aspose.Slides for Android via Java API Reference
description: يمثل فئات المخطط.
type: docs
url: /ar/com.aspose.slides/ichartcategory/
---```
public interface IChartCategory
```

يمثل فئات المخطط.
## Methods

| طريقة | الوصف |
| --- | --- |
| [getUseCell()](#getUseCell--) | إذا كان true فإن خاصية AsCell هي الفعلية. |
| [getAsCell()](#getAsCell--) | إرجاع أو تعيين كائن IChartDataCell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | إرجاع أو تعيين كائن IChartDataCell. |
| [getAsLiteral()](#getAsLiteral--) | إرجاع أو تعيين AsLiteral إذا كان UseCell false. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | إرجاع أو تعيين AsLiteral إذا كان UseCell false. |
| [getValue()](#getValue--) | إذا كان UseCell true فإن هذه الخاصية تمثل خاصية AsCell.Value. |
| [setValue(Object value)](#setValue-java.lang.Object-) | إذا كان UseCell true فإن هذه الخاصية تمثل خاصية AsCell.Value. |
| [getGroupingLevels()](#getGroupingLevels--) | حاوية مُدارة لقيم مستويات تجميع فئات المخطط. |
| [remove()](#remove--) | إزالة الفئة من المخطط. |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```

إذا كان true فإن خاصية AsCell هي الفعلية. بمعنى آخر، يتم استخدام ورقة العمل لتخزين الفئة (هذا السيناريو يدعم فئة متعددة المستويات). إذا كان false فإن خاصية AsLiteral هي الفعلية. بمعنى آخر، لا يتم استخدام ورقة العمل لتخزين الفئة (وهذا السيناريو لا يدعم فئات متعددة المستويات). Boolean للقراءة فقط.

--------------------

لتغيير قيمة هذه الخاصية (لكافة الفئات في المجموعة) اضبط القيمة الجديدة إلى خاصية [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--).

**الإرجاع:**
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```

إرجاع أو تعيين كائن IChartDataCell. إذا كانت الفئة متعددة المستويات فإن كائن IChartDataCell المُستخدم للمستوى "0". قابل للقراءة والكتابة [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**الإرجاع:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```

إرجاع أو تعيين كائن IChartDataCell. إذا كانت الفئة متعددة المستويات فإن كائن IChartDataCell المُستخدم للمستوى "0". قابل للقراءة والكتابة [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```

إرجاع أو تعيين AsLiteral إذا كان UseCell false. قابل للقراءة والكتابة Object.

**الإرجاع:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```

إرجاع أو تعيين AsLiteral إذا كان UseCell false. قابل للقراءة والكتابة Object.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.Object |  |
### getValue() {#getValue--}
```
public abstract Object getValue()
```

إذا كان UseCell true فإن هذه الخاصية تمثل خاصية AsCell.Value. إذا كان UseCell false فإن هذه الخاصية تمثل خاصية AsLiteral. قابل للقراءة والكتابة Object.

**الإرجاع:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

إذا كان UseCell true فإن هذه الخاصية تمثل خاصية AsCell.Value. إذا كان UseCell false فإن هذه الخاصية تمثل خاصية AsLiteral. قابل للقراءة والكتابة Object.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.Object |  |
### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```

حاوية مُدارة لقيم مستويات تجميع فئات المخطط. الفئة متعددة المستويات تحتوي على أكثر من مستوى تجميع واحد. فهرسة مستويات التجميع تبدأ من الصفر. قراءة فقط [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**الإرجاع:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```

إزالة الفئة من المخطط.