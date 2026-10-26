---
title: BlobManagementOptions
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides للغة C++
description: يمثل الخيارات التي يمكن استخدامها لإدارة قواعد معالجة BLOB وإعدادات BLOB الأخرى.
type: docs
weight: 196
url: /ar/aspose.slides/blobmanagementoptions/
---
## BlobManagementOptions فئة

يمثل الخيارات التي يمكن استخدامها لإدارة قواعد معالجة BLOB وإعدادات BLOB الأخرى.

```cpp
class BlobManagementOptions : public Aspose::Slides::IBlobManagementOptions
```

## طرق

| الطريقة | الوصف |
| --- | --- |
|  [BlobManagementOptions](./blobmanagementoptions/)() | ينشئ خيارات إدارة BLOB الافتراضية الجديدة. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات [Object.Equals](../../system/object/equals/) الخاصة بـ C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي على نمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي على نمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة على نمط C# حيث يُعتبر NaNانان متساويين رغم أنه وفقًا لـ IEC 60559:1989 لا يكون NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة على نمط C# حيث يُعتبر NaNانان متساويين رغم أنه وفقًا لـ IEC 60559:1989 لا يكون NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للاستخدام الداخلي فقط. |
| **bool** [get_IsTemporaryFilesAllowed](./get_istemporaryfilesallowed/)() override | تحدد هذه الخاصية ما إذا كان يمكن إنشاء ملفات مؤقتة أثناء العمل مع BLOBs، مما يقلل بشكل كبير من استهلاك الذاكرة لكنه يتطلب أذونات لإنشاء الملفات. |
| **uint64_t** [get_MaxBlobsBytesInMemory](./get_maxblobsbytesinmemory/)() override | تحدد الحد الأقصى للحجم الإجمالي (بالبايت) الذي قد تشغله جميع BLOBs في الذاكرة. بشكل افتراضي، يتم تحميل جميع BLOBs إلى الذاكرة؛ وعند بلوغ هذا الحد تُستعمَل آليات بديلة (مثل الملفات المؤقتة). إبقاء BLOBs في الذاكرة يزيد الأداء ولكنه قد يؤدي إلى استهلاك عالي للذاكرة. استخدم هذه الخاصية لتكييف السلوك مع بيئتك أو متطلباتك. |
| [Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/) [get_PresentationLockingBehavior](./get_presentationlockingbehavior/)() override | تحدد هذه الخاصية ما إذا كان كائن من الفئة [Presentation](../presentation/) يمكن أن يكون مالكًا للمصدر - الملف أو الدفق خلال عمر الكائن. إذا كان الكائن مالكًا، فإنه يقفل المصدر. يساعد ذلك في تحسين استهلاك الذاكرة والأداء أثناء العمل مع BLOBs، لكن لا يمكن تغيير المصدر (الدفق أو الملف) خلال عمر كائن [Presentation](../presentation/). |
| [System::String](../../system/string/) [get_TempFilesRootPath](./get_tempfilesrootpath/)() override | المسار الجذري حيث سيتم إنشاء الملفات المؤقتة. سيتم استخدام دليل [System](../../system/) المؤقت بشكل افتراضي. يجب أن يكون لعملية الاستضافة أذونات لإنشاء الملفات والمجلدات هناك. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة [Object.GetHashCode()](../../system/object/gethashcode/) الخاصة بـ C#. يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء [System.Object.GetType()](../../system/object/gettype/) الخاص بـ C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق ما إذا كان الكائن يمثل مثيلًا لنوع موصوف بواسطة targetType. نظير عامل 'is' في C#. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل بيان lock() في C#. يُستدعى مباشرة أو يستخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة [Object.MemberwiseClone()](../../system/object/memberwiseclone/) الخاصة بـ C#. يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بنسخ بناء الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل تعيين. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بنسخ بناء الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيدي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_IsTemporaryFilesAllowed](./set_istemporaryfilesallowed/)(**bool**) override | تحدد هذه الخاصية ما إذا كان يمكن إنشاء ملفات مؤقتة أثناء العمل مع BLOBs، مما يقلل بشكل كبير من استهلاك الذاكرة لكنه يتطلب أذونات لإنشاء الملفات. |
| void [set_MaxBlobsBytesInMemory](./set_maxblobsbytesinmemory/)(**uint64_t**) override | تحدد الحد الأقصى للحجم الإجمالي (بالبايت) الذي قد تشغله جميع BLOBs في الذاكرة. بشكل افتراضي، يتم تحميل جميع BLOBs إلى الذاكرة؛ وعند بلوغ هذا الحد تُستعمَل آليات بديلة (مثل الملفات المؤقتة). إبقاء BLOBs في الذاكرة يزيد الأداء ولكنه قد يؤدي إلى استهلاك عالي للذاكرة. استخدم هذه الخاصية لتكييف السلوك مع بيئتك أو متطلباتك. |
| void [set_PresentationLockingBehavior](./set_presentationlockingbehavior/)([Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/)) override | تحدد هذه الخاصية ما إذا كان كائن من الفئة [Presentation](../presentation/) يمكن أن يكون مالكًا للمصدر - الملف أو الدفق خلال عمر الكائن. إذا كان الكائن مالكًا، فإنه يقفل المصدر. يساعد ذلك في تحسين استهلاك الذاكرة والأداء أثناء العمل مع BLOBs، لكن لا يمكن تغيير المصدر (الدفق أو الملف) خلال عمر كائن [Presentation](../presentation/). |
| void [set_TempFilesRootPath](./set_tempfilesrootpath/)([System::String](../../system/string/)) override | المسار الجذري حيث سيتم إنشاء الملفات المؤقتة. سيتم استخدام دليل [System](../../system/) المؤقت بشكل افتراضي. يجب أن يكون لعملية الاستضافة أذونات لإنشاء الملفات والمجلدات هناك. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط النمطي رقم n ليكون مؤشرًا ضعيفًا (بدلاً من المشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع الضعف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة [Object.ToString()](../../system/object/tostring/) الخاصة بـ C#. يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل بيان lock() في C#. يُستدعى مباشرة أو يستخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* فئة [IBlobManagementOptions](../iblobmanagementoptions/)
* نطاق [Aspose::Slides](../)
* مكتبة [Aspose.Slides](../../)