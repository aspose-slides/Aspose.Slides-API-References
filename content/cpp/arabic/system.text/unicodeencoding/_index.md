---
title: UnicodeEncoding
second_title: Aspose.Slides للغة C++ مرجع API
description: "ترميز Unicode. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject() . لا تقم أبدًا بإنشاء مثيل من هذا النوع على المكدس أو باستخدام معامل new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل و/أو أخطاء التأكيد. دائمًا قم بلف هذه الفئة في مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 339
url: /ar/system.text/unicodeencoding/
---
## UnicodeEncoding فئة

Unicode encoding. يجب تخصيص كائنات هذه الفئة فقط باستخدام دالة [System::MakeObject()](../../system/makeobject/). لا تقم أبدًا بإنشاء نسخة من هذا النوع على المكدس أو باستخدام معامل new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل و/أو أخطاء التأكيد. دائمًا غلف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class UnicodeEncoding : public System::Text::ICUEncoding
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | ينسخ كائن الترميز. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | يحول البايتات بين ترميزين. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | يحول البايتات بين ترميزين. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | يقارن الترميزات. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaNين متساويتين رغم أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaNين متساويتين رغم أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](../encoding/get_ascii/)() | يُرجع ترميز ASCII. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](../encoding/get_bigendianunicode/)() | يحصل على كائن الترميز Unicode القياسي كبير-النهاية. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](../encoding/get_bigendianutf32/)() | يحصل على كائن الترميز UTF-32 القياسي كبير-النهاية. |
| virtual [String](../../system/string/) [get_BodyName](../encoding/get_bodyname/)() | يحصل على اسم الترميز المتوافق مع جسم عميل البريد. |
| virtual int [get_CodePage](../encoding/get_codepage/)() | يحصل على معرف صفحة الترميز [Windows](../../system.windows/). |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](../encoding/get_decoderfallback/)() const | يحصل على fallback للمُفكك. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](../encoding/get_default/)() | يحصل على الترميز الافتراضي. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](../encoding/get_encoderfallback/)() const | يحصل على fallback للمرمّز. |
| virtual [String](../../system/string/) [get_EncodingName](../encoding/get_encodingname/)() | يحصل على اسم الترميز القابل للقراءة البشرية. |
| virtual [String](../../system/string/) [get_HeaderName](../encoding/get_headername/)() | يحصل على اسم الترميز المتوافق مع رأس عميل البريد. |
| virtual **bool** [get_IsBrowserDisplay](../encoding/get_isbrowserdisplay/)() | يتحقق ما إذا كان يمكن استخدام الترميز في المتصفح لعرض المحتوى. |
| virtual **bool** [get_IsBrowserSave](../encoding/get_isbrowsersave/)() | يتحقق ما إذا كان يمكن استخدام الترميز في المتصفح لحفظ المحتوى. |
| virtual **bool** [get_IsMailNewsDisplay](../encoding/get_ismailnewsdisplay/)() | يتحقق ما إذا كان يمكن استخدام الترميز في عميل البريد لعرض المحتوى. |
| virtual **bool** [get_IsMailNewsSave](../encoding/get_ismailnewssave/)() | يتحقق ما إذا كان يمكن استخدام الترميز في عميل البريد لحفظ المحتوى. |
| **bool** [get_IsReadOnly](../encoding/get_isreadonly/)() | يتحقق ما إذا كان الترميز للقراءة فقط. |
| virtual **bool** [get_IsSingleByte](../encoding/get_issinglebyte/)() | يتحقق ما إذا كان الترميز بايتًا واحدًا. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](../encoding/get_latin1/)() | يحصل على ترميز Latin1. للاستخدام الداخلي فقط. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](../encoding/get_unicode/)() | يحصل على كائن الترميز Unicode القياسي. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](../encoding/get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](../encoding/get_utf7/)() | يحصل على كائن الترميز UTF-7 القياسي. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](../encoding/get_utf8/)() | يحصل على كائن الترميز UTF-8 القياسي. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](../encoding/get_utf8unmarked/)() | للاستخدام الداخلي فقط، من قبل مكتبات الفئة: غير معلم وغير صالح للتحقق من الإدخال. |
| virtual [String](../../system/string/) [get_WebName](../encoding/get_webname/)() | يحصل على اسم الترميز المتوافق مع IANA. |
| virtual int [get_WindowsCodePage](../encoding/get_windowscodepage/)() | يحصل على معرف صفحة الترميز [Windows](../../system.windows/). |
| int [GetByteCount](../icuencoding/getbytecount/)(const char_t *, int) override | يحصل على عدد الأحرف المطلوبة لترميز مخزن أحرف. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | RTTI. |
| int [GetByteCount](../icuencoding/getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(const [String](../../system/string/)\&) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(const char_t *, int) | RTTI. |
| int [GetBytes](../icuencoding/getbytes/)(const char_t *, int, **uint8_t** *, int) override | يحصل على البايتات الناتجة عن ترميز مخزن أحرف. |
| virtual int [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | يحصل على البايتات الناتجة عن ترميز مخزن أحرف. |
| virtual int [GetBytes](../icuencoding/getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | يحصل على البايتات الناتجة عن ترميز مخزن أحرف. |
| int [GetBytes](../icuencoding/getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | يحصل على البايتات الناتجة عن ترميز مخزن أحرف. |
| virtual int [GetBytes](../icuencoding/getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | يحصل على البايتات الناتجة عن ترميز مخزن أحرف. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const [String](../../system/string/)\&) | يحصل على البايتات الناتجة عن ترميز مخزن أحرف. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | يحصل على البايتات الناتجة عن ترميز مخزن أحرف. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | يحصل على البايتات الناتجة عن ترميز مخزن أحرف. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | يحصل على البايتات الناتجة عن ترميز مخزن أحرف. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | يحصل على البايتات الناتجة عن ترميز مخزن أحرف. |
| virtual int [GetBytes](../icuencoding/getbytes/)(const char_t *, int, **uint8_t** *, int) | يحصل على البايتات الناتجة عن ترميز مخزن أحرف. |
| int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) override | يحصل على عدد الأحرف المطلوبة لفك ترميز مخزن بايتات. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | يحصل على عدد الأحرف المطلوبة لفك ترميز مخزن بايتات. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | يحصل على عدد الأحرف المطلوبة لفك ترميز مخزن بايتات. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) | يحصل على عدد الأحرف المطلوبة لفك ترميز مخزن بايتات. |
| int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) override | يحصل على الأحرف الناتجة عن فك ترميز مخزن بايتات. |
| virtual int [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | يحصل على الأحرف الناتجة عن فك ترميز مخزن بايتات. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | يحصل على الأحرف الناتجة عن فك ترميز مخزن بايتات. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | يحصل على الأحرف الناتجة عن فك ترميز مخزن بايتات. |
| virtual int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) | يحصل على الأحرف الناتجة عن فك ترميز مخزن بايتات. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| [DecoderPtr](../../system/decoderptr/) [GetDecoder](../icuencoding/getdecoder/)() override | يحصل على مُفكك يوجه الطلبات إلى هذا الكائن. |
| [EncoderPtr](../../system/encoderptr/) [GetEncoder](../icuencoding/getencoder/)() override | يحصل على مرمّز يوجه الطلبات إلى هذا الكائن. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&) | يحصل على الترميز بالاسم. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int) | يحصل على الترميز بصفحة الترميز. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | يحصل على الترميز بصفحة الترميز. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | يحصل على الترميز بالاسم. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](../encoding/getencodings/)() | يحصل على قائمة الترميزات المعروفة. |
| int [GetHashCode](./gethashcode/)() const override | يجري تجزئة للترميز. |
| int [GetMaxByteCount](./getmaxbytecount/)(int) override | يحصل على الحد الأقصى لعدد البايتات اللازمة لترميز عدد محدد من الأحرف. |
| int [GetMaxCharCount](./getmaxcharcount/)(int) override | يحصل على الحد الأقصى لعدد الأحرف اللازمة لفك ترميز عدد محدد من البايتات. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](./getpreamble/)() override | يعود بتسلسل البايتات الذي يحدد الترميز (مثل BOM). |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(**uint8_t** *, int) | يفك ترميز مخزن البايتات إلى سلسلة. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | يفك ترميز مخزن البايتات إلى سلسلة. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | يفك ترميز مخزن البايتات إلى سلسلة. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | يفك ترميز مخزن البايتات إلى سلسلة. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | يفك ترميز مخزن البايتات إلى سلسلة. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | يفك ترميز مخزن البايتات إلى سلسلة. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | يفك ترميز مخزن البايتات إلى سلسلة. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | يفك ترميز مخزن البايتات إلى سلسلة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مشابه لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
|  [ICUEncoding](../icuencoding/icuencoding/)(const Details::EncodingInfoInternal *) | منشئ. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثيلاً لنوع يصفه targetType. مشابه لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مشابه لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح نسخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بنسخ الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بنسخ الفئات الفرعية. |
| **bool** [operator==](./operator_equal_equal/)(const [UnicodeEncoding](./)\&) const | يقارن الترميزات بحسب صفحات الترميز والعلامات. |
| **bool** [operator==](../icuencoding/operator_equal_equal/)(const [ICUEncoding](../icuencoding/)\&) const | يقارن الترميزات باستخدام صفحات الترميز. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعًا لكائن نوع القيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ينقص عدد مراجع المشاركة بالقيمة المحددة. |
| void [set_DecoderFallback](../encoding/set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | يضبط fallback للمُفكك. |
| void [set_EncoderFallback](../encoding/set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | يضبط fallback للمرمّز. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب الـ n كضعف إشارة (بدلاً من مشترك). يتيح تبديل المؤشرات في الحاويات إلى وضع الضعف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المراجع المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المراجع المشتركة. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المراجع المشتركة. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مشابه لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
|  [UnicodeEncoding](./unicodeencoding/)() | منشئ. |
|  [UnicodeEncoding](./unicodeencoding/)(**bool**, **bool**) | منشئ. |
|  [UnicodeEncoding](./unicodeencoding/)(**bool**, **bool**, **bool**) | منشئ. |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد الضعيفة. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد الضعيفة. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |

## الحقول

| الحقل | الوصف |
| --- | --- |
| static constexpr [BIG_UNICODE_CODE_PAGE](./big_unicode_code_page/) | رقم صفحة الترميز big endian. |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | قيمة صفحة الترميز الافتراضية. |
| static constexpr [UNICODE_CODE_PAGE](./unicode_code_page/) | رقم صفحة الترميز little endian. |

## انظر أيضًا

* فئة [ICUEncoding](../icuencoding/)
* مساحة الاسم [System::Text](../)
* مكتبة [Aspose.Slides](../../)