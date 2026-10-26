---
title: GetRangeItemLength()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert einen übergebenen String vom angegebenen Index in eine Instanz der Klasse RangeItemHeaderValue.
type: docs
weight: 92
url: /de/system.net.http.headers/rangeitemheadervalue/getrangeitemlength/
---
## RangeItemHeaderValue::GetRangeItemLength(String, int32_t, System::SharedPtr\<RangeItemHeaderValue\>\&) Methode

Konvertiert einen übergebenen String vom angegebenen Index in eine Instanz der [RangeItemHeaderValue](../) Klasse.

```cpp
static int32_t System::Net::Http::Headers::RangeItemHeaderValue::GetRangeItemLength(String input, int32_t startIndex, System::SharedPtr<RangeItemHeaderValue> &parsedValue)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | [String](../../../system/string/) | Ein String zum Parsen. |
| startIndex | **int32_t** | Eine Startposition zum Parsen. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[RangeItemHeaderValue](../)\>\& | Eine Instanz, in der das geparste Objekt zugewiesen wird. |

### Rückgabewert

Gibt die Länge eines geparsten Teilstrings zurück, andernfalls 0.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [RangeItemHeaderValue](../)
* Namensraum [System::Net::Http::Headers](../../)
* Bibliothek [Aspose.Slides](../../../)