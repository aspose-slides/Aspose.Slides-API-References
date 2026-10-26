---
title: Is()
second_title: Aspose.Slides för C++ API-referens
description: 
type: docs
weight: 27
url: /sv/system/details_notsupportedexception/is/
---
## Details_NotSupportedException::Is(const System::TypeInfo\&) const method

```cpp
bool System::Details_NotSupportedException::Is(const System::TypeInfo &target) const override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) struktur som beskriver typen för att testa det aktuella objektet mot. |

### Returvärde

Sant om objektet är av den märkta typen eller en underklass, annars falskt.

## Anmärkningar

Kontrollera om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'.

## Se också

* Class [TypeInfo](../../typeinfo/)
* Class [Details_NotSupportedException](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)