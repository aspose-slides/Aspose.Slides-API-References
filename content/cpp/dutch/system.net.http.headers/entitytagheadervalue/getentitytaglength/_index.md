---
title: GetEntityTagLength()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert een meegegeven tekenreeks vanaf de opgegeven index naar een instantie van de EntityTagHeaderValue klasse.
type: docs
weight: 118
url: /nl/system.net.http.headers/entitytagheadervalue/getentitytaglength/
---
## EntityTagHeaderValue::GetEntityTagLength(String, int32_t, System::SharedPtr\<EntityTagHeaderValue\>\&) method

Converteert een meegegeven tekenreeks vanaf de opgegeven index naar een instantie van de [EntityTagHeaderValue](../) klasse.

```cpp
static int32_t System::Net::Http::Headers::EntityTagHeaderValue::GetEntityTagLength(String input, int32_t startIndex, System::SharedPtr<EntityTagHeaderValue> &parsedValue)
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | Een tekenreeks om te parseren. |
| startIndex | **int32_t** | Een beginpositie voor het parseren. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[EntityTagHeaderValue](../)\>\& | Een instantie waarin een ontleed object wordt toegewezen. |

### Retourwaarde

De lengte van een ontlede subtekenreeks, anders 0.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [EntityTagHeaderValue](../)
* Naamruimte [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)