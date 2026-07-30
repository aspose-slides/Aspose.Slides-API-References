---
title: ChangeType()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte il valore specificato, il cui tipo è una delle rappresentazioni valide del tipo di schema XML rappresentato da XmlSchemaDatatype, al tipo di runtime specificato.
type: docs
weight: 66
url: /it/system.xml.schema/xmlschemadatatype/changetype/
---
## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&) metodo

Converte il valore specificato, il cui tipo è una delle rappresentazioni valide del tipo di schema XML rappresentato da [XmlSchemaDatatype](../), al tipo di runtime specificato.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Il valore di input da convertire al tipo specificato. |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | Il tipo di destinazione a cui convertire il valore di input. |

### Valore restituito

Il valore di input convertito.

## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) metodo

Converte il valore specificato, il cui tipo è una delle rappresentazioni valide del tipo di schema XML rappresentato da [XmlSchemaDatatype](../), al tipo di runtime specificato utilizzando [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) se [XmlSchemaDatatype](../) rappresenta il tipo **xs:QName** o un tipo derivato da esso.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Il valore di input da convertire al tipo specificato. |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | Il tipo di destinazione a cui convertire il valore di input. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Un [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) utilizzato per risolvere i prefissi dei namespace. È utile solo se [XmlSchemaDatatype](../) rappresenta il tipo **xs:QName** o un tipo derivato da esso. |

### Valore restituito

Il valore di input convertito.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [TypeInfo](../../../system/typeinfo/)
* Classe [XmlSchemaDatatype](../)
* Classe [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Namespace [System::Xml::Schema](../../)
* Libreria [Aspose.Slides](../../../)