---
title: ValidateWhitespace()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Sprawdza, czy białe znaki w podanym ciągu znaków są dozwolone w bieżącym kontekście elementu i gromadzi białe znaki do walidacji, jeśli bieżący element ma prostą zawartość.
type: docs
weight: 196
url: /pl/system.xml.schema/xmlschemavalidator/validatewhitespace/
---
## XmlSchemaValidator::ValidateWhitespace(const String\&) metoda

Sprawdza, czy białe znaki w podanym **string** są dozwolone w bieżącym kontekście elementu i gromadzi białe znaki do walidacji, jeśli bieżący element ma prostą zawartość.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateWhitespace(const String &elementValue)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| elementValue | const [String](../../../system/string/)\& | Ciąg białych znaków **string** do walidacji w bieżącym kontekście elementu. |

## XmlSchemaValidator::ValidateWhitespace(XmlValueGetter) metoda

Sprawdza, czy białe znaki zwrócone przez określony obiekt XmlValueGetter są dozwolone w bieżącym kontekście elementu i gromadzi białe znaki do walidacji, jeśli bieżący element ma prostą zawartość.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateWhitespace(XmlValueGetter elementValue)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| elementValue | [XmlValueGetter](../../xmlvaluegetter/) | Wywołanie zwrotne XmlValueGetter używane do przekazania wartości białych znaków jako typu zgodnego z typem XML [Schema](../../) Definition Language (XSD) atrybutu. |

## Zobacz także

* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Klasa [String](../../../system/string/)
* Klasa [XmlSchemaValidator](../)
* Przestrzeń nazw [System::Xml::Schema](../../)
* Biblioteka [Aspose.Slides](../../../)