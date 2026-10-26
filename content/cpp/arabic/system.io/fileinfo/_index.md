---
title: FileInfo
second_title: مرجع API ل Aspose.Slides لـ C++
description: "يمثل مسارًا إلى ملف والملف المشار إليه بهذا المسار ويوفر طرقًا لمعالجته. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject(). لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام العامل new، لأن ذلك سيسبب أخطاءً في وقت التشغيل و/أو أخطاء تأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر System::SmartPtr واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 274
url: /ar/system.io/fileinfo/
---
## الفئة FileInfo

يمثل مسارًا إلى ملف والملف المشار إليه بهذا المسار ويقدم طرقًا للتعامل معه. يجب إنشاء كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام عامل new، لأن ذلك سيسبب أخطاءً في وقت التشغيل و/أو أخطاء تأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class FileInfo : public System::IO::FileSystemInfo
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [StreamWriterPtr](../../system/streamwriterptr/) [AppendText](./appendtext/)() | يفتح ملفًا ممثلاً بواسطة الكائن الحالي للكتابة النصية باستخدام ترميز UTF-8، في وضع 'Append' بدون مشاركة. |
| [FileInfoPtr](../../system/fileinfoptr/) [CopyTo](./copyto/)(const [String](../../system/string/)\&) | ينسخ الملف الممثل بواسطة الكائن الحالي إلى الموقع المحدد. إذا كان ملف الوجهة موجودًا بالفعل، فإن النسخ يفشل. |
| [FileInfoPtr](../../system/fileinfoptr/) [CopyTo](./copyto/)(const [String](../../system/string/)\&, **bool**) | ينسخ الملف الممثل بواسطة الكائن الحالي إلى الموقع المحدد. تحدد المعلمة ما إذا كان يجب استبدال ملف الوجهة الموجود. |
| [FileStreamPtr](../../system/filestreamptr/) [Create](./create/)() | ينشئ ملفًا في الموقع المحدد بواسطة المسار الممثل بواسطة الكائن الحالي ويفتحه للقراءة والكتابة، في وضع القطع بدون مشاركة. |
| [StreamWriterPtr](../../system/streamwriterptr/) [CreateText](./createtext/)() | ينشئ ملفًا في الموقع المحدد بواسطة المسار الممثل بواسطة الكائن الحالي ويفتحه للكتابة النصية باستخدام ترميز UTF-8 بدون مشاركة. |
| void [Decrypt](./decrypt/)() | غير مُنفَّذ. |
| void [Delete](./delete/)() override | يزيل الملف الممثل بواسطة الكائن الحالي. |
| void [Encrypt](./encrypt/)() | غير مُنفَّذ. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالة C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بنمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بنمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث تُعتبر NaNين متساويتين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث تُعتبر NaNين متساويتين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للأغراض الداخلية فقط. |
| [FileInfo](./fileinfo/)(const [String](../../system/string/)\&) | يبني نسخة جديدة من الفئة [FileInfo](./) التي تمثل الملف المحدد. |
| virtual void [Finalize](../filesysteminfo/finalize/)() | لا يفعل شيئًا. |
| [FileAttributes](../fileattributes/) [get_Attributes](../filesysteminfo/get_attributes/)() | يعيد سمات الكيان الممثل بواسطة الكائن الحالي. |
| [DateTime](../../system/datetime/) [get_CreationTime](../filesysteminfo/get_creationtime/)() | يعيد وقت الإنشاء للكيان الممثل بواسطة الكائن الحالي كوقت محلي. |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](../filesysteminfo/get_creationtimeutc/)() | يعيد وقت الإنشاء للكيان الممثل بواسطة الكائن الحالي كوقت UTC. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Directory](./get_directory/)() | يعيد كائن [DirectoryInfo](../directoryinfo/) يمثل الدليل الذي يقع فيه الملف الممثل بواسطة الكائن الحالي. |
| [String](../../system/string/) [get_DirectoryName](./get_directoryname/)() | يعيد الاسم الكامل للدليل الذي يقع فيه الملف الممثل بواسطة الكائن الحالي. |
| **bool** [get_Exists](./get_exists/)() override | يعيد قيمة تشير إلى ما إذا كان الملف موجودًا. |
| [String](../../system/string/) [get_Extension](../filesysteminfo/get_extension/)() | يعيد امتداد الملف الممثل بواسطة الكائن الحالي. |
| virtual [String](../../system/string/) [get_FullName](../filesysteminfo/get_fullname/)() | يعيد الاسم الكامل (متضمنًا المسار) للكيان الممثل بواسطة الكائن الحالي. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() | يعيد قيمة تشير إلى ما إذا كانت سمة ReadOnly مفعلة. |
| [DateTime](../../system/datetime/) [get_LastAccessTime](../filesysteminfo/get_lastaccesstime/)() | يعيد وقت آخر وصول للكيان الممثل بواسطة الكائن الحالي كوقت محلي. |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](../filesysteminfo/get_lastaccesstimeutc/)() | يعيد وقت آخر وصول للكيان الممثل بواسطة الكائن الحالي كوقت UTC. |
| [DateTime](../../system/datetime/) [get_LastWriteTime](../filesysteminfo/get_lastwritetime/)() | يعيد وقت آخر كتابة للكيان الممثل بواسطة الكائن الحالي كوقت محلي. |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](../filesysteminfo/get_lastwritetimeutc/)() | يعيد وقت آخر كتابة للكيان الممثل بواسطة الكائن الحالي كوقت UTC. |
| **int64_t** [get_Length](./get_length/)() | يعيد حجم الملف بالبايت. |
| [String](../../system/string/) [get_Name](./get_name/)() override | يعيد اسم الملف. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجعية المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. نظير معامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل عبارة C# lock(). استدعِه مباشرةً أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
| void [MoveTo](./moveto/)(const [String](../../system/string/)\&) | ينقل الملف الممثل بواسطة الكائن الحالي إلى الموقع المحدد. |
| [Object](../../system/object/object/)() | ينشئ كائنًا. يهيء جميع بنى البيانات الداخلية. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ أي شيء فعليًا، فقط يهيء كائنًا جديدًا ويمكّن بنية النسخ للفئات المشتقة. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/)) | يفتح الملف الممثل بواسطة الكائن الحالي في الوضع المحدد للقراءة والكتابة بدون مشاركة. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/), [FileAccess](../fileaccess/)) | يفتح الملف الممثل بواسطة الكائن الحالي في الوضع المحدد، بنوع الوصول المحدد ودون مشاركة. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/)) | يفتح الملف الممثل بواسطة الكائن الحالي في الوضع المحدد، بنوع الوصول المحدد وخيار المشاركة. |
| [FileStreamPtr](../../system/filestreamptr/) [OpenRead](./openread/)() | يفتح ملفًا ممثلاً بالكائن الحالي للقراءة فقط، في وضع 'Open' مع وصول مشترك للقراءة. |
| [StreamReaderPtr](../../system/streamreaderptr/) [OpenText](./opentext/)() | يفتح الملف الموجود في الموقع المحدد بواسطة المسار الممثل بالكائن الحالي لقراءة النص باستخدام ترميز UTF-8 بدون مشاركة. |
| [FileStreamPtr](../../system/filestreamptr/) [OpenWrite](./openwrite/)() | يفتح ملفًا ممثلاً بالكائن الحالي للكتابة فقط، في وضع 'OpenOrCreate' بدون مشاركة. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يهيء كائنًا جديدًا ويمكّن بنية النسخ للفئات المشتقة. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| void [Refresh](../filesysteminfo/refresh/)() | يُجدد حالة الكائن الحالي. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ينقص عداد المرجعة المشتركة بالقيمة المحددة. |
| [FileInfoPtr](../../system/fileinfoptr/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | يستبدل محتويات ملف الوجهة المحدد بالملف الممثل بواسطة كائن [FileInfo](./) الحالي وينشئ نسخة احتياطية من الملف المستبدل. |
| [FileInfoPtr](../../system/fileinfoptr/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | يستبدل محتويات ملف الوجهة المحدد بالملف الممثل بواسطة كائن [FileInfo](./) الحالي وينشئ نسخة احتياطية من الملف المستبدل. |
| void [set_Attributes](../filesysteminfo/set_attributes/)([FileAttributes](../fileattributes/)) | يضبط السمات المحددة للكيان الممثل بالكائن الحالي. |
| void [set_CreationTime](../filesysteminfo/set_creationtime/)([DateTime](../../system/datetime/)) | يضبط وقت الإنشاء للكيان الممثل بالكائن الحالي كوقت محلي. |
| void [set_CreationTimeUtc](../filesysteminfo/set_creationtimeutc/)([DateTime](../../system/datetime/)) | يضبط وقت الإنشاء للكيان الممثل بالكائن الحالي كوقت UTC. |
| void [set_IsReadOnly](./set_isreadonly/)(**bool**) | يضبط أو يلغي سمة ReadOnly على الملف. |
| void [set_LastAccessTime](../filesysteminfo/set_lastaccesstime/)([DateTime](../../system/datetime/)) | يضبط وقت آخر وصول للكيان الممثل بالكائن الحالي كوقت محلي. |
| void [set_LastAccessTimeUtc](../filesysteminfo/set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | يضبط وقت آخر وصول للكيان الممثل بالكائن الحالي كوقت UTC. |
| void [set_LastWriteTime](../filesysteminfo/set_lastwritetime/)([DateTime](../../system/datetime/)) | يضبط وقت آخر كتابة للكيان الممثل بالكائن الحالي كوقت محلي. |
| void [set_LastWriteTimeUtc](../filesysteminfo/set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | يضبط وقت آخر كتابة للكيان الممثل بالكائن الحالي كوقت UTC. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n إلى مؤشر ضعيف (بدلاً من مشترك). يتيح تحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجعة المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجعة المشتركة. لا يجب استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجعة المشتركة. لا يجب استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | يعيد مسارًا ممثلاً بالكائن الحالي. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل عبارة C# lock(). استدعِه مباشرةً أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجعة الضعيفة. لا يجب استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجعة الضعيفة. لا يجب استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* الفئة [FileSystemInfo](../filesysteminfo/)
* النطاق [System::IO](../)
* المكتبة [Aspose.Slides](../../)