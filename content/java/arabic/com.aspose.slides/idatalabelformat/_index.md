---
title: IDataLabelFormat
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل خيارات التنسيق لـ DataLabel.
type: docs
url: /ar/com.aspose.slides/idatalabelformat/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IDataLabelFormat extends IFormattedTextContainer
```

يمثل خيارات تنسيق لـ DataLabel.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | قراءة/كتابة boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | قراءة/كتابة boolean. |
| [getNumberFormat()](#getNumberFormat--) | يمثل سلسلة التنسيق لكائن DataLabels. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | يمثل سلسلة التنسيق لكائن DataLabels. |
| [getFormat()](#getFormat--) | يمثل تنسيق تسمية البيانات. |
| [getPosition()](#getPosition--) | يمثل موقع تسمية البيانات. |
| [setPosition(int value)](#setPosition-int-) | يمثل موقع تسمية البيانات. |
| [getShowLegendKey()](#getShowLegendKey--) | يمثل سلوك عرض مفتاح وسمة تسمية البيانات لمخطط محدد. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | يمثل سلوك عرض مفتاح وسمة تسمية البيانات لمخطط محدد. |
| [getShowValue()](#getShowValue--) | يمثل سلوك عرض قيمة النسبة المئوية لتسمية البيانات لمخطط محدد. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | يمثل سلوك عرض قيمة النسبة المئوية لتسمية البيانات لمخطط محدد. |
| [getShowCategoryName()](#getShowCategoryName--) | يمثل سلوك عرض اسم الفئة لتسمية البيانات لمخطط محدد. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | يمثل سلوك عرض اسم الفئة لتسمية البيانات لمخطط محدد. |
| [getShowSeriesName()](#getShowSeriesName--) | يرجع أو يضع Boolean لتحديد سلوك عرض اسم السلسلة لتسميات البيانات على مخطط. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | يرجع أو يضع Boolean لتحديد سلوك عرض اسم السلسلة لتسميات البيانات على مخطط. |
| [getShowPercentage()](#getShowPercentage--) | يمثل سلوك عرض قيمة النسبة المئوية لتسمية البيانات لمخطط محدد. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | يمثل سلوك عرض قيمة النسبة المئوية لتسمية البيانات لمخطط محدد. |
| [getShowBubbleSize()](#getShowBubbleSize--) | يمثل سلوك عرض قيمة حجم الفقاعات لتسمية البيانات لمخطط محدد. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | يمثل سلوك عرض قيمة حجم الفقاعات لتسمية البيانات لمخطط محدد. |
| [getShowLeaderLines()](#getShowLeaderLines--) | يمثل سلوك عرض خطوط القائد لتسمية البيانات لمخطط محدد. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | يمثل سلوك عرض خطوط القائد لتسمية البيانات لمخطط محدد. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | يحدد ما إذا كانت تسمية البيانات لمخطط محدد سيُعرض كإشارة بيانات أو كتسمية بيانات. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | يحدد ما إذا كانت تسمية البيانات لمخطط محدد سيُعرض كإشارة بيانات أو كتسمية بيانات. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | يمثل سلوك عرض قيمة خلية التسمية لمخطط محدد. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | يمثل سلوك عرض قيمة خلية التسمية لمخطط محدد. |
| [getSeparator()](#getSeparator--) | يضبط أو يرجع Variant يمثل الفاصل المستخدم لتسميات البيانات على مخطط. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | يضبط أو يرجع Variant يمثل الفاصل المستخدم لتسميات البيانات على مخطط. |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

قراءة/كتابة boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات، فإن هذه الخاصية تحصل على أو تضبط القيمة الافتراضية لخاصية IsNumberFormatLinkedToSource لتسميات البيانات الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة سيقوم أيضًا بضبط هذه القيمة لخاصية IsNumberFormatLinkedToSource لجميع تسميات البيانات في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" يسبب أن تكون جميع DataLabels.get_Item(i).isNumberFormatLinkedToSource() مساوية للقيمة).

**القيمة المرجعة:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

قراءة/كتابة boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات، فإن هذه الخاصية تحصل على أو تضبط القيمة الافتراضية لخاصية IsNumberFormatLinkedToSource لتسميات البيانات الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة سيقوم أيضًا بضبط هذه القيمة لخاصية IsNumberFormatLinkedToSource لجميع تسميات البيانات في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" يسبب أن تكون جميع DataLabels.get_Item(i).isNumberFormatLinkedToSource() مساوية للقيمة).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

يمثل سلسلة التنسيق لكائن DataLabels. قراءة/كتابة String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```


