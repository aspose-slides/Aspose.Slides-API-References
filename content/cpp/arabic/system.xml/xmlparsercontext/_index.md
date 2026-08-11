---
title: XmlParserContext
second_title: مرجع API Aspose.Slides للـ C++
description: يوفر جميع معلومات السياق المطلوبة من قبل XmlReader لتحليل جزء XML.
type: docs
weight: 391
url: /ar/system.xml/xmlparsercontext/
---
## XmlParserContext فئة


Provides all the context information required by the [XmlReader](../xmlreader/) to parse an XML fragment.

```cpp
class XmlParserContext : public System::Object
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يقوم بمحاكاة مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين على الرغم من أنه وفقًا لـ IEC 60559:1989 فإن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يقوم بمحاكاة مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين على الرغم من أنه وفقًا لـ IEC 60559:1989 فإن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للغرض الداخلي فقط. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | يعيد URI الأساسي. |
| [String](../../system/string/) [get_DocTypeName](./get_doctypename/)() | يعيد اسم إعلان نوع المستند. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | يعيد نوع الترميز. |
| [String](../../system/string/) [get_InternalSubset](./get_internalsubset/)() | يعيد الجزء الداخلي من DTD. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\> [get_NamespaceManager](./get_namespacemanager/)() | يعيد الـ [XmlNamespaceManager](../xmlnamespacemanager/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | يعيد الـ [XmlNameTable](../xmlnametable/) المستخدم لتجزيء السلاسل. لمزيد من المعلومات حول السلاسل المجزأة، انظر [XmlNameTable](../xmlnametable/). |
| [String](../../system/string/) [get_PublicId](./get_publicid/)() | يعيد المعرف العام. |
| [String](../../system/string/) [get_SystemId](./get_systemid/)() | يعيد المعرف النظامي. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | يعيد نطاق **xml:lang** الحالي. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() | يعيد نطاق **xml:space** الحالي. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجعية المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تماثل طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تماثل استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. تماثل عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | يقوم بتنفيذ قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تماثل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ الكائن. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويتيح إنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويتيح إنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن بالمرجع كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_BaseURI](./set_baseuri/)(const [String](../../system/string/)\&) | يضبط URI الأساسي. |
| void [set_DocTypeName](./set_doctypename/)(const [String](../../system/string/)\&) | يضبط اسم إعلان نوع المستند. |
| void [set_Encoding](./set_encoding/)(const [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\>\&) | يضبط نوع الترميز. |
| void [set_InternalSubset](./set_internalsubset/)(const [String](../../system/string/)\&) | يضبط الجزء الداخلي من DTD. |
| void [set_NamespaceManager](./set_namespacemanager/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | يضبط الـ [XmlNamespaceManager](../xmlnamespacemanager/). |
| void [set_NameTable](./set_nametable/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | يضبط الـ [XmlNameTable](../xmlnametable/) المستخدم لتجزيء السلاسل. لمزيد من المعلومات حول السلاسل المجزأة، انظر [XmlNameTable](../xmlnametable/). |
| void [set_PublicId](./set_publicid/)(const [String](../../system/string/)\&) | يضبط المعرف العام. |
| void [set_SystemId](./set_systemid/)(const [String](../../system/string/)\&) | يضبط المعرف النظامي. |
| void [set_XmlLang](./set_xmllang/)(const [String](../../system/string/)\&) | يضبط نطاق **xml:lang** الحالي. |
| void [set_XmlSpace](./set_xmlspace/)([System::Xml::XmlSpace](../xmlspace/)) | يضبط نطاق **xml:space** الحالي. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n كمؤشر ضعيف (بدلاً من المشترك). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تماثل طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يقوم بتنفيذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يقوم بتنفيذ فك قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
|  [XmlParserContext](./xmlparsercontext/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&, const [String](../../system/string/)\&, [System::Xml::XmlSpace](../xmlspace/)) | ينشئ نسخة جديدة من الفئة [XmlParserContext](./) بالقيم المحددة [XmlNameTable](../xmlnametable/)، [XmlNamespaceManager](../xmlnamespacemanager/)، **xml:lang** و **xml:space**. |
|  [XmlParserContext](./xmlparsercontext/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&, const [String](../../system/string/)\&, [System::Xml::XmlSpace](../xmlspace/), const [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\>\&) | ينشئ نسخة جديدة من الفئة [XmlParserContext](./) بالقيم المحددة [XmlNameTable](../xmlnametable/)، [XmlNamespaceManager](../xmlnamespacemanager/)، **xml:lang**، **xml:space**، والترميز. |
|  [XmlParserContext](./xmlparsercontext/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, [System::Xml::XmlSpace](../xmlspace/)) | ينشئ نسخة جديدة من الفئة [XmlParserContext](./) بالقيم المحددة [XmlNameTable](../xmlnametable/)، [XmlNamespaceManager](../xmlnamespacemanager/)، URI الأساس، **xml:lang**، **xml:space**، وقيم نوع المستند. |
|  [XmlParserContext](./xmlparsercontext/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, [System::Xml::XmlSpace](../xmlspace/), const [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\>\&) | ينشئ نسخة جديدة من الفئة [XmlParserContext](./) بالقيم المحددة [XmlNameTable](../xmlnametable/)، [XmlNamespaceManager](../xmlnamespacemanager/)، URI الأساس، **xml:lang**، **xml:space**، الترميز، وقيم نوع المستند. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |

## تعريفات النوع

| تعريف نوع | الوصف |
| --- | --- |
| [Ptr](./ptr/) | اسم مستعار لمؤشر مشترك لنسخة من هذه الفئة. |

## ملاحظات

يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تُنشئ أبدًا نسخًا من هذا النوع على المكدس أو باستخدام العامل new، لأنه سيتسبب في أخطاء وقت التشغيل و/أو أخطاء التأكيد. احصر دائمًا هذه الفئة داخل مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. 

## انظر أيضًا

* فئة [Object](../../system/object/)
* مساحة الاسم [System::Xml](../)
* مكتبة [Aspose.Slides](../../)