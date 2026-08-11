---
title: Encoding
second_title: مرجع API لـ Aspose.Slides للـ C++
description: خدمات الترميز.
type: docs
weight: 222
url: /ar/system.text/encoding/
---
## Encoding فئة


[Encoding](./) خدمات.

```cpp
class Encoding : public System::Object
```

## طرق

| Method | Description |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() | ينسخ كائن الترميز. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](./convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | تحويل البايتات بين ترميزين. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](./convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | تحويل البايتات بين ترميزين. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | يقارن بين الترميزات. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بنمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث يُعتبر اثنان NaN متساويين رغم أنه وفقًا لـ IEC 60559:1989 لا يُعتبر NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث يُعتبر اثنان NaN متساويين رغم أنه وفقًا لـ IEC 60559:1989 لا يُعتبر NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للغرض الداخلي فقط. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](./get_ascii/)() | يحصل على ترميز ASCII. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](./get_bigendianunicode/)() | يحصل على كائن ترميز Unicode القياسي بنظام big-endian. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](./get_bigendianutf32/)() | يحصل على كائن ترميز UTF-32 القياسي بنظام big-endian. |
| virtual [String](../../system/string/) [get_BodyName](./get_bodyname/)() | يحصل على اسم الترميز المتوافق مع جسم عميل البريد. |
| virtual int [get_CodePage](./get_codepage/)() | يحصل على معرف صفحة الترميز [Windows](../../system.windows/). |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](./get_decoderfallback/)() const | يحصل على تعويض فك الترميز. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](./get_default/)() | يحصل على الترميز الافتراضي. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](./get_encoderfallback/)() const | يحصل على تعويض مشفر الترميز. |
| virtual [String](../../system/string/) [get_EncodingName](./get_encodingname/)() | يحصل على اسم الترميز القابل للقراءة البشرية. |
| virtual [String](../../system/string/) [get_HeaderName](./get_headername/)() | يحصل على اسم الترميز المتوافق مع رأس عميل البريد. |
| virtual **bool** [get_IsBrowserDisplay](./get_isbrowserdisplay/)() | يتحقق مما إذا كان يمكن استخدام الترميز في المتصفح لعرض المحتوى. |
| virtual **bool** [get_IsBrowserSave](./get_isbrowsersave/)() | يتحقق مما إذا كان يمكن استخدام الترميز في المتصفح لحفظ المحتوى. |
| virtual **bool** [get_IsMailNewsDisplay](./get_ismailnewsdisplay/)() | يتحقق مما إذا كان يمكن استخدام الترميز في عميل البريد لعرض المحتوى. |
| virtual **bool** [get_IsMailNewsSave](./get_ismailnewssave/)() | يتحقق مما إذا كان يمكن استخدام الترميز في عميل البريد لحفظ المحتوى. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() | يتحقق مما إذا كان الترميز للقراءة فقط. |
| virtual **bool** [get_IsSingleByte](./get_issinglebyte/)() | يتحقق مما إذا كان الترميز بايتًا واحدًا. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](./get_latin1/)() | يحصل على ترميز Latin1. للاستخدام الداخلي. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](./get_unicode/)() | يحصل على كائن ترميز Unicode القياسي. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](./get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](./get_utf7/)() | يحصل على كائن ترميز UTF-7 القياسي. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](./get_utf8/)() | يحصل على كائن ترميز UTF-8 القياسي. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](./get_utf8unmarked/)() | للاستخدام الداخلي فقط، من قبل مكتبات الفئة: غير معلم وغير مُصادق على الإدخال. |
| virtual [String](../../system/string/) [get_WebName](./get_webname/)() | يحصل على اسم الترميز المتوافق مع IANA. |
| virtual int [get_WindowsCodePage](./get_windowscodepage/)() | يحصل على معرف صفحة الترميز [Windows](../../system.windows/). |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | يحصل على عدد الأحرف المطلوبة لترميز مخزن الأحرف. |
| virtual int [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | يحصل على عدد الأحرف المطلوبة لترميز مخزن الأحرف. |
| int [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | يحصل على عدد الأحرف المطلوبة لترميز مخزن الأحرف. |
| virtual int [GetByteCount](./getbytecount/)(const [String](../../system/string/)\&) | يحصل على عدد الأحرف المطلوبة لترميز سلسلة. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | يحصل على عدد الأحرف المطلوبة لترميز مخزن الأحرف. |
| virtual int [GetByteCount](./getbytecount/)(const char_t *, int) | يحصل على عدد الأحرف المطلوبة لترميز مخزن الأحرف. |
| virtual int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | يحصل على البايتات الناتجة عن ترميز مخزن الأحرف. |
| virtual int [GetBytes](./getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | يحصل على البايتات الناتجة عن ترميز مخزن الأحرف. |
| int [GetBytes](./getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | يحصل على البايتات الناتجة عن ترميز مخزن الأحرف. |
| virtual int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | يحصل على البايتات الناتجة عن ترميز مخزن الأحرف. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const [String](../../system/string/)\&) | يحصل على البايتات الناتجة عن ترميز مخزن الأحرف. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | يحصل على البايتات الناتجة عن ترميز مخزن الأحرف. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | يحصل على البايتات الناتجة عن ترميز مخزن الأحرف. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | يحصل على البايتات الناتجة عن ترميز مخزن الأحرف. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | يحصل على البايتات الناتجة عن ترميز مخزن الأحرف. |
| virtual int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) | يحصل على البايتات الناتجة عن ترميز مخزن الأحرف. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | يحصل على عدد الأحرف المطلوبة لفك ترميز مخزن البايتات. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | يحصل على عدد الأحرف المطلوبة لفك ترميز مخزن البايتات. |
| virtual int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) | يحصل على عدد الأحرف المطلوبة لفك ترميز مخزن البايتات. |
| virtual int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | يحصل على الأحرف الناتجة عن فك ترميز مخزن البايتات. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | يحصل على الأحرف الناتجة عن فك ترميز مخزن البايتات. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | يحصل على الأحرف الناتجة عن فك ترميز مخزن البايتات. |
| virtual int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) | يحصل على الأحرف الناتجة عن فك ترميز مخزن البايتات. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عدّاد المرجع المرتبط بالكائن. |
| virtual [DecoderPtr](../../system/decoderptr/) [GetDecoder](./getdecoder/)() | احصل على فك شيفرة يوجه الطلبات إلى هذا الكائن. |
| virtual [EncoderPtr](../../system/encoderptr/) [GetEncoder](./getencoder/)() | احصل على مشفر يوجه الطلبات إلى هذا الكائن. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(const [String](../../system/string/)\&) | يحصل على الترميز بالاسم. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(int) | يحصل على الترميز بصفحة الترميز. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | يحصل على الترميز بصفحة الترميز. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | يحصل على الترميز بالاسم. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](./getencodings/)() | يحصل على قائمة الترميزات المعروفة. |
| int [GetHashCode](./gethashcode/)() const override | يحسب تجزئة الترميز. |
| virtual int [GetMaxByteCount](./getmaxbytecount/)(int) | يحصل على الحد الأقصى لعدد البايتات المطلوبة لترميز عدد محدد من الأحرف. |
| virtual int [GetMaxCharCount](./getmaxcharcount/)(int) | يحصل على الحد الأقصى لعدد الأحرف المطلوبة لفك ترميز عدد محدد من البايتات. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](./getpreamble/)() | يرجع تسلسل بايتات يحدد الترميز (مثل BOM). |
| virtual [String](../../system/string/) [GetString](./getstring/)(**uint8_t** *, int) | يفك تشفير مخزن بايتات إلى سلسلة. |
| [String](../../system/string/) [GetString](./getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | يفك تشفير مخزن بايتات إلى سلسلة. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | يفك تشفير مخزن بايتات إلى سلسلة. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | يفك تشفير مخزن بايتات إلى سلسلة. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | يفك تشفير مخزن بايتات إلى سلسلة. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | يفك تشفير مخزن بايتات إلى سلسلة. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | يفك تشفير مخزن بايتات إلى سلسلة. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | يفك تشفير مخزن بايتات إلى سلسلة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. نظير مشغل C# 'is'. |
| void [Lock](../../system/object/lock/)() | يُنفّذ قفل تعبير C# lock(). استدعِ مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ الكائن. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخة للطبقات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخة للطبقات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالإشارة. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالإشارة. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالإشارة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدّاد الإشارة المشتركة بقيمة محددة. |
| void [set_DecoderFallback](./set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | يضبط تعويض الفك. |
| void [set_EncoderFallback](./set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | يضبط تعويض الترميز. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد الإشارة المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد الإشارة المشتركة. لا ينبغي استدعاؤه مباشرة؛ استخدم مؤشرات ذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عدّاد الإشارة المشتركة. لا ينبغي استدعاؤه مباشرة؛ استخدم مؤشرات ذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يُنفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يُنفّذ إلغاء قفل تعبير C# lock(). استدعِ مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم مؤشرات ذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عدّاد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم مؤشرات ذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## حقول

| Field | Description |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](./default_code_page/) | قيمة صفحة الترميز الافتراضية. |

## تعريفات الأنواع

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | RTTI. |

## أنظر أيضًا

* Class [Object](../../system/object/)
* Namespace [System::Text](../)
* Library [Aspose.Slides](../../)