---
title: TypeInfoPtr
second_title: Aspose.Slides för C++ API-referens
description: "Omslag för en pekare till en instans av TypeInfo-klassen. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig System::SmartPtr-klassen för att hantera objekt av denna typ."
type: docs
weight: 1951
url: /sv/system/typeinfoptr/
---
## TypeInfoPtr struct

Omslag för en pekare till en instans av [TypeInfo](../typeinfo/)-klassen. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig [System::SmartPtr](../smartptr/)-klassen för att hantera objekt av denna typ.

```cpp
class TypeInfoPtr
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  [operator TypeInfo *](./operator_typeinfo__star/)() | Returnerar en råpekare till det representerade [TypeInfo](../typeinfo/)-objektet. |
|  [TypeInfoPtr](./typeinfoptr/)() | Standardkonstruktör. |
|  [TypeInfoPtr](./typeinfoptr/)(const std::type_info\&) | Konstruktor. |
|  [TypeInfoPtr](./typeinfoptr/)(const char_t *, **uint32_t**) | Konstruktor. |
|  [TypeInfoPtr](./typeinfoptr/)(const char_t *) | Konstruktor. |
|  [TypeInfoPtr](./typeinfoptr/)(const [String](../string/)\&) | Konstruktor. |
|  [~TypeInfoPtr](./~typeinfoptr/)() | Destruktor. |
## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)