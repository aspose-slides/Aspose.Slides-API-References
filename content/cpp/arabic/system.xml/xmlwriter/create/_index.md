---
title: Create()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة C++
description: ينشئ مثيلًا جديدًا من XmlWriter باستخدام اسم الملف المحدد.
type: docs
weight: 469
url: /ar/system.xml/xmlwriter/create/
---
## XmlWriter::Create(const String\&) طريقة

إنشاء مثيل [XmlWriter](../) جديد باستخدام اسم الملف المحدد.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | الملف الذي تريد الكتابة إليه. يقوم [XmlWriter](../) بإنشاء ملف في المسار المحدد ويكتب إليه بصيغة نص XML 1.0. يجب أن يكون **outputFileName** مسار نظام ملفات. |

### قيمة الإرجاع

كائن [XmlWriter](../).

## XmlWriter::Create(const String\&, SharedPtr\<XmlWriterSettings\>) طريقة

إنشاء مثيل [XmlWriter](../) جديد باستخدام اسم الملف وكائن [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName, SharedPtr<XmlWriterSettings> settings)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | الملف الذي تريد الكتابة إليه. يقوم [XmlWriter](../) بإنشاء ملف في المسار المحدد ويكتب إليه بصيغة نص XML 1.0. يجب أن يكون **outputFileName** مسار نظام ملفات. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | الكائن [XmlWriterSettings](../../xmlwritersettings/) المستخدم لتكوين مثيل [XmlWriter](../) الجديد. إذا كان هذا **nullptr**، سيتم استخدام [XmlWriterSettings](../../xmlwritersettings/) بالإعدادات الافتراضية. إذا كان يتم استخدام [XmlWriter](../) مع طريقة XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>)، يجب عليك استخدام قيمة XslCompiledTransform::get_OutputSettings للحصول على كائن [XmlWriterSettings](../../xmlwritersettings/) بالإعدادات الصحيحة. يضمن ذلك أن كائن [XmlWriter](../) الذي تم إنشاؤه يحتوي على إعدادات الإخراج الصحيحة. |

### قيمة الإرجاع

كائن [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&) طريقة

إنشاء مثيل [XmlWriter](../) جديد باستخدام الدفق المحدد.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | الدفق الذي تريد الكتابة إليه. يقوم [XmlWriter](../) بكتابة صيغة نص XML 1.0 ويضيفها إلى الدفق المحدد. |

### قيمة الإرجاع

كائن [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlWriterSettings\>) طريقة

إنشاء مثيل [XmlWriter](../) جديد باستخدام الدفق وكائن [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output, SharedPtr<XmlWriterSettings> settings)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | الدفق الذي تريد الكتابة إليه. يقوم [XmlWriter](../) بكتابة صيغة نص XML 1.0 ويضيفها إلى الدفق المحدد. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | الكائن [XmlWriterSettings](../../xmlwritersettings/) المستخدم لتكوين مثيل [XmlWriter](../) الجديد. إذا كان هذا **nullptr**، سيتم استخدام [XmlWriterSettings](../../xmlwritersettings/) بالإعدادات الافتراضية. إذا كان يتم استخدام [XmlWriter](../) مع طريقة XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>)، يجب عليك استخدام قيمة XslCompiledTransform::get_OutputSettings للحصول على كائن [XmlWriterSettings](../../xmlwritersettings/) بالإعدادات الصحيحة. يضمن ذلك أن كائن [XmlWriter](../) الذي تم إنشاؤه يحتوي على إعدادات الإخراج الصحيحة. |

### قيمة الإرجاع

كائن [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&) طريقة

إنشاء مثيل [XmlWriter](../) جديد باستخدام كاتب النص المحدد.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | كاتب النص الذي تريد الكتابة إليه. يقوم [XmlWriter](../) بكتابة صيغة نص XML 1.0 ويضيفها إلى كاتب النص المحدد. |

### قيمة الإرجاع

كائن [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&, SharedPtr\<XmlWriterSettings\>) طريقة

