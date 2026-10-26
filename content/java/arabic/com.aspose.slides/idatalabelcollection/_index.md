---
title: IDataLabelCollection
second_title: Aspose.Slides لمرجع API جافا
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
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | يرجع التنسيق الافتراضي لجميع تسميات البيانات في المجموعة. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | يمثل تنسيق خطوط القائد لتسميات البيانات. |
| [isVisible()](#isVisible--) | False يعني أن تسمية البيانات غير مرئية افتراضياً (وبالتالي جميع علمات Show*-flags (ShowValue, ...) لخاصية DefaultDataLabelFormat هي false). |
| [hide()](#hide--) | اجعل تسمية البيانات مخفية افتراضياً عن طريق ضبط جميع علمات Show*-flags (ShowValue, ...) لخاصية DefaultDataLabelFormat إلى الحالة false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | يحصل على عدد تسميات البيانات المرئية في المجموعة. |
| [getCount()](#getCount--) | يحصل على عدد جميع تسميات البيانات في المجموعة. |
| [getParentSeries()](#getParentSeries--) | يرجع السلسلة الأصلية للمخطط. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | يرجع فهرس DataLabel المحدد في المجموعة. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```

يحصل على تسمية البيانات للنقطة ذات الفهرس المحدد.

--------------------

طريقة بديلة للوصول إلى تسمية البيانات هي: - getSeries().getDataPoints().get_Item(i).getLabel() - إدارة خصائص التسمية.

**الوسائط:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**الإرجاع:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public abstract IDataLabelFormat getDefaultDataLabelFormat()
```

يرجع التنسيق الافتراضي لجميع تسميات البيانات في المجموعة. للقراءة فقط [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**الإرجاع:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
```

يمثل تنسيق خطوط القائد لتسميات البيانات. للقراءة فقط [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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
>      labels.getLeaderLinesFormat().getLine().getFillFormat().getSolidFillColor().setColor(new java.awt.Color(255, 0, 0, 255));
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

False يعني أن تسمية البيانات غير مرئية افتراضياً (وبالتالي جميع علمات Show*-flags (ShowValue, ...) لخاصية DefaultDataLabelFormat هي false). للقراءة فقط boolean .

--------------------

إذا كانت تسمية البيانات مرئية افتراضياً يمكنك إخفاؤها افتراضياً باستخدام طريقة Hide(). ولكن إذا كانت تسمية البيانات غير مرئية افتراضياً (IsVisible هو false) يمكنك جعلها "مرئية افتراضياً" عن طريق ضبط علمات Show*-flags (ShowValue, ...) لخاصية DefaultDataLabelFormat إلى الحالة true.

**الإرجاع:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

اجعل تسمية البيانات مخفية افتراضياً عن طريق ضبط جميع علمات Show*-flags (ShowValue, ...) لخاصية DefaultDataLabelFormat إلى الحالة false. سيكون IsVisible يساوي false بعد ذلك.

--------------------

إذا كانت تسمية البيانات غير مرئية افتراضياً (IsVisible هو false) يمكنك جعلها "مرئية افتراضياً" عن طريق ضبط علمات Show*-flags (ShowValue, ...) لخاصية DefaultDataLabelFormat إلى الحالة true.
### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```

يحصل على عدد تسميات البيانات المرئية في المجموعة. للقراءة فقط int .

**الإرجاع:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```

يحصل على عدد جميع تسميات البيانات في المجموعة. للقراءة فقط int .

**الإرجاع:**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```

يرجع السلسلة الأصلية للمخطط. للقراءة فقط [IChartSeries](../../com.aspose.slides/ichartseries).

**الإرجاع:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public abstract int indexOf(IDataLabel value)
```

يرجع فهرس DataLabel المحدد في المجموعة.

**الوسائط:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel للبحث عنه. |

**الإرجاع:**
int - فهرس DataLabel أو -1 إذا لم يكن DataLabel من هذه المجموعة.