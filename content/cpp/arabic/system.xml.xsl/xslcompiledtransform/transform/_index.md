---
title: Transform()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينفّذ التحويل باستخدام المستند المدخل المحدد بواسطة كائن IXPathNavigable ويُخرج النتائج إلى XmlWriter.
type: docs
weight: 40
url: /ar/system.xml.xsl/xslcompiledtransform/transform/
---
## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XmlWriter\>\&) طريقة

ينفذ التحويل باستخدام المستند المدخل المحدد من قبل كائن IXPathNavigable ويُخرج النتائج إلى [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XmlWriter> &results)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | كائن ينفّذ واجهة IXPathNavigable. يمكن أن يكون إما [XmlNode](../../../system.xml/xmlnode/) (عادةً [XmlDocument](../../../system.xml/xmldocument/)) أو XPathDocument يحتوي على البيانات التي سيتم تحويلها. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) الذي تريد الإخراج إليه. إذا كانت ورقة الأنماط تحتوي على عنصر **xsl:output**، يجب أن تنشئ [XmlWriter](../../../system.xml/xmlwriter/) باستخدام كائن [XmlWriterSettings](../../../system.xml/xmlwritersettings/) المعاد من القيمة [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). هذا يضمن أن [XmlWriter](../../../system.xml/xmlwriter/) يملك إعدادات الإخراج الصحيحة. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) طريقة

ينفذ التحويل باستخدام المستند المدخل المحدد من قبل كائن IXPathNavigable ويُخرج النتائج إلى [XmlWriter](../../../system.xml/xmlwriter/). يوفر [XsltArgumentList](../../xsltargumentlist/) وسائط تشغيل إضافية.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | كائن ينفّذ واجهة IXPathNavigable. يمكن أن يكون إما [XmlNode](../../../system.xml/xmlnode/) (عادةً [XmlDocument](../../../system.xml/xmldocument/)) أو XPathDocument يحتوي على البيانات التي سيتم تحويلها. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) يحتوي على الوسائط المؤهلة بالأسماء المكانية المستخدمة كمدخل للتحويل. يمكن أن تكون هذه القيمة **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) الذي تريد الإخراج إليه. إذا كانت ورقة الأنماط تحتوي على عنصر **xsl:output**، يجب أن تنشئ [XmlWriter](../../../system.xml/xmlwriter/) باستخدام كائن [XmlWriterSettings](../../../system.xml/xmlwritersettings/) المعاد من القيمة [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). هذا يضمن أن [XmlWriter](../../../system.xml/xmlwriter/) يملك إعدادات الإخراج الصحيحة. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) طريقة

ينفذ التحويل باستخدام المستند المدخل المحدد من قبل كائن IXPathNavigable ويُخرج النتائج إلى TextWriter. يوفر [XsltArgumentList](../../xsltargumentlist/) وسائط تشغيل إضافية.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | كائن ينفّذ واجهة IXPathNavigable. يمكن أن يكون إما [XmlNode](../../../system.xml/xmlnode/) (عادةً [XmlDocument](../../../system.xml/xmldocument/)) أو XPathDocument يحتوي على البيانات التي سيتم تحويلها. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) يحتوي على الوسائط المؤهلة بالأسماء المكانية المستخدمة كمدخل للتحويل. يمكن أن تكون هذه القيمة **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter الذي تريد الإخراج إليه. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) طريقة

ينفذ التحويل باستخدام المستند المدخل المحدد من قبل كائن IXPathNavigable ويُخرج النتائج إلى تدفق. يوفر [XsltArgumentList](../../xsltargumentlist/) وسائط تشغيل إضافية.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | كائن ينفّذ واجهة IXPathNavigable. يمكن أن يكون إما [XmlNode](../../../system.xml/xmlnode/) (عادةً [XmlDocument](../../../system.xml/xmldocument/)) أو XPathDocument يحتوي على البيانات التي سيتم تحويلها. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) يحتوي على الوسائط المؤهلة بالأسماء المكانية المستخدمة كمدخل للتحويل. يمكن أن تكون هذه القيمة **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | التدفق الذي تريد الإخراج إليه. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XmlWriter\>\&) طريقة

