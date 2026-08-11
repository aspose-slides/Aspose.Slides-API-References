---
title: ASCIIEncoding
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يمثل ترميز ASCII. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject(). لا تقم بإنشاء مثيل من هذا النوع على المكدس أو باستخدام العامل new، لأن ذلك سيسبب أخطاء وقت التشغيل أو أخطاء تأكيد. دائمًا قم بلف هذه الفئة في مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 1
url: /ar/system.text/asciiencoding/
---
## ASCIIEncoding فئة

يمثل ترميز ASCII. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام العامل new، لأنه سيسبب أخطاء وقت التشغيل أو أخطاء تأكيد. دائمًا قم بلف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class ASCIIEncoding : public System::Text::ICUEncoding
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
|  [ASCIIEncoding](./asciiencoding/)() | منشئ. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](../encoding/clone/)() | ينسخ كائن الترميز. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | يحوِّل البايتات بين ترميزين. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | يحوِّل البايتات بين ترميزين. |
| **bool** [Equals](../encoding/equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | يقارن الترميزات. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالة C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | تحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتَبَر NaNانين متساويين حتى وإن كان وفقًا لـ IEC 60559:1989 NaN ليس مساويًا لأي قيمة، بما فيها NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | تحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتَبَر NaNانين متساويين حتى وإن كان وفقًا لـ IEC 60559:1989 NaN ليس مساويًا لأي قيمة، بما فيها NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](../encoding/get_ascii/)() | يحصل على ترميز ASCII. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](../encoding/get_bigendianunicode/)() | يحصل على كائن ترميز Unicode القياسي ذو الترتيب الكبير (big-endian). |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](../encoding/get_bigendianutf32/)() | يحصل على كائن ترميز UTF-32 القياسي ذو الترتيب الكبير. |
| virtual [String](../../system/string/) [get_BodyName](../encoding/get_bodyname/)() | يحصل على اسم الترميز المتوافق مع جسم عميل البريد. |
| virtual int [get_CodePage](../encoding/get_codepage/)() | يحصل على معرف صفحة الترميز [Windows](../../system.windows/). |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](../encoding/get_decoderfallback/)() const | يحصل على استبدال المُفكك. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](../encoding/get_default/)() | يحصل على الترميز الافتراضي. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](../encoding/get_encoderfallback/)() const | يحصل على استبدال المشفر. |
| virtual [String](../../system/string/) [get_EncodingName](../encoding/get_encodingname/)() | يحصل على اسم الترميز القابل للقراءة البشرية. |
| virtual [String](../../system/string/) [get_HeaderName](../encoding/get_headername/)() | يحصل على اسم الترميز المتوافق مع رأس عميل البريد. |
| virtual **bool** [get_IsBrowserDisplay](../encoding/get_isbrowserdisplay/)() | يتحقق مما إذا كان يمكن استخدام الترميز في المتصفح لعرض المحتوى. |
| virtual **bool** [get_IsBrowserSave](../encoding/get_isbrowsersave/)() | يتحقق مما إذا كان يمكن استخدام الترميز في المتصفح لحفظ المحتوى. |
| virtual **bool** [get_IsMailNewsDisplay](../encoding/get_ismailnewsdisplay/)() | يتحقق مما إذا كان يمكن استخدام الترميز في عميل البريد لعرض المحتوى. |
| virtual **bool** [get_IsMailNewsSave](../encoding/get_ismailnewssave/)() | يتحقق مما إذا كان يمكن استخدام الترميز في عميل البريد لحفظ المحتوى. |
| **bool** [get_IsReadOnly](../encoding/get_isreadonly/)() | يتحقق مما إذا كان الترميز للقراءة فقط. |
| virtual **bool** [get_IsSingleByte](../encoding/get_issinglebyte/)() | يتحقق مما إذا كان الترميز بايتًا واحدًا. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](../encoding/get_latin1/)() | يحصل على ترميز Latin1. للاستخدام الداخلي فقط. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](../encoding/get_unicode/)() | يحصل على كائن ترميز Unicode القياسي. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](../encoding/get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](../encoding/get_utf7/)() | يحصل على كائن ترميز UTF-7 القياسي. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](../encoding/get_utf8/)() | يحصل على كائن ترميز UTF-8 القياسي. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](../encoding/get_utf8unmarked/)() | للاستخدام الداخلي فقط، لاستخدام مكتبات الفئة: غير معلم وغير متحقق من صحة الإدخال. |
| virtual [String](../../system/string/) [get_WebName](../encoding/get_webname/)() | يحصل على اسم الترميز المتوافق مع IANA. |
| virtual int [get_WindowsCodePage](../encoding/get_windowscodepage/)() | يحصل على معرف صفحة الترميز [Windows](../../system.windows/). |
| int [GetByteCount](../icuencoding/getbytecount/)(const char_t *, int) override | يحصل على عدد الأحرف المطلوبة لترميز مخزن الحروف. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | RTTI. |
| int [GetByteCount](../icuencoding/getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(const [String](../../system/string/)\&) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(const char_t *, int) | RTTI. |
| int [GetBytes](../icuencoding/getbytes/)(const char_t *, int, **uint8_t** *, int) override | يحصل على البايتات الناتجة عن ترميز مخزن الحروف. |
| virtual int [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | يحصل على البايتات الناتجة عن ترميز مخزن الحروف. |
| virtual int [GetBytes](../icuencoding/getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | يحصل على البايتات الناتجة عن ترميز مخزن الحروف. |
| int [GetBytes](../icuencoding/getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | يحصل على البايتات الناتجة عن ترميز مخزن الحروف. |
| virtual int [GetBytes](../icuencoding/getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | يحصل على البايتات الناتجة عن ترميز مخزن الحروف. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const [String](../../system/string/)\&) | يحصل على البايتات الناتجة عن ترميز مخزن الحروف. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | يحصل على البايتات الناتجة عن ترميز مخزن الحروف. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | يحصل على البايتات الناتجة عن ترميز مخزن الحروف. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | يحصل على البايتات الناتجة عن ترميز مخزن الحروف. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | يحصل على البايتات الناتجة عن ترميز مخزن الحروف. |
| virtual int [GetBytes](../icuencoding/getbytes/)(const char_t *, int, **uint8_t** *, int) | يحصل على البايتات الناتجة عن ترميز مخزن الحروف. |
| int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) override | يحصل على عدد الأحرف المطلوبة لفك ترميز مخزن البايتات. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | يحصل على عدد الأحرف المطلوبة لفك ترميز مخزن البايتات. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | يحصل على عدد الأحرف المطلوبة لفك ترميز مخزن البايتات. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) | يحصل على عدد الأحرف المطلوبة لفك ترميز مخزن البايتات. |
| int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) override | يحصل على الأحرف الناتجة عن فك ترميز مخزن البايتات. |
| virtual int [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | يحصل على الأحرف الناتجة عن فك ترميز مخزن البايتات. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | يحصل على الأحرف الناتجة عن فك ترميز مخزن البايتات. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | يحصل على الأحرف الناتجة عن فك ترميز مخزن البايتات. |
| virtual int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) | يحصل على الأحرف الناتجة عن فك ترميز مخزن البايتات. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| [DecoderPtr](../../system/decoderptr/) [GetDecoder](../icuencoding/getdecoder/)() override | يحصل على مفكك يوجه الطلبات إلى هذا الكائن. |
| [EncoderPtr](../../system/encoderptr/) [GetEncoder](../icuencoding/getencoder/)() override | يحصل على مشفر يوجه الطلبات إلى هذا الكائن. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&) | يحصل على الترميز حسب الاسم. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int) | يحصل على الترميز حسب صفحة الترميز. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | يحصل على الترميز حسب صفحة الترميز. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | يحصل على الترميز حسب الاسم. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](../encoding/getencodings/)() | يحصل على قائمة الترميزات المعروفة. |
| int [GetHashCode](../encoding/gethashcode/)() const override | يَجْزِّئ الترميز. |
| int [GetMaxByteCount](./getmaxbytecount/)(int) override | يحصل على الحد الأقصى لعدد البايتات الممكن احتواء سلسلة بعدد أحرف معروف. |
| int [GetMaxCharCount](./getmaxcharcount/)(int) override | يحصل على الحد الأقصى لعدد الأحرف المطلوبة لفك ترميز عدد محدد من البايتات. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](../icuencoding/getpreamble/)() override | يرجع تسلسلًا من البايتات الذي يدل على الترميز (مثال: BOM). |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(**uint8_t** *, int) | يفك ترميز مخزن بايتات إلى سلسلة. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | يفك ترميز مخزن بايتات إلى سلسلة. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | يفك ترميز مخزن بايتات إلى سلسلة. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | يفك ترميز مخزن بايتات إلى سلسلة. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | يفك ترميز مخزن بايتات إلى سلسلة. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | يفك ترميز مخزن بايتات إلى سلسلة. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | يفك ترميز مخزن بايتات إلى سلسلة. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | يفك ترميز مخزن بايتات إلى سلسلة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
|  [ICUEncoding](../icuencoding/icuencoding/)(const Details::EncodingInfoInternal *) | منشئ. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل نسخة من النوع الموضح بـ targetType. مماثل لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل بيان C# lock(). استدع مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصَّصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| **bool** [operator==](../icuencoding/operator_equal_equal/)(const [ICUEncoding](../icuencoding/)\&) const | يقارن الترميزات باستخدام صفحات الترميز. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن نوع القيمة بـ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بقيمة محددة. |
| void [set_DecoderFallback](../encoding/set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | يضبط استبدال المُفكك. |
| void [set_EncoderFallback](../encoding/set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | يضبط استبدال المشفر. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n كمؤشر ضعيف (بدلاً من مشترَك). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصَّصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ فك قفل بيان C# lock(). استدع مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |

## الحقول

| الحقل | الوصف |
| --- | --- |
| static constexpr [ASCII_CODE_PAGE](./ascii_code_page/) | RTTI. |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | القيمة الافتراضية لصفحة الترميز. |

## انظر أيضًا

* فئة [ICUEncoding](../icuencoding/)
* مساحة الأسماء [System::Text](../)
* مكتبة [Aspose.Slides](../../)