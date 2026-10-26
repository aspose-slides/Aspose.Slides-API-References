---
title: IDataLabelFormat
second_title: Aspose.Slides لنظام Android عبر مرجع Java API
description: يمثل خيارات تنسيق لملصق البيانات.
type: docs
url: /ar/com.aspose.slides/idatalabelformat/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IDataLabelFormat extends IFormattedTextContainer
```

يمثل خيارات التنسيق ل DataLabel.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | قراءة/كتابة boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | قراءة/كتابة boolean. |
| [getNumberFormat()](#getNumberFormat--) | يمثل سلسلة التنسيق لكائن DataLabels. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | يمثل سلسلة التنسيق لكائن DataLabels. |
| [getFormat()](#getFormat--) | يمثل تنسيق ملصق البيانات. |
| [getPosition()](#getPosition--) | يمثل موضع ملصق البيانات. |
| [setPosition(int value)](#setPosition-int-) | يمثل موضع ملصق البيانات. |
| [getShowLegendKey()](#getShowLegendKey--) | يمثل سلوك عرض مفتاح أسطورة ملصق البيانات لمخطط محدد. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | يمثل سلوك عرض مفتاح أسطورة ملصق البيانات لمخطط محدد. |
| [getShowValue()](#getShowValue--) | يمثل سلوك عرض قيمة النسبة المئوية لملصق البيانات لمخطط محدد. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | يمثل سلوك عرض قيمة النسبة المئوية لملصق البيانات لمخطط محدد. |
| [getShowCategoryName()](#getShowCategoryName--) | يمثل سلوك عرض اسم الفئة لملصق البيانات لمخطط محدد. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | يمثل سلوك عرض اسم الفئة لملصق البيانات لمخطط محدد. |
| [getShowSeriesName()](#getShowSeriesName--) | إرجاع أو ضبط قيمة Boolean لتحديد سلوك عرض اسم السلسلة لملصقات البيانات على مخطط. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | إرجاع أو ضبط قيمة Boolean لتحديد سلوك عرض اسم السلسلة لملصقات البيانات على مخطط. |
| [getShowPercentage()](#getShowPercentage--) | يمثل سلوك عرض قيمة النسبة المئوية لملصق البيانات لمخطط محدد. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | يمثل سلوك عرض قيمة النسبة المئوية لملصق البيانات لمخطط محدد. |
| [getShowBubbleSize()](#getShowBubbleSize--) | يمثل سلوك عرض قيمة حجم الفقاعة لملصق البيانات لمخطط محدد. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | يمثل سلوك عرض قيمة حجم الفقاعة لملصق البيانات لمخطط محدد. |
| [getShowLeaderLines()](#getShowLeaderLines--) | يمثل سلوك عرض خطوط القادة لملصق البيانات لمخطط محدد. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | يمثل سلوك عرض خطوط القادة لملصق البيانات لمخطط محدد. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | يحدد ما إذا كان ملصق البيانات لمخطط محدد سيظهر كنداء بياني أو كملصق بيانات. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | يحدد ما إذا كان ملصق البيانات لمخطط محدد سيظهر كنداء بياني أو كملصق بيانات. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | يمثل سلوك عرض قيمة خلية الملصق لملصق البيانات لمخطط محدد. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | يمثل سلوك عرض قيمة خلية الملصق لملصق البيانات لمخطط محدد. |
| [getSeparator()](#getSeparator--) | ضبط أو إرجاع Variant يمثل الفاصل المستخدم لملصقات البيانات على مخطط. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | ضبط أو إرجاع Variant يمثل الفاصل المستخدم لملصقات البيانات على مخطط. |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

قراءة/كتابة boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من ملصقات البيانات، فإن هذه الخاصية تحصل على أو تعين القيمة الافتراضية لخاصية IsNumberFormatLinkedToSource لملصقات البيانات الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يضبط أيضاً هذه القيمة لخاصية IsNumberFormatLinkedToSource لجميع ملصقات البيانات في مجموعة DataLabelCollection (على سبيل المثال "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" يتسبب في أن تكون جميع DataLabels.get_Item(i).isNumberFormatLinkedToSource() مساوية لـ val).

**القيمة المرجعة:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

قراءة/كتابة boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من ملصقات البيانات، فإن هذه الخاصية تحصل على أو تعين القيمة الافتراضية لخاصية IsNumberFormatLinkedToSource لملصقات البيانات الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يضبط أيضاً هذه القيمة لخاصية IsNumberFormatLinkedToSource لجميع ملصقات البيانات في مجموعة DataLabelCollection (على سبيل المثال "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" يتسبب في أن تكون جميع DataLabels.get_Item(i).isNumberFormatLinkedToSource() مساوية لـ val).

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

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من ملصقات البيانات، فإن هذه الخاصية تحصل على أو تعين القيمة الافتراضية لخاصية NumberFormat لملصقات البيانات الجديدة في مجموعة DataLabelCollection. عند ضبط هذه الخاصية بقيمة، يتم ضبط تلك القيمة أيضاً لخاصية NumberFormat لجميع ملصقات البيانات في مجموعة DataLabelCollection (على سبيل المثال "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" يتسبب في أن تكون جميع DataLabels.get_Item(i).getNumberFormat() مساوية لـ val).

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

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من ملصقات البيانات، فإن هذه الخاصية تحصل على أو تعين القيمة الافتراضية لخاصية NumberFormat لملصقات البيانات الجديدة في مجموعة DataLabelCollection. عند ضبط هذه الخاصية بقيمة، يتم ضبط تلك القيمة أيضاً لخاصية NumberFormat لجميع ملصقات البيانات في مجموعة DataLabelCollection (على سبيل المثال "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" يتسبب في أن تكون جميع DataLabels.get_Item(i).getNumberFormat() مساوية لـ val).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

يمثل تنسيق ملصق البيانات. قراءة فقط [IFormat](../../com.aspose.slides/iformat).

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من ملصقات البيانات فإن هذه الخاصية تمثل التنسيق الافتراضي لملصقات البيانات الجديدة في مجموعة DataLabelCollection.

**القيمة المرجعة:**
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

يمثل موضع ملصق البيانات. قراءة/كتابة [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من ملصقات البيانات فإن هذه الخاصية تحصل على أو تعين القيمة الافتراضية لخاصية Position لملصقات البيانات الجديدة في مجموعة DataLabelCollection. تمثل الموضع لكائنات DataLabel. ضبط هذه الخاصية بقيمة يضبط أيضاً هذه القيمة لخاصية Position لجميع ملصقات البيانات في مجموعة DataLabelCollection (على سبيل المثال "DataLabels.getDefaultDataLabelFormat().setPosition(val)" يتسبب في أن تكون جميع DataLabels.get_Item(i).getPosition() مساوية لـ val).

**القيمة المرجعة:**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

يمثل موضع ملصق البيانات. قراءة/كتابة [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من ملصقات البيانات فإن هذه الخاصية تحصل على أو تعين القيمة الافتراضية لخاصية Position لملصقات البيانات الجديدة في مجموعة DataLabelCollection. تمثل الموضع لكائنات DataLabel. ضبط هذه الخاصية بقيمة يضبط أيضاً هذه القيمة لخاصية Position لجميع ملصقات البيانات في مجموعة DataLabelCollection (على سبيل المثال "DataLabels.getDefaultDataLabelFormat().setPosition(val)" يتسبب في أن تكون جميع DataLabels.get_Item(i).getPosition() مساوية لـ val).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public abstract boolean getShowLegendKey()
```

