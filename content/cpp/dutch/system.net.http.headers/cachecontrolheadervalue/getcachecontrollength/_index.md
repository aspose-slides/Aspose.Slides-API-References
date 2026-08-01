---
title: GetCacheControlLength()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert een meegeleverde tekenreeks vanaf de opgegeven index naar een instantie van de CacheControlHeaderValue klasse.
type: docs
weight: 456
url: /nl/system.net.http.headers/cachecontrolheadervalue/getcachecontrollength/
---
## CacheControlHeaderValue::GetCacheControlLength(String, int32_t, System::SharedPtr\<CacheControlHeaderValue\>, System::SharedPtr\<CacheControlHeaderValue\>\&) method

Converteert een meegeleverde tekenreeks vanaf de opgegeven index naar een instantie van de [CacheControlHeaderValue](../) klasse.

```cpp
static int32_t System::Net::Http::Headers::CacheControlHeaderValue::GetCacheControlLength(String input, int32_t startIndex, System::SharedPtr<CacheControlHeaderValue> storeValue, System::SharedPtr<CacheControlHeaderValue> &parsedValue)
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | Een tekenreeks om te parseren. |
| startIndex | **int32_t** | Een startpositie voor het parseren. |
| storeValue | [System::SharedPtr](../../../system/sharedptr/)\<[CacheControlHeaderValue](../)\> | Een waarde die moet worden toegevoegd aan het geparseerde object. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[CacheControlHeaderValue](../)\>\& | Een instantie waaraan een geparseerd object zal worden toegewezen. |

### Retourwaarde

The length of a parsed substring, otherwise 0.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [CacheControlHeaderValue](../)
* Naamruimte [System::Net::Http::Headers](../../)
* Bibliotheek [Aspose.Slides](../../../)