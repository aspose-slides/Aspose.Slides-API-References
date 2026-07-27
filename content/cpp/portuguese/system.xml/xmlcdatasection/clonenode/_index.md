---
title: CloneNode()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma cópia duplicada deste nó.
type: docs
weight: 53
url: /pt/system.xml/xmlcdatasection/clonenode/
---
## XmlCDataSection::CloneNode(bool) método


Cria uma cópia duplicada deste nó.

```cpp
SharedPtr<XmlNode> System::Xml::XmlCDataSection::CloneNode(bool deep) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| deep | **bool** | **true** para clonar recursivamente a subárvore sob o nó especificado; **false** para clonar apenas o nó em si. Como os nós CDATA não têm filhos, independentemente da configuração do parâmetro, o nó clonado sempre incluirá o conteúdo dos dados. |

### Valor de Retorno

O nó clonado.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlCDataSection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)