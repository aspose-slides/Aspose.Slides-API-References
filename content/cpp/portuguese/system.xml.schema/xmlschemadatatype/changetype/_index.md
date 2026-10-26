---
title: ChangeType()
second_title: Referência da API Aspose.Slides para C++
description: Converte o valor especificado, cujo tipo é uma das representações válidas do tipo de esquema XML representado por XmlSchemaDatatype, para o tipo de tempo de execução especificado.
type: docs
weight: 66
url: /pt/system.xml.schema/xmlschemadatatype/changetype/
---
## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&) método

Converte o valor especificado, cujo tipo é uma das representações válidas do tipo de esquema XML representado por [XmlSchemaDatatype](../), para o tipo de tempo de execução especificado.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | O valor de entrada a ser convertido para o tipo especificado. |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | O tipo de destino para o qual o valor de entrada será convertido. |

### Valor de retorno

O valor de entrada convertido.

## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) método

Converte o valor especificado, cujo tipo é uma das representações válidas do tipo de esquema XML representado por [XmlSchemaDatatype](../), para o tipo de tempo de execução especificado usando [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) se [XmlSchemaDatatype](../) representar o tipo **xs:QName** ou um tipo derivado dele.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | O valor de entrada a ser convertido para o tipo especificado. |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | O tipo de destino para o qual o valor de entrada será convertido. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Um [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) usado para resolver prefixos de namespace. Isto somente é útil se [XmlSchemaDatatype](../) representar o tipo **xs:QName** ou um tipo derivado dele. |

### Valor de retorno

O valor de entrada convertido.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [TypeInfo](../../../system/typeinfo/)
* Classe [XmlSchemaDatatype](../)
* Classe [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Namespace [System::Xml::Schema](../../)
* Biblioteca [Aspose.Slides](../../../)