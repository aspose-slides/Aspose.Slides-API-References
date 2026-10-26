---
title: Transform()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحوّل بيانات XML في XPathNavigator باستخدام args المحددة ويخرج النتيجة إلى XmlReader.
type: docs
weight: 40
url: /ar/system.xml.xsl/xsltransform/transform/
---
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) طريقة

يحوِّل بيانات XML في XPathNavigator باستخدام **args** المحددة ويُخرج النتيجة إلى [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | كائن XPathNavigator يحتوي على البيانات التي سيتم تحويلها. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | كائن [XsltArgumentList](../../xsltargumentlist/) يحتوي على المعلمات المؤهلة بالمساحة الاسمية المستخدمة كمدخل للتحويل. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | الـ[XmlResolver](../../../system.xml/xmlresolver/) المستخدم لحل وظيفة XSLT **document()**. إذا كان هذا **nullptr**، فإن وظيفة **document()** لن تُحل. الـ[XmlResolver](../../../system.xml/xmlresolver/) غير مخزن مؤقتًا بعد اكتمال هذه الطريقة. |

### قيمة الإرجاع

كائن [XmlReader](../../../system.xml/xmlreader/) يحتوي على نتائج التحويل.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&) طريقة

يحوِّل بيانات XML في XPathNavigator باستخدام **args** المحددة ويُخرج النتيجة إلى [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | كائن XPathNavigator يحتوي على البيانات التي سيتم تحويلها. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | كائن [XsltArgumentList](../../xsltargumentlist/) يحتوي على المعلمات المؤهلة بالمساحة الاسمية المستخدمة كمدخل للتحويل. |

### قيمة الإرجاع

كائن [XmlReader](../../../system.xml/xmlreader/) يحتوي على نتائج التحويل.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) طريقة

يحوِّل بيانات XML في XPathNavigator باستخدام **args** المحددة ويُخرج النتيجة إلى [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | كائن XPathNavigator يحتوي على البيانات التي سيتم تحويلها. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | كائن [XsltArgumentList](../../xsltargumentlist/) يحتوي على المعلمات المؤهلة بالمساحة الاسمية المستخدمة كمدخل للتحويل. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | الـ[XmlWriter](../../../system.xml/xmlwriter/) الذي تريد الإخراج إليه. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | الـ[XmlResolver](../../../system.xml/xmlresolver/) المستخدم لحل وظيفة XSLT **document()**. إذا كان هذا **nullptr**، فإن وظيفة **document()** لن تُحل. الـ[XmlResolver](../../../system.xml/xmlresolver/) غير مخزن مؤقتًا بعد اكتمال هذه الطريقة. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) طريقة

يحوِّل بيانات XML في XPathNavigator باستخدام **args** المحددة ويُخرج النتيجة إلى [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | كائن XPathNavigator يحتوي على البيانات التي سيتم تحويلها. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | كائن [XsltArgumentList](../../xsltargumentlist/) يحتوي على المعلمات المؤهلة بالمساحة الاسمية المستخدمة كمدخل للتحويل. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | الـ[XmlWriter](../../../system.xml/xmlwriter/) الذي تريد الإخراج إليه. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) طريقة

يحوِّل بيانات XML في XPathNavigator باستخدام **args** المحددة ويُخرج النتيجة إلى Stream.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | كائن XPathNavigator يحتوي على البيانات التي سيتم تحويلها. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | كائن [XsltArgumentList](../../xsltargumentlist/) يحتوي على المعلمات المؤهلة بالمساحة الاسمية المستخدمة كمدخل للتحويل. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | الـStream الذي تريد الإخراج إليه. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | الـ[XmlResolver](../../../system.xml/xmlresolver/) المستخدم لحل وظيفة XSLT **document()**. إذا كان هذا **nullptr**، فإن وظيفة **document()** لن تُحل. الـ[XmlResolver](../../../system.xml/xmlresolver/) غير مخزن مؤقتًا بعد اكتمال هذه الطريقة. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) طريقة

يحوِّل بيانات XML في XPathNavigator باستخدام **args** المحددة ويُخرج النتيجة إلى Stream.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | كائن XPathNavigator يحتوي على البيانات التي سيتم تحويلها. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | كائن [XsltArgumentList](../../xsltargumentlist/) يحتوي على المعلمات المؤهلة بالمساحة الاسمية المستخدمة كمدخل للتحويل. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | الـStream الذي تريد الإخراج إليه. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) طريقة

