---
title: Index
second_title: Aspose.Slides för C++ API-referens
description: "Representerar ett index i en samling. Indexet kan vara från början eller från slutet. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller som referens. Använd aldrig System::SmartPtr-klass för att hantera objekt av denna typ."
type: docs
weight: 1015
url: /sv/system/index/
---
## Index klass


Representerar ett index i en samling. Indexet kan vara från början eller från slutet. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller som referens. Använd aldrig [System::SmartPtr](../smartptr/) klass för att hantera objekt av denna typ.

```cpp
class Index : public System::Details::BoxableObjectBase
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| **bool** [Equals](./equals/)(const [Index](./)\&) const | Bestämmer om den aktuella instansen och den specificerade [Index](./) representerar samma position. |
| static constexpr [Index](./) [FromEnd](./fromend/)(**int32_t**) | Skapar ett [Index](./) som är relativt slutet av samlingen. |
| static constexpr [Index](./) [get_End](./get_end/)() | Hämtar ett [Index](./) objekt som representerar slutet av en samling. |
| constexpr **bool** [get_IsFromEnd](./get_isfromend/)() const | Hämtar ett värde som anger om indexet kommer från slutet. |
| static constexpr [Index](./) [get_Start](./get_start/)() | Hämtar ett [Index](./) objekt som representerar början av en samling. |
| constexpr **int32_t** [get_Value](./get_value/)() const | Hämtar indexvärdet. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Returnerar en hashkod för det aktuella indexet. |
| **int32_t** [GetOffset](./getoffset/)(**int32_t**) const | Konverterar den aktuella [Index](./) till ett avstånd från början av en samling med den angivna längden. |
| constexpr [Index](./index/)() | Skapar en instans som representerar början av en samling. |
| constexpr [Index](./index/)(**int32_t**) | Skapar en instans som representerar den specificerade positionen från början av en samling. |
| constexpr [Index](./index/)(**int32_t**, **bool**) | Skapar en instans som representerar det specificerade indexet. |
## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)