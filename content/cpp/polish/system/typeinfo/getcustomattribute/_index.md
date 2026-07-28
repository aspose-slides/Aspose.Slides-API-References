---
title: GetCustomAttribute()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Wyszukuje niestandardowy atrybut o określonym typie, zastosowany do typu reprezentowanego przez bieżący obiekt.
type: docs
weight: 573
url: /pl/system/typeinfo/getcustomattribute/
---
## TypeInfo::GetCustomAttribute(const TypeInfo\&) const metoda

Wyszukuje niestandardowy atrybut o podanym typie, zastosowany do typu reprezentowanego przez bieżący obiekt.

```cpp
ObjectPtr System::TypeInfo::GetCustomAttribute(const TypeInfo &attributeType) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | Stałe odwołanie do obiektu [TypeInfo](../) reprezentującego typ atrybutu, który ma zostać wyszukany |

### Wartość zwracana

Wskaźnik do obiektu reprezentującego znaleziony atrybut, lub null-pointer jeśli nie znaleziono atrybutu spełniającego kryteria wyszukiwania

## Zobacz także

* Klasa [SmartPtr](../../smartptr/)
* Klasa [TypeInfo](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)