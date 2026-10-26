---
title: ToDateTime()
second_title: Aspose.Slides per C++ Riferimento API
description: Converte la String in un equivalente DateTime.
type: docs
weight: 417
url: /it/system.xml/xmlconvert/todatetime/
---
## XmlConvert::ToDateTime(const String\&) metodo

Converte il [String](../../../system/string/) in un equivalente [DateTime](../../../system/datetime/).

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | La stringa da convertire. |

### Valore di ritorno

Un equivalente [DateTime](../../../system/datetime/) della stringa.

## XmlConvert::ToDateTime(const String\&, const String\&) metodo

Converte il [String](../../../system/string/) in un equivalente [DateTime](../../../system/datetime/).

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const String &format)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | La stringa da convertire. |
| format | const [String](../../../system/string/)\& | La struttura di formato da applicare al [DateTime](../../../system/datetime/) convertito. I formati validi includono "yyyy-MM-ddTHH:mm:sszzzzzz" e le sue sotto-stringhe. La stringa è convalidata rispetto a questo formato. |

### Valore di ritorno

Un equivalente [DateTime](../../../system/datetime/) della stringa.

## XmlConvert::ToDateTime(const String\&, const ArrayPtr\<String\>\&) metodo

Converte il [String](../../../system/string/) in un equivalente [DateTime](../../../system/datetime/).

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const ArrayPtr<String> &formats)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | La stringa da convertire. |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | Un array contenente le strutture di formato da applicare al [DateTime](../../../system/datetime/) convertito. I formati validi includono "yyyy-MM-ddTHH:mm:sszzzzzz" e le sue sotto-stringhe. |

### Valore di ritorno

Un equivalente [DateTime](../../../system/datetime/) della stringa.

## XmlConvert::ToDateTime(const String\&, XmlDateTimeSerializationMode) metodo

Converte il [String](../../../system/string/) in un [DateTime](../../../system/datetime/) usando lo XmlDateTimeSerializationMode specificato.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, XmlDateTimeSerializationMode dateTimeOption)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Il valore [String](../../../system/string/) da convertire. |
| dateTimeOption | [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/) | Uno dei valori dell'enumerazione che specifica se la data deve essere convertita in ora locale o mantenuta come Coordinated Universal Time (UTC), se è una data UTC. |

### Valore di ritorno

Un equivalente [DateTime](../../../system/datetime/) del [String](../../../system/string/).

## Vedi anche

* Enum [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [DateTime](../../../system/datetime/)
* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)