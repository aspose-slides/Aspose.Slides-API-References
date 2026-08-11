---
title: File
second_title: مرجع API Aspose.Slides للـ C++
description: يقدم طرقًا للتعامل مع الملفات. هذا نوع ثابت لا يحتوي على خدمات كائن. لا يجب إنشاء مثيلات منه بأي وسيلة.
type: docs
weight: 261
url: /ar/system.io/file/
---
## File فئة

يوفر طرقًا للتعامل مع الملفات. هذا نوع ثابت لا يحتوي على خدمات كائن. يجب ألا تقوم بإنشاء مثيلات له بأي وسيلة.

```cpp
class File
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| static void [AppendAllLines](./appendalllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | يضيف السلاسل من مجموعة السلاسل المحددة إلى الملف المحدد باستخدام الترميز المحدد عن طريق كتابة كل سلسلة في سطر جديد. إذا لم يكن الملف المحدد موجودًا، يتم إنشاؤه. يتم إغلاق الملف بعد كتابة جميع السلاسل. |
| static void [AppendAllText](./appendalltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | يضيف السلسلة المحددة إلى الملف المحدد باستخدام الترميز المحدد. |
| static [StreamWriterPtr](../../system/streamwriterptr/) [AppendText](./appendtext/)(const [String](../../system/string/)\&) | ينشئ كائن [StreamWriter](../streamwriter/) يضيف نصًا إلى الملف المحدد باستخدام ترميز UTF-8. إذا لم يكن الملف المحدد موجودًا، يتم إنشاؤه. |
| static void [Copy](./copy/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | ينقل الملف المحدد إلى الموقع الجديد. |
| static [FileStreamPtr](../../system/filestreamptr/) [Create](./create/)(const [String](../../system/string/)\&, **int32_t**, [FileOptions](../fileoptions/)) | ينشئ ملفًا جديدًا (أو يستبدل الموجود) ويفتحه للوصول للقراءة والكتابة باستخدام حجم المخزن المؤقت المحدد والخيارات. |
| static [StreamWriterPtr](../../system/streamwriterptr/) [CreateText](./createtext/)(const [String](../../system/string/)\&) | ينشئ ملفًا جديدًا أو يفتح ملفًا موجودًا لكتابة نص مشفر بـ UTF-8. |
| static void [Decrypt](./decrypt/)(const [String](../../system/string/)\&) | غير مُنفّذ. |
| static void [Delete](./delete/)(const [String](../../system/string/)\&) | يحذف الملف أو الدليل المحدد. |
| static void [Encrypt](./encrypt/)(const [String](../../system/string/)\&) | غير مُنفّذ. |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | يحدد ما إذا كان المسار المحدد يشير إلى ملف موجود. |
| static [FileAttributes](../fileattributes/) [GetAttributes](./getattributes/)(const [String](../../system/string/)\&) | يرجع سمات الكيان المحدد. |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | يرجع وقت الإنشاء للكيان المحدد بالتوقيت المحلي. |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | يرجع وقت الإنشاء للكيان المحدد بتوقيت UTC. |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | يرجع وقت الوصول الأخير للكيان المحدد بالتوقيت المحلي. |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | يرجع وقت الوصول الأخير للكيان المحدد بتوقيت UTC. |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | يرجع وقت الكتابة الأخير للكيان المحدد بالتوقيت المحلي. |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | يرجع وقت الكتابة الأخير للكيان المحدد بتوقيت UTC. |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | ينقل الملف المحدد إلى الموقع الجديد. |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/)) | يفتح الملف المحدد في الوضع المحدد للقراءة والكتابة دون مشاركة. |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/)) | يفتح الملف المحدد في الوضع المحدد، مع نوع الوصول المحدد وخيار المشاركة المحدد. |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenRead](./openread/)(const [String](../../system/string/)\&) | يفتح الملف المحدد للقراءة فقط، في وضع 'Open' مع وصول مشترك للقراءة. |
| static [StreamReaderPtr](../../system/streamreaderptr/) [OpenText](./opentext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | يفتح الملف الموجود المحدد لقراءة النص باستخدام ترميز UTF-8 دون مشاركة. |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenWrite](./openwrite/)(const [String](../../system/string/)\&) | يفتح الملف المحدد للكتابة فقط، في وضع 'OpenOrCreate' دون مشاركة. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ReadAllBytes](./readallbytes/)(const [String](../../system/string/)\&) | يقرأ محتوى الملف الثنائي المحدد إلى مصفوفة بايت. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [ReadAllLines](./readalllines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | يقرأ محتوى ملف النص المحدد سطرًا بسطر إلى مصفوفة من السلاسل باستخدام الترميز المحدد. |
| static [String](../../system/string/) [ReadAllText](./readalltext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | يقرأ محتوى ملف النص المحدد إلى كائن [String](../../system/string/) واحد باستخدام الترميز المحدد. |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\> [ReadLines](./readlines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | يقرأ محتوى ملف النص المحدد سطرًا بسطر باستخدام الترميز المحدد ويعيد مجموعة قابلة للتعداد من السلاسل، كل منها يمثل سطرًا واحدًا من محتوى الملف. |
| static void [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | يستبدل محتويات ملف بملف آخر ويُنشئ نسخة احتياطية من الملف المستبدل. |
| static void [SetAttributes](./setattributes/)(const [String](../../system/string/)\&, [FileAttributes](../fileattributes/)) | يضبط السمات المحددة على الملف المحدد. |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | غير مُنفّذ. |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | غير مُنفّذ. |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | غير مُنفّذ. |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | غير مُنفّذ. |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | يضبط وقت الكتابة الأخير للكيان المحدد بالتوقيت المحلي. |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | يضبط وقت الكتابة الأخير للكيان المحدد بتوقيت UTC. |
| static void [WriteAllBytes](./writeallbytes/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | يستبدل الملف الثنائي المحدد ويكتب البايتات المحددة فيه. |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | ينشئ ملف نصي جديد أو يستبدل الملف الموجود ويكتب جميع السلاسل من مجموعة السلاسل القابلة للتعداد المحددة إليه، كل سلسلة في سطر جديد، باستخدام الترميز المحدد. |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | ينشئ ملف نصي جديد أو يستبدل الملف الموجود ويكتب جميع السلاسل من المصفوفة المحددة إلى الملف، كل سلسلة في سطر جديد، باستخدام الترميز المحدد. |
| static void [WriteAllText](./writealltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | ينشئ ملف نصي جديد أو يستبدل الملف الموجود ويكتب محتوى السلسلة المحددة إليه باستخدام الترميز المحدد. |

## الحقول

| الحقل | الوصف |
| --- | --- |
| static [DefaultBufferSize](./defaultbuffersize/) | القيمة الافتراضية لعدد البايتات المخزنة مؤقتًا أثناء القراءة من ملف والكتابة إليه. |

## انظر أيضًا

* النطاق [System::IO](../)
* المكتبة [Aspose.Slides](../../)