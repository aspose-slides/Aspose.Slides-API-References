---
title: MoveToAttribute()
second_title: Referência da API Aspose.Slides para C++
description: "Quando sobrescrito em uma classe derivada, move para o atributo com o valor especificado de XmlReader::get_Name."
type: docs
weight: 625
url: /pt/system.xml/xmlreader/movetoattribute/
---
## XmlReader::MoveToAttribute(String) método


Quando sobrescrito em uma classe derivada, move para o atributo com o valor [XmlReader::get_Name](../get_name/) especificado.

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | O nome qualificado do atributo. |

### Valor de Retorno

**true** se o atributo for encontrado; caso contrário, **false**. Se **false**, a posição do leitor não muda.

## XmlReader::MoveToAttribute(String, String) método


Quando sobrescrito em uma classe derivada, move para o atributo com os valores [XmlReader::get_LocalName](../get_localname/) e [XmlReader::get_NamespaceURI](../get_namespaceuri/) especificados.

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name, String ns)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | O nome local do atributo. |
| ns | [String](../../../system/string/) | O URI do namespace do atributo. |

### Valor de Retorno

**true** se o atributo for encontrado; caso contrário, **false**. Se **false**, a posição do leitor não muda.

## XmlReader::MoveToAttribute(int32_t) método


Quando sobrescrito em uma classe derivada, move para o atributo com o índice especificado.

```cpp
virtual void System::Xml::XmlReader::MoveToAttribute(int32_t i)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| i | **int32_t** | O índice do atributo. |

## Ver Também

* Classe [String](../../../system/string/)
* Classe [XmlReader](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)