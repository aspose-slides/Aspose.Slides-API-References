---
title: Is()
second_title: Aspose.Slides för C++ API-referens
description: 
type: docs
weight: 27
url: /sv/system.security/details_securityexception/is/
---
## Details_SecurityException::Is(const System::TypeInfo\&) const method




```cpp
bool System::Security::Details_SecurityException::Is(const System::TypeInfo &target) const override
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) struktur som beskriver typen som det aktuella objektet ska testas mot. |

### Returvärde

Sant om objektet är av den markerade typen eller dess underklass, falskt annars.
## Anmärkningar


Kontrollera om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C# 'is'-operatorn. 
## Se även

* Class [TypeInfo](../../../system/typeinfo/)
* Class [Details_SecurityException](../)
* Namespace [System::Security](../../)
* Library [Aspose.Slides](../../../)