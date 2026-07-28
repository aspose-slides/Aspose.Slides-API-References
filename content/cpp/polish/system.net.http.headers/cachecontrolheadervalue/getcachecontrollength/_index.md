---
title: GetCacheControlLength()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Konwertuje przekazany ciąg znaków od podanego indeksu na instancję klasy CacheControlHeaderValue.
type: docs
weight: 456
url: /pl/system.net.http.headers/cachecontrolheadervalue/getcachecontrollength/
---
## CacheControlHeaderValue::GetCacheControlLength(String, int32_t, System::SharedPtr\<CacheControlHeaderValue\>, System::SharedPtr\<CacheControlHeaderValue\>\&) metoda


Konwertuje przekazany ciąg znaków od określonego indeksu na instancję klasy [CacheControlHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::CacheControlHeaderValue::GetCacheControlLength(String input, int32_t startIndex, System::SharedPtr<CacheControlHeaderValue> storeValue, System::SharedPtr<CacheControlHeaderValue> &parsedValue)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | [String](../../../system/string/) | Ciąg znaków do przetworzenia. |
| startIndex | **int32_t** | Pozycja początkowa do przetwarzania. |
| storeValue | [System::SharedPtr](../../../system/sharedptr/)\<[CacheControlHeaderValue](../)\> | Wartość, która musi zostać dodana do przetworzonego obiektu. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[CacheControlHeaderValue](../)\>\& | Instancja, do której zostanie przypisany przetworzony obiekt. |

### Wartość zwracana

Długość przetworzonego podciągu, w przeciwnym razie 0.

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [String](../../../system/string/)
* Klasa [CacheControlHeaderValue](../)
* Przestrzeń nazw [System::Net::Http::Headers](../../)
* Biblioteka [Aspose.Slides](../../../)