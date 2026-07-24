---
title: GetProductLength()
second_title: Aspose.Slides für C++ API Referenz
description: Konvertiert einen übergebenen String ab dem angegebenen Index in eine Instanz der ProductHeaderValue Klasse.
type: docs
weight: 105
url: /de/system.net.http.headers/productheadervalue/getproductlength/
---
## ProductHeaderValue::GetProductLength(String, int32_t, System::SharedPtr\<ProductHeaderValue\>\&) Methode

Konvertiert einen übergebenen String ab dem angegebenen Index in eine Instanz der [ProductHeaderValue](../) Klasse.

```cpp
static int32_t System::Net::Http::Headers::ProductHeaderValue::GetProductLength(String input, int32_t startIndex, System::SharedPtr<ProductHeaderValue> &parsedValue)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | [String](../../../system/string/) | Ein zu parsender String. |
| startIndex | **int32_t** | Eine Startposition zum Parsen. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[ProductHeaderValue](../)\>\& | Eine Instanz, in der ein geparstes Objekt zugewiesen wird. |

### Rückgabewert

Gibt die Länge eines geparsten Teilstrings zurück, sonst 0.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [ProductHeaderValue](../)
* Namensraum [System::Net::Http::Headers](../../)
* Bibliothek [Aspose.Slides](../../../)