إنشاء مثيل [XmlWriter](../) جديد باستخدام كاتب النص وكائنات [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output, SharedPtr<XmlWriterSettings> settings)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | كاتب النص الذي تريد الكتابة إليه. يقوم [XmlWriter](../) بكتابة صيغة نص XML 1.0 ويضيفها إلى كاتب النص المحدد. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | الكائن [XmlWriterSettings](../../xmlwritersettings/) المستخدم لتكوين مثيل [XmlWriter](../) الجديد. إذا كان هذا **nullptr**، سيتم استخدام [XmlWriterSettings](../../xmlwritersettings/) بالإعدادات الافتراضية. إذا كان يتم استخدام [XmlWriter](../) مع طريقة XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>)، يجب عليك استخدام قيمة XslCompiledTransform::get_OutputSettings للحصول على كائن [XmlWriterSettings](../../xmlwritersettings/) بالإعدادات الصحيحة. يضمن ذلك أن كائن [XmlWriter](../) الذي تم إنشاؤه يحتوي على إعدادات الإخراج الصحيحة. |

### قيمة الإرجاع

كائن [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&) طريقة

إنشاء مثيل [XmlWriter](../) جديد باستخدام [Text::StringBuilder](../../../system.text/stringbuilder/) المحدد.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | [Text::StringBuilder](../../../system.text/stringbuilder/) التي سيتم الكتابة إليها. المحتوى المكتوب بواسطة [XmlWriter](../) يضاف إلى [Text::StringBuilder](../../../system.text/stringbuilder/). |

### قيمة الإرجاع

كائن [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&, SharedPtr\<XmlWriterSettings\>) طريقة

إنشاء مثيل [XmlWriter](../) جديد باستخدام كائنات [Text::StringBuilder](../../../system.text/stringbuilder/) و[XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output, SharedPtr<XmlWriterSettings> settings)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | [Text::StringBuilder](../../../system.text/stringbuilder/) التي سيتم الكتابة إليها. المحتوى المكتوب بواسطة [XmlWriter](../) يضاف إلى [Text::StringBuilder](../../../system.text/stringbuilder/). |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | الكائن [XmlWriterSettings](../../xmlwritersettings/) المستخدم لتكوين مثيل [XmlWriter](../) الجديد. إذا كان هذا **nullptr**، سيتم استخدام [XmlWriterSettings](../../xmlwritersettings/) بالإعدادات الافتراضية. إذا كان يتم استخدام [XmlWriter](../) مع طريقة XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>)، يجب عليك استخدام قيمة XslCompiledTransform::get_OutputSettings للحصول على كائن [XmlWriterSettings](../../xmlwritersettings/) بالإعدادات الصحيحة. يضمن ذلك أن كائن [XmlWriter](../) الذي تم إنشاؤه يحتوي على إعدادات الإخراج الصحيحة. |

### قيمة الإرجاع

كائن [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&) طريقة

إنشاء مثيل [XmlWriter](../) جديد باستخدام كائن [XmlWriter](../) المحدد.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | كائن [XmlWriter](../) الذي تريد استخدامه ككاتب أساسي. |

### قيمة الإرجاع

كائن [XmlWriter](../) ملفوف حول كائن [XmlWriter](../) المحدد.

## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&, SharedPtr\<XmlWriterSettings\>) طريقة

إنشاء مثيل [XmlWriter](../) جديد باستخدام كائنات [XmlWriter](../) و[XmlWriterSettings](../../xmlwritersettings/) المحددة.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output, SharedPtr<XmlWriterSettings> settings)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | كائن [XmlWriter](../) الذي تريد استخدامه ككاتب أساسي. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | الكائن [XmlWriterSettings](../../xmlwritersettings/) المستخدم لتكوين مثيل [XmlWriter](../) الجديد. إذا كان هذا **nullptr**، سيتم استخدام [XmlWriterSettings](../../xmlwritersettings/) بالإعدادات الافتراضية. إذا كان يتم استخدام [XmlWriter](../) مع طريقة XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>)، يجب عليك استخدام قيمة XslCompiledTransform::get_OutputSettings للحصول على كائن [XmlWriterSettings](../../xmlwritersettings/) بالإعدادات الصحيحة. يضمن ذلك أن كائن [XmlWriter](../) الذي تم إنشاؤه يحتوي على إعدادات الإخراج الصحيحة. |

### قيمة الإرجاع

كائن [XmlWriter](../) ملفوف حول كائن [XmlWriter](../) المحدد.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [String](../../../system/string/)
* Class [XmlWriterSettings](../../xmlwritersettings/)
* Class [Stream](../../../system.io/stream/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [StringBuilder](../../../system.text/stringbuilder/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)