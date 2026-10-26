---
title: XmlSchemaValidator()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بتهيئة نسخة جديدة من الفئة XmlSchemaValidator.
type: docs
weight: 92
url: /ar/system.xml.schema/xmlschemavalidator/xmlschemavalidator/
---
## XmlSchemaValidator::XmlSchemaValidator(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlSchemaSet\>\&, const SharedPtr\<IXmlNamespaceResolver\>\&, XmlSchemaValidationFlags) منشئ

يقوم بتهيئة نسخة جديدة من الفئة [XmlSchemaValidator](../).

```cpp
System::Xml::Schema::XmlSchemaValidator::XmlSchemaValidator(const SharedPtr<XmlNameTable> &nameTable, const SharedPtr<XmlSchemaSet> &schemas, const SharedPtr<IXmlNamespaceResolver> &namespaceResolver, XmlSchemaValidationFlags validationFlags)
```

### معاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| nameTable | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\>\& | كائن [XmlNameTable](../../../system.xml/xmlnametable/) يحتوي على أسماء العناصر والسمات كسلاسل مجزأة. |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\>\& | كائن [XmlSchemaSet](../../xmlschemaset/) يحتوي على مخططات XML [Schema](../../) لغة التعريف (XSD) المستخدمة في التحقق. |
| namespaceResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | كائن [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) يُستخدم لحل مساحات الأسماء التي تُواجه أثناء التحقق. |
| validationFlags | [XmlSchemaValidationFlags](../../xmlschemavalidationflags/) | قيمة XmlSchemaValidationFlags تحدد خيارات التحقق من المخطط. |

## انظر أيضًا

* عدد [XmlSchemaValidationFlags](../../xmlschemavalidationflags/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [XmlNameTable](../../../system.xml/xmlnametable/)
* فئة [XmlSchemaSet](../../xmlschemaset/)
* فئة [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* فئة [XmlSchemaValidator](../)
* مساحة الأسماء [System::Xml::Schema](../../)
* مكتبة [Aspose.Slides](../../../)