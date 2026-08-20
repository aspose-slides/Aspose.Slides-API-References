---
title: IDataLabel
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل تسميات السلسلة.
type: docs
url: /ar/com.aspose.slides/idatalabel/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

يمثل تسميات السلسلة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [isVisible()](#isVisible--) | False يعني أن تسمية البيانات غير مرئية (وبالتالي جميع Show*-flags (ShowValue, ...) هي false). |
| [hide()](#hide--) | اجعل تسمية البيانات مخفية عن طريق تعيين جميع Show*-flags (ShowValue, ...) إلى الحالة false. |
| [getDataLabelFormat()](#getDataLabelFormat--) | إرجاع تنسيق تسمية البيانات. |
| [getValueFromCell()](#getValueFromCell--) | الحصول على أو تعيين خلية بيانات دفتر العمل. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | الحصول على أو تعيين خلية بيانات دفتر العمل. |
| [getActualLabelText()](#getActualLabelText--) | إرجاع نص التسمية الفعلي بناءً على إعدادات DataLabelFormat أو قيمة TextFrameForOverriding.Text. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False يعني أن تسمية البيانات غير مرئية (وبالتالي جميع Show*-flags (ShowValue, ...) هي false). قيمة منطقية للقراءة فقط.

--------------------

إذا كانت تسمية البيانات مرئية يمكنك إخفاؤها باستخدام طريقة Hide(). ولكن إذا كانت تسمية البيانات غير مرئية (IsVisible هي false) يمكنك جعلها مرئية عن طريق تعيين Show*-flags (ShowValue, ...) إلى الحالة true.

**القيمة المرجعة:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

اجعل تسمية البيانات مخفية عن طريق تعيين جميع Show*-flags (ShowValue, ...) إلى الحالة false. سيكون IsVisible false بعد ذلك.

--------------------

إذا كانت تسمية البيانات غير مرئية (IsVisible هي false) يمكنك جعلها مرئية عن طريق تعيين Show*-flags (ShowValue, ...) إلى الحالة true.

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```

إرجاع تنسيق تسمية البيانات. للقراءة فقط [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**القيمة المرجعة:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```

الحصول على أو تعيين خلية بيانات دفتر العمل. يتم تطبيقها إذا كان خاصية IDataLabelFormat.ShowLabelValueFromCell تساوي true.

**القيمة المرجعة:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

الحصول على أو تعيين خلية بيانات دفتر العمل. يتم تطبيقها إذا كان خاصية IDataLabelFormat.ShowLabelValueFromCell تساوي true.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```

إرجاع نص التسمية الفعلي بناءً على إعدادات DataLabelFormat أو قيمة TextFrameForOverriding.Text.

**القيمة المرجعة:**
java.lang.String - نص التسمية الفعلي String