---
title: AreEqualData()
second_title: Aspose.Slides pro C++ API Reference
description: "Porovnává dva kontejnery pomocí System::Object::Equals na prvcích. Funguje pro prvky typu SmartPtr."
type: docs
weight: 14
url: /cs/system.testpredicates.details.sharedptrasserts/areequaldata/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1\&, const T2\&) function

Porovnává dva kontejnery pomocí [System::Object::Equals](../../system/object/equals/) na prvcích. Funguje pro [SmartPtr](../../system/smartptr/) prvky.

```cpp
template<typename T1,typename T2> std::enable_if<System::IsSmartPtr<typenameT1::value_type>::value &&System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1 &lhs, const T2 &rhs)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Typ kontejneru LHS. |
| T2 | Typ kontejneru RHS. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs | const T1\& | Odkaz na kontejner LHS. |
| rhs | const T2\& | Odkaz na kontejner RHS. |

### Návratová hodnota

Pravda, pokud se shodují obsažené prvky a velikosti, jinak nepravda.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1\&, const T2\&) function

Porovnává dva kontejnery pomocí operátoru == na prvcích. Funguje pro prvky, které nejsou SmartPtr.

```cpp
template<typename T1,typename T2> std::enable_if<!System::IsSmartPtr<typenameT1::value_type>::value &&!System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1 &lhs, const T2 &rhs)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Typ kontejneru LHS. |
| T2 | Typ kontejneru RHS. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs | const T1\& | Kontejner LHS. |
| rhs | const T2\& | Kontejner RHS. |

### Návratová hodnota

Pravda, pokud se shodují obsažené prvky a velikosti, jinak nepravda.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T\&, const T\&) function

Porovnává dva kontejnery stejného typu. Funguje pro prvky, které nejsou SmartPtr.

```cpp
template<typename T> std::enable_if<!System::IsSmartPtr<typenameT::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T &lhs, const T &rhs)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Typ kontejneru LHS. |
| T2 | Typ kontejneru RHS. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs | const T\& | Kontejner LHS. |
| rhs | const T\& | Kontejner RHS. |

### Návratová hodnota

Pravda, pokud se shodují obsažené prvky a velikosti, jinak nepravda.

## Viz také

* Struktura [IsSmartPtr](../../system/issmartptr/)
* Jmenný prostor [System::TestPredicates::Details::SharedPtrAsserts](../)
* Knihovna [Aspose.Slides](../../)