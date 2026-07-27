---
title: CheckValidity()
second_title: Referência da API Aspose.Slides para C++
description: Verifica se os dados XML no XPathNavigator estão em conformidade com o esquema da linguagem de definição XML Schema (XSD) fornecido.
type: docs
weight: 755
url: /pt/system.xml.xpath/xpathnavigator/checkvalidity/
---
## XPathNavigator::CheckValidity(SharedPtr\<System::Xml::Schema::XmlSchemaSet\>, System::Xml::Schema::ValidationEventHandler) método

Verifica se os dados XML em [XPathNavigator](../) estão em conformidade com a linguagem de definição XML [Schema](../../../system.xml.schema/) (XSD) fornecida.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::CheckValidity(SharedPtr<System::Xml::Schema::XmlSchemaSet> schemas, System::Xml::Schema::ValidationEventHandler validationEventHandler)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)\> | O XmlSchemaSet contendo os esquemas usados para validar os dados XML contidos em [XPathNavigator](../). |
| validationEventHandler | [System::Xml::Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | O ValidationEventHandler que recebe informações sobre avisos e erros de validação de esquema. |

### Valor de Retorno

**true** se não ocorreram erros de validação de esquema; caso contrário, **false**.

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Classe [XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)
* Classe [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Biblioteca [Aspose.Slides](../../../)