---
title: CloneNode()
second_title: Aspose.Slides para C++ Referência da API
description: Cria uma duplicata deste nó.
type: docs
weight: 92
url: /pt/system.xml/xmlentityreference/clonenode/
---
## XmlEntityReference::CloneNode(bool) método

Cria uma duplicata deste nó.

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntityReference::CloneNode(bool deep) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| deep | **bool** | **true** para clonar recursivamente a subárvore sob o nó especificado; **false** para clonar apenas o próprio nó. Para nós [XmlEntityReference](../), este método sempre retorna um nó de referência de entidade sem filhos. O texto de substituição é definido quando o nó é inserido em um pai. |

### Valor de Retorno

O nó clonado.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlEntityReference](../)
* Espaço de nomes [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)