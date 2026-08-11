---
title: SecureString
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "Secure string، تمثل نصًا يجب أن يبقى سريًا. هذه الفئة لا تقوم بتشفير البيانات الداخلية. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject() . لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام العامل new، حيث سيؤدي ذلك إلى أخطاء وقت تشغيل أو فشل في التأكيد. دائمًا قم بلف هذه الفئة في مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 14
url: /ar/system.security/securestring/
---
## SecureString فئة

سلسلة آمنة، تمثل نصًا يجب أن يبقى سريًا. هذه الفئة لا تقوم بتشفير البيانات الداخلية. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام العامل new، حيث سيؤدي ذلك إلى أخطاء وقت تشغيل و/أو فشل في التأكيد. دائمًا قم بلف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class SecureString : public System::IDisposable
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| void [AppendChar](./appendchar/)(char16_t) | يضيف حرفًا إلى نهاية السلسلة. |
| void [Clear](./clear/)() | يحذف جميع الأحرف من السلسلة الآمنة الحالية. |
| [SecureStringPtr](../securestringptr/) [Copy](./copy/)() const | ينشئ نسخة متماثلة من هذه السلسلة الآمنة. |
| void [Dispose](./dispose/)() override | يحرر جميع الموارد المستخدمة بواسطة الكائن الحالي. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام قواعد C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | محاكاة مقارنة نقطية بنمط C# حيث يُعتبر NaNين متساويين رغم أن وفقًا لـ IEC 60559:1989 لا يساوي NaN أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | محاكاة مقارنة نقطية بنمط C# حيث يُعتبر NaNين متساويين رغم أن وفقًا لـ IEC 60559:1989 لا يساوي NaN أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| **int32_t** [get_Length](./get_length/)() const | يحصل على عدد الأحرف في هذه السلسلة الآمنة. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجعية المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| void [InsertAt](./insertat/)(**int32_t**, char16_t) | يدرج حرفًا في الفهرس المحدد. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموضّح بـ targetType. نظير عامل C# 'is'. |
| **bool** [IsReadOnly](./isreadonly/)() const | يحصل على العلامة التي تشير ما إذا كان هذا الكائن محددًا للقراءة فقط. |
| void [Lock](../../system/object/lock/)() | يطبق عملية القفل في عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| void [MakeReadOnly](./makereadonly/)() | يجعل هذه السلسلة الآمنة للقراءة فقط. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
| [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويمكّن من إنشاء نسخ فرعية. |
| [SecureString](./)\& [operator=](./operator_equal/)(const [SecureString](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويمكّن من إنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| void [RemoveAt](./removeat/)(**int32_t**) | يزيل الحرف في الموضع المحدد. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| [SecureString](./securestring/)() | معلومات RTTI. |
| [SecureString](./securestring/)(const char16_t *, **int32_t**) | منشئ. |
| [SecureString](./securestring/)(const [SecureString](./)\&) |  |
| void [SetAt](./setat/)(**int32_t**, char16_t) | يستبدل الحرف الموجود في الموضع المحدد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n كمؤشر ضعيف (بدلاً من المشترك). يسمح بتبديل المؤشرات في الحاويات إلى وضع الضعف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي أن يستدعى مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي أن يستدعى مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| [String](../../system/string/) [ToUnsecureString](./tounsecurestring/)() const | ينسخ محتويات هذه السلسلة الآمنة إلى كائن [String](../../system/string/) غير آمن. استخدم بحذر. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ فك قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي أن يستدعى مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي أن يستدعى مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |
| [~SecureString](./~securestring/)() | المدمر. |

## انظر أيضًا

* الفئة [IDisposable](../../system/idisposable/)
* النطاق [System::Security](../)
* المكتبة [Aspose.Slides](../../)