يمثل سلوك عرض مفتاح أسطورة ملصق البيانات لمخطط محدد. true إذا كان مفتاح الأسطورة مرئياً. قراءة/كتابة boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من ملصقات البيانات فإن هذه الخاصية تحصل على أو تعين القيمة الافتراضية لخاصية ShowLegendKey لملصقات البيانات الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يضبط أيضاً هذه القيمة لخاصية ShowLegendKey لجميع ملصقات البيانات في مجموعة DataLabelCollection (على سبيل المثال "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" يتسبب في أن تكون جميع DataLabels.get_Item(i).getShowLegendKey() مساوية لـ val).

**القيمة المرجعة:**
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public abstract void setShowLegendKey(boolean value)
```

يمثل سلوك عرض مفتاح أسطورة ملصق البيانات لمخطط محدد. true إذا كان مفتاح الأسطورة مرئياً. قراءة/كتابة boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من ملصقات البيانات فإن هذه الخاصية تحصل على أو تعين القيمة الافتراضية لخاصية ShowLegendKey لملصقات البيانات الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يضبط أيضاً هذه القيمة لخاصية ShowLegendKey لجميع ملصقات البيانات في مجموعة DataLabelCollection (على سبيل المثال "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" يتسبب في أن تكون جميع DataLabels.get_Item(i).getShowLegendKey() مساوية لـ val).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public abstract boolean getShowValue()
```

