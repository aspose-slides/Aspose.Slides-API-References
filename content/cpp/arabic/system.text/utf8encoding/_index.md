---
title: UTF8Encoding
second_title: Aspose.Slides لـ C++ مرجع API
description: "ترميز UTF-8. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject(). لا تقم بإنشاء مثيل من هذا النوع على المكدس أو باستخدام العامل new، لأن ذلك سيؤدي إلى أخطاء تشغيلية و/أو أعطال في التأكيد. دائمًا قم بلف هذه الفئة في مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كوسيط."
type: docs
weight: 378
url: /ar/system.text/utf8encoding/
---
## UTF8Encoding فئة

UTF-8 encoding. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class UTF8Encoding : public System::Text::ICUEncoding
```

## الأساليب

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | ينسخ كائن الترميز. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | يحول البايتات بين ترميزين. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | يحول البايتات بين ترميزين. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | يقارن مع كائن. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالة C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | محاكاة مقارنة نقطية عائمة بأسلوب C# حيث يُعتبر NaNانان متساويين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN غير مساوي لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | محاكاة مقارنة نقطية مزدوجة بأسلوب C# حيث يُعتبر NaNانان متساويين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN غير مساوي لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للاستخدام الداخلي فقط. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](../encoding/get_ascii/)() | يحصل على ترميز ASCII. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](../encoding/get_bigendianunicode/)() | يحصل على كائن ترميز Unicode القياسي ذو النهاية الكبيرة. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](../encoding/get_bigendianutf32/)() | يحصل على كائن ترميز UTF-32 القياسي ذو النهاية الكبيرة. |
| virtual [String](../../system/string/) [get_BodyName](../encoding/get_bodyname/)() | يحصل على اسم ترميز متوافق مع جسم عميل البريد. |
| virtual int [get_CodePage](../encoding/get_codepage/)() | يحصل على معرّف صفحة الترميز [Windows](../../system.windows/). |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](../encoding/get_decoderfallback/)() const | يحصل على بديلة فك الترميز. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](../encoding/get_default/)() | يحصل على الترميز الافتراضي. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](../encoding/get_encoderfallback/)() const | يحصل على بديلة المشفر. |
| virtual [String](../../system/string/) [get_EncodingName](../encoding/get_encodingname/)() | يحصل على اسم الترميز المقروء للإنسان. |
| virtual [String](../../system/string/) [get_HeaderName](../encoding/get_headername/)() | يحصل على اسم ترميز متوافق مع رأس عميل البريد. |
| virtual **bool** [get_IsBrowserDisplay](../encoding/get_isbrowserdisplay/)() | يتحقق مما إذا كان يمكن استخدام الترميز في المتصفح لعرض المحتوى. |
| virtual **bool** [get_IsBrowserSave](../encoding/get_isbrowsersave/)() | يتحقق مما إذا كان يمكن استخدام الترميز في المتصفح لحفظ المحتوى. |
| virtual **bool** [get_IsMailNewsDisplay](../encoding/get_ismailnewsdisplay/)() | يتحقق مما إذا كان يمكن استخدام الترميز في برنامج البريد لعرض المحتوى. |
| virtual **bool** [get_IsMailNewsSave](../encoding/get_ismailnewssave/)() | يتحقق مما إذا كان يمكن استخدام الترميز في برنامج البريد لحفظ المحتوى. |
| **bool** [get_IsReadOnly](../encoding/get_isreadonly/)() | يتحقق مما إذا كان الترميز للقراءة فقط. |
| virtual **bool** [get_IsSingleByte](../encoding/get_issinglebyte/)() | يتحقق مما إذا كان الترميز بايتًا واحدًا. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](../encoding/get_latin1/)() | يحصل على ترميز Latin1. للاستخدام الداخلي. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](../encoding/get_unicode/)() | يحصل على كائن ترميز Unicode القياسي. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](../encoding/get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](../encoding/get_utf7/)() | يحصل على كائن ترميز UTF-7 القياسي. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](../encoding/get_utf8/)() | يحصل على كائن ترميز UTF-8 القياسي. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](../encoding/get_utf8unmarked/)() | للاستخدام الداخلي فقط، لاستخدامه من قبل مكتبات الفئة: غير معلم وغير يتحقق من صحة الإدخال. |
| virtual [String](../../system/string/) [get_WebName](../encoding/get_webname/)() | يحصل على اسم ترميز متوافق مع IANA. |
| virtual int [get_WindowsCodePage](../encoding/get_windowscodepage/)() | يحصل على معرّف صفحة الترميز [Windows](../../system.windows/). |
| int [GetByteCount](../icuencoding/getbytecount/)(const char_t *, int) override | يحصل على عدد الأحرف المطلوبة لترميز مخزن الأحرف. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | RTTI. |
| int [GetByteCount](../icuencoding/getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(const [String](../../system/string/)\&) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(const char_t *, int) | RTTI. |
| int [GetBytes](../icuencoding/getbytes/)(const char_t *, int, **uint8_t** *, int) override | يحصل على البايتات الناتجة عن ترميز مخزن الأحرف. |
| virtual int [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | يحصل على البايتات الناتجة عن ترميز مخزن الأحرف. |
| virtual int [GetBytes](../icuencoding/getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | يحصل على البايتات الناتجة عن ترميز مخزن الأحرف. |
| int [GetBytes](../icuencoding/getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | يحصل على البايتات الناتجة عن ترميز مخزن الأحرف. |
| virtual int [GetBytes](../icuencoding/getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | يحصل على البايتات الناتجة عن ترميز مخزن الأحرف. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const [String](../../system/string/)\&) | يحصل على البايتات الناتجة عن ترميز مخزن الأحرف. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | يحصل على البايتات الناتجة عن ترميز مخزن الأحرف. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | يحصل على البايتات الناتجة عن ترميز مخزن الأحرف. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | يحصل على البايتات الناتجة عن ترميز مخزن الأحرف. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | يحصل على البايتات الناتجة عن ترميز مخزن الأحرف. |
| virtual int [GetBytes](../icuencoding/getbytes/)(const char_t *, int, **uint8_t** *, int) | يحصل على البايتات الناتجة عن ترميز مخزن الأحرف. |
| int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) override | يحصل على عدد الأحرف المطلوبة لفك ترميز مخزن البايتات. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | يحصل على عدد الأحرف المطلوبة لفك ترميز مخزن البايتات. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | يحصل على عدد الأحرف المطلوبة لفك ترميز مخزن البايتات. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) | يحصل على عدد الأحرف المطلوبة لفك ترميز مخزن البايتات. |
| int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) override | يحصل على الأحرف الناتجة عن فك ترميز مخزن البايتات. |
| virtual int [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | يحصل على الأحرف الناتجة عن فك ترميز مخزن البايتات. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | يحصل على الأحرف الناتجة عن فك ترميز مخزن البايتات. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | يحصل على الأحرف الناتجة عن فك ترميز مخزن البايتات. |
| virtual int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) | يحصل على الأحرف الناتجة عن فك ترميز مخزن البايتات. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على هيكل عداد المرجع المرتبط بالكائن. |
| [DecoderPtr](../../system/decoderptr/) [GetDecoder](../icuencoding/getdecoder/)() override | يحصل على محلل يعيد توجيه الطلبات إلى هذا الكائن. |
| [EncoderPtr](../../system/encoderptr/) [GetEncoder](../icuencoding/getencoder/)() override | يحصل على مشفر يعيد توجيه الطلبات إلى هذا الكائن. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&) | يحصل على الترميز بالاسم. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int) | يحصل على الترميز بواسطة صفحة الترميز. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | يحصل على الترميز بواسطة صفحة الترميز. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | يحصل على الترميز بالاسم. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](../encoding/getencodings/)() | يحصل على قائمة الترميزات المعروفة. |
| int [GetHashCode](./gethashcode/)() const override | يحصل على رمز التجزئة للترميز. |
| int [GetMaxByteCount](./getmaxbytecount/)(int) override | يحصل على الحد الأقصى للبايتات اللازمة لترميز عدد محدد من الأحرف. |
| int [GetMaxCharCount](./getmaxcharcount/)(int) override | يحصل على الحد الأقصى للأحرف اللازمة لفك ترميز عدد محدد من البايتات. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](./getpreamble/)() override | يحصل على بادئة صفحة الترميز. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(**uint8_t** *, int) | يفك ترميز مخزن من البايتات إلى سلسلة. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | يفك ترميز مخزن من البايتات إلى سلسلة. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | يفك ترميز مخزن من البايتات إلى سلسلة. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | يفك ترميز مخزن من البايتات إلى سلسلة. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | يفك ترميز مخزن من البايتات إلى سلسلة. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | يفك ترميز مخزن من البايتات إلى سلسلة. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | يفك ترميز مخزن من البايتات إلى سلسلة. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | يفك ترميز مخزن من البايتات إلى سلسلة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تماثل استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
|  [ICUEncoding](../icuencoding/icuencoding/)(const Details::EncodingInfoInternal *) | منشئ. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. تماثل عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل بيان C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تماثل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح نسخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ كل هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| **bool** [operator==](./operator_equal_equal/)(const [UTF8Encoding](./)\&) const | يقارن معلمات الترميزات. |
| **bool** [operator==](../icuencoding/operator_equal_equal/)(const [ICUEncoding](../icuencoding/)\&) const | يقارن الترميزات باستخدام صفحات الترميز. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائنًا من نوع القيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_DecoderFallback](../encoding/set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | يضبط بديلة المفكك. |
| void [set_EncoderFallback](../encoding/set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | يضبط بديلة المشفر. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط المتغيّر القالب رقم n إلى مؤشر ضعيف (بدلاً من المشترك). يسمح بتغيير المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم مؤشرات ذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم مؤشرات ذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تماثل طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ فك قفل بيان C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
|  [UTF8Encoding](./utf8encoding/)() | منشئ. |
|  [UTF8Encoding](./utf8encoding/)(**bool**) | منشئ. |
|  [UTF8Encoding](./utf8encoding/)(**bool**, **bool**) | منشئ. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم مؤشرات ذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم مؤشرات ذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر كل هياكل البيانات الداخلية. |

## الحقول

| Field | Description |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | القيمة الافتراضية لصفحة الترميز. |
| static constexpr [UTF8_CODE_PAGE](./utf8_code_page/) | معلومات RTTI. |

## انظر أيضًا

* فئة [ICUEncoding](../icuencoding/)
* مساحة الاسم [System::Text](../)
* مكتبة [Aspose.Slides](../../)