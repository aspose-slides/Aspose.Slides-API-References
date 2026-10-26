---
title: IBlobManagementOptions
second_title: مرجع API لـ Aspose.Slides للغة C++
description: كائن كبير ثنائي (BLOB) هو بيانات ثنائية مخزنة ككيان واحد - أي أن BLOB يمكن أن يكون صوتًا أو فيديو أو عرضًا تقديميًا بحد ذاته. تُستخدم عدة تقنيات لتحسين استهلاك الذاكرة أثناء التعامل مع BLOBs - التي قد تكون مخزنة مسبقًا في العرض التقديمي أو تُضاف لاحقًا برمجيًا. باستخدام IBlobManagementOptions يمكنك تغيير جوانب سلوك مختلفة تتعلق بمعالجة BLOBs طوال عمر مثيل IPresentation.
type: docs
weight: 1535
url: /ar/aspose.slides/iblobmanagementoptions/
---
## IBlobManagementOptions فئة

كائن كبير ثنائي (BLOB) هو بيانات ثنائية مخزنة ككيان واحد - أي أن BLOB يمكن أن يكون صوتًا أو فيديو أو عرضًا تقديميًا بحد ذاته. تُستخدم مجموعة من التقنيات لتحسين استهلاك الذاكرة أثناء التعامل مع BLOBs - التي قد تكون مخزنة مسبقًا في العرض التقديمي أو تُضاف لاحقًا برمجيًا. باستخدام [IBlobManagementOptions](./) يمكنك تغيير جوانب سلوك مختلفة تتعلق بمعالجة BLOBs طوال عمر المثيل [IPresentation](../ipresentation/).

```cpp
class IBlobManagementOptions : public virtual System::Object
```

## طرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمتا NaN متساويتين على الرغم من أن معيار IEC 60559:1989 ينص على أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمتا NaN متساويتين على الرغم من أن معيار IEC 60559:1989 ينص على أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual **bool** [get_IsTemporaryFilesAllowed](./get_istemporaryfilesallowed/)() | تحدد هذه الخاصية ما إذا يمكن إنشاء ملفات مؤقتة أثناء العمل مع BLOBs، مما يقلل كثيرًا من استهلاك الذاكرة ولكنه يتطلب أذونات لإنشاء الملفات. |
| virtual **uint64_t** [get_MaxBlobsBytesInMemory](./get_maxblobsbytesinmemory/)() | تحدد الحد الأقصى للحجم الإجمالي (بالبايت) الذي قد تشغله جميع BLOBs في الذاكرة. بشكل افتراضي، يتم تحميل جميع BLOBs إلى الذاكرة؛ وعند وصول هذا الحد تُستعمل آليات بديلة (مثل الملفات المؤقتة). الحفاظ على BLOBs في الذاكرة يعزز الأداء لكنه قد يسبب استهلاكًا عاليًا للذاكرة. استخدم هذه الخاصية لتخصيص السلوك وفقًا لبيئتك أو متطلباتك. |
| virtual [Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/) [get_PresentationLockingBehavior](./get_presentationlockingbehavior/)() | تحدد هذه الخاصية ما إذا كان يمكن لكائن من فئة [Presentation](../presentation/) أن يكون مالكًا للمصدر - الملف أو التدفق طوال عمر المثيل. إذا كان الكائن مالكًا، فإنه يقوم بقفل المصدر. يساعد ذلك في تحسين استهلاك الذاكرة والأداء أثناء العمل مع BLOBs، ولكن لا يمكن تغيير المصدر (التدفق أو الملف) خلال عمر المثيل [Presentation](../presentation/). هذا مثال: |
| virtual [System::String](../../system/string/) [get_TempFilesRootPath](./get_tempfilesrootpath/)() | المسار الجذر حيث سيتم إنشاء الملفات المؤقتة. سيتم استخدام الدليل المؤقت [System](../../system/) بشكل افتراضي. يجب أن تكون عملية الاستضافة لديها أذونات لإنشاء الملفات والمجلدات هناك. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المراجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل مثيلًا لنوع موصوف بواسطة targetType. مماثل لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة C# lock(). استدع مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالإشارة. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالإشارة. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالإشارة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد الإشارة المشتركة بالقيمة المحددة. |
| virtual void [set_IsTemporaryFilesAllowed](./set_istemporaryfilesallowed/)(**bool**) | تحدد هذه الخاصية ما إذا يمكن إنشاء ملفات مؤقتة أثناء العمل مع BLOBs، مما يقلل كثيرًا من استهلاك الذاكرة ولكنه يتطلب أذونات لإنشاء الملفات. |
| virtual void [set_MaxBlobsBytesInMemory](./set_maxblobsbytesinmemory/)(**uint64_t**) | تحدد الحد الأقصى للحجم الإجمالي (بالبايت) الذي قد تشغله جميع BLOBs في الذاكرة. بشكل افتراضي، يتم تحميل جميع BLOBs إلى الذاكرة؛ وعند وصول هذا الحد تُستعمل آليات بديلة (مثل الملفات المؤقتة). الحفاظ على BLOBs في الذاكرة يعزز الأداء لكنه قد يسبب استهلاكًا عاليًا للذاكرة. استخدم هذه الخاصية لتخصيص السلوك وفقًا لبيئتك أو متطلباتك. |
| virtual void [set_PresentationLockingBehavior](./set_presentationlockingbehavior/)([Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/)) | تحدد هذه الخاصية ما إذا كان يمكن لكائن من فئة [Presentation](../presentation/) أن يكون مالكًا للمصدر - الملف أو التدفق طوال عمر المثيل. إذا كان الكائن مالكًا، فإنه يقوم بقفل المصدر. يساعد ذلك في تحسين استهلاك الذاكرة والأداء أثناء العمل مع BLOBs، ولكن لا يمكن تغيير المصدر (التدفق أو الملف) خلال عمر المثيل [Presentation](../presentation/). هذا مثال: |
| virtual void [set_TempFilesRootPath](./set_tempfilesrootpath/)([System::String](../../system/string/)) | المسار الجذر حيث سيتم إنشاء الملفات المؤقتة. سيتم استخدام الدليل المؤقت [System](../../system/) بشكل افتراضي. يجب أن تكون عملية الاستضافة لديها أذونات لإنشاء الملفات والمجلدات هناك. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب الـ n't إلى مؤشر ضعيف (بدلاً من المشترك). يتيح تحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد الإشارة المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد الإشارة المشتركة. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل عداد الإشارة المشتركة ويعيد قيمته. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل عبارة C# lock(). استدع مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* فئة [Object](../../system/object/)
* نطاق [Aspose::Slides](../)
* مكتبة [Aspose.Slides](../../)