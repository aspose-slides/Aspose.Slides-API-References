---
title: ValidateText()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Sprawdza, czy podany ciąg tekstowy jest dozwolony w bieżącym kontekście elementu i gromadzi tekst do weryfikacji, jeśli bieżący element ma prostą zawartość.
type: docs
weight: 183
url: /pl/system.xml.schema/xmlschemavalidator/validatetext/
---
## XmlSchemaValidator::ValidateText(const String\&) metoda


Sprawdza, czy podany **string** tekst jest dozwolony w bieżącym kontekście elementu i gromadzi tekst do weryfikacji, jeśli bieżący element ma prostą zawartość.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(const String &elementValue)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| elementValue | const [String](../../../system/string/)\& | Tekst **string** do zweryfikowania w bieżącym kontekście elementu. |

## XmlSchemaValidator::ValidateText(XmlValueGetter) metoda


Sprawdza, czy tekst zwrócony przez określony obiekt XmlValueGetter jest dozwolony w bieżącym kontekście elementu i gromadzi tekst do weryfikacji, jeśli bieżący element ma prostą zawartość.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(XmlValueGetter elementValue)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| elementValue | [XmlValueGetter](../../xmlvaluegetter/) | Wywołanie zwrotne XmlValueGetter używane do przekazania wartości tekstowej jako typu zgodnego z typem języka definicji XML [Schema](../../) (XSD) atrybutu. |

## Zobacz także

* Definicja typu [XmlValueGetter](../../xmlvaluegetter/)
* Klasa [String](../../../system/string/)
* Klasa [XmlSchemaValidator](../)
* Przestrzeń nazw [System::Xml::Schema](../../)
* Biblioteka [Aspose.Slides](../../../)