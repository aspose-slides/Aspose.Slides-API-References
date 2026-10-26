---
title: XmlReaderSettings
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يحدد مجموعة من الميزات لدعمها على كائن XmlReader الذي تم إنشاؤه بواسطة طريقة XmlReader::Create."
type: docs
weight: 443
url: /ar/system.xml/xmlreadersettings/
---
## XmlReaderSettings فئة

يحدد مجموعة من الميزات لدعمها على كائن [XmlReader](../xmlreader/) الذي تم إنشاؤه بواسطة طريقة [XmlReader::Create](../xmlreader/create/).

```cpp
class XmlReaderSettings : public System::Object
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| void [CheckReadOnly](./checkreadonly/)(const [String](../../system/string/)\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](./)\> [Clone](./clone/)() | يقوم بإنشاء نسخة من المثيل [XmlReaderSettings](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يcompare الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يُقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر اثنان NaN متساويين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليس متساويًا مع أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر اثنان NaN متساويين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليس متساويًا مع أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | يعيد قيمة تشير إلى ما إذا كان يجب إجراء فحص الأحرف. |
| **bool** [get_CloseInput](./get_closeinput/)() | يعيد قيمة تشير إلى ما إذا كان يجب إغلاق التدفق الأساسي أو TextReader عند إغلاق القارئ. |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | يعيد مستوى التوافق الذي سيتوافق معه [XmlReader](../xmlreader/). |
| [System::Xml::DtdProcessing](../dtdprocessing/) [get_DtdProcessing](./get_dtdprocessing/)() | يعيد قيمة تحدد معالجة DTDs. |
| **bool** [get_IgnoreComments](./get_ignorecomments/)() | يعيد قيمة تشير إلى ما إذا كان يجب تجاهل التعليقات. |
| **bool** [get_IgnoreProcessingInstructions](./get_ignoreprocessinginstructions/)() | يعيد قيمة تشير إلى ما إذا كان يجب تجاهل تعليمات المعالجة. |
| **bool** [get_IgnoreWhitespace](./get_ignorewhitespace/)() | يعيد قيمة تشير إلى ما إذا كان يجب تجاهل المسافات البيضاء غير المهمة. |
| **int32_t** [get_LineNumberOffset](./get_linenumberoffset/)() | يعيد إزاحة رقم السطر لكائن [XmlReader](../xmlreader/). |
| **int32_t** [get_LinePositionOffset](./get_linepositionoffset/)() | يعيد إزاحة موضع السطر لكائن [XmlReader](../xmlreader/). |
| **int64_t** [get_MaxCharactersFromEntities](./get_maxcharactersfromentities/)() | يعيد قيمة تشير إلى الحد الأقصى المسموح لعدد الأحرف في مستند ناتج عن توسيع الكيانات. |
| **int64_t** [get_MaxCharactersInDocument](./get_maxcharactersindocument/)() | يعيد قيمة تشير إلى الحد الأقصى المسموح لعدد الأحرف في مستند XML. القيمة صفر (0) تعني عدم وجود حدود لحجم مستند XML. القيمة غير الصفرية تحدد الحد الأقصى للحجم، بالأحرف. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | يعيد [XmlNameTable](../xmlnametable/) المستخدم لمقارنات السلاسل المتجذرة. |
| **bool** [get_ProhibitDtd](./get_prohibitdtd/)() | يعيد قيمة تشير إلى ما إذا كان يجب منع معالجة تعريف نوع المستند (DTD). |
| [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\> [get_Schemas](./get_schemas/)() | يعيد XmlSchemaSet لاستخدامه عند تنفيذ التحقق من المخطط. |
| [Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/) [get_ValidationFlags](./get_validationflags/)() | يعيد قيمة تشير إلى إعدادات التحقق من المخطط. ينطبق هذا الإعداد على كائنات [XmlReader](../xmlreader/) التي تتحقق من المخططات (القيمة [XmlReaderSettings::get_ValidationType](./get_validationtype/) هي [ValidationType::Schema](../validationtype/)). |
| [System::Xml::ValidationType](../validationtype/) [get_ValidationType](./get_validationtype/)() | يعيد قيمة تشير إلى ما إذا كان [XmlReader](../xmlreader/) سيقوم بالتحقق أو تعيين النوع عند القراءة. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق ما إذا كان الكائن يمثل مثلاً من النوع الموصوف بـ targetType. نظير معامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل بيان C# lock(). استدعِه مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويفسح المجال لإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويفسح المجال لإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعياً كائن النوع القيمي بـ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) في حالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) في حالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بقيمة محددة. |
| void [Reset](./reset/)() | يعيد ضبط أعضاء فئة الإعدادات إلى قيمها الافتراضية. |
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان يجب إجراء فحص الأحرف. |
| void [set_CloseInput](./set_closeinput/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان يجب إغلاق التدفق الأساسي أو TextReader عند إغلاق القارئ. |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | يضبط مستوى التوافق الذي سيتوافق معه [XmlReader](../xmlreader/). |
| void [set_DtdProcessing](./set_dtdprocessing/)([System::Xml::DtdProcessing](../dtdprocessing/)) | يضبط قيمة تحدد معالجة DTDs. |
| void [set_IgnoreComments](./set_ignorecomments/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان يجب تجاهل التعليقات. |
| void [set_IgnoreProcessingInstructions](./set_ignoreprocessinginstructions/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان يجب تجاهل تعليمات المعالجة. |
| void [set_IgnoreWhitespace](./set_ignorewhitespace/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان يجب تجاهل المسافات البيضاء غير المهمة. |
| void [set_LineNumberOffset](./set_linenumberoffset/)(**int32_t**) | يضبط إزاحة رقم السطر لكائن [XmlReader](../xmlreader/). |
| void [set_LinePositionOffset](./set_linepositionoffset/)(**int32_t**) | يضبط إزاحة موضع السطر لكائن [XmlReader](../xmlreader/). |
| void [set_MaxCharactersFromEntities](./set_maxcharactersfromentities/)(**int64_t**) | يضبط قيمة تشير إلى الحد الأقصى المسموح لعدد الأحرف في مستند ناتج عن توسيع الكيانات. |
| void [set_MaxCharactersInDocument](./set_maxcharactersindocument/)(**int64_t**) | يضبط قيمة تشير إلى الحد الأقصى المسموح لعدد الأحرف في مستند XML. القيمة صفر (0) تعني عدم وجود حدود لحجم مستند XML. القيمة غير الصفرية تحدد الحد الأقصى للحجم، بالأحرف. |
| void [set_NameTable](./set_nametable/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | يضبط [XmlNameTable](../xmlnametable/) المستخدم لمقارنات السلاسل المتجذرة. |
| void [set_ProhibitDtd](./set_prohibitdtd/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان يجب منع معالجة تعريف نوع المستند (DTD). |
| void [set_Schemas](./set_schemas/)(const [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>\&) | يضبط XmlSchemaSet لاستخدامه عند تنفيذ التحقق من المخطط. |
| void [set_ValidationFlags](./set_validationflags/)([Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/)) | يضبط قيمة تشير إلى إعدادات التحقق من المخطط. ينطبق هذا الإعداد على كائنات [XmlReader](../xmlreader/) التي تتحقق من المخططات (القيمة [XmlReaderSettings::get_ValidationType](./get_validationtype/) هي [ValidationType::Schema](../validationtype/)). |
| void [set_ValidationType](./set_validationtype/)([System::Xml::ValidationType](../validationtype/)) | يضبط قيمة تشير إلى ما إذا كان [XmlReader](../xmlreader/) سيقوم بالتحقق أو تعيين النوع عند القراءة. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | يضبط [XmlResolver](../xmlresolver/) المستخدم للوصول إلى المستندات الخارجية. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط المتغير النمطي رقم n كمؤشر ضعيف (بدلاً من المشترك). يتيح تبديل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ بدلًا من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ بدلًا من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل بيان C# lock(). استدعِه مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | يضيف معالج حدث يحدث عندما يواجه القارئ أخطاء التحقق. |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | يزيل معالج الحدث الذي يحدث عندما يواجه القارئ أخطاء التحقق. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ بدلًا من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ بدلًا من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
|  [XmlReaderSettings](./xmlreadersettings/)() | يُهيئ نسخة جديدة من فئة [XmlReaderSettings](./). |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## أنواع تعريفية

| تعريف نوع | الوصف |
| --- | --- |
| [Ptr](./ptr/) | اسم مستعار للمؤشر المشترك إلى مثيل من هذه الفئة. |

## ملاحظات

يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تقم أبدًا بإنشاء مثيلات من هذا النوع على المكدس أو باستخدام عامل new، حيث سيتسبب ذلك في أخطاء وقت التشغيل أو أعطال التأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدام هذا المؤشر لتمريره إلى الدوال كوسيطة.

## انظر أيضًا

* فئة [Object](../../system/object/)
* مساحة الاسم [System::Xml](../)
* مكتبة [Aspose.Slides](../../)