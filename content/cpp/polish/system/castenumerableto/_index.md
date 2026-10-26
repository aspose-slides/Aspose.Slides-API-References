---
title: CastEnumerableTo()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Wykonuje jawne rzutowanie elementów określonego obiektu enumerable na inny typ.
type: docs
weight: 2965
url: /pl/system/castenumerableto/
---
## System::CastEnumerableTo(const From\&) funkcja

Wykonuje jawne rzutowanie elementów określonego obiektu enumerable na inny typ.

```cpp
template<class To,class From> std::enable_if<!System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| To | Typ, na który statycznie rzutowane są elementy obiektu enumerable |
| From | Typ obiektu enumerable |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| enumerable | const From\& | Obiekt enumerable zawierający elementy do rzutowania |

### Wartość zwracana

Wskaźnik do nowej kolekcji zawierającej elementy typu **To** równoważne elementom **enumerable**

## System::CastEnumerableTo(const From\&) funkcja

Wykonuje jawne rzutowanie elementów określonego obiektu enumerable na inny typ.

```cpp
template<class To,class From> std::enable_if<System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| To | Typ, na który statycznie rzutowane są elementy obiektu enumerable |
| From | Typ obiektu enumerable |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| enumerable | const From\& | Jest dziedzicielem obiektu Enumerable posiadającego zdefiniowaną metodę get_Count i zawierającego elementy do rzutowania |

### Wartość zwracana

Wskaźnik do nowej kolekcji zawierającej elementy typu **To** równoważne elementom **enumerable**

## Zobacz także

* Klasa [ListPtr](../../system.collections.generic/listptr/)
* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)