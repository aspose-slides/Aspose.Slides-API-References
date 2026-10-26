---
title: ChangeType()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar det angivna värdet, vars typ är en av de giltiga representationerna av XML-schematypen som representeras av XmlSchemaDatatype, till den specificerade körningstypen.
type: docs
weight: 66
url: /sv/system.xml.schema/xmlschemadatatype/changetype/
---
## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&) metod

Konverterar det angivna värdet, vars typ är en av de giltiga representationerna av XML-schematypen som representeras av [XmlSchemaDatatype](../), till den specificerade körningstypen.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Inmatningsvärdet som ska konverteras till den specificerade typen. |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | Måltpypen som inmatningsvärdet ska konverteras till. |

### Returvärde

Det konverterade inmatningsvärdet.

## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) metod

Konverterar det angivna värdet, vars typ är en av de giltiga representationerna av XML-schematypen som representeras av [XmlSchemaDatatype](../), till den specificerade körningstypen med hjälp av [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) om [XmlSchemaDatatype](../) representerar **xs:QName**-typen eller en typ härledd från den.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Inmatningsvärdet som ska konverteras till den specificerade typen. |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | Måltpypen som inmatningsvärdet ska konverteras till. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | En [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) som används för att lösa namnrymdspräfixer. Detta är endast användbart om [XmlSchemaDatatype](../) representerar **xs:QName**-typen eller en typ härledd från den. |

### Returvärde

Det konverterade inmatningsvärdet.

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [Object](../../../system/object/)
* Klass [TypeInfo](../../../system/typeinfo/)
* Klass [XmlSchemaDatatype](../)
* Klass [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Namnrymd [System::Xml::Schema](../../)
* Bibliotek [Aspose.Slides](../../../)