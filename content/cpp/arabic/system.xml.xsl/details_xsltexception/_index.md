---
title: Details_XsltException
second_title: مرجع API لـ Aspose.Slides للغة C++
description: الاستثناء الذي يُرمى عندما يحدث خطأ أثناء معالجة تحويل XSLT.
type: docs
weight: 14
url: /ar/system.xml.xsl/details_xsltexception/
---
## Details_XsltException فئة

الاستثناء الذي يُرمى عندما يحدث خطأ أثناء معالجة تحويل XSLT.

```cpp
class Details_XsltException : public System::Details_SystemException
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات من نوع الإشارة بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات من نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة نقطية عائمة بأسلوب C# حيث تُعتبر NaNان متساوين رغم أن وفقًا لـ IEC 60559:1989 لا يعتبر NaN مساويًا لأي قيمة، بما فيها NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة نقطية عائمة بأسلوب C# حيث تُعتبر NaNان متساوين رغم أن وفقًا لـ IEC 60559:1989 لا يعتبر NaN مساويًا لأي قيمة، بما فيها NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\> [get_Data](../../system/details_exception/get_data/)() | يعيد قاموسًا يحتوي على بيانات استثناء مخصصة. |
| **int32_t** [get_HResult](../../system/details_exception/get_hresult/)() const | يعيد قيمة عددية من 32 بت تمثل رمز HRESULT المرتبط بالاستثناء الممثَّل بالكائن الحالي. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [get_InnerException](../../system/details_exception/get_innerexception/)() const | يعيد مرجعًا إلى الكائن الذي يمثل الاستثناء الداخلي. |
| virtual **int32_t** [get_LineNumber](./get_linenumber/)() | يعيد رقم السطر الذي يشير إلى مكان حدوث الخطأ في ورقة الأنماط. |
| virtual **int32_t** [get_LinePosition](./get_lineposition/)() | يعيد موضع السطر الذي يشير إلى مكان حدوث الخطأ في ورقة الأنماط. |
| [String](../../system/string/) [get_Message](./get_message/)() const override | يعيد رسالة الخطأ المنسقة التي تصف الاستثناء الحالي. |
| virtual [String](../../system/string/) [get_SourceUri](./get_sourceuri/)() | يعيد مسار موقع ورقة الأنماط. |
| virtual [String](../../system/string/) [get_StackTrace](../../system/details_exception/get_stacktrace/)() const | يعيد السلسلة التي تحتوي على تتبع المكدس. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [GetBaseException](../../system/details_exception/getbaseexception/)() const | يعيد نسخة من كائن Exception الذي يمثل الاستثناء الأكثر داخلًا. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| const [System::TypeInfo](../../system/typeinfo/)\& [GetType](../../system/details_systemexception/gettype/)() const override | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| **bool** [Is](../../system/details_systemexception/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const override |  |
| void [Lock](../../system/object/lock/)() | ينفذ قفل جملة C# lock(). استدعِه مباشرة أو استخدم الكائن [LockContext](../../system/lockcontext/) الحارس. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويفعل إنشاء النسخ للفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويفعل إنشاء النسخ للفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات عن طريق المرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات عن طريق المرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_HResult](../../system/details_exception/set_hresult/)(**int32_t**) | يضبط HRESULT، وهو قيمة رقمية مشفرة تُعطى لاستثناء محدد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي الـ n إلى مؤشر ضعيف (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| [String](../../system/string/) [ToString](../../system/details_exception/tostring/)() const override | يعيد تمثيل السلسلة للكائن الحالي. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/details_systemexception/type/)() |  |
| void [Unlock](../../system/object/unlock/)() | ينفذ فك قفل جملة C# lock(). استدعِه مباشرة أو استخدم الكائن [LockContext](../../system/lockcontext/) الحارس. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual const char * [what](../../system/details_exception/what/)() const | ينفذ طريقة [what()](../../system/details_exception/what/) التي يستدعيها الصف [ExceptionWrapper](../../system/exceptionwrapper/). على الرغم من أن هذا الصف لا يرث من std::exception، فإن الصفوف المشتقة يمكنها استخدام الأعضاء المحمية/الخاصة لتنفيذ منطقها. نقل تنفيذ هذه الطريقة إلى [ExceptionWrapper](../../system/exceptionwrapper/) قد يعيق ذلك المنطق. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## تعريفات الأنواع

| التعريف | الوصف |
| --- | --- |
| [Ptr](./ptr/) | اسم مستعار لمؤشر مشترك إلى نسخة من هذه الفئة. |

## انظر أيضاً

* الفئة [Details_SystemException](../../system/details_systemexception/)
* النطاق [System::Xml::Xsl](../)
* المكتبة [Aspose.Slides](../../)