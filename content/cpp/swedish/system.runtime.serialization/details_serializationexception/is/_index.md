---
title: Is()
second_title: Aspose.Slides för C++ API-referens
description: 
type: docs
weight: 27
url: /sv/system.runtime.serialization/details_serializationexception/is/
---
## Details_SerializationException::Is(const System::TypeInfo\&) const method




```cpp
bool System::Runtime::Serialization::Details_SerializationException::Is(const System::TypeInfo &target) const override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) struktur som beskriver typen som ska testas mot det aktuella objektet. |

### Returvärde

Sant om objektet är av den markerade typen eller dess underklass, falskt annars.
## Anmärkningar


Kontrollera om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'.
## Se även

* Klass [TypeInfo](../../../system/typeinfo/)
* Klass [Details_SerializationException](../)
* Namnrymd [System::Runtime::Serialization](../../)
* Bibliotek [Aspose.Slides](../../../)