---
title: ProtectionManager
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة C++
description: إدارة حماية كلمة المرور للعرض التقديمي.
type: docs
weight: 4915
url: /ar/aspose.slides/protectionmanager/
---
## فئة ProtectionManager

[Presentation](../presentation/) إدارة حماية كلمة المرور.

```cpp
class ProtectionManager : public Aspose::Slides::IProtectionManager
```

## الطرق

| Method | Description |
| --- | --- |
| **bool** [CheckWriteProtection](./checkwriteprotection/)([System::String](../../system/string/)) override | يحدد ما إذا كان العرض محمياً بكلمة مرور للتعديل. |
| void [Encrypt](./encrypt/)([System::String](../../system/string/)) override | يقوم بتشفير [Presentation](../presentation/) باستخدام كلمة المرور المحددة. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | تحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُ considered NaNين متساويتين رغم أن معيار IEC 60559:1989 يحدد أن NaN غير مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | تحاكي مقارنة النقطة العائمة مزدوجة الدقة بأسلوب C# حيث تُ considered NaNين متساويتين رغم أن معيار IEC 60559:1989 يحدد أن NaN غير مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| **bool** [get_EncryptDocumentProperties](./get_encryptdocumentproperties/)() override | هذه الخاصية ذات معنى إذا كان العرض محمياً بكلمة مرور. إذا كان True فإن خصائص المستند مشفرة في ملف العرض. إذا كان False فإن خصائص المستند عامة بينما يكون العرض مشفراً. قراءة **bool**. |
| [System::String](../../system/string/) [get_EncryptionPassword](./get_encryptionpassword/)() override | يحصل على كلمة المرور المستخدمة لتشفير العرض. للقراءة فقط [System::String](../../system/string/). |
| **bool** [get_IsEncrypted](./get_isencrypted/)() override | يحصل على قيمة تشير إلى ما إذا كانت هذه النسخة مشفرة. **bool** للقراءة فقط. |
| **bool** [get_IsOnlyDocumentPropertiesLoaded](./get_isonlydocumentpropertiesloaded/)() override | هذه الخاصية ذات معنى إذا كان ملف العرض محمياً بكلمة مرور وخصائص المستند لهذا الملف عامة. قيمة True تعني أن خصائص المستند فقط يتم تحميلها من ملف عرض مشفر دون استخدام كلمة مرور. قيمة False تعني أن العرض المشفر بالكامل يتم تحميله باستخدام كلمة مرور صحيحة، وليس فقط خصائص المستند. إذا لم يكن العرض مشفرًا فإن قيمة الخاصية تكون دائمًا False. إذا لم تكن خصائص المستند لملف مشفر عامة فإن قيمة الخاصية تكون دائمًا False. إذا كان Presentation.EncryptDocumentProperties يساوي True فإن قيمة الخاصية IsOnlyDocumentPropertiesLoaded تكون دائمًا False. **bool** للقراءة فقط. |
| **bool** [get_IsWriteProtected](./get_iswriteprotected/)() override | يحصل على قيمة تشير إلى ما إذا كان هذا العرض محمياً من الكتابة. **bool** للقراءة فقط. |
| **bool** [get_ReadOnlyRecommended](./get_readonlyrecommended/)() override | يحصل على توصية للقراءة فقط. قراءة **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نسخة مماثلة لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). تمكّن من تجزئة الكائنات المخصّصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نسخة مماثلة لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. نسخة مماثلة لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل جملة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نسخة مماثلة لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). تمكّن من استنساخ الأنماط المخصّصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيّء جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة النسخ. لا ينسخ شيئًا فعليًا، بل يهيّء كائنًا جديدًا ويمكّن من نسخ بناء الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيّء كائنًا جديدًا ويمكّن من نسخ بناء الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن بالمرجع كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدد المراجع المشتركة بقيمة محددة. |
| void [RemoveEncryption](./removeencryption/)() override | يزيل التشفير. |
| void [RemoveWriteProtection](./removewriteprotection/)() override | يزيل حماية الكتابة لهذا العرض. |
| void [set_EncryptDocumentProperties](./set_encryptdocumentproperties/)(**bool**) override | هذه الخاصية ذات معنى إذا كان العرض محمياً بكلمة مرور. إذا كان True فإن خصائص المستند مشفرة في ملف العرض. إذا كان False فإن خصائص المستدم عامة بينما يكون العرض مشفراً. كتابة **bool**. |
| void [set_ReadOnlyRecommended](./set_readonlyrecommended/)(**bool**) override | يضبط توصية للقراءة فقط. كتابة **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الحجة النموذجية رقم n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل الإشارات في الحاويات إلى وضع ضعيف. |
| void [SetWriteProtection](./setwriteprotection/)([System::String](../../system/string/)) override | يضبط حماية الكتابة لهذا العرض باستخدام كلمة المرور المحددة. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المراجع المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدد المراجع المشتركة. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عدد المراجع المشتركة. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نسخة مماثلة لطريقة C# [Object.ToString()](../../system/object/tostring/). تمكّن من تحويل الكائنات المخصّصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل جملة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدد المراجع الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عدد المراجع الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استعم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* فئة [IProtectionManager](../iprotectionmanager/)
* مساحة الاسم [Aspose::Slides](../)
* المكتبة [Aspose.Slides](../../)