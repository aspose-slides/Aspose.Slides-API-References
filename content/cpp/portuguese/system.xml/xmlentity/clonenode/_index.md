---
title: CloneNode()
second_title: Aspose.Slides para C++ Referência da API
description: Cria uma duplicata deste nó. Nós de entidade não podem ser clonados. Chamar este método em um objeto XmlEntity lança uma exceção.
type: docs
weight: 170
url: /pt/system.xml/xmlentity/clonenode/
---
## XmlEntity::CloneNode(bool) método


Cria uma duplicata deste nó. Nós de entidade não podem ser clonados. Chamar este método em um objeto [XmlEntity](../) lança uma exceção.

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntity::CloneNode(bool deep) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| deep | **bool** | **true** para clonar recursivamente a subárvore sob o nó especificado; **false** para clonar apenas o próprio nó. |

### Valor de Retorno

Uma cópia do [XmlNode](../../xmlnode/) a partir do qual o método é chamado.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlEntity](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)