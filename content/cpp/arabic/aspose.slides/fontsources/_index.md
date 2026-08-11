---
title: FontSources
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يوفر مصادر ملفات وذاكرة للخطوط الخارجية.
type: docs
weight: 1002
url: /ar/aspose.slides/fontsources/
---
## فئة FontSources

يوفر مصادر ملفات وذاكرة للخطوط الخارجية.

```cpp
class FontSources : public Aspose::Slides::IFontSources
```

## الطرق

| Method | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام سي شارب [Object.Equals](../../system/object/equals/) السياق. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن الكائنات من نوع المرجع بأسلوب سي شارب. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن الكائنات من نوع القيمة بأسلوب سي شارب. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب سي شارب حيث يُعتبر NaNانان متساويين على الرغم من أنه وفقًا لـ IEC 60559:1989 لا يُعتبر NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب سي شارب حيث يُعتبر NaNانان متساويين على الرغم من أنه وفقًا لـ IEC 60559:1989 لا يُعتبر NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للاستخدام الداخلي فقط. |
|  [FontSources](./fontsources/)() | ينشئ خيارات الخط الافتراضية الجديدة. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_FontFolders](./get_fontfolders/)() override | المجلدات التي تحتوي على ملفات الخط. جميع ملفات الخط الموجودة في هذه المجلدات تُدرج في المجموعة. المجلدات التي يتم البحث فيها بشكل متكرر. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\> [get_MemoryFonts](./get_memoryfonts/)() override | مجموعة من الخطوط ممثلة كمصفوفات بايت. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد الإشارة المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لطريقة [Object.GetHashCode()](../../system/object/gethashcode/) في سي شارب. يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء [System.Object.GetType()](../../system/object/gettype/) في سي شارب. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثالًا للنوع الموصوف بـ targetType. مماثل للمشغل 'is' في سي شارب. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل عبارة lock() في سي شارب. استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة [Object.MemberwiseClone()](../../system/object/memberwiseclone/) في سي شارب. يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيّء جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويمكّن بناء النسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويمكّن بناء النسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن النوع القيمي بـ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد الإشارة المشتركة بالقيمة المحددة. |
| void [set_FontFolders](./set_fontfolders/)([System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) override | المجلدات التي تحتوي على ملفات الخط. جميع ملفات الخط الموجودة في هذه المجلدات تُدرج في المجموعة. المجلدات التي يتم البحث فيها بشكل متكرر. |
| void [set_MemoryFonts](./set_memoryfonts/)([System::ArrayPtr](../../system/arrayptr/)\<[System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\>) override | مجموعة من الخطوط ممثلة كمصفوفات بايت. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب الـ n't إلى مؤشر ضعيف (بدلاً من المشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد الإشارة المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد الإشارة المشتركة. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويُعيد عداد الإشارة المشتركة. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة [Object.ToString()](../../system/object/tostring/) في سي شارب. يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية typeof([System.Object](../../system/object/)) في سي شارب. |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل عبارة lock() في سي شارب. استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* الفئة [IFontSources](../ifontsources/)
* النطاق [Aspose::Slides](../)
* المكتبة [Aspose.Slides](../../)