---
title: StringBuilder
second_title: مرجع API لـ Aspose.Slides لـ C++
description: "مخزن لتجميع أجزاء السلسلة جزءًا بآخر. يمكن تخصيص هذا النوع إما على المكدس كنوع قيمة أو على الكومة باستخدام الدالة System::MakeObject() function. بمجرد تخصيص الكائن، لا تخلط بين هاتين الحالتين: وجود SmartPtr pointers onto stack-allocated objects is strictly prohibited."
type: docs
weight: 326
url: /ar/system.text/stringbuilder/
---
## StringBuilder فئة

[Buffer](../../system/buffer/) لتجميع أجزاء السلسلة جزءً بجزء. يمكن تخصيص هذا النوع إما على المكدس كنوع قيمة أو على الكومة باستخدام الدالة [System::MakeObject()](../../system/makeobject/). بمجرد تخصيص الكائن، لا تخلط بين هاتين الحالتين: وجود مؤشرات [SmartPtr](../../system/smartptr/) إلى كائنات مخصصة على المكدس محظور تمامًا.

```cpp
class StringBuilder : public System::Object
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [StringBuilder](./) * [Append](./append/)(char_t) | يضيف حرفًا إلى المُنشئ. |
| [StringBuilder](./) * [Append](./append/)(char_t, int) | يضيف أحرفًا إلى المُنشئ. |
| [StringBuilder](./) * [Append](./append/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | يضيف مصفوفة أحرف إلى المُنشئ. |
| [StringBuilder](./) * [Append](./append/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | يضيف جزءًا من مصفوفة الأحرف إلى المُنشئ. |
| [StringBuilder](./) * [Append](./append/)(const [String](../../system/string/)\&) | يضيف سلسلة إلى المُنشئ. |
| [StringBuilder](./) * [Append](./append/)(const [String](../../system/string/)\&, int, int) | يضيف جزءًا من السلسلة إلى المُنشئ. |
| [StringBuilder](./) * [Append](./append/)(const [SharedPtr](../../system/sharedptr/)\<T\>\&) | يضيف تمثيل السلسلة الخاص بالكائن إلى المُنشئ. |
| [StringBuilder](./) * [Append](./append/)(const [SharedPtr](../../system/sharedptr/)\<[StringBuilder](./)\>\&) | يضيف محتوى المُنشئ إلى المُنشئ. |
| [StringBuilder](./) * [Append](./append/)(**float**) | يضيف قيمة نقطة عائمة إلى المُنشئ. |
| [StringBuilder](./) * [Append](./append/)(**double**) | يضيف قيمة مزدوجة إلى المُنشئ. |
| [StringBuilder](./) * [Append](./append/)(int) | يضيف قيمة عددية صحيحة إلى المُنشئ. |
| std::enable_if\<std::is_arithmetic\<T\>::value, [StringBuilder](./) *\>::type [Append](./append/)(T) | يضيف قيمة حسابية إلى المُنشئ. |
| std::enable_if\<std::is_enum\<E\>::value, [StringBuilder](./) *\>::type [Append](./append/)(E) | يضيف تمثيل سلسلة لقيمة التعداد إلى المُنشئ. |
| [StringBuilder](./) * [AppendFormat](./appendformat/)(const [String](../../system/string/)\&, const TArgs\&...) | يضيف سلسلة مُنسقة إلى المُنشئ. |
| [StringBuilder](./) * [AppendFormat](./appendformat/)(const [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\>\&, const [String](../../system/string/)\&, const TArgs\&...) | يضيف سلسلة مُنسقة إلى المُنشئ. |
| [StringBuilder](./) * [AppendLine](./appendline/)() | يضيف حرف سطر جديد إلى المُنشئ. |
| [StringBuilder](./) * [AppendLine](./appendline/)(const [String](../../system/string/)\&) | يضيف سلسلة متبوعة بحرف سطر جديد إلى المُنشئ. |
| [StringBuilder](./) * [Clear](./clear/)() | يزيل جميع الأحرف من المُنشئ. |
| void [CopyTo](./copyto/)(int, [System::ArrayPtr](../../system/arrayptr/)\<char_t\> const\&, int, int) | ينسخ بيانات المُنشئ إلى مواضع المصفوفة الحالية. |
| **int32_t** [EnsureCapacity](./ensurecapacity/)(**int32_t**) | يضمن أن سعة هذا المثال من [System.Text.StringBuilder](./) لا تقل عن القيمة المحددة. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام سلوك C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يقلد مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaNّان متساويتين رغم أن IEC 60559:1989 تنص على عدم مساواة NaN بأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يقلد مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaNّان متساويتين رغم أن IEC 60559:1989 تنص على عدم مساواة NaN بأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| int [get_Capacity](./get_capacity/)() const | يسترجع السعة الحالية لباني السلسلة. |
| int [get_Length](./get_length/)() const | يسترجع طول السلسلة الحالية في المُنشئ. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يسترجع بنية عدّاد الإشارة المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يسترجع النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| char_t [idx_get](./idx_get/)(int) const | يسترجع الحرف في الموضع المحدد. |
| void [idx_set](./idx_set/)(int, char_t) | يحدد الحرف في الموضع المحدد. |
| [StringBuilder](./) * [Insert](./insert/)(int, const [String](../../system/string/)\&) | يدرج سلسلة في موضع ثابت بالمُنشئ. |
| [StringBuilder](./) * [Insert](./insert/)(**int32_t**, const [String](../../system/string/)\&, **int32_t**) | يدرج سلسلة متكررة في موضع ثابت بالمُنشئ. |
| [StringBuilder](./) * [Insert](./insert/)(int, char_t) | يدرج حرف في موضع ثابت بالمُنشئ. |
| [StringBuilder](./) * [Insert](./insert/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | يدرج أحرف في موضع ثابت بالمُنشئ. |
| std::enable_if\<std::is_arithmetic\<T\>::value, [StringBuilder](./) *\>::type [Insert](./insert/)(int, T) | يدرج قيمة في موضع ثابت بالمُنشئ. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. نظير عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ تعليمة C# lock() لتأمين. يُستدعى مباشرة أو يستخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ الكائن. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، بل يهيء كائنًا جديدًا ويمكّن النسخ للأنواع المشتقة. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيء كائنًا جديدًا ويمكّن النسخ للأنواع المشتقة. |
| char_t [operator[]](./operator[]/)(int) const | يسترجع الحرف في الموضع المحدد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بواسطة المرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بواسطة المرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالـ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصصية [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة والـ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصصية [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| [StringBuilder](./) * [Remove](./remove/)(int, int) | يزيل جزءًا من المُنشئ. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد الإشارة المشتركة بالقيمة المحددة. |
| [StringBuilder](./) * [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | يستبدل جزءًا من النص عبر المُنشئ. |
| [StringBuilder](./) * [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) | يستبدل جزءًا من النص عبر نطاق المُنشئ. |
| [StringBuilder](./) * [Replace](./replace/)(char_t, char_t) | يستبدل حرفًا عبر المُنشئ. |
| [StringBuilder](./) * [Replace](./replace/)(char_t, char_t, int, int) | يستبدل حرفًا عبر نطاق المُنشئ. |
| void [set_Capacity](./set_capacity/)(int) | يحدد السعة الحالية لباني السلسلة. |
| void [set_Length](./set_length/)(int) | يختصر أو يطيل باني السلسلة إلى الطول المحدد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط ال template الثامن إلى مؤشر ضعيف (بدلاً من مشترك). يسمح بتبديل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يسترجع القيمة الحالية لعداد الإشارة المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد الإشارة المشتركة. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد الإشارة المشتركة. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
|  [StringBuilder](./stringbuilder/)() | باني. |
|  [StringBuilder](./stringbuilder/)(int) | باني. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&) | باني. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&, int) | باني. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&, int, int, int) | باني. |
| [String](../../system/string/) [ToString](./tostring/)() const override | يسترجع السلسلة الحالية في المُنشئ. |
| [String](../../system/string/) [ToString](./tostring/)(int, int) const | يسترجع جزءًا من السلسلة الحالية في المُنشئ. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يزيل تأمين تعليمة C# lock(). يُستدعى مباشرة أو يستخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |
|  [~StringBuilder](./~stringbuilder/)() | المدمر. |

## انظر أيضًا

* الفئة [Object](../../system/object/)
* النطاق [System::Text](../)
* المكتبة [Aspose.Slides](../../)