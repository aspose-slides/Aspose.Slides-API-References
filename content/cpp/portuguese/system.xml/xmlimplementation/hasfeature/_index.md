---
title: HasFeature()
second_title: Referência da API Aspose.Slides para C++
description: Testa se a implementação do Document Object Model (DOM) implementa um recurso específico.
type: docs
weight: 14
url: /pt/system.xml/xmlimplementation/hasfeature/
---
## XmlImplementation::HasFeature(const String\&, const String\&) método

Testa se a implementação do Modelo (DOM) [Object](../../../system/object/) do Documento implementa um recurso específico.

```cpp
bool System::Xml::XmlImplementation::HasFeature(const String &strFeature, const String &strVersion)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| strFeature | const [String](../../../system/string/)\& | O nome do pacote do recurso a ser testado. Este nome não diferencia maiúsculas de minúsculas. |
| strVersion | const [String](../../../system/string/)\& | Este é o número da versão do nome do pacote a ser testado. Se a versão não for especificada (**nullptr**), suportar qualquer versão do recurso faz com que o método retorne **true**. |

### Valor de Retorno

**true** se o recurso estiver implementado na versão especificada; caso contrário, **false**.

## Observações

A tabela a seguir mostra as combinações que fazem **HasFeature** retornar **true**. 

| strFeature | strVersion |
| --- | --- |
| XML | 1.0 |
| XML | 2.0 |

## Ver também

* Classe [String](../../../system/string/)
* Classe [XmlImplementation](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)