--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات، فإن هذه الخاصية تحصل على أو تضبط القيمة الافتراضية لخاصية NumberFormat لتسميات البيانات الجديدة في مجموعة DataLabelCollection. عندما يتم ضبط هذه الخاصية بقيمة، يتم أيضًا ضبط تلك القيمة لخاصية NumberFormat لجميع تسميات البيانات في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" يسبب أن تكون جميع DataLabels.get_Item(i).getNumberFormat() مساوية للقيمة).

**القيمة المرجعة:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

يمثل سلسلة التنسيق لكائن DataLabels. قراءة/كتابة String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```


--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات، فإن هذه الخاصية تحصل على أو تضبط القيمة الافتراضية لخاصية NumberFormat لتسميات البيانات الجديدة في مجموعة DataLabelCollection. عندما يتم ضبط هذه الخاصية بقيمة، يتم أيضًا ضبط تلك القيمة لخاصية NumberFormat لجميع تسميات البيانات في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" يسبب أن تكون جميع DataLabels.get_Item(i).getNumberFormat() مساوية للقيمة).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

يمثل تنسيق تسمية البيانات. قراءة فقط [IFormat](../../com.aspose.slides/iformat).

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات فإن هذه الخاصية تمثل التنسيق الافتراضي لتسميات البيانات الجديدة في مجموعة DataLabelCollection.

**القيمة المرجعة:**
[IFormat](../../com.aspose.slides/iformat)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

يمثل موقع تسمية البيانات. قراءة/كتابة [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات فإن هذه الخاصية تحصل على أو تضبط القيمة الافتراضية لخاصية Position لتسميات البيانات الجديدة في مجموعة DataLabelCollection. يمثل الموقع لكائنات DataLabel. ضبط هذه الخاصية بقيمة سيقوم أيضًا بضبط تلك القيمة لخاصية Position لجميع تسميات البيانات في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setPosition(val)" يسبب أن تكون جميع DataLabels.get_Item(i).getPosition() مساوية للقيمة).

**القيمة المرجعة:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

يمثل موقع تسمية البيانات. قراءة/كتابة [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات فإن هذه الخاصية تحصل على أو تضبط القيمة الافتراضية لخاصية Position لتسميات البيانات الجديدة في مجموعة DataLabelCollection. يمثل الموقع لكائنات DataLabel. ضبط هذه الخاصية بقيمة سيقوم أيضًا بضبط تلك القيمة لخاصية Position لجميع تسميات البيانات في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setPosition(val)" يسبب أن تكون جميع DataLabels.get_Item(i).getPosition() مساوية للقيمة).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public abstract boolean getShowLegendKey()
```

يمثل سلوك عرض مفتاح وسمة تسمية البيانات لمخطط محدد. true إذا كان مفتاح وسمة التسمية مرئيًا. قراءة/كتابة boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات فإن هذه الخاصية تحصل على أو تضبط القيمة الافتراضية لخاصية ShowLegendKey لتسميات البيانات الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة سيقوم أيضًا بضبط تلك القيمة لخاصية ShowLegendKey لجميع تسميات البيانات في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" يسبب أن تكون جميع DataLabels.get_Item(i).getShowLegendKey() مساوية للقيمة).

**القيمة المرجعة:**
boolean
### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public abstract void setShowLegendKey(boolean value)
```

يمثل سلوك عرض مفتاح وسمة تسمية البيانات لمخطط محدد. true إذا كان مفتاح وسمة التسمية مرئيًا. قراءة/كتابة boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات فإن هذه الخاصية تحصل على أو تضبط القيمة الافتراضية لخاصية ShowLegendKey لتسميات البيانات الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة سيقوم أيضًا بضبط تلك القيمة لخاصية ShowLegendKey لجميع تسميات البيانات في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" يسبب أن تكون جميع DataLabels.get_Item(i).getShowLegendKey() مساوية للقيمة).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public abstract boolean getShowValue()
```

يمثل سلوك عرض قيمة النسبة المئوية لتسمية البيانات لمخطط محدد. true يعرض القيمة النسبية. false يخفيها. قراءة/كتابة boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات فإن هذه الخاصية تحصل على أو تضبط القيمة الافتراضية لخاصية ShowValue لتسميات البيانات الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة سيقوم أيضًا بضبط تلك القيمة لخاصية ShowValue لجميع تسميات البيانات في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" يسبب أن تكون جميع DataLabels.get_Item(i).getShowValue() مساوية للقيمة).

