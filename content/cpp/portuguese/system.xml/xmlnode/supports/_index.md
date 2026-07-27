---
title: Supports()
second_title: Aspose.Slides para Referência da API C++
description: Testa se a implementação do DOM implementa um recurso específico.
type: docs
weight: 482
url: /pt/system.xml/xmlnode/supports/
---
## XmlNode::Supports(String, String) método

Testa se a implementação do DOM implementa um recurso específico.

```cpp
virtual bool System::Xml::XmlNode::Supports(String feature, String version)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| feature | [String](../../../system/string/) | O nome do pacote do recurso a ser testado. Este nome não diferencia maiúsculas de minúsculas. |
| version | [String](../../../system/string/) | O número da versão do nome do pacote a ser testado. Se a versão não for especificada (null), suportar qualquer versão do recurso faz com que o método retorne true. |

### Valor de retorno

**true** se o recurso estiver implementado na versão especificada; caso contrário, **false**.
## Observações



A tabela a seguir descreve as combinações que retornam **true**. 

| Recurso | [Version](../../../system/version/)|
| --- | --- |
| XML | 1.0 |
| XML | 2.0 |

## Ver também

* Classe [String](../../../system/string/)
* Classe [XmlNode](../)
* Espaço de nomes [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)