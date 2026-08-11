---
title: Convert
second_title: مرجع Aspose.Slides للـ C++ API
description: "البنية التي تحتوي على طرق تنفيذ تحويل القيم من نوع إلى قيم من نوع آخر. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم أبداً فئة System::SmartPtr لإدارة كائنات هذا النوع."
type: docs
weight: 1561
url: /ar/system/convert/
---
## تحويل البنية

البنية التي تحتوي على طرق تقوم بتحويل القيم من نوع إلى قيم من نوع آخر. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم أبداً الفئة [System::SmartPtr](../smartptr/) لإدارة كائنات هذا النوع.

```cpp
class Convert
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ChangeType](./changetype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [TypeInfo](../typeinfo/)\&) | غير مُنفّذ. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ChangeType](./changetype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) |  |
| static [ArrayPtr](../arrayptr/)\<**uint8_t**\> [FromBase64CharArray](./frombase64chararray/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) | يفكّ شفرة البيانات المشفّرة بـ base-64 الممثلة كنطاق في مصفوفة أحرف Unicode. |
| static [ArrayPtr](../arrayptr/)\<**uint8_t**\> [FromBase64String](./frombase64string/)(const [String](../string/)\&) | يفكّ شفرة البيانات المشفّرة بـ base-64 الممثلة كسلسلة. |
| static [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | يعيد قيمة TypeCode التي تمثل نوع القيمة المعلّبة المحددة. |
| static std::enable_if_t<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\> [IsDBNull](./isdbnull/)(const T\&) | غير مُنفّذ. |
| static **bool** [IsDBNull](./isdbnull/)(const [SharedPtr](../sharedptr/)\<T\>\&) | غير مُنفّذ تنفيذ وهمي، يتحقق مما إذا كانت القيمة nullptr. |
| static Target [To](./to/)(const Source\&) |  |
| static int [ToBase64CharArray](./tobase64chararray/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../arrayptr/)\<char16_t\>\&, int, **bool**) | يقوم بترميز Base-64 لنطاق من العناصر في مصفوفة البايت المحددة ويخزن البيانات المشفّرة كمصفوفة من أحرف Unicode. |
| static int [ToBase64CharArray](./tobase64chararray/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, [Base64FormattingOptions](../base64formattingoptions/)) | يقوم بترميز Base-64 لنطاق من العناصر في مصفوفة البايت المحددة ويخزن البيانات المشفّرة كمصفوفة من أحرف Unicode. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, **bool**) | يقوم بترميز Base-64 للعناصر في مصفوفة البايت المحددة ويعيد البيانات المشفّرة كسلسلة. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, **bool**) | يقوم بترميز Base-64 لنطاق من العناصر في مصفوفة البايت المحددة ويعيد البيانات المشفّرة كسلسلة. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, [Base64FormattingOptions](../base64formattingoptions/)) | يقوم بترميز Base-64 للعناصر في مصفوفة البايت المحددة ويعيد البيانات المشفّرة كسلسلة. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, [Base64FormattingOptions](../base64formattingoptions/)) | يقوم بترميز Base-64 لنطاق من العناصر في مصفوفة البايت المحددة ويعيد البيانات المشفّرة كسلسلة. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**bool**) | يعيد القيمة البوليانية المحددة. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint8_t**) | تحول العدد الصحيح غير الموقع 8-bit المحدد إلى قيمة بوليانية مكافئة. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int8_t**) | تحول العدد الصحيح الموقع 8-bit المحدد إلى قيمة بوليانية مكافئة. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint16_t**) | تحول العدد الصحيح غير الموقع 16-bit المحدد إلى قيمة بوليانية مكافئة. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int16_t**) | تحول العدد الصحيح الموقع 16-bit المحدد إلى قيمة بوليانية مكافئة. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint32_t**) | تحول العدد الصحيح غير الموقع 32-bit المحدد إلى قيمة بوليانية مكافئة. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int32_t**) | تحول العدد الصحيح الموقع 32-bit المحدد إلى قيمة بوليانية مكافئة. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint64_t**) | تحول العدد الصحيح غير الموقع 64-bit المحدد إلى قيمة بوليانية مكافئة. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int64_t**) | تحول العدد الصحيح الموقع 64-bit المحدد إلى قيمة بوليانية مكافئة. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**float**) | تحول عدد الفاصلة العائمة المحدد إلى قيمة بوليانية مكافئة. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**double**) | تحول عدد double المحدد إلى قيمة بوليانية مكافئة. |
| static **bool** [ToBoolean](./toboolean/)(const [Decimal](../decimal/)\&) | تحول العدد العشري المحدد إلى قيمة بوليانية مكافئة. |
| static **bool** [ToBoolean](./toboolean/)(char_t) | التحويل غير مدعوم. دائمًا يرمي InvalidCastException. |
| static **bool** [ToBoolean](./toboolean/)([DateTime](../datetime/)) | التحويل غير مدعوم. دائمًا يرمي InvalidCastException. |
| static constexpr **bool** [ToBoolean](./toboolean/)(std::nullptr_t) | تحول السلسلة الفارغة المحددة إلى القيمة البوليانية المكافئة. |
| static **bool** [ToBoolean](./toboolean/)(const char_t *) | تحول السلسلة c المحددة إلى قيمة من نوع bool. |
| static **bool** [ToBoolean](./toboolean/)(const [String](../string/)\&) | تحول السلسلة المحددة إلى قيمة من نوع bool. |
| static **bool** [ToBoolean](./toboolean/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | تحول السلسلة المحددة إلى قيمة من نوع bool. |
| static **bool** [ToBoolean](./toboolean/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | تحول القيمة المعلّبة المحددة إلى قيمة بوليانية مكافئة. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(**bool**) | تحول القيمة البوليانية المحددة إلى عدد صحيح غير موقع 8-bit مكافئ. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(**uint8_t**) | يعيد العدد الصحيح غير الموقع 8-bit المحدد. |
| static **uint8_t** [ToByte](./tobyte/)(**int8_t**) | تحول العدد الصحيح الموقع 8-bit المحدد إلى عدد صحيح غير موقع 8-bit مكافئ. |
| static **uint8_t** [ToByte](./tobyte/)(**uint16_t**) | تحول العدد الصحيح غير الموقع 16-bit المحدد إلى عدد صحيح غير موقع 8-bit مكافئ. |
| static **uint8_t** [ToByte](./tobyte/)(**int16_t**) | تحول العدد الصحيح الموقع 16-bit المحدد إلى عدد صحيح غير موقع 8-bit مكافئ. |
| static **uint8_t** [ToByte](./tobyte/)(**uint32_t**) | تحول العدد الصحيح غير الموقع 32-bit المحدد إلى عدد صحيح غير موقع 8-bit مكافئ. |
| static **uint8_t** [ToByte](./tobyte/)(**int32_t**) | تحول العدد الصحيح الموقع 32-bit المحدد إلى عدد صحيح غير موقع 8-bit مكافئ. |
| static **uint8_t** [ToByte](./tobyte/)(**uint64_t**) | تحول العدد الصحيح غير الموقع 64-bit المحدد إلى عدد صحيح غير موقع 8-bit مكافئ. |
| static **uint8_t** [ToByte](./tobyte/)(**int64_t**) | تحول العدد الصحيح الموقع 64-bit المحدد إلى عدد صحيح غير موقع 8-bit مكافئ. |
| static **uint8_t** [ToByte](./tobyte/)(**float**) | تحول عدد الفاصلة العائمة المحدد إلى عدد صحيح غير موقع 8-bit مكافئ. |
| static **uint8_t** [ToByte](./tobyte/)(**double**) | تحول عدد double المحدد إلى عدد صحيح غير موقع 8-bit مكافئ. |
| static **uint8_t** [ToByte](./tobyte/)(const [Decimal](../decimal/)\&) | تحول العدد العشري المحدد إلى عدد صحيح غير موقع 8-bit مكافئ. |
| static **uint8_t** [ToByte](./tobyte/)(char_t) | تحول الحرف Unicode المحدد إلى عدد صحيح غير موقع 8-bit مكافئ. |
| static **uint8_t** [ToByte](./tobyte/)([DateTime](../datetime/)) | التحويل غير مدعوم. دائمًا يرمي InvalidCastException. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(std::nullptr_t) | تحول السلسلة الفارغة المحددة إلى قيمة عدد صحيح غير موقع 8-bit مكافئة. |
| static **uint8_t** [ToByte](./tobyte/)(const char_t *) | تحول السلسلة c التي تحتوي على تمثيل عدد كسلسلة إلى قيمة عدد صحيح غير موقع 8-bit مكافئة. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&) | تحول السلسلة المحددة التي تحتوي على تمثيل عدد كسلسلة إلى قيمة عدد صحيح غير موقع 8-bit مكافئة. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, int) | تحول السلسلة التي تحتوي على تمثيل عدد كسلسلة في القاعدة المحددة إلى قيمة عدد صحيح غير موقع 8-bit مكافئة. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | تحول السلسلة التي تحتوي على تمثيل عدد كسلسلة إلى قيمة عدد صحيح غير موقع 8-bit مكافئة باستخدام معلومات التنسيق المقدمة. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | تحول السلسلة التي تحتوي على تمثيل عدد كسلسلة إلى قيمة عدد صحيح غير موقع 8-bit مكافئة باستخدام معلومات التنسيق ونمط العدد المقدمة. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint8_t** [ToByte](./tobyte/)([Enum](../enum/)) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | تحول القيمة المعلّبة المحددة إلى قيمة عدد صحيح غير موقع 8-bit مكافئة. |
| static char_t [ToChar](./tochar/)(**bool**) | التحويل غير مدعوم. دائمًا يرمي InvalidCastException. |
| static constexpr char_t [ToChar](./tochar/)(**uint8_t**) | تحول العدد الصحيح غير الموقع 8-bit المحدد إلى حرف Unicode مكافئ. |
| static char_t [ToChar](./tochar/)(**int8_t**) | تحول العدد الصحيح الموقع 8-bit المحدد إلى حرف Unicode مكافئ. |
| static constexpr char_t [ToChar](./tochar/)(**uint16_t**) | تحول العدد الصحيح غير الموقع 16-bit المحدد إلى حرف Unicode مكافئ. |
| static char_t [ToChar](./tochar/)(**int16_t**) | تحول العدد الصحيح الموقع 16-bit المحدد إلى حرف Unicode مكافئ. |
| static char_t [ToChar](./tochar/)(**uint32_t**) | تحول العدد الصحيح غير الموقع 32-bit المحدد إلى حرف Unicode مكافئ. |
| static char_t [ToChar](./tochar/)(**int32_t**) | تحول العدد الصحيح الموقع 32-bit المحدد إلى حرف Unicode مكافئ. |
| static char_t [ToChar](./tochar/)(**uint64_t**) | تحول العدد الصحيح غير الموقع 64-bit المحدد إلى حرف Unicode مكافئ. |
| static char_t [ToChar](./tochar/)(**int64_t**) | تحول العدد الصحيح الموقع 64-bit المحدد إلى حرف Unicode مكافئ. |
| static char_t [ToChar](./tochar/)(**float**) | التحويل غير مدعوم. دائمًا يرمي InvalidCastException. |
| static char_t [ToChar](./tochar/)(**double**) | التحويل غير مدعوم. دائمًا يرمي InvalidCastException. |
| static char_t [ToChar](./tochar/)(const [Decimal](../decimal/)\&) | التحويل غير مدعوم. دائمًا يرمي InvalidCastException. |
| static constexpr char_t [ToChar](./tochar/)(char_t) | يعيد الحرف Unicode المحدد. |
| static char_t [ToChar](./tochar/)([DateTime](../datetime/)) | التحويل غير مدعوم. دائمًا يرمي InvalidCastException. |
| static char_t [ToChar](./tochar/)(const char_t *) | تحول الحرف الأول والوحيد في السلسلة c المحددة إلى قيمة char_t. |
| static char_t [ToChar](./tochar/)(const [String](../string/)\&) | تحول الحرف الأول والوحيد في السلسلة المحددة إلى قيمة char_t. |
| static char_t [ToChar](./tochar/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | تحول الحرف الأول والوحيد في السلسلة المحددة إلى قيمة char_t. |
| static char_t [ToChar](./tochar/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | تحول القيمة المعلّبة المحددة إلى حرف Unicode مكافئ. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**bool**) | التحويل غير مدعوم. دائمًا يرمي InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint8_t**) | التحويل غير مدعوم. دائمًا يرمي InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int8_t**) | التحويل غير مدعوم. دائمًا يرمي InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint16_t**) | التحويل غير مدعوم. دائمًا يرمي InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int16_t**) | التحويل غير مدعوم. دائمًا يرمي InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint32_t**) | التحويل غير مدعوم. دائمًا يرمي InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int32_t**) | التحويل غير مدعوم. دائمًا يرمي InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint64_t**) | التحويل غير مدعوم. دائمًا يرمي InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int64_t**) | التحويل غير مدعوم. دائمًا يرمي InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**float**) | التحويل غير مدعوم. دائمًا يلقي استثناء InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**double**) | التحويل غير مدعوم. دائمًا يلقي استثناء InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [Decimal](../decimal/)\&) | التحويل غير مدعوم. دائمًا يلقي استثناء InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(char_t) | التحويل غير مدعوم. دائمًا يلقي استثناء InvalidCastException. |
| static constexpr [DateTime](../datetime/) [ToDateTime](./todatetime/)([DateTime](../datetime/)) | يعيد التاريخ والوقت المحددين. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&) | يحول السلسلة المحددة إلى كائن من الفئة [DateTime](../datetime/). |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يحول السلسلة المحددة إلى كائن من الفئة [DateTime](../datetime/) باستخدام معلومات التنسيق المقدمة. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, std::nullptr_t) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يحول القيمة المغلفة المحددة إلى القيمة المكافئة [DateTime](../datetime/). |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**bool**) | يحول القيمة البوليانية المحددة إلى رقم عشري مكافئ. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint8_t**) | يحول عددًا صحيحًا غير موقّع 8-بت المحدد إلى رقم عشري مكافئ. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int8_t**) | يحول عددًا صحيحًا موقّع 8-بت المحدد إلى رقم عشري مكافئ. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint16_t**) | يحول عددًا صحيحًا غير موقّع 16-بت المحدد إلى رقم عشري مكافئ. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int16_t**) | يحول عددًا صحيحًا موقّع 16-بت المحدد إلى رقم عشري مكافئ. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint32_t**) | يحول عددًا صحيحًا غير موقّع 32-بت المحدد إلى رقم عشري مكافئ. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int32_t**) | يحول عددًا صحيحًا موقّع 32-بت المحدد إلى رقم عشري مكافئ. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint64_t**) | يحول عددًا صحيحًا غير موقّع 64-بت المحدد إلى رقم عشري مكافئ. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int64_t**) | يحول عددًا صحيحًا موقّع 64-بت المحدد إلى رقم عشري مكافئ. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**float**) | يحول العدد من نوع float المحدد إلى رقم عشري مكافئ. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**double**) | يحول العدد من نوع double المحدد إلى رقم عشري مكافئ. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [Decimal](../decimal/)\&) | يعيد الرقم العشري المحدد. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(char_t) | التحويل غير مدعوم. دائمًا يلقي استثناء InvalidCastException. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)([DateTime](../datetime/)) | التحويل غير مدعوم. دائمًا يلقي استثناء InvalidCastException. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(std::nullptr_t) | يحول السلسلة الفارغة المحددة إلى القيمة المكافئة [Decimal](../decimal/). |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const char_t *) | يحول سلسلة c-string المحددة التي تحتوي على تمثيل رقمي لسلسلة إلى القيمة المكافئة [Decimal](../decimal/). |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&) | يحول السلسلة المحددة التي تحتوي على تمثيل رقمي لسلسلة إلى القيمة المكافئة [Decimal](../decimal/). |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يحول السلسلة المحددة التي تحتوي على تمثيل رقمي لسلسلة إلى القيمة المكافئة [Decimal](../decimal/) باستخدام معلومات التنسيق المقدمة. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يحول السلسلة المحددة التي تحتوي على تمثيل رقمي لسلسلة إلى القيمة المكافئة [Decimal](../decimal/) باستخدام أنماط الأرقام المحددة ومعلومات التنسيق. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يحول القيمة المغلفة المحددة إلى القيمة المكافئة [Decimal](../decimal/). |
| static constexpr **double** [ToDouble](./todouble/)(**bool**) | يحول القيمة البوليانية المحددة إلى عدد عائم مزدوج الدقة مكافئ. |
| static constexpr **double** [ToDouble](./todouble/)(**uint8_t**) | يحول عددًا صحيحًا غير موقّع 8-بت المحدد إلى عدد عائم مزدوج الدقة مكافئ. |
| static constexpr **double** [ToDouble](./todouble/)(**int8_t**) | يحول عددًا صحيحًا موقّع 8-بت المحدد إلى عدد عائم مزدوج الدقة مكافئ. |
| static constexpr **double** [ToDouble](./todouble/)(**uint16_t**) | يحول عددًا صحيحًا غير موقّع 16-بت المحدد إلى عدد عائم مزدوج الدقة مكافئ. |
| static constexpr **double** [ToDouble](./todouble/)(**int16_t**) | يحول عددًا صحيحًا موقّع 16-بت المحدد إلى عدد عائم مزدوج الدقة مكافئ. |
| static constexpr **double** [ToDouble](./todouble/)(**uint32_t**) | يحول عددًا صحيحًا غير موقّع 32-بت المحدد إلى عدد عائم مزدوج الدقة مكافئ. |
| static constexpr **double** [ToDouble](./todouble/)(**int32_t**) | يحول عددًا صحيحًا موقّع 32-بت المحدد إلى عدد عائم مزدوج الدقة مكافئ. |
| static constexpr **double** [ToDouble](./todouble/)(**uint64_t**) | يحول عددًا صحيحًا غير موقّع 64-بت المحدد إلى عدد عائم مزدوج الدقة مكافئ. |
| static constexpr **double** [ToDouble](./todouble/)(**int64_t**) | يحول عددًا صحيحًا موقّع 64-بت المحدد إلى عدد عائم مزدوج الدقة مكافئ. |
| static constexpr **double** [ToDouble](./todouble/)(**float**) | يحول العدد من نوع float المحدد إلى عدد عائم مزدوج الدقة مكافئ. |
| static constexpr **double** [ToDouble](./todouble/)(**double**) | يعيد العدد المزدوج المحدد. |
| static **double** [ToDouble](./todouble/)(const [Decimal](../decimal/)\&) | يحول الرقم العشري المحدد إلى عدد عائم مزدوج الدقة مكافئ. |
| static **double** [ToDouble](./todouble/)(char_t) | التحويل غير مدعوم. دائمًا يلقي استثناء InvalidCastException. |
| static **double** [ToDouble](./todouble/)([DateTime](../datetime/)) | التحويل غير مدعوم. دائمًا يلقي استثناء InvalidCastException. |
| static constexpr **double** [ToDouble](./todouble/)(std::nullptr_t) | يحول السلسلة الفارغة المحددة إلى القيمة المكافئة من نوع عدد عائم مزدوج الدقة. |
| static **double** [ToDouble](./todouble/)(const char_t *) | يحول سلسلة c-string المحددة التي تحتوي على تمثيل رقمي لسلسلة إلى القيمة المكافئة من نوع عدد عائم مزدوج الدقة. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&) | يحول السلسلة المحددة التي تحتوي على تمثيل رقمي لسلسلة إلى القيمة المكافئة من نوع عدد عائم مزدوج الدقة. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يحول السلسلة المحددة التي تحتوي على تمثيل رقمي لسلسلة إلى القيمة المكافئة من نوع عدد عائم مزدوج الدقة باستخدام معلومات التنسيق المقدمة. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يحول السلسلة المحددة التي تحتوي على تمثيل رقمي لسلسلة إلى القيمة المكافئة من نوع عدد عائم مزدوج الدقة باستخدام معلومات التنسيق المقدمة ونمط الرقم. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **double** [ToDouble](./todouble/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يحول القيمة المغلفة المحددة إلى قيمة عدد عائم مزدوج الدقة. إذا كان نوع القيمة المغلفة هو [String](../string/)، يتم استخدام تنسيق السلسلة المحدد أثناء التحويل. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**bool**) | يحول القيمة البوليانية المحددة إلى عدد صحيح موقّع 16-بت مكافئ. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**uint8_t**) | يحول عددًا صحيحًا غير موقّع 8-بت المحدد إلى عدد صحيح موقّع 16-بت مكافئ. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**int8_t**) | يحول عددًا صحيحًا موقّع 8-بت المحدد إلى عدد صحيح موقّع 16-بت مكافئ. |
| static **int16_t** [ToInt16](./toint16/)(**uint16_t**) | يحول عددًا صحيحًا غير موقّع 16-بت المحدد إلى عدد صحيح موقّع 16-بت مكافئ. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**int16_t**) | يعيد العدد الصحيح الموقّع 16-بت المحدد. |
| static **int16_t** [ToInt16](./toint16/)(**uint32_t**) | يحول عددًا صحيحًا غير موقّع 32-بت المحدد إلى عدد صحيح موقّع 16-بت مكافئ. |
| static **int16_t** [ToInt16](./toint16/)(**int32_t**) | يحول عددًا صحيحًا موقّع 32-بت المحدد إلى عدد صحيح موقّع 16-بت مكافئ. |
| static **int16_t** [ToInt16](./toint16/)(**uint64_t**) | يحول عددًا صحيحًا غير موقّع 64-بت المحدد إلى عدد صحيح موقّع 16-بت مكافئ. |
| static **int16_t** [ToInt16](./toint16/)(**int64_t**) | يحول عددًا صحيحًا موقّع 64-بت المحدد إلى عدد صحيح موقّع 16-بت مكافئ. |
| static **int16_t** [ToInt16](./toint16/)(**float**) | يحول العدد من نوع float المحدد إلى عدد صحيح موقّع 16-بت مكافئ. |
| static **int16_t** [ToInt16](./toint16/)(**double**) | يحول العدد من نوع double المحدد إلى عدد صحيح موقّع 16-بت مكافئ. |
| static **int16_t** [ToInt16](./toint16/)(const [Decimal](../decimal/)\&) | يحول الرقم العشري المحدد إلى عدد صحيح موقّع 16-بت مكافئ. |
| static **int16_t** [ToInt16](./toint16/)(char_t) | يحول الحرف Unicode المحدد إلى عدد صحيح موقّع 16-بت مكافئ. |
| static **int16_t** [ToInt16](./toint16/)([DateTime](../datetime/)) | التحويل غير مدعوم. دائمًا يلقي استثناء InvalidCastException. |
| static constexpr **int16_t** [ToInt16](./toint16/)(std::nullptr_t) | يحول السلسلة الفارغة المحددة إلى القيمة المكافئة من نوع عدد صحيح 16-بت. |
| static **int16_t** [ToInt16](./toint16/)(const char_t *) | يحول سلسلة c-string المحددة التي تحتوي على تمثيل رقمي لسلسلة إلى القيمة المكافئة من نوع عدد صحيح 16-بت. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&) | يحول السلسلة المحددة التي تحتوي على تمثيل رقمي لسلسلة إلى القيمة المكافئة من نوع عدد صحيح 16-بت. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, int) | يحول السلسلة المحددة التي تحتوي على تمثيل رقمي لسلسلة في القاعدة المحددة إلى القيمة المكافئة من نوع عدد صحيح 16-بت. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يحول السلسلة المحددة التي تحتوي على تمثيل رقمي لسلسلة إلى القيمة المكافئة من نوع عدد صحيح 16-بت باستخدام معلومات التنسيق المقدمة. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يحول السلسلة المحددة التي تحتوي على تمثيل رقمي لسلسلة إلى القيمة المكافئة من نوع عدد صحيح 16-بت باستخدام معلومات التنسيق المقدمة ونمط الرقم. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int16_t** [ToInt16](./toint16/)([Enum](../enum/)) |  |
| static **int16_t** [ToInt16](./toint16/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يحول القيمة المغلفة المحددة إلى قيمة عدد صحيح 16-بت مكافئة. |
| static constexpr int [ToInt32](./toint32/)(**bool**) | يحول القيمة البوليانية المحددة إلى عدد صحيح موقّع 32-بت مكافئ. |
| static constexpr int [ToInt32](./toint32/)(**uint8_t**) | يحول عددًا صحيحًا غير موقّع 8-بت المحدد إلى عدد صحيح موقّع 32-بت مكافئ. |
| static constexpr int [ToInt32](./toint32/)(**int8_t**) | يقوم بتحويل عدد صحيح موقّع 8-بت المحدد إلى عدد صحيح موقّع 32-بت مكافئ. |
| static constexpr int [ToInt32](./toint32/)(**uint16_t**) | يقوم بتحويل عدد صحيح غير موقّع 16-بت المحدد إلى عدد صحيح موقّع 32-بت مكافئ. |
| static constexpr int [ToInt32](./toint32/)(**int16_t**) | يقوم بتحويل عدد صحيح موقّع 16-بت المحدد إلى عدد صحيح موقّع 32-بت مكافئ. |
| static int [ToInt32](./toint32/)(**uint32_t**) | يقوم بتحويل عدد صحيح غير موقّع 32-بت المحدد إلى عدد صحيح موقّع 32-بت مكافئ. |
| static constexpr int [ToInt32](./toint32/)(**int32_t**) | يعيد العدد الصحيح الموقّع 32-بت المحدد. |
| static int [ToInt32](./toint32/)(**uint64_t**) | يقوم بتحويل عدد صحيح غير موقّع 64-بت المحدد إلى عدد صحيح موقّع 32-بت مكافئ. |
| static int [ToInt32](./toint32/)(**int64_t**) | يقوم بتحويل عدد صحيح موقّ ع64-بت المحدد إلى عدد صحيح موقّ ع32-بت مكافئ. |
| static int [ToInt32](./toint32/)(**float**) | يقوم بتحويل العدد العائم المحدد إلى عدد صحيح موقّ ع32-بت مكافئ. |
| static int [ToInt32](./toint32/)(**double**) | يقوم بتحويل العدد المزدوج المحدد إلى عدد صحيح موقّ ع32-بت مكافئ. |
| static int [ToInt32](./toint32/)(const [Decimal](../decimal/)\&) | يقوم بتحويل العدد العشري المحدد إلى عدد صحيح موقّ ع32-بت مكافئ. |
| static constexpr int [ToInt32](./toint32/)(char_t) | يقوم بتحويل الحرف Unicode المحدد إلى عدد صحيح موقّ ع32-بت مكافئ. |
| static int [ToInt32](./toint32/)([DateTime](../datetime/)) | التحويل غير مدعوم. دائمًا يرمي استثناء InvalidCastException. |
| static constexpr int [ToInt32](./toint32/)(std::nullptr_t) | يقوم بتحويل السلسلة الفارغة المحددة إلى قيمة عدد صحيح 32-بت مكافئ. |
| static int [ToInt32](./toint32/)(const char_t *) | يقوم بتحويل سلسلة C المحددة التي تحتوي على تمثيل نصي لعدد إلى قيمة عدد صحيح 32-بت مكافئ. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&) | يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى قيمة عدد صحيح 32-بت مكافئ. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, int) | يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل نصي لعدد بالقاعدة المحددة إلى قيمة عدد صحيح 32-بت مكافئ. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى قيمة عدد صحيح 32-بت مكافئ باستخدام معلومات التنسيق المقدمة. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, std::nullptr_t) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى قيمة عدد صحيح 32-بت مكافئ باستخدام معلومات التنسيق المقدمة ونمط الرقم. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int32_t** [ToInt32](./toint32/)([Enum](../enum/)) |  |
| static int [ToInt32](./toint32/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يقوم بتحويل القيمة المعبأة المحددة إلى قيمة عدد صحيح 32-بت مكافئ. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**bool**) | يقوم بتحويل القيمة البوليانية المحددة إلى عدد صحيح موقّ ع64-بت مكافئ. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint8_t**) | يقوم بتحويل عدد صحيح غير موقّ ع8-بت المحدد إلى عدد صحيح موقّ ع64-بت مكافئ. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int8_t**) | يقوم بتحويل عدد صحيح موقّ ع8-بت المحدد إلى عدد صحيح موقّ ع64-بت مكافئ. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint16_t**) | يقوم بتحويل عدد صحيح غير موقّ ع16-بت المحدد إلى عدد صحيح موقّ ع64-بت مكافئ. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int16_t**) | يقوم بتحويل عدد صحيح موقّ ع16-بت المحدد إلى عدد صحيح موقّ ع64-بت مكافئ. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint32_t**) | يقوم بتحويل عدد صحيح غير موقّ ع32-بت المحدد إلى عدد صحيح موقّ ع64-بت مكافئ. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int32_t**) | يقوم بتحويل عدد صحيح موقّ ع32-بت المحدد إلى عدد صحيح موقّ ع64-بت مكافئ. |
| static **int64_t** [ToInt64](./toint64/)(**uint64_t**) | يقوم بتحويل عدد صحيح غير موقّ ع64-بت المحدد إلى عدد صحيح موقّ ع64-بت مكافئ. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int64_t**) | يعيد العدد الصحيح الموقّع 64-بت المحدد. |
| static **int64_t** [ToInt64](./toint64/)(**float**) | يقوم بتحويل العدد العائم المحدد إلى عدد صحيح موقّ ع64-بت مكافئ. |
| static **int64_t** [ToInt64](./toint64/)(**double**) | يقوم بتحويل العدد المزدوج المحدد إلى عدد صحيح موقّ ع64-بت مكافئ. |
| static **int64_t** [ToInt64](./toint64/)(const [Decimal](../decimal/)\&) | يقوم بتحويل العدد العشري المحدد إلى عدد صحيح موقّ ع64-بت مكافئ. |
| static constexpr **int64_t** [ToInt64](./toint64/)(char_t) | يقوم بتحويل الحرف Unicode المحدد إلى عدد صحيح موقّ ع64-بت مكافئ. |
| static **int64_t** [ToInt64](./toint64/)([DateTime](../datetime/)) | التحويل غير مدعوم. دائمًا يرمي استثناء InvalidCastException. |
| static constexpr **int64_t** [ToInt64](./toint64/)(std::nullptr_t) | يقوم بتحويل السلسلة الفارغة المحددة إلى قيمة عدد صحيح 64-بت مكافئ. |
| static **int64_t** [ToInt64](./toint64/)(const char_t *) | يقوم بتحويل سلسلة C المحددة التي تحتوي على تمثيل نصي لعدد إلى قيمة عدد صحيح 64-بت مكافئ. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&) | يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى قيمة عدد صحيح 64-بت مكافئ. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, int) | يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل نصي لعدد بالقاعدة المحددة إلى قيمة عدد صحيح 64-بت مكافئ. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى قيمة عدد صحيح 64-بت مكافئ باستخدام معلومات التنسيق المقدمة. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى قيمة عدد صحيح 64-بت مكافئ باستخدام معلومات التنسيق المقدمة ونمط الرقم. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int64_t** [ToInt64](./toint64/)([Enum](../enum/)) |  |
| static **int64_t** [ToInt64](./toint64/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يقوم بتحويل القيمة المعبأة المحددة إلى قيمة عدد صحيح 64-بت مكافئ. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(**bool**) | يقوم بتحويل القيمة البوليانية المحددة إلى عدد صحيح موقّ ع8-بت مكافئ. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint8_t**) | يقوم بتحويل عدد صحيح غير موقّ ع8-بت المحدد إلى عدد صحيح موقّ ع8-بت مكافئ. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(**int8_t**) | يعيد العدد الصحيح الموقّع 8-بت المحدد. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint16_t**) | يقوم بتحويل عدد صحيح غير موقّ ع16-بت المحدد إلى عدد صحيح موقّ ع8-بت مكافئ. |
| static **int8_t** [ToSByte](./tosbyte/)(**int16_t**) | يقوم بتحويل عدد صحيح موقّ ع16-بت المحدد إلى عدد صحيح موقّ ع8-بت مكافئ. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint32_t**) | يقوم بتحويل عدد صحيح غير موقّ ع32-بت المحدد إلى عدد صحيح موقّ ع8-بت مكافئ. |
| static **int8_t** [ToSByte](./tosbyte/)(**int32_t**) | يقوم بتحويل عدد صحيح موقّ ع32-بت المحدد إلى عدد صحيح موقّ ع8-بت مكافئ. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint64_t**) | يقوم بتحويل عدد صحيح غير موقّ ع64-بت المحدد إلى عدد صحيح موقّ ع8-بت مكافئ. |
| static **int8_t** [ToSByte](./tosbyte/)(**int64_t**) | يقوم بتحويل عدد صحيح موقّ ع64-بت المحدد إلى عدد صحيح موقّ ع8-بت مكافئ. |
| static **int8_t** [ToSByte](./tosbyte/)(**float**) | يقوم بتحويل العدد العائم المحدد إلى عدد صحيح موقّ ع8-بت مكافئ. |
| static **int8_t** [ToSByte](./tosbyte/)(**double**) | يقوم بتحويل العدد المزدوج المحدد إلى عدد صحيح موقّ ع8-بت مكافئ. |
| static **int8_t** [ToSByte](./tosbyte/)(const [Decimal](../decimal/)\&) | يقوم بتحويل العدد العشري المحدد إلى عدد صحيح موقّ ع8-بت مكافئ. |
| static **int8_t** [ToSByte](./tosbyte/)(char_t) | يقوم بتحويل الحرف Unicode المحدد إلى عدد صحيح موقّ ع8-بت مكافئ. |
| static **int8_t** [ToSByte](./tosbyte/)([DateTime](../datetime/)) | التحويل غير مدعوم. دائمًا يرمي استثناء InvalidCastException. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(std::nullptr_t) | يقوم بتحويل السلسلة الفارغة المحددة إلى قيمة عدد صحيح 8-بت مكافئ. |
| static **int8_t** [ToSByte](./tosbyte/)(const char_t *) | يقوم بتحويل سلسلة C المحددة التي تحتوي على تمثيل نصي لعدد إلى قيمة عدد صحيح 8-بت مكافئ. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&) | يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى قيمة عدد صحيح 8-بت مكافئ. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, int) | يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل نصي لعدد بالقاعدة المحددة إلى قيمة عدد صحيح 8-بت مكافئ. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى قيمة عدد صحيح غير موقّ 8-بت مكافئ باستخدام معلومات التنسيق المقدمة. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى قيمة عدد صحيح 8-بت مكافئ باستخدام معلومات التنسيق المقدمة ونمط الرقم. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int8_t** [ToSByte](./tosbyte/)([Enum](../enum/)) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يقوم بتحويل القيمة المعبأة المحددة إلى قيمة عدد صحيح 8-بت مكافئ. |
| static constexpr **float** [ToSingle](./tosingle/)(**bool**) | يقوم بتحويل القيمة البوليانية المحددة إلى عدد عائم بدقة أحادية. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint8_t**) | يقوم بتحويل عدد صحيح غير موقّ ع8-بت المحدد إلى عدد عائم بدقة أحادية مكافئ. |
| static constexpr **float** [ToSingle](./tosingle/)(**int8_t**) | يقوم بتحويل عدد صحيح موقّ ع8-بت المحدد إلى عدد عائم بدقة أحادية مكافئ. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint16_t**) | يقوم بتحويل عدد صحيح غير موقّ ع16-بت المحدد إلى عدد عائم بدقة أحادية مكافئ. |
| static constexpr **float** [ToSingle](./tosingle/)(**int16_t**) | يقوم بتحويل عدد صحيح موقّ ع16-بت المحدد إلى عدد عائم بدقة أحادية مكافئ. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint32_t**) | يقوم بتحويل عدد صحيح غير موقّ ع32-بت المحدد إلى عدد عائم بدقة أحادية مكافئ. |
| static constexpr **float** [ToSingle](./tosingle/)(**int32_t**) | يقوم بتحويل عدد صحيح موقّ ع32-بت المحدد إلى عدد عائم بدقة أحادية مكافئ. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint64_t**) | يحوّل العدد الصحيح غير الموقع 64-بت المحدد إلى عدد عائم بدقة أحادية مكافئ. |
| static constexpr **float** [ToSingle](./tosingle/)(**int64_t**) | يحوّل العدد الصحيح الموقع 64-بت المحدد إلى عدد عائم بدقة أحادية مكافئ. |
| static constexpr **float** [ToSingle](./tosingle/)(**float**) | يرجع العدد العائم المحدد. |
| static constexpr **float** [ToSingle](./tosingle/)(**double**) | يحوّل العدد ذو الدقة المزدوجة المحدد إلى عدد عائم بدقة أحادية مكافئ. |
| static **float** [ToSingle](./tosingle/)(const [Decimal](../decimal/)\&) | يحوّل العدد العشري المحدد إلى عدد عائم بدقة أحادية مكافئ. |
| static **float** [ToSingle](./tosingle/)(char_t) | التحويل غير مدعوم. دائمًا يرمي استثناء InvalidCastException. |
| static **float** [ToSingle](./tosingle/)([DateTime](../datetime/)) | التحويل غير مدعوم. دائمًا يرمي استثناء InvalidCastException. |
| static constexpr **float** [ToSingle](./tosingle/)(std::nullptr_t) | يحوّل السلسلة null المحددة إلى قيمة ذات دقة أحادية مكافئة. |
| static **float** [ToSingle](./tosingle/)(const char_t *) | يحوّل السلسلة c-string المحددة التي تمثل عددًا إلى قيمة ذات دقة أحادية مكافئة. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&) | يحوّل السلسلة المحددة التي تمثل عددًا إلى قيمة ذات دقة أحادية مكافئة. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يحوّل السلسلة المحددة التي تمثل عددًا إلى قيمة ذات دقة أحادية مكافئة باستخدام معلومات التنسيق المتوفرة. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يحوّل السلسلة المحددة التي تمثل عددًا إلى قيمة ذات دقة أحادية مكافئة باستخدام معلومات التنسيق المتوفرة ونمط الرقم. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **float** [ToSingle](./tosingle/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يحوّل القيمة المعلبة المحددة إلى قيمة عائمة بدقة أحادية. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**) | يحوّل القيمة المحددة إلى تمثيلها كسلسلة. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**) | يحوّل القيمة المحددة إلى تمثيلها كسلسلة. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**) | يحوّل القيمة المحددة إلى تمثيلها بسلسلة. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**) | يحوّل القيمة المحددة إلى تمثيلها بسلسلة. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**) | يحوّل القيمة المحددة إلى تمثيلها بسلسلة. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**) | يحوّل القيمة المحددة إلى تمثيلها بسلسلة. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**) | يحوّل القيمة المحددة إلى تمثيلها بسلسلة. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**) | يحوّل القيمة المحددة إلى تمثيلها بسلسلة. |
| static [String](../string/) [ToString](./tostring/)(**float**) | يحوّل القيمة المحددة إلى تمثيلها بسلسلة. |
| static [String](../string/) [ToString](./tostring/)(**double**) | يحوّل القيمة المحددة إلى تمثيلها بسلسلة. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&) | يحوّل القيمة المحددة إلى تمثيلها بسلسلة. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/)) | يحوّل القيمة المحددة إلى تمثيلها بسلسلة. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يحوّل القيمة المحددة إلى سلسلة باستخدام معلومات التنسيق الخاصة بالثقافة. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يحوّل القيمة المحددة إلى سلسلة باستخدام معلومات التنسيق الخاصة بالثقافة. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يحوّل القيمة المحددة إلى سلسلة باستخدام معلومات التنسيق الخاصة بالثقافة. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يحوّل القيمة المحددة إلى سلسلة باستخدام معلومات التنسيق الخاصة بالثقافة. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يحوّل القيمة المحددة إلى سلسلة باستخدام معلومات التنسيق الخاصة بالثقافة. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يحوّل القيمة المحددة إلى سلسلة باستخدام معلومات التنسيق الخاصة بالثقافة. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يحوّل القيمة المحددة إلى سلسلة باستخدام معلومات التنسيق الخاصة بالثقافة. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يحوّل القيمة المحددة إلى سلسلة باستخدام معلومات التنسيق الخاصة بالثقافة. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يحوّل القيمة المحددة إلى سلسلة باستخدام معلومات التنسيق الخاصة بالثقافة. |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يحوّل القيمة المحددة إلى سلسلة باستخدام معلومات التنسيق الخاصة بالثقافة. |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يحوّل القيمة المحددة إلى سلسلة باستخدام معلومات التنسيق الخاصة بالثقافة. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يحوّل القيمة المحددة إلى سلسلة باستخدام معلومات التنسيق الخاصة بالثقافة. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يحوّل القيمة المحددة إلى تمثيلها كسلسلة باستخدام تنسيق السلسلة المحدد ومعلومات التنسيق الخاصة بالثقافة المقدمة من كائن [IFormatProvider](../iformatprovider/) المحدد. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يحوّل القيمة المحددة إلى تمثيلها كسلسلة باستخدام تنسيق السلسلة المحدد ومعلومات التنسيق الخاصة بالثقافة المقدمة من كائن [IFormatProvider](../iformatprovider/) المحدد. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يحوّل القيمة المحددة إلى تمثيلها كسلسلة باستخدام تنسيق السلسلة المحدد ومعلومات التنسيق الخاصة بالثقافة المقدمة من كائن [IFormatProvider](../iformatprovider/) المحدد. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يحوّل القيمة المحددة إلى تمثيلها كسلسلة باستخدام تنسيق السلسلة المحدد ومعلومات التنسيق الخاصة بالثقافة المقدمة من كائن [IFormatProvider](../iformatprovider/) المحدد. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يحوّل القيمة المحددة إلى تمثيلها كسلسلة باستخدام تنسيق السلسلة المحدد ومعلومات التنسيق الخاصة بالثقافة المقدمة من كائن [IFormatProvider](../iformatprovider/) المحدد. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يحوّل القيمة المحددة إلى تمثيلها كسلسلة باستخدام تنسيق السلسلة المحدد ومعلومات التنسيق الخاصة بالثقافة المقدمة من كائن [IFormatProvider](../iformatprovider/) المحدد. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يقوم بتحويل القيمة المحددة إلى تمثيلها النصي باستخدام تنسيق السلسلة المحدد ومعلومات تنسيق الثقافة المقدمة من الكائن [IFormatProvider](../iformatprovider/) المحدد. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يقوم بتحويل القيمة المحددة إلى تمثيلها النصي باستخدام تنسيق السلسلة المحدد ومعلومات تنسيق الثقافة المقدمة من الكائن [IFormatProvider](../iformatprovider/) المحدد. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يقوم بتحويل القيمة المحددة إلى تمثيلها النصي باستخدام تنسيق السلسلة المحدد ومعلومات تنسيق الثقافة المقدمة من الكائن [IFormatProvider](../iformatprovider/) المحدد. |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يقوم بتحويل القيمة المحددة إلى تمثيلها النصي باستخدام تنسيق السلسلة المحدد ومعلومات تنسيق الثقافة المقدمة من الكائن [IFormatProvider](../iformatprovider/) المحدد. |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يقوم بتحويل القيمة المحددة إلى تمثيلها النصي باستخدام تنسيق السلسلة المحدد ومعلومات تنسيق الثقافة المقدمة من الكائن [IFormatProvider](../iformatprovider/) المحدد. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يقوم بتحويل القيمة المحددة إلى تمثيلها النصي باستخدام تنسيق السلسلة المحدد ومعلومات تنسيق الثقافة المقدمة من الكائن [IFormatProvider](../iformatprovider/) المحدد. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Guid](../guid/)\&) | يقوم بتحويل القيمة المحددة إلى نص. |
| static [String](../string/) [ToString](./tostring/)(const [Guid](../guid/)\&, const [String](../string/)\&) | يقوم بتحويل القيمة المحددة إلى نص باستخدام تنسيق السلسلة المحدد. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), std::nullptr_t) | يقوم بتحويل مصفوفة الأحرف Unicode المحددة إلى نص. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يقوم بتحويل مصفوفة الأحرف Unicode المحددة إلى نص باستخدام معلومات تنسيق الثقافة المقدمة من الكائن [IFormatProvider](../iformatprovider/) المحدد. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) | يعيد القيمة المحددة؛ لا يتم أي تحويل. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يعيد القيمة المحددة؛ لا يتم أي تحويل. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | يعيد القيمة المحددة؛ لا يتم أي تحويل. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) | يعيد القيمة المحددة؛ لا يتم أي تحويل. |
| static [String](../string/) [ToString](./tostring/)(char_t, std::nullptr_t) | يعيد القيمة المحددة؛ لا يتم أي تحويل. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يعيد القيمة المحددة؛ لا يتم أي تحويل. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | يعيد القيمة المحددة؛ لا يتم أي تحويل. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يعيد القيمة المحددة؛ لا يتم أي تحويل. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | يعيد القيمة المحددة؛ لا يتم أي تحويل. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, std::nullptr_t) | يعيد القيمة المحددة؛ لا يتم أي تحويل. |
| static [String](../string/) [ToString](./tostring/)(**bool**, std::nullptr_t) | يقوم بتحويل القيمة المحددة إلى تمثيلها النصي. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يقوم بتحويل القيمة المحددة إلى تمثيلها النصي. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | يقوم بتحويل القيمة المحددة إلى تمثيلها النصي. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) | يقوم بتحويل القيمة المحددة إلى تمثيلها النصي. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يقوم بتحويل القيمة المحددة إلى تمثيلها النصي. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | يقوم بتحويل القيمة المحددة إلى تمثيلها النصي. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, std::nullptr_t) | يقوم بتحويل القيمة المحددة إلى تمثيلها النصي. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, int) | يقوم بتحويل القيمة الصحيحة المحددة إلى تمثيلها النصي في القاعدة المحددة. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, int) | يقوم بتحويل القيمة الصحيحة المحددة إلى تمثيلها النصي في القاعدة المحددة. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, int) | يقوم بتحويل القيمة الصحيحة المحددة إلى تمثيلها النصي في القاعدة المحددة. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, int) | يقوم بتحويل القيمة الصحيحة المحددة إلى تمثيلها النصي في القاعدة المحددة. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يقوم بتحويل القيمة المعلبة المحددة إلى تمثيلها النصي. إذا كان نوع القيمة المعلبة هو [String](../string/)، يتم استخدام تنسيق السلسلة المحدد أثناء التحويل. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**bool**) | يقوم بتحويل القيمة البوليانية المحددة إلى عدد صحيح غير موقع 16-بت مكافئ. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**uint8_t**) | يقوم بتحويل القيمة 8-بت غير موقع إلى عدد صحيح غير موقع 16-بت مكافئ. |
| static **uint16_t** [ToUInt16](./touint16/)(**int8_t**) | يقوم بتحويل القيمة 8-بت موقع إلى عدد صحيح غير موقع 16-بت مكافئ. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**uint16_t**) | يعيد العدد الصحيح غير الموقع 16-بت المحدد. |
| static **uint16_t** [ToUInt16](./touint16/)(**int16_t**) | يقوم بتحويل القيمة 16-بت موقع إلى عدد صحيح غير موقع 16-بت مكافئ. |
| static **uint16_t** [ToUInt16](./touint16/)(**uint32_t**) | يقوم بتحويل القيمة 32-بت غير موقع إلى عدد صحيح غير موقع 16-بت مكافئ. |
| static **uint16_t** [ToUInt16](./touint16/)(**int32_t**) | يقوم بتحويل القيمة 32-بت موقع إلى عدد صحيح غير موقع 16-بت مكافئ. |
| static **uint16_t** [ToUInt16](./touint16/)(**uint64_t**) | يقوم بتحويل القيمة 64-بت غير موقع إلى عدد صحيح غير موقع 16-بت مكافئ. |
| static **uint16_t** [ToUInt16](./touint16/)(**int64_t**) | يقوم بتحويل القيمة 64-بت موقع إلى عدد صحيح غير موقع 16-بت مكافئ. |
| static **uint16_t** [ToUInt16](./touint16/)(**float**) | يقوم بتحويل عدد الفاصلة العائمة المحدد إلى عدد صحيح غير موقع 16-بت مكافئ. |
| static **uint16_t** [ToUInt16](./touint16/)(**double**) | يقوم بتحويل عدد الـ double المحدد إلى عدد صحيح غير موقع 16-بت مكافئ. |
| static **uint16_t** [ToUInt16](./touint16/)(const [Decimal](../decimal/)\&) | يقوم بتحويل العدد العشري المحدد إلى عدد صحيح غير موقع 16-بت مكافئ. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(char_t) | يقوم بتحويل الحرف Unicode المحدد إلى عدد صحيح غير موقع 16-بت مكافئ. |
| static **uint16_t** [ToUInt16](./touint16/)([DateTime](../datetime/)) | التحويل غير مدعوم. دائمًا يُلقِي استثناء InvalidCastException. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(std::nullptr_t) | يقوم بتحويل السلسلة الفارغة إلى قيمة عدد صحيح غير موقع 16-بت مكافئ. |
| static **uint16_t** [ToUInt16](./touint16/)(const char_t *) | يقوم بتحويل سلسلة C التي تحتوي على تمثيل نصي لعدد إلى قيمة عدد صحيح غير موقع 16-بت مكافئ. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&) | يقوم بتحويل السلسلة التي تحتوي على تمثيل نصي لعدد إلى قيمة عدد صحيح غير موقع 16-بت مكافئ. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, int) | يقوم بتحويل السلسلة التي تحتوي على تمثيل نصي لعدد في القاعدة المحددة إلى قيمة عدد صحيح غير موقع 16-بت مكافئ. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يقوم بتحويل السلسلة التي تحتوي على تمثيل نصي لعدد إلى قيمة عدد صحيح غير موقع 16-بت مكافئ باستخدام معلومات التنسيق المقدمة. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يقوم بتحويل السلسلة التي تحتوي على تمثيل نصي لعدد إلى قيمة عدد صحيح غير موقع 16-بت مكافئ باستخدام معلومات التنسيق ونمط العدد المقدمة. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint16_t** [ToUInt16](./touint16/)([Enum](../enum/)) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يقوم بتحويل القيمة المعلبة المحددة إلى قيمة عدد صحيح غير موقع 16-بت مكافئ. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**bool**) | يقوم بتحويل القيمة البوليانية المحددة إلى عدد صحيح غير موقع 32-بت مكافئ. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint8_t**) | يقوم بتحويل القيمة 8-بت غير موقع إلى عدد صحيح غير موقع 32-بت مكافئ. |
| static **uint32_t** [ToUInt32](./touint32/)(**int8_t**) | يقوم بتحويل القيمة 8-بت موقع إلى عدد صحيح غير موقع 32-بت مكافئ. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint16_t**) | يقوم بتحويل القيمة 16-بت غير موقع إلى عدد صحيح غير موقع 32-بت مكافئ. |
| static **uint32_t** [ToUInt32](./touint32/)(**int16_t**) | يقوم بتحويل القيمة 16-بت موقع إلى عدد صحيح غير موقع 32-بت مكافئ. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint32_t**) | يعيد العدد الصحيح غير الموقع 32-بت المحدد. |
| static **uint32_t** [ToUInt32](./touint32/)(**int32_t**) | يقوم بتحويل عدد صحيح 32-بت موقع إلى عدد صحيح غير موقع مقاس 32-بت مكافئ. |
| static **uint32_t** [ToUInt32](./touint32/)(**uint64_t**) | يقوم بتحويل عدد صحيح غير موقع 64-بت إلى عدد صحيح غير موقع مقاس 32-بت مكافئ. |
| static **uint32_t** [ToUInt32](./touint32/)(**int64_t**) | يقوم بتحويل عدد صحيح موقع 64-بت إلى عدد صحيح غير موقع مقاس 32-بت مكافئ. |
| static **uint32_t** [ToUInt32](./touint32/)(**float**) | يقوم بتحويل الرقم العائم المحدد إلى عدد صحيح غير موقع مقاس 32-بت مكافئ. |
| static **uint32_t** [ToUInt32](./touint32/)(**double**) | يقوم بتحويل الرقم مزدوج الدقة المحدد إلى عدد صحيح غير موقع مقاس 32-بت مكافئ. |
| static **uint32_t** [ToUInt32](./touint32/)(const [Decimal](../decimal/)\&) | يقوم بتحويل العدد العشري المحدد إلى عدد صحيح غير موقع مقاس 32-بت مكافئ. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(char_t) | يقوم بتحويل الحرف يونيكود المحدد إلى عدد صحيح غير موقع مقاس 32-بت مكافئ. |
| static **uint32_t** [ToUInt32](./touint32/)([DateTime](../datetime/)) | التحويل غير مدعوم. دائمًا يرمى InvalidCastException. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(std::nullptr_t) | يقوم بتحويل السلسلة الفارغة المحددة إلى قيمة عدد صحيح غير موقع مقاس 32-بت مكافئة. |
| static **uint32_t** [ToUInt32](./touint32/)(const char_t *) | يقوم بتحويل c-string المحدد الذي يحتوي على تمثيل النص لعدد إلى القيمة المكافئة لعدد صحيح غير موقع مقاس 32-بت. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&) | يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل النص لعدد إلى القيمة المكافئة لعدد صحيح غير موقع مقاس 32-بت. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, int) | يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل النص لعدد بالقاعدة المحددة إلى القيمة المكافئة لعدد صحيح غير موقع مقاس 32-بت. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل النص لعدد إلى القيمة المكافئة لعدد صحيح غير موقع مقاس 32-بت باستخدام معلومات التنسيق المقدمة. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل النص لعدد إلى القيمة المكافئة لعدد صحيح غير موقع مقاس 32-بت باستخدام معلومات التنسيق المقدمة ونمط الرقم. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint32_t** [ToUInt32](./touint32/)([Enum](../enum/)) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يقوم بتحويل القيمة المعبأة المحددة إلى قيمة عدد صحيح غير موقع مقاس 32-بت مكافئة. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**bool**) | يقوم بتحويل القيمة البوليانية المحددة إلى عدد صحيح غير موقع مقاس 64-بت مكافئ. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint8_t**) | يقوم بتحويل عدد صحيح غير موقع 8-بت إلى عدد صحيح غير موقع مقاس 64-بت مكافئ. |
| static **uint64_t** [ToUInt64](./touint64/)(**int8_t**) | يقوم بتحويل عدد صحيح موقع 8-بت إلى عدد صحيح غير موقع مقاس 64-بت مكافئ. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint16_t**) | يقوم بتحويل عدد صحيح غير موقع 16-بت إلى عدد صحيح غير موقع مقاس 64-بت مكافئ. |
| static **uint64_t** [ToUInt64](./touint64/)(**int16_t**) | يقوم بتحويل عدد صحيح موقع 16-بت إلى عدد صحيح غير موقع مقاس 64-بت مكافئ. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint32_t**) | يقوم بتحويل عدد صحيح غير موقع 32-بت إلى عدد صحيح غير موقع مقاس 64-بت مكافئ. |
| static **uint64_t** [ToUInt64](./touint64/)(**int32_t**) | يقوم بتحويل عدد صحيح موقع 32-بت إلى عدد صحيح غير موقع مقاس 64-بت مكافئ. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint64_t**) | يرجع عدد صحيح غير موقع 64-بت المحدد. |
| static **uint64_t** [ToUInt64](./touint64/)(**int64_t**) | يقوم بتحويل عدد صحيح موقع 64-بت إلى عدد صحيح غير موقع مقاس 64-بت مكافئ. |
| static **uint64_t** [ToUInt64](./touint64/)(**float**) | يقوم بتحويل الرقم العائم المحدد إلى عدد صحيح غير موقع مقاس 64-بت مكافئ. |
| static **uint64_t** [ToUInt64](./touint64/)(**double**) | يقوم بتحويل الرقم مزدوج الدقة المحدد إلى عدد صحيح غير موقع مقاس 64-بت مكافئ. |
| static **uint64_t** [ToUInt64](./touint64/)(const [Decimal](../decimal/)\&) | يقوم بتحويل العدد العشري المحدد إلى عدد صحيح غير موقع مقاس 64-بت مكافئ. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(char_t) | يقوم بتحويل الحرف يونيكود المحدد إلى عدد صحيح غير موقع مقاس 64-بت مكافئ. |
| static **uint64_t** [ToUInt64](./touint64/)([DateTime](../datetime/)) | التحويل غير مدعوم. دائمًا يرمى InvalidCastException. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(std::nullptr_t) | يقوم بتحويل السلسلة الفارغة المحددة إلى قيمة عدد صحيح غير موقع مقاس 64-بت مكافئة. |
| static **uint64_t** [ToUInt64](./touint64/)(const char_t *) | يقوم بتحويل c-string المحدد الذي يحتوي على تمثيل النص لعدد إلى القيمة المكافئة لعدد صحيح غير موقع مقاس 64-بت. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&) | يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل النص لعدد إلى القيمة المكافئة لعدد صحيح غير موقع مقاس 64-بت. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, int) | يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل النص لعدد بالقاعدة المحددة إلى القيمة المكافئة لعدد صحيح غير موقع مقاس 64-بت. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل النص لعدد إلى القيمة المكافئة لعدد صحيح غير موقع مقاس 64-بت باستخدام معلومات التنسيق المقدمة. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل النص لعدد إلى القيمة المكافئة لعدد صحيح غير موقع مقاس 64-بت باستخدام معلومات التنسيق المقدمة ونمط الرقم. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint64_t** [ToUInt64](./touint64/)([Enum](../enum/)) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يقوم بتحويل القيمة المعبأة المحددة إلى قيمة عدد صحيح غير موقع مقاس 64-بت مكافئة. |
## راجع أيضًا

* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)