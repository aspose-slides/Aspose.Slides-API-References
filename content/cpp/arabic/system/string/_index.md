---
title: String
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "فئة String تُستخدم عبر المكتبة. هي بديل لـ C# System.String عند ترجمة الشيفرة. لأسباب تحسين الأداء، لا تُعتبر فئة فرعية من Object. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم أبداً فئة System::SmartPtr لإدارة كائنات هذا النوع."
type: docs
weight: 1275
url: /ar/system/string/
---
## فئة String


[String](./) فئة تُستخدم عبر المكتبة. هي بديل لـ C# [System.String](./) عند ترجمة الشيفرة. لأسباب تحسين الأداء، لا تُعتبر فئة فرعية من [Object](../object/). يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم فئة [System::SmartPtr](../smartptr/) لإدارة كائنات من هذا النوع.

```cpp
class String
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
|  [ASPOSECPP_VALUE_TYPE_IMPLEMENTS_INTERFACES](./asposecpp_value_type_implements_interfaces/)() | [String](./) هو نوع قيمة على جانب C++ والذي ينفذ ضمنيًا (بدون وراثة) بعض الواجهات. |
| const UChar * [begin](./begin/)() const | إرجاع مؤشر إلى بداية المخزن الفعلي للسلسلة. لا يعيد تخصيص أي شيء. لا يضمن أن يكون المخزن مُنتهي بـ null. |
| [String](./) [Clone](./clone/)() const | ينشئ نسخة من السلسلة الحالية. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**) | يقارن جزءين فرعيين باستخدام مقارنة أقل-مساواة-أكبر. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | يقارن جزءين فرعيين باستخدام مقارنة أقل-مساواة-أكبر. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | يقارن سلسلتين باستخدام مقارنة أقل-مساواة-أكبر. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) | يقارن سلسلتين باستخدام مقارنة أقل-مساواة-أكبر. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**) | يقارن سلسلتين باستخدام مقارنة أقل-مساواة-أكبر. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | يقارن سلسلتين باستخدام مقارنة أقل-مساواة-أكبر. |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, const [String](./)\&) | يقارن سلسلتين باستخدام مقارنة أقل-مساواة-أكبر في وضع الترتيب. |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, int, const [String](./)\&, int, int) | يقارن سلسلتين باستخدام مقارنة أقل-مساواة-أكبر في وضع الترتيب. |
| int [CompareTo](./compareto/)(const [String](./)\&) const | يقارن سلسلتين بنمط 'أقل-مساوية-أكثر'. يستخدم الثقافة الحالية. |
| static [String](./) [Concat](./concat/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&) | يقوم بدمج السلاسل. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&) | يقوم بدمج السلاسل. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&) | يقوم بدمج السلاسل. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&, const [String](./)\&) | يقوم بدمج السلاسل. |
| **bool** [Contains](./contains/)(const [String](./)\&) const | يتحقق ما إذا كانت str جزءًا من السلسلة الحالية. |
| **bool** [Contains](./contains/)(char16_t) const | يتحقق مما إذا كانت السلسلة تحتوي على الحرف المحدد. |
| static [String](./) [Copy](./copy/)(const [String](./)\&) | ينشئ نسخة من السلسلة. |
| void [CopyTo](./copyto/)(int, const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) const | ينسخ أحرف السلسلة إلى عناصر مصفوفة موجودة. لا يتم تعديل الحجم. |
| const UChar * [end](./end/)() const | إرجاع مؤشر إلى نهاية المخزن الفعلي للسلسلة. لا يعيد تخصيص أي شيء. لا يضمن أن يكون المخزن مُنتهي بـ null. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&) const | يتحقق ما إذا كانت السلسلة تنتهي بالجزء الفرعي المحدد. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | يتحقق ما إذا كانت السلسلة تنتهي بالجزء الفرعي المحدد. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | يتحقق ما إذا كانت السلسلة تنتهي بالجزء الفرعي المحدد. |
| **bool** [Equals](./equals/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | [String](./) مقارنة مساواة. يتم دعم عدة أوضاع مقدمة بواسطة تعداد StringComparison. |
| **bool** [Equals](./equals/)(const [String](./)\&) const | [String](./) مقارنة مساواة. يستخدم وضع المقارنة [System::StringComparison::Ordinal](../stringcomparison/). |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&) | يقارن مساواة سلسلتين باستخدام وضع المقارنة Ordial. |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | يقارن مساواة سلسلتين. |
| int [FastToAscii](./fasttoascii/)(char, int) const | يحاول تحويل [String](./) إلى سلسلة ASCII. |
| static [String](./) [Format](./format/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, const [String](./)\&, const Args\&...) | يقوم بتنسيق السلسلة على نمط C#. |
| static [String](./) [Format](./format/)(std::nullptr_t, const [String](./)\&, const Args\&...) | يقوم بتنسيق السلسلة على نمط C#. |
| static [String](./) [Format](./format/)(std::nullptr_t, const char16_t(&), const Args\&...) | يقوم بتنسيق السلسلة على نمط C#. |
| static [String](./) [Format](./format/)(const [String](./)\&, const Args\&...) | يقوم بتنسيق السلسلة على نمط C#. |
| static [String](./) [Format](./format/)(const [String](./)\&, const [System::ArrayPtr](../arrayptr/)\<T\>\&) | يقوم بتنسيق السلسلة على نمط C#. |
| static [String](./) [FromAscii](./fromascii/)(const char *) | ينشئ [String](./) من سلسلة ASCII. |
| static [String](./) [FromAscii](./fromascii/)(const char *, int) | ينشئ [String](./) من سلسلة ASCII. |
| static [String](./) [FromAscii](./fromascii/)(const std::string\&) | ينشئ [String](./) من سلسلة ASCII. |
| static [String](./) [FromUtf16](./fromutf16/)(const std::u16string\&) | ينشئ [String](./) من سلسلة utf16. |
| static [String](./) [FromUtf32](./fromutf32/)(const **uint32_t** *, **int32_t**) | ينشئ [String](./) من سلسلة utf32. |
| static [String](./) [FromUtf8](./fromutf8/)(const char *) | ينشئ [String](./) من سلسلة utf8. |
| static [String](./) [FromUtf8](./fromutf8/)(const char *, int) | ينشئ [String](./) من سلسلة utf8. |
| static [String](./) [FromUtf8](./fromutf8/)(const **uint8_t** *) | ينشئ [String](./) من سلسلة utf8. |
| static [String](./) [FromUtf8](./fromutf8/)(const std::string\&) | ينشئ [String](./) من سلسلة utf8. |
| static [String](./) [FromWCS](./fromwcs/)(const std::wstring\&) | ينشئ [String](./) من widestring. |
| int [get_Length](./get_length/)() const | يحصل على طول السلسلة. |
| int [GetHashCode](./gethashcode/)() const | يحسب تجزئة السلسلة المحتواة. تم تنفيذها في ICU، ولا تتطابق مع التجزئات في C#. |
| int [IndexOf](./indexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | بحث أمامي عن جزء فرعي. |
| int [IndexOf](./indexof/)(char_t, int) const | بحث أمامي عن حرف. |
| int [IndexOf](./indexof/)(char_t, int, int) const | بحث أمامي عن حرف داخل جزء فرعي. |
| int [IndexOf](./indexof/)(const [String](./)\&, int) const | بحث أمامي عن جزء فرعي. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | بحث أمامي عن جزء فرعي. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) const | بحث أمامي عن جزء فرعي. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int) const | بحث أمامي عن جزء فرعي. |
| int [IndexOfAny](./indexofany/)(char_t, int) const | بحث أمامي عن حرف. |
| int [IndexOfAny](./indexofany/)(const [String](./)\&, int) const | وبالتالي يبحث عن جميع أحرف str في هذه السلسلة. إذا تم العثور على الحرف الأول، تُرجع موضعه، وإلا يبحث عن الحرف الثاني وهكذا. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | يبحث عن أي من الأحرف الممرَّة عبر السلسلة كاملة. يقارن أول حرف في السلسلة بكل الأحرف في anyOf، ثم الثاني وهكذا. يرجع فهرس أول مطابقة. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | يبحث عن أي من الأحرف الممرَّة عبر الجزء الفرعي. يقارن أول حرف في السلسلة بكل الأحرف في anyOf، ثم الثاني وهكذا. يرجع فهرس أول مطابقة. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | يبحث عن أي من الأحرف الممرَّة عبر الجزء الفرعي. يقارن أول حرف في السلسلة بكل الأحرف في anyOf، ثم الثاني وهكذا. يرجع فهرس أول مطابقة. |
| [String](./) [Insert](./insert/)(int, const [String](./)\&) const | يدرج جزءًا فرعيًا في الموضع المحدد. |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const | يتحقق ما إذا كان كائن السلسلة من النوع المحدد بواسطة [TypeInfo](../typeinfo/) الممرَّ. |
| **bool** [IsAsciiString](./isasciistring/)() const | يشير إلى ما إذا كان [String](./) يحتوي على رموز ASCII فقط. |
| **bool** [IsEmpty](./isempty/)() const | يتحقق ما إذا كانت السلسلة غير null وفارغة. |
| **bool** [IsNormalized](./isnormalized/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | يتحقق ما إذا كانت السلسلة Unicode مُنظمة باستخدام صيغة التسوية المحددة. |
| **bool** [IsNull](./isnull/)() const | يتحقق ما إذا كانت السلسلة تعتبر null. [String](./) هي null فقط إذا بُنيت عبر المنشئ [String()](./string/)، أو نُقلت، أو نُسخت أو عيّنت من سلسلة null أو نُدِّي طريقة [reset()](./reset/). |
| **bool** [IsNullOrEmpty](./isnullorempty/)() const | يتحقق ما إذا كانت السلسلة فارغة أو تعتبر null. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [String](./)\&) | يتحقق ما إذا كانت السلسلة الممرَّة null أو فارغة. |
| static **bool** [IsNullOrWhiteSpace](./isnullorwhitespace/)(const [String](./)\&) | يشير إلى ما إذا كانت السلسلة المحددة null أو فارغة أو تتكون فقط من مسافات بيضاء. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, int, int) | يجمع المصفوفة باستخدام السلسلة كفاصل. |
| static [String](./) [Join](./join/)(const [String](./)\&, const System::Details::ArrayView\<[String](./)\>\&, int, int) | يجمع المصفوفة باستخدام السلسلة كفاصل. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](./)\>\>\&) | يجمع المصفوفة باستخدام السلسلة كفاصل. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\&) | يجمع المصفوفة باستخدام السلسلة كفاصل. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int) const | بحث خلفي عن جزء فرعي. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | بحث خلفي عن جزء فرعي. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | بحث خلفي عن جزء فرعي. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, int, [StringComparison](../stringcomparison/)) const | بحث خلفي عن جزء فرعي. |
| int [LastIndexOf](./lastindexof/)(char_t) const | بحث خلفي عن حرف. |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**) const | بحث خلفي عن حرف. |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**, **int32_t**) const | بحث خلفي عن حرف. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | يبحث عن أي من الأحرف الممرَّة عبر السلسلة كاملة بصورة عكسية. يقارن آخر حرف في السلسلة بكل الأحرف في anyOf، ثم السابق وهكذا. يرجع فهرس أول مطابقة تم العثور عليها. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | يبحث عن أي من الأحرف الممرَّة عبر الجزء الفرعي بصورة عكسية. يقارن آخر حرف في السلسلة بكل الأحرف في anyOf، ثم السابق وهكذا. يرجع فهرس أول مطابقة تم العثور عليها. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | يبحث عن أي من الأحرف الممرَّة عبر الجزء الفرعي بصورة عكسية. يقارن آخر حرف في السلسلة بكل الأحرف في anyOf، ثم السابق وهكذا. يرجع فهرس أول مطابقة تم العثور عليها. |
| [String](./) [Normalize](./normalize/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | يقوم بتطبيع السلسلة Unicode باستخدام صيغة التسوية المحددة. |
|  [operator ReadOnlySpan< char16_t >](./operator_readonlyspan_less_char16_t__greater/)() const | يحول السلسلة إلى مقطع قراءة فقط. |
| **bool** [operator!=](./operator_not_equal/)(const [String](./)\&) const | عامل مقارنة غير مساواة. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | يتحقق ما إذا كانت السلسلة ليست null. يطبق نفس منطق استدعاء [IsNull()](./isnull/). |
| [String](./) [operator+](./operator_plus/)(const [String](./)\&) const | عامل دمج [String](./). |
| [String](./) [operator+](./operator_plus/)(const T\&) const | دمج [String](./) مع حرف نصي ثابت أو مؤشر سلسلة حرفية. |
| [String](./) [operator+](./operator_plus/)(char_t) const | يضيف حرفًا إلى نهاية السلسلة. |
| [String](./) [operator+](./operator_plus/)(int) const | يضيف تمثيل قيمة عددية صحيحة كسلسلة إلى نهاية السلسلة. |
| [String](./) [operator+](./operator_plus/)(**uint32_t**) const | يضيف تمثيل قيمة عددية غير موقعة كسلسلة إلى نهاية السلسلة. |
| [String](./) [operator+](./operator_plus/)(**double**) const | يضيف تمثيل قيمة عددية عائمة كسلسلة إلى نهاية السلسلة. |
| [String](./) [operator+](./operator_plus/)(**int64_t**) const | يضيف تمثيل قيمة عددية صحيحة كسلسلة إلى نهاية السلسلة. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | يضيف تمثيل كائن من نوع مرجعي كسلسلة إلى نهاية السلسلة. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | يضيف تمثيل كائن من نوع مرجعي كسلسلة إلى نهاية السلسلة. |
| [String](./) [operator+](./operator_plus/)(T) const | يضيف تمثيل قيمة منطقية كسلسلة إلى نهاية السلسلة. |
| [String](./)\& [operator+=](./operator_plus_equal/)(char_t) | عامل إسناد دمج. |
| [String](./)\& [operator+=](./operator_plus_equal/)(const [String](./)\&) | عامل إسناد دمج. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**double**) | عامل إسناد دمج. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint8_t**) | عامل إسناد دمج. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int16_t**) | عامل إسناد التجميع. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint16_t**) | عامل إسناد التجميع. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int32_t**) | عامل إسناد التجميع. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint32_t**) | عامل إسناد التجميع. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int64_t**) | عامل إسناد التجميع. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint64_t**) | عامل إسناد التجميع. |
| [String](./)\& [operator+=](./operator_plus_equal/)(T) | عامل إسناد التجميع. |
| **bool** [operator<](./operator_less/)(const [String](./)\&) const | يقارن ترتيب السلاسل. |
| [String](./)\& [operator=](./operator_equal/)(const [String](./)\&) | عامل الإسناد. |
| [String](./)\& [operator=](./operator_equal/)([String](./)\&&) | عامل إسناد النقل. |
| **bool** [operator==](./operator_equal_equal/)(const [String](./)\&) const | عامل مقارنة المساواة. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | يفحص ما إذا كانت السلسلة فارغة. يطبق نفس المنطق كما في استدعاء [IsNull()](./isnull/). |
| **bool** [operator>](./operator_greater/)(const [String](./)\&) const | يقارن ترتيب السلاسل. |
| char_t [operator[]](./operator[]/)(int) const | يحصل على الحرف في الموضع المحدد. |
| [String](./) [PadLeft](./padleft/)(int, char_t) const | يضيف حشوة على يسار السلسلة الأصلية. |
| [String](./) [PadRight](./padright/)(int, char_t) const | يضيف حشوة على يمين السلسلة الأصلية. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() const | يعيد مكرّرًا عكسيًا إلى آخر حرف (إن وجد) في مخزن السلسلة الفعلي. |
| [String](./) [Remove](./remove/)(**int32_t**, **int32_t**) const | يستخرج كل شيء ما عدا الجزء الفرعي من السلسلة الحالية. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() const | يعيد مكرّرًا عكسيًا إلى ما قبل أول حرف (إن وجد) في مخزن السلسلة الفعلي. |
| [String](./) [Replace](./replace/)(char_t, char_t) const | يستبدل كل حدوث للحرف في السلسلة. |
| [String](./) [Replace](./replace/)(const [String](./)\&, const [String](./)\&) const | يستبدل كل حدوث للبحث في هذه السلسلة. |
| [String](./)\& [reset](./reset/)() | يضبط السلسلة على فارغة. وهو مماثل لـ 'string_variable_name = null' في C#. |
| [String](./)\& [SetCharAt](./setcharat/)(int, char_t) | يضبط الحرف في الموضع المحدد. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, [StringSplitOptions](../stringsplitoptions/)) const | يقسم السلسلة بالحرف. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | يقسم السلسلة بالحرف. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, char_t, [StringSplitOptions](../stringsplitoptions/)) const | يقسم السلسلة بأحد حرفين. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, [StringSplitOptions](../stringsplitoptions/)) const | يقسم السلسلة بأحد الأحرف المحددة. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | يقسم السلسلة بأحد الأحرف المحددة. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [String](./)\&, [StringSplitOptions](../stringsplitoptions/)) const | يقسم السلسلة بالجزء الفرعي. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [String](./)\&, int, [StringSplitOptions](../stringsplitoptions/)) const | يقسم السلسلة بالجزء الفرعي. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, [StringSplitOptions](../stringsplitoptions/)) const | يقسم السلسلة بالجزء الفرعي. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, int, [StringSplitOptions](../stringsplitoptions/)) const | يقسم السلسلة بالجزء الفرعي. حاليًا، يدعم فقط مصفوفة الفواصل التي تحتوي على صفر أو عنصر واحد. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&) const | يتحقق ما إذا كانت السلسلة تبدأ بالجزء الفرعي المحدد. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | يتحقق ما إذا كانت السلسلة تبدأ بالجزء الفرعي المحدد. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | يتحقق ما إذا كانت السلسلة تبدأ بالجزء الفرعي المحدد. |
| [String](./string/)() | منشئ افتراضي. ينشئ كائن سلسلة يُعتبر فارغًا. |
| [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, char16_t\>::value\>::type *) | يبني سلسلة استنادًا إلى ثابت نصي. يعتبر الثابت سلسلة منتهية بالصفر، يحسب طول السلسلة الهدف بناءً على حجم الثابت. |
| [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, char16_t\>::value\>::type *) | يبني سلسلة استنادًا إلى مؤشر سلسلة أحرف. يعتبر السلسلة المشار إليها منتهية بالصفر، يحسب طول السلسلة الهدف بناءً على حرف النهاية. |
| explicit [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, char\>::value\>::type *) | يبني سلسلة استنادًا إلى ثابت نصي. يعتبر الثابت سلسلة منتهية بالصفر بترميز UTF8، يحسب طول السلسلة الهدف بناءً على حجم الثابت. |
| explicit [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, char\>::value\>::type *) | يبني سلسلة استنادًا إلى مؤشر سلسلة أحرف. يعتبر السلسلة المشار إليها منتهية بالصفر بترميز UTF8، يحسب طول السلسلة الهدف بناءً على حرف النهاية. |
| [String](./string/)(const char16_t *, int) | يبني سلسلة من مؤشر سلسلة أحرف وطول صريح. |
| [String](./string/)(const [ReadOnlySpan](../readonlyspan/)\<char16_t\>\&) | يُهيئ نسخة جديدة من الفئة [System.String](./) إلى أحرف Unicode المحددة في النطاق القابل للقراءة فقط المحدد. |
| [String](./string/)(const char *, int) | يبني سلسلة من مؤشر سلسلة أحرف وطول صريح. |
| [String](./string/)(const char16_t *, int, int) | يبني سلسلة من مؤشر سلسلة أحرف بدءًا من موضع معين باستخدام الطول. |
| explicit [String](./string/)(const char16_t, int) | منشئ تعبئة. |
| [String](./string/)(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) | منشئ nullptr. مُعلن كقالب لحل الأولويات مع منشئات القالب الأخرى. |
| explicit [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, **wchar_t**\>::value\>::type *) | يبني سلسلة استنادًا إلى ثابت نص واسع. يعتبر الثابت سلسلة منتهية بالصفر، يحسب طول السلسلة الهدف بناءً على حجم الثابت. التحويل من **wchar_t** يستغرق وقتًا على بعض المنصات، لذا لا يُسمح بالتحويلات الضمنية. |
| explicit [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, **wchar_t**\>::value\>::type *) | يبني سلسلة استنادًا إلى مؤشر سلسلة أحرف واسعة. يعتبر السلسلة المشار إليها منتهية بالصفر، يحسب طول السلسلة الهدف بناءً على حرف النهاية. التحويل من **wchar_t** يستغرق وقتًا على بعض المنصات، لذا لا يُسمح بالتحويلات الضمنية. |
| explicit [String](./string/)(const **wchar_t** *, int) | يبني سلسلة من مؤشر سلسلة أحرف واسعة وطول صريح. التحويل من **wchar_t** يستغرق وقتًا على بعض المنصات، لذا لا يُسمح بالتحويلات الضمنية. |
| explicit [String](./string/)(const **wchar_t**, int) | منشئ تعبئة. التحويل من **wchar_t** يستغرق وقتًا على بعض المنصات، لذا لا يُسمح بالتحويلات الضمنية. |
| [String](./string/)(const [String](./)\&) | منشئ نسخة. |
| [String](./string/)([String](./)\&&) | منشئ نقل. |
| [String](./string/)(const [ArrayPtr](../arrayptr/)\<char16_t\>\&) | يحول كامل مصفوفة الأحرف إلى سلسلة. |
| [String](./string/)(const [ArrayPtr](../arrayptr/)\<char16_t\>\&, int, int) | يحول نطاقًا فرعيًا من مصفوفة الأحرف إلى سلسلة. إذا كانت المعاملات خارج حدود المصفوفة، يتم إنشاء سلسلة فارغة. |
| explicit [String](./string/)(const codeporting_icu::UnicodeString\&) | يغلف UnicodeString داخل [String](./). |
| explicit [String](./string/)(codeporting_icu::UnicodeString\&&) | منشئ نقل. |
| explicit [String](./string/)(const std::wstring\&) | ينشئ [String](./) من سلسلة واسعة. |
| explicit [String](./string/)(const std::u16string\&) | ينشئ [String](./) من سلسلة utf16. |
| explicit [String](./string/)(const std::string\&) | ينشئ [String](./) من سلسلة std::string معروضة بتنسيق UTF-8. |
| explicit [String](./string/)(const std::u32string\&) | ينشئ [String](./) من سلسلة std::u32string. |
| [String](./) [Substring](./substring/)(**int32_t**) const | يستخرج الجزء الفرعي. |
| [String](./) [Substring](./substring/)(**int32_t**, **int32_t**) const | يستخرج الجزء الفرعي. |
| std::string [ToAsciiString](./toasciistring/)() const | يحول السلسلة إلى std::string. يستخدم ترميز ASCII. |
| [ArrayPtr](../arrayptr/)\<**uint8_t**\> [ToByteArray](./tobytearray/)(**int32_t**, **int32_t**, **bool**) const | يحول السلسلة أو الجزء الفرعي إلى مصفوفة من البايتات. |
| [ArrayPtr](../arrayptr/)\<char_t\> [ToCharArray](./tochararray/)(**int32_t**, **int32_t**) const | يحول السلسلة أو الجزء الفرعي إلى مصفوفة من الأحرف. |
| [String](./) [ToLower](./tolower/)() const | يحول جميع أحرف السلسلة إلى حروف صغيرة. |
| [String](./) [ToLower](./tolower/)(const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | يحول جميع أحرف السلسلة إلى حروف صغيرة باستخدام ثقافة محددة. |
| [String](./) [ToLowerInvariant](./tolowerinvariant/)() const | يحول جميع أحرف السلسلة إلى حروف صغيرة باستخدام ثقافة ثابتة. |
| [String](./) [ToString](./tostring/)() const | غلاف لمعالجة الفئة [String](./) في سياقات يتم فيها استدعاء [ToString()](./tostring/) على كائنات من النوع القيمي. |
| [String](./) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | غلاف لمعالجة الفئة [String](./) في سياقات يتم فيها استدعاء [ToString()](./tostring/) على كائنات من النوع القيمي. |
| std::u16string [ToU16Str](./tou16str/)() const | يحول السلسلة إلى std::u16string. |
| std::u32string [ToU32Str](./tou32str/)() const | يحول السلسلة إلى std::u32string. |
| [String](./) [ToUpper](./toupper/)() const | يحول جميع أحرف السلسلة إلى حروف كبيرة. |
| [String](./) [ToUpper](./toupper/)(const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | يحول جميع أحرف السلسلة إلى حروف كبيرة باستخدام ثقافة محددة. |
| [String](./) [ToUpperInvariant](./toupperinvariant/)() const | يحول جميع أحرف السلسلة إلى حروف كبيرة باستخدام ثقافة ثابتة. |
| std::string [ToUtf8String](./toutf8string/)() const | يحول السلسلة إلى std::string. يستخدم ترميز UTF-8. |
| std::wstring [ToWCS](./towcs/)() const | يحول السلسلة إلى std::wstring. |
| [String](./) [Trim](./trim/)() const | يزيل جميع أحرف المسافات البيضاء من بداية ونهاية السلسلة. |
| [String](./) [Trim](./trim/)(char_t) const | يزيل جميع حالات الحرف الممرّ من بداية ونهاية السلسلة. |
| [String](./) [Trim](./trim/)(const [String](./)\&) const | يزيل جميع حالات الأحرف الممرّات من بداية ونهاية السلسلة. |
| [String](./) [Trim](./trim/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | يزيل جميع حالات الأحرف الممرّات من بداية ونهاية السلسلة. |
| [String](./) [TrimEnd](./trimend/)() const | يزيل جميع أحرف المسافات البيضاء من نهاية السلسلة. |
| [String](./) [TrimEnd](./trimend/)(char_t) const | يزيل جميع حالات الحرف الممرّ من نهاية السلسلة. |
| [String](./) [TrimEnd](./trimend/)(const [String](./)\&) const | يزيل جميع حالات الأحرف الممرّات من نهاية السلسلة. |
| [String](./) [TrimEnd](./trimend/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | يزيل جميع حالات الأحرف الممرّات من نهاية السلسلة. |
| [String](./) [TrimStart](./trimstart/)() const | يزيل جميع أحرف المسافات البيضاء من بداية السلسلة. |
| [String](./) [TrimStart](./trimstart/)(char_t) const | يزيل جميع حالات الحرف الممرّ من بداية السلسلة. |
| [String](./) [TrimStart](./trimstart/)(const [String](./)\&) const | يزيل جميع حالات الأحرف الممرّات من بداية السلسلة. |
| [String](./) [TrimStart](./trimstart/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | يزيل جميع حالات الأحرف الممرّات من بداية السلسلة. |
| const UChar * [u_str](./u_str/)() const | يعيد مخزن مؤقت منتهي بالصفر على نمط ICU. قد يعيد تخصيص السلسلة. |
| [~String](./~string/)() | المدمر. |

## الحقول

| الحقل | الوصف |
| --- | --- |
| static [Empty](./empty/) | سلسلة فارغة. |
| static [Null](./null/) | سلسلة null. |

## تعريفات النوع

| تعريف النوع | الوصف |
| --- | --- |
| [reverse_iterator](./reverse_iterator/) | نوع المكرّر العكسي. |

## ملاحظات



```cpp
#include "system/string.h"
#include <iostream>

int main()
{
  // إنشاء سلسلة من مصفوفة الأحرف وطباعةها.
  const auto chars = {u'h', u'e', u'l', u'l', u'o'};
  const System::String string1(chars);
  std::cout << string1 << std::endl;

  // إنشاء سلسلة من مصفوفة البايتات وطباعةها.
  const uint8_t bytes[] = {0x77, 0x6f, 0x72, 0x6c, 0x64, 0x0};
  const auto string2 = System::String::FromUtf8(bytes);
  std::cout << string2 << std::endl;

  // قص السلسلة أدناه وطباعةها.
  const System::String string3(u"   This string contains whitespaces in the beginning and at the end.   ");
  std::cout << '"' << string3.Trim() << '"' << std::endl;

  // طباعة عدد الكلمات في .
  std::cout << "Number of words: " << string3.Trim().Split(' ')->get_Length() << std::endl;

  return 0;
}
/*
هذا المثال البرمجي ينتج المخرجات التالية:
hello
world
"This string contains whitespaces in the beginning and at the end."
Number of words: 11
*/
```

## أنظر أيضاً

* نطاق [System](../)
* مكتبة [Aspose.Slides](../../)