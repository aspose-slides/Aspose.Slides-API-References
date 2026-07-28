---
title: BindingFlags
second_title: Odwołanie API Aspose.Slides dla C++
description: Definiuje tryby wyszukiwania członków i typów oraz powiązania.
type: docs
weight: 157
url: /pl/system.reflection/bindingflags/
---
## BindingFlags enum

Definiuje tryby wyszukiwania członków i typów oraz powiązania.

```cpp
enum class BindingFlags
```

### Wartości

| Nazwa | Wartość | Opis |
| --- | --- | --- |
| Default | 0 | Brak specjalnych opcji. |
| IgnoreCase | 1 | Ignoruje wielkość liter nazwy podczas wyszukiwania elementu. |
| DeclaredOnly | 2 | Wyszukuje tylko członków zadeklarowanych w typie, a nie w typach bazowych. |
| Instance | 4 | Przegląda członków instancji. |
| Static | 8 | Przegląda członków statycznych. |
| Public | 16 | Przegląda członków publicznych. |
| NonPublic | 32 | Przegląda członków niepublicznych. |
| FlattenHierarchy | 64 | Przegląda publiczne i chronione statyczne członki typu bazowego. |
| InvokeMethod | 256 | Wywołuje metodę. |
| CreateInstance | 512 | Tworzy instancję odzwierciedlonego typu. |
| GetField | 1024 | Pobiera wartość pola. |
| SetField | 2048 | Ustawia wartość pola. |
| GetProperty | 4096 | Pobiera wartość właściwości. |
| SetProperty | 8192 | Ustawia wartość właściwości. |
| PutDispProperty | 16384 | Ustawia właściwość COM. |
| PutRefDispProperty | 32768 | Ustawia właściwość referencyjną COM. |
| ExactBinding | 65536 | Powiązanie typu musi być dokładne, bez żadnych zmian typu. |
| SuppressChangeType | 131072 | Nieobsługiwane. |
| OptionalParamBinding | 262144 | Wybiera przeciążenie na podstawie liczby argumentów. |
| IgnoreReturn | 16777216 | Ignoruje wartość zwracana przez interakcję COM. |

## Zobacz także

* Przestrzeń nazw [System::Reflection](../)
* Biblioteka [Aspose.Slides](../../)