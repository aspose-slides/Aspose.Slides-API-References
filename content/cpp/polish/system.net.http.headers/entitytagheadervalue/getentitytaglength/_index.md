---
title: GetEntityTagLength()
second_title: Aspose.Slides dla C++ – referencja API
description: Konwertuje przekazany ciąg znaków od określonego indeksu na instancję klasy EntityTagHeaderValue.
type: docs
weight: 118
url: /pl/system.net.http.headers/entitytagheadervalue/getentitytaglength/
---
## EntityTagHeaderValue::GetEntityTagLength(String, int32_t, System::SharedPtr\<EntityTagHeaderValue\>\&) metoda


Konwertuje przekazany ciąg znaków od określonego indeksu na instancję klasy [EntityTagHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::EntityTagHeaderValue::GetEntityTagLength(String input, int32_t startIndex, System::SharedPtr<EntityTagHeaderValue> &parsedValue)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | [String](../../../system/string/) | Ciąg znaków do analizowania. |
| startIndex | **int32_t** | Pozycja początkowa do analizowania. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[EntityTagHeaderValue](../)\>\& | Instancja, do której zostanie przypisany przetworzony obiekt. |

### Wartość zwracana

Długość przetworzonego podciągu, w przeciwnym razie 0.

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [String](../../../system/string/)
* Klasa [EntityTagHeaderValue](../)
* Przestrzeń nazw [System::Net::Http::Headers](../../)
* Biblioteka [Aspose.Slides](../../../)