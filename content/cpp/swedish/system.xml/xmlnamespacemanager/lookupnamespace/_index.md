---
title: LookupNamespace()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar namnrymdens URI för det angivna prefixet.
type: docs
weight: 118
url: /sv/system.xml/xmlnamespacemanager/lookupnamespace/
---
## XmlNamespaceManager::LookupNamespace(const String\&) metod


Returnerar namnrymdens URI för det angivna prefixet.

```cpp
String System::Xml::XmlNamespaceManager::LookupNamespace(const String &prefix) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Prefixet vars namnrymds-URI du vill lösa. För att matcha standardnamnrymden, skicka [String::Empty](../../../system/string/empty/). |

### Returvärde

Namnrymdens URI för **prefix** eller **nullptr** om det inte finns någon mappad namnrymd. Den returnerade strängen är atomiserad. För mer information om atomiserade strängar, se klassen [XmlNameTable](../../xmlnametable/).

## Se också

* Klass [String](../../../system/string/)
* Klass [XmlNamespaceManager](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)