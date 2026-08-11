---
title: SetAttributeNode()
second_title: Aspose.Slides برای C++ مرجع API
description: ویژگی XmlAttribute مشخص شده را اضافه می‌کند.
type: docs
weight: 261
url: /fa/system.xml/xmlelement/setattributenode/
---
## XmlElement::SetAttributeNode(SharedPtr\<XmlAttribute\>) متد

مورد [XmlAttribute](../../xmlattribute/) مشخص شده را اضافه می‌کند.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(SharedPtr<XmlAttribute> newAttr)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| newAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | گره [XmlAttribute](../../xmlattribute/) که برای اضافه کردن به مجموعهٔ ویژگی‌ها برای این عنصر استفاده می‌شود. |

### مقدار بازگشت

اگر ویژگی جایگزین یک ویژگی موجود با همان نام شود، [XmlAttribute](../../xmlattribute/) قدیمی بازگردانده می‌شود؛ در غیر این صورت، **nullptr** بازگردانده می‌شود.

## XmlElement::SetAttributeNode(String, String) متد

مورد [XmlAttribute](../../xmlattribute/) مشخص شده را اضافه می‌کند.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(String localName, String namespaceURI)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| localName | [String](../../../system/string/) | نام محلی ویژگی. |
| namespaceURI | [String](../../../system/string/) | URI فضای نام ویژگی. |

### مقدار بازگشت

[XmlAttribute](../../xmlattribute/) برای اضافه کردن.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlAttribute](../../xmlattribute/)
* کلاس [XmlElement](../)
* کلاس [String](../../../system/string/)
* فضای‌نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)