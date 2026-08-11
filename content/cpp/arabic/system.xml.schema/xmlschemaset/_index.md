---
title: XmlSchemaSet
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحتوي على ذاكرة مخبأة لمخططات لغة تعريف مخطط XML (XSD).
type: docs
weight: 781
url: /ar/system.xml.schema/xmlschemaset/
---
## فئة XmlSchemaSet

Contains a cache of XML [Schema](../) definition language (XSD) schemas.

```cpp
class XmlSchemaSet : public System::Object
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Add](./add/)([String](../../system/string/), const [String](../../system/string/)\&) | يضيف مخطط XML [Schema](../) تعريف اللغة (XSD) عند URL المحدد إلى [XmlSchemaSet](./). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Add](./add/)([String](../../system/string/), const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&) | يضيف مخطط XML [Schema](../) تعريف اللغة (XSD) الموجود في [XmlReader](../../system.xml/xmlreader/) إلى [XmlSchemaSet](./). |
| void [Add](./add/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSet](./)\>\&) | يضيف جميع مخططات XML [Schema](../) تعريف اللغة (XSD) الموجودة في [XmlSchemaSet](./) إلى [XmlSchemaSet](./). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Add](./add/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | يضيف [XmlSchema](../xmlschema/) المحددة إلى [XmlSchemaSet](./). |
| void [Compile](./compile/)() | يقوم بدمج مخططات XML [Schema](../) تعريف اللغة (XSD) المضافة إلى [XmlSchemaSet](./) في مخطط منطقي واحد. |
| **bool** [Contains](./contains/)([String](../../system/string/)) | يشير إلى ما إذا كان مخطط XML [Schema](../) تعريف اللغة (XSD) مع مساحة الاسم الهدف المحددة موجودًا في [XmlSchemaSet](./). |
| **bool** [Contains](./contains/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | يشير إلى ما إذا كان كائن [Schema](../) XML [XmlSchema](../xmlschema/) تعريف اللغة (XSD) المحدد موجودًا في [XmlSchemaSet](./). |
| void [CopyTo](./copyto/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\>\&, **int32_t**) | ينسخ جميع كائنات [XmlSchema](../xmlschema/) من [XmlSchemaSet](./) إلى المصفوفة المعطاة، بدءًا من الفهرس المحدد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN غير مساوي لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN غير مساوي لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaCompilationSettings](../xmlschemacompilationsettings/)\> [get_CompilationSettings](./get_compilationsettings/)() | إرجاع [XmlSchemaCompilationSettings](../xmlschemacompilationsettings/) لـ [XmlSchemaSet](./). |
| **int32_t** [get_Count](./get_count/)() | إرجاع عدد مخططات XML [Schema](../) تعريف اللغة (XSD) المنطقية في [XmlSchemaSet](./). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_GlobalAttributes](./get_globalattributes/)() | إرجاع جميع الصفات العامة في جميع مخططات XML [Schema](../) تعريف اللغة (XSD) في [XmlSchemaSet](./). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_GlobalElements](./get_globalelements/)() | إرجاع جميع العناصر العامة في جميع مخططات XML [Schema](../) تعريف اللغة (XSD) في [XmlSchemaSet](./). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_GlobalTypes](./get_globaltypes/)() | إرجاع جميع الأنواع العامة البسيطة والمعقدة في جميع مخططات XML [Schema](../) تعريف اللغة (XSD) في [XmlSchemaSet](./). |
| **bool** [get_IsCompiled](./get_iscompiled/)() | يرجع قيمة تشير إلى ما إذا تم تجميع مخططات XML [Schema](../) تعريف اللغة (XSD) في [XmlSchemaSet](./). |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\> [get_NameTable](./get_nametable/)() | يرجع [XmlNameTable](../../system.xml/xmlnametable/) الافتراضي المستخدم بواسطة [XmlSchemaSet](./) عند تحميل مخططات XML [Schema](../) تعريف اللغة (XSD) الجديدة. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عدّاد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل مثيلًا لنوع موصوف بواسطة targetType. نظير لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بنسخ بناء الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بنسخ بناء الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعياً كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالات السلاسل. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Remove](./remove/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | يزيل مخطط XML [Schema](../) تعريف اللغة (XSD) المحدد من [XmlSchemaSet](./). |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدّاد المرجع المشترك بالقيمة المحددة. |
| **bool** [RemoveRecursive](./removerecursive/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | يزيل مخطط XML [Schema](../) تعريف اللغة (XSD) المحدد وجميع المخططات التي يستوردها من [XmlSchemaSet](./). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Reprocess](./reprocess/)([SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>) | يعيد معالجة مخطط XML [Schema](../) تعريف اللغة (XSD) الموجود بالفعل في [XmlSchemaSet](./). |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\>\> [Schemas](./schemas/)() | يرجع مجموعة من جميع مخططات XML [Schema](../) تعريف اللغة (XSD) في [XmlSchemaSet](./). |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\>\> [Schemas](./schemas/)([String](../../system/string/)) | يرجع مجموعة من جميع مخططات XML [Schema](../) تعريف اللغة (XSD) في [XmlSchemaSet](./) التي تنتمي إلى مساحة الاسم المحددة. |
| void [set_CompilationSettings](./set_compilationsettings/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaCompilationSettings](../xmlschemacompilationsettings/)\>\&) | يضبط [XmlSchemaCompilationSettings](../xmlschemacompilationsettings/) لـ [XmlSchemaSet](./). |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | يضبط [XmlResolver](../../system.xml/xmlresolver/) المستخدم لحل مساحات الأسماء أو المواقع المشار إليها في عناصر include و import للمخطط. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب الـ n كضعيف (بدلاً من مشترك). يتيح تحويل المؤشرات في الحاويات إلى وضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن [LockContext](../../system/lockcontext/). |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | يضيف معالج حدث لتلقي معلومات عن أخطاء تحقق مخطط XML [Schema](../) تعريف اللغة (XSD). |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | يزيل معالج حدث لتلقي معلومات عن أخطاء تحقق مخطط XML [Schema](../) تعريف اللغة (XSD). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
|  [XmlSchemaSet](./xmlschemaset/)() | يُهيّء مثيلًا جديدًا للفئة [XmlSchemaSet](./). |
|  [XmlSchemaSet](./xmlschemaset/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\>\&) | يُهيّء مثيلًا جديدًا للفئة [XmlSchemaSet](./) باستخدام [XmlNameTable](../../system.xml/xmlnametable/) المحدد. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## التعريفات

| التعريف | الوصف |
| --- | --- |
| [Ptr](./ptr/) | اسم مستعار لمؤشر مشترك إلى مثيل من هذه الفئة. |

## ملاحظات

يجب تخصيص كائنات هذه الفئة باستخدام دالة [System::MakeObject()](../../system/makeobject/) فقط. لا تقم أبدًا بإنشاء مثيلات من هذا النوع على المكدس أو باستخدام العامل new، حيث سيؤدي ذلك إلى أخطاء وقت تشغيل و/أو أعطال في التأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

## أنظر أيضًا

* الفئة [Object](../../system/object/)
* النطاق [System::Xml::Schema](../)
* المكتبة [Aspose.Slides](../../)