يحوِّل بيانات XML في XPathNavigator باستخدام **args** المحددة ويُخرج النتيجة إلى TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | كائن XPathNavigator يحتوي على البيانات التي سيتم تحويلها. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | كائن [XsltArgumentList](../../xsltargumentlist/) يحتوي على المعلمات المؤهلة بالمساحة الاسمية المستخدمة كمدخل للتحويل. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | الـTextWriter الذي تريد الإخراج إليه. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | الـ[XmlResolver](../../../system.xml/xmlresolver/) المستخدم لحل وظيفة XSLT **document()**. إذا كان هذا **nullptr**، فإن وظيفة **document()** لن تُحل. الـ[XmlResolver](../../../system.xml/xmlresolver/) غير مخزن مؤقتًا بعد اكتمال هذه الطريقة. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) طريقة

يحوِّل بيانات XML في XPathNavigator باستخدام **args** المحددة ويُخرج النتيجة إلى TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | كائن XPathNavigator يحتوي على البيانات التي سيتم تحويلها. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | كائن [XsltArgumentList](../../xsltargumentlist/) يحتوي على المعلمات المؤهلة بالمساحة الاسمية المستخدمة كمدخل للتحويل. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | الـTextWriter الذي تريد الإخراج إليه. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) طريقة

يحوِّل بيانات XML في IXPathNavigable باستخدام **args** المحددة ويُخرج النتيجة إلى [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | كائن يطبق واجهة IXPathNavigable. يمكن أن يكون إما [XmlNode](../../../system.xml/xmlnode/) (عادةً [XmlDocument](../../../system.xml/xmldocument/)) أو XPathDocument يحتوي على البيانات التي سيتم تحويلها. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | كائن [XsltArgumentList](../../xsltargumentlist/) يحتوي على المعلمات المؤهلة بالمساحة الاسمية المستخدمة كمدخل للتحويل. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | الـ[XmlResolver](../../../system.xml/xmlresolver/) المستخدم لحل وظيفة XSLT **document()**. إذا كان هذا **nullptr**، فإن وظيفة **document()** لن تُحل. الـ[XmlResolver](../../../system.xml/xmlresolver/) غير مخزن مؤقتًا بعد اكتمال هذه الطريقة. |

### قيمة الإرجاع

كائن [XmlReader](../../../system.xml/xmlreader/) يحتوي على نتائج التحويل.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&) طريقة

يحوِّل بيانات XML في IXPathNavigable باستخدام **args** المحددة ويُخرج النتيجة إلى [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | كائن يطبق واجهة IXPathNavigable. يمكن أن يكون إما [XmlNode](../../../system.xml/xmlnode/) (عادةً [XmlDocument](../../../system.xml/xmldocument/)) أو XPathDocument يحتوي على البيانات التي سيتم تحويلها. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | كائن [XsltArgumentList](../../xsltargumentlist/) يحتوي على المعلمات المؤهلة بالمساحة الاسمية المستخدمة كمدخل للتحويل. |

### قيمة الإرجاع

كائن [XmlReader](../../../system.xml/xmlreader/) يحتوي على نتائج التحويل.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) طريقة

يحوِّل بيانات XML في IXPathNavigable باستخدام **args** المحددة ويُخرج النتيجة إلى TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | كائن يطبق واجهة IXPathNavigable. يمكن أن يكون إما [XmlNode](../../../system.xml/xmlnode/) (عادةً [XmlDocument](../../../system.xml/xmldocument/)) أو XPathDocument يحتوي على البيانات التي سيتم تحويلها. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | كائن [XsltArgumentList](../../xsltargumentlist/) يحتوي على المعلمات المؤهلة بالمساحة الاسمية المستخدمة كمدخل للتحويل. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | الـTextWriter الذي تريد الإخراج إليه. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | الـ[XmlResolver](../../../system.xml/xmlresolver/) المستخدم لحل وظيفة XSLT **document()**. إذا كان هذا **nullptr**، فإن وظيفة **document()** لن تُحل. الـ[XmlResolver](../../../system.xml/xmlresolver/) غير مخزن مؤقتًا بعد اكتمال هذه الطريقة. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) طريقة

يحوِّل بيانات XML في IXPathNavigable باستخدام **args** المحددة ويُخرج النتيجة إلى TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | كائن يطبق واجهة IXPathNavigable. يمكن أن يكون إما [XmlNode](../../../system.xml/xmlnode/) (عادةً [XmlDocument](../../../system.xml/xmldocument/)) أو XPathDocument يحتوي على البيانات التي سيتم تحويلها. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | كائن [XsltArgumentList](../../xsltargumentlist/) يحتوي على المعلمات المؤهلة بالمساحة الاسمية المستخدمة كمدخل للتحويل. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | الـTextWriter الذي تريد الإخراج إليه. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) طريقة

