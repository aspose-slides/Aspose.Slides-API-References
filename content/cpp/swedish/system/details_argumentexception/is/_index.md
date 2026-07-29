---
title: Is()
second_title: Aspose.Slides för C++ API-referens
description: 
type: docs
weight: 27
url: /sv/system/details_argumentexception/is/
---
## Detaljer_ArgumentException::Is(const System::TypeInfo\&) const method




```cpp
bool System::Details_ArgumentException::Is(const System::TypeInfo &target) const override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) struktur som beskriver typen för att testa det aktuella objektet mot. |

### Returvärde

Sant om objektet är av den markerade typen eller en underklass till den, falskt annars.
## Anmärkningar


Kontrollera om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'.
## Se även

* Klass [TypeInfo](../../typeinfo/)
* Klass [Details_ArgumentException](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)