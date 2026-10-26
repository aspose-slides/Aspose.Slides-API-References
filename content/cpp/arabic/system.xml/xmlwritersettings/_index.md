---
title: XmlWriterSettings
second_title: مرجع API لـ Aspose.Slides للـ C++
description: "يحدد مجموعة من الميزات لدعمها على كائن XmlWriter الذي تم إنشاؤه بواسطة طريقة XmlWriter::Create."
type: docs
weight: 586
url: /ar/system.xml/xmlwritersettings/
---
## فئة XmlWriterSettings

يحدد مجموعة من الميزات لدعمها على كائن [XmlWriter](../xmlwriter/) الذي تم إنشاؤه بواسطة طريقة [XmlWriter::Create](../xmlwriter/create/).

```cpp
class XmlWriterSettings : public System::Object
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](./)\> [Clone](./clone/)() | ينشئ نسخة من كائن [XmlWriterSettings](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بنمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بنمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة الأعداد الفاصلة العائمة بنمط C# حيث تُعتبر قيمتا NaN متساويتين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليست مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة الأعداد العائمة بنمط C# حيث تُعتبر قيمتا NaN متساويتين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليست مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | يرجع قيمة تشير إلى ما إذا كان كاتب XML يجب أن يتحقق لضمان أن جميع الأحرف في المستند تتوافق مع قسم "2.2 Characters" من W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets). |
| **bool** [get_CloseOutput](./get_closeoutput/)() | يرجع قيمة تشير إلى ما إذا كان [XmlWriter](../xmlwriter/) يجب أن يغلق أيضًا الدفق الأساسي أو TextWriter عند استدعاء طريقة [XmlWriter::Close](../xmlwriter/close/). |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | يرجع مستوى الالتزام الذي يتحقق منه كاتب XML لمخرج XML. |
| **bool** [get_DoNotEscapeUriAttributes](./get_donotescapeuriattributes/)() | يرجع قيمة تشير إلى ما إذا كان [XmlWriter](../xmlwriter/) لا يقوم بتهرب خصائص URI. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | يرجع نوع ترميز النص لاستخدامه. |
| **bool** [get_Indent](./get_indent/)() | يرجع قيمة تشير إلى ما إذا كان يجب إزاحة العناصر. |
| [String](../../system/string/) [get_IndentChars](./get_indentchars/)() | يرجع سلسلة الأحرف المستخدمة عند الإزاحة. يُستخدم هذا الإعداد عندما تكون قيمة [XmlWriterSettings::set_Indent](./set_indent/) مضبوطة على **true**. |
| [System::Xml::NamespaceHandling](../namespacehandling/) [get_NamespaceHandling](./get_namespacehandling/)() | يرجع قيمة تشير إلى ما إذا كان [XmlWriter](../xmlwriter/) يجب أن يزيل إعلانات المجال المتكررة عند كتابة محتوى XML. السلوك الافتراضي هو أن يقوم الكاتب بإخراج جميع إعلانات النطاق الموجودة في محلل النطاق الخاص بالكاتب. |
| [String](../../system/string/) [get_NewLineChars](./get_newlinechars/)() | يرجع سلسلة الأحرف المستخدمة لفواصل الأسطر. |
| [System::Xml::NewLineHandling](../newlinehandling/) [get_NewLineHandling](./get_newlinehandling/)() | يرجع قيمة تشير إلى ما إذا كان يجب تطبيع فواصل الأسطر في الناتج. |
| **bool** [get_NewLineOnAttributes](./get_newlineonattributes/)() | يرجع قيمة تشير إلى ما إذا كان يجب كتابة الخصائص في سطر جديد. |
| **bool** [get_OmitXmlDeclaration](./get_omitxmldeclaration/)() | يرجع قيمة تشير إلى ما إذا كان يجب حذف إعلان XML. |
| [XmlOutputMethod](../xmloutputmethod/) [get_OutputMethod](./get_outputmethod/)() | يرجع الطريقة المستخدمة لتسلسل ناتج [XmlWriter](../xmlwriter/). |
| **bool** [get_WriteEndDocumentOnClose](./get_writeenddocumentonclose/)() | يرجع قيمة تشير إلى ما إذا كان [XmlWriter](../xmlwriter/) سيضيف وسوم إغلاق لجميع وسوم العناصر غير المغلقة عند استدعاء طريقة [XmlWriter::Close](../xmlwriter/close/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. نظير عامل 'is' في C#. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل بيان C# lock(). استدعِ مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ الكائن. يُهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخة. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويُمكّن بناء نسخ الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويُمكّن بناء نسخ الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن بالمرجعية كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [Reset](./reset/)() | يعيد ضبط أعضاء فئة الإعدادات إلى قيمها الافتراضية. |
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان كاتب XML يجب أن يتحقق لضمان أن جميع الأحرف في المستند تتوافق مع قسم "2.2 Characters" من W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets). |
| void [set_CloseOutput](./set_closeoutput/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان [XmlWriter](../xmlwriter/) يجب أن يغلق أيضًا الدفق الأساسي أو TextWriter عند استدعاء طريقة [XmlWriter::Close](../xmlwriter/close/). |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | يضبط مستوى الالتزام الذي يتحقق منه كاتب XML لمخرج XML. |
| void [set_DoNotEscapeUriAttributes](./set_donotescapeuriattributes/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان [XmlWriter](../xmlwriter/) لا يقوم بتهرب خصائص URI. |
| void [set_Encoding](./set_encoding/)(const [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\>\&) | يضبط نوع ترميز النص لاستخدامه. |
| void [set_Indent](./set_indent/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان يجب إزاحة العناصر. |
| void [set_IndentChars](./set_indentchars/)(const [String](../../system/string/)\&) | يضبط سلسلة الأحرف المستخدمة عند الإزاحة. يُستخدم هذا الإعداد عندما تكون قيمة [XmlWriterSettings::set_Indent](./set_indent/) مضبوطة على **true**. |
| void [set_NamespaceHandling](./set_namespacehandling/)([System::Xml::NamespaceHandling](../namespacehandling/)) | يضبط قيمة تشير إلى ما إذا كان [XmlWriter](../xmlwriter/) يجب أن يزيل إعلانات المجال المتكررة عند كتابة محتوى XML. السلوك الافتراضي هو أن يقوم الكاتب بإخراج جميع إعلانات النطاق الموجودة في محلل النطاق الخاص بالكاتب. |
| void [set_NewLineChars](./set_newlinechars/)(const [String](../../system/string/)\&) | يضبط سلسلة الأحرف المستخدمة لفواصل الأسطر. |
| void [set_NewLineHandling](./set_newlinehandling/)([System::Xml::NewLineHandling](../newlinehandling/)) | يضبط قيمة تشير إلى ما إذا كان يجب تطبيع فواصل الأسطر في الناتج. |
| void [set_NewLineOnAttributes](./set_newlineonattributes/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان يجب كتابة الخصائص في سطر جديد. |
| void [set_OmitXmlDeclaration](./set_omitxmldeclaration/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان يجب حذف إعلان XML. |
| void [set_WriteEndDocumentOnClose](./set_writeenddocumentonclose/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان [XmlWriter](../xmlwriter/) سيضيف وسوم إغلاق لجميع وسوم العناصر غير المغلقة عند استدعاء طريقة [XmlWriter::Close](../xmlwriter/close/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب الـ n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عدد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل بيان C# lock(). استدعِ مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
|  [XmlWriterSettings](./xmlwritersettings/)() | يُهيئ نسخة جديدة من فئة [XmlWriterSettings](./). |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## تعريفات الأنواع

| التعريف | الوصف |
| --- | --- |
| [Ptr](./ptr/) | اسم مستعار لمؤشر مشترك إلى نسخة من هذه الفئة. |

## ملاحظات

يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تقم أبدًا بإنشاء نسخ من هذا النوع على المكدس أو باستخدام عامل new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل أو أعطال التأكيد. دائمًا غلف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

## انظر أيضًا

* الفئة [Object](../../system/object/)
* النطاق [System::Xml](../)
* المكتبة [Aspose.Slides](../../)