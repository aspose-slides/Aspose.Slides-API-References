---
title: SetAttribute()
second_title: Referência da API Aspose.Slides para C++
description: Define o valor do atributo com o nome especificado.
type: docs
weight: 222
url: /pt/system.xml/xmlelement/setattribute/
---
## XmlElement::SetAttribute(String, String) método


Define o valor do atributo com o nome especificado.

```cpp
virtual void System::Xml::XmlElement::SetAttribute(String name, String value)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | O nome do atributo a ser criado ou alterado. Este é um nome qualificado. Se o nome contiver dois-pontos, ele será analisado em componentes de prefixo e nome local. |
| value | [String](../../../system/string/) | O valor a ser definido para o atributo. |

## XmlElement::SetAttribute(String, String, String) método


Define o valor do atributo com o nome local e o URI do namespace especificados.

```cpp
virtual String System::Xml::XmlElement::SetAttribute(String localName, String namespaceURI, String value)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| localName | [String](../../../system/string/) | O nome local do atributo. |
| namespaceURI | [String](../../../system/string/) | O URI do namespace do atributo. |
| value | [String](../../../system/string/) | O valor a ser definido para o atributo. |

### Valor de Retorno

O valor do atributo.

## Veja Também

* Classe [String](../../../system/string/)
* Classe [XmlElement](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)