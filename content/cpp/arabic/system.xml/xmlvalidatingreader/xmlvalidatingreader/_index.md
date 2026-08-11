---
title: XmlValidatingReader()
second_title: Aspose.Slides للـ C++ مرجع API
description: يُنشئ مثلاً جديداً من فئة XmlValidatingReader التي تتحقق من صحة المحتوى المسترجع من XmlReader المحدد.
type: docs
weight: 430
url: /ar/system.xml/xmlvalidatingreader/xmlvalidatingreader/
---
## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<XmlReader\>\&) constructor


يُنشئ مثالًا جديدًا من الفئة [XmlValidatingReader](../) التي تتحقق من صحة المحتوى المرجع من [XmlReader](../../xmlreader/) المحدد.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<XmlReader> &reader)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\>\& | ال[XmlReader](../../xmlreader/) للقراءة منه أثناء التحقق. يدعم التنفيذ الحالي فقط [XmlTextReader](../../xmltextreader/). |

## XmlValidatingReader::XmlValidatingReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor


يُنشئ مثالًا جديدًا من الفئة [XmlValidatingReader](../) بالقيم المحددة.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | السلسلة التي تحتوي على مقطع XML لتجهيزه. |
| fragType | [XmlNodeType](../../xmlnodetype/) | نوع XmlNodeType لمقطع XML. يحدد هذا أيضًا ما يمكن أن يحتويه النص (انظر الجدول أدناه). |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | [XmlParserContext](../../xmlparsercontext/) الذي سيُجرى فيه تحليل مقطع XML. يشمل ذلك [NameTable](../../nametable/) المستخدمة، والترميز، ونطاق مساحة الاسم، و**xml:lang** الحالي، ونطاق **xml:space**. |

## ملاحظات



القائمة التالية تسرد القيم الصالحة لـ **fragType** وكيفية تحليل القارئ لكل نوع من أنواع العقد المختلفة.

| XmlNodeType | ما قد يحتويه المقطع |
| --- | --- |
| Element| أي محتوى عنصر صالح (على سبيل المثال، أي تركيبة من العناصر، التعليقات، تعليمات المعالجة، cdata، النص، وإشارات الكيان). |
| [Attribute](../../../system/attribute/)| قيمة السمة (الجزء داخل علامات الاقتباس). |
| Document| محتويات مستند XML كامل؛ يفرض ذلك قواعد على مستوى المستند. |


## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor


يُنشئ مثالًا جديدًا من الفئة [XmlValidatingReader](../) بالقيم المحددة.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | الدفق الذي يحتوي على مقطع XML لتجهيزه. |
| fragType | [XmlNodeType](../../xmlnodetype/) | نوع XmlNodeType لمقطع XML. يحدد هذا ما يمكن أن يحتويه النص (انظر الجدول أدناه). |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | [XmlParserContext](../../xmlparsercontext/) الذي سيُجرى فيه تحليل مقطع XML. يشمل ذلك [XmlNameTable](../../xmlnametable/) المستخدمة، والترميز، ونطاق مساحة الاسم، و**xml:lang** الحالي، ونطاق **xml:space**. |

## ملاحظات



القائمة التالية تسرد القيم الصالحة لـ **fragType** وكيفية تحليل القارئ لكل نوع من أنواع العقد المختلفة.

| XmlNodeType | ما قد يحتويه المقطع |
| --- | --- |
| Element| أي محتوى عنصر صالح (على سبيل المثال، أي تركيبة من العناصر، التعليقات، تعليمات المعالجة، cdata، النص، وإشارات الكيان). |
| [Attribute](../../../system/attribute/)| قيمة السمة (الجزء داخل علامات الاقتباس). |
| Document| محتويات مستند XML كامل؛ يفرض ذلك قواعد على مستوى المستند. |


## انظر أيضًا

* تعداد [XmlNodeType](../../xmlnodetype/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [XmlReader](../../xmlreader/)
* فئة [XmlValidatingReader](../)
* فئة [String](../../../system/string/)
* فئة [XmlParserContext](../../xmlparsercontext/)
* فئة [Stream](../../../system.io/stream/)
* مساحة الاسم [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)