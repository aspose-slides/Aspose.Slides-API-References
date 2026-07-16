---
title: ToDateTime()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit le String en un équivalent DateTime.
type: docs
weight: 417
url: /fr/system.xml/xmlconvert/todatetime/
---
## XmlConvert::ToDateTime(const String\&) méthode


Convertit le [String](../../../system/string/) en un équivalent [DateTime](../../../system/datetime/).

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | La chaîne à convertir. |

### Valeur de retour

Un équivalent [DateTime](../../../system/datetime/) de la chaîne.

## XmlConvert::ToDateTime(const String\&, const String\&) méthode


Convertit le [String](../../../system/string/) en un équivalent [DateTime](../../../system/datetime/).

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const String &format)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | La chaîne à convertir. |
| format | const [String](../../../system/string/)\& | La structure de format à appliquer à la [DateTime](../../../system/datetime/) convertie. Les formats valides incluent "yyyy-MM-ddTHH:mm:sszzzzzz" et leurs sous-ensembles. La chaîne est validée par rapport à ce format. |

### Valeur de retour

Un équivalent [DateTime](../../../system/datetime/) de la chaîne.

## XmlConvert::ToDateTime(const String\&, const ArrayPtr\<String\>\&) méthode


Convertit le [String](../../../system/string/) en un équivalent [DateTime](../../../system/datetime/).

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const ArrayPtr<String> &formats)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | La chaîne à convertir. |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | Un tableau contenant les structures de format à appliquer à la [DateTime](../../../system/datetime/) convertie. Les formats valides incluent "yyyy-MM-ddTHH:mm:sszzzzzz" et leurs sous-ensembles. |

### Valeur de retour

Un équivalent [DateTime](../../../system/datetime/) de la chaîne.

## XmlConvert::ToDateTime(const String\&, XmlDateTimeSerializationMode) méthode


Convertit le [String](../../../system/string/) en un [DateTime](../../../system/datetime/) en utilisant le XmlDateTimeSerializationMode spécifié.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, XmlDateTimeSerializationMode dateTimeOption)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | La valeur [String](../../../system/string/) à convertir. |
| dateTimeOption | [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/) | L'une des valeurs d'énumération qui indique si la date doit être convertie en heure locale ou conservée en Temps Universel Coordonné (UTC), si c’est une date UTC. |

### Valeur de retour

Un équivalent [DateTime](../../../system/datetime/) du [String](../../../system/string/).

## Voir aussi

* Enum [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [DateTime](../../../system/datetime/)
* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)