**القيمة المرجعة:**
boolean
### setShowValue(boolean value) {#setShowValue-boolean-}
```
public abstract void setShowValue(boolean value)
```

يمثل سلوك عرض قيمة النسبة المئوية لتسمية البيانات لمخطط محدد. true يعرض القيمة النسبية. false يخفيها. قراءة/كتابة boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات فإن هذه الخاصية تحصل على أو تضبط القيمة الافتراضية لخاصية ShowValue لتسميات البيانات الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة سيقوم أيضًا بضبط تلك القيمة لخاصية ShowValue لجميع تسميات البيانات في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" يسبب أن تكون جميع DataLabels.get_Item(i).getShowValue() مساوية للقيمة).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public abstract boolean getShowCategoryName()
```

يمثل سلوك عرض اسم الفئة لتسمية البيانات لمخطط محدد. true لعرض اسم الفئة لتسميات البيانات على مخطط. false للإخفاء. قراءة/كتابة boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات فإن هذه الخاصية تحصل على أو تضبط القيمة الافتراضية لخاصية ShowCategoryName لتسميات البيانات الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة سيقوم أيضًا بضبط تلك القيمة لخاصية ShowCategoryName لجميع تسميات البيانات في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" يسبب أن تكون جميع DataLabels.get_Item(i).getShowCategoryName() مساوية للقيمة).

**القيمة المرجعة:**
boolean
### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public abstract void setShowCategoryName(boolean value)
```

يمثل سلوك عرض اسم الفئة لتسمية البيانات لمخطط محدد. true لعرض اسم الفئة لتسميات البيانات على مخطط. false للإخفاء. قراءة/كتابة boolean.

--------------------
إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات فإن هذه الخاصية تحصل أو تعيين القيمة الافتراضية للخاصية ShowCategoryName لتسميات البيانات الجديدة في مجموعة DataLabelCollection. تعيين هذه الخاصية بالقيمة يضبط أيضاً هذه القيمة للخاصية ShowCategoryName لجميع تسميات البيانات في مجموعة DataLabelCollection (على سبيل المثال "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" يؤدي إلى أن جميع DataLabels.get_Item(i).getShowCategoryName() يساوي val).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public abstract boolean getShowSeriesName()
```

يُعيد أو يحدد قيمة Boolean لتحديد سلوك عرض اسم السلسلة لتسميات البيانات على المخطط. True لإظهار اسم السلسلة. False لإخفائه. قابل للقراءة والكتابة Boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات فإن هذه الخاصية تحصل أو تعيين القيمة الافتراضية للخاصية ShowSeriesName لتسميات البيانات الجديدة في مجموعة DataLabelCollection. تعيين هذه الخاصية بالقيمة يضبط أيضاً هذه القيمة للخاصية ShowSeriesName لجميع تسميات البيانات في مجموعة DataLabelCollection (على سبيل المثال "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" يؤدي إلى أن جميع DataLabels.get_Item(i).getShowSeriesName() يساوي val).

**القيمة المرجعة:**
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public abstract void setShowSeriesName(boolean value)
```

يُعيد أو يحدد قيمة Boolean لتحديد سلوك عرض اسم السلسلة لتسميات البيانات على المخطط. True لإظهار اسم السلسلة. False لإخفائه. قابل للقراءة والكتابة Boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات فإن هذه الخاصية تحصل أو تعيين القيمة الافتراضية للخاصية ShowSeriesName لتسميات البيانات الجديدة في مجموعة DataLabelCollection. تعيين هذه الخاصية بالقيمة يضبط أيضاً هذه القيمة للخاصية ShowSeriesName لجميع تسميات البيانات في مجموعة DataLabelCollection (على سبيل المثال "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" يؤدي إلى أن جميع DataLabels.get_Item(i).getShowSeriesName() يساوي val).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public abstract boolean getShowPercentage()
```

يمثل سلوك عرض قيمة النسبة المئوية لتسمية البيانات في مخطط محدد. True لعرض القيمة النسبية. False للإخفاء. قابل للقراءة والكتابة Boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات فإن هذه الخاصية تحصل أو تعيين القيمة الافتراضية للخاصية ShowPercentage لتسميات البيانات الجديدة في مجموعة DataLabelCollection. تعيين هذه الخاصية بالقيمة يضبط أيضاً هذه القيمة للخاصية ShowPercentage لجميع تسميات البيانات في مجموعة DataLabelCollection (على سبيل المثال "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" يؤدي إلى أن جميع DataLabels.get_Item(i).getShowPercentage() يساوي val).

**القيمة المرجعة:**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public abstract void setShowPercentage(boolean value)
```

