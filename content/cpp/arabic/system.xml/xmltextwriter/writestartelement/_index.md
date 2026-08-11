---
title: WriteStartElement()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يكتب علامة البداية المحددة ويربطها بمساحة الاسم والبادئة المحددة.
type: docs
weight: 235
url: /ar/system.xml/xmltextwriter/writestartelement/
---
## XmlTextWriter::WriteStartElement(const String\&, const String\&, const String\&) طريقة

يكتب علامة البداية المحددة ويربطها بمساحة الاسم والبادئة المحددة.

```cpp
void System::Xml::XmlTextWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | بادئة مساحة الاسم للعنصر. |
| localName | const [String](../../../system/string/)\& | الاسم المحلي للعنصر. |
| ns | const [String](../../../system/string/)\& | معرّف URI لمساحة الاسم لربطه بالعنصر. إذا كانت مساحة الاسم هذه موجودة بالفعل في النطاق ولها بادئة مرتبطة فإن الكاتب يكتب تلك البادئة تلقائيًا أيضًا. |

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [XmlTextWriter](../)
* النطاق [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)