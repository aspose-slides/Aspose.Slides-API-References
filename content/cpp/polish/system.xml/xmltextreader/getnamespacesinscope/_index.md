---
title: GetNamespacesInScope()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Zwraca kolekcję zawierającą wszystkie aktualnie obowiązujące przestrzenie nazw.
type: docs
weight: 716
url: /pl/system.xml/xmltextreader/getnamespacesinscope/
---
## XmlTextReader::GetNamespacesInScope(XmlNamespaceScope) metoda

Zwraca kolekcję zawierającą wszystkie aktualnie obowiązujące przestrzenie nazw.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlTextReader::GetNamespacesInScope(XmlNamespaceScope scope) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | Wartość XmlNamespaceScope określająca typ węzłów przestrzeni nazw, które mają zostać zwrócone. |

### Wartość zwracana

Obiekt IDictionary zawierający wszystkie aktualne przestrzenie nazw w zasięgu. Jeśli czytnik nie jest ustawiony na elemencie, zwracany jest pusty słownik (bez przestrzeni nazw).

## Zobacz także

* Wyliczenie [XmlNamespaceScope](../../xmlnamespacescope/)
* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IDictionary](../../../system.collections.generic/idictionary/)
* Klasa [String](../../../system/string/)
* Klasa [XmlTextReader](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)