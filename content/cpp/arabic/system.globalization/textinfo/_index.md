---
title: TextInfo
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يُعرّف خصائص النص الخاصة بالمحلية. عمليات الضبط مفعَّلة فقط على الكائنات غير القابلة للقراءة فقط. يجب إنشاء كائنات هذه الفئة باستخدام الدالة System::MakeObject() فقط. لا تُنشئ أبدًا نسخة من هذا النوع على المكدس أو باستخدام عامل new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل أو أعطال في التأكيد. دائمًا غلف هذه الفئة في مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 365
url: /ar/system.globalization/textinfo/
---
## فئة TextInfo

يعرّف خصائص النص الخاصة بالمحلية. عمليات الضبط مفعّلة فقط على الكائنات غير القابلة للقراءة فقط. يجب إنشاء كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../../system/makeobject/) فقط. لا تقم أبداً بإنشاء نسخة من هذا النوع على المكدس أو باستخدام عامل new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل أو أعطال في التأكيد. دائمًا غلف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class TextInfo : public System::ICloneable
```

## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | ينشئ نسخة من الكائن الحالي ويعيد مؤشرًا مشتركًا إليه. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override |  |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة نقاط عائمة بأسلوب C# حيث تُعتبر قيمتا NaN متساويتين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة القيم المزدوجة بأسلوب C# حيث تُعتبر قيمتا NaN متساويتين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للاستخدام الداخلي فقط. |
| virtual int [get_ANSICodePage](./get_ansicodepage/)() const | يحصل على صفحة الشيفرة ANSI. |
| [String](../../system/string/) [get_CultureName](./get_culturename/)() const | يحصل على اسم الثقافة. |
| virtual int [get_EBCDICCodePage](./get_ebcdiccodepage/)() const | يحصل على صفحة الشيفرة EBCDIC. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | يتحقق مما إذا كان التنسيق للقراءة فقط. |
| **bool** [get_IsRightToLeft](./get_isrighttoleft/)() const | يتحقق مما إذا كان النص مكتوبًا من اليسار إلى اليمين. |
| int [get_LCID](./get_lcid/)() const | يحصل على معرف المنطقة. |
| virtual [String](../../system/string/) [get_ListSeparator](./get_listseparator/)() const | يحصل على فاصل القائمة. |
| virtual int [get_MacCodePage](./get_maccodepage/)() const | يحصل على صفحة الشيفرة Macintosh. |
| virtual int [get_OEMCodePage](./get_oemcodepage/)() const | يحصل على صفحة الشيفرة OEM. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على هيكل بيانات عداد المراجع المرتبط بالكائن. |
| int [GetHashCode](./gethashcode/)() const override | مماثل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. مماثل للمشغل 'is' في C#. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل عبارة C# lock(). استدعِ مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيء جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيء فعليًا، بل يهيء كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [TextInfo](./)\& [operator=](./operator_equal/)(const [TextInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيء فعليًا، بل يهيء كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| static [TextInfoPtr](../textinfoptr/) [ReadOnly](./readonly/)(const [TextInfoPtr](../textinfoptr/)\&) | يحصل على نسخة للقراءة فقط من الثقافة. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائنًا من نوع القيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدد المراجع المشتركة بالقيمة المحددة. |
| virtual void [set_ListSeparator](./set_listseparator/)([String](../../system/string/)) | يضبط فاصل القائمة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب الـ n'th كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المراجع المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المراجع المشتركة. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل عداد المراجع المشتركة ويعيد قيمته. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
|  [TextInfo](./textinfo/)(const [TextInfo](./)\&) | معلومات RTTI. |
| virtual char_t [ToLower](./tolower/)(char_t) const | يحوِّل الحرف إلى حالة صغيرة. |
| virtual [String](../../system/string/) [ToLower](./tolower/)([String](../../system/string/)) const | يحوِّل السلسلة إلى حالة صغيرة. |
| [String](../../system/string/) [ToString](./tostring/)() const override | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| [String](../../system/string/) [ToTitleCase](./totitlecase/)([String](../../system/string/)) const | يحوّل السلسلة إلى حالة عنوان (باستثناء الاختصارات التي هي بالحروف الكبيرة بالفعل). |
| virtual char_t [ToUpper](./toupper/)(char_t) const | يحوِّل الحرف إلى حالة كبيرة. |
| virtual [String](../../system/string/) [ToUpper](./toupper/)([String](../../system/string/)) const | يحوِّل السلسلة إلى حالة كبيرة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل عبارة C# lock(). استدعِ مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* فئة [ICloneable](../../system/icloneable/)
* مساحة الاسم [System::Globalization](../)
* مكتبة [Aspose.Slides](../../)