ينفذ التحويل باستخدام المستند المدخل المحدد بواسطة كائن [XmlReader](../../../system.xml/xmlreader/) ويُخرج النتائج إلى [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XmlWriter> &results)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) الذي يحتوي على المستند المدخل. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) الذي تريد الإخراج إليه. إذا كانت ورقة الأنماط تحتوي على عنصر **xsl:output**، يجب أن تنشئ [XmlWriter](../../../system.xml/xmlwriter/) باستخدام كائن [XmlWriterSettings](../../../system.xml/xmlwritersettings/) المعاد من القيمة [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). هذا يضمن أن [XmlWriter](../../../system.xml/xmlwriter/) يملك إعدادات الإخراج الصحيحة. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) طريقة

ينفذ التحويل باستخدام المستند المدخل المحدد بواسطة كائن [XmlReader](../../../system.xml/xmlreader/) ويُخرج النتائج إلى [XmlWriter](../../../system.xml/xmlwriter/). يوفر [XsltArgumentList](../../xsltargumentlist/) وسائط تشغيل إضافية.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) الذي يحتوي على المستند المدخل. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) يحتوي على الوسائط المؤهلة بالأسماء المكانية المستخدمة كمدخل للتحويل. يمكن أن تكون هذه القيمة **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) الذي تريد الإخراج إليه. إذا كانت ورقة الأنماط تحتوي على عنصر **xsl:output**، يجب أن تنشئ [XmlWriter](../../../system.xml/xmlwriter/) باستخدام كائن [XmlWriterSettings](../../../system.xml/xmlwritersettings/) المعاد من القيمة [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). هذا يضمن أن [XmlWriter](../../../system.xml/xmlwriter/) يملك إعدادات الإخراج الصحيحة. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) طريقة

ينفذ التحويل باستخدام المستند المدخل المحدد بواسطة كائن [XmlReader](../../../system.xml/xmlreader/) ويُخرج النتائج إلى TextWriter. يوفر [XsltArgumentList](../../xsltargumentlist/) وسائط تشغيل إضافية.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) الذي يحتوي على المستند المدخل. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) يحتوي على الوسائط المؤهلة بالأسماء المكانية المستخدمة كمدخل للتحويل. يمكن أن تكون هذه القيمة **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter الذي تريد الإخراج إليه. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) طريقة

ينفذ التحويل باستخدام المستند المدخل المحدد بواسطة كائن [XmlReader](../../../system.xml/xmlreader/) ويُخرج النتائج إلى تدفق. يوفر [XsltArgumentList](../../xsltargumentlist/) وسائط تشغيل إضافية.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) الذي يحتوي على المستند المدخل. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) يحتوي على الوسائط المؤهلة بالأسماء المكانية المستخدمة كمدخل للتحويل. يمكن أن تكون هذه القيمة **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | التدفق الذي تريد الإخراج إليه. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XmlWriter\>\&) طريقة

ينفذ التحويل باستخدام المستند المدخل المحدد بواسطة URI ويُخرج النتائج إلى [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XmlWriter> &results)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI للمستند المدخل. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) الذي تريد الإخراج إليه. إذا كانت ورقة الأنماط تحتوي على عنصر **xsl:output**، يجب أن تنشئ [XmlWriter](../../../system.xml/xmlwriter/) باستخدام كائن [XmlWriterSettings](../../../system.xml/xmlwritersettings/) المعاد من القيمة [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). هذا يضمن أن [XmlWriter](../../../system.xml/xmlwriter/) يملك إعدادات الإخراج الصحيحة. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) طريقة

ينفذ التحويل باستخدام المستند المدخل المحدد بواسطة URI ويُخرج النتائج إلى [XmlWriter](../../../system.xml/xmlwriter/). يوفر [XsltArgumentList](../../xsltargumentlist/) وسائط تشغيل إضافية.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI للمستند المدخل. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) يحتوي على الوسائط المؤهلة بالأسماء المكانية المستخدمة كمدخل للتحويل. يمكن أن تكون هذه القيمة **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) الذي تريد الإخراج إليه. إذا كانت ورقة الأنماط تحتوي على عنصر **xsl:output**، يجب أن تنشئ [XmlWriter](../../../system.xml/xmlwriter/) باستخدام كائن [XmlWriterSettings](../../../system.xml/xmlwritersettings/) المعاد من القيمة [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). هذا يضمن أن [XmlWriter](../../../system.xml/xmlwriter/) يملك إعدادات الإخراج الصحيحة. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) طريقة

