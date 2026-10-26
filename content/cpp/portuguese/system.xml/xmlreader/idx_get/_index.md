---
title: idx_get()
second_title: Referência da API Aspose.Slides para C++
description: Quando sobrescrito em uma classe derivada, obtém o valor do atributo com o índice especificado.
type: docs
weight: 612
url: /pt/system.xml/xmlreader/idx_get/
---
## XmlReader::idx_get(int32_t) método

Quando substituído em uma classe derivada, obtém o valor do atributo com o índice especificado.

```cpp
virtual String System::Xml::XmlReader::idx_get(int32_t i)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| i | **int32_t** | O índice do atributo. |

### Valor de Retorno

O valor do atributo especificado.

## XmlReader::idx_get(String) método

Quando substituído em uma classe derivada, obtém o valor do atributo com o valor [XmlReader::get_Name](../get_name/) especificado.

```cpp
virtual String System::Xml::XmlReader::idx_get(String name)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | O nome qualificado do atributo. |

### Valor de Retorno

O valor do atributo especificado. Se o atributo não for encontrado, **nullptr** é retornado.

## XmlReader::idx_get(String, String) método

Quando substituído em uma classe derivada, obtém o valor do atributo com os valores [XmlReader::get_LocalName](../get_localname/) e [XmlReader::get_NamespaceURI](../get_namespaceuri/) especificados.

```cpp
virtual String System::Xml::XmlReader::idx_get(String name, String namespaceURI)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | O nome local do atributo. |
| namespaceURI | [String](../../../system/string/) | O URI do namespace do atributo. |

### Valor de Retorno

O valor do atributo especificado. Se o atributo não for encontrado, **nullptr** é retornado.

## Veja Também

* Classe [String](../../../system/string/)
* Classe [XmlReader](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)