---
title: BindingFlags
second_title: Aspose.Slides pro C++ API Reference
description: Definuje režimy vyhledávání členů a typů a vazby.
type: docs
weight: 157
url: /cs/system.reflection/bindingflags/
---
## BindingFlags výčtový typ

Definuje režimy vyhledávání členů a typů a vazby.

```cpp
enum class BindingFlags
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| Default | 0 | Žádné speciální volby. |
| IgnoreCase | 1 | Ignoruje velikost písmen názvu při hledání položky. |
| DeclaredOnly | 2 | Vyhledá pouze členy deklarované v typu a ne v základních typech. |
| Instance | 4 | Prochází instance členy. |
| Static | 8 | Prochází statické členy. |
| Public | 16 | Prochází veřejné členy. |
| NonPublic | 32 | Prochází neveřejné členy. |
| FlattenHierarchy | 64 | Prochází veřejné a chráněné statické členy základního typu. |
| InvokeMethod | 256 | Volá metodu. |
| CreateInstance | 512 | Vytváří instanci reflektovaného typu. |
| GetField | 1024 | Získá hodnotu pole. |
| SetField | 2048 | Nastaví hodnotu pole. |
| GetProperty | 4096 | Získá hodnotu vlastnosti. |
| SetProperty | 8192 | Nastaví hodnotu vlastnosti. |
| PutDispProperty | 16384 | Nastaví COM vlastnost. |
| PutRefDispProperty | 32768 | Nastaví referenční COM vlastnost. |
| ExactBinding | 65536 | Vazba typu musí být přesná, bez jakýchkoli změn typu. |
| SuppressChangeType | 131072 | Není podporováno. |
| OptionalParamBinding | 262144 | Vybere přetížení na základě počtu argumentů. |
| IgnoreReturn | 16777216 | Ignoruje návratovou hodnotu COM interop. |

## Viz také

* Jmenný prostor [System::Reflection](../)
* Knihovna [Aspose.Slides](../../)