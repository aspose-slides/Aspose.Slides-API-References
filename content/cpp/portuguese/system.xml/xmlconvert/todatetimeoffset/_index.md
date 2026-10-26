---
title: ToDateTimeOffset()
second_title: Referência da API Aspose.Slides para C++
description: Converte a String fornecida para um equivalente DateTimeOffset.
type: docs
weight: 430
url: /pt/system.xml/xmlconvert/todatetimeoffset/
---
## XmlConvert::ToDateTimeOffset(const String\&) método


Converte o [String](../../../system/string/) fornecido para um equivalente [DateTimeOffset](../../../system/datetimeoffset/).

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | A string a ser convertida. A string deve estar em conformidade com um subconjunto da Recomendação W3C para o tipo XML dateTime. Para mais informações, veja a seção [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) da especificação XML [Schema](../../../system.xml.schema/). |

### Valor de retorno

O equivalente [DateTimeOffset](../../../system/datetimeoffset/) da string fornecida.

## XmlConvert::ToDateTimeOffset(const String\&, const String\&) método


Converte o [String](../../../system/string/) fornecido para um equivalente [DateTimeOffset](../../../system/datetimeoffset/).

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const String &format)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | A string a ser convertida. |
| format | const [String](../../../system/string/)\& | O formato a partir do qual **s** é convertido. O parâmetro de formato pode ser qualquer subconjunto da Recomendação W3C para o tipo XML dateTime. Para mais informações, veja a seção [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) da especificação XML [Schema](../../../system.xml.schema/). A string **s** é validada contra este formato. |

### Valor de retorno

O equivalente [DateTimeOffset](../../../system/datetimeoffset/) da string fornecida.

## XmlConvert::ToDateTimeOffset(const String\&, const ArrayPtr\<String\>\&) método


Converte o [String](../../../system/string/) fornecido para um equivalente [DateTimeOffset](../../../system/datetimeoffset/).

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const ArrayPtr<String> &formats)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | A string a ser convertida. |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | Um array de formatos a partir dos quais **s** pode ser convertido. Cada formato em **formats** pode ser qualquer subconjunto da Recomendação W3C para o tipo XML dateTime. Para mais informações, veja a seção [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) da especificação XML [Schema](../../../system.xml.schema/). A string **s** é validada contra um desses formatos. |

### Valor de retorno

O equivalente [DateTimeOffset](../../../system/datetimeoffset/) da string fornecida.

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [DateTimeOffset](../../../system/datetimeoffset/)
* Classe [String](../../../system/string/)
* Classe [XmlConvert](../)
* Espaço de nomes [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)