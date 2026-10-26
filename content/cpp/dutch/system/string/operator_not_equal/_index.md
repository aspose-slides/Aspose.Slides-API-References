---
title: operator!=()
second_title: Aspose.Slides voor C++ API-referentie
description: Niet-gelijkheidsoperator.
type: docs
weight: 313
url: /nl/system/string/operator_not_equal/
---
## String::operator!=(const String&) const methode


Niet-gelijkheidsoperator.

```cpp
bool System::String::operator!=(const String &str) const
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) om te vergelijken met de huidige. |

### Returnwaarde

false als beide strings null zijn of beide niet null zijn en overeenkomen, true anders.

## String::operator!=(std::nullptr_t) const methode


Controleert of de string niet null is. Past dezelfde logica toe als de [IsNull()](../isnull/)-aanroep.

```cpp
bool System::String::operator!=(std::nullptr_t) const
```


### Returnwaarde

false als de string null is, true anders.

## Zie ook

* Klasse [String](../)
* Namespace [System](../../)
* Bibliotheek [Aspose.Slides](../../../)