يمثل سلوك عرض قيمة النسبة المئوية لملصق البيانات لمخطط محدد. true يعرض القيمة النسبية. false لإخفائها. قراءة/كتابة boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من ملصقات البيانات فإن هذه الخاصية تحصل على أو تعين القيمة الافتراضية لخاصية ShowValue لملصقات البيانات الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يضبط أيضاً هذه القيمة لخاصية ShowValue لجميع ملصقات البيانات في مجموعة DataLabelCollection (على سبيل المثال "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" يتسبب في أن تكون جميع DataLabels.get_Item(i).getShowValue() مساوية لـ val).

**القيمة المرجعة:**
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public abstract void setShowValue(boolean value)
```

يمثل سلوك عرض قيمة النسبة المئوية لملصق البيانات لمخطط محدد. true يعرض القيمة النسبية. false لإخفائها. قراءة/كتابة boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من ملصقات البيانات فإن هذه الخاصية تحصل على أو تعين القيمة الافتراضية لخاصية ShowValue لملصقات البيانات الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يضبط أيضاً هذه القيمة لخاصية ShowValue لجميع ملصقات البيانات في مجموعة DataLabelCollection (على سبيل المثال "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" يتسبب في أن تكون جميع DataLabels.get_Item(i).getShowValue() مساوية لـ val).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public abstract boolean getShowCategoryName()
```

يمثل سلوك عرض اسم الفئة لملصق البيانات لمخطط محدد. true لعرض اسم الفئة لملصقات البيانات على مخطط. false لإخفائه. قراءة/كتابة boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من ملصقات البيانات فإن هذه الخاصية تحصل على أو تعين القيمة الافتراضية لخاصية ShowCategoryName لملصقات البيانات الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يضبط أيضاً هذه القيمة لخاصية ShowCategoryName لجميع ملصقات البيانات في مجموعة DataLabelCollection (على سبيل المثال "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" يتسبب في أن تكون جميع DataLabels.get_Item(i).getShowCategoryName() مساوية لـ val).

**القيمة المرجعة:**
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public abstract void setShowCategoryName(boolean value)
```

يمثل سلوك عرض اسم الفئة لملصق البيانات لمخطط محدد. true لعرض اسم الفئة لملصقات البيانات على مخطط. false لإخفائه. قراءة/كتابة boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من ملصقات البيانات فإن هذه الخاصية تحصل على أو تعين القيمة الافتراضية لخاصية ShowCategoryName لملصقات البيانات الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يضبط أيضاً هذه القيمة لخاصية ShowCategoryName لجميع ملصقات البيانات في مجموعة DataLabelCollection (على سبيل المثال "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" يتسبب في أن تكون جميع DataLabels.get_Item(i).getShowCategoryName() مساوية لـ val).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public abstract boolean getShowSeriesName()
```

إرجاع أو ضبط Boolean لتحديد سلوك عرض اسم السلسلة لملصقات البيانات على مخطط. true لعرض اسم السلسلة. false لإخفائه. قراءة/كتابة boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من ملصقات البيانات فإن هذه الخاصية تحصل على أو تعين القيمة الافتراضية لخاصية ShowSeriesName لملصقات البيانات الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يضبط أيضاً هذه القيمة لخاصية ShowSeriesName لجميع ملصقات البيانات في مجموعة DataLabelCollection (على سبيل المثال "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" يتسبب في أن تكون جميع DataLabels.get_Item(i).getShowSeriesName() مساوية لـ val).

**القيمة المرجعة:**
boolean

### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public abstract void setShowSeriesName(boolean value)
```

إرجاع أو ضبط Boolean لتحديد سلوك عرض اسم السلسلة لملصقات البيانات على مخطط. true لعرض اسم السلسلة. false لإخفائه. قراءة/كتابة boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من ملصقات البيانات فإن هذه الخاصية تحصل على أو تعين القيمة الافتراضية لخاصية ShowSeriesName لملصقات البيانات الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يضبط أيضاً هذه القيمة لخاصية ShowSeriesName لجميع ملصقات البيانات في مجموعة DataLabelCollection (على سبيل المثال "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" يتسبب في أن تكون جميع DataLabels.get_Item(i).getShowSeriesName() مساوية لـ val).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public abstract boolean getShowPercentage()
```

