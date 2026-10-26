---
title: ValidateText()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يتحقق مما إذا كانت سلسلة النص المحددة مسموحة في سياق العنصر الحالي، ويجمع النص للتحقق إذا كان للعنصر الحالي محتوى بسيط.
type: docs
weight: 183
url: /ar/system.xml.schema/xmlschemavalidator/validatetext/
---
## XmlSchemaValidator::ValidateText(const String\&) طريقة

يتحقق مما إذا كانت **سلسلة** النص المحددة مسموحة في سياق العنصر الحالي، ويجمع النص للتحقق إذا كان للعنصر الحالي محتوى بسيط.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(const String &elementValue)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| elementValue | const [String](../../../system/string/)\& | **سلسلة** نصية للتحقق في سياق العنصر الحالي. |

## XmlSchemaValidator::ValidateText(XmlValueGetter) طريقة

يتحقق مما إذا كان النص الذي تُعيده كائن XmlValueGetter المحدد مسموحًا به في سياق العنصر الحالي، ويجمع النص للتحقق إذا كان للعنصر الحالي محتوى بسيط.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(XmlValueGetter elementValue)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| elementValue | [XmlValueGetter](../../xmlvaluegetter/) | استدعاء رد نداء XmlValueGetter يُستخدم لتمرير قيمة النص كنمط متوافق مع نوع لغة تعريف XML [Schema](../../) (XSD) للخاصية. |

## انظر أيضًا

* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* فئة [String](../../../system/string/)
* فئة [XmlSchemaValidator](../)
* نطاق [System::Xml::Schema](../../)
* مكتبة [Aspose.Slides](../../../)