يحوِّل بيانات XML في IXPathNavigable باستخدام **args** المحددة ويُخرج النتيجة إلى Stream.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | كائن يطبق واجهة IXPathNavigable. يمكن أن يكون إما [XmlNode](../../../system.xml/xmlnode/) (عادةً [XmlDocument](../../../system.xml/xmldocument/)) أو XPathDocument يحتوي على البيانات التي سيتم تحويلها. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | كائن [XsltArgumentList](../../xsltargumentlist/) يحتوي على المعلمات المؤهلة بالمساحة الاسمية المستخدمة كمدخل للتحويل. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | الـStream الذي تريد الإخراج إليه. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | الـ[XmlResolver](../../../system.xml/xmlresolver/) المستخدم لحل وظيفة XSLT **document()**. إذا كان هذا **nullptr**، فإن وظيفة **document()** لن تُحل. الـ[XmlResolver](../../../system.xml/xmlresolver/) غير مخزن مؤقتًا بعد طريقة [XslTransform::Transform](./). |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) طريقة

يحوِّل بيانات XML في IXPathNavigable باستخدام **args** المحددة ويُخرج النتيجة إلى Stream.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | كائن يطبق واجهة IXPathNavigable. يمكن أن يكون إما [XmlNode](../../../system.xml/xmlnode/) (عادةً [XmlDocument](../../../system.xml/xmldocument/)) أو XPathDocument يحتوي على البيانات التي سيتم تحويلها. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | كائن [XsltArgumentList](../../xsltargumentlist/) يحتوي على المعلمات المؤهلة بالمساحة الاسمية المستخدمة كمدخل للتحويل. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | الـStream الذي تريد الإخراج إليه. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) طريقة

يحوِّل بيانات XML في IXPathNavigable باستخدام **args** المحددة ويُخرج النتيجة إلى [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | كائن يطبق واجهة IXPathNavigable. يمكن أن يكون إما [XmlNode](../../../system.xml/xmlnode/) (عادةً [XmlDocument](../../../system.xml/xmldocument/)) أو XPathDocument يحتوي على البيانات التي سيتم تحويلها. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | كائن [XsltArgumentList](../../xsltargumentlist/) يحتوي على المعلمات المؤهلة بالمساحة الاسمية المستخدمة كمدخل للتحويل. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | الـ[XmlWriter](../../../system.xml/xmlwriter/) الذي تريد الإخراج إليه. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | الـ[XmlResolver](../../../system.xml/xmlresolver/) المستخدم لحل وظيفة XSLT **document()**. إذا كان هذا **nullptr**، فإن وظيفة **document()** لن تُحل. الـ[XmlResolver](../../../system.xml/xmlresolver/) غير مخزن مؤقتًا بعد اكتمال هذه الطريقة. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) طريقة

يحوِّل بيانات XML في IXPathNavigable باستخدام **args** المحددة ويُخرج النتيجة إلى [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | كائن يطبق واجهة IXPathNavigable. يمكن أن يكون إما [XmlNode](../../../system.xml/xmlnode/) (عادةً [XmlDocument](../../../system.xml/xmldocument/)) أو XPathDocument يحتوي على البيانات التي سيتم تحويلها. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | كائن [XsltArgumentList](../../xsltargumentlist/) يحتوي على المعلمات المؤهلة بالمساحة الاسمية المستخدمة كمدخل للتحويل. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | الـ[XmlWriter](../../../system.xml/xmlwriter/) الذي تريد الإخراج إليه. |

## XslTransform::Transform(const String\&, const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) طريقة

يحوِّل بيانات XML في ملف الإدخال ويُخرج النتيجة إلى ملف الإخراج.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| inputfile | const [String](../../../system/string/)\& | عنوان URL للملف المصدر الذي سيُحوَّل. |
| outputfile | const [String](../../../system/string/)\& | عنوان URL لملف الإخراج. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | الـ[XmlResolver](../../../system.xml/xmlresolver/) المستخدم لحل وظيفة XSLT **document()**. إذا كان هذا **nullptr**، فإن وظيفة **document()** لن تُحل. الـ[XmlResolver](../../../system.xml/xmlresolver/) غير مخزن مؤقتًا بعد طريقة [XslTransform::Transform](./). |

## XslTransform::Transform(const String\&, const String\&) طريقة

يحوِّل بيانات XML في ملف الإدخال ويُخرج النتيجة إلى ملف الإخراج.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| inputfile | const [String](../../../system/string/)\& | عنوان URL للملف المصدر الذي سيُحوَّل. |
| outputfile | const [String](../../../system/string/)\& | عنوان URL لملف الإخراج. |

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [Stream](../../../system.io/stream/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)