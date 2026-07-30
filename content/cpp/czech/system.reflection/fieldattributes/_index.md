---
title: FieldAttributes
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Reflektované atributy pole.
type: docs
weight: 170
url: /cs/system.reflection/fieldattributes/
---
## FieldAttributes enum

Reflektované atributy pole.

```cpp
enum class FieldAttributes
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| FieldAccessMask | 7 | Maska přístupu k členům. Použijte tuto masku k získání informací o přístupnosti. |
| PrivateScope | 0 | Členové, které nelze referencovat. |
| Private | 1 | Soukromí členové. |
| FamANDAssem | 2 | Soukromí členové s dosahem sestavení. |
| Assembly | 3 | Členové s rozsahem sestavení. |
| Family | 4 | Členové přístupní typem i podtypy. |
| FamORAssem | 5 | Členové přístupní typem, podtypy a sestavením. |
| Public | 6 | Členové přístupní komukoli. |
| Static | 16 | Statické členy na rozdíl od instančních členů. |
| InitOnly | 32 | Konstantní členy, které lze pouze inicializovat, ale neměnit. |
| Literal | 64 | Členy konstantní při kompilaci. |
| NotSerialized | 128 | Neserializované členy. |
| SpecialName | 512 | Speciální pole jednoho z níže uvedených názvů. |
| PinvokeImpl | 8192 | Implementace přeposlaná interoperabilitou. |
| ReservedMask | 38144 | Rezervované příznaky pouze pro použití v době běhu. |
| RTSpecialName | 1024 | Runtime by měl zkontrolovat kódování názvu. |
| HasFieldMarshal | 4096 | Informace o marshalingu jsou přítomny. |
| HasDefault | 32768 | Výchozí hodnota je přítomna. |
| HasFieldRVA | 256 | RVA je přítomno. |

## Viz také

* Jmenný prostor [System::Reflection](../)
* Knihovna [Aspose.Slides](../../)