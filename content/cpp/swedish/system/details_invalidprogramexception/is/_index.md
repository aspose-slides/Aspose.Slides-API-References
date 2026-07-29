---
title: Is()
second_title: Aspose.Slides för C++ API-referens
description: 
type: docs
weight: 27
url: /sv/system/details_invalidprogramexception/is/
---
## Detaljer_InvalidProgramException::Is(const System::TypeInfo\&) const metod




```cpp
bool System::Details_InvalidProgramException::Is(const System::TypeInfo &target) const override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) struktur som beskriver typen som det aktuella objektet ska testas mot. |

### Returvärde

Sant om objektet är av den taggade typen eller dess underklass, falskt annars.

## Anmärkningar

Kontrollera om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'.

## Se också

* Klass [TypeInfo](../../typeinfo/)
* Klass [Details_InvalidProgramException](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)