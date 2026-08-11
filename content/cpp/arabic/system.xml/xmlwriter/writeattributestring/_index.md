---
title: WriteAttributeString()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: عند تجاوزها في فئة مشتقة، تقوم بكتابة سمة بالاسم المحلي المحدد، ورابط مساحة الاسم، والقيمة.
type: docs
weight: 131
url: /ar/system.xml/xmlwriter/writeattributestring/
---
## XmlWriter::WriteAttributeString(const String\&, const String\&, const String\&) طريقة

عند تجاوزها في فئة مشتقة، تقوم بكتابة سمة بالاسم المحلي المحدد، ورابط مساحة الاسم، والقيمة.

```cpp
void System::Xml::XmlWriter::WriteAttributeString(const String &localName, const String &ns, const String &value)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | الاسم المحلي للخاصية. |
| ns | const [String](../../../system/string/)\& | رابط مساحة الاسم المرتبط بالخاصية. |
| value | const [String](../../../system/string/)\& | قيمة الخاصية. |

## XmlWriter::WriteAttributeString(const String\&, const String\&) طريقة

عند تجاوزها في فئة مشتقة، تقوم بكتابة السمة بالاسم المحلي والقيمة المحددين.

```cpp
void System::Xml::XmlWriter::WriteAttributeString(const String &localName, const String &value)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | الاسم المحلي للخاصية. |
| value | const [String](../../../system/string/)\& | قيمة الخاصية. |

## XmlWriter::WriteAttributeString(const String\&, const String\&, const String\&, const String\&) طريقة

عند تجاوزها في فئة مشتقة، تقوم بكتابة السمة بالبادئة والاسم المحلي ورابط مساحة الاسم والقيمة المحددين.

```cpp
void System::Xml::XmlWriter::WriteAttributeString(const String &prefix, const String &localName, const String &ns, const String &value)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | بادئة مساحة الاسم للخاصية. |
| localName | const [String](../../../system/string/)\& | الاسم المحلي للخاصية. |
| ns | const [String](../../../system/string/)\& | رابط مساحة الاسم للخاصية. |
| value | const [String](../../../system/string/)\& | قيمة الخاصية. |

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [XmlWriter](../)
* مساحة الاسم [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)