---
title: XmlTextWriter()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ مثيلاً من فئة XmlTextWriter باستخدام الدفق والترميز المحددين.
type: docs
weight: 183
url: /ar/system.xml/xmltextwriter/xmltextwriter/
---
## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Text::Encoding\>\&) المنشئ

ينشئ مثيلاً من الفئة [XmlTextWriter](../) باستخدام الدفق المحدد والترميز.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::Stream> &w, const SharedPtr<Text::Encoding> &encoding)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | الدفق الذي تريد الكتابة إليه. |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | الترميز الذي سيتم إنشاؤه. إذا كان الترميز **nullptr** فإنه يكتب الدفق كـ UTF-8 ويحذف خاصية الترميز من **ProcessingInstruction**. |

## XmlTextWriter::XmlTextWriter(const String\&, const SharedPtr\<Text::Encoding\>\&) المنشئ

ينشئ مثيلاً من الفئة [XmlTextWriter](../) باستخدام الملف المحدد.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const String &filename, const SharedPtr<Text::Encoding> &encoding)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | اسم الملف للكتابة إليه. إذا كان الملف موجودًا، يتم تقصيره والكتابة فوقه بالمحتوى الجديد. |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | الترميز الذي سيتم إنشاؤه. إذا كان الترميز **nullptr** فإنه يكتب الملف كـ UTF-8 ويحذف خاصية الترميز من **ProcessingInstruction**. |

## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::TextWriter\>\&) المنشئ

ينشئ مثيلاً من الفئة [XmlTextWriter](../) باستخدام الـ TextWriter المحدد.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::TextWriter> &w)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | الـ TextWriter الذي سيتم الكتابة إليه. يُفترض أن الـ TextWriter مُعد مسبقًا للترميز الصحيح. |

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* الفئة [Stream](../../../system.io/stream/)
* الفئة [Encoding](../../../system.text/encoding/)
* الفئة [XmlTextWriter](../)
* الفئة [String](../../../system/string/)
* الفئة [TextWriter](../../../system.io/textwriter/)
* النطاق [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)