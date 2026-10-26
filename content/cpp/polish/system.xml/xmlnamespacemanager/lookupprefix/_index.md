---
title: LookupPrefix()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Znajduje prefiks zadeklarowany dla podanego identyfikatora URI przestrzeni nazw.
type: docs
weight: 131
url: /pl/system.xml/xmlnamespacemanager/lookupprefix/
---
## XmlNamespaceManager::LookupPrefix(const String\&) metoda

Znajduje prefiks zadeklarowany dla podanego identyfikatora URI przestrzeni nazw.

```cpp
String System::Xml::XmlNamespaceManager::LookupPrefix(const String &uri) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | Przestrzeń nazw do rozstrzygnięcia prefiksu. |

### Wartość zwracana

Odpowiadający prefiks. Jeśli nie ma przypisanego prefiksu, metoda zwraca [String::Empty](../../../system/string/empty/). Jeśli podana zostanie wartość null, zwracany jest **nullptr**.

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlNamespaceManager](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)