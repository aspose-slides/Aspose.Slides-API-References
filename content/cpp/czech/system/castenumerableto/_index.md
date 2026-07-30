---
title: CastEnumerableTo()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Provádí explicitní přetypování prvků zadaného objektu typu enumerable na jiný typ.
type: docs
weight: 2965
url: /cs/system/castenumerableto/
---
## System::CastEnumerableTo(const From\&) funkce


Provádí explicitní přetypování prvků zadaného objektu typu enumerable na jiný typ.

```cpp
template<class To,class From> std::enable_if<!System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| To | Typ, na který se mají staticky přetypovat prvky objektu enumerable |
| From | Typ objektu enumerable |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| enumerable | const From\& | Objekt enumerable obsahující prvky k přetypování |

### Návratová hodnota

Ukazatel na novou kolekci obsahující prvky typu **To**, ekvivalentní prvkům **enumerable**

## System::CastEnumerableTo(const From\&) funkce


Provádí explicitní přetypování prvků zadaného objektu typu enumerable na jiný typ.

```cpp
template<class To,class From> std::enable_if<System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| To | Typ, na který se mají staticky přetypovat prvky objektu enumerable |
| From | Typ objektu enumerable |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| enumerable | const From\& | je dědic objektu Enumerable s definovanou metodou get_Count a obsahuje prvky k přetypování |

### Návratová hodnota

Ukazatel na novou kolekci obsahující prvky typu **To**, ekvivalentní prvkům **enumerable**

## Viz také

* Třída [ListPtr](../../system.collections.generic/listptr/)
* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)