---
title: CharacterRange
second_title: Aspose.Slides för C++ API-referens
description: "Representerar ett intervall av teckenpositioner i en sträng. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig System::SmartPtr klass för att hantera objekt av denna typ."
type: docs
weight: 40
url: /sv/system.drawing/characterrange/
---
## CharacterRange klass


Representerar ett intervall av teckenpositioner i en sträng. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig [System::SmartPtr](../../system/smartptr/) klass för att hantera objekt av denna typ.

```cpp
class CharacterRange
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  [CharacterRange](./characterrange/)(**int32_t**, **int32_t**) | Skapar en ny instans av [CharacterRange](./) klass som representerar det specificerade intervallet. |
|  [CharacterRange](./characterrange/)() | Skapar en ny instans av [CharacterRange](./) klass som representerar ett tomt intervall. |
| **int32_t** [get_First](./get_first/)() const | Returnerar positionen för det första tecknet i intervallet som representeras av det aktuella objektet. |
| **int32_t** [get_Length](./get_length/)() const | Returnerar antalet tecken i intervallet som representeras av det aktuella objektet. |
| **bool** [operator!=](./operator_not_equal/)(const [CharacterRange](./)\&) const | Avgör om det aktuella och specificerade objektet representerar olika intervall. |
| **bool** [operator==](./operator_equal_equal/)(const [CharacterRange](./)\&) const | Avgör om det aktuella och specificerade objektet representerar samma intervall. |
| void [set_First](./set_first/)(**int32_t**) | Ställer in positionen för det första tecknet i intervallet som representeras av det aktuella objektet. |
| void [set_Length](./set_length/)(**int32_t**) | Returnerar antalet tecken i intervallet som representeras av det aktuella objektet. |
## Se också

* Namnrymd [System::Drawing](../)
* Bibliotek [Aspose.Slides](../../)