يمثل سلوك عرض قيمة النسبة المئوية لملصق البيانات لمخطط محدد. true يعرض القيمة النسبية. false لإخفائها. قراءة/كتابة boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من ملصقات البيانات فإن هذه الخاصية تحصل على أو تعين القيمة الافتراضية لخاصية ShowPercentage لملصقات البيانات الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يضبط أيضاً هذه القيمة لخاصية ShowPercentage لجميع ملصقات البيانات في مجموعة DataLabelCollection (على سبيل المثال "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" يتسبب في أن تكون جميع DataLabels.get_Item(i).getShowPercentage() مساوية لـ val).

**القيمة المرجعة:**
boolean

### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public abstract void setShowPercentage(boolean value)
```

يمثل سلوك عرض قيمة النسبة المئوية لملصق البيانات لمخطط محدد. true يعرض القيمة النسبية. false لإخفائها. قراءة/كتابة boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من ملصقات البيانات فإن هذه الخاصية تحصل على أو تعين القيمة الافتراضية لخاصية ShowPercentage لملصقات البيانات الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يضبط أيضاً هذه القيمة لخاصية ShowPercentage لجميع ملصقات البيانات في مجموعة DataLabelCollection (على سبيل المثال "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" يتسبب في أن تكون جميع DataLabels.get_Item(i).getShowPercentage() مساوية لـ val).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public abstract boolean getShowBubbleSize()
```

يمثل سلوك عرض قيمة حجم الفقاعة لملصق البيانات لمخطط محدد. true يعرض قيمة حجم الفقاعة. false لإخفائها. قراءة/كتابة boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من ملصقات البيانات فإن هذه الخاصية تحصل على أو تعين القيمة الافتراضية لخاصية ShowBubbleSize لملصقات البيانات الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يضبط أيضاً هذه القيمة لخاصية ShowBubbleSize لجميع ملصقات البيانات في مجموعة DataLabelCollection (على سبيل المثال "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" يتسبب في أن تكون جميع DataLabels.get_Item(i).getShowBubbleSize() مساوية لـ val).

**القيمة المرجعة:**
boolean

### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public abstract void setShowBubbleSize(boolean value)
```

يمثل سلوك عرض قيمة حجم الفقاعة لملصق البيانات لمخطط محدد. true يعرض قيمة حجم الفقاعة. false لإخفائها. قراءة/كتابة boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من ملصقات البيانات فإن هذه الخاصية تحصل على أو تعين القيمة الافتراضية لخاصية ShowBubbleSize لملصقات البيانات الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يضبط أيضاً هذه القيمة لخاصية ShowBubbleSize لجميع ملصقات البيانات في مجموعة DataLabelCollection (على سبيل المثال "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" يتسبب في أن تكون جميع DataLabels.get_Item(i).getShowBubbleSize() مساوية لـ val).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public abstract boolean getShowLeaderLines()
```

يمثل سلوك عرض خطوط القادة لملصق البيانات لمخطط محدد. true يعرض خطوط القادة. false لإخفائها. قراءة/كتابة boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من ملصقات البيانات فإن هذه الخاصية تحصل على أو تعين القيمة الافتراضية لخاصية ShowLeaderLines لملصقات البيانات الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يضبط أيضاً هذه القيمة لخاصية ShowLeaderLines لجميع ملصقات البيانات في مجموعة DataLabelCollection (على سبيل المثال "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" يتسبب في أن تكون جميع DataLabels.get_Item(i).getShowLeaderLines() مساوية لـ val).

**القيمة المرجعة:**
boolean

### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public abstract void setShowLeaderLines(boolean value)
```

يمثل سلوك عرض خطوط القادة لملصق البيانات لمخطط محدد. true يعرض خطوط القادة. false لإخفائها. قراءة/كتابة boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من ملصقات البيانات فإن هذه الخاصية تحصل على أو تعين القيمة الافتراضية لخاصية ShowLeaderLines لملصقات البيانات الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يضبط أيضاً هذه القيمة لخاصية ShowLeaderLines لجميع ملصقات البيانات في مجموعة DataLabelCollection (على سبيل المثال "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" يتسبب في أن تكون جميع DataLabels.get_Item(i).getShowLeaderLines() مساوية لـ val).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public abstract boolean getShowLabelAsDataCallout()
```

