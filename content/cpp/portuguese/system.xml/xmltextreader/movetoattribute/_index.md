---
title: MoveToAttribute()
second_title: Referência da API Aspose.Slides para C++
description: Move para o atributo com o nome especificado.
type: docs
weight: 508
url: /pt/system.xml/xmltextreader/movetoattribute/
---
## XmlTextReader::MoveToAttribute(String) método


Move para o atributo com o nome especificado.

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String name) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | O nome qualificado do atributo. |

### Valor de Retorno

**true** se o atributo for encontrado; caso contrário, **false**. Se **false**, a posição do leitor não é alterada.

## XmlTextReader::MoveToAttribute(String, String) método


Move para o atributo com o nome local e o URI do namespace especificados.

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String localName, String namespaceURI) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| localName | [String](../../../system/string/) | O nome local do atributo. |
| namespaceURI | [String](../../../system/string/) | O URI do namespace do atributo. |

### Valor de Retorno

**true** se o atributo for encontrado; caso contrário, **false**. Se **false**, a posição do leitor não é alterada.

## XmlTextReader::MoveToAttribute(int32_t) método


Move para o atributo com o índice especificado.

```cpp
void System::Xml::XmlTextReader::MoveToAttribute(int32_t i) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| i | **int32_t** | O índice do atributo. |

## Veja Também

* Classe [String](../../../system/string/)
* Classe [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)