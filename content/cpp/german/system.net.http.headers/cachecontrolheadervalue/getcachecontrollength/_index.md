---
title: GetCacheControlLength()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert einen übergebenen String vom angegebenen Index in eine Instanz der CacheControlHeaderValue-Klasse.
type: docs
weight: 456
url: /de/system.net.http.headers/cachecontrolheadervalue/getcachecontrollength/
---
## CacheControlHeaderValue::GetCacheControlLength(String, int32_t, System::SharedPtr\<CacheControlHeaderValue\>, System::SharedPtr\<CacheControlHeaderValue\>\&) Methode

Konvertiert einen übergebenen String vom angegebenen Index in eine Instanz der [CacheControlHeaderValue](../) Klasse.

```cpp
static int32_t System::Net::Http::Headers::CacheControlHeaderValue::GetCacheControlLength(String input, int32_t startIndex, System::SharedPtr<CacheControlHeaderValue> storeValue, System::SharedPtr<CacheControlHeaderValue> &parsedValue)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | [String](../../../system/string/) | Ein zu parsierender String. |
| startIndex | **int32_t** | Eine Startposition für das Parsen. |
| storeValue | [System::SharedPtr](../../../system/sharedptr/)\<[CacheControlHeaderValue](../)\> | Ein Wert, der dem geparsten Objekt hinzugefügt werden muss. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[CacheControlHeaderValue](../)\>\& | Eine Instanz, in die ein geparstes Objekt zugewiesen wird. |

### Rückgabewert

Die Länge eines geparsten Teilstrings, sonst 0.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [CacheControlHeaderValue](../)
* Namensraum [System::Net::Http::Headers](../../)
* Bibliothek [Aspose.Slides](../../../)