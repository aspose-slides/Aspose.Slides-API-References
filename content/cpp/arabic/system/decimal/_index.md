---
title: Decimal
second_title: Aspose.Slides لواجهة برمجة تطبيقات C++
description: "يمثل عددًا عشريًا. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم أبداً فئة System::SmartPtr لإدارة كائنات هذا النوع."
type: docs
weight: 261
url: /ar/system/decimal/
---
## فئة Decimal

يمثل عددًا عشريًا. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم فئة [System::SmartPtr](../smartptr/) لإدارة كائنات هذا النوع.

```cpp
class Decimal
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| static [Decimal](./) [Add](./add/)(const [Decimal](./)\&, const [Decimal](./)\&) | يضيف قيمتين [Decimal](./) محددتين. |
| static [Decimal](./) [Ceiling](./ceiling/)(const [Decimal](./)\&) | يعيد أصغر قيمة عددية صحيحة تكون أكبر من أو مساوية للقيمة المحددة. |
| static int [Compare](./compare/)(const [Decimal](./)\&, const [Decimal](./)\&) | يحدد ما إذا كانت القيمة التي يمثلها الكائن [Decimal](./) الأول أصغر من أو مساوية أو أكبر من القيمة التي يمثلها الكائن [Decimal](./) الثاني. |
| int [CompareTo](./compareto/)(const [Decimal](./)\&) const | يحدد ما إذا كانت القيمة التي يمثلها الكائن الحالي أصغر من أو مساوية أو أكبر من القيمة التي يمثلها الكائن المحدد. |
| [Decimal](./decimal/)() | ينشئ مثيلاً يمثل الصفر. |
| [Decimal](./decimal/)(std::int8_t) | ينشئ مثيلاً يمثل القيمة المحددة. |
| [Decimal](./decimal/)(std::int16_t) | ينشئ مثيلاً يمثل القيمة المحددة. |
| [Decimal](./decimal/)(std::int32_t) | ينشئ مثيلاً يمثل القيمة المحددة. |
| [Decimal](./decimal/)(std::int64_t) | ينشئ مثيلاً يمثل القيمة المحددة. |
| [Decimal](./decimal/)(std::uint8_t) | ينشئ مثيلاً يمثل القيمة المحددة. |
| [Decimal](./decimal/)(std::uint16_t) | ينشئ مثيلاً يمثل القيمة المحددة. |
| [Decimal](./decimal/)(std::uint32_t) | ينشئ مثيلاً يمثل القيمة المحددة. |
| [Decimal](./decimal/)(std::uint64_t) | ينشئ مثيلاً يمثل القيمة المحددة. |
| [Decimal](./decimal/)(**float**) | ينشئ مثيلاً يمثل القيمة المحددة. |
| [Decimal](./decimal/)(**double**) | ينشئ مثيلاً يمثل القيمة المحددة. |
| explicit [Decimal](./decimal/)(const std::string\&) | ينشئ مثيلاً يمثل قيمة تم تمثيلها كسلسلة نصية محددة ككائن من فئة std::string. |
| [Decimal](./decimal/)(**int32_t**, **int32_t**, **int32_t**, **bool**, **uint8_t**) | ينشئ كائن [Decimal](./) من المكونات المحددة. |
| [Decimal](./decimal/)(const [Decimal](./)\&) | ينشئ مثيلاً من فئة [Decimal](./) يمثل نفس الرقم كما في الكائن [Decimal](./) المحدد. |
| [Decimal](./decimal/)(const [ArrayPtr](../arrayptr/)\<**int32_t**\>\&) | ينشئ مثيلاً من فئة [Decimal](./) من مصفوفة أعداد صحيحة تحتوي على تمثيل ثنائي. |
| [Decimal](./decimal/)(std::nullptr_t) | دائمًا يرمي استثناء ArgumentNullException. |
| [Decimal](./decimal/)(const [number_type](./number_type/)\&) | ينشئ مثيلاً من فئة [Decimal](./) يمثل القيمة المحددة. |
| static [Decimal](./) [Divide](./divide/)(const [Decimal](./)\&, const [Decimal](./)\&) | يقسم قيمتين [Decimal](./) محددتين. |
| **bool** [Equals](./equals/)(const [Decimal](./)\&) const | يحدد ما إذا كانت القيم التي يمثلها الكائن الحالي والكائن المحدد متساوية. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | يحدد ما إذا كانت القيم التي يمثلها الكائن الحالي والكائن المحدد متساوية. |
| static **bool** [Equals](./equals/)(const [Decimal](./)\&, const [Decimal](./)\&) | يحدد ما إذا كانت القيم التي يمثلها الكائنان المحددان متساوية. |
| static [Decimal](./) [Floor](./floor/)(const [Decimal](./)\&) | يعيد أكبر قيمة عددية صحيحة تكون أصغر من أو مساوية للقيمة المحددة. |
| static [Decimal](./) [FromOACurrency](./fromoacurrency/)(**int64_t**) | [Convert](../convert/) القيمة OLE currency المحددة إلى القيمة [Decimal](./) المكافئة. غير مُنفّذ. |
| static [System::ArrayPtr](../arrayptr/)\<int\> [GetBits](./getbits/)(const [Decimal](./)\&) | يحول الكائن [Decimal](./) المحدد إلى التمثيل الثنائي للقيمة التي يمثلها. |
| static void [GetBytes](./getbytes/)(const [Decimal](./)\&, const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | [Convert](../convert/) القيمة [Decimal](./) المحددة إلى مصفوفة من البايتات. |
| int [GetHashCode](./gethashcode/)() const | يعيد رمز تجزئة للكائن الحالي. |
| [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() const | يحصل على رمز نوع الكائن. |
| static [Decimal](./) [Multiply](./multiply/)(const [Decimal](./)\&, const [Decimal](./)\&) | يضرب قيمتين [Decimal](./) محددتين. |
| static [Decimal](./) [Negate](./negate/)(const [Decimal](./)\&) | يعيد مثيلاً جديدًا من فئة [Decimal](./) يمثل قيمة ناتجة عن نفي القيمة التي يمثلها الكائن المحدد. |
| explicit [operator bool](./operator_bool/)() const | يحول القيمة التي يمثلها الكائن الحالي إلى قيمة منطقية. |
| explicit [operator double](./operator_double/)() const | يحول القيمة التي يمثلها الكائن الحالي إلى قيمة عائمة مزدوجة الدقة. |
| explicit [operator float](./operator_float/)() const | يحول القيمة التي يمثلها الكائن الحالي إلى قيمة عائمة ذات دقة واحدة. |
| **bool** [operator!=](./operator_not_equal/)(const [Decimal](./)\&) const | يحدد ما إذا كانت القيم التي يمثلها الكائن الحالي والكائن المحدد غير متساوية. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | يحدد ما إذا كانت القيمة التي يمثلها الكائن الحالي مختلفة عن الصفر. |
| [Decimal](./) [operator%](./operator%/)(const [Decimal](./)\&) const | يعيد مثيلاً جديدًا من فئة [Decimal](./) يمثل قيمة ناتجة عن عملية باقي القسمة بين القيم التي يمثلها الكائن الحالي والكائن المحدد. |
| [Decimal](./)\& [operator%=](./operator%_equal/)(const [Decimal](./)\&) | يعين للكائن الحالي قيمة جديدة هي نتيجة عملية باقي القسمة بين القيم التي يمثلها الكائن الحالي والكائن المحدد. |
| [Decimal](./) [operator*](./operator_star/)(const [Decimal](./)\&) const | يعيد مثيلاً جديدًا من فئة [Decimal](./) يمثل قيمة ناتجة عن ضرب القيم التي يمثلها الكائن الحالي والكائن المحدد. |
| [Decimal](./)\& [operator*=](./operator_star_equal/)(const [Decimal](./)\&) | يعين للكائن الحالي قيمة جديدة هي نتيجة ضرب القيم التي يمثلها الكائن الحالي والكائن المحدد. |
| [Decimal](./) [operator+](./operator_plus/)(const [Decimal](./)\&) const | يعيد مثيلاً جديدًا من فئة [Decimal](./) يمثل قيمة هي مجموع القيم التي يمثلها الكائن الحالي والكائن المحدد. |
| [Decimal](./)\& [operator++](./operator_plus_plus/)() | يزيد القيمة التي يمثلها الكائن الحالي. |
| [Decimal](./)\& [operator+=](./operator_plus_equal/)(const [Decimal](./)\&) | يعين للكائن الحالي قيمة جديدة هي مجموع القيم التي يمثلها الكائن الحالي والكائن المحدد. |
| [Decimal](./) [operator-](./operator_minus/)(const [Decimal](./)\&) const | يعيد مثيلاً جديدًا من فئة [Decimal](./) يمثل قيمة هي نتيجة طرح القيمة التي يمثلها الكائن المحدد من القيمة التي يمثلها الكائن الحالي. |
| [Decimal](./) [operator-](./operator_minus/)() const | يعيد مثيلاً جديدًا من فئة [Decimal](./) يمثل قيمة ناتجة عن نفي القيمة التي يمثلها الكائن الحالي. |
| [Decimal](./)\& [operator--](./operator_minus_minus/)() | يقلل القيمة التي يمثلها الكائن الحالي. |
| [Decimal](./)\& [operator-=](./operator_minus_equal/)(const [Decimal](./)\&) | يعين للكائن الحالي قيمة جديدة هي نتيجة طرح القيمة التي يمثلها الكائن المحدد من القيمة التي يمثلها الكائن الحالي. |
| [Decimal](./) [operator/](./operator_div/)(const [Decimal](./)\&) const | يعيد مثيلاً جديدًا من فئة [Decimal](./) يمثل قيمة هي نتيجة قسمة القيمة التي يمثلها الكائن الحالي على القيمة التي يمثلها الكائن المحدد. |
| [Decimal](./)\& [operator/=](./operator_div_equal/)(const [Decimal](./)\&) | يعين للكائن الحالي قيمة جديدة هي نتيجة قسمة القيمة التي يمثلها الكائن الحالي على القيمة التي يمثلها الكائن المحدد. |
| **bool** [operator<](./operator_less/)(const [Decimal](./)\&) const | يحدد ما إذا كانت القيمة التي يمثلها الكائن الحالي أصغر من القيمة التي يمثلها الكائن المحدد. |
| **bool** [operator<=](./operator_less_equal/)(const [Decimal](./)\&) const | يحدد ما إذا كانت القيمة التي يمثلها الكائن الحالي أصغر من أو مساوية للقيمة التي يمثلها الكائن المحدد. |
| [Decimal](./)\& [operator=](./operator_equal/)(const [Decimal](./)\&) | يعين القيمة التي يمثلها الكائن المحدد إلى الكائن الحالي. |
| **bool** [operator==](./operator_equal_equal/)(const [Decimal](./)\&) const | يحدد ما إذا كانت القيم التي يمثلها الكائن الحالي والكائن المحدد متساوية. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | يحدد ما إذا كانت القيمة التي يمثلها الكائن الحالي هي الصفر. |
| **bool** [operator>](./operator_greater/)(const [Decimal](./)\&) const | يحدد ما إذا كانت القيمة التي يمثلها الكائن الحالي أكبر من القيمة التي يمثلها الكائن المحدد. |
| **bool** [operator>=](./operator_greater_equal/)(const [Decimal](./)\&) const | يحدد ما إذا كانت القيمة التي يمثلها الكائن الحالي أكبر من أو مساوية للقيمة التي يمثلها الكائن المحدد. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&) | يحول تمثيل النص لعدد عشري إلى مثيل مكافئ من فئة [Decimal](./). |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/)) | يحول تمثيل النص لعدد عشري إلى مثيل مكافئ من فئة [Decimal](./) باستخدام النمط المحدد. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يحول تمثيل النص لعدد عشري إلى مثيل مكافئ من فئة [Decimal](./) باستخدام موفر الصيغة المحدد. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يحول تمثيل النص لعدد عشري إلى مثيل مكافئ من فئة [Decimal](./) باستخدام النمط وموفر الصيغة المحددين. |
| static [Decimal](./) [Remainder](./remainder/)(const [Decimal](./)\&, const [Decimal](./)\&) | يحسب باقي القسمة بعد قسمة قيمتين [Decimal](./). |
| static [Decimal](./) [Round](./round/)(const [Decimal](./)\&, [MidpointRounding](../midpointrounding/)) | يقرب القيمة المحددة إلى أقرب عدد صحيح. يحدد أحد المعاملات سلوك الدالة إذا كانت القيمة المحددة متساوية القرب من أقرب عددين. |
| static [Decimal](./) [Round](./round/)(const [Decimal](./)\&, int, [MidpointRounding](../midpointrounding/)) | يقرب القيمة المحددة إلى أقرب قيمة بعدد محدد من الأرقام العشرية. يحدد أحد المعاملات سلوك الدالة إذا كانت القيمة المحددة متساوية القرب من أقرب قيمتين. |
| static [Decimal](./) [Subtract](./subtract/)(const [Decimal](./)\&, const [Decimal](./)\&) | يطرح قيمة [Decimal](./) محددة من أخرى. |
| static **uint8_t** [ToByte](./tobyte/)([Decimal](./)) | يحول قيمة [Decimal](./) إلى قيمة عدد صحيح غير موقع 8-بت. |
| static **double** [ToDouble](./todouble/)([Decimal](./)) | يحول قيمة [Decimal](./) إلى عدد عائم مزدوج الدقة. |
| static **int16_t** [ToInt16](./toint16/)([Decimal](./)) | يحول قيمة [Decimal](./) إلى قيمة عدد صحيح موقع 16-بت. |
| static **int32_t** [ToInt32](./toint32/)([Decimal](./)) | يحول قيمة [Decimal](./) إلى قيمة عدد صحيح موقع 32-بت. |
| static **int64_t** [ToInt64](./toint64/)([Decimal](./)) | يحول قيمة [Decimal](./) إلى قيمة عدد صحيح موقع 64-بت. |
| static **int64_t** [ToOACurrency](./tooacurrency/)(const [Decimal](./)\&) | [Convert](../convert/) القيمة [Decimal](./) المحددة إلى قيمة OLE currency المكافئة. غير مُنفّذ. |
| static **int8_t** [ToSByte](./tosbyte/)([Decimal](./)) | يحول قيمة [Decimal](./) إلى قيمة عدد صحيح موقع 8-بت. |
| static **float** [ToSingle](./tosingle/)([Decimal](./)) | يحول قيمة [Decimal](./) إلى عدد عائم بدقة واحدة. |
| std::string [ToStdString](./tostdstring/)() const | يعيد مثيلاً من std::string يحتوي على تمثيل نصي للقيمة التي يمثلها الكائن. |
| [String](../string/) [ToString](./tostring/)() const | يعيد التمثيل النصي للقيمة التي يمثلها الكائن. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | يحول الكائن الحالي إلى سلسلة نصية باستخدام معلومات تنسيق خاصة بالثقافة. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [Decimal](./)\&, std::nullptr_t) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | يحول الكائن الحالي إلى تمثيله النصي باستخدام تنسيق السلسلة المحدد ومعلومات التنسيق الخاصة بالثقافة التي يوفرها الكائن [IFormatProvider](../iformatprovider/) المحدد. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| [String](../string/) [ToStringInternal](./tostringinternal/)() const | يعيد التمثيل النصي للقيمة التي يمثلها الكائن. للاستخدام الداخلي. |
| static **uint16_t** [ToUInt16](./touint16/)([Decimal](./)) | يحول قيمة [Decimal](./) إلى قيمة عدد صحيح غير موقع 16-بت. |
| static **uint32_t** [ToUInt32](./touint32/)([Decimal](./)) | يحول قيمة [Decimal](./) إلى قيمة عدد صحيح غير موقع 32-بت. |
| static **uint64_t** [ToUInt64](./touint64/)([Decimal](./)) | يحول قيمة [Decimal](./) إلى قيمة عدد صحيح غير موقع 64-بت. |
| static [Decimal](./) [Truncate](./truncate/)(const [Decimal](./)\&) | يعيد الكائن [Decimal](./) الذي يمثل قيمة لها الجزء الصحيح مساويًا للجزء الصحيح للقيمة التي يمثلها الكائن [Decimal](./) المحدد مع إهمال جميع الأرقام العشرية. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Decimal](./)\&) | يحول السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى القيمة [Decimal](./) المكافئة. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Decimal](./)\&) | يحول السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى القيمة [Decimal](./) المكافئة باستخدام معلومات التنسيق ونمط الرقم المقدمة. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | يعيد مرجعًا إلى الكائن [TypeInfo](../typeinfo/) الذي يمثل معلومات نوع الفئة [Decimal](./). |
| [~Decimal](./~decimal/)() | المدمر. |
## الحقول

| الحقل | الوصف |
| --- | --- |
| static [MaxValue](./maxvalue/) | يمثل أكبر عدد يمكن تمثيله بواسطة فئة [Decimal](./). |
| static [MinusOne](./minusone/) | يمثل العدد -1. |
| static [MinValue](./minvalue/) | يمثل أصغر عدد يمكن تمثيله بواسطة فئة [Decimal](./). |
| static [One](./one/) | يمثل العدد 1. |
| static [Zero](./zero/) | يمثل العدد 0. |
## التعريف

| التعريف | الوصف |
| --- | --- |
| [number_type](./number_type/) | اسم مستعار لـ Detail::decimal_number_type. |
## ملاحظات



```cpp
#include "system/console.h"
#include "system/decimal.h"

int main()
{
  using namespace System;

  Console::WriteLine(Decimal::MinValue);
  Console::WriteLine(Decimal::MaxValue);

  auto dividend = Decimal::One;
  auto divisor = 6;
  Console::WriteLine(dividend/divisor);

  return 0;
}
/*
هذا المثال البرمجي ينتج المخرجات التالية:
- 79228162514264337593543950335
79228162514264337593543950335
0,1666666666666666666666666667
*/
```

## أنظر أيضاً

* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)