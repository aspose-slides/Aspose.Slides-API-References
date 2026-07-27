---
title: GetAttribute()
second_title: Referência da API Aspose.Slides para C++
description: Retorna o valor do atributo com o nome especificado.
type: docs
weight: 443
url: /pt/system.xml/xmlvalidatingreader/getattribute/
---
## XmlValidatingReader::GetAttribute(String) método

Retorna o valor do atributo com o nome especificado.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String name) override
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | O nome qualificado do atributo. |

### Valor de Retorno

O valor do atributo especificado. Se o atributo não for encontrado, **nullptr** é retornado.

## XmlValidatingReader::GetAttribute(String, String) método

Retorna o valor do atributo com o nome local e o identificador uniforme de recurso (URI) do namespace especificados.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String localName, String namespaceURI) override
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | O nome local do atributo. |
| namespaceURI | [String](../../../system/string/) | O URI do namespace do atributo. |

### Valor de Retorno

O valor do atributo especificado. Se o atributo não for encontrado, **nullptr** é retornado. Este método não move o leitor.

## XmlValidatingReader::GetAttribute(int32_t) método

Retorna o valor do atributo com o índice especificado.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(int32_t i) override
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| i | **int32_t** | O índice do atributo. O índice começa em zero. (O primeiro atributo tem índice 0.) |

### Valor de Retorno

O valor do atributo especificado.

## Veja Também

* Classe [String](../../../system/string/)
* Classe [XmlValidatingReader](../)
* Espaço de nomes [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)