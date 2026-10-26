---
title: CloneNode()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma duplicata deste nó. Nós de notação não podem ser clonados. Chamar este método em um objeto XmlNotation lança uma exceção.
type: docs
weight: 118
url: /pt/system.xml/xmlnotation/clonenode/
---
## XmlNotation::CloneNode(bool) método


Cria uma duplicata deste nó. Nós de notação não podem ser clonados. Chamar este método em um objeto [XmlNotation](../) lança uma exceção.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNotation::CloneNode(bool deep) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| deep | **bool** | **true** para clonagem recursiva da subárvore sob o nó especificado; **false** para clonar apenas o nó em si. |

### Valor de Retorno

Uma cópia [XmlNode](../../xmlnode/) do nó a partir do qual o método é chamado.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [XmlNotation](../)
* Espaço de nomes [System::Xml](../../)
* Library [Aspose.Slides](../../../)