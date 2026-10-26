---
title: GetAttributeNode()
second_title: Referência da API Aspose.Slides para C++
description: Retorna o XmlAttribute com o nome especificado.
type: docs
weight: 248
url: /pt/system.xml/xmlelement/getattributenode/
---
## XmlElement::GetAttributeNode(String) método

Retorna o [XmlAttribute](../../xmlattribute/) com o nome especificado.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String name)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | O nome do atributo a ser recuperado. Este é um nome qualificado. Ele é comparado ao valor **get_Name** do nó correspondente. |

### Valor de Retorno

O [XmlAttribute](../../xmlattribute/) especificado ou **nullptr** se nenhum atributo correspondente for encontrado.

## XmlElement::GetAttributeNode(String, String) método

Retorna o [XmlAttribute](../../xmlattribute/) com o nome local e o URI do namespace especificados.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String localName, String namespaceURI)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| localName | [String](../../../system/string/) | O nome local do atributo. |
| namespaceURI | [String](../../../system/string/) | O URI do namespace do atributo. |

### Valor de Retorno

O [XmlAttribute](../../xmlattribute/) especificado ou **nullptr** se nenhum atributo correspondente for encontrado.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlAttribute](../../xmlattribute/)
* Classe [String](../../../system/string/)
* Classe [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)