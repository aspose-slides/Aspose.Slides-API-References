---
title: GetCacheControlLength()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar en given sträng från den angivna indexen till en instans av klassen CacheControlHeaderValue.
type: docs
weight: 456
url: /sv/system.net.http.headers/cachecontrolheadervalue/getcachecontrollength/
---
## CacheControlHeaderValue::GetCacheControlLength(String, int32_t, System::SharedPtr\<CacheControlHeaderValue\>, System::SharedPtr\<CacheControlHeaderValue\>\&) metod

Konverterar en given sträng från den angivna indexen till en instans av [CacheControlHeaderValue](../) klass.

```cpp
static int32_t System::Net::Http::Headers::CacheControlHeaderValue::GetCacheControlLength(String input, int32_t startIndex, System::SharedPtr<CacheControlHeaderValue> storeValue, System::SharedPtr<CacheControlHeaderValue> &parsedValue)
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | En sträng att tolka. |
| startIndex | **int32_t** | En startposition för parsning. |
| storeValue | [System::SharedPtr](../../../system/sharedptr/)\<[CacheControlHeaderValue](../)\> | Ett värde som måste läggas till det parserade objektet. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[CacheControlHeaderValue](../)\>\& | En instans där ett parserat objekt kommer att tilldelas. |

### Returvärde

Längden på en parserad delsträng, annars 0.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [String](../../../system/string/)
* Klass [CacheControlHeaderValue](../)
* Namnrymd [System::Net::Http::Headers](../../)
* Bibliotek [Aspose.Slides](../../../)