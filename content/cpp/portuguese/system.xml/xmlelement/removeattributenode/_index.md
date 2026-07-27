---
title: RemoveAttributeNode()
second_title: Referência da API Aspose.Slides para C++
description: Remove o XmlAttribute especificado.
type: docs
weight: 274
url: /pt/system.xml/xmlelement/removeattributenode/
---
## XmlElement::RemoveAttributeNode(SharedPtr\<XmlAttribute\>) método


Remove o [XmlAttribute](../../xmlattribute/) especificado.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(SharedPtr<XmlAttribute> oldAttr)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| oldAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | O nó [XmlAttribute](../../xmlattribute/) a ser removido. Se o atributo removido tem um valor padrão, ele será imediatamente substituído. |

### Valor de Retorno

O [XmlAttribute](../../xmlattribute/) removido ou **nullptr** se **oldAttr** não for um nó de atributo do [XmlElement](../).

## XmlElement::RemoveAttributeNode(String, String) método


Remove o [XmlAttribute](../../xmlattribute/) especificado pelo nome local e pelo URI de namespace. (Se o atributo removido tem um valor padrão, ele será imediatamente substituído).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(String localName, String namespaceURI)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| localName | [String](../../../system/string/) | O nome local do atributo. |
| namespaceURI | [String](../../../system/string/) | O URI de namespace do atributo. |

### Valor de Retorno

O [XmlAttribute](../../xmlattribute/) removido ou **nullptr** se o [XmlElement](../) não possuir um nó de atributo correspondente.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlAttribute](../../xmlattribute/)
* Classe [XmlElement](../)
* Classe [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)