---
title: ConsoleOutput
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يمثل تدفق الإخراج القياسي. يجب إنشاء كائنات هذه الفئة باستخدام الدالة System::MakeObject() فقط. لا تقم أبداً بإنشاء نسخة من هذا النوع على المكدس أو باستخدام عامل new، حيث سيتسبب ذلك في أخطاء وقت التشغيل و/أو أخطاء التأكيد. احرص دائماً على تغليف هذه الفئة في مؤشر System::SmartPtr واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 209
url: /ar/system/consoleoutput/
---
## فئة ConsoleOutput

يمثل تدفق الإخراج القياسي. يجب إنشاء كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../makeobject/) فقط. لا تقم أبداً بإنشاء نسخة من هذا النوع على المكدس أو باستخدام عامل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل و/أو أعطال التأكيد. احرص دائماً على تغليف هذه الفئة في مؤشر [System::SmartPtr](../smartptr/) واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class ConsoleOutput : public System::IO::TextWriter
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual void [Close](../../system.io/textwriter/close/)() | يغلق التدفق ويحرّر الموارد المكتسبة. |
| void [Dispose](../../system.io/textwriter/dispose/)() override | يطلق سراح جميع الموارد المستخدمة بواسطة الكائن الحالي ويغلق التدفق الأساسي. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة المزدوجة بأسلوب C# حيث يُعتبر NaNانان متساويين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | للاستخدام الداخلي فقط. |
| virtual void [Flush](../../system.io/textwriter/flush/)() | يفرغ محتوى المخزن المؤقت إلى التدفق الأساسي. |
| [SharedPtr](../sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() override | دائمًا ما يُعيد ترميز ASCII. |
| virtual [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\> [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() const | يعيد الكائن [IFormatProvider](../iformatprovider/) المستخدم حاليًا. |
| [IFormatProviderPtr](../iformatproviderptr/) [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() | يعيد الكائن [IFormatProvider](../iformatprovider/) المستخدم حاليًا. |
| virtual [System::String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() const | يعيد سلسلة فاصل السطر. |
| [String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() | يعيد سلسلة فاصل السطر. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../object/gettype/). |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثيلاً للنوع الوصفي بواسطة targetType. نظير عامل C# 'is'. |
| void [Lock](../object/lock/)() | ينفذ قفل تعبير C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../object/object/)([Object](../object/) const\&) | منشئ نسخ. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بنسخ بناء الفئات الفرعية. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بنسخ بناء الفئات الفرعية. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | تخصيص [Object::ReferenceEquals](../object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [set_NewLine](../../system.io/textwriter/set_newline/)(const [System::String](../string/)\&) | يضبط سلسلة فاصل السطر. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | نظير طريقة C# [Object.ToString()](../object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | ينفذ بنية C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | ينفذ فك قفل تعبير C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [Write](./write/)(**bool**) override | يُخرج تمثيل السلسلة للقيمة bool المحددة إلى تدفق الإخراج الممثَّل بالكائن الحالي. |
| void [Write](./write/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | يُخرج تمثيل السلسلة للكائن المحدد إلى تدفق الإخراج الممثَّل بالكائن الحالي. |
| void [Write](./write/)(char_t) override | يُخرج قيمة الحرف المحدد إلى تدفق الإخراج الممثَّل بالكائن الحالي. |
| void [Write](./write/)([Decimal](../decimal/)) override | يُخرج تمثيل السلسلة لقيمة [Decimal](../decimal/) إلى تدفق الإخراج الممثَّل بالكائن الحالي. |
| void [Write](./write/)(**double**) override | يُخرج تمثيل السلسلة للقيمة النقطة العائمة بدقة مزدوجة إلى تدفق الإخراج الممثَّل بالكائن الحالي. |
| void [Write](./write/)(**int32_t**) override | يُخرج تمثيل السلسلة لقيمة عدد صحيح 32-بت إلى تدفق الإخراج الممثَّل بالكائن الحالي. |
| void [Write](./write/)(**int64_t**) override | يُخرج تمثيل السلسلة لقيمة عدد صحيح 64-بت إلى تدفق الإخراج الممثَّل بالكائن الحالي. |
| void [Write](./write/)(**float**) override | يُخرج تمثيل السلسلة لقيمة النقطة العائمة ذات دقة مفردة إلى تدفق الإخراج الممثَّل بالكائن الحالي. |
| void [Write](./write/)(const [String](../string/)\&) override | يُخرج كائن السلسلة المحدد إلى تدفق الإخراج الممثَّل بالكائن الحالي. |
| void [Write](./write/)(**uint32_t**) override | يُخرج تمثيل السلسلة لقيمة عدد صحيح غير موقع 32-بت إلى تدفق الإخراج الممثَّل بالكائن الحالي. |
| void [Write](./write/)(**uint64_t**) override | يُخرج تمثيل السلسلة لقيمة عدد صحيح غير موقع 64-بت إلى تدفق الإخراج الممثَّل بالكائن الحالي. |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | يُخرج تمثيل السلسلة للمصفوفة الحرفية المحددة إلى تدفق الإخراج الممثَّل بالكائن الحالي. |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | يُخرج تمثيل السلسلة لنطاق من القيم في المصفوفة الحرفية المحددة إلى تدفق الإخراج الممثَّل بالكائن الحالي. |
| void [Write](./write/)(const char_t *) override | يُخرج السلسلة c المحددة إلى تدفق الإخراج الممثَّل بالكائن الحالي. |
| void [Write](./write/)(const [TypeInfo](../typeinfo/)\&) override | يُخرج تمثيل السلسلة للكائن [TypeInfo](../typeinfo/) المحدد إلى تدفق الإخراج الممثَّل بالكائن الحالي. |
| void [Write](./write/)(const char *) |  |
| virtual void [Write](../../system.io/textwriter/write/)(int) | يكتب تمثيل السلسلة للقيمة عدد صحيح 32-بت المحددة إلى التدفق. |
| void [Write](../../system.io/textwriter/write/)(const [String](../string/)\&, const TArgs\&...) | يكتب القيم المحددة مُنسَّقة وفقًا للتنسيق المحدد إلى التدفق. |
| void [WriteLine](./writeline/)() override | يُخرج فاصل السطر الحالي إلى تدفق الإخراج الممثَّل بالكائن الحالي. |
| void [WriteLine](./writeline/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | يُخرج تمثيل السلسلة للكائن المحدد متبوعًا بفاصل السطر الحالي إلى تدفق الإخراج الممثَّل بالكائن الحالي. |
| void [WriteLine](./writeline/)(**bool**) override | يُخرج تمثيل السلسلة للقيمة bool المحددة متبوعًا بفاصل السطر الحالي إلى تدفق الإخراج الممثَّل بالكائن الحالي. |
| void [WriteLine](./writeline/)(char_t) override | يُخرج قيمة الحرف المحددة متبوعة بفاصل السطر الحالي إلى تدفق الإخراج الممثَّل بالكائن الحالي. |
| void [WriteLine](./writeline/)([Decimal](../decimal/)) override | يُخرج تمثيل السلسلة لقيمة [Decimal](../decimal/) متبوعًا بفاصل السطر الحالي إلى تدفق الإخراج الممثَّل بالكائن الحالي. |
| void [WriteLine](./writeline/)(**double**) override | يُخرج تمثيل السلسلة للقيمة النقطة العائمة بدقة مزدوجة متبوعًا بفاصل السطر الحالي إلى تدفق الإخراج الممثَّل بالكائن الحالي. |
| void [WriteLine](./writeline/)(int) override | يُخرج تمثيل السلسلة لقيمة عدد صحيح 32-بت متبوعًا بفاصل السطر الحالي إلى تدفق الإخراج الممثَّل بالكائن الحالي. |
| void [WriteLine](./writeline/)(**int64_t**) override | يُخرج تمثيل السلسلة لقيمة عدد صحيح 64-بت متبوعًا بفاصل السطر الحالي إلى تدفق الإخراج الممثَّل بالكائن الحالي. |
| void [WriteLine](./writeline/)(**float**) override | يُخرج تمثيل السلسلة لقيمة النقطة العائمة ذات دقة مفردة متبوعًا بفاصل السطر الحالي إلى تدفق الإخراج الممثَّل بالكائن الحالي. |
| void [WriteLine](./writeline/)(const [String](../string/)\&) override | يُخرج كائن السلسلة المحدد متبوعًا بفاصل السطر الحالي إلى تدفق الإخراج الممثَّل بالكائن الحالي. |
| void [WriteLine](./writeline/)(**uint32_t**) override | يُخرج تمثيل السلسلة لقيمة عدد صحيح غير موقع 32-بت متبوعًا بفاصل السطر الحالي إلى تدفق الإخراج الممثَّل بالكائن الحالي. |
| void [WriteLine](./writeline/)(**uint64_t**) override | يُخرج تمثيل السلسلة لقيمة عدد صحيح غير موقع 64-بت متبوعًا بفاصل السطر الحالي إلى تدفق الإخراج الممثَّل بالكائن الحالي. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | يُخرج تمثيل السلسلة للمصفوفة الحرفية المحددة متبوعًا بفاصل السطر الحالي إلى تدفق الإخراج الممثَّل بالكائن الحالي. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | يُخرج تمثيل السلسلة لنطاق من القيم في المصفوة الحرفية المحددة متبوعًا بفاصل السطر الحالي إلى تدفق الإخراج الممثَّل بالكائن الحالي. |
| void [WriteLine](./writeline/)(const char_t *) override | يُخرج السلسلة c المحددة متبوعة بفاصل السطر الحالي إلى تدفق الإخراج الممثَّل بالكائن الحالي. |
| void [WriteLine](./writeline/)(const [TypeInfo](../typeinfo/)\&) override | يُخرج تمثيل السلسلة للكائن [TypeInfo](../typeinfo/) المحدد متبوعًا بفاصل السطر الحالي إلى تدفق الإخراج الممثَّل بالكائن الحالي. |
| void [WriteLine](./writeline/)(const char *) |  |
| void [WriteLine](../../system.io/textwriter/writeline/)(const [String](../string/)\&, const TArgs\&...) | يكتب القيم المحددة مُنسَّقة وفقًا للتنسيق المحدد متبوعة بأحرف إنهاء السطر إلى التدفق. |
| virtual  [~Object](../object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |
| virtual  [~TextWriter](../../system.io/textwriter/~textwriter/)() | المُدمّر. |

## انظر أيضًا

* الفئة [TextWriter](../../system.io/textwriter/)
* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)