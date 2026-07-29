---
title: SmartPtrInfo
second_title: Aspose.Slides för C++ API-referens
description: "Serviceklass för att testa och ändra SmartPtr:s innehåll utan att känna till den slutliga typen. Används för skräpsamling och upptäckt av loopreferenser, med mera. Tänk på det som en 'pekare till pekare'. Vi kan inte använda SmartPtr:s basistyp eftersom den inte har någon; istället använder vi den här 'info'-klassen."
type: docs
weight: 1249
url: /sv/system/smartptrinfo/
---
## SmartPtrInfo klass

Serviceklass för att testa och ändra [SmartPtr](../smartptr/)'s innehåll utan att känna till den slutliga typen. Används för skräpsamling och upptäckt av loopreferenser, med mera. Tänk på det som en 'pekare till pekare'. Vi kan inte använda [SmartPtr](../smartptr/)'s basistyp eftersom den inte har någon; istället använder vi denna 'info'-klass.

```cpp
class SmartPtrInfo
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| const void * [getInternalPtr](./getinternalptr/)() const | Hämtar det råa objekt som den refererade pekaren pekar på. |
| [Object](../object/) * [getObject](./getobject/)() const | Hämtar objektet som den refererade pekaren pekar på. |
| [Object](../object/) * [getOwned](./getowned/)() const | Hämtar den ägda objektpekaren. |
|  [operator bool](./operator_bool/)() const | Kontrollerar om infoobjektet pekar på en icke-null pekare. |
| **bool** [operator!](./operator_not/)() const | Kontrollerar om infoobjektet inte pekar på en icke-null pekare. |
| [Object](../object/) * [operator->](./operator_minus_greater/)() const | Tillåter att anropa metoder för [Object](../object/) som den refererade pekaren pekar på. |
| **bool** [operator<](./operator_less/)(const [SmartPtrInfo](./)\&) const | Jämför mindre värden för pekarna som refereras av två infoobjekt. |
|  [SmartPtrInfo](./smartptrinfo/)() | Skapar ett tomt [SmartPtrInfo](./)-objekt. |
| explicit  [SmartPtrInfo](./smartptrinfo/)(const [SmartPtr](../smartptr/)\<T\>\&) | Skapar ett [SmartPtrInfo](./)-objekt med information om en specifik smartpekare. |

## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)