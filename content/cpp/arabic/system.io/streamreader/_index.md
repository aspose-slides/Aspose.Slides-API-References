---
title: StreamReader
second_title: مرجع API Aspose.Slides للـ C++
description: "يمثل قارئًا يقرأ الأحرف من تدفق بايت. يجب إنشاء كائنات هذه الفئة باستخدام الدالة System::MakeObject() فقط. لا تقم أبدًا بإنشاء نسخة من هذا النوع على المكدس أو باستخدام العامل new، لأن ذلك سيسبب أخطاءً في وقت التشغيل و/أو أعطالًا في التأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر System::SmartPtr واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 378
url: /ar/system.io/streamreader/
---
## فئة StreamReader

يمثل قارئًا يقرأ الأحرف من تدفق بايت. يجب إنشاء كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../../system/makeobject/) فقط. لا تقم أبدًا بإنشاء نسخة من هذا النوع على المكدس أو باستخدام العامل new، لأن ذلك سيسبب أخطاءً في وقت التنفيذ و/أو أعطالًا في التأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class StreamReader : public System::IO::TextReader
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| void [Close](./close/)() override | يغلق التدفقات الحالية والضمنية. |
| virtual void [Dispose](./dispose/)(**bool**) | يحرر جميع الموارد المستخدمة بواسطة الكائن الحالي ويغلق التدفق الضمني. |
| void [Dispose](./dispose/)() override | يحرر جميع الموارد المستخدمة بواسطة الكائن الحالي ويغلق التدفق الضمني. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام سلوك C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بنمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بنمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث يُعامل NaNانين على أنهما متساويان رغم أن وفقًا لـ IEC 60559:1989 لا يكون NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث يُعامل NaNانين على أنهما متساويان رغم أن وفقًا لـ IEC 60559:1989 لا يكون NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() const | يعيد مؤشرًا مشتركًا إلى كائن يمثل التدفق الضمني. |
| [EncodingPtr](../../system/encodingptr/) [get_CurrentEncoding](./get_currentencoding/)() | يعيد الترميز المستخدم حاليًا. |
| **bool** [get_EndOfStream](./get_endofstream/)() | يعيد قيمة تشير إلى ما إذا تم الوصول إلى نهاية التدفق. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجعية المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تماثل طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تماثل نداء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. تماثل عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | يطبق قفل بيان C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تماثل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| int [Peek](./peek/)() override | يقرا حرفًا واحدًا من التدفق دون تغيير مؤشر القراءة في التدفق. |
| int [Read](./read/)() override | يقرا حرفًا واحدًا من التدفق. |
| int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) override | يقرأ عدد الأحرف المحدد من التدفق، يحولها إلى ترميز UTF-16 ويكتب الأحرف الناتجة بصيغة UTF-16 في مصفوفة الأحرف المحددة بدءًا من الموضع المحدد. |
| virtual int [ReadBlock](../textreader/readblock/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | يقرأ الحد الأقصى المحدد من الأحرف من القارئ النصي الحالي ويكتب البيانات إلى مخزن مؤقت، بدءًا من الفهرس المحدد. |
| [String](../../system/string/) [ReadLine](./readline/)() override | يقرأ الأحرف من التدفق حتى نهاية السطر الحالي. |
| [String](../../system/string/) [ReadToEnd](./readtoend/)() override | يقرأ الأحرف من التدفق حتى نهاية التدفق. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجعية المشتركة بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي رقم n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتبديل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجعية المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجعية المشتركة. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجعية المشتركة. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | ينشئ نسخة من كائن [StreamReader](./) الذي يقرأ الأحرف من التدفق الضمني المحدد باستخدام ترميز UTF-8 ومخزن بحجم افتراضي 1024 بايت. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **bool**) | ينشئ نسخة من كائن [StreamReader](./) الذي يقرأ الأحرف من التدفق الضمني المحدد باستخدام ترميز UTF-8 ومخزن بحجم افتراضي 1024 بايت. يحدد معامل ما إذا كان يجب تمكين اكتشاف علامة ترتيب البايت. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | ينشئ نسخة من كائن [StreamReader](./) الذي يقرأ الأحرف من التدفق الضمني المحدد باستخدام الترميز المحدد ومخزن بحجم افتراضي 1024 بايت. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | ينشئ نسخة من كائن [StreamReader](./) الذي يقرأ الأحرف من التدفق الضمني المحدد باستخدام الترميز المحدد ومخزن بحجم افتراضي 1024 بايت. يحدد معامل ما إذا كان يجب تمكين اكتشاف علامة ترتيب البايت. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**, int) | ينشئ نسخة من كائن [StreamReader](./) الذي يقرأ الأحرف من التدفق الضمني المحدد باستخدام الترميز المحدد ومخزن بالحجم المحدد. يحدد معامل ما إذا كان يجب تمكين اكتشاف علامة ترتيب البايت. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&) | ينشئ نسخة من كائن [StreamReader](./) الذي يقرأ الأحرف من الملف المحدد باستخدام ترميز UTF-8 ومخزن بحجم افتراضي 4096 بايت. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, **bool**) | ينشئ نسخة من كائن [StreamReader](./) الذي يقرأ الأحرف من الملف المحدد باستخدام ترميز UTF-8 ومخزن بحجم افتراضي 4096 بايت. يحدد معامل ما إذا كان يجب تمكين اكتشاف علامة ترتيب البايت. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | ينشئ نسخة من كائن [StreamReader](./) الذي يقرأ الأحرف من الملف المحدد باستخدام الترميز المحدد ومخزن بحجم افتراضي 4096 بايت. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | ينشئ نسخة من كائن [StreamReader](./) الذي يقرأ الأحرف من التدفق الضمني المحدد باستخدام الترميز المحدد ومخزن بحجم افتراضي 4096 بايت. يحدد معامل ما إذا كان يجب تمكين اكتشاف علامة ترتيب البايت. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**, int) | ينشئ نسخة من كائن [StreamReader](./) الذي يقرأ الأحرف من الملف المحدد باستخدام الترميز المحدد ومخزن بالحجم المحدد. يحدد معامل ما إذا كان يجب تمكين اكتشاف علامة ترتيب البايت. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تماثل طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يطبق بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يطبق إلغاء قفل بيان C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجعية الضعيفة. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجعية الضعيفة. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |
|  [~StreamReader](./~streamreader/)() | المدمر. |

## انظر أيضًا

* الصنف [TextReader](../textreader/)
* النطاق [System::IO](../)
* المكتبة [Aspose.Slides](../../)