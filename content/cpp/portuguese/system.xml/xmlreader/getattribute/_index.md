---
title: GetAttribute()
second_title: Referência da API Aspose.Slides para C++
description: "Quando substituído em uma classe derivada, obtém o valor do atributo com o valor especificado XmlReader::get_Name."
type: docs
weight: 599
url: /pt/system.xml/xmlreader/getattribute/
---
## XmlReader::GetAttribute(String) método

Quando substituído em uma classe derivada, obtém o valor do atributo com o valor [XmlReader::get_Name](../get_name/) especificado.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | O nome qualificado do atributo. |

### Valor de Retorno

O valor do atributo especificado. Se o atributo não for encontrado ou o valor for [String::Empty](../../../system/string/empty/), **nullptr** é retornado.

## XmlReader::GetAttribute(String, String) método

Quando substituído em uma classe derivada, obtém o valor do atributo com os valores [XmlReader::get_LocalName](../get_localname/) e [XmlReader::get_NamespaceURI](../get_namespaceuri/) especificados.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name, String namespaceURI)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | O nome local do atributo. |
| namespaceURI | [String](../../../system/string/) | O URI do namespace do atributo. |

### Valor de Retorno

O valor do atributo especificado. Se o atributo não for encontrado ou o valor for [String::Empty](../../../system/string/empty/), **nullptr** é retornado. Este método não move o leitor.

## XmlReader::GetAttribute(int32_t) método

Quando substituído em uma classe derivada, obtém o valor do atributo com o índice especificado.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(int32_t i)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| i | **int32_t** | O índice do atributo. O índice é baseado em zero. (O primeiro atributo tem índice 0.) |

### Valor de Retorno

O valor do atributo especificado. Este método não move o leitor.

## Veja Também

* Classe [String](../../../system/string/)
* Classe [XmlReader](../)
* Espaço de nomes [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)