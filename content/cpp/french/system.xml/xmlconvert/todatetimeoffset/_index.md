---
title: ToDateTimeOffset()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit la chaîne fournie en un équivalent DateTimeOffset.
type: docs
weight: 430
url: /fr/system.xml/xmlconvert/todatetimeoffset/
---
## XmlConvert::ToDateTimeOffset(const String\&) méthode

Convertit le [String](../../../system/string/) fourni en un équivalent [DateTimeOffset](../../../system/datetimeoffset/).

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | La chaîne à convertir. La chaîne doit respecter un sous-ensemble de la recommandation W3C pour le type XML dateTime. Pour plus d'informations, voir la section [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) de la spécification XML [Schema](../../../system.xml.schema/). |

### Valeur de retour

L'équivalent [DateTimeOffset](../../../system/datetimeoffset/) de la chaîne fournie.

## XmlConvert::ToDateTimeOffset(const String\&, const String\&) méthode

Convertit le [String](../../../system/string/) fourni en un équivalent [DateTimeOffset](../../../system/datetimeoffset/).

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const String &format)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | La chaîne à convertir. |
| format | const [String](../../../system/string/)\& | Le format à partir duquel **s** est converti. Le paramètre format peut être n'importe quel sous-ensemble de la recommandation W3C pour le type XML dateTime. Pour plus d'informations, voir la section [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) de la spécification XML [Schema](../../../system.xml.schema/). La chaîne **s** est validée par rapport à ce format. |

### Valeur de retour

L'équivalent [DateTimeOffset](../../../system/datetimeoffset/) de la chaîne fournie.

## XmlConvert::ToDateTimeOffset(const String\&, const ArrayPtr\<String\>\&) méthode

Convertit le [String](../../../system/string/) fourni en un équivalent [DateTimeOffset](../../../system/datetimeoffset/).

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const ArrayPtr<String> &formats)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | La chaîne à convertir. |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | Un tableau de formats à partir desquels **s** peut être converti. Chaque format dans **formats** peut être n'importe quel sous-ensemble de la recommandation W3C pour le type XML dateTime. Pour plus d'informations, voir la section [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) de la spécification XML [Schema](../../../system.xml.schema/). La chaîne **s** est validée par rapport à l'un de ces formats. |

### Valeur de retour

L'équivalent [DateTimeOffset](../../../system/datetimeoffset/) de la chaîne fournie.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [DateTimeOffset](../../../system/datetimeoffset/)
* Classe [String](../../../system/string/)
* Classe [XmlConvert](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)