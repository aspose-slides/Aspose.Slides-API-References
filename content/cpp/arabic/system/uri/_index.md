---
title: Uri
second_title: مرجع API لـ Aspose.Slides للـ C++
description: "معرف الموارد الموحد. يجب تخصيص كائنات هذه الفئة باستخدام دالة System::MakeObject() فقط. لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام عامل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل أو أخطاء التأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر System::SmartPtr واستخدام هذا المؤشر لتمريره إلى الدوال كوسيط."
type: docs
weight: 1392
url: /ar/system/uri/
---
## فئة Uri

معرف الموارد الموحد. يجب تخصيص كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../makeobject/) فقط. لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام عامل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل أو أخطاء التأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](../smartptr/) واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class Uri : public System::Object
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| static [UriHostNameType](../urihostnametype/) [CheckHostName](./checkhostname/)([String](../string/)) | يحدد نوع اسم المضيف المحدد. |
| static **bool** [CheckSchemeName](./checkschemename/)(const [String](../string/)\&) | يحدد ما إذا كان المخطط المحدد صالحًا. |
| static **int32_t** [Compare](./compare/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, [UriComponents](../uricomponents/), [UriFormat](../uriformat/), [StringComparison](../stringcomparison/)) | يقارن كائنات [Uri](./) المحددة باستخدام قواعد المقارنة المحددة. |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) override | يحدد ما إذا كانت عناوين URI التي تمثلها الكائنات الحالية والمحددة متساوية. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static [String](../string/) [EscapeDataString](./escapedatastring/)(const [String](../string/)\&) | يحول سلسلة إلى تمثيلها المشفر. |
| static [String](../string/) [EscapeUriString](./escapeuristring/)(const [String](../string/)\&) | يحول سلسلة URI إلى تمثيلها المشفر. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | للأغراض الداخلية فقط. |
| static **int32_t** [FromHex](./fromhex/)(char16_t) | يحصل على القيمة العشرية لرقم سداسي عشري. |
| [String](../string/) [get_AbsolutePath](./get_absolutepath/)() const | يعيد المسار المطلق للـ URI. |
| [String](../string/) [get_AbsoluteUri](./get_absoluteuri/)() const | يعيد الـ URI المطلق. |
| [String](../string/) [get_Authority](./get_authority/)() const | يعيد اسم المضيف ورقم المنفذ لخادم. |
| [String](../string/) [get_DnsSafeHost](./get_dnssafehost/)() const | يعيد اسم مضيف غير مشفر. |
| [String](../string/) [get_Fragment](./get_fragment/)() const | يعيد جزء الـ URI المشفر. |
| [String](../string/) [get_Host](./get_host/)() const | يعيد اسم المضيف. |
| [UriHostNameType](../urihostnametype/) [get_HostNameType](./get_hostnametype/)() const | يعيد نوع اسم المضيف. |
| [String](../string/) [get_IdnHost](./get_idnhost/)() const | يعيد اسم نطاق دولي للمضيف. |
| **bool** [get_IsAbsoluteUri](./get_isabsoluteuri/)() const | يحدد ما إذا كان الـ URI الممثَل بواسطة الكائن الحالي مطلقًا. |
| **bool** [get_IsDefaultPort](./get_isdefaultport/)() const | يحدد ما إذا كان الـ URI الممثَل بواسطة الكائن الحالي يحتوي على المنفذ الافتراري للمخطط الخاص بالـ URI. |
| **bool** [get_IsFile](./get_isfile/)() const | يحدد ما إذا كان الـ URI الممثَل بواسطة الكائن الحالي هو ملف. |
| **bool** [get_IsLoopback](./get_isloopback/)() const | يحدد ما إذا كان الـ URI الممثَل بواسطة الكائن الحالي يشير إلى مضيف محلي. |
| **bool** [get_IsUnc](./get_isunc/)() const | يحدد ما إذا كان الـ URI الممثَل بواسطة الكائن الحالي هو مسار UNC. |
| [String](../string/) [get_LocalPath](./get_localpath/)() const | يعيد تمثيل نظام التشغيل لاسم الملف المشار إليه بواسطة الـ URI الممثَل بواسطة الكائن الحالي. |
| [String](../string/) [get_OriginalString](./get_originalstring/)() const | يعيد سلسلة الـ URI التي تم تمريرها إلى المُنشئ عند إنشاء الكائن الحالي. |
| [String](../string/) [get_PathAndQuery](./get_pathandquery/)() const | يعيد مسارًا مطلقًا ومكونات الاستعلام للـ URI الممثَل بواسطة الكائن الحالي مفصولة بعلامة استفهام (؟). |
| **int32_t** [get_Port](./get_port/)() const | يعيد رقم المنفذ للـ URI الممثَل بواسطة الكائن الحالي. |
| [String](../string/) [get_Query](./get_query/)() const | يعيد معلومات الاستعلام المتضمنة في الـ URI الممثَل بواسطة الكائن الحالي. |
| [String](../string/) [get_Scheme](./get_scheme/)() const | يعيد المخطط للـ URI الممثَل بواسطة الكائن الحالي. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [get_Segments](./get_segments/)() const | يعيد مصفوفة من السلاسل التي تحتوي على أقسام المسار للـ URI الممثَل بـ الكائن الحالي. |
| **bool** [get_UserEscaped](./get_userescaped/)() const | يحدد ما إذا كانت سلسلة الـ URI التي تم تمريرها إلى مُنشئ الكائن الحالي مشفرة بالكامل. |
| [String](../string/) [get_UserInfo](./get_userinfo/)() const | يعيد اسم المستخدم، كلمة المرور ومعلومات المستخدم الأخرى المرتبطة بالـ URI الممثَل بـ الكائن الحالي. |
| [String](../string/) [GetComponents](./getcomponents/)([UriComponents](../uricomponents/), [UriFormat](../uriformat/)) const | يعيد المكونات المحددة للـ URI الممثَل بـ الكائن الحالي باستخدام الترميز المحدد. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | يحصل على قيمة التجزئة للـ URI. |
| [String](../string/) [GetLeftPart](./getleftpart/)([UriPartial](../uripartial/)) | يعيد الجزء المحدد من الـ URI الممثَل بـ الكائن الحالي. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../object/gettype/). |
| static [String](../string/) [HexEscape](./hexescape/)(char16_t) | يعيد ما يعادل الحرف المحدد في نظام سداسي عشري. |
| static char16_t [HexUnescape](./hexunescape/)(const [String](../string/)\&, **int32_t**\&) | يحول التمثيل السداسي العشري المحدد لحرف إلى حرف. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثيلًا للنوع الموصوف بـ targetType. نظير مشغل C# 'is'. |
| **bool** [IsBaseOf](./isbaseof/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) const | يحدد ما إذا كان الـ URI الممثَل بـ الكائن [Uri](./) الحالي هو أساس الـ URI الممثَل بـ الكائن [Uri](./) المحدد. |
| static **bool** [IsHexDigit](./ishexdigit/)(char16_t) | يحدد ما إذا كان الحرف المحدد يمثل رقمًا سداسيًا صالحًا. |
| static **bool** [IsHexEncoding](./ishexencoding/)(const [String](../string/)\&, **int32_t**) | يحدد ما إذا كان حرف في السلسلة المحددة عند الموضع المحدد مشفرًا سداسيًا. |
| **bool** [IsWellFormedOriginalString](./iswellformedoriginalstring/)() const | يشير إلى ما إذا كانت السلسلة المستخدمة لإنشاء هذا [Uri](./) مُشكّلة بشكل صحيح ولا تحتاج إلى تشفير إضافي. |
| static **bool** [IsWellFormedUriString](./iswellformeduristring/)(const [String](../string/)\&, [UriKind](../urikind/)) | يحدد ما إذا كانت السلسلة المحددة URI مُشكّلة بشكل صحيح. |
| void [Lock](../object/lock/)() | ينفذ قفل بيان C# lock(). استدعِ مباشرةً أو استخدم كائن الحراسة [LockContext](../lockcontext/). |
| [String](../string/) [MakeRelative](./makerelative/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | يحدد الفرق بين مثيلتين من [Uri](./). |
| [SharedPtr](../sharedptr/)\<[Uri](./)\> [MakeRelativeUri](./makerelativeuri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | يحدد الفرق بين عناوين URI الممثلة بـ الكائن الحالي والكائن [Uri](./) المحدد. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../object/object/)() | ينشئ كائنًا. يتهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../object/object/)([Object](../object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، بل يتهيئ كائنًا جديدًا ويسمح بنسخ البُنى الفرعية. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يتهيئ كائنًا جديدًا ويسمح بنسخ البُنى الفرعية. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن نوع القيمة بـ nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | يضبط المتغيّر القالبي n مؤشرًا ضعيفًا (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| [String](../string/) [ToString](./tostring/)() const override | يعيد التمثيل النصي للـ URI الممثَل بـ الكائن الحالي. |
| static **bool** [TryCreate](./trycreate/)(const [String](../string/)\&, [UriKind](../urikind/), [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | ينشئ كائن [Uri](./) يمثل الـ URI المحدد؛ تُحدد الوسيطة نوع الـ URI. |
| static **bool** [TryCreate](./trycreate/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&, [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | ينشئ كائن [Uri](./) من الكائن [Uri](./) المحدد الذي يمثل الـ URI الأساسي والتمثيل النصي للـ URI النسبي. |
| static **bool** [TryCreate](./trycreate/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | ينشئ كائن [Uri](./) من الـ URI الأساسي والـ URI النسبي المحددين. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | ينفذ بناء C# typeof([System.Object](../object/)). |
| static [String](../string/) [UnescapeDataString](./unescapedatastring/)(const [String](../string/)\&) | يفك تشفير السلسلة المشفرة المحددة. |
| void [Unlock](../object/unlock/)() | ينفذ إلغاء قفل بيان C# lock(). استدعِ مباشرةً أو استخدم كائن الحراسة [LockContext](../lockcontext/). |
|  [Uri](./uri/)(const [String](../string/)\&) | ينشئ كائن [Uri](./) يمثل الـ URI المحدد. |
|  [Uri](./uri/)(const [String](../string/)\&, **bool**) | ينشئ كائن [Uri](./) يمثل الـ URI المحدد؛ تُحدد الوسيطة ما إذا كان يجب تشفير الـ URI. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&, **bool**) | ينشئ كائن [Uri](./) من الكائن [Uri](./) المحدد الذي يمثل الـ URI الأساسي والتمثيل النصي للـ URI النسبي؛ تُحدد الوسيطة ما إذا كان يجب تشفير الـ URI. |
|  [Uri](./uri/)(const [String](../string/)\&, [UriKind](../urikind/)) | ينشئ كائن [Uri](./) يمثل الـ URI المحدد؛ تُحدد الوسيطة نوع الـ URI. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&) | ينشئ كائن [Uri](./) من الـ URI الأساسي والـ URI النسبي المحددين. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | ينشئ كائن [Uri](./) من الـ URI الأساسي والـ URI النسبي المحددين. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../object/~object/)() | يدمر الكائن. يحذف جميع هياكل البيانات الداخلية. |

## الحقول

| الحقل | الوصف |
| --- | --- |
| static [SchemeDelimiter](./schemedelimiter/) | يحدد الأحرف التي تفصل مخطط بروتوكول الاتصال عن جزء العنوان من الـ [Uri](./). |
| static [UriSchemeFile](./urischemefile/) | يحدد أن الـ [Uri](./) هو مؤشر إلى ملف. |
| static [UriSchemeFtp](./urischemeftp/) | يحدد أن الـ [Uri](./) يتم الوصول إليه عبر بروتوكول نقل الملفات. |
| static [UriSchemeGopher](./urischemegopher/) | يحدد أن الـ [Uri](./) يتم الوصول إليه عبر بروتوكول Gopher. |
| static [UriSchemeHttp](./urischemehttp/) | يحدد أن الـ [Uri](./) يتم الوصول إليه عبر بروتوكول نقل النص الفائق. |
| static [UriSchemeHttps](./urischemehttps/) | يحدد أن الـ [Uri](./) يتم الوصول إليه عبر بروتوكول نقل النص الفائق الآمن. |
| static [UriSchemeMailto](./urischememailto/) | يحدد أن الـ [Uri](./) هو عنوان بريد إلكتروني ويتم الوصول إليه عبر بروتوكول نقل البريد البسيط. |
| static [UriSchemeNetPipe](./urischemenetpipe/) | يحدد أن الـ [Uri](./) يتم الوصول إليه عبر مخطط NetPipe المستخدم من قبل [Windows](../../system.windows/) Communication Foundation. |
| static [UriSchemeNetTcp](./urischemenettcp/) | يحدد أن الـ [Uri](./) يتم الوصول إليه عبر مخطط NetTcp المستخدم من قبل [Windows](../../system.windows/) Communication Foundation. |
| static [UriSchemeNews](./urischemenews/) | يحدد أن الـ [Uri](./) هو مجموعة أخبار إنترنت ويتم الوصول إليها عبر بروتوكول نقل أخبار الشبكة. |
| static [UriSchemeNntp](./urischemenntp/) | يحدد أن الـ [Uri](./) هو مجموعة أخبار إنترنت ويتم الوصول إليها عبر بروتوكول نقل أخبار الشبكة. |

## ملاحظات

```cpp
#include "system/smart_ptr.h"
#include "system/uri.h"
#include <iostream>

int main()
{
  const auto uri = System::MakeObject<System::Uri>(u"https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/");

std::cout <<
  "AbsolutePath: " << uri->get_AbsolutePath() << std::endl <<
  "AbsoluteUri: " << uri->get_AbsoluteUri() << std::endl <<
  "Authority: " << uri->get_Authority() << std::endl <<
  "DnsSafeHost: " << uri->get_DnsSafeHost() << std::endl <<
  "Fragment: " << uri->get_Fragment() << std::endl <<
  "Host: " << uri->get_Host() << std::endl <<
  "IdnHost: " << uri->get_IdnHost() << std::endl <<
  "LocalPath: " << uri->get_LocalPath() << std::endl <<
  "OriginalString: " << uri->get_OriginalString() << std::endl <<
  "PathAndQuery: " << uri->get_PathAndQuery() << std::endl <<
  "Port: " << uri->get_Port() << std::endl <<
  "Query: " << uri->get_Query() << std::endl <<
  "Scheme: " << uri->get_Scheme() << std::endl;

  return 0;
}
/*
هذا المثال البرمجي ينتج الإخراج التالي:
المسار المطلق: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
الرابط المطلق: https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
السلطة: docs.codeporting.com
المضيف الآمن DNS: docs.codeporting.com
الجزء:
المضيف: docs.codeporting.com
المضيف IDN: docs.codeporting.com
المسار المحلي: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
السلسلة الأصلية: https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
المسار والاستعلام: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
المنفذ: 443
الاستعلام:
المخطط: https
*/
```

## انظر أيضًا

* الفئة [Object](../object/)
* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)