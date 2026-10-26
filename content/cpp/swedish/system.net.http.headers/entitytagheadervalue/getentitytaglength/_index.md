---
title: GetEntityTagLength()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar en given sträng från det angivna indexet till en instans av klassen EntityTagHeaderValue.
type: docs
weight: 118
url: /sv/system.net.http.headers/entitytagheadervalue/getentitytaglength/
---
## EntityTagHeaderValue::GetEntityTagLength(String, int32_t, System::SharedPtr\<EntityTagHeaderValue\>\&) metod

Konverterar en given sträng från det angivna indexet till en instans av klassen [EntityTagHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::EntityTagHeaderValue::GetEntityTagLength(String input, int32_t startIndex, System::SharedPtr<EntityTagHeaderValue> &parsedValue)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | [String](../../../system/string/) | En sträng att analysera. |
| startIndex | **int32_t** | En startposition för parsning. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[EntityTagHeaderValue](../)\>\& | En instans där ett parserat objekt kommer att tilldelas. |

### Returvärde

Längden på en parserad delsträng, annars 0.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [String](../../../system/string/)
* Klass [EntityTagHeaderValue](../)
* Namnrymd [System::Net::Http::Headers](../../)
* Bibliotek [Aspose.Slides](../../../)