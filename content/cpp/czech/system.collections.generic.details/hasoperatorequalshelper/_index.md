---
title: HasOperatorEqualsHelper()
second_title: Aspose.Slides pro C++ API referenci
description: Pomocná funkce pro určení, zda konkrétní třída má operátor ==.
type: docs
weight: 235
url: /cs/system.collections.generic.details/hasoperatorequalshelper/
---
## System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *) funkce

Pomocná funkce pro určení, zda konkrétní třída má operátor ==.

```cpp
template<class T,typename Dummy> std::true_type System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ, který se má zkontrolovat. |
| Dummy | Dummy argument pro SFINAE magii. |

### Návratová hodnota

Hodnota std::true_type, pokud je operátor == přítomen, a false jinak.

## System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *) funkce

Pomocná funkce pro určení, zda konkrétní třída má operátor ==.

```cpp
std::false_type System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *)
```

### Návratová hodnota

Hodnota std::true_type, pokud je operátor == přítomen, a false jinak.

## Viz také

* Jmenný prostor [System::Collections::Generic::Details](../)
* Knihovna [Aspose.Slides](../../)