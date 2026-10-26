---
title: ValidateElement()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يتحقق من صحة العنصر في السياق الحالي.
type: docs
weight: 131
url: /ar/system.xml.schema/xmlschemavalidator/validateelement/
---
## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) طريقة

يتحقق من صحة العنصر في السياق الحالي.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | الاسم المحلي للعنصر المراد التحقق منه. |
| namespaceUri | const [String](../../../system/string/)\& | معرف مساحة الاسم للعنصر المراد التحقق منه. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | كائن [XmlSchemaInfo](../../xmlschemainfo/) يتم تعيين خصائصه عند نجاح التحقق من اسم العنصر. يمكن أن تكون هذه المعلمة **nullptr**. |

## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&, const String\&, const String\&, const String\&, const String\&) طريقة

يتحقق من صحة العنصر في السياق الحالي مع قيم السمات **xsi:Type**, **xsi:Nil**, **xsi:SchemaLocation**, و **xsi:NoNamespaceSchemaLocation** المحددة.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo, const String &xsiType, const String &xsiNil, const String &xsiSchemaLocation, const String &xsiNoNamespaceSchemaLocation)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | الاسم المحلي للعنصر المراد التحقق منه. |
| namespaceUri | const [String](../../../system/string/)\& | معرف مساحة الاسم للعنصر المراد التحقق منه. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | كائن [XmlSchemaInfo](../../xmlschemainfo/) يتم تعيين خصائصه عند نجاح التحقق من اسم العنصر. يمكن أن تكون هذه المعلمة **nullptr**. |
| xsiType | const [String](../../../system/string/)\& | قيمة سمة **xsi:Type** للعنصر. يمكن أن تكون هذه المعلمة **nullptr**. |
| xsiNil | const [String](../../../system/string/)\& | قيمة سمة **xsi:Nil** للعنصر. يمكن أن تكون هذه المعلمة **nullptr**. |
| xsiSchemaLocation | const [String](../../../system/string/)\& | قيمة سمة **xsi:SchemaLocation** للعنصر. يمكن أن تكون هذه المعلمة **nullptr**. |
| xsiNoNamespaceSchemaLocation | const [String](../../../system/string/)\& | قيمة سمة **xsi:NoNamespaceSchemaLocation** للعنصر. يمكن أن تكون هذه المعلمة **nullptr**. |

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [String](../../../system/string/)
* فئة [XmlSchemaInfo](../../xmlschemainfo/)
* فئة [XmlSchemaValidator](../)
* مساحة الاسم [System::Xml::Schema](../../)
* مكتبة [Aspose.Slides](../../../)