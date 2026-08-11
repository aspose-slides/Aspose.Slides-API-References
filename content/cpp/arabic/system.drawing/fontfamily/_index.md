---
title: FontFamily
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides لـ C++
description: "يمثل مجموعة من الخطوط التي تشترك في تصميم أساسي مشابه. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject(). لا تقم أبداً بإنشاء مثيل لهذا النوع على المكدس أو باستخدام المشغل new، لأن ذلك سيسبّب أخطاءً أثناء التشغيل و/أو أخطاءً في العبارات الشرطية. احرص دائماً على تغليف هذه الفئة في مؤشر System::SmartPtr واستخدام هذا المؤشر لتمريره إلى الدوال كوسيط."
type: docs
weight: 105
url: /ar/system.drawing/fontfamily/
---
## FontFamily فئة

يمثل مجموعة من الخطوط التي تشترك في تصميم أساسي مشابه. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تقم أبداً بإنشاء مثيل لهذا النوع على المكدس أو باستخدام المشغل new، لأن ذلك سيسبّب أخطاءً أثناء التشغيل و/أو أخطاءً في العبارات الشرطية. احرص دائماً على تغليف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدام هذا المؤشر لتمريره إلى الدوال كوسيط.

```cpp
class FontFamily : public System::Object
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[FontFamily](./)\> [Clone](./clone/)() | تُعيد نسخة من الكائن [FontFamily](./) الحالي. |
| void [Dispose](./dispose/)() | يطلق جميع موارد نظام التشغيل التي تم الحصول عليها بواسطة الكائن الحالي. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | يحدّد ما إذا كان الكائنان الحالي والمحدّد متطابقين. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة الأعداد الفاصلة العائمة على نمط C# حيث يُعتبر NaNانان مساويين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة الأعداد الفاصلة العائمة (double) على نمط C# حيث يُعتبر NaNانان مساويين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [FontFamily](./fontfamily/)(const [String](../../system/string/)\&) | ينشئ مثيلاً جديداً من الفئة [FontFamily](./) الذي يمثل عائلة خطوط بالاسم المحدد. |
| [FontFamily](./fontfamily/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Text::FontCollection](../../system.drawing.text/fontcollection/)\>\&) | ينشئ مثيلاً جديداً من [FontFamily](./) في مجموعة الخطوط المحددة بالاسم المحدد. |
| [FontFamily](./fontfamily/)([Text::GenericFontFamilies](../../system.drawing.text/genericfontfamilies/)) | ينشئ مثيلاً جديداً من [FontFamily](./) من عائلة الخطوط العامة المحددة. |
| static [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[FontFamily](./)\>\> [get_Families](./get_families/)() | تُعيد مصفوفة تحتوي على جميع كائنات [FontFamily](./) المرتبطة بسياق الرسومات الحالي. |
| static [SharedPtr](../../system/sharedptr/)\<[FontFamily](./)\> [get_GenericMonospace](./get_genericmonospace/)() | تُعيد كائن [FontFamily](./) الذي يمثل عائلة خطوط أحادية العرض عامة. |
| static [SharedPtr](../../system/sharedptr/)\<[FontFamily](./)\> [get_GenericSansSerif](./get_genericsansserif/)() | تُعيد كائن [FontFamily](./) الذي يمثل عائلة خطوط Sans Serif عامة. |
| static [SharedPtr](../../system/sharedptr/)\<[FontFamily](./)\> [get_GenericSerif](./get_genericserif/)() | تُعيد كائن [FontFamily](./) الذي يمثل عائلة خطوط Serif عامة. |
| [String](../../system/string/) [get_Name](./get_name/)() const | تُعيد اسم عائلة الخطوط التي يمثلها الكائن الحالي. |
| int [GetCellAscent](./getcellascent/)([FontStyle](../fontstyle/)) | تُعيد صعود الخلية لعائلة الخطوط التي يمثلها الكائن الحالي للنمط المحدد. |
| int [GetCellDescent](./getcelldescent/)([FontStyle](../fontstyle/)) | تُعيد هبوط الخلية لعائلة الخطوط التي يمثلها الكائن الحالي للنمط المحدد. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عدّاد المرجع المرتبط بالكائن. |
| int [GetEmHeight](./getemheight/)([FontStyle](../fontstyle/)) | تُعيد ارتفاع مربع الـ em بوحدات تصميم الخط للنمط المحدد. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تمثيل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصَّصة. |
| int [GetLineSpacing](./getlinespacing/)([FontStyle](../fontstyle/)) | تُعيد تباعد السطر لعائلة الخطوط التي يمثلها الكائن الحالي للنمط المحدد. |
| [String](../../system/string/) [GetName](./getname/)(int) const | تُعيد اسم عائلة الخطوط التي يمثلها الكائن الحالي. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تمثيل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثيلاً للنوع الموصوف بواسطة targetType. تمثيل لمشغل C# 'is'. |
| **bool** [IsStyleAvailable](./isstyleavailable/)([FontStyle](../fontstyle/)) | يحدّد ما إذا كان النمط الخط المحدد متاحاً. |
| void [Lock](../../system/object/lock/)() | يُطبق قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تمثيل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصَّصة. |
| [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن المرجع لكائن من نوع القيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقوم بتقليل عدّاد المرجع المشترك بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n كـ مؤشر ضعيف (بدلاً من المشترك). يتيح تحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استعن بالمؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استعن بالمؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تمثيل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصَّصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يُطبق بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يُطبق إلغاء قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استعن بالمؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استعن بالمؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~FontFamily](./~fontfamily/)() | المدمر. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يُحرِّر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* فئة [Object](../../system/object/)
* مساحة الأسماء [System::Drawing](../)
* مكتبة [Aspose.Slides](../../)