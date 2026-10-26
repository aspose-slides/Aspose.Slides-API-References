---
title: GetEntityTagLength()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert eine übergebene Zeichenkette ab dem angegebenen Index in eine Instanz der EntityTagHeaderValue Klasse.
type: docs
weight: 118
url: /de/system.net.http.headers/entitytagheadervalue/getentitytaglength/
---
## EntityTagHeaderValue::GetEntityTagLength(String, int32_t, System::SharedPtr\<EntityTagHeaderValue\>\&) Methode

Konvertiert eine übergebene Zeichenkette ab dem angegebenen Index in eine Instanz der [EntityTagHeaderValue](../) Klasse.

```cpp
static int32_t System::Net::Http::Headers::EntityTagHeaderValue::GetEntityTagLength(String input, int32_t startIndex, System::SharedPtr<EntityTagHeaderValue> &parsedValue)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | [String](../../../system/string/) | Eine zu parsende Zeichenkette. |
| startIndex | **int32_t** | Eine Startposition für das Parsen. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[EntityTagHeaderValue](../)\>\& | Eine Instanz, in der ein geparstes Objekt zugewiesen wird. |

### Rückgabewert

Die Länge eines geparsten Teilstrings, sonst 0.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [EntityTagHeaderValue](../)
* Namensraum [System::Net::Http::Headers](../../)
* Bibliothek [Aspose.Slides](../../../)