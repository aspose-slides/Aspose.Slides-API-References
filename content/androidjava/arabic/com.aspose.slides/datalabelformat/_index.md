---
title: DataLabelFormat
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل خيارات التنسيق ل DataLabel.
type: docs
url: /ar/com.aspose.slides/datalabelformat/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
```
public final class DataLabelFormat extends PVIObject implements IDataLabelFormat
```

يمثل خيارات تنسيق للـ DataLabel.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | قراءة/كتابة boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | قراءة/كتابة boolean. |
| [getNumberFormat()](#getNumberFormat--) | يمثل سلسلة التنسيق لكائن DataLabels. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | يمثل سلسلة التنسيق لكائن DataLabels. |
| [getFormat()](#getFormat--) | يمثل تنسيق العلامة البيانية. |
| [getPosition()](#getPosition--) | يمثل موضع العلامة البيانية. |
| [setPosition(int value)](#setPosition-int-) | يمثل موضع العلامة البيانية. |
| [getShowLegendKey()](#getShowLegendKey--) | يمثل سلوك عرض مفتاح وساطة أسطورة المخطط للعلامة البيانية المحددة. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | يمثل سلوك عرض مفتاح وساطة أسطورة المخطط للعلامة البيانية المحددة. |
| [getShowValue()](#getShowValue--) | يمثل سلوك عرض قيمة النسبة المئوية للعلامة البيانية للمخطط المحدد. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | يمثل سلوك عرض قيمة النسبة المئوية للعلامة البيانية للمخطط المحدد. |
| [getShowCategoryName()](#getShowCategoryName--) | يمثل سلوك عرض اسم الفئة للعلامة البيانية للمخطط المحدد. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | يمثل سلوك عرض اسم الفئة للعلامة البيانية للمخطط المحدد. |
| [getShowSeriesName()](#getShowSeriesName--) | يعيد أو يضبط Boolean لتحديد سلوك عرض اسم السلسلة للعلامات البيانية على المخطط. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | يعيد أو يضبط Boolean لتحديد سلوك عرض اسم السلسلة للعلامات البيانية على المخطط. |
| [getShowPercentage()](#getShowPercentage--) | يمثل سلوك عرض قيمة النسبة المئوية للعلامة البيانية للمخطط المحدد. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | يمثل سلوك عرض قيمة النسبة المئوية للعلامة البيانية للمخطط المحدد. |
| [getShowBubbleSize()](#getShowBubbleSize--) | يمثل سلوك عرض قيمة حجم الفقاعة للعلامة البيانية للمخطط المحدد. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | يمثل سلوك عرض قيمة حجم الفقاعة للعلامة البيانية للمخطط المحدد. |
| [getShowLeaderLines()](#getShowLeaderLines--) | يمثل سلوك عرض خطوط القائد للعلامة البيانية للمخطط المحدد. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | يمثل سلوك عرض خطوط القائد للعلامة البيانية للمخطط المحدد. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | يمثل سلوك عرض قيمة الخلية للعلامة البيانية للمخطط المحدد. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | يمثل سلوك عرض قيمة الخلية للعلامة البيانية للمخطط المحدد. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | يحدد ما إذا كانت العلامة البيانية للمخطط المحدد ستُعرض كاستدعاء بيانات أو كعلامة بيانية. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | يحدد ما إذا كانت العلامة البيانية للمخطط المحدد ستُعرض كاستدعاء بيانات أو كعلامة بيانية. |
| [getSeparator()](#getSeparator--) | يضبط أو يرجع Variant يمثل الفاصل المستخدم للعلامات البيانية على مخطط. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | يضبط أو يرجع Variant يمثل الفاصل المستخدم للعلامات البيانية على مخطط. |
| [getTextFormat()](#getTextFormat--) | يعيد تنسيق نص المخطط. |
| [getChart()](#getChart--) | يعيد المخطط. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

الإصدار. قراءة فقط long.

**الإرجاع:**
long

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

قراءة/كتابة boolean.

--------------------

إذا كان أصل كائن DataLabelFormat هذا هو مجموعة DataLabelCollection من العلامات البيانية، فإن هذه الخاصية تحصل أو تضبط القيمة الافتراضية لخاصية IsNumberFormatLinkedToSource للعلامات البيانية الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يؤدي أيضًا إلى ضبط هذه القيمة لخاصية IsNumberFormatLinkedToSource لجميع العلامات البيانية في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" يؤدي إلى أن تكون جميع DataLabels.get\_Item(i).isNumberFormatLinkedToSource() مساوية للقيمة).

**الإرجاع:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

قراءة/كتابة boolean.

--------------------

إذا كان أصل كائن DataLabelFormat هذا هو مجموعة DataLabelCollection من العلامات البيانية، فإن هذه الخاصية تحصل أو تضبط القيمة الافتراضية لخاصية IsNumberFormatLinkedToSource للعلامات البيانية الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يؤدي أيضًا إلى ضبط هذه القيمة لخاصية IsNumberFormatLinkedToSource لجميع العلامات البيانية في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" يؤدي إلى أن تكون جميع DataLabels.get\_Item(i).isNumberFormatLinkedToSource() مساوية للقيمة).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

يمثل سلسلة التنسيق لكائن DataLabels. قراءة/كتابة String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```


إذا كان أصل كائن DataLabelFormat هذا هو مجموعة DataLabelCollection من العلامات البيانية، فإن هذه الخاصية تحصل أو تضبط القيمة الافتراضية لخاصية NumberFormat للعلامات البيانية الجديدة في مجموعة DataLabelCollection. عندما يتم ضبط هذه الخاصية بقيمة، تُضبط نفس القيمة لخاصية NumberFormat لجميع العلامات البيانية في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" يؤدي إلى أن تكون جميع DataLabels.get\_Item(i).getNumberFormat() مساوية للقيمة).

**الإرجاع:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

يمثل سلسلة التنسيق لكائن DataLabels. قراءة/كتابة String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```


إذا كان أصل كائن DataLabelFormat هذا هو مجموعة DataLabelCollection من العلامات البيانية، فإن هذه الخاصية تحصل أو تضبط القيمة الافتراضية لخاصية NumberFormat للعلامات البيانية الجديدة في مجموعة DataLabelCollection. عندما يتم ضبط هذه الخاصية بقيمة، تُضبط نفس القيمة لخاصية NumberFormat لجميع العلامات البيانية في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" يؤدي إلى أن تكون جميع DataLabels.get\_Item(i).getNumberFormat() مساوية للقيمة).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

يمثل تنسيق العلامة البيانية. قراءة فقط [IFormat](../../com.aspose.slides/iformat).

--------------------

إذا كان أصل كائن DataLabelFormat هذا هو مجموعة DataLabelCollection من العلامات البيانية، فإن هذه الخاصية تمثل التنسيق الافتراضي للعلامات البيانية الجديدة في مجموعة DataLabelCollection.

**الإرجاع:**
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public final int getPosition()
```

يمثل موضع العلامة البيانية. قراءة/كتابة [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

إذا كان أصل كائن DataLabelFormat هذا هو مجموعة DataLabelCollection من العلامات البيانية، فإن هذه الخاصية تحصل أو تضبط القيمة الافتراضية لخاصية Position للعلامات البيانية الجديدة في مجموعة DataLabelCollection. تمثل الموضع لكائنات DataLabel. ضبط هذه الخاصية بقيمة يؤدي أيضًا إلى ضبط هذه القيمة لخاصية Position لجميع العلامات البيانية في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setPosition(val);" يؤدي إلى أن تكون جميع DataLabels.get\_Item(i).getPosition() مساوية للقيمة).

**الإرجاع:**
int

### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

يمثل موضع العلامة البيانية. قراءة/كتابة [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

إذا كان أصل كائن DataLabelFormat هذا هو مجموعة DataLabelCollection من العلامات البيانية، فإن هذه الخاصية تحصل أو تضبط القيمة الافتراضية لخاصية Position للعلامات البيانية الجديدة في مجموعة DataLabelCollection. تمثل الموضع لكائنات DataLabel. ضبط هذه الخاصية بقيمة يؤدي أيضًا إلى ضبط هذه القيمة لخاصية Position لجميع العلامات البيانية في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setPosition(val);" يؤدي إلى أن تكون جميع DataLabels.get\_Item(i).getPosition() مساوية للقيمة).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public final boolean getShowLegendKey()
```

يمثل سلوك عرض مفتاح وساطة أسطورة المخطط للعلامة البيانية المحددة. صحيح إذا كان مفتاح وساطة الأسطورة للعلامة البيانية مرئيًا. قراءة/كتابة boolean.

--------------------

إذا كان أصل كائن DataLabelFormat هذا هو مجموعة DataLabelCollection من العلامات البيانية، فإن هذه الخاصية تحصل أو تضبط القيمة الافتراضية لخاصية ShowLegendKey للعلامات البيانية الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يؤدي أيضًا إلى ضبط هذه القيمة لخاصية ShowLegendKey لجميع العلامات البيانية في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" يؤدي إلى أن تكون جميع DataLabels.get\_Item(i).getShowLegendKey() مساوية للقيمة).

**الإرجاع:**
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public final void setShowLegendKey(boolean value)
```

يمثل سلوك عرض مفتاح وساطة أسطورة المخطط للعلامة البيانية المحددة. صحيح إذا كان مفتاح وساطة الأسطورة للعلامة البيانية مرئيًا. قراءة/كتابة boolean.

--------------------

إذا كان أصل كائن DataLabelFormat هذا هو مجموعة DataLabelCollection من العلامات البيانية، فإن هذه الخاصية تحصل أو تضبط القيمة الافتراضية لخاصية ShowLegendKey للعلامات البيانية الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يؤدي أيضًا إلى ضبط هذه القيمة لخاصية ShowLegendKey لجميع العلامات البيانية في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" يؤدي إلى أن تكون جميع DataLabels.get\_Item(i).getShowLegendKey() مساوية للقيمة).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public final boolean getShowValue()
```

يمثل سلوك عرض قيمة النسبة المئوية للعلامة البيانية للمخطط المحدد. صحيح إذا تم عرض القيمة النسبية. خاطئ للإخفاء. قراءة/كتابة boolean.

--------------------

إذا كان أصل كائن DataLabelFormat هذا هو مجموعة DataLabelCollection من العلامات البيانية، فإن هذه الخاصية تحصل أو تضبط القيمة الافتراضية لخاصية ShowValue للعلامات البيانية الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يؤدي أيضًا إلى ضبط هذه القيمة لخاصية ShowValue لجميع العلامات البيانية في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" يؤدي إلى أن تكون جميع DataLabels.get\_Item(i).getShowValue() مساوية للقيمة).

**الإرجاع:**
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public final void setShowValue(boolean value)
```

يمثل سلوك عرض قيمة النسبة المئوية للعلامة البيانية للمخطط المحدد. صحيح إذا تم عرض القيمة النسبية. خاطئ للإخفاء. قراءة/كتابة boolean.

--------------------

إذا كان أصل كائن DataLabelFormat هذا هو مجموعة DataLabelCollection من العلامات البيانية، فإن هذه الخاصية تحصل أو تضبط القيمة الافتراضية لخاصية ShowValue للعلامات البيانية الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يؤدي أيضًا إلى ضبط هذه القيمة لخاصية ShowValue لجميع العلامات البيانية في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" يؤدي إلى أن تكون جميع DataLabels.get\_Item(i).getShowValue() مساوية للقيمة).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public final boolean getShowCategoryName()
```

يمثل سلوك عرض اسم الفئة للعلامة البيانية للمخطط المحدد. صحيح لعرض اسم الفئة للعلامات البيانية على المخطط. خاطئ للإخفاء. قراءة/كتابة boolean.

--------------------

إذا كان أصل كائن DataLabelFormat هذا هو مجموعة DataLabelCollection من العلامات البيانية، فإن هذه الخاصية تحصل أو تضبط القيمة الافتراضية لخاصية ShowCategoryName للعلامات البيانية الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يؤدي أيضًا إلى ضبط هذه القيمة لخاصية ShowCategoryName لجميع العلامات البيانية في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" يؤدي إلى أن تكون جميع DataLabels.get\_Item(i).getShowCategoryName() مساوية للقيمة).

**الإرجاع:**
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public final void setShowCategoryName(boolean value)
```

يمثل سلوك عرض اسم الفئة للعلامة البيانية للمخطط المحدد. صحيح لعرض اسم الفئة للعلامات البيانية على المخطط. خاطئ للإخفاء. قراءة/كتابة boolean.

--------------------

إذا كان أصل كائن DataLabelFormat هذا هو مجموعة DataLabelCollection من العلامات البيانية، فإن هذه الخاصية تحصل أو تضبط القيمة الافتراضية لخاصية ShowCategoryName للعلامات البيانية الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يؤدي أيضًا إلى ضبط هذه القيمة لخاصية ShowCategoryName لجميع العلامات البيانية في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" يؤدي إلى أن تكون جميع DataLabels.get\_Item(i).getShowCategoryName() مساوية للقيمة).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public final boolean getShowSeriesName()
```

يعيد أو يضبط Boolean لتحديد سلوك عرض اسم السلسلة للعلامات البيانية على مخطط. صحيح لعرض اسم السلسلة. خاطئ للإخفاء. قراءة/كتابة boolean.

--------------------

إذا كان أصل كائن DataLabelFormat هذا هو مجموعة DataLabelCollection من العلامات البيانية، فإن هذه الخاصية تحصل أو تضبط القيمة الافتراضية لخاصية ShowSeriesName للعلامات البيانية الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يؤدي أيضًا إلى ضبط هذه القيمة لخاصية ShowSeriesName لجميع العلامات البيانية في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" يؤدي إلى أن تكون جميع DataLabels.get\_Item(i).getShowSeriesName() مساوية للقيمة).

**الإرجاع:**
boolean

### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public final void setShowSeriesName(boolean value)
```

يعيد أو يضبط Boolean لتحديد سلوك عرض اسم السلسلة للعلامات البيانية على مخطط. صحيح لعرض اسم السلسلة. خاطئ للإخفاء. قراءة/كتابة boolean.

--------------------

إذا كان أصل كائن DataLabelFormat هذا هو مجموعة DataLabelCollection من العلامات البيانية، فإن هذه الخاصية تحصل أو تضبط القيمة الافتراضية لخاصية ShowSeriesName للعلامات البيانية الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يؤدي أيضًا إلى ضبط هذه القيمة لخاصية ShowSeriesName لجميع العلامات البيانية في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" يؤدي إلى أن تكون جميع DataLabels.get\_Item(i).getShowSeriesName() مساوية للقيمة).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public final boolean getShowPercentage()
```

يمثل سلوك عرض قيمة النسبة المئوية للعلامة البيانية للمخطط المحدد. صحيح إذا تم عرض القيمة النسبية. خاطئ للإخفاء. قراءة/كتابة boolean.

--------------------

إذا كان أصل كائن DataLabelFormat هذا هو مجموعة DataLabelCollection من العلامات البيانية، فإن هذه الخاصية تحصل أو تضبط القيمة الافتراضية لخاصية ShowPercentage للعلامات البيانية الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يؤدي أيضًا إلى ضبط هذه القيمة لخاصية ShowPercentage لجميع العلامات البيانية في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" يؤدي إلى أن تكون جميع DataLabels.get\_Item(i).getShowPercentage() مساوية للقيمة).

**الإرجاع:**
boolean

### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public final void setShowPercentage(boolean value)
```

يمثل سلوك عرض قيمة النسبة المئوية للعلامة البيانية للمخطط المحدد. صحيح إذا تم عرض القيمة النسبية. خاطئ للإخفاء. قراءة/كتابة boolean.

--------------------

إذا كان أصل كائن DataLabelFormat هذا هو مجموعة DataLabelCollection من العلامات البيانية، فإن هذه الخاصية تحصل أو تضبط القيمة الافتراضية لخاصية ShowPercentage للعلامات البيانية الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يؤدي أيضًا إلى ضبط هذه القيمة لخاصية ShowPercentage لجميع العلامات البيانية في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" يؤدي إلى أن تكون جميع DataLabels.get\_Item(i).getShowPercentage() مساوية للقيمة).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public final boolean getShowBubbleSize()
```

يمثل سلوك عرض قيمة حجم الفقاعة للعلامة البيانية للمخطط المحدد. صحيح إذا تم عرض قيمة حجم الفقاعة. خاطئ للإخفاء. قراءة/كتابة boolean.

--------------------

إذا كان أصل كائن DataLabelFormat هذا هو مجموعة DataLabelCollection من العلامات البيانية، فإن هذه الخاصية تحصل أو تضبط القيمة الافتراضية لخاصية ShowBubbleSize للعلامات البيانية الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يؤدي أيضًا إلى ضبط هذه القيمة لخاصية ShowBubbleSize لجميع العلامات البيانية في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" يؤدي إلى أن تكون جميع DataLabels.get\_Item(i).getShowBubbleSize() مساوية للقيمة).

**الإرجاع:**
boolean

### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public final void setShowBubbleSize(boolean value)
```

يمثل سلوك عرض قيمة حجم الفقاعة للعلامة البيانية للمخطط المحدد. صحيح إذا تم عرض قيمة حجم الفقاعة. خاطئ للإخفاء. قراءة/كتابة boolean.

--------------------

إذا كان أصل كائن DataLabelFormat هذا هو مجموعة DataLabelCollection من العلامات البيانية، فإن هذه الخاصية تحصل أو تضبط القيمة الافتراضية لخاصية ShowBubbleSize للعلامات البيانية الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يؤدي أيضًا إلى ضبط هذه القيمة لخاصية ShowBubbleSize لجميع العلامات البيانية في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" يؤدي إلى أن تكون جميع DataLabels.get\_Item(i).getShowBubbleSize() مساوية للقيمة).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public final boolean getShowLeaderLines()
```

يمثل سلوك عرض خطوط القائد للعلامة البيانية للمخطط المحدد. صحيح إذا تم عرض خطوط القائد. خاطئ للإخفاء. قراءة/كتابة boolean.

--------------------

إذا كان أصل كائن DataLabelFormat هذا هو مجموعة DataLabelCollection من العلامات البيانية، فإن هذه الخاصية تحصل أو تضبط القيمة الافتراضية لخاصية ShowLeaderLines للعلامات البيانية الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يؤدي أيضًا إلى ضبط هذه القيمة لخاصية ShowLeaderLines لجميع العلامات البيانية في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" يؤدي إلى أن تكون جميع DataLabels.get\_Item(i).getShowLeaderLines() مساوية للقيمة).

**الإرجاع:**
boolean

### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public final void setShowLeaderLines(boolean value)
```

يمثل سلوك عرض خطوط القائد للعلامة البيانية للمخطط المحدد. صحيح إذا تم عرض خطوط القائد. خاطئ للإخفاء. قراءة/كتابة boolean.

--------------------

إذا كان أصل كائن DataLabelFormat هذا هو مجموعة DataLabelCollection من العلامات البيانية، فإن هذه الخاصية تحصل أو تضبط القيمة الافتراضية لخاصية ShowLeaderLines للعلامات البيانية الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يؤدي أيضًا إلى ضبط هذه القيمة لخاصية ShowLeaderLines لجميع العلامات البيانية في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" يؤدي إلى أن تكون جميع DataLabels.get\_Item(i).getShowLeaderLines() مساوية للقيمة).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public final boolean getShowLabelValueFromCell()
```

يمثل سلوك عرض قيمة الخلية للعلامة البيانية للمخطط المحدد. صحيح إذا تم عرض قيمة الخلية. خاطئ للإخفاء. قراءة/كتابة boolean.

--------------------

إذا كان أصل كائن DataLabelFormat هذا هو مجموعة DataLabelCollection من العلامات البيانية، فإن هذه الخاصية تحصل أو تضبط القيمة الافتراضية لخاصية ShowLabelValueFromCell للعلامات البيانية الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يؤدي أيضًا إلى ضبط هذه القيمة لخاصية ShowLabelValueFromCell لجميع العلامات البيانية في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" يؤدي إلى أن تكون جميع DataLabels.get\_Item(i).getShowLabelValueFromCell() مساوية للقيمة).

**الإرجاع:**
boolean

### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public final void setShowLabelValueFromCell(boolean value)
```

يمثل سلوك عرض قيمة الخلية للعلامة البيانية للمخطط المحدد. صحيح إذا تم عرض قيمة الخلية. خاطئ للإخفاء. قراءة/كتابة boolean.

--------------------

إذا كان أصل كائن DataLabelFormat هذا هو مجموعة DataLabelCollection من العلامات البيانية، فإن هذه الخاصية تحصل أو تضبط القيمة الافتراضية لخاصية ShowLabelValueFromCell للعلامات البيانية الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يؤدي أيضًا إلى ضبط هذه القيمة لخاصية ShowLabelValueFromCell لجميع العلامات البيانية في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" يؤدي إلى أن تكون جميع DataLabels.get\_Item(i).getShowLabelValueFromCell() مساوية للقيمة).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public final boolean getShowLabelAsDataCallout()
```

يحدد ما إذا كانت العلامة البيانية للمخطط المحدد ستُعرض كاستدعاء بيانات أو كعلامة بيانية.

--------------------

إذا كان أصل كائن DataLabelFormat هذا هو مجموعة DataLabelCollection من العلامات البيانية، فإن هذه الخاصية تحصل أو تضبط القيمة الافتراضية لخاصية ShowLabelAsDataCallout للعلامات البيانية الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يؤدي أيضًا إلى ضبط هذه القيمة لخاصية ShowLabelAsDataCallout لجميع العلامات البيانية في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" يؤدي إلى أن تكون جميع DataLabels.get\_Item(i).getShowLabelAsDataCallout() مساوية للقيمة).

**الإرجاع:**
boolean

### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public final void setShowLabelAsDataCallout(boolean value)
```

يحدد ما إذا كانت العلامة البيانية للمخطط المحدد ستُعرض كاستدعاء بيانات أو كعلامة بيانية.

--------------------

إذا كان أصل كائن DataLabelFormat هذا هو مجموعة DataLabelCollection من العلامات البيانية، فإن هذه الخاصية تحصل أو تضبط القيمة الافتراضية لخاصية ShowLabelAsDataCallout للعلامات البيانية الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يؤدي أيضًا إلى ضبط هذه القيمة لخاصية ShowLabelAsDataCallout لجميع العلامات البيانية في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" يؤدي إلى أن تكون جميع DataLabels.get\_Item(i).getShowLabelAsDataCallout() مساوية للقيمة).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```

يضبط أو يرجع Variant يمثل الفاصل المستخدم للعلامات البيانية على مخطط. قراءة/كتابة String.

--------------------

إذا كان أصل كائن DataLabelFormat هذا هو مجموعة DataLabelCollection من العلامات البيانية، فإن هذه الخاصية تحصل أو تضبط القيمة الافتراضية لخاصية Separator للعلامات البيانية الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يؤدي أيضًا إلى ضبط هذه القيمة لخاصية Separator لجميع العلامات البيانية في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" يؤدي إلى أن تكون جميع DataLabels.get\_Item(i).getSeparator() مساوية للقيمة).

**الإرجاع:**
java.lang.String

### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```

يضبط أو يرجع Variant يمثل الفاصل المستخدم للعلامات البيانية على مخطط. قراءة/كتابة String.

--------------------

إذا كان أصل كائن DataLabelFormat هذا هو مجموعة DataLabelCollection من العلامات البيانية، فإن هذه الخاصية تحصل أو تضبط القيمة الافتراضية لخاصية Separator للعلامات البيونية الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يؤدي أيضًا إلى ضبط هذه القيمة لخاصية Separator لجميع العلامات البيونية في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" يؤدي إلى أن تكون جميع DataLabels.get\_Item(i).getSeparator() مساوية للقيمة).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

يعيد تنسيق نص المخطط. قراءة فقط [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**الإرجاع:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getChart() {#getChart--}
```
public final IChart getChart()
```

يعيد المخطط. قراءة فقط [IChart](../../com.aspose.slides/ichart).

**الإرجاع:**
[IChart](../../com.aspose.slides/ichart)