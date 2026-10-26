---
title: Char
second_title: مرجع API Aspose.Slides برای C++
description: متدهایی برای دستکاری کاراکترهایی که به صورت واحدهای کد UTF-16 نمایش داده می‌شوند فراهم می‌کند. این یک نوع ایستا است که سرویس نمونه ندارد. شما نباید به هیچ وجه نمونه‌ای از آن ایجاد کنید.
type: docs
weight: 170
url: /fa/system/char/
---
## کلاس Char

روش‌هایی برای دستکاری کاراکترهایی که به صورت واحدهای کد UTF-16 نمایان شده‌اند را فراهم می‌کند. این یک نوع استاتیک بدون سرویس‌های نمونه است. شما نباید به هیچ شیوه‌ای از این نوع نمونه ایجاد کنید.

```cpp
class Char
```

## متدها

| Method | Description |
| --- | --- |
| static [String](../string/) [ConvertFromUtf32](./convertfromutf32/)(**uint32_t**) | یک واحد کد UTF-32 را به یک نمونه از کلاس [System::String](../string/) تبدیل می‌کند. |
| static int [ConvertToUtf32](./converttoutf32/)(char_t, char_t) | جفت جایگزین UTF-16 مشخص شده را به واحد کد UTF-32 تبدیل می‌کند. |
| static int [ConvertToUtf32](./converttoutf32/)(const [String](../string/)\&, int) | مقدار یک حرف یا جفت جایگزین کدگذاری‌شده UTF-16 را در موقعیت مشخصی در رشته به واحد کد UTF-32 تبدیل می‌کند. |
| static **double** [GetNumericValue](./getnumericvalue/)(char_t) | حرف UTF-16 مشخص شده را به مقدار عددی شناور دو دقت **double** تبدیل می‌کند. |
| static [Globalization::UnicodeCategory](../../system.globalization/unicodecategory/) [GetUnicodeCategory](./getunicodecategory/)(char_t) | مقداری را برمی‌گرداند که دسته‌بندی Unicode حرف مشخص شده را نشان می‌دهد. |
| static constexpr **bool** [IsAsciiWhiteSpace](./isasciiwhitespace/)(char_t) | تشخیص می‌دهد که آیا حرف مشخص شده به‌عنوان یک کاراکتر فضای سفید ASCII طبقه‌بندی شده است. |
| static **bool** [IsControl](./iscontrol/)(const char_t *, int) | تشخیص می‌دهد که کاراکتر در ایندکس مشخص در بافر کاراکتر مشخص‌شده به‌عنوان کاراکتر کنترل Unicode طبقه‌بندی شده است. |
| static **bool** [IsControl](./iscontrol/)(char_t) | تشخیص می‌دهد که آیا حرف مشخص شده به‌عنوان کاراکتر کنترل Unicode طبقه‌بندی شده است. |
| static **bool** [IsDigit](./isdigit/)(const char_t *, int) | تشخیص می‌دهد که کاراکتر در ایندکس مشخص در بافر کاراکتر مشخص‌شده به‌عنوان یک رقم ده‌دهی طبقه‌بندی شده است. |
| static **bool** [IsDigit](./isdigit/)(const [String](../string/)\&, const **int32_t**) | تشخیص می‌دهد که کاراکتر در ایندکس مشخص در رشتهٔ مشخص‌شده به‌عنوان یک رقم ده‌دهی طبقه‌بندی شده است. |
| static **bool** [IsDigit](./isdigit/)(char_t) | تشخیص می‌دهد که آیا حرف مشخص شده به‌عنوان یک رقم ده‌دهی طبقه‌بندی شده است. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const [String](../string/)\&, int) | تشخیص می‌دهد که کاراکتر در ایندکس مشخص در رشتهٔ مشخص‌شده یک واحد کد بالا (high surrogate) UTF-16 است. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const char_t *, int) | تشخیص می‌دهد که کاراکتر در ایندکس مشخص در بافر کاراکتر مشخص‌شده یک high surrogate است. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(char_t) | تشخیص می‌دهد که آیا حرف مشخص شده یک high surrogate است. |
| static **bool** [IsLetter](./isletter/)(const char_t *, int) | تشخیص می‌دهد که کاراکتر در ایندکس مشخص در بافر کاراکتر مشخص‌شده به‌عنوان حرف Unicode طبقه‌بندی شده است. |
| static **bool** [IsLetter](./isletter/)(char_t) | تشخیص می‌دهد که آیا حرف مشخص شده به‌عنوان حرف Unicode طبقه‌بندی شده است. |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(const char_t *, int) | تشخیص می‌دهد که کاراکتر در ایندکس مشخص در بافر کاراکتر مشخص‌شده به‌عنوان حرف Unicode یا یک رقم ده‌دهی طبقه‌بندی شده است. |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(char_t) | تشخیص می‌دهد که آیا حرف مشخص شده به‌عنوان حرف Unicode یا یک رقم ده‌دهی طبقه‌بندی شده است. |
| static **bool** [IsLower](./islower/)(const char_t *, int) | تشخیص می‌دهد که کاراکتر در ایندکس مشخص در بافر کاراکتر مشخص‌شده به‌عنوان حرف کوچک (lower case) طبقه‌بندی شده است. |
| static **bool** [IsLower](./islower/)(char_t) | تشخیص می‌دهد که آیا حرف مشخص شده به‌عنوان حرف کوچک (lower case) طبقه‌بندی شده است. |
| static **bool** [IsLower](./islower/)(const [String](../string/)\&, int) | تشخیص می‌دهد که کاراکتر در ایندکس مشخص در رشتهٔ مشخص‌شده به‌عنوان حرف کوچک (lower case) طبقه‌بندی شده است. |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(const char_t *, int) | تشخیص می‌دهد که کاراکتر در ایندکس مشخص در بافر کاراکتر مشخص‌شده یک low surrogate است. |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(char_t) | تشخیص می‌دهد که آیا حرف مشخص شده یک low surrogate است. |
| static **bool** [IsNumber](./isnumber/)(const char_t *, int) | تشخیص می‌دهد که کاراکتر در ایندکس مشخص در بافر کاراکتر مشخص‌شده به‌عنوان یک عدد طبقه‌بندی شده است. |
| static **bool** [IsNumber](./isnumber/)(char_t) | تشخیص می‌دهد که آیا حرف مشخص شده به‌عنوان عدد طبقه‌بندی شده است. |
| static **bool** [IsPunctuation](./ispunctuation/)(const char_t *, int) | تشخیص می‌دهد که کاراکتر در ایندکس مشخص در بافر کاراکتر مشخص‌شده به‌عنوان یک علامت نقطه‌گذاری (punctuation) طبقه‌بندی شده است. |
| static **bool** [IsPunctuation](./ispunctuation/)(char_t) | تشخیص می‌دهد که آیا حرف مشخص شده به‌عنوان یک علامت نقطه‌گذاری (punctuation) طبقه‌بندی شده است. |
| static **bool** [IsSeparator](./isseparator/)(const char_t *, int) | تشخیص می‌دهد که کاراکتر در ایندکس مشخص در بافر کاراکتر مشخص‌شده به‌عنوان یک کاراکتر جداساز (separator) طبقه‌بندی شده است. |
| static **bool** [IsSeparator](./isseparator/)(char_t) | تشخیص می‌دهد که آیا حرف مشخص شده به‌عنوان یک کاراکتر جداساز (separator) طبقه‌بندی شده است. |
| static **bool** [IsSurrogate](./issurrogate/)(char_t) | تشخیص می‌دهد که آیا حرف مشخص شده یک واحد کد جایگزین UTF-16 است. |
| static **bool** [IsSurrogate](./issurrogate/)(const [String](../string/)\&, int) | تشخیص می‌دهد که کاراکتر در ایندکس مشخص در رشتهٔ مشخص‌شده یک واحد کد جایگزین UTF-16 است. |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(char_t, char_t) | تشخیص می‌دهد که آیا دو حرف مشخص‌شده برای یک جفت جایگزین UTF-16 هستند. |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(const [String](../string/)\&, int) | تشخیص می‌دهد که آیا دو کاراکتر متوالی در بافر کاراکتر مشخص‌شده یک جفت جایگزین (surrogate pair) هستند. |
| static **bool** [IsSymbol](./issymbol/)(const char_t *, int) | تشخیص می‌دهد که کاراکتر در ایندکس مشخص در بافر کاراکتر مشخص‌شده به‌عنوان یک کاراکتر نماد (symbol) طبقه‌بندی شده است. |
| static **bool** [IsSymbol](./issymbol/)(char_t) | تشخیص می‌دهد که آیا حرف مشخص شده به‌عنوان یک کاراکتر نماد (symbol) طبقه‌بندی شده است. |
| static **bool** [IsUpper](./isupper/)(const [String](../string/)\&, int) | تشخیص می‌دهد که کاراکتر در ایندکس مشخص در رشتهٔ مشخص‌شده به‌عنوان یک حرف بزرگ (upper case) طبقه‌بندی شده است. |
| static **bool** [IsUpper](./isupper/)(const char_t *, int) | تشخیص می‌دهد که کاراکتر در ایندکس مشخص در بافر کاراکتر مشخص‌شده به‌عنوان یک حرف بزرگ (upper case) طبقه‌بندی شده است. |
| static **bool** [IsUpper](./isupper/)(char_t) | تشخیص می‌دهد که آیا حرف مشخص شده به‌عنوان یک حرف بزرگ (upper case) طبقه‌بندی شده است. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const char_t *, int) | تشخیص می‌دهد که کاراکتر در ایندکس مشخص در بافر کاراکتر مشخص‌شده به‌عنوان کاراکتر فضای سفید (white space) طبقه‌بندی شده است. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(char_t) | تشخیص می‌دهد که آیا حرف مشخص شده به‌عنوان کاراکتر فضای سفید (white space) طبقه‌بندی شده است. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const [String](../string/)\&, int) | تشخیص می‌دهد که کاراکتر در ایندکس مشخص در رشتهٔ مشخص‌شده به‌عنوان کاراکتر فضای سفید (white space) طبقه‌بندی شده است. |
| static char_t [Parse](./parse/)(const [String](../string/)\&) | اولین و تنها کاراکتر رشتهٔ مشخص‌شده را به مقدار char_t تبدیل می‌کند. |
| static char_t [ToLower](./tolower/)(char_t) | حرف مشخص‌شده را به حروف کوچک تبدیل می‌کند. |
| static char_t [ToLower](./tolower/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | حرف مشخص‌شده را به حروف کوچک تبدیل می‌کند. |
| static char_t [ToLowerInvariant](./tolowerinvariant/)(char_t) | حرف مشخص‌شده را به حروف کوچک تبدیل می‌کند. |
| static char_t [ToUpper](./toupper/)(char_t) | حرف مشخص‌شده را به حروف بزرگ تبدیل می‌کند. |
| static char_t [ToUpper](./toupper/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | حرف مشخص‌شده را به حروف بزرگ تبدیل می‌کند. |
| static char_t [ToUpperInvariant](./toupperinvariant/)(char_t) | حرف مشخص‌شده را به حروف بزرگ تبدیل می‌کند. |
| static **bool** [TryParse](./tryparse/)(const [System::String](../string/)\&, char_t\&) | سعی می‌کند رشته‌ای شامل یک کاراکتر تنها را به کاراکتر UTF-16 تبدیل کند. این تابع تنها زمانی موفق می‌شود که رشتهٔ ورودی خالی نباشد و دقیقاً طول یک کاراکتر داشته باشد. |

## مراجع

* فضای نام [System](../)
* کتابخانه [Aspose.Slides](../../)