---
title: GetProductLength()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Převede předaný řetězec z určeného indexu na instanci třídy ProductHeaderValue.
type: docs
weight: 105
url: /cs/system.net.http.headers/productheadervalue/getproductlength/
---
## ProductHeaderValue::GetProductLength(String, int32_t, System::SharedPtr\<ProductHeaderValue\>\&) metoda

Převádí předaný řetězec z určeného indexu na instanci třídy [ProductHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::ProductHeaderValue::GetProductLength(String input, int32_t startIndex, System::SharedPtr<ProductHeaderValue> &parsedValue)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | [String](../../../system/string/) | Řetězec k analýze. |
| startIndex | **int32_t** | Počáteční pozice pro parsování. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[ProductHeaderValue](../)\>\& | Instance, do které bude přiřazen analyzovaný objekt. |

## Vrácená hodnota

Vrací délku analyzovaného podřetězce, jinak 0.

## Viz také

* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [String](../../../system/string/)
* Třída [ProductHeaderValue](../)
* Jmenný prostor [System::Net::Http::Headers](../../)
* Knihovna [Aspose.Slides](../../../)