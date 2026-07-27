---
title: MoveToAttribute()
second_title: Referência da API Aspose.Slides para C++
description: Move para o atributo com o nome especificado.
type: docs
weight: 300
url: /pt/system.xml/xmlnodereader/movetoattribute/
---
## XmlNodeReader::MoveToAttribute(String) método


Move para o atributo com o nome especificado.

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | O nome qualificado do atributo. |

### Valor de Retorno

**true** se o atributo for encontrado; caso contrário, **false**. Se **false**, a posição do leitor não muda.

## XmlNodeReader::MoveToAttribute(String, String) método


Move para o atributo com o nome local e o URI do namespace especificados.

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name, String namespaceURI) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | O nome local do atributo. |
| namespaceURI | [String](../../../system/string/) | O URI do namespace do atributo. |

### Valor de Retorno

**true** se o atributo for encontrado; caso contrário, **false**. Se **false**, a posição do leitor não muda.

## XmlNodeReader::MoveToAttribute(int32_t) método


Move para o atributo com o índice especificado.

```cpp
void System::Xml::XmlNodeReader::MoveToAttribute(int32_t attributeIndex) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| attributeIndex | **int32_t** | O índice do atributo. |

## Veja Também

* Classe [String](../../../system/string/)
* Classe [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)