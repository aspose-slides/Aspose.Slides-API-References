---
title: WriteStartAttribute()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يكتب بداية سمة بالاسم المحلي المحدد ومسار URI مساحة الاسم.
type: docs
weight: 144
url: /ar/system.xml/xmlwriter/writestartattribute/
---
## XmlWriter::WriteStartAttribute(const String&, const String&) طريقة

يكتب بداية سمة بالاسم المحلي المحدد ومسار URI مساحة الاسم.

```cpp
void System::Xml::XmlWriter::WriteStartAttribute(const String &localName, const String &ns)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | الاسم المحلي للسمة. |
| ns | const [String](../../../system/string/)\& | مسار URI مساحة الاسم للسمة. |

## XmlWriter::WriteStartAttribute(const String&, const String&, const String&) طريقة

عند إعادة تعريفه في فئة مشتقة، يكتب بداية سمة مع البادئة المحددة والاسم المحلي ومسار URI مساحة الاسم.

```cpp
virtual void System::Xml::XmlWriter::WriteStartAttribute(const String &prefix, const String &localName, const String &ns)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | بادئة مساحة الاسم للسمة. |
| localName | const [String](../../../system/string/)\& | الاسم المحلي للسمة. |
| ns | const [String](../../../system/string/)\& | مسار URI مساحة الاسم للسمة. |

## XmlWriter::WriteStartAttribute(const String&) طريقة

يكتب بداية سمة بالاسم المحلي المحدد.

```cpp
void System::Xml::XmlWriter::WriteStartAttribute(const String &localName)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | الاسم المحلي للسمة. |

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [XmlWriter](../)
* النطاق [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)