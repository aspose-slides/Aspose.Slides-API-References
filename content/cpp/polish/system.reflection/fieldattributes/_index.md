---
title: FieldAttributes
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Odzwzorowane atrybuty pola.
type: docs
weight: 170
url: /pl/system.reflection/fieldattributes/
---
## FieldAttributes enum

Odwzorowane atrybuty pola.

```cpp
enum class FieldAttributes
```

### Values

| Nazwa | Wartość | Opis |
| --- | --- | --- |
| FieldAccessMask | 7 | Maska dostępu członków. Użyj tej maski, aby pobrać informacje o dostępności. |
| PrivateScope | 0 | Członkowie nie referencjonowane. |
| Private | 1 | Prywatni członkowie. |
| FamANDAssem | 2 | Członkowie prywatni i o zasięgu zestawu. |
| Assembly | 3 | Członkowie o zasięgu zestawu. |
| Family | 4 | Członkowie dostępni dla typu i podtypów. |
| FamORAssem | 5 | Członkowie dostępni dla typu, podtypów i zestawu. |
| Public | 6 | Członkowie dostępni dla wszystkich. |
| Static | 16 | Statyczni członkowie w przeciwieństwie do członków instancji. |
| InitOnly | 32 | Stałe członkowie, które mogą być tylko zainicjalizowane, ale nie zmieniane. |
| Literal | 64 | Członkowie będące stałymi czasu kompilacji. |
| NotSerialized | 128 | Członkowie nie serializowane. |
| SpecialName | 512 | Specjalne pole jednego z poniższych nazw. |
| PinvokeImpl | 8192 | Implementacja przekierowana przez interop. |
| ReservedMask | 38144 | Zarezerwowane flagi wyłącznie do użycia w czasie wykonywania. |
| RTSpecialName | 1024 | Środowisko uruchomieniowe powinno sprawdzić kodowanie nazw. |
| HasFieldMarshal | 4096 | Informacje o marshalling są obecne. |
| HasDefault | 32768 | Domyślna wartość jest obecna. |
| HasFieldRVA | 256 | RVA jest obecny. |

## Zobacz także

* Przestrzeń nazw [System::Reflection](../)
* Biblioteka [Aspose.Slides](../../)