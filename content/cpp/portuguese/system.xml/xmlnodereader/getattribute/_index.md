---
title: GetAttribute()
second_title: Referência da API Aspose.Slides para C++
description: Retorna o valor do atributo com o nome especificado.
type: docs
weight: 287
url: /pt/system.xml/xmlnodereader/getattribute/
---
## XmlNodeReader::GetAttribute(String) método

Retorna o valor do atributo com o nome especificado.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | O nome qualificado do atributo. |

### Valor de Retorno

O valor do atributo especificado. Se o atributo não for encontrado, **nullptr** é retornado.

## XmlNodeReader::GetAttribute(String, String) método

Retorna o valor do atributo com o nome local e o URI do namespace especificados.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name, String namespaceURI) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | O nome local do atributo. |
| namespaceURI | [String](../../../system/string/) | O URI do namespace do atributo. |

### Valor de Retorno

O valor do atributo especificado. Se o atributo não for encontrado, **nullptr** é retornado.

## XmlNodeReader::GetAttribute(int32_t) método

Retorna o valor do atributo com o índice especificado.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(int32_t attributeIndex) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| attributeIndex | **int32_t** | O índice do atributo. O índice começa em zero. (O primeiro atributo tem índice 0.) |

### Valor de Retorno

O valor do atributo especificado.

## Veja Também

* Classe [String](../../../system/string/)
* Classe [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)