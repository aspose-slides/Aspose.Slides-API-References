---
title: ChangeType()
second_title: Aspose.Slides for C++ API Referencia
description: Átalakítja a megadott értéket, amelynek típusa az XmlSchemaDatatype által képviselt XML-séma típus egyik érvényes reprezentációja, a megadott futásidejű típusra.
type: docs
weight: 66
url: /hu/system.xml.schema/xmlschemadatatype/changetype/
---
## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&) metódus


Átalakítja a megadott értéket, amelynek típusa a [XmlSchemaDatatype](../) által képviselt XML-sématípus egyik érvényes reprezentációja, a megadott futásidejű típusra.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | The input value to convert to the specified type. |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | The target type to convert the input value to. |

### Visszatérési érték

Az átalakított bemeneti érték.

## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) metódus


Átalakítja a megadott értéket, amelynek típusa a [XmlSchemaDatatype](../) által képviselt XML-sématípus egyik érvényes reprezentációja, a megadott futásidejű típusra a [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) használatával, ha a [XmlSchemaDatatype](../) a **xs:QName** típust vagy abból származtatott típust képviseli.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | The input value to convert to the specified type. |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | The target type to convert the input value to. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Egy [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) amely az űrtér előtagok feloldásához használható. Ez csak akkor hasznos, ha a [XmlSchemaDatatype](../) a **xs:QName** típust vagy abból származtatott típust képviseli. |

### Visszatérési érték

Az átalakított bemeneti érték.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Object](../../../system/object/)
* Osztály [TypeInfo](../../../system/typeinfo/)
* Osztály [XmlSchemaDatatype](../)
* Osztály [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Névterület [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)