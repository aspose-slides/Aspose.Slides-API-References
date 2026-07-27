---
title: CloneNode()
second_title: Aspose.Slides para a referência da API C++
description: Cria uma duplicata deste nó.
type: docs
weight: 79
url: /pt/system.xml/xmlsignificantwhitespace/clonenode/
---
## XmlSignificantWhitespace::CloneNode(bool) método

Cria uma duplicata deste nó.

```cpp
SharedPtr<XmlNode> System::Xml::XmlSignificantWhitespace::CloneNode(bool deep) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| deep | **bool** | **true** para clonar recursivamente a subárvore sob o nó especificado; **false** para clonar apenas o próprio nó. Para nós de espaço em branco significativo, o nó clonado sempre inclui o valor de dados, independentemente da configuração do parâmetro. |

### Valor de Retorno

O nó clonado.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlSignificantWhitespace](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)