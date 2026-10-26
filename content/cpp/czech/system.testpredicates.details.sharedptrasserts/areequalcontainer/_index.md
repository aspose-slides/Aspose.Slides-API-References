---
title: AreEqualContainer()
second_title: Aspose.Slides pro C++ API Reference
description: Porovnává dva kontejnery pomocí operátoru == na prvcích. Funguje pro prvky, které nejsou SmartPtr.
type: docs
weight: 1
url: /cs/system.testpredicates.details.sharedptrasserts/areequalcontainer/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1\&, const T2\&) funkce

Porovnává dva kontejnery pomocí operator == na prvcích. Funguje pro prvky, které nejsou SmartPtr.

```cpp
template<typename T1,typename T2> std::enable_if<!System::IsSmartPtr<typenameT1::value_type>::value &&!System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Typ kontejneru LHS. |
| T2 | Typ kontejneru RHS. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs | const T1\& | LHS kontejner. |
| rhs | const T2\& | RHS kontejner. |

### Návratová hodnota

True, pokud se shodují obsažené prvky a velikosti, false jinak.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1\&, const T2\&) funkce

Porovnává dva kontejnery pomocí [System::Object::Equals](../../system/object/equals/) na prvcích. Funguje pro [SmartPtr](../../system/smartptr/) prvky.

```cpp
template<typename T1,typename T2> std::enable_if<System::IsSmartPtr<typenameT1::value_type>::value &&System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Typ kontejneru LHS. |
| T2 | Typ kontejneru RHS. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs | const T1\& | Reference na LHS kontejner. |
| rhs | const T2\& | Reference na RHS kontejner. |

### Návratová hodnota

True, pokud se shodují obsažené prvky a velikosti, false jinak.

## Viz také

* Struct [IsSmartPtr](../../system/issmartptr/)
* Jmenný prostor [System::TestPredicates::Details::SharedPtrAsserts](../)
* Knihovna [Aspose.Slides](../../)