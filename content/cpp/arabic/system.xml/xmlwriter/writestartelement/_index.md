---
title: WriteStartElement()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: عند تجاوزها في فئة مشتقة، تقوم بكتابة علامة البدء المحددة وتربطها بالمساحة الاسمية المعطاة.
type: docs
weight: 92
url: /ar/system.xml/xmlwriter/writestartelement/
---
## XmlWriter::WriteStartElement(const String&, const String&) طريقة

عند تجاوزها في فئة مشتقة، تقوم بكتابة العلامة الأولية المحددة وتربطها بالمساحة الاسمية المعطاة.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName, const String &ns)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | اسم العنصر المحلي. |
| ns | const [String](../../../system/string/)\& | معرف مساحة الاسم (URI) لربطه بالعنصر. إذا كانت هذه المساحة الاسمية موجودة بالفعل في النطاق ولها مقدّم مرتبط، فإن الكاتب يكتب ذلك المقدّم تلقائيًا أيضًا. |

## XmlWriter::WriteStartElement(const String&, const String&, const String&) طريقة

عند تجاوزها في فئة مشتقة، تقوم بكتابة العلامة الأولية المحددة وتربطها بالمساحة الاسمية والمقدّم المعطى.

```cpp
virtual void System::Xml::XmlWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | مقدّم مساحة الاسم للعنصر. |
| localName | const [String](../../../system/string/)\& | اسم العنصر المحلي. |
| ns | const [String](../../../system/string/)\& | معرف مساحة الاسم (URI) لربطه بالعنصر. |

## XmlWriter::WriteStartElement(const String&) طريقة

عند تجاوزها في فئة مشتقة، تقوم بكتابة علامة بدء بالاسم المحلي المحدد.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | اسم العنصر المحلي. |

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [XmlWriter](../)
* النطاق [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)