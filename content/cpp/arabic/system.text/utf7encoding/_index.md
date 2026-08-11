---
title: UTF7Encoding
second_title: مرجع API لـ Aspose.Slides للـ C++
description: "ترميز UTF-7. يجب تخصيص كائنات هذه الفئة باستخدام الدالة System::MakeObject() فقط. لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام عامل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل و/أو أخطاء assertion. دائمًا غلف هذه الفئة في مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كوسيطة."
type: docs
weight: 365
url: /ar/system.text/utf7encoding/
---
## UTF7Encoding class

ترميز UTF-7. يجب تخصيص كائنات هذه الفئة باستخدام دالة [System::MakeObject()](../../system/makeobject/) فقط. لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام عامل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل أو أخطاء التأكيد. دائمًا غلف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كوسيطة.

```cpp
class UTF7Encoding : public System::Text::Encoding
```

## Methods

| الطريقة | الوصف |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | ينسخ كائن الترميز. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | يحول البايتات بين ترميزين. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | يحول البايتات بين ترميزين. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | يقارن مع الكائن. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع على نمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يقوم بمحاكاة مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaNانين متساويتين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يقوم بمحاكاة مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaNانين متساويتين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](../encoding/get_ascii/)() | يحصل على ترميز ASCII. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](../encoding/get_bigendianunicode/)() | يحصل على كائن ترميز Unicode القياسي ذو النهاية الكبيرة. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](../encoding/get_bigendianutf32/)() | يحصل على كائن ترميز UTF-32 القياسي ذو النهاية الكبيرة. |
| virtual [String](../../system/string/) [get_BodyName](../encoding/get_bodyname/)() | يحصل على اسم الترميز المتوافق مع جسم عميل البريد. |
| virtual int [get_CodePage](../encoding/get_codepage/)() | يحصل على معرّف صفحة الشفرات [Windows](../../system.windows/). |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](../encoding/get_decoderfallback/)() const | يحصل على بديل المفكّ. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](../encoding/get_default/)() | يحصل على الترميز الافتراضي. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](../encoding/get_encoderfallback/)() const | يحصل على بديل المشفر. |
| virtual [String](../../system/string/) [get_EncodingName](../encoding/get_encodingname/)() | يحصل على اسم الترميز القابل للقراءة البشرية. |
| virtual [String](../../system/string/) [get_HeaderName](../encoding/get_headername/)() | يحصل على اسم الترميز المتوافق مع رأس عميل البريد. |
| virtual **bool** [get_IsBrowserDisplay](../encoding/get_isbrowserdisplay/)() | يتحقق مما إذا كان يمكن استخدام الترميز في المتصفح لعرض المحتوى. |
| virtual **bool** [get_IsBrowserSave](../encoding/get_isbrowsersave/)() | يتحقق مما إذا كان يمكن استخدام الترميز في المتصفح لحفظ المحتوى. |
| virtual **bool** [get_IsMailNewsDisplay](../encoding/get_ismailnewsdisplay/)() | يتحقق مما إذا كان يمكن استخدام الترميز في عميل البريد لعرض المحتوى. |
| virtual **bool** [get_IsMailNewsSave](../encoding/get_ismailnewssave/)() | يتحقق مما إذا كان يمكن استخدام الترميز في عميل البريد لحفظ المحتوى. |
| **bool** [get_IsReadOnly](../encoding/get_isreadonly/)() | يتحقق مما إذا كان الترميز للقراءة فقط. |
| virtual **bool** [get_IsSingleByte](../encoding/get_issinglebyte/)() | يتحقق مما إذا كان الترميز بايتًا واحدًا. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](../encoding/get_latin1/)() | يحصل على ترميز Latin1. للاستخدام الداخلي. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](../encoding/get_unicode/)() | يحصل على كائن ترميز Unicode القياسي. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](../encoding/get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](../encoding/get_utf7/)() | يحصل على كائن ترميز UTF-7 القياسي. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](../encoding/get_utf8/)() | يحصل على كائن ترميز UTF-8 القياسي. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](../encoding/get_utf8unmarked/)() | للاستخدام الداخلي فقط، لاستخدامه من قبل مكتبات الفئة: غير معلم وغير صالح للتحقق من الإدخال. |
| virtual [String](../../system/string/) [get_WebName](../encoding/get_webname/)() | يحصل على اسم الترميز المتوافق مع IANA. |
| virtual int [get_WindowsCodePage](../encoding/get_windowscodepage/)() | يحصل على معرّف صفحة الشفرات [Windows](../../system.windows/). |
| int [GetByteCount](./getbytecount/)(const char_t *, int) override | يحصل على عدد الأحرف المطلوبة لتشفير مخزن مؤقت من الأحرف. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | يحصل على عدد الأحرف المطلوبة لتشفير مخزن مؤقت من الأحرف. |
| virtual int [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | يحصل على عدد الأحرف المطلوبة لتشفير مخزن مؤقت من الأحرف. |
| int [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | يحصل على عدد الأحرف المطلوبة لتشفير مخزن مؤقت من الأحرف. |
| virtual int [GetByteCount](./getbytecount/)(const [String](../../system/string/)\&) | يحصل على عدد الأحرف المطلوبة لتشفير سلسلة. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | يحصل على عدد الأحرف المطلوبة لتشفير مخزن مؤقت من الأحرف. |
| virtual int [GetByteCount](./getbytecount/)(const char_t *, int) | يحصل على عدد الأحرف المطلوبة لتشفير مخزن مؤقت من الأحرف. |
| int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) override | يحصل على البايتات الناتجة عن تشفير مخزن مؤقت من الأحرف. |
| int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) override | يحصل على البايتات الناتجة عن تشفير مخزن مؤقت من الأحرف. |
| int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) override | يحصل على البايتات الناتجة عن تشفير مخزن مؤقت من الأحرف. |
| virtual int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | يحصل على البايتات الناتجة عن تشفير مخزن مؤقت من الأحرف. |
| virtual int [GetBytes](./getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | يحصل على البايتات الناتجة عن تشفير مخزن مؤقت من الأحرف. |
| int [GetBytes](./getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | يحصل على البايتات الناتجة عن تشفير مخزن مؤقت من الأحرف. |
| virtual int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | يحصل على البايتات الناتجة عن تشفير مخزن مؤقت من الأحرف. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const [String](../../system/string/)\&) | يحصل على البايتات الناتجة عن تشفير مخزن مؤقت من الأحرف. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | يحصل على البايتات الناتجة عن تشفير مخزن مؤقت من الأحرف. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | يحصل على البايتات الناتجة عن تشفير مخزن مؤقت من الأحرف. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | يحصل على البايتات الناتجة عن تشفير مخزن مؤقت من الأحرف. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | يحصل على البايتات الناتجة عن تشفير مخزن مؤقت من الأحرف. |
| virtual int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) | يحصل على البايتات الناتجة عن تشفير مخزن مؤقت من الأحرف. |
| int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) override | يحصل على عدد الأحرف المطلوبة لفك تشفير مخزن مؤقت من البايتات. |
| int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) override | يحصل على عدد الأحرف المطلوبة لفك تشفير مخزن مؤقت من البايتات. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | يحصل على عدد الأحرف المطلوبة لفك تشفير مخزن مؤقت من البايتات. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | يحصل على عدد الأحرف المطلوبة لفك تشفير مخزن مؤقت من البايتات. |
| virtual int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) | يحصل على عدد الأحرف المطلوبة لفك تشفير مخزن مؤقت من البايتات. |
| int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) override | يحصل على الأحرف الناتجة عن فك تشفير مخزن مؤقت من البايتات. |
| int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) override | يحصل على الأحرف الناتجة عن فك تشفير مخزن مؤقت من البايتات. |
| virtual int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | يحصل على الأحرف الناتجة عن فك تشفير مخزن مؤقت من البايتات. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | يحصل على الأحرف الناتجة عن فك تشفير مخزن مؤقت من البايتات. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | يحصل على الأحرف الناتجة عن فك تشفير مخزن مؤقت من البايتات. |
| virtual int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) | يحصل على الأحرف الناتجة عن فك تشفير مخزن مؤقت من البايتات. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| [DecoderPtr](../../system/decoderptr/) [GetDecoder](./getdecoder/)() override | يحصل على فكّ يُعيد توجيه الطلبات إلى هذا الكائن. |
| [EncoderPtr](../../system/encoderptr/) [GetEncoder](./getencoder/)() override | يحصل على مشفر يُعيد توجيه الطلبات إلى هذا الكائن. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&) | يحصل على الترميز بحسب الاسم. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int) | يحصل على الترميز بحسب صفحة الشفرات. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | يحصل على الترميز بحسب صفحة الشفرات. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | يحصل على الترميز بحسب الاسم. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](../encoding/getencodings/)() | يحصل على قائمة الترميزات المعروفة. |
| int [GetHashCode](./gethashcode/)() const override | يحصل على رمز تجزئة الترميز. |
| int [GetMaxByteCount](./getmaxbytecount/)(int) override | يحصل على الحد الأقصى لعدد البايتات المطلوبة لتشفير عدد محدد من الأحرف. |
| int [GetMaxCharCount](./getmaxcharcount/)(int) override | يحصل على الحد الأقصى لعدد الأحرف المطلوبة لفك تشفير عدد محدد من البايتات. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](../encoding/getpreamble/)() | يرجع تسلسلًا من البايتات يُشير إلى الترميز (مثلاً BOM). |
| [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) override | يفك ترميز مخزن مؤقت من البايتات إلى سلسلة. |
| virtual [String](../../system/string/) [GetString](./getstring/)(**uint8_t** *, int) | يفك ترميز مخزن مؤقت من البايتات إلى سلسلة. |
| [String](../../system/string/) [GetString](./getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | يفك ترميز مخزن مؤقت من البايتات إلى سلسلة. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | يفك ترميز مخزن مؤقت من البايتات إلى سلسلة. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | يفك ترميز مخزن مؤقت من البايتات إلى سلسلة. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | يفك ترميز مخزن مؤقت من البايتات إلى سلسلة. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | يفك ترميز مخزن مؤقت من البايتات إلى سلسلة. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | يفك ترميز مخزن مؤقت من البايتات إلى سلسلة. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | يفك ترميز مخزن مؤقت من البايتات إلى سلسلة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. نظير لمشغل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويمكّن بناء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويمكّن بناء نسخ فرعية. |
| **bool** [operator==](./operator_equal_equal/)(const [UTF7Encoding](./)\&) const | يقارن معلمات الترميزات. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن المرجع لكائن نوع القيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدد المراجع المشتركة بالقيمة المحددة. |
| void [set_DecoderFallback](../encoding/set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | يضبط بديل المفكّ. |
| void [set_EncoderFallback](../encoding/set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | يضبط بديل المشفر. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب الـ n't كإشارة ضعيفة (بدلاً من مشتركة). يتيح تبديل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المراجع المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدد المراجع المشتركة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عدد المراجع المشتركة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
|  [UTF7Encoding](./utf7encoding/)() | منشئ. |
|  [UTF7Encoding](./utf7encoding/)(**bool**) | منشئ. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدد المراجع الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عدد المراجع الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## Fields

| الحقل | الوصف |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | قيمة صفحة الشفرات الافتراضية. |
| static constexpr [UTF7_CODE_PAGE](./utf7_code_page/) | العدد السحري المستخدم بواسطة [Windows](../../system.windows/) لهوية صفحة شفرات UTF-7. |

## راجع أيضًا

* الفئة [Encoding](../encoding/)
* مساحة الأسماء [System::Text](../)
* مكتبة [Aspose.Slides](../../)