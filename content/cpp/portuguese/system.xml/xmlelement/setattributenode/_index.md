---
title: SetAttributeNode()
second_title: Aspose.Slides para C++ Referência da API
description: Adiciona o XmlAttribute especificado.
type: docs
weight: 261
url: /pt/system.xml/xmlelement/setattributenode/
---
## XmlElement::SetAttributeNode(SharedPtr\<XmlAttribute\>) método

Adiciona o [XmlAttribute](../../xmlattribute/) especificado.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(SharedPtr<XmlAttribute> newAttr)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| newAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | O nó [XmlAttribute](../../xmlattribute/) a ser adicionado à coleção de atributos para este elemento. |

### Valor de Retorno

Se o atributo substituir um atributo existente com o mesmo nome, o antigo [XmlAttribute](../../xmlattribute/) é retornado; caso contrário, **nullptr** é retornado.

## XmlElement::SetAttributeNode(String, String) método

Adiciona o [XmlAttribute](../../xmlattribute/) especificado.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(String localName, String namespaceURI)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| localName | [String](../../../system/string/) | O nome local do atributo. |
| namespaceURI | [String](../../../system/string/) | O URI do namespace do atributo. |

### Valor de Retorno

O [XmlAttribute](../../xmlattribute/) a ser adicionado.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlAttribute](../../xmlattribute/)
* Classe [XmlElement](../)
* Classe [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)