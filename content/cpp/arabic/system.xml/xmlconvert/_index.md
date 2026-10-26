---
title: XmlConvert
second_title: مرجع API Aspose.Slides للغة C++
description: يقوم بترميز وفك ترميز أسماء XML، ويوفر طرقًا لتحويل بين أنواع وقت التشغيل وأنواع لغة تعريف مخطط XML (XSD). عند تحويل أنواع البيانات، تكون القيم المعادة مستقلة عن الإعدادات المحلية.
type: docs
weight: 157
url: /ar/system.xml/xmlconvert/
---
## فئة XmlConvert

Encodes and decodes XML names, and provides methods for converting between runtime types and XML [Schema](../../system.xml.schema/) definition language (XSD) types. When converting data types, the values returned are locale-independent.

```cpp
class XmlConvert : public System::Object
```

## الأساليب

| الطريقة | الوصف |
| --- | --- |
| static [String](../../system/string/) [DecodeName](./decodename/)(const [String](../../system/string/)\&) | يفك تشفير اسم. تقوم هذه الطريقة بالعكس من طرق XmlConvert::EncodeName(String) و XmlConvert::EncodeLocalName(String). |
| static [String](../../system/string/) [EncodeLocalName](./encodelocalname/)(const [String](../../system/string/)\&) | يحوِّل الاسم إلى اسم محلي XML صالح. |
| static [String](../../system/string/) [EncodeName](./encodename/)(const [String](../../system/string/)\&) | يحوِّل الاسم إلى اسم XML صالح. |
| static [String](../../system/string/) [EncodeNmToken](./encodenmtoken/)(const [String](../../system/string/)\&) | يتحقق من صحة الاسم وفقًا لمواصفة XML. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يقلِّد مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين على الرغم من أن IEC 60559:1989 تُعرّف أن NaN غير مساوي لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يقلِّد مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين على الرغم من أن IEC 60559:1989 تُعرّف أن NaN غير مساوي لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عدّاد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة (hashing) الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموضّح بواسطة targetType. مماثل لمعامل C# 'is'. |
| static **bool** [IsNCNameChar](./isncnamechar/)(char16_t) | يتحقق مما إذا كان الحرف المدخل من نوع حرف غير نقطتين (colon) صالح. |
| static **bool** [IsPublicIdChar](./ispublicidchar/)(char16_t) | يعيد نسخة الحرف المدخل إذا كان الحرف في الوسيط من نوع حرف معرف عام صالح، وإلا **nullptr**. |
| static **bool** [IsStartNCNameChar](./isstartncnamechar/)(char16_t) | يتحقق مما إذا كان الحرف المدخل من نوع حرف بدء اسم صالح. |
| static **bool** [IsWhitespaceChar](./iswhitespacechar/)(char16_t) | يتحقق مما إذا كان الحرف المدخل من نوع مسافة بيضاء XML صالحة. |
| static **bool** [IsXmlChar](./isxmlchar/)(char16_t) | يتحقق مما إذا كان الحرف المدخل من نوع حرف XML صالح. |
| static **bool** [IsXmlSurrogatePair](./isxmlsurrogatepair/)(char16_t, char16_t) | يتحقق مما إذا كان الزوج التعويضي (surrogate pair) المدخل من الأحرف هو حرف XML صالح. |
| void [Lock](../../system/object/lock/)() | يطبق إقفال بيان C# lock(). يُستدعى مباشرة أو يستخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ الكائن. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات حسب المرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات حسب المرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدّاد المرجع المشترك بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط وسيطة القالب رقم n إلى مؤشر ضعيف (بدلاً من المشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| static **bool** [ToBoolean](./toboolean/)([String](../../system/string/)) | يحوِّل [String](../../system/string/) إلى ما يعادل [Boolean](../../system/boolean/). |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../../system/string/)\&) | يحوِّل [String](../../system/string/) إلى ما يعادل [Byte](../../system/byte/). |
| static char16_t [ToChar](./tochar/)(const [String](../../system/string/)\&) | يحوِّل [String](../../system/string/) إلى ما يعادل [Char](../../system/char/). |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&) | يحوِّل [String](../../system/string/) إلى ما يعادل [DateTime](../../system/datetime/). |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | يحوِّل [String](../../system/string/) إلى ما يعادل [DateTime](../../system/datetime/). |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | يحوِّل [String](../../system/string/) إلى ما يعادل [DateTime](../../system/datetime/). |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/)) | يحوِّل [String](../../system/string/) إلى [DateTime](../../system/datetime/) باستخدام XmlDateTimeSerializationMode المحدد. |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&) | يحوِّل [String](../../system/string/) المزوّد إلى ما يعادل [DateTimeOffset](../../system/datetimeoffset/). |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | يحوِّل [String](../../system/string/) المزوّد إلى ما يعادل [DateTimeOffset](../../system/datetimeoffset/). |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | يحوِّل [String](../../system/string/) المزوّد إلى ما يعادل [DateTimeOffset](../../system/datetimeoffset/). |
| static [Decimal](../../system/decimal/) [ToDecimal](./todecimal/)(const [String](../../system/string/)\&) | يحوِّل [String](../../system/string/) إلى ما يعادل [Decimal](../../system/decimal/). |
| static **double** [ToDouble](./todouble/)([String](../../system/string/)) | يحوِّل [String](../../system/string/) إلى ما يعادل [Double](../../system/double/). |
| static [Guid](../../system/guid/) [ToGuid](./toguid/)(const [String](../../system/string/)\&) | يحوِّل [String](../../system/string/) إلى ما يعادل [Guid](../../system/guid/). |
| static **int16_t** [ToInt16](./toint16/)(const [String](../../system/string/)\&) | يحوِّل [String](../../system/string/) إلى ما يعادل [Int16](../../system/int16/). |
| static **int32_t** [ToInt32](./toint32/)(const [String](../../system/string/)\&) | يحوِّل [String](../../system/string/) إلى ما يعادل [Int32](../../system/int32/). |
| static **int64_t** [ToInt64](./toint64/)(const [String](../../system/string/)\&) | يحوِّل [String](../../system/string/) إلى ما يعادل [Int64](../../system/int64/). |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../../system/string/)\&) | يحوِّل [String](../../system/string/) إلى ما يعادل [SByte](../../system/sbyte/). |
| static **float** [ToSingle](./tosingle/)([String](../../system/string/)) | يحوِّل [String](../../system/string/) إلى ما يعادل [Single](../../system/single/). |
| static [String](../../system/string/) [ToString](./tostring/)(**bool**) | يحوِّل [Boolean](../../system/boolean/) إلى [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(char16_t) | يحوِّل [Char](../../system/char/) إلى [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([Decimal](../../system/decimal/)) | يحوِّل [Decimal](../../system/decimal/) إلى [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**int8_t**) | يحوِّل [SByte](../../system/sbyte/) إلى [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**int16_t**) | يحوِّل [Int16](../../system/int16/) إلى [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**int32_t**) | يحوِّل [Int32](../../system/int32/) إلى [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**int64_t**) | يحوِّل [Int64](../../system/int64/) إلى [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**uint8_t**) | يحوِّل [Byte](../../system/byte/) إلى [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**uint16_t**) | يحوِّل [UInt16](../../system/uint16/) إلى [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**uint32_t**) | يحوِّل [UInt32](../../system/uint32/) إلى [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**uint64_t**) | يحوِّل [UInt64](../../system/uint64/) إلى [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**float**) | يحوِّل [Single](../../system/single/) إلى [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**double**) | يحوِّل [Double](../../system/double/) إلى [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([TimeSpan](../../system/timespan/)) | يحوِّل [TimeSpan](../../system/timespan/) إلى [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/)) | يحوِّل [DateTime](../../system/datetime/) إلى [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/), const [String](../../system/string/)\&) | يحوِّل [DateTime](../../system/datetime/) إلى [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/), [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/)) | يحوِّل [DateTime](../../system/datetime/) إلى [String](../../system/string/) باستخدام XmlDateTimeSerializationMode المحدد. |
| static [String](../../system/string/) [ToString](./tostring/)([DateTimeOffset](../../system/datetimeoffset/)) | يحوِّل [DateTimeOffset](../../system/datetimeoffset/) المزوّد إلى [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([DateTimeOffset](../../system/datetimeoffset/), const [String](../../system/string/)\&) | يحوِّل [DateTimeOffset](../../system/datetimeoffset/) المزوّد إلى [String](../../system/string/) بالتنسيق المحدد. |
| static [String](../../system/string/) [ToString](./tostring/)([Guid](../../system/guid/)) | يحوِّل [Guid](../../system/guid/) إلى [String](../../system/string/). |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static [TimeSpan](../../system/timespan/) [ToTimeSpan](./totimespan/)(const [String](../../system/string/)\&) | يحوِّل [String](../../system/string/) إلى ما يعادل [TimeSpan](../../system/timespan/). |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../../system/string/)\&) | يحوِّل [String](../../system/string/) إلى ما يعادل [UInt16](../../system/uint16/). |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../../system/string/)\&) | يحوِّل [String](../../system/string/) إلى ما يعادل [UInt32](../../system/uint32/). |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../../system/string/)\&) | يحوِّل [String](../../system/string/) إلى ما يعادل [UInt64](../../system/uint64/). |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يطبق بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يطبق فك إقفال بيان C# lock(). يُستدعى مباشرة أو يستخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| static [String](../../system/string/) [VerifyName](./verifyname/)(const [String](../../system/string/)\&) | يتحقق من أن الاسم صالح وفقًا لتوصية W3C Extended Markup Language. |
| static [String](../../system/string/) [VerifyNCName](./verifyncname/)(const [String](../../system/string/)\&) | يتحقق من أن الاسم هو **NCName** صالح وفقًا لتوصية W3C Extended Markup Language. الـ **NCName** هو اسم لا يمكن أن يحتوي على نقطتين. |
| static [String](../../system/string/) [VerifyNMTOKEN](./verifynmtoken/)(const [String](../../system/string/)\&) | يتحقق من أن السلسلة هي NMTOKEN صالح وفقًا لتوصية W3C XML [Schema](../../system.xml.schema/) الجزء 2: الأنواع. |
| static [String](../../system/string/) [VerifyPublicId](./verifypublicid/)(const [String](../../system/string/)\&) | يعيد نسخة السلسلة المدخلة إذا كانت جميع الأحرف في الوسيط صالحة كأحرف معرف عام. |
| static [String](../../system/string/) [VerifyTOKEN](./verifytoken/)(const [String](../../system/string/)\&) | يتحقق من أن السلسلة هي رمز صالح وفقًا لتوصية W3C XML [Schema](../../system.xml.schema/) الجزء 2: الأنواع. |
| static [String](../../system/string/) [VerifyWhitespace](./verifywhitespace/)(const [String](../../system/string/)\&) | يعيد نسخة السلسلة المدخلة إذا كانت جميع الأحرف في الوسيط صالحة كمسافات بيضاء. |
| static [String](../../system/string/) [VerifyXmlChars](./verifyxmlchars/)(const [String](../../system/string/)\&) | يعيد السلسلة المدخلة إذا كانت جميع الأحرف وأزواج التعويض في الوسيط صالحة كحروف XML، وإلا يتم إلقاء XmlException مع معلومات حول أول حرف غير صالح تم العثور عليه. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## الأنواع التعريفية

| النوع التعريفي | الوصف |
| --- | --- |
| [Ptr](./ptr/) | اسم مستعار لمؤشر مشترك إلى نسخة من هذه الفئة. |

## راجع أيضًا

* الفئة [Object](../../system/object/)
* المجال [System::Xml](../)
* المكتبة [Aspose.Slides](../../)