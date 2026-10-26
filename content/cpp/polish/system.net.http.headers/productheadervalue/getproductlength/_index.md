---
title: GetProductLength()
second_title: Aspose.Slides dla C++ – referencja API
description: Konwertuje przekazany ciąg znaków od określonego indeksu na instancję klasy ProductHeaderValue.
type: docs
weight: 105
url: /pl/system.net.http.headers/productheadervalue/getproductlength/
---
## ProductHeaderValue::GetProductLength(String, int32_t, System::SharedPtr\<ProductHeaderValue\>\&) metoda

Konwertuje przekazany ciąg znaków od określonego indeksu na instancję klasy [ProductHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::ProductHeaderValue::GetProductLength(String input, int32_t startIndex, System::SharedPtr<ProductHeaderValue> &parsedValue)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | [String](../../../system/string/) | Ciąg znaków do parsowania. |
| startIndex | **int32_t** | Pozycja początkowa do parsowania. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[ProductHeaderValue](../)\>\& | Instancja, do której zostanie przypisany sparsowany obiekt. |

### Wartość zwracana

Zwraca długość sparsowanego podciągu, w przeciwnym razie 0.

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [String](../../../system/string/)
* Klasa [ProductHeaderValue](../)
* Przestrzeń nazw [System::Net::Http::Headers](../../)
* Biblioteka [Aspose.Slides](../../../)