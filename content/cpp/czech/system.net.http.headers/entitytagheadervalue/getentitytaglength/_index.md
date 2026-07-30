---
title: GetEntityTagLength()
second_title: Aspose.Slides pro C++ API Reference
description: Převede předaný řetězec od zadaného indexu na instanci třídy EntityTagHeaderValue.
type: docs
weight: 118
url: /cs/system.net.http.headers/entitytagheadervalue/getentitytaglength/
---
## EntityTagHeaderValue::GetEntityTagLength(String, int32_t, System::SharedPtr\<EntityTagHeaderValue\>\&) metoda

Převede předaný řetězec od určeného indexu na instanci třídy [EntityTagHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::EntityTagHeaderValue::GetEntityTagLength(String input, int32_t startIndex, System::SharedPtr<EntityTagHeaderValue> &parsedValue)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | [String](../../../system/string/) | Řetězec k analýze. |
| startIndex | **int32_t** | Počáteční pozice pro analýzu. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[EntityTagHeaderValue](../)\>\& | Instance, do které bude přiřazen analyzovaný objekt. |

### Návratová hodnota

Délka analyzovaného podřetězce, jinak 0.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [String](../../../system/string/)
* Třída [EntityTagHeaderValue](../)
* Jmenný prostor [System::Net::Http::Headers](../../)
* Knihovna [Aspose.Slides](../../../)