ينفذ التحويل باستخدام المستند المدخل المحدد بواسطة URI ويُخرج النتائج إلى TextWriter.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI للمستند المدخل. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) يحتوي على الوسائط المؤهلة بالأسماء المكانية المستخدمة كمدخل للتحويل. يمكن أن تكون هذه القيمة **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter الذي تريد الإخراج إليه. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) طريقة

ينفذ التحويل باستخدام المستند المدخل المحدد بواسطة URI ويُخرج النتائج إلى تدفق. يوفر [XsltArgumentList](../../xsltargumentlist/) وسائط تشغيل إضافية.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI للمستند المدخل. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) يحتوي على الوسائط المؤهلة بالأسماء المكانية المستخدمة كمدخل للتحويل. يمكن أن تكون هذه القيمة **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | التدفق الذي تريد الإخراج إليه. |

## XslCompiledTransform::Transform(const String\&, const String\&) طريقة

ينفذ التحويل باستخدام المستند المدخل المحدد بواسطة URI ويُخرج النتائج إلى ملف.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const String &resultsFile)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI للمستند المدخل. |
| resultsFile | const [String](../../../system/string/)\& | URI للملف الناتج. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) طريقة

ينفذ التحويل باستخدام المستند المدخل المحدد بواسطة كائن [XmlReader](../../../system.xml/xmlreader/) ويُخرج النتائج إلى [XmlWriter](../../../system.xml/xmlwriter/). يوفر [XsltArgumentList](../../xsltargumentlist/) وسائط تشغيل إضافية ويُحَلّ [XmlResolver](../../../system.xml/xmlresolver/) الدالة XSLT **document()**.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) الذي يحتوي على المستند المدخل. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) يحتوي على الوسائط المؤهلة بالأسماء المكانية المستخدمة كمدخل للتحويل. يمكن أن تكون هذه القيمة **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) الذي تريد الإخراج إليه. إذا كانت ورقة الأنماط تحتوي على عنصر **xsl:output**، يجب أن تنشئ [XmlWriter](../../../system.xml/xmlwriter/) باستخدام كائن [XmlWriterSettings](../../../system.xml/xmlwritersettings/) المعاد من القيمة [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). هذا يضمن أن [XmlWriter](../../../system.xml/xmlwriter/) يملك إعدادات الإخراج الصحيحة. |
| documentResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) المستخدم لحل دالة XSLT **document()**. إذا كان هذا **nullptr**، فإن الدالة **document()** لن تُحَلّ. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) طريقة

ينفذ التحويل باستخدام المستند المدخل المحدد بواسطة كائن IXPathNavigable ويُخرج النتائج إلى [XmlWriter](../../../system.xml/xmlwriter/). يوفر [XsltArgumentList](../../xsltargumentlist/) وسائط تشغيل إضافية ويُحَلّ [XmlResolver](../../../system.xml/xmlresolver/) الدالة XSLT **document()**.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | المستند المراد تحويله والذي حدده كائن IXPathNavigable. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | قائمة الوسائط ك[XsltArgumentList](../../xsltargumentlist/). |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) الذي تريد الإخراج إليه. إذا كانت ورقة الأنماط تحتوي على عنصر **xsl:output**، يجب أن تنشئ [XmlWriter](../../../system.xml/xmlwriter/) باستخدام كائن [XmlWriterSettings](../../../system.xml/xmlwritersettings/) المعاد من القيمة [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). هذا يضمن أن [XmlWriter](../../../system.xml/xmlwriter/) يملك إعدادات الإخراج الصحيحة. |
| documentResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) المستخدم لحل دالة XSLT **document()**. إذا كان هذا **nullptr**، فإن الدالة **document()** لن تُحَلّ. |

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XslCompiledTransform](../)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [String](../../../system/string/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)