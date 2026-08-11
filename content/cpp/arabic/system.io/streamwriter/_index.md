---
title: StreamWriter
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يمثِّل كاتبًا يكتب الأحرف إلى تدفق بايتات. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject(). لا تُنشئ أبدًا نسخة من هذا النوع على المكدس أو باستخدام معامل new، لأن ذلك سيؤدي إلى أخطاء وقت التنفيذ و/أو أعطابات التحقق. احwrap دائمًا هذه الفئة في مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 391
url: /ar/system.io/streamwriter/
---
## StreamWriter الفئة

يمثِّل كاتبًا يَكتب الأحرف إلى تدفق بايتات. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تُنشئ أبداً نسخة من هذا النوع على المكدس أو باستخدام معامل new، لأن ذلك سيؤدي إلى أخطاء زمن التشغيل أو أعطابات في التحقق. احwrap دائمًا هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class StreamWriter : public System::IO::TextWriter
```

## Methods

| Method | Description |
| --- | --- |
| void [Close](./close/)() override | يغلق التدفق ويحرّر الموارد المكتسبة. |
| void [Dispose](./dispose/)() override | يحرّر جميع الموارد المستخدمة بواسطة الكائن الحالي ويغلق التدفق الأساسي. |
| virtual void [Dispose](./dispose/)(**bool**) | يحرّر جميع الموارد المستخدمة بواسطة الكائن الحالي ويغلق التدفق الأساسي. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانساويًا للآخر حتى إذا كان IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة بما فيها NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانساويًا للآخر حتى إذا كان IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة بما فيها NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| void [Flush](./flush/)() override | يفرغ محتوى المخزن المؤقت إلى التدفق الأساسي ثم يفرغ التدفق الأساسي. |
| **bool** [get_AutoFlush](./get_autoflush/)() const | يُعيد قيمة تُشير إلى ما إذا كان [StreamWriter](./) سيُفرغ البيانات إلى التدفق الأساسي في كل مرة يُستدعى فيها الدالة [StreamWriter::Write](./write/). |
| [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() const | يُعيد مؤشرًا مشتركًا إلى كائن يُمثِّل التدفق الأساسي. |
| [EncodingPtr](../../system/encodingptr/) [get_Encoding](./get_encoding/)() override | يُعيد الترميز المُستخدَم حاليًا. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](../textwriter/get_formatprovider/)() const | يُعيد الكائن [IFormatProvider](../../system/iformatprovider/) المُستخدَم حاليًا. |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](../textwriter/get_formatprovider/)() | يُعيد الكائن [IFormatProvider](../../system/iformatprovider/) المُستخدَم حاليًا. |
| virtual [System::String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() const | يُعيد سلسلة محدد سطر. |
| [String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() | يُعيد سلسلة محدد سطر. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصَّصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. نظير معامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | يُنفّذ بيان القفل C# lock(). استدعِ مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصَّصة. |
|  [Object](../../system/object/object/)() | يُنشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | مُنشئ نسخ. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويُمكّن بناء نسخ الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | معامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويُمكّن بناء نسخ الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن نوع قيم مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_AutoFlush](./set_autoflush/)(**bool**) | يُعيد قيمة تُحدِّد ما إذا كان [StreamWriter](./) سيُفرغ البيانات إلى التدفق الأساسي في كل مرة يُستدعى فيها الدالة [StreamWriter::Write](./write/). |
| virtual void [set_NewLine](../textwriter/set_newline/)(const [System::String](../../system/string/)\&) | يضع سلسلة محدد سطر. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضع المؤشر الضعيف للمعامل القالب رقم n بدلاً من المشترك. يسمح بتحويل المؤشرات في الحاويات إلى وضعية ضعيفة. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل عداد المرجع المشترك ويُعيده. لا يجب استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | يُنشئ نسخة من كائن [StreamWriter](./) يكتب الأحرف إلى التدفق الأساسي المحدد باستخدام ترميز UTF-8 ومخزن مؤقت بحجم افتراضي 1024 بايت. |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | يُنشئ نسخة من كائن [StreamWriter](./) يكتب الأحرف إلى التدفق الأساسي المحدد باستخدام الترميز المحدد ومخزن مؤقت بحجم افتراضي 1024 بايت. |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, int, **bool**) | يُنشئ نسخة من كائن [StreamWriter](./) يكتب الأحرف إلى التدفق الأساسي المحدد باستخدام الترميز المحدد ومخزن مؤقت بالحجم المحدد. يُحدِّد معامل ما إذا كان يجب إغلاق التدفق الأساسي عند التخلص من كائن [StreamWriter](./). |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&) | يُنشئ نسخة من كائن [StreamWriter](./) يكتب الأحرف إلى الملف المحدد باستخدام ترميز UTF-8 ومخزن مؤقت بحجم افتراضي 1024 بايت. |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&, **bool**, const [EncodingPtr](../../system/encodingptr/)\&) | يُنشئ نسخة من كائن [StreamWriter](./) يكتب الأحرف إلى الملف المحدد باستخدام الترميز المحدد ومخزن مؤقت بحجم افتراضي 1024 بايت. يُحدِّد معامل ما إذا كان يجب إلحاق البيانات بالملف أو استبدال المحتوى. |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&, **bool**, const [EncodingPtr](../../system/encodingptr/)\&, int) | يُنشئ نسخة من كائن [StreamWriter](./) يكتب الأحرف إلى الملف المحدد باستخدام الترميز المحدد وحجم المخزن المؤقت. يُحدِّد معامل ما إذا كان يجب إلحاق البيانات بالملف أو استبدال المحتوى. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصَّصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يُنفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يُنفّذ بيان فك القفل C# lock(). استدعِ مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا يجب استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا يجب استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| void [Write](./write/)(char_t) override | يكتب الحرف المحدد إلى التدفق. |
| void [Write](./write/)(const [String](../../system/string/)\&) override | يكتب السلسلة المحددة إلى التدفق. |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) override | يكتب تمثيل السلسلة للكائن المحدد إلى التدفق. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) override | يكتب جميع الأحرف من المصفوفة المحددة إلى التدفق. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | يكتب النطاق الفرعي المحدد من أحرف UTF-16 من المصفوفة المحددة إلى التدفق. |
| void [Write](./write/)(const char_t *) override | يكتب السلسلة C المحددة إلى التدفق. |
| void [Write](./write/)(const [System::SharedPtr](../../system/sharedptr/)\<T\>\&) | يكتب تمثيل السلسلة للكائن المحدد إلى التدفق. |
| virtual void [Write](../textwriter/write/)(**bool**) | يكتب تمثيل السلسلة للقيمة المنطقية المحددة إلى التدفق. |
| virtual void [Write](../textwriter/write/)([Decimal](../../system/decimal/)) | يكتب تمثيل السلسلة لكائن [Decimal](../../system/decimal/) المحدد إلى التدفق. |
| virtual void [Write](../textwriter/write/)(**double**) | يكتب تمثيل السلسلة للقيمة العائمة ذات الدقة المضاعفة المحددة إلى التدفق. |
| virtual void [Write](../textwriter/write/)(int) | يكتب تمثيل السلسلة للقيمة الصحيحة 32-بت المحددة إلى التدفق. |
| virtual void [Write](../textwriter/write/)(**int64_t**) | يكتب تمثيل السلسلة للقيمة الصحيحة 64-بت المحددة إلى التدفق. |
| virtual void [Write](../textwriter/write/)(**float**) | يكتب تمثيل السلسلة للقيمة العائمة ذات الدقة المفردة المحددة إلى التدفق. |
| virtual void [Write](../textwriter/write/)(**uint32_t**) | يكتب تمثيل السلسلة للقيمة الصحيحة غير الموقعة 32-بت المحددة إلى التدفق. |
| virtual void [Write](../textwriter/write/)(**uint64_t**) | يكتب تمثيل السلسلة للقيمة الصحيحة غير الموقعة 64-بت المحددة إلى التدفق. |
| virtual void [Write](../textwriter/write/)(const [TypeInfo](../../system/typeinfo/)\&) | يكتب تمثيل السلسلة لكائن [TypeInfo](../../system/typeinfo/) المحدد إلى التدفق. |
| void [Write](../textwriter/write/)(const [String](../../system/string/)\&, const TArgs\&...) | يكتب القيم المحددة بصيغة التنسيق المحدد إلى التدفق. |
| void [WriteLine](./writeline/)() override | يكتب أحرف محدد السطر إلى التدفق. |
| void [WriteLine](./writeline/)(const [String](../../system/string/)\&) override | يكتب السلسلة المحددة متبوعةً بأحرف محدد السطر إلى التدفق. |
| void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) override | يكتب تمثيل السلسلة للكائن المحدد متبوعًا بأحرف محدد السطر إلى التدفق. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) override | يكتب جميع الأحرف من المصفوفة المحددة متبوعةً بأحرف محدد السطر إلى التدفق. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | يكتب النطاق الفرعي المحدد من أحرف UTF-16 من المصفوفة المحددة متبوعًا بأحرف محدد السطر إلى التدفق. |
| void [WriteLine](./writeline/)(const char_t *) override | يكتب السلسلة C المحددة متبوعةً بأحرف محدد السطر إلى التدفق. |
| void [WriteLine](./writeline/)(const [System::SharedPtr](../../system/sharedptr/)\<T\>\&) | يكتب تمثيل السلسلة للكائن المحدد متبوعًا بأحرف محدد السطر إلى التدفق. |
| virtual void [WriteLine](../textwriter/writeline/)(**bool**) | يكتب تمثيل السلسلة للقيمة المنطقية المحددة متبوعًا بأحرف محدد السطر إلى التدفق. |
| virtual void [WriteLine](../textwriter/writeline/)(char_t) | يكتب الحرف المحدد متبوعًا بأحرف محدد السطر إلى التدفق. |
| virtual void [WriteLine](../textwriter/writeline/)([Decimal](../../system/decimal/)) | يكتب تمثيل السلسلة لكائن [Decimal](../../system/decimal/) المحدد متبوعًا بأحرف محدد السطر إلى التدفق. |
| virtual void [WriteLine](../textwriter/writeline/)(**double**) | يكتب تمثيل السلسلة للقيمة العائمة ذات الدقة المضاعفة المحددة متبوعةً بأحرف محدد السطر إلى التدفق. |
| virtual void [WriteLine](../textwriter/writeline/)(int) | يكتب تمثيل السلسلة للقيمة الصحيحة 32-بت المحددة متبوعةً بأحرف محدد السطر إلى التدفق. |
| virtual void [WriteLine](../textwriter/writeline/)(**int64_t**) | يكتب تمثيل السلسلة للقيمة الصحيحة 64-بت المحددة متبوعةً بأحرف محدد السطر إلى التدفق. |
| virtual void [WriteLine](../textwriter/writeline/)(**float**) | يكتب تمثيل السلسلة للقيمة العائمة ذات الدقة المفردة المحددة متبوعةً بأحرف محدد السطر إلى التدفق. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint32_t**) | يكتب تمثيل السلسلة للقيمة الصحيحة غير الموقعة 32-بت المحددة متبوعةً بأحرف محدد السطر إلى التدفق. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint64_t**) | يكتب تمثيل السلسلة للقيمة الصحيحة غير الموقعة 64-بت المحددة متبوعةً بأحرف محدد السطر إلى التدفق. |
| virtual void [WriteLine](../textwriter/writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | يكتب تمثيل السلسلة لكائن [TypeInfo](../../system/typeinfo/) المحدد متبوعًا بأحرف محدد السطر إلى التدفق. |
| void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | يكتب القيم المحددة بصيغة التنسيق المحدد متبوعةً بأحرف محدد السطر إلى التدفق. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يُحرّر جميع هياكل البيانات الداخلية. |
|  [~StreamWriter](./~streamwriter/)() | المُدمِّر. |
| virtual  [~TextWriter](../textwriter/~textwriter/)() | المُدمِّر. |

## انظر أيضًا

* الفئة [TextWriter](../textwriter/)
* النطاق [System::IO](../)
* المكتبة [Aspose.Slides](../../)