---
title: ParseValue()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: عند تجاوزها في فئة مشتقة، يتحقق من صحة السلسلة المحددة مقابل نوع بسيط مدمج أو معرف من قبل المستخدم.
type: docs
weight: 53
url: /ar/system.xml.schema/xmlschemadatatype/parsevalue/
---
## XmlSchemaDatatype::ParseValue(String, SharedPtr\<XmlNameTable\>, SharedPtr\<IXmlNamespaceResolver\>) طريقة

عند تجاوزها في فئة مشتقة، تتحقق من صحة **string** المحدد مقابل نوع بسيط مدمج أو معرف من قبل المستخدم.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ParseValue(String s, SharedPtr<XmlNameTable> nameTable, SharedPtr<IXmlNamespaceResolver> nsmgr)=0
```

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| s | [String](../../../system/string/) | ال**string** للتحقق من صحتها مقابل النوع البسيط. |
| nameTable | [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\> | ال[XmlNameTable](../../../system.xml/xmlnametable/) لاستخدامه في التجزئة أثناء تحليل **string** إذا كان هذا الكائن [XmlSchemaDatatype](../) يمثل نوع **xs:NCName**. |
| nsmgr | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | ال[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) لاستخدامه أثناء تحليل **string** إذا كان هذا الكائن [XmlSchemaDatatype](../) يمثل نوع **xs:QName**. |

### قيمة الإرجاع

كائن [Object](../../../system/object/) يمكن تحويله بأمان إلى النوع الذي تُعيده عملية [XmlSchemaDatatype::get_ValueType](../get_valuetype/).

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [Object](../../../system/object/)
* فئة [String](../../../system/string/)
* فئة [XmlNameTable](../../../system.xml/xmlnametable/)
* فئة [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* فئة [XmlSchemaDatatype](../)
* مساحة اسم [System::Xml::Schema](../../)
* مكتبة [Aspose.Slides](../../../)