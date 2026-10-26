---
title: DataLabelFormat
second_title: مرجع API لـ Aspose.Slides for Java
description: يمثل خيارات تنسيق لتسمية البيانات.
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

يمثل خيارات التنسيق لـ DataLabel.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | قابل للقراءة/الكتابة boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | قابل للقراءة/الكتابة boolean. |
| [getNumberFormat()](#getNumberFormat--) | يمثل سلسلة التنسيق لكائن DataLabels. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | يمثل سلسلة التنسيق لكائن DataLabels. |
| [getFormat()](#getFormat--) | يمثل تنسيق DataLabel. |
| [getPosition()](#getPosition--) | يمثل موقع DataLabel. |
| [setPosition(int value)](#setPosition-int-) | يمثل موقع DataLabel. |
| [getShowLegendKey()](#getShowLegendKey--) | يمثل سلوك عرض مفتاح وسيلة إيضاح تسمية البيانات لمخطط محدد. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | يمثل سلوك عرض مفتاح وسيلة إيضاح تسمية البيانات لمخطط محدد. |
| [getShowValue()](#getShowValue--) | يمثل سلوك عرض قيمة النسبة المئوية لتسمية البيانات لمخطط محدد. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | يمثل سلوك عرض قيمة النسبة المئوية لتسمية البيانات لمخطط محدد. |
| [getShowCategoryName()](#getShowCategoryName--) | يمثل سلوك عرض اسم الفئة لتسمية البيانات لمخطط محدد. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | يمثل سلوك عرض اسم الفئة لتسمية البيانات لمخطط محدد. |
| [getShowSeriesName()](#getShowSeriesName--) | تُرجع أو تُعيّن Boolean لتحديد سلوك عرض اسم السلسلة لتسميات البيانات على مخطط. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | تُرجع أو تُعيّن Boolean لتحديد سلوك عرض اسم السلسلة لتسميات البيانات على مخطط. |
| [getShowPercentage()](#getShowPercentage--) | يمثل سلوك عرض قيمة النسبة المئوية لتسمية البيانات لمخطط محدد. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | يمثل سلوك عرض قيمة النسبة المئوية لتسمية البيانات لمخطط محدد. |
| [getShowBubbleSize()](#getShowBubbleSize--) | يمثل سلوك عرض قيمة حجم الفقاعات لتسمية البيانات لمخطط محدد. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | يمثل سلوك عرض قيمة حجم الفقاعات لتسمية البيانات لمخطط محدد. |
| [getShowLeaderLines()](#getShowLeaderLines--) | يمثل سلوك عرض خطوط القائد لتسمية البيانات لمخطط محدد. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | يمثل سلوك عرض خطوط القائد لتسمية البيانات لمخطط محدد. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | يمثل سلوك عرض قيمة الخلية لتسمية البيانات لمخطط محدد. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | يمثل سلوك عرض قيمة الخلية لتسمية البيانات لمخطط محدد. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | يحدد ما إذا ستُعرض تسمية البيانات لمخطط محدد كإشارة بيانية أو كتسمية بيانات. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | يحدد ما إذا ستُعرض تسمية البيانات لمخطط محدد كإشارة بيانية أو كتسمية بيانات. |
| [getSeparator()](#getSeparator--) | يضع أو يُرجع Variant يمثل الفاصل المستخدم لتسميات البيانات على مخطط. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | يضع أو يُرجع Variant يمثل الفاصل المستخدم لتسميات البيانات على مخطط. |
| [getTextFormat()](#getTextFormat--) | يُرجع تنسيق نص المخطط. |
| [getChart()](#getChart--) | يُرجع المخطط. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

الإصدار. عدد صحيح للقراءة فقط.

**الإرجاع:**
long
### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

قابل للقراءة/الكتابة boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات، فإن هذه الخاصية تحصل على أو تعيين القيمة الافتراضية للخاصية IsNumberFormatLinkedToSource لتسميات البيانات الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يضبط هذه القيمة أيضاً للخاصية IsNumberFormatLinkedToSource لجميع تسميات البيانات في مجموعة DataLabelCollection (مثل "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" يؤدي إلى أن تكون جميع DataLabels.get_Item(i).isNumberFormatLinkedToSource() مساوية للقيمة).

**الإرجاع:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

قابل للقراءة/الكتابة boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات، فإن هذه الخاصية تحصل على أو تعيين القيمة الافتراضية للخاصية IsNumberFormatLinkedToSource لتسميات البيانات الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يضبط هذه القيمة أيضاً للخاصية IsNumberFormatLinkedToSource لجميع تسميات البيانات في مجموعة DataLabelCollection (مثل "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" يؤدي إلى أن تكون جميع DataLabels.get_Item(i).isNumberFormatLinkedToSource() مساوية للقيمة).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

يمثل سلسلة التنسيق لكائن DataLabels. قابل للقراءة/الكتابة String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```


--------------------

إذا كان أصل هذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات، فإن هذه الخاصية تحصل على أو تعيين القيمة الافتراضية للخاصية NumberFormat لتسميات البيانات الجديدة في مجموعة DataLabelCollection. عند ضبط هذه الخاصية بقيمة، يتم ضبط نفس القيمة للخاصية NumberFormat لجميع تسميات البيانات في مجموعة DataLabelCollection (مثل "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" يؤدي إلى أن تكون جميع DataLabels.get_Item(i).getNumberFormat() مساوية للقيمة).

**الإرجاع:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

يمثل سلسلة التنسيق لكائن DataLabels. قابل للقراءة/الكتابة String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```


--------------------

إذا كان أصل هذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات، فإن هذه الخاصية تحصل على أو تعيين القيمة الافتراضية للخاصية NumberFormat لتسميات البيانات الجديدة في مجموعة DataLabelCollection. عند ضبط هذه الخاصية بقيمة، يتم ضبط نفس القيمة للخاصية NumberFormat لجميع تسميات البيانات في مجموعة DataLabelCollection (مثل "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" يؤدي إلى أن تكون جميع DataLabels.get_Item(i).getNumberFormat() مساوية للقيمة).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

يمثل تنسيق DataLabel. للقراءة فقط [IFormat](../../com.aspose.slides/iformat).

--------------------

إذا كان أصل هذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات فإن هذه الخاصية تمثل التنسيق الافتراضي لتسميات البيانات الجديدة في مجموعة DataLabelCollection.

**الإرجاع:**
[IFormat](../../com.aspose.slides/iformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```

يمثل موقع DataLabel. قابل للقراءة/الكتابة [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

إذا كان أصل هذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات فإن هذه الخاصية تحصل على أو تعيين القيمة الافتراضية للخاصية Position لتسميات البيانات الجديدة في مجموعة DataLabelCollection. تمثل الموقع لكائنات DataLabel. ضبط هذه الخاصية بقيمة يضبط هذه القيمة أيضاً للخاصية Position لجميع تسميات البيانات في مجموعة DataLabelCollection (مثل "DataLabels.getDefaultDataLabelFormat().setPosition(val);" يؤدي إلى أن تكون جميع DataLabels.get_Item(i).getPosition() مساوية للقيمة).

**الإرجاع:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

يمثل موقع DataLabel. قابل للقراءة/الكتابة [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

إذا كان أصل هذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات فإن هذه الخاصية تحصل على أو تعيين القيمة الافتراضية للخاصية Position لتسميات البيانات الجديدة في مجموعة DataLabelCollection. تمثل الموقع لكائنات DataLabel. ضبط هذه الخاصية بقيمة يضبط هذه القيمة أيضاً للخاصية Position لجميع تسميات البيانات في مجموعة DataLabelCollection (مثل "DataLabels.getDefaultDataLabelFormat().setPosition(val);" يؤدي إلى أن تكون جميع DataLabels.get_Item(i).getPosition() مساوية للقيمة).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public final boolean getShowLegendKey()
```

يمثل سلوك عرض مفتاح وسيلة إيضاح تسمية البيانات لمخطط محدد. True إذا كان مفتاح وسيلة إيضاح تسمية البيانات مرئياً. قابل للقراءة/الكتابة boolean.

--------------------

إذا كان أصل هذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات فإن هذه الخاصية تحصل على أو تعيين القيمة الافتراضية للخاصية ShowLegendKey لتسميات البيانات الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يضبط هذه القيمة أيضاً للخاصية ShowLegendKey لجميع تسميات البيانات في مجموعة DataLabelCollection (مثل "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" يؤدي إلى أن تكون جميع DataLabels.get_Item(i).getShowLegendKey() مساوية للقيمة).

**الإرجاع:**
boolean
### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public final void setShowLegendKey(boolean value)
```

يمثل سلوك عرض مفتاح وسيلة إيضاح تسمية البيانات لمخطط محدد. True إذا كان مفتاح وسيلة إيضاح تسمية البيانات مرئياً. قابل للقراءة/الكتابة boolean.

--------------------

إذا كان أصل هذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات فإن هذه الخاصية تحصل على أو تعيين القيمة الافتراضية للخاصية ShowLegendKey لتسميات البيانات الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يضبط هذه القيمة أيضاً للخاصية ShowLegendKey لجميع تسميات البيانات في مجموعة DataLabelCollection (مثل "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" يؤدي إلى أن تكون جميع DataLabels.get_Item(i).getShowLegendKey() مساوية للقيمة).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public final boolean getShowValue()
```

يمثل سلوك عرض قيمة النسبة المئوية لتسمية البيانات لمخطط محدد. True يعرض القيمة النسبية. False لإخفائها. قابل للقراءة/الكتابة boolean.

--------------------

إذا كان أصل هذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات فإن هذه الخاصية تحصل على أو تعيين القيمة الافتراضية للخاصية ShowValue لتسميات البيانات الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يضبط هذه القيمة أيضاً للخاصية ShowValue لجميع تسميات البيانات في مجموعة DataLabelCollection (مثل "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" يؤدي إلى أن تكون جميع DataLabels.get_Item(i).getShowValue() مساوية للقيمة).

**الإرجاع:**
boolean
### setShowValue(boolean value) {#setShowValue-boolean-}
```
public final void setShowValue(boolean value)
```

يمثل سلوك عرض قيمة النسبة المئوية لتسمية البيانات لمخطط محدد. True يعرض القيمة النسبية. False لإخفائها. قابل للقراءة/الكتابة boolean.

--------------------

إذا كان أصل هذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات فإن هذه الخاصية تحصل على أو تعيين القيمة الافتراضية للخاصية ShowValue لتسميات البيانات الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يضبط هذه القيمة أيضاً للخاصية ShowValue لجميع تسميات البيانات في مجموعة DataLabelCollection (مثل "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" يؤدي إلى أن تكون جميع DataLabels.get_Item(i).getShowValue() مساوية للقيمة).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public final boolean getShowCategoryName()
```

يمثل سلوك عرض اسم الفئة لتسمية البيانات لمخطط محدد. True لعرض اسم الفئة لتسميات البيانات على المخطط. False للإخفاء. قابل للقراءة/الكتابة boolean.

--------------------

إذا كان أصل هذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات فإن هذه الخاصية تحصل على أو تعيين القيمة الافتراضية للخاصية ShowCategoryName لتسميات البيانات الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يضبط هذه القيمة أيضاً للخاصية ShowCategoryName لجميع تسميات البيانات في مجموعة DataLabelCollection (مثل "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" يؤدي إلى أن تكون جميع DataLabels.get_Item(i).getShowCategoryName() مساوية للقيمة).

**الإرجاع:**
boolean
### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public final void setShowCategoryName(boolean value)
```

يمثل سلوك عرض اسم الفئة لتسمية البيانات لمخطط محدد. True لعرض اسم الفئة لتسميات البيانات على المخطط. False للإخفاء. قابل للقراءة/الكتابة boolean.

--------------------

إذا كان أصل هذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات فإن هذه الخاصية تحصل على أو تعيين القيمة الافتراضية للخاصية ShowCategoryName لتسميات البيانات الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بقيمة يضبط هذه القيمة أيضاً للخاصية ShowCategoryName لجميع تسميات البيانات في مجموعة DataLabelCollection (مثل "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" يؤدي إلى أن تكون جميع DataLabels.get_Item(i).getShowCategoryName() مساوية للقيمة).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من ملصقات البيانات، فإن هذه الخاصية تحصل على أو تعيين القيمة الافتراضية لخاصية ShowCategoryName لملصقات البيانات الجديدة في مجموعة DataLabelCollection. تعيين هذه الخاصية بقيمة يقوم أيضًا بتعيين هذه القيمة لخاصية ShowCategoryName لجميع ملصقات البيانات في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" يؤدي إلى أن تكون جميع DataLabels.get_Item(i).getShowCategoryName() مساوية لـ val).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public final boolean getShowSeriesName()
```

إرجاع أو تعيين Boolean لتحديد سلوك عرض اسم السلسلة لملصقات البيانات على المخطط. True لإظهار اسم السلسلة. False للإخفاء. قراءة/كتابة boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من ملصقات البيانات، فإن هذه الخاصية تحصل على أو تعيين القيمة الافتراضية لخاصية ShowSeriesName للملصقات الجديدة في مجموعة DataLabelCollection. تعيين هذه الخاصية بقيمة يقوم أيضًا بتعيين هذه القيمة لخاصية ShowSeriesName لجميع ملصقات البيانات في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" يؤدي إلى أن تكون جميع DataLabels.get_Item(i).getShowSeriesName() مساوية لـ val).

**القيمة المرجعة:**
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public final void setShowSeriesName(boolean value)
```

إرجاع أو تعيين Boolean لتحديد سلوك عرض اسم السلسلة لملصقات البيانات على المخطط. True لإظهار اسم السلسلة. False للإخفاء. قراءة/كتابة boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من ملصقات البيانات، فإن هذه الخاصية تحصل على أو تعيين القيمة الافتراضية لخاصية ShowSeriesName للملصقات الجديدة في مجموعة DataLabelCollection. تعيين هذه الخاصية بقيمة يقوم أيضًا بتعيين هذه القيمة لخاصية ShowSeriesName لجميع ملصقات البيانات في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" يؤدي إلى أن تكون جميع DataLabels.get_Item(i).getShowSeriesName() مساوية لـ val).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public final boolean getShowPercentage()
```

يمثل سلوك عرض قيمة النسبة المئوية لملصق البيانات في المخطط المحدد. True لعرض القيمة المئوية. False للإخفاء. قراءة/كتابة boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من ملصقات البيانات، فإن هذه الخاصية تحصل على أو تعيين القيمة الافتراضية لخاصية ShowPercentage للملصقات الجديدة في مجموعة DataLabelCollection. تعيين هذه الخاصية بقيمة يقوم أيضًا بتعيين هذه القيمة لخاصية ShowPercentage لجميع ملصقات البيانات في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" يؤدي إلى أن تكون جميع DataLabels.get_Item(i).getShowPercentage() مساوية لـ val).

**القيمة المرجعة:**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public final void setShowPercentage(boolean value)
```

يمثل سلوك عرض قيمة النسبة المئوية لملصق البيانات في المخطط المحدد. True لعرض القيمة المئوية. False للإخفاء. قراءة/كتابة boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من ملصقات البيانات، فإن هذه الخاصية تحصل على أو تعيين القيمة الافتراضية لخاصية ShowPercentage للملصقات الجديدة في مجموعة DataLabelCollection. تعيين هذه الخاصية بقيمة يقوم أيضًا بتعيين هذه القيمة لخاصية ShowPercentage لجميع ملصقات البيانات في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" يؤدي إلى أن تكون جميع DataLabels.get_Item(i).getShowPercentage() مساوية لـ val).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public final boolean getShowBubbleSize()
```

يمثل سلوك عرض قيمة حجم الفقاعة لملصق البيانات في المخطط المحدد. True لعرض قيمة حجم الفقاعة. False للإخفاء. قراءة/كتابة boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من ملصقات البيانات، فإن هذه الخاصية تحصل على أو تعيين القيمة الافتراضية لخاصية ShowBubbleSize للملصقات الجديدة في مجموعة DataLabelCollection. تعيين هذه الخاصية بقيمة يقوم أيضًا بتعيين هذه القيمة لخاصية ShowBubbleSize لجميع ملصقات البيانات في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" يؤدي إلى أن تكون جميع DataLabels.get_Item(i).getShowBubbleSize() مساوية لـ val).

**القيمة المرجعة:**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public final void setShowBubbleSize(boolean value)
```

يمثل سلوك عرض قيمة حجم الفقاعة لملصق البيانات في المخطط المحدد. True لعرض قيمة حجم الفقاعة. False للإخفاء. قراءة/كتابة boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من ملصقات البيانات، فإن هذه الخاصية تحصل على أو تعيين القيمة الافتراضية لخاصية ShowBubbleSize للملصقات الجديدة في مجموعة DataLabelCollection. تعيين هذه الخاصية بقيمة يقوم أيضًا بتعيين هذه القيمة لخاصية ShowBubbleSize لجميع ملصقات البيانات في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" يؤدي إلى أن تكون جميع DataLabels.get_Item(i).getShowBubbleSize() مساوية لـ val).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public final boolean getShowLeaderLines()
```

يمثل سلوك عرض خطوط القائد لملصق البيانات في المخطط المحدد. True لعرض خطوط القائد. False للإخفاء. قراءة/كتابة boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من ملصقات البيانات، فإن هذه الخاصية تحصل على أو تعيين القيمة الافتراضية لخاصية ShowLeaderLines للملصقات الجديدة في مجموعة DataLabelCollection. تعيين هذه الخاصية بقيمة يقوم أيضًا بتعيين هذه القيمة لخاصية ShowLeaderLines لجميع ملصقات البيانات في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" يؤدي إلى أن تكون جميع DataLabels.get_Item(i).getShowLeaderLines() مساوية لـ val).

**القيمة المرجعة:**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public final void setShowLeaderLines(boolean value)
```

يمثل سلوك عرض خطوط القائد لملصق البيانات في المخطط المحدد. True لعرض خطوط القائد. False للإخفاء. قراءة/كتابة boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من ملصقات البيانات، فإن هذه الخاصية تحصل على أو تعيين القيمة الافتراضية لخاصية ShowLeaderLines للملصقات الجديدة في مجموعة DataLabelCollection. تعيين هذه الخاصية بقيمة يقوم أيضًا بتعيين هذه القيمة لخاصية ShowLeaderLines لجميع ملصقات البيانات في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" يؤدي إلى أن تكون جميع DataLabels.get_Item(i).getShowLeaderLines() مساوية لـ val).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public final boolean getShowLabelValueFromCell()
```

يمثل سلوك عرض قيمة الخلية لملصق البيانات في المخطط المحدد. True لعرض قيمة الخلية. False للإخفاء. قراءة/كتابة boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من ملصقات البيانات، فإن هذه الخاصية تحصل على أو تعيين القيمة الافتراضية لخاصية ShowLabelValueFromCell للملصقات الجديدة في مجموعة DataLabelCollection. تعيين هذه الخاصية بقيمة يقوم أيضًا بتعيين هذه القيمة لخاصية ShowLabelValueFromCell لجميع ملصقات البيانات في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" يؤدي إلى أن تكون جميع DataLabels.get_Item(i).getShowLabelValueFromCell() مساوية لـ val).

**القيمة المرجعة:**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public final void setShowLabelValueFromCell(boolean value)
```

يمثل سلوك عرض قيمة الخلية لملصق البيانات في المخطط المحدد. True لعرض قيمة الخلية. False للإخفاء. قراءة/كتابة boolean.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من ملصقات البيانات، فإن هذه الخاصية تحصل على أو تعيين القيمة الافتراضية لخاصية ShowLabelValueFromCell للملصقات الجديدة في مجموعة DataLabelCollection. تعيين هذه الخاصية بقيمة يقوم أيضًا بتعيين هذه القيمة لخاصية ShowLabelValueFromCell لجميع ملصقات البيانات في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" يؤدي إلى أن تكون جميع DataLabels.get_Item(i).getShowLabelValueFromCell() مساوية لـ val).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public final boolean getShowLabelAsDataCallout()
```

يحدد ما إذا كان ملصق البيانات في المخطط المحدد سيعرض كنقطة اتصال بيانية أو كملصق بيانات.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من ملصقات البيانات، فإن هذه الخاصية تحصل على أو تعيين القيمة الافتراضية لخاصية ShowLabelAsDataCallout للملصقات الجديدة في مجموعة DataLabelCollection. تعيين هذه الخاصية بقيمة يقوم أيضًا بتعيين هذه القيمة لخاصية ShowLabelAsDataCallout لجميع ملصقات البيانات في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" يؤدي إلى أن تكون جميع DataLabels.get_Item(i).getShowLabelAsDataCallout() مساوية لـ val).

**القيمة المرجعة:**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public final void setShowLabelAsDataCallout(boolean value)
```

يحدد ما إذا كان ملصق البيانات في المخطط المحدد سيعرض كنقطة اتصال بيانية أو كملصق بيانات.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من ملصقات البيانات، فإن هذه الخاصية تحصل على أو تعيين القيمة الافتراضية لخاصية ShowLabelAsDataCallout للملصقات الجديدة في مجموعة DataLabelCollection. تعيين هذه الخاصية بقيمة يقوم أيضًا بتعيين هذه القيمة لخاصية ShowLabelAsDataCallout لجميع ملصقات البيانات في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" يؤدي إلى أن تكون جميع DataLabels.get_Item(i).getShowLabelAsDataCallout() مساوية لـ val).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```

تعيين أو إرجاع Variant يمثل الفاصل المستخدم لملصقات البيانات في المخطط. قراءة/كتابة String.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من ملصقات البيانات، فإن هذه الخاصية تحصل على أو تعيين القيمة الافتراضية لخاصية Separator للملصقات الجديدة في مجموعة DataLabelCollection. تعيين هذه الخاصية بقيمة يقوم أيضًا بتعيين هذه القيمة لخاصية Separator لجميع ملصقات البيانات في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" يؤدي إلى أن تكون جميع DataLabels.get_Item(i).getSeparator() مساوية لـ val).

**القيمة المرجعة:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```

تعيين أو إرجاع Variant يمثل الفاصل المستخدم لملصقات البيانات في المخطط. قراءة/كتابة String.

--------------------

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من ملصقات البيانات، فإن هذه الخاصية تحصل على أو تعيين القيمة الافتراضية لخاصية Separator للملصقات الجديدة في مجموعة DataLabelCollection. تعيين هذه الخاصية بقيمة يقوم أيضًا بتعيين هذه القيمة لخاصية Separator لجميع ملصقات البيانات في مجموعة DataLabelCollection (مثال: "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" يؤدي إلى أن تكون جميع DataLabels.get_Item(i).getSeparator() مساوية لـ val).
**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

إرجاع تنسيق نص chart. للقراءة فقط [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**القيمة المرجعة:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getChart() {#getChart--}
```
public final IChart getChart()
```

إرجاع chart. للقراءة فقط [IChart](../../com.aspose.slides/ichart).

**القيمة المرجعة:**
[IChart](../../com.aspose.slides/ichart)