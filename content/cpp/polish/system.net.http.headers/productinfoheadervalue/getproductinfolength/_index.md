---
title: GetProductInfoLength()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Konwertuje podany ciąg znaków od określonego indeksu na instancję klasy ProductInfoHeaderValue.
type: docs
weight: 105
url: /pl/system.net.http.headers/productinfoheadervalue/getproductinfolength/
---
## ProductInfoHeaderValue::GetProductInfoLength(String, int32_t, System::SharedPtr\<ProductInfoHeaderValue\>\&) metoda

Konwertuje podany ciąg znaków od określonego indeksu na instancję klasy [ProductInfoHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::ProductInfoHeaderValue::GetProductInfoLength(String input, int32_t startIndex, System::SharedPtr<ProductInfoHeaderValue> &parsedValue)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | [String](../../../system/string/) | Ciąg znaków do przetworzenia. |
| startIndex | **int32_t** | Pozycja początkowa dla parsowania. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[ProductInfoHeaderValue](../)\>\& | Instancja, do której zostanie przypisany sparsowany obiekt. |

### Wartość zwracana

Zwraca długość sparsowanego podciągu, w przeciwnym razie 0.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [String](../../../system/string/)
* Klasa [ProductInfoHeaderValue](../)
* Przestrzeń nazw [System::Net::Http::Headers](../../)
* Biblioteka [Aspose.Slides](../../../)