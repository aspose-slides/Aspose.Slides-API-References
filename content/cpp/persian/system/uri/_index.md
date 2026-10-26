---
title: Uri
second_title: مرجع API Aspose.Slides برای C++
description: "شناسهٔ منبع یکپارچه. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص یابند. هرگز نمونه‌ای از این نوع را روی پشته یا با عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا شکست‌های ادعا می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای ارسال به توابع به‌عنوان آرگومان استفاده کنید."
type: docs
weight: 1392
url: /fa/system/uri/
---
## Uri کلاس


Unified resource identifier. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Uri : public System::Object
```

## متدها

| Method | Description |
| --- | --- |
| static [UriHostNameType](../urihostnametype/) [CheckHostName](./checkhostname/)([String](../string/)) | نوع نام میزبان مشخص‌شده را تعیین می‌کند. |
| static **bool** [CheckSchemeName](./checkschemename/)(const [String](../string/)\&) | تعیین می‌کند آیا طرح‌وارهٔ مشخص‌شده معتبر است. |
| static **int32_t** [Compare](./compare/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, [UriComponents](../uricomponents/), [UriFormat](../uriformat/), [StringComparison](../stringcomparison/)) | اشیای [Uri](./) مشخص‌شده را با استفاده از قوانین مقایسهٔ مشخص‌شده مقایسه می‌کند. |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) override | تعیین می‌کند آیا URIهای نمایان‌شده توسط شیء جاری و شیء مشخص‌شده برابر هستند. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | اشیاء را با استفاده از معنای [Object.Equals](../object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | اشیای نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static [String](../string/) [EscapeDataString](./escapedatastring/)(const [String](../string/)\&) | یک رشته را به نمایش‌گذاری فرار شدهٔ آن تبدیل می‌کند. |
| static [String](../string/) [EscapeUriString](./escapeuristring/)(const [String](../string/)\&) | یک رشتهٔ URI را به نمایش‌گذاری فرار شدهٔ آن تبدیل می‌کند. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| static **int32_t** [FromHex](./fromhex/)(char16_t) | مقدار دهدهی یک رقم هگزادسیمال را دریافت می‌کند. |
| [String](../string/) [get_AbsolutePath](./get_absolutepath/)() const | مسیر مطلق URI را برمی‌گرداند. |
| [String](../string/) [get_AbsoluteUri](./get_absoluteuri/)() const | URI مطلق را برمی‌گرداند. |
| [String](../string/) [get_Authority](./get_authority/)() const | نام میزبان و شمارهٔ درگاه برای یک سرور را برمی‌گرداند. |
| [String](../string/) [get_DnsSafeHost](./get_dnssafehost/)() const | نام میزبان بدون فرار را برمی‌گرداند. |
| [String](../string/) [get_Fragment](./get_fragment/)() const | قسمت فرار شدهٔ URI را برمی‌گرداند. |
| [String](../string/) [get_Host](./get_host/)() const | نام میزبان را برمی‌گرداند. |
| [UriHostNameType](../urihostnametype/) [get_HostNameType](./get_hostnametype/)() const | نوع نام میزبان را برمی‌گرداند. |
| [String](../string/) [get_IdnHost](./get_idnhost/)() const | نام دامنهٔ بین‌المللی میزبان را برمی‌گرداند. |
| **bool** [get_IsAbsoluteUri](./get_isabsoluteuri/)() const | تعیین می‌کند آیا URI نمایان‌شده توسط شیء جاری مطلق است. |
| **bool** [get_IsDefaultPort](./get_isdefaultport/)() const | تعیین می‌کند آیا URI نمایان‌شده توسط شیء جاری پورت پیش‌فرض برای طرح‌وارهٔ URI دارد. |
| **bool** [get_IsFile](./get_isfile/)() const | تعیین می‌کند آیا URI نمایان‌شده توسط شیء جاری یک فایل است. |
| **bool** [get_IsLoopback](./get_isloopback/)() const | تعیین می‌کند آیا URI نمایان‌شده توسط شیء جاری به میزبان محلی ارجاع می‌دهد. |
| **bool** [get_IsUnc](./get_isunc/)() const | تعیین می‌کند آیا URI نمایان‌شده توسط شیء جاری یک مسیر UNC است. |
| [String](../string/) [get_LocalPath](./get_localpath/)() const | نمایش سیستم‌عامل از نام فایل ارجاع‌شده توسط URI نمایان‌شده توسط شیء جاری را برمی‌گرداند. |
| [String](../string/) [get_OriginalString](./get_originalstring/)() const | رشتهٔ URI که هنگام ساخت شیء جاری به سازنده پاس داده شد را برمی‌گرداند. |
| [String](../string/) [get_PathAndQuery](./get_pathandquery/)() const | مسیر مطلق و اجزای پرس‌وجو URI نمایان‌شده توسط شیء جاری را که با علامت سؤال (?) جدا شده‌اند، برمی‌گرداند. |
| **int32_t** [get_Port](./get_port/)() const | شمارهٔ درگاه URI نمایان‌شده توسط شیء جاری را برمی‌گرداند. |
| [String](../string/) [get_Query](./get_query/)() const | اطلاعات پرس‌وجو گنجانده‌شده در URI نمایان‌شده توسط شیء جاری را برمی‌گرداند. |
| [String](../string/) [get_Scheme](./get_scheme/)() const | طرح‌وارهٔ URI نمایان‌شده توسط شیء جاری را برمی‌گرداند. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [get_Segments](./get_segments/)() const | آرایه‌ای از رشته‌ها که بخش‌های مسیر URI نمایان‌شده توسط شیء جاری را شامل می‌شود را برمی‌گرداند. |
| **bool** [get_UserEscaped](./get_userescaped/)() const | تعیین می‌کند آیا رشتهٔ URI که به سازندهٔ شیء جاری پاس داده شد به‌طور کامل فرار شده بود. |
| [String](../string/) [get_UserInfo](./get_userinfo/)() const | نام کاربر، گذرواژه و سایر اطلاعات کاربری مرتبط با URI نمایان‌شده توسط شیء جاری را برمی‌گرداند. |
| [String](../string/) [GetComponents](./getcomponents/)([UriComponents](../uricomponents/), [UriFormat](../uriformat/)) const | اجزای مشخص‌شدهٔ URI نمایان‌شده توسط شیء جاری را با استفاده از فرارشدن مشخص‌شده برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | کد هش URI را دریافت می‌کند. |
| [String](../string/) [GetLeftPart](./getleftpart/)([UriPartial](../uripartial/)) | بخش مشخص‌شدهٔ URI نمایان‌شده توسط شیء جاری را برمی‌گرداند. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../object/gettype/) در C#. |
| static [String](../string/) [HexEscape](./hexescape/)(char16_t) | معادل هگزادسیمال کاراکتر مشخص‌شده را برمی‌گرداند. |
| static char16_t [HexUnescape](./hexunescape/)(const [String](../string/)\&, **int32_t**\&) | نمایش هگزادسیمال مشخص‌شدهٔ یک کاراکتر را به کاراکتر تبدیل می‌کند. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | بررسی می‌کند آیا شیء یک نمونه از نوعی که توسط targetType توصیف شده است را نمایان می‌کند. معادل عملگر 'is' در C#. |
| **bool** [IsBaseOf](./isbaseof/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) const | تعیین می‌کند آیا URI نمایان‌شده توسط شیء [Uri](./) جاری، پایهٔ URI نمایان‌شده توسط شیء [Uri](./) مشخص‌شده است. |
| static **bool** [IsHexDigit](./ishexdigit/)(char16_t) | تعیین می‌کند آیا کاراکتر مشخص‌شده یک رقم هگزادسیمال معتبر است. |
| static **bool** [IsHexEncoding](./ishexencoding/)(const [String](../string/)\&, **int32_t**) | تعیین می‌کند آیا کاراکتری در رشتهٔ مشخص‌شده در موقعیت مشخص‌شده به صورت هگزادسیمال رمزگذاری شده است. |
| **bool** [IsWellFormedOriginalString](./iswellformedoriginalstring/)() const | نشان می‌دهد آیا رشتهٔ استفاده‌شده برای ساخت این [Uri](./) به‌درستی شکل‌گیری شده است و نیاز به فرار بیشتر ندارد. |
| static **bool** [IsWellFormedUriString](./iswellformeduristring/)(const [String](../string/)\&, [UriKind](../urikind/)) | تعیین می‌کند آیا رشتهٔ مشخص‌شده یک URI صحیح شکل‌گیری است. |
| void [Lock](../object/lock/)() | قفل‌کردن عبارت lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../lockcontext/) استفاده کنید. |
| [String](../string/) [MakeRelative](./makerelative/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | تفاوت بین دو نمونهٔ [Uri](./) را تعیین می‌کند. |
| [SharedPtr](../sharedptr/)\<[Uri](./)\> [MakeRelativeUri](./makerelativeuri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | تفاوت بین URIهای نمایان‌شده توسط شیء جاری و شیء [Uri](./) مشخص‌شده را تعیین می‌کند. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../object/memberwiseclone/) در C#. امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../object/object/)([Object](../object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را می‌دهد. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | اپراتور انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را می‌دهد. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ مرجع شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | تخصص [Object::ReferenceEquals](../object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | تعداد مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگوی قالب را به اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش داده و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| [String](../string/) [ToString](./tostring/)() const override | نمایش رشته‌ای URI نمایان‌شده توسط شیء جاری را برمی‌گرداند. |
| static **bool** [TryCreate](./trycreate/)(const [String](../string/)\&, [UriKind](../urikind/), [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | یک شیء [Uri](./) که URI مشخص‌شده را نمایان می‌کند می‌سازد؛ یک آرگومان نوع URI را مشخص می‌کند. |
| static **bool** [TryCreate](./trycreate/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&, [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | یک [Uri](./) شیء را از شیء [Uri](./) که پایهٔ URI را نمایان می‌کند و نمایش رشته‌ای URI نسبی می‌سازد. |
| static **bool** [TryCreate](./trycreate/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | یک [Uri](./) شیء را از پایهٔ URI و URI نسبی مشخص‌شده می‌سازد. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | ساختار typeof([System.Object](../object/)) در C# را پیاده‌سازی می‌کند. |
| static [String](../string/) [UnescapeDataString](./unescapedatastring/)(const [String](../string/)\&) | رشتهٔ فرار شدهٔ مشخص‌شده را حذف فرار می‌کند. |
| void [Unlock](../object/unlock/)() | قفل‌برداری عبارت lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهدار [LockContext](../lockcontext/) استفاده کنید. |
|  [Uri](./uri/)(const [String](../string/)\&) | یک [Uri](./) شیء که URI مشخص‌شده را نمایان می‌کند می‌سازد. |
|  [Uri](./uri/)(const [String](../string/)\&, **bool**) | یک [Uri](./) شیء که URI مشخص‌شده را نمایان می‌کند می‌سازد؛ یک آرگومان تعیین می‌کند آیا URI باید فرار شود. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&, **bool**) | یک [Uri](./) شیء را از شیء [Uri](./) که پایهٔ URI را نمایان می‌کند و نمایش رشته‌ای URI نسبی می‌سازد؛ یک آرگومان تعیین می‌کند آیا URI باید فرار شود. |
|  [Uri](./uri/)(const [String](../string/)\&, [UriKind](../urikind/)) | یک [Uri](./) شیء که URI مشخص‌شده را نمایان می‌کند می‌سازد؛ یک آرگومان نوع URI را مشخص می‌کند. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&) | یک [Uri](./) شیء را از پایهٔ URI و URI نسبی مشخص‌شده می‌سازد. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | یک [Uri](./) شیء را از پایهٔ URI و URI نسبی مشخص‌شده می‌سازد. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## فیلدها

| Field | Description |
| --- | --- |
| static [SchemeDelimiter](./schemedelimiter/) | کاراکترهایی را که طرح‌وارهٔ پروتکل ارتباطی را از بخش آدرس [Uri](./) جدا می‌کنند، تعیین می‌کند. |
| static [UriSchemeFile](./urischemefile/) | مشخص می‌کند که [Uri](./) یک اشاره‌گر به یک فایل است. |
| static [UriSchemeFtp](./urischemeftp/) | مشخص می‌کند که [Uri](./) از طریق پروتکل انتقال فایل (FTP) دسترسی دارد. |
| static [UriSchemeGopher](./urischemegopher/) | مشخص می‌کند که [Uri](./) از طریق پروتکل Gopher دسترسی دارد. |
| static [UriSchemeHttp](./urischemehttp/) | مشخص می‌کند که [Uri](./) از طریق پروتکل انتقال ابرمتن (HTTP) دسترسی دارد. |
| static [UriSchemeHttps](./urischemehttps/) | مشخص می‌کند که [Uri](./) از طریق پروتکل امن انتقال ابرمتن (HTTPS) دسترسی دارد. |
| static [UriSchemeMailto](./urischememailto/) | مشخص می‌کند که [Uri](./) یک آدرس ایمیل است و از طریق پروتکل ساده انتقال ایمیل (SMTP) دسترسی دارد. |
| static [UriSchemeNetPipe](./urischemenetpipe/) | مشخص می‌کند که [Uri](./) از طریق طرح‌واره NetPipe که توسط [Windows](../../system.windows/) Communication Foundation استفاده می‌شود، دسترسی دارد. |
| static [UriSchemeNetTcp](./urischemenettcp/) | مشخص می‌کند که [Uri](./) از طریق طرح‌واره NetTcp که توسط [Windows](../../system.windows/) Communication Foundation استفاده می‌شود، دسترسی دارد. |
| static [UriSchemeNews](./urischemenews/) | مشخص می‌کند که [Uri](./) یک گروه خبری اینترنتی است و از طریق پروتکل انتقال اخبار شبکه (NNTP) دسترسی دارد. |
| static [UriSchemeNntp](./urischemenntp/) | مشخص می‌کند که [Uri](./) یک گروه خبری اینترنتی است و از طریق پروتکل انتقال اخبار شبکه (NNTP) دسترسی دارد. |

## یادداشت‌ها



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
این مثال کد خروجی زیر را تولید می‌کند:
AbsolutePath: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
AbsoluteUri: https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
Authority: docs.codeporting.com
DnsSafeHost: docs.codeporting.com
Fragment:
Host: docs.codeporting.com
IdnHost: docs.codeporting.com
LocalPath: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
OriginalString: https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
PathAndQuery: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
Port: 443
Query:
Scheme: https
*/
```

## موارد مرتبط

* کلاس [Object](../object/)
* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)