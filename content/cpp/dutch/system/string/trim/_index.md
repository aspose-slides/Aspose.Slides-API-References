---
title: Trim()
second_title: Aspose.Slides voor C++ API-referentie
description: Verwijdert alle witruimtetekens van zowel het begin als het einde van de string.
type: docs
weight: 677
url: /nl/system/string/trim/
---
## String::Trim() const methode

Verwijdert alle witruimtetekens aan het begin en het einde van de string.

```cpp
String System::String::Trim() const
```

### Retourwaarde

[String](../) met geen witruimtes aan het begin of einde.

## String::Trim(char_t) const methode

Verwijdert alle voorkomens van het opgegeven teken aan het begin en het einde van de string.

```cpp
String System::String::Trim(char_t ch) const
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| ch | char_t | Symbool om te verwijderen. |

### Retourwaarde

Verwijderingsresultaat.

## String::Trim(const String\&) const methode

Verwijdert alle voorkomens van de opgegeven tekens aan het begin en het einde van de string.

```cpp
String System::String::Trim(const String &anyOf) const
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) van tekens om te verwijderen. |

### Retourwaarde

[String](../) zonder verwijderde tekens.

## String::Trim(const ArrayPtr\<char_t\>\&) const methode

Verwijdert alle voorkomens van de opgegeven tekens aan het begin en het einde van de string.

```cpp
String System::String::Trim(const ArrayPtr<char_t> &anyOf) const
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) van tekens om te verwijderen. |

### Retourwaarde

[String](../) zonder verwijderde tekens.

## Zie ook

* Typedef [ArrayPtr](../../arrayptr/)
* Klasse [String](../)
* Namespace [System](../../)
* Bibliotheek [Aspose.Slides](../../../)