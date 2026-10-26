---
title: PrependChild()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona o nó especificado ao início da lista de nós filhos deste nó.
type: docs
weight: 261
url: /pt/system.xml/xmlattribute/prependchild/
---
## XmlAttribute::PrependChild(SharedPtr\<XmlNode\>) método

Adiciona o nó especificado ao início da lista de nós filhos deste nó.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::PrependChild(SharedPtr<XmlNode> newChild) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | O [XmlNode](../../xmlnode/) a ser adicionado. Se for um [XmlDocumentFragment](../../xmldocumentfragment/), todo o conteúdo do fragmento de documento será movido para a lista de filhos deste nó. |

### Valor de Retorno

O [XmlNode](../../xmlnode/) adicionado.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlAttribute](../)
* Espaço de nomes [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)