---
title: XsltSettings
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة C++
description: يحدد ميزات XSLT التي يجب دعمها أثناء تنفيذ ورقة أنماط XSLT.
type: docs
weight: 118
url: /ar/system.xml.xsl/xsltsettings/
---
## XsltSettings فئة

Specifies the XSLT features to support during execution of the XSLT style sheet.

```cpp
class XsltSettings : public System::Object
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بنمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بنمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يماثل مقارنة النقطة العائمة بنمط C# حيث يُعتبر NaNانان متساويين رغم أن معيار IEC 60559:1989 يُصِّر أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يماثل مقارنة النقطة العائمة بنمط C# حيث يُعتبر NaNانان متساويين رغم أن معيار IEC 60559:1989 يُصِّر أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لغرض الداخلي فقط. |
| static [SharedPtr](../../system/sharedptr/)\<[XsltSettings](./)\> [get_Default](./get_default/)() | إرجاع كائن [XsltSettings](./) بإعدادات افتراضية. دعم دالة XSLT **document()** والكتل النصية المضمّنة معطل. |
| **bool** [get_EnableDocumentFunction](./get_enabledocumentfunction/)() | إرجاع قيمة تُشير إلى ما إذا كان يجب تمكين دعم دالة XSLT **document()**. |
| **bool** [get_EnableScript](./get_enablescript/)() | إرجاع قيمة تُشير إلى ما إذا كان يجب تمكين دعم الكتل النصية المضمّنة. |
| static [SharedPtr](../../system/sharedptr/)\<[XsltSettings](./)\> [get_TrustedXslt](./get_trustedxslt/)() | إرجاع كائن [XsltSettings](./) يُمكّن دعم دالة XSLT **document()** والكتل النصية المضمّنة. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عدّاد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يُمكّن تجزئة الكائنات المخصّصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. نظير عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | يُنفّذ قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يُمكّن استنساخ الأنواع المخصّصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيء جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ أي شيء، في الحقيقة، فقط يهيء كائنًا جديدًا ويُمكّن بنية نسخ الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء، في الحقيقة، فقط يهيء كائنًا جديدًا ويُمكّن بنية نسخ الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن بالمرجع كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يُقلِّل عدّاد المرجع المشترك بالقيمة المحددة. |
| void [set_EnableDocumentFunction](./set_enabledocumentfunction/)(**bool**) | يضبط قيمة تُشير إلى ما إذا كان يجب تمكين دعم دالة XSLT **document()**. |
| void [set_EnableScript](./set_enablescript/)(**bool**) | يضبط قيمة تُشير إلى ما إذا كان يجب تمكين دعم الكتل النصية المضمّنة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط النّ من القالب كإشارة ضعيفة (بدلاً من مشتركة). يتيح تحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعدّاد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يُمكّن تحويل الكائنات المخصّصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يُنفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يُنفّذ إلغاء قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
|  [XsltSettings](./xsltsettings/)() | يُهيئ نسخة جديدة من الفئة [XsltSettings](./) بإعدادات افتراضية. |
|  [XsltSettings](./xsltsettings/)(**bool**, **bool**) | يُهيئ نسخة جديدة من الفئة [XsltSettings](./) بالإعدادات المحددة. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يُحرّر جميع بنى البيانات الداخلية. |

## تعريفات الأنواع

| تعريف النوع | الوصف |
| --- | --- |
| [Ptr](./ptr/) | اسم مستعار للمؤشر المشترك إلى نسخة من هذه الفئة. |

## ملاحظات

يجب إنشاء كائنات هذه الفئة باستخدام دالة [System::MakeObject()](../../system/makeobject/) فقط. لا تقم بإنشاء نسخ من هذا النوع على المكدس أو باستخدام عامل new، لأن ذلك سيتسبب في أخطاء وقت التشغيل و/أو أعطال التأكيد. دائماً غلف هذه الفئة داخل مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. 

## أنظر أيضاً

* فئة [Object](../../system/object/)
* مساحة الأسماء [System::Xml::Xsl](../)
* المكتبة [Aspose.Slides](../../)