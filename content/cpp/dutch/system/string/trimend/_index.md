---
title: TrimEnd()
second_title: Aspose.Slides voor C++ API-referentie
description: Verwijdert alle witruimtetekens van het einde van de string.
type: docs
weight: 703
url: /nl/system/string/trimend/
---
## String::TrimEnd() const methode


Verwijdert alle witruimtetekens van het einde van de string.

```cpp
String System::String::TrimEnd() const
```


### Retourwaarde

[String](../) zonder witruimtes aan het begin.

## String::TrimEnd(char_t) const methode


Verwijdert alle voorkomens van het meegegeven teken van het einde van de string.

```cpp
String System::String::TrimEnd(char_t ch) const
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| ch | char_t | Symbool om te verwijderen. |

### Retourwaarde

Verwijderingsresultaat.

## String::TrimEnd(const String\&) const methode


Verwijdert alle voorkomens van de meegegeven tekens van het einde van de string.

```cpp
String System::String::TrimEnd(const String &anyOf) const
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) van tekens om te verwijderen. |

### Retourwaarde

[String](../) zonder verwijderde tekens.

## String::TrimEnd(const ArrayPtr\<char_t\>\&) const methode


Verwijdert alle voorkomens van de meegegeven tekens van het einde van de string.

```cpp
String System::String::TrimEnd(const ArrayPtr<char_t> &anyOf) const
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) van tekens om te verwijderen. |

### Retourwaarde

[String](../) zonder verwijderde tekens.

## Zie ook

* Typedef [ArrayPtr](../../arrayptr/)
* Klasse [String](../)
* Namespace [System](../../)
* Bibliotheek [Aspose.Slides](../../../)