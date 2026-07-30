---
title: ToDateTimeOffset()
second_title: Aspose.Slides per C++ Riferimento API
description: Converte la String fornita in un equivalente DateTimeOffset.
type: docs
weight: 430
url: /it/system.xml/xmlconvert/todatetimeoffset/
---
## XmlConvert::ToDateTimeOffset(const String\&) metodo

Converte il [String](../../../system/string/) fornito in un equivalente [DateTimeOffset](../../../system/datetimeoffset/).

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | La stringa da convertire. La stringa deve conformarsi a un sottoinsieme della Raccomandazione W3C per il tipo XML dateTime. Per ulteriori informazioni, vedere la sezione [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) della specifica XML [Schema](../../../system.xml.schema/). |

### Valore restituito

L'equivalente [DateTimeOffset](../../../system/datetimeoffset/) della stringa fornita.

## XmlConvert::ToDateTimeOffset(const String\&, const String\&) metodo

Converte il [String](../../../system/string/) fornito in un equivalente [DateTimeOffset](../../../system/datetimeoffset/).

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const String &format)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | La stringa da convertire. |
| format | const [String](../../../system/string/)\& | Il formato da cui **s** viene convertito. Il parametro format può essere qualsiasi sottoinsieme della Raccomandazione W3C per il tipo XML dateTime. Per ulteriori informazioni, vedere la sezione [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) della specifica XML [Schema](../../../system.xml.schema/). La stringa **s** è validata rispetto a questo formato. |

### Valore restituito

L'equivalente [DateTimeOffset](../../../system/datetimeoffset/) della stringa fornita.

## XmlConvert::ToDateTimeOffset(const String\&, const ArrayPtr\<String\>\&) metodo

Converte il [String](../../../system/string/) fornito in un equivalente [DateTimeOffset](../../../system/datetimeoffset/).

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const ArrayPtr<String> &formats)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | La stringa da convertire. |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | Un array di formati da cui **s** può essere convertito. Ogni formato in **formats** può essere qualsiasi sottoinsieme della Raccomandazione W3C per il tipo XML dateTime. Per ulteriori informazioni, vedere la sezione [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) della specifica XML [Schema](../../../system.xml.schema/). La stringa **s** è validata rispetto a uno di questi formati. |

### Valore restituito

L'equivalente [DateTimeOffset](../../../system/datetimeoffset/) della stringa fornita.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [DateTimeOffset](../../../system/datetimeoffset/)
* Classe [String](../../../system/string/)
* Classe [XmlConvert](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)