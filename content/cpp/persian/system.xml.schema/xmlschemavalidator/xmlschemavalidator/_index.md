---
title: XmlSchemaValidator()
second_title: Aspose.Slides برای C++ مستندات API
description: یک نمونه جدید از کلاس XmlSchemaValidator را مقداردهی می‌کند.
type: docs
weight: 92
url: /fa/system.xml.schema/xmlschemavalidator/xmlschemavalidator/
---
## XmlSchemaValidator::XmlSchemaValidator(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlSchemaSet\>\&, const SharedPtr\<IXmlNamespaceResolver\>\&, XmlSchemaValidationFlags) سازنده

یک نمونه جدید از کلاس [XmlSchemaValidator](../) را مقداردهی می‌کند.

```cpp
System::Xml::Schema::XmlSchemaValidator::XmlSchemaValidator(const SharedPtr<XmlNameTable> &nameTable, const SharedPtr<XmlSchemaSet> &schemas, const SharedPtr<IXmlNamespaceResolver> &namespaceResolver, XmlSchemaValidationFlags validationFlags)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| nameTable | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\>\& | یک شیء [XmlNameTable](../../../system.xml/xmlnametable/) که شامل نام‌های عنصر و ویژگی به عنوان رشته‌های اتمی شده است. |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\>\& | یک شیء [XmlSchemaSet](../../xmlschemaset/) که شامل طرح‌های XML [Schema](../../) Definition Language (XSD) مورد استفاده برای اعتبارسنجی است. |
| namespaceResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | یک شیء [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) که برای حل فضاهای نامی که در هنگام اعتبارسنجی مواجه می‌شود استفاده می‌شود. |
| validationFlags | [XmlSchemaValidationFlags](../../xmlschemavalidationflags/) | یک مقدار XmlSchemaValidationFlags که گزینه‌های اعتبارسنجی طرح را مشخص می‌کند. |

## موارد مرتبط

* شمارشی [XmlSchemaValidationFlags](../../xmlschemavalidationflags/)
* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlNameTable](../../../system.xml/xmlnametable/)
* کلاس [XmlSchemaSet](../../xmlschemaset/)
* کلاس [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* کلاس [XmlSchemaValidator](../)
* فضای‌نام [System::Xml::Schema](../../)
* کتابخانه [Aspose.Slides](../../../)