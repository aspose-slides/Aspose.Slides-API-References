---
title: ValueAs()
second_title: Referência da API Aspose.Slides para C++
description: Retorna o valor do elemento ou atributo XML validado como o tipo especificado usando o objeto IXmlNamespaceResolver especificado para resolver prefixos de namespace.
type: docs
weight: 144
url: /pt/system.xml.schema/xmlatomicvalue/valueas/
---
## XmlAtomicValue::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) método

Retorna o valor do elemento ou atributo XML validado como o tipo especificado usando o objeto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) especificado para resolver prefixos de namespace.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlAtomicValue::ValueAs(const TypeInfo &type, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| type | const [TypeInfo](../../../system/typeinfo/)\& | O tipo para o qual retornar o valor do elemento ou atributo XML validado. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | O objeto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) usado para resolver prefixos de namespace. |

### Valor de Retorno

O valor do elemento ou atributo XML validado como o tipo solicitado.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [TypeInfo](../../../system/typeinfo/)
* Classe [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Classe [XmlAtomicValue](../)
* Espaço de nomes [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)