يحدد ما إذا كان ملصق البيانات لمخطط محدد سيظهر كنداء بياني أو كملصق بيانات.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من ملصقات البيانات فإن هذه الخاصية تحصل على أو تعين القيمة الافتراضية لخاصية ShowLabelAsDataCallout لملصقات البيانات الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يضبط أيضاً هذه القيمة لخاصية ShowLabelAsDataCallout لجميع ملصقات البيانات في مجموعة DataLabelCollection (على سبيل المثال "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" يتسبب في أن تكون جميع DataLabels.get_Item(i).getShowLabelAsDataCallout() مساوية لـ val).

**القيمة المرجعة:**
boolean

### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public abstract void setShowLabelAsDataCallout(boolean value)
```

يحدد ما إذا كان ملصق البيانات لمخطط محدد سيظهر كنداء بياني أو كملصق بيانات.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من ملصقات البيانات فإن هذه الخاصية تحصل على أو تعين القيمة الافتراضية لخاصية ShowLabelAsDataCallout لملصقات البيانات الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يضبط أيضاً هذه القيمة لخاصية ShowLabelAsDataCallout لجميع ملصقات البيانات في مجموعة DataLabelCollection (على سبيل المثال "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" يتسبب في أن تكون جميع DataLabels.get_Item(i).getShowLabelAsDataCallout() مساوية لـ val).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public abstract boolean getShowLabelValueFromCell()
```

يمثل سلوك عرض قيمة الخلية لملصق البيانات لمخطط محدد. true يعرض قيمة الخلية. false لإخفائها. قراءة/كتابة boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من ملصقات البيانات فإن هذه الخاصية تحصل على أو تعين القيمة الافتراضية لخاصية ShowLabelValueFromCell لملصقات البيانات الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يضبط أيضاً هذه القيمة لخاصية ShowLabelValueFromCell لجميع ملصقات البيانات في مجموعة DataLabelCollection (على سبيل المثال "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" يتسبب في أن تكون جميع DataLabels.get_Item(i).getShowLabelValueFromCell() مساوية لـ val).

**القيمة المرجعة:**
boolean

### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public abstract void setShowLabelValueFromCell(boolean value)
```

يمثل سلوك عرض قيمة الخلية لملصق البيانات لمخطط محدد. true يعرض قيمة الخلية. false لإخفائها. قراءة/كتابة boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من ملصقات البيانات فإن هذه الخاصية تحصل على أو تعين القيمة الافتراضية لخاصية ShowLabelValueFromCell لملصقات البيانات الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يضبط أيضاً هذه القيمة لخاصية ShowLabelValueFromCell لجميع ملصقات البيانات في مجموعة DataLabelCollection (على سبيل المثال "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" يتسبب في أن تكون جميع DataLabels.get_Item(i).getShowLabelValueFromCell() مساوية لـ val).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public abstract String getSeparator()
```

ضبط أو إرجاع Variant يمثل الفاصل المستخدم لملصقات البيانات على مخطط. قراءة/كتابة String.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من ملصقات البيانات فإن هذه الخاصية تحصل على أو تعين القيمة الافتراضية لخاصية Separator لملصقات البيانات الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يضبط أيضاً هذه القيمة لخاصية Separator لجميع ملصقات البيانات في مجموعة DataLabelCollection (على سبيل المثال "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" يتسبب في أن تكون جميع DataLabels.get_Item(i).getSeparator() مساوية لـ val).

**القيمة المرجعة:**
java.lang.String

### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public abstract void setSeparator(String value)
```

ضبط أو إرجاع Variant يمثل الفاصل المستخدم لملصقات البيانات على مخطط. قراءة/كتابة String.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من ملصقات البيانات فإن هذه الخاصية تحصل على أو تعين القيمة الافتراضية لخاصية Separator لملصقات البيانات الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يضبط أيضاً هذه القيمة لخاصية Separator لجميع ملصقات البيانات في مجموعة DataLabelCollection (على سبيل المثال "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" يتسبب في أن تكون جميع DataLabels.get_Item(i).getSeparator() مساوية لـ val).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |