---
title: Range
second_title: Aspose.Slides för C++ API-referens
description: "Representerar ett intervall med ett start- och slutindex. Denna typ bör allokeras på stacken och skickas till funktioner per värde eller per referens. Använd aldrig System::SmartPtr-klassen för att hantera objekt av denna typ."
type: docs
weight: 1197
url: /sv/system/range/
---
## Range klass

Representerar ett intervall med ett start- och slutindex. Denna typ bör allokeras på stacken och skickas till funktioner per värde eller per referens. Använd aldrig [System::SmartPtr](../smartptr/) klass för att hantera objekt av denna typ.

```cpp
class Range : public System::Details::BoxableObjectBase
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static constexpr [Range](./) [EndAt](./endat/)(const [Index](../index/)\&) | Skapar ett intervall som börjar vid början av samlingen och slutar vid det angivna slutindexet. |
| **bool** [Equals](./equals/)(const [Range](./)\&) const | Bestämmer om det aktuella intervallet är lika med det angivna intervallet. |
| static constexpr [Range](./) [get_All](./get_all/)() | Returnerar en [Range](./) som representerar hela samlingen. |
| const [Index](../index/)\& [get_End](./get_end/)() const | Hämtar slutindexet. |
| const [Index](../index/)\& [get_Start](./get_start/)() const | Hämtar startindexet. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Returnerar en hashkod för det aktuella intervallet. |
| [System::ValueTuple](../valuetuple/)\<**int32_t**, **int32_t**\> [GetOffsetAndLength](./getoffsetandlength/)(**int32_t**) const | Beräknar den nollbaserade startoffseten och längden för den angivna samlingslängden. |
| constexpr [Range](./range/)() | Skapar ett tomt intervall. |
| constexpr [Range](./range/)(const [Index](../index/)\&, const [Index](../index/)\&) | Skapar en [Range](./) från de angivna start- och slutindexen. |
| static constexpr [Range](./) [StartAt](./startat/)(const [Index](../index/)\&) | Skapar ett intervall som börjar vid det angivna startindexet och sträcker sig till slutet av samlingen. |

## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)