يمثل سلوك عرض قيمة النسبة المئوية لتسمية البيانات في مخطط محدد. True لعرض القيمة النسبية. False للإخفاء. قابل للقراءة والكتابة Boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات فإن هذه الخاصية تحصل أو تعيين القيمة الافتراضية للخاصية ShowPercentage لتسميات البيانات الجديدة في مجموعة DataLabelCollection. تعيين هذه الخاصية بالقيمة يضبط أيضاً هذه القيمة للخاصية ShowPercentage لجميع تسميات البيانات في مجموعة DataLabelCollection (على سبيل المثال "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" يؤدي إلى أن جميع DataLabels.get_Item(i).getShowPercentage() يساوي val).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public abstract boolean getShowBubbleSize()
```

يمثل سلوك عرض قيمة حجم الفقاعة لتسمية البيانات في مخطط محدد. True لعرض قيمة حجم الفقاعة. False للإخفاء. قابل للقراءة والكتابة Boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات فإن هذه الخاصية تحصل أو تعيين القيمة الافتراضية للخاصية ShowBubbleSize لتسميات البيانات الجديدة في مجموعة DataLabelCollection. تعيين هذه الخاصية بالقيمة يضبط أيضاً هذه القيمة للخاصية ShowBubbleSize لجميع تسميات البيانات في مجموعة DataLabelCollection (على سبيل المثال "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" يؤدي إلى أن جميع DataLabels.get_Item(i).getShowBubbleSize() يساوي val).

**القيمة المرجعة:**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public abstract void setShowBubbleSize(boolean value)
```

يمثل سلوك عرض قيمة حجم الفقاعة لتسمية البيانات في مخطط محدد. True لعرض قيمة حجم الفقاعة. False للإخفاء. قابل للقراءة والكتابة Boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات فإن هذه الخاصية تحصل أو تعيين القيمة الافتراضية للخاصية ShowBubbleSize لتسميات البيانات الجديدة في مجموعة DataLabelCollection. تعيين هذه الخاصية بالقيمة يضبط أيضاً هذه القيمة للخاصية ShowBubbleSize لجميع تسميات البيانات في مجموعة DataLabelCollection (على سبيل المثال "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" يؤدي إلى أن جميع DataLabels.get_Item(i).getShowBubbleSize() يساوي val).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public abstract boolean getShowLeaderLines()
```

يمثل سلوك عرض خطوط القائد لتسمية البيانات في مخطط محدد. True لعرض خطوط القائد. False للإخفاء. قابل للقراءة والكتابة Boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات فإن هذه الخاصية تحصل أو تعيين القيمة الافتراضية للخاصية ShowLeaderLines لتسميات البيانات الجديدة في مجموعة DataLabelCollection. تعيين هذه الخاصية بالقيمة يضبط أيضاً هذه القيمة للخاصية ShowLeaderLines لجميع تسميات البيانات في مجموعة DataLabelCollection (على سبيل المثال "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" يؤدي إلى أن جميع DataLabels.get_Item(i).getShowLeaderLines() يساوي val).

**القيمة المرجعة:**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public abstract void setShowLeaderLines(boolean value)
```

يمثل سلوك عرض خطوط القائد لتسمية البيانات في مخطط محدد. True لعرض خطوط القائد. False للإخفاء. قابل للقراءة والكتابة Boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات فإن هذه الخاصية تحصل أو تعيين القيمة الافتراضية للخاصية ShowLeaderLines لتسميات البيانات الجديدة في مجموعة DataLabelCollection. تعيين هذه الخاصية بالقيمة يضبط أيضاً هذه القيمة للخاصية ShowLeaderLines لجميع تسميات البيانات في مجموعة DataLabelCollection (على سبيل المثال "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" يؤدي إلى أن جميع DataLabels.get_Item(i).getShowLeaderLines() يساوي val).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public abstract boolean getShowLabelAsDataCallout()
```

يحدد ما إذا كان سيُعرض تسمية البيانات في المخطط كنداء بيانات أم كتسمية بيانات.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات فإن هذه الخاصية تحصل أو تعيين القيمة الافتراضية للخاصية ShowLabelAsDataCallout لتسميات البيانات الجديدة في مجموعة DataLabelCollection. تعيين هذه الخاصية بالقيمة يضبط أيضاً هذه القيمة للخاصية ShowLabelAsDataCallout لجميع تسميات البيانات في مجموعة DataLabelCollection (على سبيل المثال "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" يؤدي إلى أن جميع DataLabels.get_Item(i).getShowLabelAsDataCallout() يساوي val).

**القيمة المرجعة:**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public abstract void setShowLabelAsDataCallout(boolean value)
```

