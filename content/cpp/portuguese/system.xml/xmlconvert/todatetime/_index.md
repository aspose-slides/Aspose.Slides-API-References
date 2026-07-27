---
title: ToDateTime()
second_title: Referência da API Aspose.Slides para C++
description: Converte a String para um equivalente DateTime.
type: docs
weight: 417
url: /pt/system.xml/xmlconvert/todatetime/
---
## XmlConvert::ToDateTime(const String\&) método


Converte o [String](../../../system/string/) para um equivalente [DateTime](../../../system/datetime/).

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | A string a ser convertida. |

### Valor de Retorno

Um equivalente [DateTime](../../../system/datetime/) da string.

## XmlConvert::ToDateTime(const String\&, const String\&) método


Converte o [String](../../../system/string/) para um equivalente [DateTime](../../../system/datetime/).

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const String &format)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | A string a ser convertida. |
| format | const [String](../../../system/string/)\& | A estrutura de formato a ser aplicada ao [DateTime](../../../system/datetime/) convertido. Formatos válidos incluem "yyyy-MM-ddTHH:mm:sszzzzzz" e seus subconjuntos. A string é validada contra este formato. |

### Valor de Retorno

Um equivalente [DateTime](../../../system/datetime/) da string.

## XmlConvert::ToDateTime(const String\&, const ArrayPtr\<String\>\&) método


Converte o [String](../../../system/string/) para um equivalente [DateTime](../../../system/datetime/).

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const ArrayPtr<String> &formats)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | A string a ser convertida. |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | Um array contendo as estruturas de formato a serem aplicadas ao [DateTime](../../../system/datetime/) convertido. Formatos válidos incluem "yyyy-MM-ddTHH:mm:sszzzzzz" e seus subconjuntos. |

### Valor de Retorno

Um equivalente [DateTime](../../../system/datetime/) da string.

## XmlConvert::ToDateTime(const String\&, XmlDateTimeSerializationMode) método


Converte o [String](../../../system/string/) para um [DateTime](../../../system/datetime/) usando o XmlDateTimeSerializationMode especificado.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, XmlDateTimeSerializationMode dateTimeOption)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | O [String](../../../system/string/) valor a ser convertido. |
| dateTimeOption | [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/) | Um dos valores da enumeração que especificam se a data deve ser convertida para horário local ou preservada como Tempo Universal Coordenado (UTC), se for uma data UTC. |

### Valor de Retorno

Um equivalente [DateTime](../../../system/datetime/) do [String](../../../system/string/).

## Veja Também

* Enum [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [DateTime](../../../system/datetime/)
* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)