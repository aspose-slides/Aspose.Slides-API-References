---
title: GetAttribute()
second_title: Referência da API Aspose.Slides para C++
description: Retorna o valor do atributo com o nome especificado.
type: docs
weight: 495
url: /pt/system.xml/xmltextreader/getattribute/
---
## XmlTextReader::GetAttribute(String) método

Retorna o valor do atributo com o nome especificado.

```cpp
String System::Xml::XmlTextReader::GetAttribute(String name) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | O nome qualificado do atributo. |

### Valor de Retorno

O valor do atributo especificado. Se o atributo não for encontrado, **nullptr** é retornado.

## XmlTextReader::GetAttribute(String, String) método

Retorna o valor do atributo com o nome local e o URI de namespace especificados.

```cpp
String System::Xml::XmlTextReader::GetAttribute(String localName, String namespaceURI) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| localName | [String](../../../system/string/) | O nome local do atributo. |
| namespaceURI | [String](../../../system/string/) | O URI de namespace do atributo. |

### Valor de Retorno

O valor do atributo especificado. Se o atributo não for encontrado, **nullptr** é retornado. Este método não avança o leitor.

## XmlTextReader::GetAttribute(int32_t) método

Retorna o valor do atributo com o índice especificado.

```cpp
String System::Xml::XmlTextReader::GetAttribute(int32_t i) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| i | **int32_t** | O índice do atributo. O índice é baseado em zero. (O primeiro atributo tem índice 0.) |

### Valor de Retorno

O valor do atributo especificado.

## Veja também

* Classe [String](../../../system/string/)
* Classe [XmlTextReader](../)
* Espaço de nomes [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)