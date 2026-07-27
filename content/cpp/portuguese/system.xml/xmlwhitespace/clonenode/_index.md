---
title: CloneNode()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma duplicata deste nó.
type: docs
weight: 79
url: /pt/system.xml/xmlwhitespace/clonenode/
---
## XmlWhitespace::CloneNode(bool) método

Cria uma duplicata deste nó.

```cpp
SharedPtr<XmlNode> System::Xml::XmlWhitespace::CloneNode(bool deep) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| deep | **bool** | **true** para clonar recursivamente a subárvore sob o nó especificado; **false** para clonar apenas o próprio nó. Para nós de espaço em branco, o nó clonado sempre inclui o valor de dados, independentemente da configuração do parâmetro. |

### Valor de Retorno

O nó clonado.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlWhitespace](../)
* Espaço de nomes [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)