---
title: Char
second_title: مرجع API ل Aspose.Slides للـ C++
description: توفر طرقًا للتلاعب بالأحرف الممثلة كوحدات شفرة UTF-16. هذا نوع ثابت لا يحتوي على خدمات للنسخ. لا ينبغي لك أبدًا إنشاء نسخ منه بأي وسيلة.
type: docs
weight: 170
url: /ar/system/char/
---
## فئة Char

توفر طرقًا للتلاعب بالأحرف الممثلة كوحدات شفرة UTF-16. هذا نوع ثابت لا يحتوي على خدمات للنسخ. لا ينبغي عليك أبدًا إنشاء نسخ منه بأي طريقة.

```cpp
class Char
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| static [String](../string/) [ConvertFromUtf32](./convertfromutf32/)(**uint32_t**) | تحوّل وحدة شفرة UTF-32 إلى نسخة من الفئة [System::String](../string/). |
| static int [ConvertToUtf32](./converttoutf32/)(char_t, char_t) | تحوّل زوج البديل UTF-16 المحدد إلى وحدة شفرة UTF-32. |
| static int [ConvertToUtf32](./converttoutf32/)(const [String](../string/)\&, int) | تحوّل قيمة حرف UTF-16 المشفر أو زوج البديل في موقع محدد داخل سلسلة إلى وحدة شفرة UTF-32. |
| static **double** [GetNumericValue](./getnumericvalue/)(char_t) | تحوّل الحرف UTF-16 المحدد إلى قيمة عددية ذات دقة مزدوجة. |
| static [Globalization::UnicodeCategory](../../system.globalization/unicodecategory/) [GetUnicodeCategory](./getunicodecategory/)(char_t) | ترجع قيمة تمثل فئة Unicode للحرف المحدد. |
| static constexpr **bool** [IsAsciiWhiteSpace](./isasciiwhitespace/)(char_t) | تحدد ما إذا كان الحرف المحدد مصنفًا كحرف مسافة بيضاء ASCII. |
| static **bool** [IsControl](./iscontrol/)(const char_t *, int) | تحدد ما إذا كان الحرف في الفهرس المحدد داخل المخزن المؤقت للحرف المحدد مصنفًا كحرف تحكم Unicode. |
| static **bool** [IsControl](./iscontrol/)(char_t) | تحدد ما إذا كان الحرف المحدد مصنفًا كحرف تحكم Unicode. |
| static **bool** [IsDigit](./isdigit/)(const char_t *, int) | تحدد ما إذا كان الحرف في الفهرس المحدد داخل المخزن المؤقت للحرف المحدد مصنفًا كرقم عشري. |
| static **bool** [IsDigit](./isdigit/)(const [String](../string/)\&, const **int32_t**) | تحدد ما إذا كان الحرف في الفهرس المحدد داخل السلسلة المحددة مصنفًا كرقم عشري. |
| static **bool** [IsDigit](./isdigit/)(char_t) | تحدد ما إذا كان الحرف المحدد مصنفًا كرقم عشري. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const [String](../string/)\&, int) | تحدد ما إذا كان الحرف في الفهرس المحدد داخل السلسلة المحددة هو وحدة شفرة UTF-16 عالية البديل. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const char_t *, int) | تحدد ما إذا كان الحرف في الفهرس المحدد داخل المخزن المؤقت للحرف المحدد هو بديل عالي. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(char_t) | تحدد ما إذا كان الحرف المحدد بديلًا عاليًا. |
| static **bool** [IsLetter](./isletter/)(const char_t *, int) | تحدد ما إذا كان الحرف في الفهرس المحدد داخل المخزن المؤقت للحرف المحدد مصنفًا كحرف Unicode. |
| static **bool** [IsLetter](./isletter/)(char_t) | تحدد ما إذا كان الحرف المحدد مصنفًا كحرف Unicode. |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(const char_t *, int) | تحدد ما إذا كان الحرف في الفهرس المحدد داخل المخزن المؤقت للحرف المحدد مصنفًا كحرف Unicode أو رقم عشري. |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(char_t) | تحدد ما إذا كان الحرف المحدد مصنفًا كحرف Unicode أو رقم عشري. |
| static **bool** [IsLower](./islower/)(const char_t *, int) | تحدد ما إذا كان الحرف في الفهرس المحدد داخل المخزن المؤقت للحرف المحدد مصنفًا كحرف صغير. |
| static **bool** [IsLower](./islower/)(char_t) | تحدد ما إذا كان الحرف المحدد مصنفًا كحرف صغير. |
| static **bool** [IsLower](./islower/)(const [String](../string/)\&, int) | تحدد ما إذا كان الحرف في الفهرس المحدد داخل السلسلة المحددة مصنفًا كحرف صغير. |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(const char_t *, int) | تحدد ما إذا كان الحرف في الفهرس المحدد داخل المخزن المؤقت للحرف المحدد هو بديل منخفض. |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(char_t) | تحدد ما إذا كان الحرف المحدد بديلًا منخفضًا. |
| static **bool** [IsNumber](./isnumber/)(const char_t *, int) | تحدد ما إذا كان الحرف في الفهرس المحدد داخل المخزن المؤقت للحرف المحدد مصنفًا كعدد. |
| static **bool** [IsNumber](./isnumber/)(char_t) | تحدد ما إذا كان الحرف المحدد مصنفًا كعدد. |
| static **bool** [IsPunctuation](./ispunctuation/)(const char_t *, int) | تحدد ما إذا كان الحرف في الفهرس المحدد داخل المخزن المؤقت للحرف المحدد مصنفًا كحرف ترقيم. |
| static **bool** [IsPunctuation](./ispunctuation/)(char_t) | تحدد ما إذا كان الحرف المحدد مصنفًا كحرف ترقيم. |
| static **bool** [IsSeparator](./isseparator/)(const char_t *, int) | تحدد ما إذا كان الحرف في الفهرس المحدد داخل المخزن المؤقت للحرف المحدد مصنفًا كحرف فاصل. |
| static **bool** [IsSeparator](./isseparator/)(char_t) | تحدد ما إذا كان الحرف المحدد مصنفًا كحرف فاصل. |
| static **bool** [IsSurrogate](./issurrogate/)(char_t) | تحدد ما إذا كان الحرف المحدد هو وحدة شفرة بديلة UTF-16. |
| static **bool** [IsSurrogate](./issurrogate/)(const [String](../string/)\&, int) | تحدد ما إذا كان الحرف في الفهرس المحدد داخل السلسلة المحددة هو وحدة شفرة بديلة UTF-16. |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(char_t, char_t) | تحدد ما إذا كان الحرفان المحددان يشكلان زوجًا بديلًا UTF-16. |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(const [String](../string/)\&, int) | تحدد ما إذا كان حرفان متتابعان في المخزن المؤقت المحدد يشكلان زوجًا بديلًا. |
| static **bool** [IsSymbol](./issymbol/)(const char_t *, int) | تحدد ما إذا كان الحرف في الفهرس المحدد داخل المخزن المؤقت للحرف المحدد مصنفًا كحرف رمز. |
| static **bool** [IsSymbol](./issymbol/)(char_t) | تحدد ما إذا كان الحرف المحدد مصنفًا كحرف رمز. |
| static **bool** [IsUpper](./isupper/)(const [String](../string/)\&, int) | تحدد ما إذا كان الحرف في الفهرس المحدد داخل السلسلة المحددة مصنفًا كحرف كبير. |
| static **bool** [IsUpper](./isupper/)(const char_t *, int) | تحدد ما إذا كان الحرف في الفهرس المحدد داخل المخزن المؤقت للحرف المحدد مصنفًا كحرف كبير. |
| static **bool** [IsUpper](./isupper/)(char_t) | تحدد ما إذا كان الحرف المحدد مصنفًا كحرف كبير. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const char_t *, int) | تحدد ما إذا كان الحرف في الفهرس المحدد داخل المخزن المؤقت للحرف المحدد مصنفًا كحرف مساحة بيضاء. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(char_t) | تحدد ما إذا كان الحرف المحدد مصنفًا كحرف مساحة بيضاء. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const [String](../string/)\&, int) | تحدد ما إذا كان الحرف في الفهرس المحدد داخل السلسلة المحددة مصنفًا كحرف مساحة بيضاء. |
| static char_t [Parse](./parse/)(const [String](../string/)\&) | تحوّل الحرف الأول والوحيد في السلسلة المحددة إلى قيمة char_t. |
| static char_t [ToLower](./tolower/)(char_t) | تحوّل الحرف المحدد إلى حرف صغير. |
| static char_t [ToLower](./tolower/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | تحوّل الحرف المحدد إلى حرف صغير. |
| static char_t [ToLowerInvariant](./tolowerinvariant/)(char_t) | تحوّل الحرف المحدد إلى حرف صغير. |
| static char_t [ToUpper](./toupper/)(char_t) | تحوّل الحرف المحدد إلى حرف كبير. |
| static char_t [ToUpper](./toupper/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | تحوّل الحرف المحدد إلى حرف كبير. |
| static char_t [ToUpperInvariant](./toupperinvariant/)(char_t) | تحوّل الحرف المحدد إلى حرف كبير. |
| static **bool** [TryParse](./tryparse/)(const [System::String](../string/)\&, char_t\&) | يحاول تحويل سلسلة تتكون من حرف واحد إلى حرف UTF-16. تنجح الدالة فقط عندما تكون السلسلة الإدخالية غير فارغة وتملك طول حرف واحد بالضبط. |

## انظر أيضًا

* المساحة الاسمية [System](../)
* المكتبة [Aspose.Slides](../../)