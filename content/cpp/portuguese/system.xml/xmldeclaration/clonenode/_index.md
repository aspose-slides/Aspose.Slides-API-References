---
title: CloneNode()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma duplicata deste nó.
type: docs
weight: 157
url: /pt/system.xml/xmldeclaration/clonenode/
---
## XmlDeclaration::CloneNode(bool) método

Cria uma duplicata deste nó.

```cpp
SharedPtr<XmlNode> System::Xml::XmlDeclaration::CloneNode(bool deep) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| deep | **bool** | **true** para clonar recursivamente a subárvore sob o nó especificado; **false** para clonar apenas o próprio nó. Como os nós [XmlDeclaration](../) não têm filhos, o nó clonado sempre inclui o valor de dados, independentemente da configuração do parâmetro. |

### Valor de Retorno

O nó clonado.

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlDeclaration](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)