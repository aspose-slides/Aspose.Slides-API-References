---
title: IDataSourceTypeForErrorBarsCustomValues
second_title: دليل API الخاص بـ Aspose.Slides للغة C++
description: يحدد أنواع القيم في قائمة خصائص ChartDataPoint.ErrorBarsCustomValues
type: docs
weight: 976
url: /ar/aspose.slides.charts/idatasourcetypeforerrorbarscustomvalues/
---
## IDataSourceTypeForErrorBarsCustomValues فئة

Specifies types of values in ChartDataPoint.ErrorBarsCustomValues properties list

```cpp
class IDataSourceTypeForErrorBarsCustomValues : public virtual System::Object
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة نقطية عائمة بأسلوب C# حيث تُعتبر NaNان اثنان متساويتين رغم أنه وفقًا لـ IEC 60559:1989 لا تكون NaN مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة نقطية عائمة بأسلوب C# حيث تُعتبر NaNان اثنان متساويتين رغم أنه وفقًا لـ IEC 60559:1989 لا تكون NaN مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [DataSourceType](../datasourcetype/) [get_DataSourceTypeForXMinusValues](./get_datasourcetypeforxminusvalues/)() | يحدد ما إذا كانت الخاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن خاصية XMinus لنقاط البيانات للقيم المخصصة لأشرطة الخطأ. بعبارة أخرى، يحدد نوع قيمة الخاصية ChartDataPoint.ErrorBarsCustomValues.XMinus.Data. اقرأ [DataSourceType](../datasourcetype/). |
| virtual [DataSourceType](../datasourcetype/) [get_DataSourceTypeForXPlusValues](./get_datasourcetypeforxplusvalues/)() | يحدد ما إذا كانت الخاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن خاصية XPlus لنقاط البيانات للقيم المخصصة لأشرطة الخطأ. بعبارة أخرى، يحدد نوع قيمة الخاصية ChartDataPoint.ErrorBarsCustomValues.XPlus.Data. اقرأ [DataSourceType](../datasourcetype/). |
| virtual [DataSourceType](../datasourcetype/) [get_DataSourceTypeForYMinusValues](./get_datasourcetypeforyminusvalues/)() | يحدد ما إذا كانت الخاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن خاصية YMinus لنقاط البيانات للقيم المخصصة لأشرطة الخطأ. بعبارة أخرى، يحدد نوع قيمة الخاصية ChartDataPointEx.ErrorBarsCustomValues.YMinus.Data. اقرأ [DataSourceType](../datasourcetype/). |
| virtual [DataSourceType](../datasourcetype/) [get_DataSourceTypeForYPlusValues](./get_datasourcetypeforyplusvalues/)() | يحدد ما إذا كانت الخاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن خاصية YPlus لنقاط البيانات للقيم المخصصة لأشرطة الخطأ. بعبارة أخرى، يحدد نوع قيمة الخاصية ChartDataPointEx.ErrorBarsCustomValues.YPlus.Data. اقرأ [DataSourceType](../datasourcetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. مماثل لمشغل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل بيان C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويتيح إنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويتيح إنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقوم بتقليل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [set_DataSourceTypeForXMinusValues](./set_datasourcetypeforxminusvalues/)([DataSourceType](../datasourcetype/)) | يحدد ما إذا كانت الخاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن خاصية XMinus لنقاط البيانات للقيم المخصصة لأشرطة الخطأ. بعبارة أخرى، يحدد نوع قيمة الخاصية ChartDataPoint.ErrorBarsCustomValues.XMinus.Data. اكتب [DataSourceType](../datasourcetype/). |
| virtual void [set_DataSourceTypeForXPlusValues](./set_datasourcetypeforxplusvalues/)([DataSourceType](../datasourcetype/)) | يحدد ما إذا كانت الخاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن خاصية XPlus لنقاط البيانات للقيم المخصصة لأشرطة الخطأ. بعبارة أخرى، يحدد نوع قيمة الخاصية ChartDataPoint.ErrorBarsCustomValues.XPlus.Data. اكتب [DataSourceType](../datasourcetype/). |
| virtual void [set_DataSourceTypeForYMinusValues](./set_datasourcetypeforyminusvalues/)([DataSourceType](../datasourcetype/)) | يحدد ما إذا كانت الخاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن خاصية YMinus لنقاط البيانات للقيم المخصصة لأشرطة الخطأ. بعبارة أخرى، يحدد نوع قيمة الخاصية ChartDataPointEx.ErrorBarsCustomValues.YMinus.Data. اكتب [DataSourceType](../datasourcetype/). |
| virtual void [set_DataSourceTypeForYPlusValues](./set_datasourcetypeforyplusvalues/)([DataSourceType](../datasourcetype/)) | يحدد ما إذا كانت الخاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن خاصية YPlus لنقاط البيانات للقيم المخصصة لأشرطة الخطأ. بعبارة أخرى، يحدد نوع قيمة الخاصية ChartDataPointEx.ErrorBarsCustomValues.YPlus.Data. اكتب [DataSourceType](../datasourcetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب الـ n بمؤشر ضعيف (بدلاً من المشترك). يسمح بتبديل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقوم بتقليل وإرجاع عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل بيان C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقوم بتقليل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |

## أنظر أيضًا

* فئة [Object](../../system/object/)
* نطاق [Aspose::Slides::Charts](../)
* مكتبة [Aspose.Slides](../../)