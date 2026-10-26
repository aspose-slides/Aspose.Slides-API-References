---
title: IDataLabelCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API للـ Java
description: يمثل تسميات السلسلة.
type: docs
url: /ar/com.aspose.slides/idatalabelcollection/
---
**جميع الواجهات المُنفذة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IDataLabelCollection extends System.Collections.Generic.IGenericEnumerable<IDataLabel>, IChartComponent
```

يمثل تسميات السلسلة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يحصل على تسمية البيانات للنقطة ذات الفهرس المحدد. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | يعيد التنسيق الافتراضي لجميع تسميات البيانات في المجموعة. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | يمثل تنسيق خطوط القادة لتسميات البيانات. |
| [isVisible()](#isVisible--) | False يعني أن تسمية البيانات غير مرئية افتراضيًا (وبالتالي جميع أعلام Show* (ShowValue, ...) لخاصية DefaultDataLabelFormat تكون false). |
| [hide()](#hide--) | اجعل تسمية البيانات مخفية افتراضيًا عن طريق ضبط جميع أعلام Show* (ShowValue, ...) لخاصية DefaultDataLabelFormat إلى الحالة false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | يحصل على عدد تسميات البيانات المرئية في المجموعة. |
| [getCount()](#getCount--) | يحصل على عدد جميع تسميات البيانات في المجموعة. |
| [getParentSeries()](#getParentSeries--) | يعيد سلسلة المخطط الأصلية. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | يعيد فهرس DataLabel المحدد في المجموعة. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```

يحصل على تسمية البيانات للنقطة ذات الفهرس المحدد.

--------------------

طريقة بديلة للوصول إلى تسمية البيانات هي: - getSeries().getDataPoints().get_Item(i).getLabel() - إدارة خصائص التسمية.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**الإرجاع:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public abstract IDataLabelFormat getDefaultDataLabelFormat()
```

يعيد التنسيق الافتراضي لجميع تسميات البيانات في المجموعة. قراءة فقط [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**الإرجاع:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
```

يمثل تنسيق خطوط القادة لتسميات البيانات. قراءة فقط [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IChart chart = (IChart) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      IDataLabelCollection labels = series.get_Item(0).getLabels();
>      labels.getLeaderLinesFormat().getLine().getFillFormat().setFillType(FillType.Solid);
>      labels.getLeaderLinesFormat().getLine().getFillFormat().getSolidFillColor().setColor(Color.RED);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**الإرجاع:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False يعني أن تسمية البيانات غير مرئية افتراضيًا (وبالتالي جميع أعلام Show* (ShowValue, ...) لخاصية DefaultDataLabelFormat تكون false). قراءة فقط  boolean .

--------------------

إذا كانت تسمية البيانات مرئية افتراضيًا يمكنك جعلها مخفية افتراضيًا باستخدام طريقة Hide(). لكن إذا كانت تسمية البيانات غير مرئية افتراضيًا (IsVisible هو false) يمكنك جعلها "مرئية افتراضيًا" بضبط أعلام Show* (ShowValue, ...) لخاصية DefaultDataLabelFormat إلى الحالة true.

**الإرجاع:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

اجعل تسمية البيانات مخفية افتراضيًا عن طريق ضبط جميع أعلام Show* (ShowValue, ...) لخاصية DefaultDataLabelFormat إلى الحالة false. سيكون IsVisible false بعد ذلك.

--------------------

إذا كانت تسمية البيانات غير مرئية افتراضيًا (IsVisible هو false) يمكنك جعلها "مرئية افتراضيًا" بضبط أعلام Show* (ShowValue, ...) لخاصية DefaultDataLabelFormat إلى الحالة true.
### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```

يحصل على عدد تسميات البيانات المرئية في المجموعة. قراءة فقط  int .

**الإرجاع:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```

يحصل على عدد جميع تسميات البيانات في المجموعة. قراءة فقط  int .

**الإرجاع:**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```

يعيد سلسلة المخطط الأصلية. قراءة فقط [IChartSeries](../../com.aspose.slides/ichartseries).

**الإرجاع:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public abstract int indexOf(IDataLabel value)
```

يعيد فهرس DataLabel المحدد في المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel للبحث عنه. |

**الإرجاع:**
int - فهرس DataLabel أو -1 إذا لم يكن DataLabel من هذه المجموعة.