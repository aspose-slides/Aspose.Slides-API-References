---
title: AreEqualData()
second_title: Aspose.Slides dla C++ API Reference
description: "Porównuje dwa kontenery przy użyciu System::Object::Equals na elementach. Działa dla elementów SmartPtr."
type: docs
weight: 14
url: /pl/system.testpredicates.details.sharedptrasserts/areequaldata/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1&, const T2&) funkcja

Porównuje dwa kontenery przy użyciu [System::Object::Equals](../../system/object/equals/) na elementach. Działa dla [SmartPtr](../../system/smartptr/) elementów.

```cpp
template<typename T1,typename T2> std::enable_if<System::IsSmartPtr<typenameT1::value_type>::value &&System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1 &lhs, const T2 &rhs)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | Typ kontenera LHS. |
| T2 | Typ kontenera RHS. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| lhs | const T1& | Referencja do kontenera LHS. |
| rhs | const T2& | Referencja do kontenera RHS. |

### Wartość zwracana

Prawda, jeśli elementy i rozmiary się zgadzają, w przeciwnym razie fałsz.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1&, const T2&) funkcja

Porównuje dwa kontenery przy użyciu operatora == na elementach. Działa dla elementów nie będących SmartPtr.

```cpp
template<typename T1,typename T2> std::enable_if<!System::IsSmartPtr<typenameT1::value_type>::value &&!System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1 &lhs, const T2 &rhs)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | Typ kontenera LHS. |
| T2 | Typ kontenera RHS. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| lhs | const T1& | Kontener LHS. |
| rhs | const T2& | Kontener RHS. |

### Wartość zwracana

Prawda, jeśli elementy i rozmiary się zgadzają, w przeciwnym razie fałsz.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T&, const T&) funkcja

Porównuje dwa kontenery tego samego typu. Działa dla elementów nie będących SmartPtr.

```cpp
template<typename T> std::enable_if<!System::IsSmartPtr<typenameT::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T &lhs, const T &rhs)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | Typ kontenera LHS. |
| T2 | Typ kontenera RHS. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| lhs | const T& | Kontener LHS. |
| rhs | const T& | Kontener RHS. |

### Wartość zwracana

Prawda, jeśli elementy i rozmiary się zgadzają, w przeciwnym razie fałsz.

## Zobacz także

* Struktura [IsSmartPtr](../../system/issmartptr/)
* Przestrzeń nazw [System::TestPredicates::Details::SharedPtrAsserts](../)
* Biblioteka [Aspose.Slides](../../)