---
title: CastEnumerableTo()
second_title: Aspose.Slides för C++ API-referens
description: Utför en explicit castning av element i det specificerade enumerable-objektet till en annan typ.
type: docs
weight: 2965
url: /sv/system/castenumerableto/
---
## System::CastEnumerableTo(const From&) funktion

Utför en explicit castning av element i det angivna enumerable-objektet till en annan typ.

```cpp
template<class To,class From> std::enable_if<!System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| To | Typen att statiskt casta elementen i enumerable-objektet till |
| From | Typen av enumerable-objekt |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| enumerable | const From\& | Enumerable-objekt som innehåller elementen att casta |

### Returvärde

En pekare till en ny samling som innehåller element av typen **To** som motsvarar elementen i **enumerable**

## System::CastEnumerableTo(const From&) funktion

Utför en explicit castning av element i det angivna enumerable-objektet till en annan typ.

```cpp
template<class To,class From> std::enable_if<System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| To | Typen att statiskt casta elementen i enumerable-objektet till |
| From | Typen av enumerable-objekt |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| enumerable | const From\& | är en ärvare av Enumerable-objekt med definierad get_Count-metod och innehåller elementen att casta |

### Returvärde

En pekare till en ny samling som innehåller element av typen **To** som motsvarar elementen i **enumerable**

## Se även

* Klass [ListPtr](../../system.collections.generic/listptr/)
* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)