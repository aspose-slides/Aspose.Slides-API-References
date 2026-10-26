---
title: CloneNode()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma cópia deste nó.
type: docs
weight: 118
url: /pt/system.xml/xmldocumenttype/clonenode/
---
## XmlDocumentType::CloneNode(bool) método


Creates a duplicate of this node.

```cpp
SharedPtr<XmlNode> System::Xml::XmlDocumentType::CloneNode(bool deep) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| deep | **bool** | **true** para clonar recursivamente a subárvore sob o nó especificado; **false** para clonar apenas o próprio nó. Para nós de tipo de documento, o nó clonado sempre inclui a subárvore, independentemente da configuração do parâmetro. |

### Valor de Retorno

O nó clonado.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlDocumentType](../)
* namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)