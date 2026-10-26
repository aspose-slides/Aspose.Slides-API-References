---
title: ValueAs()
second_title: مرجع API برای Aspose.Slides برای C++
description: مقدار عنصر یا ویژگی XML معتبر را به عنوان نوع مشخص‌شده با استفاده از شیء IXmlNamespaceResolver برای حل پیشوندهای فضای‌نام باز می‌گرداند.
type: docs
weight: 144
url: /fa/system.xml.schema/xmlatomicvalue/valueas/
---
## XmlAtomicValue::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) متد

مقدار عنصر یا ویژگی XML معتبر را به عنوان نوع مشخص‌شده با استفاده از شیء [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) برای حل پیشوندهای فضای‌نام باز می‌گرداند.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlAtomicValue::ValueAs(const TypeInfo &type, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | const [TypeInfo](../../../system/typeinfo/)\& | نوعی که مقدار عنصر یا ویژگی XML معتبر را به‌ عنوان آن برمی‌گرداند. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | شیء [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) که برای حل پیشوندهای فضای‌نام استفاده می‌شود. |

### مقدار بازگشت

مقدار عنصر یا ویژگی XML معتبر به عنوان نوع درخواست‌شده.

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [Object](../../../system/object/)
* کلاس [TypeInfo](../../../system/typeinfo/)
* کلاس [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* کلاس [XmlAtomicValue](../)
* فضای‌نام [System::Xml::Schema](../../)
* کتابخانه [Aspose.Slides](../../../)