يحدد ما إذا كان سيُعرض تسمية البيانات في المخطط كنداء بيانات أم كتسمية بيانات.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات فإن هذه الخاصية تحصل أو تعيين القيمة الافتراضية للخاصية ShowLabelAsDataCallout لتسميات البيانات الجديدة في مجموعة DataLabelCollection. تعيين هذه الخاصية بالقيمة يضبط أيضاً هذه القيمة للخاصية ShowLabelAsDataCallout لجميع تسميات البيانات في مجموعة DataLabelCollection (على سبيل المثال "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" يؤدي إلى أن جميع DataLabels.get_Item(i).getShowLabelAsDataCallout() يساوي val).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public abstract boolean getShowLabelValueFromCell()
```

يمثل سلوك عرض قيمة الخلية لتسمية البيانات في مخطط محدد. True لعرض قيمة الخلية. False للإخفاء. قابل للقراءة والكتابة Boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات فإن هذه الخاصية تحصل أو تعيين القيمة الافتراضية للخاصية ShowLabelValueFromCell لتسميات البيانات الجديدة في مجموعة DataLabelCollection. تعيين هذه الخاصية بالقيمة يضبط أيضاً هذه القيمة للخاصية ShowLabelValueFromCell لجميع تسميات البيانات في مجموعة DataLabelCollection (على سبيل المثال "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" يؤدي إلى أن جميع DataLabels.get_Item(i).getShowLabelValueFromCell() يساوي val).

**القيمة المرجعة:**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public abstract void setShowLabelValueFromCell(boolean value)
```

يمثل سلوك عرض قيمة الخلية لتسمية البيانات في مخطط محدد. True لعرض قيمة الخلية. False للإخفاء. قابل للقراءة والكتابة Boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات فإن هذه الخاصية تحصل أو تعيين القيمة الافتراضية للخاصية ShowLabelValueFromCell لتسميات البيانات الجديدة في مجموعة DataLabelCollection. تعيين هذه الخاصية بالقيمة يضبط أيضاً هذه القيمة للخاصية ShowLabelValueFromCell لجميع تسميات البيانات في مجموعة DataLabelCollection (على سبيل المثال "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" يؤدي إلى أن جميع DataLabels.get_Item(i).getShowLabelValueFromCell() يساوي val).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public abstract String getSeparator()
```

يضبط أو يُعيد Variant يمثل الفاصل المستخدم لتسميات البيانات على المخطط. قابل للقراءة والكتابة String.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات فإن هذه الخاصية تحصل أو تعيين القيمة الافتراضية للخاصية Separator لتسميات البيانات الجديدة في مجموعة DataLabelCollection. تعيين هذه الخاصية بالقيمة يضبط أيضاً هذه القيمة للخاصية Separator لجميع تسميات البيانات في مجموعة DataLabelCollection (على سبيل المثال "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" يؤدي إلى أن جميع DataLabels.get_Item(i).getSeparator() يساوي val).

**القيمة المرجعة:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public abstract void setSeparator(String value)
```

يضبط أو يُعيد Variant يمثل الفاصل المستخدم لتسميات البيانات على المخطط. قابل للقراءة والكتابة String.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات فإن هذه الخاصية تحصل أو تعيين القيمة الافتراضية للخاصية Separator لتسميات البيانات الجديدة في مجموعة DataLabelCollection. تعيين هذه الخاصية بالقيمة يضبط أيضاً هذه القيمة للخاصية Separator لجميع تسميات البيانات في مجموعة DataLabelCollection (على سبيل المثال "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" يؤدي إلى أن جميع DataLabels.get_Item(i).getSeparator() يساوي val).
**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |