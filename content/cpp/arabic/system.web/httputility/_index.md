---
title: HttpUtility
second_title: مرجع API لـ Aspose.Slides للـ C++
description: فئة خدمة تقوم بترميز وفك ترميز أجزاء عنوان URL إلى ومن أجزاء الهروب السداسي عشرية.
type: docs
weight: 40
url: /ar/system.web/httputility/
---
## فئة HttpUtility

فئة خدمة تقوم بترميز وفك ترميز أجزاء عناوين URL إلى ومن أجزاء هروب سداسي عشرية.

```cpp
class HttpUtility : public System::Object
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالة C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين على الرغم من أن معيار IEC 60559:1989 ينص على أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين على الرغم من أن معيار IEC 60559:1989 ينص على أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثلة لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). تمكّن تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثلة لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| static [String](../../system/string/) [HtmlDecode](./htmldecode/)(const [String](../../system/string/)\&) | يفك ترميز مقطع HTML. |
| static void [HtmlDecode](./htmldecode/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | يفك ترميز مقطع HTML. |
| static [String](../../system/string/) [HtmlEncode](./htmlencode/)(const [String](../../system/string/)\&) | يشفّر مقطع HTML. |
| static [String](../../system/string/) [HtmlEncode](./htmlencode/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | يشفّر مقطع HTML. |
| static void [HtmlEncode](./htmlencode/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | يشفّر مقطع HTML. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثيلاً للنوع الموصوف بـ targetType. مماثل لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل بيان C# lock(). استدعِه مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثلة لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). تمكّن من استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يتهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ أي شيء، بل يهيئ كائنًا جديدًا ويُتيح بناء النسخ للصفوف الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء، بل يهيئ كائنًا جديدًا ويُتيح بناء النسخ للصفوف الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط الن-المؤشر في القالب إلى إشارة ضعيفة (بدلاً من مشتركة). يسمح بتبديل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثلة لطريقة C# [Object.ToString()](../../system/object/tostring/). تمكّن من تحويل الكائنات المخصصة إلى سلسلة نصية. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل بيان C# lock(). استدعِه مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| static [String](../../system/string/) [UrlDecode](./urldecode/)([String](../../system/string/)) | يفك ترميز مقطع URI من سلسلة. |
| static [String](../../system/string/) [UrlDecode](./urldecode/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>) | يفك ترميز مقطع URI من سلسلة. |
| static [String](../../system/string/) [UrlDecode](./urldecode/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | يفك ترميز مقطع URI من مصفوفة بايتات. |
| static [String](../../system/string/) [UrlDecode](./urldecode/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | يفك ترميز مقطع URI من مصفوفة بايتات. |
| static [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [UrlDecodeToBytes](./urldecodetobytes/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | يفك ترميز مقطع URI من مصفوفة بايتات. |
| static [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [UrlDecodeToBytes](./urldecodetobytes/)(const [String](../../system/string/)\&) | يفك ترميز مقطع URI من سلسلة بايتات. |
| static [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [UrlDecodeToBytes](./urldecodetobytes/)(const [String](../../system/string/)\&, const [System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | يفك ترميز مقطع URI من سلسلة. |
| static [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [UrlDecodeToBytes](./urldecodetobytes/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | يفك ترميز مقطع URI من مصفوفة بايتات. |
| static [String](../../system/string/) [UrlEncode](./urlencode/)([String](../../system/string/)) | يشفّر مقطع URI. |
| static [String](../../system/string/) [UrlEncode](./urlencode/)([String](../../system/string/), const [System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | يشفّر مقطع URI. |
| static [String](../../system/string/) [UrlEncode](./urlencode/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | يشفّر مقطع URI. |
| static [String](../../system/string/) [UrlEncode](./urlencode/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | يشفّر مقطع URI. |
| static [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [UrlEncodeToBytes](./urlencodetobytes/)(const [String](../../system/string/)\&) | يشفّر مقطع URI. |
| static [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [UrlEncodeToBytes](./urlencodetobytes/)(const [String](../../system/string/)\&, const [System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | يشفّر مقطع URI. |
| static [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [UrlEncodeToBytes](./urlencodetobytes/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | يشفّر مقطع URI. |
| static [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [UrlEncodeToBytes](./urlencodetobytes/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | يشفّر مقطع URI. |
| static [String](../../system/string/) [UrlEncodeUnicode](./urlencodeunicode/)(const [String](../../system/string/)\&) | يشفّر مقطع URI باستخدام Unicode. |
| static [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [UrlEncodeUnicodeToBytes](./urlencodeunicodetobytes/)(const [String](../../system/string/)\&) | يشفّر مقطع URI باستخدام Unicode. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## راجع أيضًا

* الفئة [Object](../../system/object/)
* النطاق [System::Web](../)
* المكتبة [Aspose.Slides](../../)