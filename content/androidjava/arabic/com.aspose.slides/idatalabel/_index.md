---
title: IDataLabel
second_title: Aspose.Slides لنظام Android عبر مرجع API للغة Java
description: يمثل تسميات السلسلة.
type: docs
url: /ar/com.aspose.slides/idatalabel/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

يمثل تسميات سلسلة.
## الطرق

| Method | Description |
| --- | --- |
| [isVisible()](#isVisible--) | False تعني أن تسمية البيانات غير مرئية (وبالتالي جميع Show*-flags (ShowValue, ...) تكون false). |
| [hide()](#hide--) | اجعل تسمية البيانات مخفية عن طريق ضبط جميع Show*-flags (ShowValue, ...) إلى الحالة false. |
| [getDataLabelFormat()](#getDataLabelFormat--) | يعيد تنسيق تسمية البيانات. |
| [getValueFromCell()](#getValueFromCell--) | يحصل أو يعيّن خلية بيانات المصنف. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | يحصل أو يعيّن خلية بيانات المصنف. |
| [getActualLabelText()](#getActualLabelText--) | يعيد نص التسمية الفعلي بناءً على إعدادات DataLabelFormat أو قيمة TextFrameForOverriding.Text. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False تعني أن تسمية البيانات غير مرئية (وبالتالي جميع Show*-flags (ShowValue, ...) تكون false). قيمة منطقية للقراءة فقط.

--------------------

إذا كانت تسمية البيانات مرئية يمكنك إخفاؤها باستخدام طريقة Hide(). ولكن إذا كانت تسمية البيانات غير مرئية (IsVisible هو false) يمكنك جعلها مرئية عن طريق ضبط Show*-flags (ShowValue, ...) إلى الحالة true.

**الإرجاع:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

اجعل تسمية البيانات مخفية عن طريق ضبط جميع Show*-flags (ShowValue, ...) إلى الحالة false. ستكون IsVisible مساوية لـ false بعد ذلك.

--------------------

إذا كانت تسمية البيانات غير مرئية (IsVisible هو false) يمكنك جعلها مرئية عن طريق ضبط Show*-flags (ShowValue, ...) إلى الحالة true.

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```

يعيد تنسيق تسمية البيانات. للقراءة فقط [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**الإرجاع:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```

يحصل أو يعيّن خلية بيانات المصنف. يتم التطبيق إذا كانت خاصية IDataLabelFormat.ShowLabelValueFromCell تساوي true.

**الإرجاع:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

يحصل أو يعيّن خلية بيانات المصنف. يتم التطبيق إذا كانت خاصية IDataLabelFormat.ShowLabelValueFromCell تساوي true.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```

يعيد نص التسمية الفعلي بناءً على إعدادات DataLabelFormat أو قيمة TextFrameForOverriding.Text.

**الإرجاع:**
java.lang.String - سلسلة نص العلامة الفعلية