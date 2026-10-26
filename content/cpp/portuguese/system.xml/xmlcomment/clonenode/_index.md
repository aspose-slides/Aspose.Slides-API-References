---
title: CloneNode()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma duplicata deste nó.
type: docs
weight: 40
url: /pt/system.xml/xmlcomment/clonenode/
---
## XmlComment::CloneNode(bool) método

Cria uma duplicata deste nó.

```cpp
SharedPtr<XmlNode> System::Xml::XmlComment::CloneNode(bool deep) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| deep | **bool** | **true** para clonar recursivamente a subárvore sob o nó especificado; **false** para clonar somente o próprio nó. Como nós de comentário não têm filhos, o nó clonado sempre inclui o conteúdo de texto, independentemente da configuração do parâmetro. |

### Valor de Retorno

O nó clonado.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlComment](../)
* Espaço de nomes [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)